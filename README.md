# NERGRIT CORPUS

## MUST READ
All NERGRIT contributors and LICENSE must be included if You use this corpus. This corpus can be used both for learning or commercially.

## NERGRIT
NERGRIT is machine learning based NLP Tools used for Indonesian Named Entity Recognition, Statement Extraction, and Sentiment Analysis. This is the corpus we made and have `F1 score` with using `glove` as follow:

  - Named Entity Recognition: ~ 80.00%
  - Statement Extraction: ~ 70%
  - Sentiment Analysis: ~ 75%

## Download
Open this link => https://ner.grit.id/index.php/front/about
and click "GET NERGRIT CORPUS"
## How to Use
Better use Python 3 and use your GPU instead of CPU for training, and run the following on your OS:
```bash
pip install virtualenv
```
Virtual Enviroment for `NER` and `Statement` using Anago version 1.0.8 :
```bash
cd nergrit-corpus
mkdir venv
virtualenv venv
source venv/bin/activate
pip install anago
```
Traning the model for `Name Entity Recognition (NER)` with:
```bash
cd ner/
python make_model.py
```
Try the model with:
```bash
python tag.py
```

Traning the model for `Statement Extraction` with:
```bash
cd statement/
python make_model.py
```
Try the model with:
```bash
python tag_statetement.py
```

Virtual Enviroment for `Sentiment Analysis` using Anago version 0.0.5 :
```bash
cd nergrit-corpus
mkdir venvold
virtualenv venvold
source venvold/bin/activate
pip install anago==0.0.5
```
Traning the model for `Sentiment Analysis` with:
```bash
cd sentiment/
python make_model.py
```
Try the model with:
```bash
python test_data.py
```
If You demand the model to be optimized more, you can create `glove` from wikipedia Indonesia or any Indonesian articles.
#### Copyright (C) 2019 NERGRIT DEVELOPERS
`Coach`:
  - Riyanti Kusumawati
 
`Mentor`:
  - Dr. Yudi Wibisono <yudi1975@gmail.com>
 
`Lead Developer`:
  - Dr. Husni Fahmi <husnifahmi@outlook.com>
 
 `Developer`:
  - Muhamad Jumadil Akbar, S.Kom <jumadil.akbar@grit.id>
  - Irvan Rahadhian <irvan.r@grit.id>
  - Irfan Fadil <kaisa.ads88@gmail.com>
  - Ridwan Dwiki Ardiansyah <ridwan.dwiki@grit.id>
  - Irfan Fakri Ardian <irfan.fakri@grit.id>
  - Aldhiaz Fathra Daiva <dhiazfathra@gmail.com>
  - Harits Abdurrohman <iceramngl@gmail.com>

`Annotator`:
  - Panca Agung Kusuma <panca.kusuma@grit.id>
  - Hanif Razin <hanif.razin@grit.id>
  - Isnadi <isnadi24@gmail.com>
  - Suwito <suwito@grit.id>
  - Hermawan Suheri <hermawan@grit.id>
  - Taqiyuddin Fahmi <muhammadtaqi@gmail.com>
  - Ihsan Nur Kholis <ihsan.nurkholis@grit.id>
  - Aldi Alpian <aldi.alpian@grit.id>
  - Nur Rokhman <nurrokhman@grit.id>
  - Shyta Ramadhanty <shytaaramadhanty@gmail.com>
  - Abdul Hamid <amitabduls@gmail.com>
  - Antonius Rony Hidajat
  - Nur Afdal
  - Listia Apritami

  `Github Issue Reporter`:
  - Yoga Yudistira <yudistirayoga97@gmail.com>

  
Try NERGRIT at: https://ner.grit.id and visit us at https://grit.id/
