# IADF SCHOOL: Deep Learning in SuperResolution


![Logo](images/logoIADF.png)



Remote sensing plays a vital role in understanding our planet, influencing critical applications such as weather forecasting, biodiversity tracking, land management, and disaster relief. The vast amount of data collected from Earth Observation (EO) satellites, such as Sentinel, opens up opportunities for innovation in image analysis techniques.

Super-resolution, a subfield of deep learning, enhances the spatial resolution of satellite images, allowing for finer details to be extracted from lower-resolution data. This approach can significantly improve decision-making processes in environmental monitoring, urban planning, and emergency response. In this repository, we explore the use of deep learning techniques to achieve super-resolution for remote sensing images, with practical examples and code implementations.

---

## Software Dependencies

1. Git: ``` sudo apt-get install git ```
2. Visual Studio Code: [https://code.visualstudio.com/](https://code.visualstudio.com/)
```
sudo dpkg -i code_1.93.0-1725459079_amd64.deb
```
3. Anaconda: [https://www.anaconda.com/download/success](https://www.anaconda.com/download/success).
```
chmod +x Anaconda3-2024.06-1-Linux-x86_64.sh
./Anaconda3-2024.06-1-Linux-x86_64.sh
source .bashrc
```
**Recomendation:** \
You can undo this by running conda init --reverse $SHELL? [yes|no]
[no] >>> **yes** \
conda config --set auto_activate_base false

---

## Create and activate the Conda Environment
```
conda create --name iadf-env
conda activate iadf-env
```

## Libraries Dependencies
```
conda install pytorch torchvision torchaudio pytorch-cuda=12.1 -c pytorch -c nvidia
conda install scikit-learn numpy matplotlib scikit-image
pip install opencv-python
```