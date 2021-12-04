# job-search-backstories
A collection of backstories for job search scenarios.

## Overview
This repository contains the backstory collection resource accompanying the following paper. For a description of how to crowdsource backstories for complex task-based search, as well as the reasoning behind it, please refer to the paper.

Manuel Steiner, Damiano Spina, Falk Scholer, Lawrence Cavedon (2021). Crowdsourcing Backstories for Complex Task-Based Search. Proceedings of the 25th Australasian Document Computing Symposium.

## Files
The following files are provided in this repository.

**job-search-backstories.csv**  
A collection of job search queries, links to associated job advertisements and backstories written for the particular query and job ad combination. The file contains the following data on each line, separated by comas. Strings may be enclosed by double quotes if they contain comas.

* `query` refers to a job search query submitted to the job search platform
* `job_url` contains the URL to the job advertisement associated with the search query in the crowdsourcing experiment. **Note:** The URL is publicly accessible information. Hoewever, the job advertisements themselves are expired and not publicly accessible. Thus, no sensitive or proprietary information is revealed. This content is part of the data for reproducibility reasons.
* `backstory` contains a backstory that was written by a crowdsourcing worker for the combination of query and job advertisement.

**paper.pdf**  
The paper as published in the ADCS proceedings.

**presentation.pdf**  
The presentation slides as presented during the ADCS semninar series.

## Acknowledgments
This research was partially supported by Australian Research Council Project LP150100252 and SEEK Ltd.
