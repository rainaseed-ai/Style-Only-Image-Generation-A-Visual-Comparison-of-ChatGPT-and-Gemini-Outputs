# Style-Only Image Generation: A Visual Comparison of ChatGPT and Gemini Outputs
## (Observational Dataset)
[![DOI](https://img.shields.io/badge/DOI-10.6084%2Fm9.figshare.34369542-blue)](https://doi.org/10.6084/m9.figshare.34369542)
## Overview
This repository contains an observational dataset comparing how two multimodal language models—**ChatGPT** and **Gemini**—generate images when provided with **STYLE-only prompts.** No content descriptions were given; only visual style templates were specified.
The dataset documents:
- Differences between ChatGPT and Gemini using the same STYLE-only templates
- Effects of new vs. continued conversation threads
- Influence of anchor images on Gemini's output consistency
- Observed content variation under STYLE-only prompting

This dataset is **independent** and is not part of the ES3-LLM supplementary materials.
## Repository Structure

```
/
├── README.md
├── Style-Only_Image_generation.md
├── Style-Only_Image_generation.pdf
images/
├── Anchor_Image_Gemini.png
├── Figure_1_ChatGPT.png
├── ...
├── Figure_6_Gemini.jpg
├── Figure_7_Gemini.png
├── Figure_8_Gemini.jpg
├── Figure_9_Gemini.jpg
└── LICENSE
```
The Markdown and PDF files contain the complete dataset, including Appendices A–D. Generated images are stored once in the images/ directory and referenced from the Markdown document.

## Dataset Contents

### Appendix A — Prompts
**Prompt Source**

The style-only prompt templates used in this dataset were adapted from the style prompts presented in the following Qiita article:

Maeda, Satoshi (@maeda-niku18). *AIっぽくない画像を作る画風プロンプト38種類＋テンプレート*. Qiita, September 7, 2026.

[Qiita article](https://qiita.com/maeda-niku18/items/b633dda178c505461080)

Five STYLE-only templates used in the observations:
1. Natural hand-drawn illustration
2. Hand-drawn manga illustration
3. Contemporary editorial illustration
4. Simple pictographic illustration
5. Risograph-style illustration

### Appendix B — Logs

AI response excerpts corresponding to the observed image-generation conditions.
Gemini continued-thread and anchor-image conditions include cases where **no additional conversation log exists.**

### Appendix C — Generated Images

Generated images for all observed conditions, including the Gemini anchor image used as a visual reference.
The Markdown version references the image files in the images/ directory, while the PDF version contains the images embedded in the document.

### Appendix D — Notes

Supplementary notes concerning:
- Conversational context influence
- Thread-related variation
- Anchor-image effects
- Dataset positioning
- Reproducibility considerations

## Summary of Observations

### ChatGPT

- Produced a recurring character across all five STYLE templates
- Recurring visual features included blue hair, a cat, PC/coding-related elements, and other repeated motifs
- Visual style changed across templates while recurring visual features remained consistent

### Gemini

- New and continued threads produced different observed content
- Without an anchor image, varied scenes were observed without a stable recurring character
- With an anchor image, character reproduction was more consistent
- Continued-thread outputs contained more background and contextual elements than new-thread outputs

## Common Observations

- In the observed conditions, STYLE templates primarily specified visual style while leaving semantic content unspecified
- Observed content varied across models and conversation conditions
- Anchor-image conditions were associated with more consistent character reproduction in the observed Gemini outputs

## Purpose of This Dataset

- Provide an observational record of STYLE-only image generation under documented conditions
- Document observed variation in generated content across models and conversation conditions
- Provide reproducible descriptions of the observed conditions for future comparison

## Positioning

This dataset is an **independent observational dataset.**
A previous case study examined differences in image generation under identical text prompts across models. The present dataset uses **STYLE-only prompting**, where semantic content is intentionally left unspecified.
The two datasets therefore examine different observational conditions and should not be treated as a single experimental series.

## License
See LICENSE for the applicable license terms.
