# FER-2013 Emotion Classification

## How to run

1. Create a virtual environment and install dependencies in PowerShell:

   ```powershell
   python -m venv .venv
   .\.venv\Scripts\Activate.ps1
   python -m pip install -r requirements.txt
   ```

2. Open `final.ipynb` in VS Code and select `.venv` as the notebook kernel.
3. Run all cells from top to bottom to download the dataset, train VGG16 and ResNet50, and view the results.

The first run requires internet access to download the dataset and ImageNet weights. Generated files are saved in `data/` and `models/`.
