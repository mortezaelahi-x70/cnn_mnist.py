# CNN MNIST Classifier

PyTorch Convolutional Neural Network (CNN) trained on the MNIST dataset.  
Includes feature map visualization to inspect activations of convolutional layers.

---

## 🛠 Features
- Two convolutional layers with max pooling
- Fully connected layers for classification
- Feature map visualization using hooks
- CPU/GPU compatible
- Easy to extend for other datasets

---

## 📂 Project Structure

```
cnn-mnist-classifier/
 ├── cnn_mnist.py        # Main Python script with model and visualization
 ├── README.md           # This file
 ├── requirements.txt    # Python dependencies
 ├── models/             # Folder to save trained models
 └── data/               # MNIST dataset (downloaded automatically)
```

---

## ⚡ How to Run

1. Create a virtual environment:

```bash
python -m venv venv
# Activate environment:
# Windows:
venv\Scripts\activate
# macOS/Linux:
source venv/bin/activate
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the project:

```bash
python cnn_mnist.py
```

> The model will automatically download MNIST dataset and display feature maps for convolutional layers.

---

## 📈 Results

- Displays feature maps for conv layers
- Tracks accuracy visually in the training loop
- Can save models in `models/` folder

---

## 🧰 Requirements

- Python 3.8+  
- torch  
- torchvision  
- matplotlib  
- numpy  

---

## 📚 References

- [PyTorch Documentation](https://pytorch.org/docs/stable/index.html)  
- [MNIST Dataset](http://yann.lecun.com/exdb/mnist/)

---

## 📄 License

MIT License
