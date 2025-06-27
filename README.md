# Spectral-Signature-Classifier
An ML tool to classify astronomical objects by fetching SDSS spectra and analyzing the light signatures of celestial objects using a Logistic Regression Model. The pre-processed spectral data is hence interpolated and used to train the model to recognize the celestial object using the captured light intensity in a specific wavelength range.
# 🌌 Spectral Signature Classifier

This project leverages authentic astronomical spectral data to perform automated classification of celestial objects — specifically **stars**, **galaxies**, and **quasars (QSOs)** — based solely on their light signatures.

It is based on data acquired from the **Sloan Digital Sky Survey (SDSS)**, one of the most comprehensive sky surveys ever conducted. By analyzing the intensity of light across wavelengths (spectral data), this project constructs a machine learning tool distinguishing object types through their unique spectral signatures.

---

## Project Overview

- Interfaces with the SDSS public database using `astroquery` to retrieve spectra
- Interpolates all flux measurements onto a standardized wavelength grid for consistency
- Trains a logistic regression classification model using scikit-learn to distinguish object types
- Visualizes and verifies spectral features for research expansion

> This model does not rely on simulations or augmented datasets — it learns directly from **real, observational data collected by the 2.5-meter SDSS telescope**.

---

## Scientific Motivation

Astronomical spectra encode critical information about cosmic objects — including redshift, elemental composition, and physical classification. However, with millions of such spectra archived and growing exponentially, manual labeling and inspection is no longer scalable.

This project illustrates the application of machine learning to:
- Automate the classification of celestial objects
- Enable scalable preprocessing of large spectral datasets
- Explore how AI can assist in future astronomical surveys and classification tasks

---

## Repository Structure

- google collab python script
- Preprocessed SDSS spectra (optional shortcut)  
  🔹 Provided for those who wish to bypass data querying and begin directly with modeling
- `README.md` — Project documentation

---


