
# Computer Vision Project 1

## Overview
This project is implemented in a single Jupyter Notebook file, `Project_1.ipynb`, which explores various aspects of image processing and computer vision techniques, including sampling, filtering, noise handling, and edge detection using Sobel filters.

The project consists of the following problems:
1. **Problem 1**: Image Sampling (Downsampling and Upsampling).
2. **Problem 2**: Gaussian Smoothing.
3. **Problem 3**: Image Filtering (Gaussian and Median Filtering).
4. **Problem 4**: Noise Handling.
5. **Problem 5**: Sobel Filters for Edge Detection and Gradient Analysis.

Each problem is explained and solved within the notebook, with corresponding outputs and observations documented for better understanding.

## Prerequisites
To run this project, you will need the following:

- **Python 3.x** (Recommended version: 3.6 or above)
- Required Python libraries:
  - `numpy`
  - `matplotlib`
  - `PIL` (Pillow)
  - `jupyter`

### Installing Dependencies
If you don't have the required libraries installed, you can install them using the following command:

```bash
pip install numpy matplotlib pillow jupyter
```

## How to Run the Project
1. **Open the Jupyter Notebook**:
   Navigate to the directory where `Project_1.ipynb` is located and start the Jupyter Notebook server by running:

   ```bash
   jupyter notebook
   ```

2. **Open `Project_1.ipynb`**:
   In the Jupyter Notebook interface that opens in your browser, locate and open the `Project_1.ipynb` file.

3. **Run Each Cell Sequentially**:
   - The notebook is structured such that each problem is handled in separate cells.
   - You can run each cell sequentially using the `Shift + Enter` command or by selecting `Run` from the toolbar.

4. **Review the Output and Observations**:
   - Each problem has corresponding outputs (images and visualizations) displayed below the respective code cells.
   - Observations and conclusions are documented within the notebook for each problem.

## Project Structure
The project files are organized as follows:

```
Project_1.ipynb
lena.png
Problem1.png
Problem2.png
Problem3.png
Problem4.png
Problem5.png
README.md
Report_Project1_Shishir.pdf
```

- The file `Project_1.ipynb` contains the code and solutions for all the problems.
- The file `lena.png` is the input image used throughout the project.
- The `Problem1.png`, `Problem2.png`, etc., are the output images generated for each problem, stored for reference.
- `README.md` provides instructions on running the project.
- Report_Project1_Shishir.pdf provides a detail report about the project 1.

## Additional Notes
- Ensure that the `lena.png` image is in the same directory as the `Project_1.ipynb` file to avoid any issues with loading the image.
- The notebook is self-contained, and all outputs will be displayed inline when run in the Jupyter environment.

## Troubleshooting
- If the notebook does not display correctly, ensure that Jupyter is installed correctly and the necessary dependencies (`numpy`, `matplotlib`, `pillow`) are available.
- If any cell throws an error due to missing files or dependencies, verify that `lena.png` is in the same directory as the notebook and rerun the cell after installing the dependencies using `pip`.


