# Scene-Detection
A Neural network model (CNN &amp; RNN) to determine the contents of an image and describe accordingly

I would like to thank Yunjey for this amazing tutorial on Pytorch. 

# Technology Stack 
- Python <br />
- Pytorch <br />
- CNN (image based model) & RNN (Resner 152 - Language based model)

# Running the project 

## 1. Clone the repositories
  - git clone https://github.com/pdollar/coco.git
  - cd coco/PythonAPI/
  - make
  - python setup.py build
  - python setup.py install
  - cd ../../
  - git clone https://github.com/kaushik618/Scene-Detection/
  
## 2. Download the dataset
  - pip install -r requirements.txt
  - chmod +x download.sh
  - ./download.sh
  
## 3. Preprocessing
- python build_vocab.py   
- python resize.py  

## 4. Train the model
- python train.py    

## 5. Test the model
- python sample.py --image='png/example.png'
