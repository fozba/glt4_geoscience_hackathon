# TEAM GLT - Geoscience Hackathon 24

**Members:** Zulkuf Azizoglu, Cinar Turhan, Fehmi Ozbayrak  
**Project Based On:** [Segment Every Grain](https://github.com/zsylvester/segmenteverygrain) (Dr. Zoltán Sylvester)

## Project Overview

This project aims to provide the end user with a workflow that takes an image of a grain collection of any sort and calculates the statistical and possibly geological quantitative properties of the grains.

---

## Folder Structure

The project directory contains the following files and directories:

- **checkpoints/**: Contains model checkpoints.
- **coconino.csv**: Resulting data from the analysis of the `coconino.jpg` image.
- **coconino.jpg**: Original image of the grain collection used for analysis.
- **cropped.jpg**: A demo image for fastly testing the segmentation workflow.
- **latex**: Associated LaTeX files
- **output_images/**: Directory where output images from the analysis are saved.
- **README.md**: This file, providing an overview of the project.
- **sam_vit_h_4b8939.pth**: Fine-tuned weights for the model.
- **Team_GLT4_Final.pptx**: The Project Presentation
- **workflow.ipynb**: The main workflow implemented in a Jupyter notebook.

## Usage

1. **Install Dependencies**: Ensure you have all necessary dependencies installed. You can find them in `environment.yml`.
  
2. **Run the Workflow**: Open `workflow.ipynb` in Jupyter Notebook. Follow the instructions within the notebook to load your grain image and run the analysis.

3. **Results**: The results of the analysis will be saved in `output_images/`. 

## Contributing

If you would like to contribute to this project, please fork the repository and create a pull request with your changes.

## License

--

## Acknowledgments

We thank Dr. Zoltán Sylvester for his foundational work, which inspired this project.
