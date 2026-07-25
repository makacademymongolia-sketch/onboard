MAK ШИНЭ АЖИЛТНЫ ПОРТАЛ — GITHUB + NETLIFY + ADMIN

ӨНГӨНИЙ ПАЛИТР:
#2F98C1 / #8CD3E9 / #C2E7F3 / #F99E23 / #F58220 / #F15B2F

1. ZIP файлыг компьютертээ задлана.
2. GitHub дахь mak-onboarding repository руу орно.
3. Add file → Upload files дарна.
4. Задалсан хавтасны ДОТОРХ бүх файл, хавтсыг repository-ийн үндсэн хэсэгт upload хийнэ.
   index.html, assets, admin, content, netlify.toml
5. Commit changes дарна.
6. Netlify → Add new project → Import an existing project → GitHub.
7. mak-onboarding repository-г сонгоод Deploy дарна.
   Build command: хоосон
   Publish directory: .
8. Netlify → Project configuration → Identity → Enable Identity.
9. Registration preferences → Invite only.
10. Identity → Services → Git Gateway → Enable Git Gateway.
11. Identity → Invite users → өөрийн имэйл хаягийг оруулна.
12. Имэйлээр ирсэн урилгыг нээгээд нууц үг үүсгэнэ.
13. https://ТАНЫ-САЙТ.netlify.app/admin/ руу орж мэдээллээ засна.
14. Save / Publish дарсны дараа GitHub-д commit үүсэж Netlify автоматаар шинэчилнэ.

МЭДЭЭЛЭЛ ЗАСАХ:
- /admin/ → Сайтын мэдээлэл → Үндсэн мэдээлэл
- Hero зураг, текст, статистик, эхний өдрийн хөтөлбөр, системийн холбоос, FAQ, имэйл бүгд засагдана.
- Зураг upload хийхэд assets/uploads дотор хадгалагдана.

АНХААРАХ:
- ZIP файлыг шууд GitHub руу upload хийхгүй; заавал задлаад доторх файлуудыг оруулна.
- Repository public бол нууц үг, token, дотоод нууц мэдээлэл бүү хадгал.
- LMS болон SharePoint холбоосыг /admin/ хэсгээс баталгаатай URL-аар солино.
