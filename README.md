# Dataset Pelanggan

## Deskripsi
Dataset ini berisi informasi tentang pelanggan, termasuk data demografis, perilaku pembelian, dan respons terhadap kampanye pemasaran. Dataset ini dapat digunakan untuk analisis pemasaran, segmentasi pelanggan, dan pengembangan strategi bisnis yang lebih efektif.

## Struktur Dataset

Dataset terdiri dari 40 kolom dengan informasi berikut:

| **Field**                            | **Deskripsi**                                                                                         |
|--------------------------------------|------------------------------------------------------------------------------------------------------|
| **Unnamed: 0**                       | Indeks atau nomor urut dari baris data.                                                            |
| **ID**                               | ID unik untuk setiap pelanggan.                                                                       |
| **Year_Birth**                       | Tahun kelahiran pelanggan (format: YYYY).                                                             |
| **Education**                        | Tingkat pendidikan pelanggan (contoh: "Primary", "Secondary", "Tertiary").                          |
| **Marital_Status**                   | Status perkawinan pelanggan (contoh: "Married", "Single", "Divorced").                              |
| **Income**                           | Pendapatan tahunan pelanggan (dalam mata uang yang relevan), mungkin mengandung nilai NaN.         |
| **Kidhome**                          | Jumlah anak yang tinggal di rumah pelanggan.                                                         |
| **Teenhome**                         | Jumlah remaja yang tinggal di rumah pelanggan.                                                       |
| **Dt_Customer**                      | Tanggal pelanggan bergabung (format: YYYY-MM-DD).                                                   |
| **Recency**                          | Jumlah hari sejak pelanggan terakhir melakukan pembelian (semakin kecil semakin baru).              |
| **MntCoke**                          | Total pengeluaran pelanggan untuk produk Coca-Cola selama periode yang ditentukan.                   |
| **MntFruits**                        | Total pengeluaran pelanggan untuk produk buah selama periode yang ditentukan.                        |
| **MntMeatProducts**                 | Total pengeluaran pelanggan untuk produk daging selama periode yang ditentukan.                      |
| **MntFishProducts**                 | Total pengeluaran pelanggan untuk produk ikan selama periode yang ditentukan.                        |
| **MntSweetProducts**                | Total pengeluaran pelanggan untuk produk manis selama periode yang ditentukan.                       |
| **MntGoldProds**                     | Total pengeluaran pelanggan untuk produk emas selama periode yang ditentukan.                        |
| **NumDealsPurchases**               | Jumlah pembelian yang dilakukan pelanggan dalam bentuk penawaran atau diskon.                       |
| **NumWebPurchases**                 | Jumlah pembelian yang dilakukan pelanggan secara online.                                            |
| **NumCatalogPurchases**             | Jumlah pembelian yang dilakukan pelanggan melalui katalog.                                           |
| **NumStorePurchases**               | Jumlah pembelian yang dilakukan pelanggan di toko fisik.                                            |
| **NumWebVisitsMonth**               | Jumlah kunjungan ke website perusahaan dalam sebulan terakhir.                                       |
| **AcceptedCmp3**                    | Menunjukkan apakah pelanggan menerima kampanye pemasaran 3 (0 = tidak, 1 = ya).                     |
| **AcceptedCmp4**                    | Menunjukkan apakah pelanggan menerima kampanye pemasaran 4 (0 = tidak, 1 = ya).                     |
| **AcceptedCmp5**                    | Menunjukkan apakah pelanggan menerima kampanye pemasaran 5 (0 = tidak, 1 = ya).                     |
| **AcceptedCmp1**                    | Menunjukkan apakah pelanggan menerima kampanye pemasaran 1 (0 = tidak, 1 = ya).                     |
| **AcceptedCmp2**                    | Menunjukkan apakah pelanggan menerima kampanye pemasaran 2 (0 = tidak, 1 = ya).                     |
| **Complain**                         | Menunjukkan apakah pelanggan mengajukan keluhan (0 = tidak, 1 = ya).                                 |
| **Z_CostContact**                   | Biaya kontak per pelanggan.                                                                           |
| **Z_Revenue**                       | Pendapatan yang dihasilkan dari kontak pelanggan.                                                    |
| **Response**                         | Menunjukkan apakah pelanggan merespons kampanye pemasaran (0 = tidak, 1 = ya).                      |
| **conversion_rate**                 | Tingkat konversi untuk kampanye pemasaran, mungkin mengandung nilai NaN.                            |
| **age**                              | Usia pelanggan (dihitung dari tahun kelahiran).                                                     |
| **num_children**                    | Total jumlah anak yang dimiliki pelanggan.                                                           |
| **total_spending**                  | Total pengeluaran pelanggan untuk semua kategori produk.                                             |
| **total_transactions**              | Jumlah total transaksi yang dilakukan oleh pelanggan.                                               |
| **avg_spending_per_transaction**    | Rata-rata pengeluaran per transaksi.                                                                  |
| **customer_tenure_days**            | Jumlah hari pelanggan telah menjadi pelanggan.                                                       |
| **customer_tenure_months**          | Jumlah bulan pelanggan telah menjadi pelanggan.                                                      |
| **customer_tenure_years**           | Jumlah tahun pelanggan telah menjadi pelanggan.                                                      |
| **age_group**                       | Kelompok usia pelanggan berdasarkan rentang usia (misal: "18-25", "26-35").                         |

## Penggunaan

Dataset ini dapat digunakan untuk berbagai analisis, termasuk:

- Segmentasi pelanggan berdasarkan demografi dan perilaku.
- Analisis efektivitas kampanye pemasaran.
- Prediksi perilaku pembelian di masa mendatang.
- Mengidentifikasi peluang untuk meningkatkan retensi pelanggan.

## Lisensi

[Masukkan informasi lisensi di sini, jika ada.]

## Kontak

Jika Anda memiliki pertanyaan atau masukan mengenai dataset ini, silakan hubungi [Nama Anda] di [Email Anda].
