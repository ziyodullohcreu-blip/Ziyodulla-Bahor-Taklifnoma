# Ziyodulla & Bahor — Taklifnoma

Bu papka to'liq tayyor veb-sahifa: `index.html` (matn, dizayn, animatsiya, sanoq, musiqa) va `assets/calikusu-jenerik.m4a` (fon musiqasi).

## GitHub Pages orqali havola olish

1. https://github.com saytida yangi repository yarating (masalan `ziyodulla-bahor-wedding`), **Public** qilib qo'ying.
2. Ushbu papkadagi barcha fayllarni (`index.html`, `assets/`, `.nojekyll`) o'sha repoga yuklang:
   - GitHub saytida "Add file → Upload files" orqali sudrab tashlashingiz mumkin, yoki
   - Terminalda:
     ```
     cd ziyodulla-bahor-wedding
     git init
     git add .
     git commit -m "Wedding invitation"
     git branch -M main
     git remote add origin https://github.com/<username>/<repo-nomi>.git
     git push -u origin main
     ```
3. Repo ichida **Settings → Pages** bo'limiga o'ting.
4. "Source" qismida **Deploy from a branch** ni tanlang, branch — **main**, papka — **/(root)**. Save qiling.
5. Bir necha daqiqadan so'ng havolangiz tayyor bo'ladi:
   `https://<username>.github.io/<repo-nomi>/`

Shu havolani istalgan odamga yuborishingiz mumkin — telefonda ham, kompyuterda ham ochiladi.

## O'zgartirish kerak bo'lsa

- **Matn/sana/manzil** — `index.html` faylida oddiy matn sifatida yozilgan, istalgan matn muharriri (Notepad, VS Code) bilan tahrirlash mumkin.
- **Musiqa** — `assets/` papkasidagi audio faylni boshqa fayl bilan almashtirib, `index.html` ichidagi `src="assets/..."` qatorini yangi fayl nomiga o'zgartiring.
- **Sanoq (countdown)** — `index.html` oxiridagi skriptda `new Date('2026-10-10T18:00:00+05:00')` qatorini sana/vaqtga mos o'zgartiring.
