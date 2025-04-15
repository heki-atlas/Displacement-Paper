# Displacement-Paper
Code used for data evaluation in: doi:

# Displacement of intraabdominal Vascular Structures during Capnoperitoneum in the Porcine Model

This repository contains code and a Jupyter notebook for evaluation of displacement of blood vessels, the ureters and the intraabdominal part of the Esophagus at 
six equidistant points. Both the distance of displacement and the angle the displacement is happening at are calculated in one of our datasets in this code.
Plotting options and code for registration will be added this week.

---

## Environment Setup

To ensure full compatibility, please use the provided `environment.yml` to recreate the environment using Conda.
The code was run on Linux Mint 22.1.

### 🔧 Installation Instructions

1. Install [Miniconda](https://docs.conda.io/en/latest/miniconda.html) or [Anaconda](https://www.anaconda.com/).
2. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo

    Create the environment:

conda env create -f environment.yml

Activate the environment:

    conda activate your-env-name

📓 Running the Notebook

    Download the Notebook as a ZIP file:

        Download the entire folder named Displacement and Angles as a ZIP from GitHub.

    Unzip the file:

        After downloading, unzip it to a directory of your choice.

    Create a new Kernel:

        To ensure the notebook runs with the correct environment, create a new Jupyter kernel linked to your Conda environment:

python -m ipykernel install --user --name your-env-name --display-name "Python (your-env-name)"

Launch Jupyter:

    Start Jupyter Notebook:

    jupyter notebook

        Select the kernel Python (your-env-name) from the Jupyter Notebook interface.

    Run the notebook:

        Open the notebook located in the A folder.

        The notebook will guide you through the analysis. Ensure that you run each cell in order to avoid errors.

    All results will be saved in the Results folder. You can also access the 3D models in the 3D Models folder and the centerlines data in the Centerlines folder.

🗂 Repository Structure

your-repo/
├── Displacemen and Angles/    # Main folder containing the notebook and subfolders, zipped
│   ├── notebook.ipynb         # Main Jupyter notebook for analysis
│   ├── Results/               # Folder for results (generated by notebook)
│   ├── 3D Models/             # Folder for 3D models (input/output)
│   └── Centerlines/           # Folder for centerlines data (input/output)
├── environment.yml            # Conda + pip environment file
└── README.md                  # Your current location :)

Notes

    This project uses both Conda and pip packages for maximum compatibility.

    For large datasets or outputs, make sure to adjust paths or mount external drives accordingly.

Contact

For questions or contributions, feel free to open an issue or reach out at [helena.kirr@outlook.com].
License

This project is licensed under the MIT License.

