# DPR RI Dashboard (2024–2029)
s.d 13 Mei 2025

Dashboard interaktif yang menyajikan visualisasi profil lengkap anggota DPR RI periode 2024–2029, berdasarkan data yang diperoleh melalui scraping dari situs Wikipedia.

## Fitur Dashboard
- Distribusi anggota berdasarkan:
  - Jenis Kelamin
  - Fraksi/Partai Politik
  - Komisi
  - Daerah Pemilihan (Dapil)
  - Koalisi Pemerintah vs Oposisi (*Bisa berubah sepanjang waktu)
  - Tampilan visual dinamis menggunakan Looker Studio

## Pratinjau Dashboard
Lihat dashboard: (https://lookerstudio.google.com/reporting/bafcd2b1-465f-40fa-a79f-a039dc1fbd49)


## Teknologi yang Digunakan

- `Python` (Jupyter Lab)
- Library: `requests`, `BeautifulSoup`, `pandas`
- Google Sheets
- Visualisasi: `Looker Studio`

## License
MIT License

Copyright (c) [2025] [Faiz Maulida]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## 💡 Catatan
- Proses pembersihan data mempertimbangkan konsistensi nama, jabatan, dan keterisian kolom antar sumber data.
- Dashboard ditujukan sebagai referensi visual cepat, bukan sebagai data resmi yang final.



