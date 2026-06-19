# Intel Image Classification Project
## Deskripsi
Proyek klasifikasi gambar menggunakan dataset Intel Image Classification
dengan 6 kelas: buildings, forest, glacier, mountain, sea, street.

## Arsitektur
- Base model : [EfficientNetB0](https://keras.io/api/applications/efficientnet/efficientnet_models/#efficientnetb0-function)
- Fine-tuning : 50 layer terakhir di-unfreeze
- Input shape : 224x224×3
- Output      : 6 kelas (softmax)

## Performa
- Train accuracy : 97.85%
- Test accuracy  : 93.28%

## Format Model
- SavedModel : untuk deployment server
- TF-Lite    : untuk mobile & embedded
- TFJS       : untuk browser

## Alur Kerja Project
- Buka Colab dengan T4 GPU
- Run All atau Run tiap cell untuk modifikasi serta eksplorasi output tiap cell
- upload kaggle.json untuk akses dan download data
- Lanjutkan Run cell dan lakukan tuning hyperparameter dan aristektur model

## Contact
- **Nama:** Wisnu Anugrah Pratama
- **Email:** wisnuanugrahpratama@gmail.com
