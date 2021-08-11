# Glauco-scan

Glauco-scan is part of our work in an internal event 'Hackathon Penelitian Teknik Biomedis 2021' held by Department of Electrical Engineering and Technological Information, University of Gadjah Mada. Our team called 'GumiGummy' consisted of myself (Kayla Queenazima S), Arin Yusianti, Hilmi Arisanti R, and Priscillia Sonia Putri L from Biomedical Engineering, UGM. We built Glauco-Scan as a simple and goto web-app to easily process OCT scan result and show the segmentation result of cup and disc, the Cup to Disc Ratio (CDR), prediction of Glaucoma, and QR code result so user can save easily the results. We built this project in 2 weeks and helped by the mentors from the department.

# Segmentation Process
Built in from the project of [Seva](https://github.com/seva100/optic-nerve-cnn), we use the same dataset as him but using [Segmentation API](https://segmentation-models.readthedocs.io/en/latest/api.html) to built the architecture of Unet with transfer learning of EfficientNet

# Cup-to-Disc Ratio Calculation
The CDR calculation editted from [Nupur Bhaisare's work](https://github.com/NupurBhaisare/Cup-and-disc-segmentation-for-glaucoma-detection-CDR-Calculation-)

# Prediction of Glaucoma
From the CDR result, based on dataset CDR in [kaggle](https://www.kaggle.com/sshikamaru/glaucoma-detection), we built algorithm to classify glaucoma using SVM 
