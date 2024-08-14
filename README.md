# DICOM to D-NeRF conversion

## Project Overview

The DICOM to D-NeRF converter is a python script focused on analyzing and processing rotational angiography data in DICOM format containing ECG and frame iamge data. The script aims to provide tools for calculating R-R intervals and frame timings in cardiac imaging.

The code was tested on a rotational angiography dataset from a Philips Azurion system.

A sample DICOM dataset can be downloaded from: [Sample DICOM dataset](https://drive.google.com/file/d/1Mu3FwYE_tJ1GG7hFb_MqmjjNYqcXIkys/view?usp=sharing).



## Features

- ECG data extraction from DICOM files
- R-peak detection in ECG signals
- Calculation of R-R interval percentages for image frames
- Visualization of R-R percentages
- Computation of the transformation matrix for each frame
- Conversion of DICOM to D-NeRF format

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/Synthangio.git
   cd Synthangio
   ```

2. Set up a virtual environment (recommended):
   ```
   python -m venv .venv
   source .venv/bin/activate  
   ```

3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

The main functionality is provided in the `camera_views.ipynb` Jupyter notebook. To use it:

1. Launch Jupyter Notebook:
   ```
   jupyter notebook
   ```

2. Open the `camera_views.ipynb` file.

3. Run the cells to process DICOM files and visualize results.

## File Structure

- `camera_views.ipynb`: Main Jupyter notebook containing the analysis code
- `.gitignore`: Specifies intentionally untracked files to ignore
- `requirements.txt`: List of Python dependencies (to be created)


## License

MIT License

## Contact

Pascal Theriault-Lauzier - [ptheriault@ottawaheart.ca]
