# Minggu 3: Linear Regression - Predicting House Prices 🏠

## Tujuan Pembelajaran
1. Memahami konsep dasar Regresi Linear Sederhana dan Berganda.
2. Mengimplementasikan model menggunakan **Scikit-Learn**.
3. Melakukan evaluasi model menggunakan metrik **MAE**, **MSE**, dan **RMSE**.
4. Melacak eksperimen regresi menggunakan **W&B**.

## Konsep Matematika
Regresi Linear mencoba mencari garis lurus terbaik yang menghubungkan antara fitur ($x$) dan target ($y$). Persamaannya adalah:
$$y = wx + b$$

Di mana:
- $y$: Target (Harga Rumah)
- $x$: Fitur (Misal: Luas Tanah)
- $w$: Weight/Slope (Bobot)
- $b$: Bias/Intercept

## Metrik Evaluasi
Untuk mengetahui seberapa akurat prediksi kita, kita menggunakan:
1. **Mean Absolute Error (MAE):** Rata-rata selisih absolut antara prediksi dan nilai asli.
2. **Mean Squared Error (MSE):** Rata-rata selisih kuadrat (memberikan penalti lebih besar pada error besar).
3. **Root Mean Squared Error (RMSE):** Akar dari MSE agar satuannya kembali sama dengan unit target.
