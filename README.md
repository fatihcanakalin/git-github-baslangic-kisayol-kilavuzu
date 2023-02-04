# Git and Github Cheat Sheet

## Git Komutları

**git init:** Yeni bir Git reposunu başlatır

**git clone [repo_url]:** Var olan bir repoyu local makinene klonlar

**git status:** Reponun durumunu kontrol eder ve hangi dosyaların değiştirildiğini görür

**git add [file]:** Dosyayı commit için hazırlar

**git commit -m "[message]":** Hazırlanan değişiklikleri mesajla birlikte kaydeder

**git diff:** Çalışma dizinindeki ve son commit arasındaki farklılıkları görür

**git log:** Tüm önceki commitlerin günlüğünü görür

**git branch [branch_name]:** Yeni bir branch oluşturur

**git checkout [branch_name]:** Farklı bir branch'e geçer

**git merge [branch_name]:** Branch'i geçerli branch'e birleştirir

**git pull:** Uzak repodan değişiklikleri getirir ve birleştirir

**git push [remote_name] [branch_name]:** Lokal branch'daki değişiklikleri uzak repoya yollar

## Github Komutları

**git push [remote_name] [branch_name]:** Lokal branch'daki değişiklikleri Github reposuna yollar

**git pull [remote_name] [branch_name]:** Github reposundan değişiklikleri lokal branch'e getirir ve birleştirir

**git fork:** Github reposunun kendi hesabınızdaki bir kopyasını oluşturur

**git clone [repo_url]:** Github reposunu local makinene klonlar

## Git ve Github Terimleri

- **Repo:** Git tarafından izlenen dosya ve dizinlerin bir koleksiyonu.

- **Commit:** Git reposundaki kaydedilmiş değişikliklerin bir seti.

- **Branch:** Aynı projeyi aynı anda birden çok kişinin çalışmasına izin veren kod tabanının ayrı bir versiyonu.

- **Remote:** Uzak sunucuda barındırılan repo versiyonu, örneğin Github.

- **Fork:** Orijinal repoyu etkilemeden değişiklik yapabileceğiniz kendi Github hesabınızdaki bir repo kopyası.

- **Pull request:** Bir branch'deki değişikliklerin başka bir branch'e (örneğin master branch'e) birleştirilmesi için bir istek.

## Git İş Akışı

1. `git init`: Bu komut ile, yerel makinenizde yeni bir Git reposu başlatabilirsiniz.

2. `git clone [repo_url]`:Bu komut ile, Github gibi bir platformdaki bir depoyu yerel makinenize klonlayabilirsiniz.

3. `git add [file]`: Bu komut, değiştirdiğiniz bir dosyayı commit için hazırlar.

4. `git commit -m "[message]"`: Hazırlanan dosyaları mesaj ile birlikte kaydedin.

5. `git push [remote_name] [branch_name]`: Yerel branchdaki değişiklikleri Github gibi bir uzak repoya yollayın.

6. `git pull [remote_name] [branch_name]`: Github gibi bir uzak repodan değişiklikleri yerel branch'e getirin ve birleştirin.

7. `git branch[branch_name]`: Bu komut ile, aynı projede birden fazla yapılacak iş için farklı bir branch oluşturun.

8. `git checkout [branch_name]`: Bu komut ile, farklı bir branch'e geçin ve orada çalışın.

9. `git merge [brach_name]`: Bu komut ile, branch'i geçerli branch'e birleştirin.

10. `git log`: Bu komut ile, tüm önceki commitlerin günlüğünü görün.


***Bu temel Git komutları ile, yerel makinenizdeki dosyaları uzak bir depoya yollayabilecek ve uzak depodaki değişiklikleri yerel makinenize getirebileceksiniz.***

## GitHub Terminolojisi

1. `Repository (Depo)`: Bir projenin tüm dosyaları ve tarihçesi için yer sağlar.

2. `Branch (Dal)`: Aynı projede birden fazla çalışma yapmak isteyebileceğiniz dallardır.

3. `Commit (Kaydetme)`: Dosyalardaki değişiklikleri mesaj ile birlikte kaydetmek için kullanılan işlem.

4. `Push (Yolla)`: Yerel makinenizdeki değişiklikleri uzak repoya yollamak için kullanılan işlem.

5. `Pull (Çek)`: Uzak repodaki değişiklikleri yerel makinenize getirmek için kullanılan işlem.

6. `Clone (Klonla)`: Uzak repoyu yerel makinenize kopyalamak için kullanılan işlem.

7. `Fork (Çatalla)`: Başka bir kullanıcının reposunu kendi Github hesabınıza kopyalamak için kullanılan işlem.

8. `Pull Request (Çekme İsteği)`: Başka bir kullanıcının reposunda yapmış olduğunuz değişiklikleri onlarla paylaşmak için gönderdiğiniz istek.

9. `Merge (Birleştir)`: İki branch'in birleştirilmesi işlemi.

***Bu terimlerle, GitHub platformunda projelerinizi nasıl yönetebileceğiniz konusunda fikir sahibi olabilirsiniz.***











