# DRIDE
Drone-Based Rice Image Disease Evaluation

# Drone-Based Rice Disease Detection

A computer vision system for detecting and classifying rice plant diseases using drones and Raspberry Pi. This project utilizes machine learning to perform real-time disease detection through aerial imagery.

## 🌾 Overview

This project implements a drone-mounted disease detection system that can:
- Capture aerial images of rice fields
- Process images in real-time using a Raspberry Pi
- Detect and classify common rice diseases
- Provide insights for early disease management

## 🛠️ Requirements

### Hardware
- Raspberry Pi (4 recommended)
- Camera module or USB webcam
- Drone with camera mount
- MicroSD card (32GB+ recommended)
- Power supply for Raspberry Pi

### Software
- Python 3.8+
- OpenCV
- TensorFlow 2.x
- NumPy
- Pillow

## 📂 Project Structure

```
rice-disease-detection/
├── data/              # Dataset storage
├── models/            # Trained models and configs
├── src/              # Source code
├── utils/            # Utility functions
├── tests/            # Unit tests
└── docs/             # Documentation
```

## 🚀 Setup

1. Clone the repository:
```bash
git clone https://github.com/yourusername/rice-disease-detection.git
cd rice-disease-detection
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Configure Raspberry Pi:
```bash
# Instructions for Raspberry Pi setup will be added
```

## 📊 Training

1. Prepare dataset:
   - Place training images in `data/raw_images`
   - Run preprocessing scripts
   - Verify processed data

2. Train model:
   - Configure training parameters
   - Run training script
   - Monitor training progress

## 🎯 Usage

1. Connect hardware:
   - Mount camera on drone
   - Ensure Raspberry Pi is properly powered
   - Test camera connection

2. Run detection:
```bash
python src/inference/detect.py
```

## 📝 Disease Classes

Currently supports detection of:
- Bacterial Leaf Blight
- Brown Spot
- Leaf Smut
- Healthy Plants

## 📈 Performance

- Inference time: [TBD]
- Accuracy: [TBD]
- Resolution support: [TBD]

## 🤝 Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/NewFeature`)
3. Commit changes (`git commit -m 'Add NewFeature'`)
4. Push to branch (`git push origin feature/NewFeature`)
5. Open Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Team

- [Angelo Agudo] - Initial work - [github.com/hellw1nd]

## 🙏 Acknowledgments

- [REDACTED]
- [REDACTED]
- [REDACTED]

## 📞 Contact

- GitHub: [@hellw1nd]

## 🔄 Status

Project is: _in development_

---
**Note:** This README will be updated as the project develops.
