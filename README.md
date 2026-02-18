# startathon
# Offroad Semantic Segmentation Model

## Setup

1. Install Anaconda
2. Create environment:
   conda create -n EDU python=3.9
3. Activate:
   conda activate EDU
4. Install dependencies:
   pip install -r requirements.txt

## Training

python train.py

## Testing

python test.py

## Outputs

- Model checkpoints saved in runs/
- IoU score displayed in console
- Predictions saved in outputs/

## Expected Performance

Mean IoU: ~0.60–0.65
Inference speed: < 50ms per image
