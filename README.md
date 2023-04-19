# Atrial Fibrillation Detection
Data Science Project - Time Series &amp; Data Mining

## Introduction

This project aims to develop a machine learning model that can detect the presence of atrial fibrillation (AF) in RR intervals of electrocardiogram (ECG) recordings. AF is a type of irregular heartbeat, or arrhythmia, that originates in the upper chambers of the heart (the atria). In AF, the atria beat irregularly and rapidly, which can cause poor blood flow to the body and increase the risk of blood clots, stroke, heart failure, and other cardiovascular complications. Although AF is a common cause of many dangerous cardiovascular complications, it can be very difficult to detect, requiring tedious manual works. AFs are very short in the ECG signals and there are a lot of noises in the signals themselves. Therefore, an automatic early AF detection is crucial for effective treatment.

## Dataset

This dataset contains electrocardiogram (ECG) data from patients who underwent coronary artery bypass graft (CABG) surgery at the Erasmus Medical Centre in Rotterdam, Department of Electrophysiology. The dataset is used for detecting atrial fibrillation (AF) using machine learning algorithms.

There are two initial datasets available: preprocessed and raw data.
- The preprocessed data consists of 150,000 observations with 30 dependent variables and one independent variable (Control).
- The raw data consists of ECG and class data. The ECG data is stored in 804 text files (Data1 to Data804) and analyzed using a semi-automatic program (Synescope) for R peak annotation. The ECG data is then manually audited by a physician to label AF cases. The class data is also stored in 804 text files (Control1 to Control804), where the AF and no-AF episodes were transformed into 1 and 0 in 30-second intervals by considering if more than 75% of the period was AF.

## Methods

...

## Results

...

## Contributors

- Michael (https://github.com/michaelgondosari)
- Pedro (https://github.com/pedrohsmay)
