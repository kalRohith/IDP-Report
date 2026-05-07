# AquaTrack: Prototype-Based Multimodal AI for Context-Aware Dehydration Prediction

This repository contains the Interdisciplinary Project (IDP) report for AquaTrack, a prototype-based multimodal system for context-aware dehydration prediction.

## Project Overview

AquaTrack brings together wearable sweat sensing, hydrogel-based biomarker capture, context detection, and machine learning to estimate dehydration risk in real time. The project focuses on creating a practical hydration-monitoring system that combines direct biomarker evidence with the user's environmental and activity context.

## Key Features

- **Hydrogel-based wearable sweat patch** for non-invasive biomarker collection
- **Dual-pipeline machine learning model** that fuses biomarker and context predictions
- **Context-aware processing** for activity intensity, climate class, and sweat availability
- **Mobile health architecture** with FastAPI backend and React Native mobile dashboard

## Report Structure

The report is organized into 6 chapters:

1. **Introduction to AquaTrack** - Overview, literature review, motivation, problem statement, objectives, and methodology
2. **Fundamentals** - Basics of sweat sensing, hydrogels, dehydration biomarkers, and chronic kidney disease relevance
3. **Methodology and Model Design** - Hydrogel synthesis, datasets, target engineering, preprocessing, feature extraction, and model training
4. **System Architecture and Implementation** - System design, context detection, dual-pipeline prediction engine, backend, and mobile deployment
5. **Results** - Experimental observations and machine learning results
6. **Conclusion and Future Scope** - Summary, future work, and learning outcomes

## Compilation

To compile the LaTeX report locally:

1. Install MacTeX (full distribution) from https://www.tug.org/mactex/
2. Navigate to the project directory
3. Run the following commands:

```bash
pdflatex IDP_Report.tex
bibtex IDP_Report
pdflatex IDP_Report.tex
pdflatex IDP_Report.tex
```

Or use an online editor like Overleaf for easier compilation.

## License

This project uses the RVCE LaTeX Project Report Template.
