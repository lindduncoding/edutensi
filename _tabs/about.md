---
# the default layout is 'page'
icon: fas fa-info-circle
order: 4
authors: [author_1, author_2]
---

Website ini merupakan persembahan tim **KKN-PPM UGM II 2025 Bolo Bulukerto** kepada masyarakat **Desa Conto**, Kecamatan Bulukerto, Kabupaten Wonogiri, Provinsi Jawa Tengah, melihat tingginya kasus dan kecenderungan masyarakat mengidap penyakit hipertensi. Sebuah kolaborasi klaster medika dan saintek, diharapkan panduan ini dapat berguna bagi masyarakat sekitar. Semoga sehat selalu!

### Behind The Scene

{% for author_id in page.authors %}
{% assign author = site.data.authors[author_id] %}
- {{ author.role }}: [{{ author.name }}]({{ author.url }}) — _{{ author.prodi }}_  
{% endfor %}