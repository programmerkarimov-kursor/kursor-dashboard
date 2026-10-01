# Kursor Vakansiya Statistikası

Bu repoda olan `vacancies_dashboard.html` faylı — Azərbaycan əmək bazarının
(boss.az, jobs.glorri.com, Kapital Bank, ABB, jobsearch.az mənbələrindən
yığılmış 4419 real iş elanı, 5 mənbə) tam hazır, özünəbəs (self-contained)
HTML/CSS/vanilla-JS dashboard-udur. Bütün data faylın içinə JSON kimi daxil
edilib (xarici DB/API çağırışı yoxdur, offline açıla bilər).

## Prompt — Artifact yaratmaq üçün

Aşağıdakı promptu Claude-a ver (bu repo-ya girişi olan sessiyada):

---

Bu repodakı `vacancies_dashboard.html` faylını oxu və onun tam məzmununu
(HTML+CSS+JS, daxilindəki JSON data daxil olmaqla, heç nəyi dəyişmədən və
qısaltmadan) **"Kursor Vakansiya Statistikası"** adlı bir Artifact kimi yarat.

Bu fayl artıq tam hazır və test edilmiş bir dashboard-dur:
- Yuxarıda ümumi statistika (say + mənbə/sektor bölgüsü, həm rəqəm, həm
  horizontal bar chart)
- Axtarış paneli (sinonim-əsaslı "ağıllı axtarış" — LLM deyil, keyword
  genişləndirmə)
- Sektor və mənbə üzrə filtrlər (dinamik, datadan qurulur)
- Axtarış/filtr nəticələrinə görə yenidən qurulan sektor qrafiki
- Kart grid (səhifələnmiş, "Daha çox göstər" düyməsi ilə)
- Kart üzərinə kliklə tam detal modalı (bütün sahələr + tam tələblər mətni)
- İşıq/qaranlıq rejim keçidi

Artifact-ı yaradarkən faylın məzmununu olduğu kimi render et (iframe/html
tipli artifact) — koddan hər hansı hissəni yenidən yazma və ya
sadələşdirmə, çünki artıq işlək və test edilib.

---

## Fayl

- `vacancies_dashboard.html` — tam dashboard (7.8MB, 4419 vakansiya)
