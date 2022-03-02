# Datawarehouse Data Model
![Homework 20 - Data Warehouse Model](https://user-images.githubusercontent.com/80464258/156370314-9b32725c-4c44-4703-853b-5f50db0a9190.png)

Skema ini dipilih karena mampu menjawab kebutuhan dari tim bisnis, diantaranya yaitu:
1. Bisa menarik data transaksi per product per bulan dari hasil join fact_transaksi dengan dim_produk dan dim_date
2. Bisa mendapatkan data user yang esensial seperti nama, email, nomor hp, hingga alamat dari dim_users
3. Bisa melihat list product, harga, serta kategori produk tersebut dari dim_produk
4. Bisa melakukan profiling geographic dari user Storepedia.com dari hasil join dim_user, dim_kota, dim_provinsi, dan dim_negara
