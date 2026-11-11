# Security Policy

KopiKita adalah aplikasi latihan yang **sengaja dibuat rentan** untuk pelatihan. Jangan deploy ke produksi.

## Supported Versions

| Versi / branch | Menerima perbaikan keamanan |
| --- | --- |
| `main` | ✅ |
| `lab/*-start`, `lab/*-solution` | ✅ (hanya perbaikan pada materi lab) |
| Fork dan branch `kerja/*` peserta | ❌ |

## Reporting a Vulnerability

Laporkan kerentanan lewat **Private vulnerability reporting** GitHub:
tab **Security → Report a vulnerability** di repo ini.

**Jangan** membuka issue publik, pull request, atau diskusi untuk kerentanan yang belum diperbaiki.

Sertakan:

- Deskripsi singkat dan dampak.
- Berkas, endpoint, atau komponen yang terdampak.
- Langkah reproduksi atau proof of concept.
- Usulan perbaikan (opsional).

## Response Timeline

| Tahap | Target |
| --- | --- |
| Konfirmasi laporan diterima | 2 hari kerja |
| Triase dan penetapan severity | 5 hari kerja |
| Perbaikan Critical / High | 14 hari kalender |
| Perbaikan Medium / Low | Rilis terjadwal berikutnya |

Pelapor akan diberi kabar di setiap tahap dan dicantumkan namanya di advisory bila bersedia.
