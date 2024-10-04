---
name: BioImage Analysis
about: Submit a microscopy image for AI-assisted analysis
title: "[Analysis Request]: "
labels: image-analysis
assignees: haesleinhuepf
---

## Bio-Image Analysis Support Request

### Image Upload
📎 **Drag & drop your microscopy image here** (JPG, PNG, GIF, 512x512 or 1024x1024, 2D only).

### Analysis Goal
- What do you want to analyze (e.g., count cells, measure structures, segment regions)?

### Python Tools
- Are you using any specific Python libraries for the analysis? If not, we'll may use:
  - numpy
  - scikit-image
  - stackview
  - pandas
  - seaborn
  - scipy

**Note:** Your images and the text you enter here may be sent to [OpenAI](https://openai.com/)'s online serivce where we use a large language model to answer your request. 
Do not upload any data you cannot share openly. Also do not enter any private or secret information. By submitting this github issue, you confirm that you understand these conditions.

Once submitted, @haesleinhuepf will review and consult [git-bob, an AI-assistant](https://github.com/haesleinhuepf/git-bob) for bio-image analysis suggestions.
