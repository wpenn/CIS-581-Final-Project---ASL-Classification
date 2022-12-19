# CIS 581 Final Project - ASL Recognizer


## Directory
    .
    ├── Datasets
    │   └── ASL-coco                        # ASL Dataset
    │       ├── test
    │       ├── train
    │       └── valid
    ├── Documents
    │   └── CIS_581_Final_Report.pdf        # Final Report
    ├── Image Results                       # Image Results from Inference                               
    ├── Notebooks
    │   ├── final.ipynb                     # Final Notebook with Relevant Implementation (Run me)
    │   ...
    └── README.md

## How to run code
1. Upload folder to your Google Drive
2. In the notebooks folder, open the `final.ipynb` in Google Collab
3. In the **Setup** section of the notebook, Edit the 'Guest' path in the `root_paths` to the directory of your folder in Google Drive:

```python
root_paths = {
    "Mark": "/content/drive/MyDrive/CIS5810/CIS581_FinalProject",
    "Brandon": "/content/drive/MyDrive/CIS581_FinalProject",
    "Wesley": "/content/drive/MyDrive/2022-2023/Sem1/CIS 581/CIS581_FinalProject",
    "Wesley(+)": "/content/drive/MyDrive/CIS 581/CIS581_FinalProject",
    "Ronil": "/content/drive/MyDrive/CIS581_FinalProject",
    "Guest": None
}
```
4. Immediately underneath `rooth_paths` in **Choose User**, select "Guest" from the dropdown menu
5. Run the Notebook: Runtime --> Run all

Note: In order to run the noteebook you are required to give permissions to your drive.