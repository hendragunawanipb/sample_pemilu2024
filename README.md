# sample_pemilu2024

***Disclaimer:***


*   Sample Data diambil berdasarkan format API SIREKAP pada 16/02/2024 (dikarenakan format bisa berubah/diubah oleh pihak KPU)

*   Sample Data diambil berdasarkan format API URL sebagai berikut
format
  ```
  https://sirekap-obj-data.kpu.go.id/pemilu/hhcw/ppwp/[TINGKAT1]/[TINGKAT2]/[TINGKAT3]/[TINGKAT4]/[TINGKAT5].json
  ```
  contoh:

  https://sirekap-obj-data.kpu.go.id/pemilu/hhcw/ppwp/31/3101/310101/3101011001/3101011001001.json

  KODE masing-masing tingkat
  *   TINGKAT1 : 31 = DKI JAKARTA
  *   TINGKAT2 : 3101 = ADM. KEP. SERIBU
  *   TINGKAT3 : 310101 = KEPULAUAN SERIBU UTARA
  *   TINGKAT4 : 3101011001 = PULAU PANGGANG
  *   TINGKAT5 : 3101011001001 = TPS 001

* Nomer Calon Presiden sesuai format berikut
  * 100025 = 01 = H. ANIES RASYID BASWEDAN, Ph.D. - Dr. (H.C.) H. A. MUHAIMIN ISKANDAR
  * 100026 = 02 = H. PRABOWO SUBIANTO - GIBRAN RAKABUMING RAKA
  * 100027 = 03 = H. GANJAR PRANOWO, S.H., M.I.P. - Prof. Dr. H. M. MAHFUD MD

```json
{
    "100025": {
        "ts": "2024-02-14 18:44:00",
        "nama": "H. ANIES RASYID BASWEDAN, Ph.D. - Dr. (H.C.) H. A. MUHAIMIN ISKANDAR",
        "warna": "#8CB9BD",
        "nomor_urut": 1
    },
    "100026": {
        "ts": "2024-02-14 18:44:00",
        "nama": "H. PRABOWO SUBIANTO - GIBRAN RAKABUMING RAKA",
        "warna": "#C7B7A3",
        "nomor_urut": 2
    },
    "100027": {
        "ts": "2024-02-14 18:44:00",
        "nama": "H. GANJAR PRANOWO, S.H., M.I.P. - Prof. Dr. H. M. MAHFUD MD",
        "warna": "#B67352",
        "nomor_urut": 3
    }
}
```






