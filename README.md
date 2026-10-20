# Dashboard BI - UTS Business Intelligence (TIF46212)

Aplikasi Flask: EDA, Preprocessing, Apriori, K-Means, dan Dashboard BI.

## Jalankan lokal
```bash
pip install -r requirements.txt
python uts_bi.py
# buka http://127.0.0.1:5000
```

## Deploy ke Render
- Build command : `pip install -r requirements.txt`
- Start command : `gunicorn uts_bi:app --workers 1 --threads 4 --timeout 300`
- Health check  : `/healthz`
- Environment   : `PYTHON_VERSION=3.11.9`, `SECRET_KEY` (acak), `APP_USER`, `APP_PASSWORD`

## Cara pakai
Login -> unggah `P8__UTS_Business_Intelligence.xlsx` -> buka Dashboard.
Foto cover: taruh `foto.jpg` / `foto.png` di folder yang sama dengan `uts_bi.py`.
