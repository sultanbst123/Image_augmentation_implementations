# Image_augmentation_implementations
Augmentasi citra(image augmentation) adalah teknik mengubah data yang ada untuk membuat beberapa data lagi untuk proses pelatihan model.

<p align="center">
 <img src="https://github.com/sultanbst123/Image_augmentation_implementations/blob/main/download.png"> 
</p>

## CutMix Augmentation
<p align="center">
 <img src="https://github.com/sultanbst123/Image_augmentation_implementations/blob/main/Cutmix.png"> 
</p>

CutMix adalah teknik augmentasi data yang membahas masalah hilangnya informasi dan ketidakefisienan yang ada dalam strategi putus sekolah regional. Alih-alih menghapus piksel dan mengisinya dengan piksel hitam atau abu-abu atau derau Gaussian, Anda mengganti bagian yang dihapus dengan tambalan dari gambar lain, sementara label kebenaran dasar dicampur secara proporsional dengan jumlah piksel gambar gabungan.

untuk lebih lanjut silahkan liat paper. 
Paper: <p><a href="https://arxiv.org/pdf/1905.04899"> CutMix: Regularization Strategy to Train Strong Classifiers with Localizable Features</a> [Yun et al., 2019]</p>

## MixUp Augmentation
<p align="center">
 <img src="https://github.com/sultanbst123/Image_augmentation_implementations/blob/main/Mixup.png"> 
</p>

Mixup adalah teknik augmentasi data Domain-agnostik, Teknik ini dinamai secara sistematis - kami benar-benar mencampurkan fitur dan label yang sesuai. Implementasi-bijaksana itu sederhana. Jaringan saraf rentan untuk menghafal label yang korup . mixup melonggarkan ini dengan menggabungkan fitur yang berbeda satu sama lain (hal yang sama juga terjadi pada label) sehingga jaringan tidak terlalu percaya diri tentang hubungan antara fitur dan labelnya.
Mixup secara khusus berguna ketika kami tidak yakin tentang memilih satu set transformasi augmentasi untuk set data tertentu, set data pencitraan medis, misalnya. mixup dapat diperluas ke berbagai modalitas data seperti visi komputer, pemrosesan bahasa alami, ucapan, dan sebagainya.

untuk lebih lanjut silahkan liat paper. 
Paper: <p><a href="https://arxiv.org/pdf/1905.04899"> mixup: Beyond Empiris Risk Minimization</a> [Zhang et al., 2017]</p>

## Referensi
- Google

