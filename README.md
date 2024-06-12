# Real estate price predictor using ViT and XGBoost

This project started from using XGBoost model for predicting price of flats.
Data for this version is provided from webscrapping real estate agent website.

### Steps
1. [Scrap all data from each active real estate offer. This is for tabular data and photos.](1_webscrapper.ipynb)
2. [Clean data from useless information.](2_data_cleansing.ipynb)
3. [Cleaned data prune from additional info for model input](3_prune_for_training.ipynb)

# Citation
1. "Real Estate Property Valuation using Self-Supervised Vision Transformers"
by **Mahdieh Yazdani, Maziar Raissi** [2023] [10.48550/arXiv.2302.00117](
https://doi.org/10.48550/arXiv.2302.00117)
2. "DINOv2: Learning Robust Visual Features without Supervision" by **Maxime Oquab, Timothée Darcet, Théo Moutakanni, Huy Vo, Marc Szafraniec, Vasil Khalidov, Pierre Fernandez, Daniel Haziza, Francisco Massa, Alaaeldin El-Nouby, Mahmoud Assran, Nicolas Ballas, Wojciech Galuba, Russell Howes, Po-Yao Huang, Shang-Wen Li, Ishan Misra, Michael Rabbat, Vasu Sharma, Gabriel Synnaeve, Hu Xu, Hervé Jegou, Julien Mairal, Patrick Labatut, Armand Joulin, Piotr Bojanowski** [2023] [10.48550/arXiv.2304.07193](https://doi.org/10.48550/arXiv.2304.07193)