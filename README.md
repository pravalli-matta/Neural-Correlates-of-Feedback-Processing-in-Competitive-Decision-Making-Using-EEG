# Neural Correlates of Feedback Processing in Competitive Decision-Making Using EEG

This project examined EEG responses to outcome feedback during a competitive Rock–Paper–Scissors task. The analysis focused on feedback following wins, losses, and draws, and was completed as part of the Human Brain Mapping course at IIT Gandhinagar (2026).

## Research Focus

Feedback provides information about the outcome of an action. Event-related potentials (ERPs) make it possible to study how brain responses change over time following different outcomes.

The project examined feedback-locked neural responses across three outcome conditions:

- Win
- Loss
- Draw

## Data and Analysis

The dataset included EEG recordings from 20 participants. The analysis was conducted using MNE-Python and involved:

1. Filtering and downsampling the EEG data.
2. Selecting channels for analysis.
3. Creating epochs time-locked to feedback events.
4. Applying baseline correction.
5. Identifying and rejecting artefact-contaminated epochs.
6. Computing and visualising ERP waveforms for the feedback conditions.
7. Examining feedback-related negativity (FRN) and P300 responses, including amplitude comparisons and scalp topographies.
8. Using paired-samples t-tests for condition comparisons.

## What the Analysis Can Address

The ERP analysis allows feedback-locked responses to be compared across win, loss, and draw outcomes. FRN and P300 are considered in relation to feedback evaluation and the processing of outcome information.

These components are not unique markers of a single psychological process. Their interpretation depends on the task, time window, electrode selection, preprocessing decisions, and statistical analysis. The project therefore treats the observed ERP patterns as evidence about responses in this task, rather than as definitive measures of an individual's feedback sensitivity.

## Report

[Read the project report (PDF)](NEURAL%20CORRELATES%20OF%20FEEDBACK%20PROCESSING%20IN%20COMPETITIVE%20DECISION-MAKING%20USING%20EEG.pdf)

## Methods and Tools

EEG, MNE-Python, preprocessing, feedback-locked epoching, baseline correction, artefact rejection, ERP analysis, FRN, P300, scalp topographies, and paired-samples t-tests.

## Project Details

- **Course:** Human Brain Mapping
- **Institution:** IIT Gandhinagar
- **Instructor:** Prof. Vaibhav Tripathi
- **Year:** 2026
- **Author:** Pravalli Matta
