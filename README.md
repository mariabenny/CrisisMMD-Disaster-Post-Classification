# CrisisMMD-Disaster-Post-Classification
# CrisisMMD Disaster Post Classification

This project compares text-only, image-only, early-fusion and late-fusion
models for identifying informative disaster posts in CrisisMMD v2.0.

## How to reproduce the results

1. Download `CrisisMMD_Experiment.ipynb` and open it in Google Colab.
2. Choose a CPU runtime and run the cells from top to bottom.
3. Mount Google Drive when prompted. Add a Hugging Face read token
   to Colab Secrets under the name `HF_TOKEN` and enable notebook access.
4. Use the recorded dataset and image revisions to reproduce the
   original run. The notebook samples 1,200 training, 300 validation
   and 300 test records from their original splits using seed 42.
5. Open the output folder printed by the notebook to find the results
   tables, plots and model files.

Dataset: https://huggingface.co/datasets/QCRI/CrisisMMD
