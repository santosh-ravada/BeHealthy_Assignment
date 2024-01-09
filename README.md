# BeHealthy_Assignment
>
> This is a system design case study for Be Healthy, a health platform. The case study focuses to build a custom NER to get the list of diseases and their treatment from the dataset.

## Table of Contents

- [Be-Healthy-System-Design-Case-Study](#be-healthy-system-design-case-study)
  - [Table of Contents](#table-of-contents)
  - [General Information](#general-information)
    - [Problem Statement](#problem-statement)
    - [Solution](#solution)

## General Information

### Problem Statement

‘BeHealthy’ has a web platform that allows doctors to list their services and manage patient interactions and provides services for patients such as booking interactions with doctors and ordering medicines online. Here, doctors can easily organize appointments, track past medical records and provide e-prescriptions. So, companies like "BeHealthy" are providing medical services, prescriptions and online consultations and generating huge data day by day.
We have been given such a data set in which a lot of text is written related to the medical domain. There are a lot of diseases that can be mentioned in the entire dataset and their related treatments are also mentioned implicitly in the text, which we saw in the aforementioned example that the disease mentioned is cancer and its treatment can be identified as chemotherapy using the sentence. However, note that it is not explicitly mentioned in the dataset about the diseases and their treatment, but we can build an algorithm to map the diseases and their respective treatment.
The requirement is to build a custom NER to get the list of diseases and their treatment from the dataset.

### Solution

Two solution has been added for the problem statement, focusing on the system design required for hosting a custom NER Model. Both draft contains explanation of the system design and the reason for choosing the particular design.
