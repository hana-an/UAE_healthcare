# UAE Healthcare Prediction

Code for **Incremental Predictive Value of Routine Biomarkers for Abnormal Glycemic Status in Young Emirati Women**.

Authors: Hanan Hussain, Syama K, and Razia Sulatana.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hana-an/UAE_healthcare/blob/main/UAE_Healthcare_Prediction.ipynb)

## Run in Google Colab

1. Open `UAE_Healthcare_Prediction.ipynb` in Google Colab.
2. Download `S1_File.sav` from the [original dataset](https://doi.org/10.6084/m9.figshare.14547246.v1) (CC BY 4.0).
3. Put the file in `My Drive/UAE Healthcare Prediction - Colab/`, or update `PROJECT` in notebook sections 2 and 10.
4. Select a CPU runtime and run the cells in order. A GPU is not required.

The notebook compares six conventional classifiers and a small MLP, basic and extended predictors, original and cleaned measurements, training-only threshold selection, and biomarker groups. It uses three repetitions of stratified five-fold cross-validation and saves CSV results under the project folder's `runs/` directory. Section 10 can also run independently for the biomarker analysis.

Dependencies are imported in the notebook; `pyreadstat` is installed by its setup cell. Published outputs were generated with fixed seeds 2026, 2027, and 2028. Notebook outputs are cleared for a clean rerun; each run records its results and environment information.

## Dataset citation

M. N. Mohamad et al., “The prevalence of diabetes amongst young Emirati female adults in the United Arab Emirates: A cross-sectional study,” PLOS ONE, 16(6), e0252884, 2021. https://doi.org/10.1371/journal.pone.0252884

T
