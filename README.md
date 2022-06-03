# SDS2022-workshop-fair-algorithms

To follow along with the exercises, you have two options:
1. Run everything locally (recommended if you already have Python and ideally Jupyter installed)
2. Use Google Colab & Google Drive (recommended if you don't have Python installed)

## 1. Run everything locally

Clone the repository in the desired folder using the command

```
git clone https://github.com/hcorinna/SDS2022-workshop-fair-algorithms.git
```

Open Jupyter and navigate to the repository you cloned, then open the Jupyter Notebook you want to edit and start coding.

## 2. Use Google Colab & Google Drive

- Go to: http://colab.research.google.com/
- Log in with a Google account
- Create a new Notebook: File > New Notebook
- Connect the notebook to Google Drive
```
from google.colab import drive
drive.mount("/content/gdrive")
```
- Add a new code cell with: + Code
```
%cd gdrive/MyDrive
! git clone [https://github.com/hcorinna/SDS2022-workshop-fair-algorithms.git](https://github.com/hcorinna/SDS2022-workshop-fair-algorithms.git)
```

Now the repository has been saved to your Google Drive. Next, go to https://drive.google.com/, open the folder "SDS2022-workshop-fair-algorithms", and open the desired Jupyter Notebook: Open with > Google Colaboratory. This should allow you to run the notebooks without having to install Python.
