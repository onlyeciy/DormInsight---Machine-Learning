# DormInsight

Sistem analisis kepuasan dan retensi penghuni asrama mahasiswa untuk membantu pengelola mengambil keputusan berbasis data.

## Language

**Retention**:
Keputusan mahasiswa untuk melanjutkan atau tidak melanjutkan masa tinggalnya di asrama pada akhir semester.
_Avoid_: churn, loyalty

**Renew**:
Keputusan mahasiswa untuk tetap tinggal di asrama pada akhir semester.
_Avoid_: stay, continue, extend

**Leave**:
Keputusan mahasiswa untuk tidak memperpanjang masa tinggalnya di asrama pada akhir semester.
_Avoid_: churn, dropout, quit

**Graduate**:
Mahasiswa yang berakhir masa studinya di kampus sehingga otomatis berhenti tinggal; bukan bagian dari label retensi.
_Avoid_: alumni, lulusan

**Decision Point**:
Satu-satunya titik waktu ketika keputusan retensi terjadi — akhir semester. Penghuni tidak dapat keluar di tengah semester.
_Await_: exit date, termination

**Penghuni**:
Mahasiswa yang sedang menempati kamar asrama pada suatu semester.
_Avoid_: resident, occupant, user

**Satisfaction**:
Penilaian penghuni terhadap kualitas asrama, diukur per dimensi: fasilitas kamar, kebersihan, keamanan, pelayanan pengelola, dan lingkungan sosial.
_Avoid_: happiness, sentiment
