# Analisis-Order-Customer---Data-Analysis
# Business Insight
Data Analyst
Retail Operations & Margin Leakage Analysis
Proyek ini membedah inefisiensi margin pada operasional ritel melalui end-to-end data pipeline. Analisis ini membongkar ilusi omset jutaan dolar yang menyembunyikan 40% rasio kerugian absolut pada level transaksi, serta merumuskan rekomendasi perbaikan struktur harga pokok.

--$Tech Stack & Workflow:

Python (Pandas): Data Wrangling untuk pembersihan format tanggal dan penanganan anomali ship_mode, dilanjutkan dengan Feature Engineering untuk membangun matriks finansial (Net Sales, Total Cost, Gross Profit).

Power BI: Visualisasi diagnostik menggunakan Bivariate Analysis, deteksi outlier via Scatter Plot, dan kalkulasi row-level otomatis menggunakan Measure DAX.

--$Key Executive Findings:

The 40% Margin Bleed: 40% dari total aktivitas transaksi perusahaan beroperasi di bawah titik impas (menghasilkan Gross Profit negatif). Kebocoran ini didominasi oleh segmen pasar Consumer.

The 5% Discount Cliff: Beban Harga Pokok Penjualan (HPP) mematikan ruang margin perusahaan. Subsidi diskon sekecil 2% hingga 5% langsung menyeret transaksi ke area kerugian absolut.

B2B Subsidy Trap: Margin rata-rata perusahaan sebesar ~9% tidak didorong oleh efisiensi sistemik, melainkan diselamatkan secara artifisial oleh segelintir transaksi skala raksasa (Whales) dari klien korporat (Corporate & Home Office).

--$Actionable Insights:

Pembekuan kampanye diskon berbasis persentase langsung untuk pasar B2C.

Transisi menuju strategi Product Bundling dan penerapan Minimum Order Quantity (MOQ).

Renegosiasi HPP (Cost Price) secara menyeluruh dengan pihak supplier untuk menambal inefisiensi sistemik.
