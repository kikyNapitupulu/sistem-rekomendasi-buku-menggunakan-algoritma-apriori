# Sistem Rekomendasi Buku menggunakan Algoritma Apriori

Proyek mata kuliah Penambangan Data

## Metodologi Data Mining
Sistem rekomendasi buku menggunakan algortima apriori dibuat dengan mengacu pada CRISP-DM (Cross-Industry Standard Process for Data Mining), yaitu siklus hidup pengembangan data mining yang terdiri dari 6 tahapan, yaitu : 
1. Business Understanding (Determine Business Objectives, Situation Assessment, Determine Data Mining Goal, Produce Project Plan) 
2. Data Understanding ( Collect Initial Data, Describe Data, Explore Data, Verify Data Quality)
3. Data Preparation ( Data Set Description, Select Data, Clean Data, Construct Data, Investigate Data)
4. Modeling (Select Modeling Technique, Build Model)
5. Evaluation
6. Deployment

## Dataset
Data tersedia dalam format csv dan dapat diunduh di link berikut:
http://www2.informatik.uni-freiburg.de/~cziegler/BX/

Dataset yang digunakan adalah Book-Crossing, yaitu kumpulan data buku yang dikumpulkan oleh Cai-Nicolas Ziegler dari komunitas Book Crossing dan terdiri dari 278.858 ribu data user yang disamarkan serta 1.149.780 data rating baik eksplisit maupun implisit dari 271.379 data buku. Pada dataset BookCrossing terdapat tiga tabel yaitu : 
1. BX-Books, yang terdiri dari 271360 baris dan 8 kolom, yaitu 'ISBN', 'Book-Title', 'Book-Author', 'Year-Of-Publication', 'Publisher',  'Image-URL-S', 'Image-URL-M', 'Image-URL-L'
2. BX-Users,  yang terdiri dari 278858 baris dan 3 kolom, yaitu 'User-ID', 'Location', 'Age'
3. BX-Book-Ratings, yang terdiri dari 1149780 baris dan 3 kolom, yaitu  'User-ID', 'ISBN', 'Book-Rating'




