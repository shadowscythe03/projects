# projects
my projects
## Aerial Sematic Segmentation

## Document Level Text Simplification of College Admission documents

## Image Segmentation techniques

## m-PainAttnNet: Multimodal Transformer Encoder with Multiscale Deep Learning for Pain Classification Using Physiological Signals

Pain is a very common symptom of many diseases. It can be of many kinds. It is important to quantify the intensity of pain level that a person is experiencing in order to decide what further steps can be taken. Automated classification of pain intensity using Artificial Intelligence based models can be a plausible solution to this problem. We propose Multimodal PainAttnNet (m-PainAttnNet) model that is a multimodal extension of the PainAttnNet model that was proposed in [Zhenyuan Lu et al](https://www.frontiersin.org/journals/physiology/articles/10.3389/fphys.2023.1294577/full). We utilized the [BioVid Heat Pain Database](https://www.nit.ovgu.de/BioVid.html) for our studies. The model comprises of 3 basic architecture blocks - MSCN, SEResNet and Transformer Encoder. Multimodal PainAttnNet can take multiple types of signals such as EDA, ECG and EMG as inputs and classify between various pain intensity levels. m-PainAttnNet can perform two types of fusion - Early and Late. We also performed ablation study on the model by comparing the performance of various blocks of the m-PainAttnNet model to the full model's performance. The performance of our m-PainAttnNet model is exceeding the benchmarks reported by the authors of [Zhenyuan Lu et al.](https://www.frontiersin.org/journals/physiology/articles/10.3389/fphys.2023.1294577/full) on almost all the classification tasks.


### Directory Structure
```python
projects\m-PainAttnNet
|   G-15_Final_Presentation.pptx is the presentation detailing our project
|   G-15_Final_Project_Draft_Abhiroop.pdf is our report detailing about m-PainAttnNet model and the results when our model is run
|   m-PainAttnNet.ipynb # Implementation of Multimodal PainAttnNet Model
|   m-PainAttnNet_Ablation_Study.ipynb # Ablation Studies on Multimodal PainAttnNet Model for various classification tasks
```

### Requirements

```
python
torchaudio
pytorch-cuda
pytorch
torchvision
scikit-learn
pandas
matplotlib
openpyxl
```

You can change settings in `m-PainAttnNet.ipynb` file for running m-PainAttnNet model for various classification tasks and fusion types.


### Dataset
The dataset is available at [BioVid Heat Pain Database](https://www.nit.ovgu.de/BioVid.html).



## Stable Matchings
