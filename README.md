# git-fundamentals

|Terim| Açıklama|
|---|---|
| Push| Yukarıya veri gönderme|
| Pull| Yukarıdan veri çekme|
| commit|  |
| branch|  |
| `git add` ve `git commit -a` farkı|  |

### Sıfırdan Mevcut kodları yeni oluşturulan repository'e gönderme
 - `git init .` -> .git klasörü oluşturmak için
 - `git remote add origin git@git...com:.......git` -> Oluşturulmuş olan repository'i oluşturduğumuz .git'e vermek
 - `git add .` -> Yeni oluşturulmuş dosyaları commit için eklemek
 - `git status` -> Canlıdaki veri ile şuanki yaptığımız değişiklikleri gözden geçirme
 - `git commit -m "Initial Commit"` -> commit'imizi hazırlama
 - `git push -u origin master` -> master branch'ına değişiklikleri gönderme

### Var olan projeyi yukarı gönderme (PUSH işlemi)
- `git status`
- `git add .` -> Eğer yeni dosyalar mevcut ise
- `git commit -a -m "Commit mesajı"` -> Değişiklikleri push için eklemek ve commit mesajı oluşturma
- `git push origin master` | `git push origin` | `git push` -> Direkt birincil branch'ına gönderme
- `git push origin master:dev` -> Yeni branch'a gönderme (örnekte yeni bnrach ismi `dev` olarak belirtildi)

### Yukarıda olan projenin güncel halini çekme (PULL işlemi)
- `git status`
- `git pull`

### Yapılan değişikleri geri alma
- `git reset HEAD --hard`

### 
##
