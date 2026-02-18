# QR Menü (GitHub Pages)

Bu klasör (`docs/`) GitHub Pages için hazırdır.

## Yerelden güncelleme

1. Menü verisini dışa aktar:

```bash
python scripts/export_qr_menu.py
```

2. `docs/menu-data.json` güncellenir.

## Yayın (Domain almadan)

1. Repo'yu GitHub'a yükleyin.
2. GitHub > Settings > Pages:
Source: `Deploy from a branch`
Branch: `main`
Folder: `/docs`
3. Linkiniz şu formatta olur:
`https://KULLANICI_ADI.github.io/REPO_ADI/`

## QR hedef linki

QR koduna yukarıdaki public linki verin.
Müşteri kendi mobil verisiyle açabilir, Wi-Fi şartı olmaz.
