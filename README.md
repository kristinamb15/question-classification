# Question Classification Using TREC-50 Data Set

XLNet with multilayer bidirectional GRU is trained on TREC-50 data set augmented using [Easy Data Augmentation techniques](https://arxiv.org/pdf/1901.11196.pdf).

The notebook was originally run in [Google Colab](https://colab.research.google.com/drive/1o1XaUGR--Hj0LdOdFFshaJJB-eeIeJ4c?usp=sharing) and can be viewed there by visiting the link, or viewed in [this repo](TrecClassification.ipynb).

**Language**: Python

## Files

    📦TrecClassification
    ┣ 📜.gitignore  
    ┣ 📜LICENSE.txt
    ┣ 📜README.md
    ┣ 📜TrecClassfication.ipynb        # Main notebook
    ┗ 📜TrecClassification.zip         # Files needed to run the notebook
        ┣ 📂data
        ┃ ┣ 📂processed
        ┃ ┃ ┣ 📜label_refs.csv          # Label names and descriptions
        ┃ ┃ ┣ 📜testing.csv             # Test data
        ┃ ┃ ┗ 📜training.csv            # Training data
        ┃ ┗ 📂raw                    
        ┃ ┃ ┣ 📜input.txt               # Data prepared for augmentation
        ┃ ┃ ┣ 📜eda_input.txt           # Augmented data
        ┃ ┃ ┣ 📜train_5500.txt          # Raw training data
        ┃ ┃ ┗ 📜TREC_10.txt             # Raw test data
        ┣ 📂eda                         # Scripts used for data augmentation
        ┃ ┣ 📜augment.py
        ┃ ┗ 📜eda.py
        ┣ 📂models
        ┃ ┗ 📜xlgru.pt                  # Saved model parameters

## License

Files in this project are free for appropriate use under the [MIT License](LICENSE.txt).