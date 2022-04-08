# Identifying and Validating Networks of Oncology Biomarkers Mined From the Scientific Literature

This repository contains code related to the publication:

Wager K, Chari D, Ho S, Rees T, Penner O, Schijvenaars BJ. Identifying and Validating Networks of Oncology Biomarkers Mined From the Scientific Literature. Cancer Informatics. January 2022. doi:10.1177/11769351221086441

The goal of this project was to produce biomarker-biomarker networks (graphs) based on co-occurrence in the text of scientific research publications.

The code provided picks up the process after co-occurrences have been counted, and carries the process forward to the point where 7 networks are generated (one for each of 6 specific cancers, plus one cancer-agnostic network that merges all co-occurrence data).

It should be noted that the code provided does not, exactly, reproduce the networks presented in the publication as these are based on updated data (*i.e.* additional publications).