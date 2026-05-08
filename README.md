# pixels-to-predictions

Fine-tuning SmolVLM-500M-Instruct for multimodal scientific VQA using DoRA-based LoRA and NLL candidate scoring.

**Final leaderboard score: 0.8190**

## How to Run

1. Open `final_project.ipynb` in Google Colab
2. Mount Google Drive
3. Run all cells in order
4. `submission.csv` will be saved automatically

## Data and Resources

All data, caption cache are available at:

[Google Drive](https://drive.google.com/drive/folders/1AkbmjhT14235LPxU-uSMyx3qqP4FJQ6O?usp=drive_link)

Place all files in:
/content/drive/MyDrive/pixels_to_predictions/

## Requirements

Installed automatically via the first cell in the notebook:
transformers==4.57.6
peft==0.19.1
bitsandbytes
accelerate
torchao
pillow

## Environment

- Google Colab (A100 GPU)
- Random seed: 42
