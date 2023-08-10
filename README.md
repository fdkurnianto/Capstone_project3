🏦 **BANK MARKETING CAMPAIGN CLASSIFICATION**
#### **Problem Statement**

##### **Context**
   Sebuah bank ingin menambah valuasi mereka melalui campaign untuk program deposito. Namun selama ini, untuk mencari kandidat nasabah yang berpotensi ingin membuka rekening deposito dan tidak cara mencarinya masih menggunakan metode manual. Bank ingin mengetahui seorang nasabah yang benar-benar berpotensi untuk diberikan campaign program deposito. Dengan diketahuinya kandidat nasabah tersebut, bank akan menghemat biaya marketing serta bisa meningkatkan efisensi waktu.

##### **Stakeholder** 
   - Bank's Marketing Manager 
   - Bank's Marketing Team.

##### **Problem**
   
   Permasalahan dari analisis ini terkait deposito nasabah. Deposito merupakan salah satu produk dari bank di mana nasabah akan menyimpan uangnya di bank, namun untuk mencairkannya harus sesuai dengan jangka waktu yang telah ditentukan di awal. Sebagai konsekuensinya, nasabah akan mendapatkan bunga yang dilihat dari total uang yang didepositokan

   Sebagai lembaga keuangan, bank tidak boleh kehilangan nasabah deposito karena dapat mengurangi aset pada bank. Selain itu, bank juga harus mencari nasabah lain untuk membuka rekening deposito. Ketika jumlah saldo deposito meningkat, maka meningkatkan juga nominal pinjaman yang dapat diberikan kepada nasabah. Dan bank akan mendapatkan keuntungan dari bunga pinjaman tersebut. Sehingga dapat dikatakan ketika saldo deposito meningkat juga dapat meningkatkan keuntungan dari bank.
   
   Untuk sampai saat ini, pihak bank masih menilai secara manual akan nasabah yang diprediksi ingin membuka rekening deposito dan tidak ingin membuka rekening deposito. Misalkan ada total sebuah bank memiliki nasabah sejumlah 100.000 orang, dengan penilaian manual maka akan cenderung meningkatkan subjektivitas dikarenakan keterbatasan jumlah sdm. Selain itu, metode manual juga riskan terhadap kesalahan prediksi. Dan jika masih menggunakan metode manual untuk memprediksi, jika dalam satu bank hanya memiliki 20 orang marketing dan dalam 1 harinya secara efektif bisa menemukan lalu menghubungi 10 orang nasabah yang berpotensi maka akan membutuhkan waktu 500 hari. Maka dari analisis ini, pihak bank ingin mencari kategori kandidat calon nasabah yang diprediksi ingin membuka rekening deposito.
   
------------

    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third-party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- Documentation of project
    │
    ├── notebooks          <- Jupyter notebooks. The naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1-0-bank-marketing-campaign-classification`.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results-oriented visualizations
    │       └── visualize.py
    │
    └── references         <- Data dictionaries https://drive.google.com/drive/folders/13lrEDlKfnTPNREfGLBaYGYf8dSjHBzfW , https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset


--------
