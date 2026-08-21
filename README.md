# E-Commerce Customer Churn Analysis
Project ini dibuat mengikuti guideline Portfolio Building dengan use case **E-Commerce Customers Churn Analysis**.

## Business Goal
Membantu Customer Retention / CRM Manager mengidentifikasi segmen pelanggan dengan churn tinggi dan menentukan prioritas tindakan retensi.

## KPI
- Total Customers: **5,630**
- Churned Customers: **948**
- Churn Rate: **16.84%**
- Retained Customers: **4,682**
- Complaint Rate: **28.49%**
- Average Tenure: **10.1 months**

## Data Cleaning
- `Phone` disatukan menjadi `Mobile Phone`.
- `CC` disatukan menjadi `Credit Card`.
- `COD` disatukan menjadi `Cash on Delivery`.
- Kategori order `Mobile` disatukan menjadi `Mobile Phone`.
- Missing values numerik diimputasi menggunakan median keseluruhan.
- Ditambahkan band untuk tenure, jarak gudang, recency, order count, dan cashback.

## Key Insights
1. Tenure 0–3 bulan memiliki churn rate **41.86%**.
2. Pelanggan yang mengajukan keluhan memiliki churn rate **32%**, tanpa keluhan **11%**
3. Pelanggan tenure 0–3 bulan yang juga mengajukan keluhan memiliki churn rate **66%**.
4. Kategori Mobile Phone memiliki churn rate **27%**.
5. COD dan E-wallet menunjukkan churn di atas rata-rata.

## Rekomendasi Bisnis
1. Program **First 90 days Retention**
2. Menetapkan **Complaint Recovery SLA**
3. Kampanye Khusus Pelanggan **Mobile Phone** serta Pengguna **COD** dan **E-wallet**
4. Pengujian Bertahap **Insentif Cashback**

## Dataset
- `Data Dict` — data dictionary dari tabel transaksi `E Comm`
- `E Comm` — tabel transaksi data mentah
- `E Comm Data Clean` — transaksi data yang sudah clean
- `Google Spreadseet:` https://docs.google.com/spreadsheets/d/1c0iWgc9cxCr4g1RK4YBPFVegQIHwLVYoBZ2vOoj78Wo/edit?gid=1642457125#gid=1642457125

## Dashboard
- `Tableau Public:` https://public.tableau.com/app/profile/michael.heydemans/viz/Purwadhika-ECommerceDashboard/DashboardChurn

## Dashboard
- `Link Video:` https://youtu.be/PMPuacuKntM

