# Cardiac MRI Segmentation

In the field of medical imaging, diagnosing a cardiac MRI sometimes requires radiologists to manually delineate the different structures of the heart to extract functional information such as cardiac volume over time or ejection fraction. This project aims to create an algorithm to assist the cardiologist in this diagnosis and segment the different parts of the heart in an MRI.

## Getting Started

This project was developed using Python, and a user interface has been implemented, but it is currently only available locally as we do not have a server to host it. The MRIs used for the training and validation dataset were downloaded from the site.

### Prerequisites

To run this program, you need Python version 3.7 or later and the following modules installed:
- pandas
- tensorflow  
- opencv2
- medpy
- nibabel

## Execution

To execute the program, simply run the python file `main.py` to see an example with an MRI from our database. It is also possible to run it with another MRI by replacing the file in the `prediction` folder in `main.py` with the new MRI. The execution will then return the segmentation of the new MRI according to our algorithm.

To facilitate the use of the program, we have also developed a local user interface with Flask and Plotly. However, it is not available online due to the lack of a hosting server, but the file can be transferred upon request.
