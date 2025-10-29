# Team-03

1. First I imported libraries included PyTorch, torchvision, Hugging Face, and utility tools for training and visualization

2. Then I loaded dataset which contains low-res (LR) and high-res (HR) image pairs. Later I resized LR images to 64*64 and HR images to 128*128, then converted it to tensors

3. Now I imported pretrained EDSR(*2 upscaling) from Hugging Face. Using MSE loss and Adam optimizer, tried to minimize pixel difference between SR output and HR image

4. Lastly I plotted training and validation loss.
