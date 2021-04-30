# Tugas 2 (REST API) RPLBK Kelompok 2

## Anggota Kelompok
- Bagaskara Muhammad Noer   **(21120117140006)**
- Afrina Ayu Insani         **(21120118120006)**
- Bernita Febrihatin        **(21120118120023)**
- Zolan Devi Khoirunnisa    **(21120118130048)**
- Muhammad Riziq Yahya      **(21120118130058)**
- Muhammad Syahrizal Fauzi  **(21120118130066)**

## Cara Pakai
1. Clone repo ini di **xampp/htdocs** atau download lalu copy folder **api** ke **xampp/htdocs/rplbk-tugas2**.
2. Pastikan database sudah ada & tabel-tabel sudah ada (bisa diambil dari link tutorialnya).
3. Hidupkan Apache & MySQL di XAMPP.
4. Panggil masing-masing endpoint dari browser (untuk yang pakai protokol GET), Postman, atau **[extension REST Client di VS Code](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)**.

*File call.http dipakai untuk extension REST Client di VS Code*

## Endpoint
1. [**GET**] http://localhost/rplbk-tugas2/api/product/read.php
2. [**POST**] http://localhost/rplbk-tugas2/api/product/create.php
3. [**GET**] http://localhost/rplbk-tugas2/api/product/read_one.php?id=56
4. [**POST**] http://localhost/rplbk-tugas2/api/product/update.php
5. [**POST**] http://localhost/rplbk-tugas2/api/product/delete.php
6. [**GET**] http://localhost/rplbk-tugas2/api/product/search.php?s=shirt
7. [**GET**] http://localhost/rplbk-tugas2/api/product/read_paging.php
8. [**GET**] http://localhost/rplbk-tugas2/api/category/read.php
