# OCR Evaluation

This project will investigate two different versions of OCR and evaluate their performance against each other
- Segmented OCR (self-trained model)
    - Naive Segmentation: Split all cells in to (60x40) images
    - Better Segmentation: Filter out empty cells to try to get individual characters in images based on a threshold

    - Trained on data from https://www.kaggle.com/datasets/harieh/ocr-dataset 

- Easy OCR (taken from https://github.com/JaidedAI/EasyOCR)
    - Prebuilt OCR model


## Sources
> 1.	Sharma, Parikshit. (2023). Advancements in OCR: A Deep Learning
> Algorithm for Enhanced Text Recognition. International Journal of Inventive Engineering and
> Sciences. 10. 1-7. 10.35940/ijies.F4263.0810823.
> https://www.researchgate.net/publication/373513855_Advancements_in_OCR_A_Deep_Learning_Algorithm_for_Enhanced_Text_Recognition 
> 2.	Artificial Intelligence - A Modern Approach (3rd Edition), Stuart Russel, Peter Norvig
> 3.	Github Project -  https://github.com/mgoldgirsh/ocr-evaluation 
> 4.	OCR-Dataset - https://www.kaggle.com/datasets/harieh/ocr-dataset 
> 5.	EasyOCR Github Repo - https://github.com/JaidedAI/EasyOCR 
