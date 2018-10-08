# commands
İlk defa vue-cli kurmak için
Npm install –g vue-cli

Yeni proje eklemek
vue init webpack-simple vue-notam
tüm sorulara enter son soruya n cevaplanır.
cd vue-notam
npm install
npm run dev

git repo ya eklemek
github.com da repo oluşturulur.
git init

git add *
git commit -m "My First Commit"

git remote add origin https://github.com/barlsym/vue-notam

git push -u origin master

NOT:
Remote’ları listeleme
git remote –v

remote silme
git remote rm origin  

“[rejected]        master -> master (fetch first)” hatası alınıyorsa. Remote’taki reponun yerine lokaldeki dosyaları kullanmak için
git push -u –force origin master


git pull origin master  (update)
git push origin master  (staged statüsündeki değişiklikleri push(server a commit))
git commit -m "deneme mesajı" (staged statüsündeki değişiklikleri commit(yerel bilgisayara))

git status (staged yapılmamış değişiklikleri göster)

git commit -a -m "deneme mesajı" (staged statüsündeki değişiklikleri staged yap ve commit)

git GUI kullanılarakta stage commit push yapılabilir.

Since git is a distributed version control system, the difference is that commit will commit changes to your local repository, whereas push will push changes up to a remote repo. git commit record your changes to the local repository. git push update the remote repository with your local changes.

Git komut satırı eski bir kullanıcı ile işlem yapıyorsa “Control Panel\User Accounts\Credential Manager Generic Credentials” den github i sil.

