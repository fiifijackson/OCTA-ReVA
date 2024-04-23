# OCTA-ReVA
## Overview
OCTA-ReVA (Optical Coherence Tomography Angiography - Retinal Vessel Analyzer) is an open-source platform designed for the automated extraction and quantitative analysis of OCTA features. It provides a user-friendly graphical interface built with MATLAB, facilitating detailed and non-invasive analysis of retinal blood vessels which is crucial for studying and diagnosing eye diseases.

## Features
**Graphical User Interface (GUI)**: Intuitive design with buttons, dropdown menus, and real-time visualization panels.\
![GUI](https://github.com/fiifijackson/OCTA-ReVA/assets/75156845/2d4ee1c9-2cb1-4a5a-9dd8-8199b50dc402)\
The interface of the OCTA-ReVA at startup.\
<br>

**Quantitative Analysis**: Capable of calculating multiple OCTA features such as vessel density, vessel caliber, vessel perimeter index, and more.\
![Features](https://github.com/fiifijackson/OCTA-ReVA/assets/75156845/68f57756-1889-4333-b57e-766a46ceb7a4)\
The OCTA-ReVA after extracting quantitative features\
<br>

**Supports Single and Batch Processing**: Enhanced utility for handling large-scale studies.\
**Flexible Binarization Techniques**: Includes several methods such as Otsu, fixed, mean, median, and 3-sigma thresholding to suit diverse analytical needs.\
![image](https://github.com/fiifijackson/OCTA-ReVA/assets/75156845/60a55889-7d87-4a41-9f54-a14e9aeddd70)
Binary masks of the various binarization techniques. A) Original OCTA image. B) Otsu method. C) Fixed thresholding with a threshold value of 0.3. D) Mean thresholding. E) Median thresholding. F) 3-sigma method.\
<br>

**Export Option**s: Allows saving of analysis results directly into Excel format and optional exporting of intermediate images.
![image](https://github.com/fiifijackson/OCTA-ReVA/assets/75156845/759be7e8-fbf1-49a2-9221-01f265105e06)\
Intermediate images. A) Original OCTA image. B) Binarized vessel map. C) Skeletonized vessel map. D) Vessel perimeter map.

## Installation
The OCTA-ReVA toolbox is available in two installer formats:

**Full Installer (Recommended)**: Includes all necessary MATLAB runtime libraries. Best for users without an internet connection or who do not have MATLAB installed.\
  &emsp;**Download:** [[Link to Full Installer](https://uofi.box.com/s/oiukszfkkxat09omhgl7cunmnkrm5p5x)]\
  &emsp;**Installation Steps:**\
    &emsp;&emsp;1. Download the Full Installer.\
    &emsp;&emsp;2. Double-click the downloaded file to begin the installation process.\
    &emsp;&emsp;3. Follow the on-screen instructions to complete the installation.
     
**Basic Installer:** Requires an active internet connection to download MATLAB runtime libraries during installation. Suitable for users with MATLAB already installed or with internet access.\
  &emsp;**Download:** [Link to Basic Installer]\
  &emsp;**Installation Steps:**\
    &emsp;&emsp;1. Download the Basic Installer.\
    &emsp;&emsp;2. Double-click the downloaded file to begin the installation process.\
    &emsp;&emsp;3. The installer will prompt you to download the MATLAB runtime if not already installed. Follow the on-screen instructions to complete both the runtime and software installation.
 

If you encounter any issues during installation or usage, please contact support.

## Usage
1. Start the OCTA-ReVA Toolbox from the MATLAB command window.
2. Load OCTA images by specifying the directory containing the images.
3. Configure analysis parameters such as plexus layer, scan size, and binarization technique.
4. Click "Apply" to start the analysis.
5. Review and save the results as needed.

## Support
For support, email adadzi2@uic.edu or xcy@uic.edu, or open an issue on the repository's issue tracker.

## Acknowledgments
• National Eye Institute.\
• Research to Prevent Blindness.\
• Richard and Loan Hill Endowment.\
• All contributors who participated in the development and enhancement of the OCTA-ReVA toolbox.

## Citation
If you use OCTA-ReVA in your research, please cite:

[...]

## Contact
Lead Developer: Albert Kofi Dadzie - adadzi2@uic.edu\
Project Supervisor: Dr. Xincheng Yao - xcy@uic.edu\
Institution: Department of Biomedical Engineering and Department of Ophthalmology & Visual Sciences, University of Illinois Chicago.
