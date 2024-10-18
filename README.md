# Final Project - Computer Vision - Leandro Salvañá

## Report
The project report is located in the file:
`Final Project Report - Computer Vision - Leandro Salvañá.pdf`

## Notebooks

- `00.run_envido.ipynb` - Code for inference on the evaluation dataset and JSON creation.
- `1_DatasetPersonal.ipynb` - Dataset cleaning, processing, augmentation, and splitting.
- `2_Entrenamiento.ipynb` - First training, optimization, and second training.
- `Inferencia_GPU.ipynb` - Inference on GPU.

## Usage
Place your annotated data into the `Data` directory in a directory called `Dataset` with YOLO format and run the `1_DatasetPersonal.ipynb` and `2_Entrenamiento.ipynb` notebooks.


## Project Directory Structure

├── Data  
│   ├── Dataset  
│   ├── Splitted_Dataset  
│   │   ├── test  
│   │   │   ├── images  
│   │   │   └── labels  
│   │   ├── train  
│   │   │   ├── images  
│   │   │   └── labels  
│   │   └── val  
│   │       ├── images  
│   │       └── labels  
│   ├── eval  
│   │   ├── images  
│   │   │   ├── train  
│   │   │   └── val  
│   │   └── labels  
│   │       ├── train  
│   │       └── val  
│   └── label_errors  
├── Results  
│   ├── Envido  
│   │   └── leandro_salvañá  
│   ├── checkpoints  
│   ├── test_results  
│   ├── yolov8_retraining  
│   │   └── weights  
│   └── yolov8_training  
│       ├── checkpoints  
│       └── weights  
└── model  
    └── weights  

### Directory Descriptions

- **Data/Dataset**: Contains the original dataset.
- **Data/Splitted_Dataset**: Contains the dataset after processing, augmentation, and splitting.
- **Data/eval**: Structure provided by the instructors for evaluation.
- **Data/label_errors**: Images detected with annotation errors during dataset processing.
- **Results**: Contains all the images and metric documents from the trainings.
- **Results/yolov8_training**: Files related to the first training.
- **Results/yolov8_retraining**: Files related to the second training.
- **Results/Envido**: Results from the evaluation notebook where the JSON is created.
- **model/weights**: Copy of the best weights from the second training.
