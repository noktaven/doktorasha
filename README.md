# Dondurma kaydı

`LISTE.sha256`, tek sınamadan önce dondurulan dosyaların SHA-256 listesidir. Liste 20 Kasım 2026, 00:50:09'da (UTC+3) yazıldı ve sınamadan önce bu depoya kondu.

`LISTE.sha256` dosyasının kendi SHA-256'sı:

```
f45ef88571318e7d56eb2178f77cbd000b9bf15eb58ab4194b543b06b7c06e17
```

Doğrulama: `sha256sum LISTE.sha256`

## Sınama öncesi kayıt

`SINAMA_ONCESI_KAYIT.sha256`, dondurmadan sonra ve tek sınamadan önce sabitlenen dosyaların SHA-256 listesidir: sınama sonucunun nasıl kullanılacağını belirleyen karar dosyası, sınamanın yürütme talimatı ve sınama dosyasını hazırlayan, biçimini denetleyen ve sınamayı çalıştıran betikler. Liste 20 Kasım 2026, 07:52:10'da (UTC+3) yazıldı ve sınamadan önce bu depoya kondu; sınama ölçüm dosyası o sırada henüz üretilmemişti.

`SINAMA_ONCESI_KAYIT.sha256` dosyasının kendi SHA-256'sı:

```
4ef3b8fbb6b8c0b659b9f6883df6078e5234f591a8bb51c9c99d84ab7a089d13
```

Doğrulama: `sha256sum SINAMA_ONCESI_KAYIT.sha256`

**Ek.** Sınama dosyasını hazırlayan betiğin ilk sürümü kendi denetiminde durdu ve dosya yazmadı; düzeltilmiş sürümün ve durma kaydının SHA-256'ları `SINAMA_ONCESI_KAYIT_EK.sha256` dosyasındadır. Bu ek de sınama ölçüm dosyası üretilmeden önce buraya kondu (liste saati 20 Kasım 2026, 07:54:42, UTC+3). Ekin kendi SHA-256'sı:

```
54c65bbc671e86a1604167e08f193ef01ecf2265472d28a56d401130fe534aa1
```

## İkinci çalışma: çözümleme planı

`ikinci-calisma/LISTE.sha256`, ikinci çalışmanın çözümleme planının ve plana dayanak olan dosyaların (planın bağımsız denetimi ve yanıtı, okuma notları ve alıntı denetimi, güç hesabı, verinin ön denetim betiği ve sonucu, veri yapısı notu, kararlar) SHA-256 listesidir. Plan, verinin direnç değerleri hesaplanmadan yazıldı ve bağımsız bir denetimden sonra sabitlendi. Liste 22 Kasım 2026, 09:59:23'te (UTC+3) yazıldı ve çözümleme kodu yazılmadan önce bu depoya kondu.

`ikinci-calisma/LISTE.sha256` dosyasının kendi SHA-256'sı:

```
21ae94adeda6edbe230a1c2182c6b76b5e49a52d856f88e6da1f452c06b52811
```

Doğrulama: `sha256sum ikinci-calisma/LISTE.sha256`

## İkinci çalışma: ek çözümleme planı

`ikinci-calisma/EK_PLAN_LISTE.sha256`, ikinci çalışmanın ek çözümleme planının ve dayanak dosyalarının (planın bağımsız denetimi ve yanıtı, kararlar, ilk planın listesi) SHA-256 listesidir. Ek plan, verinin direnç değerleri hesaplanmadan yazıldı ve bağımsız bir denetimden sonra sabitlendi. Liste 26 Kasım 2026, 10:10:03'te (UTC+3) yazıldı ve çözümleme gerçek veride çalıştırılmadan önce bu depoya kondu.

`ikinci-calisma/EK_PLAN_LISTE.sha256` dosyasının kendi SHA-256'sı:

```
0dd60a06221766bc36cf1ee6cb76bf887c223888fac332be29a7b7620c5e7b07
```

Doğrulama: `sha256sum ikinci-calisma/EK_PLAN_LISTE.sha256`
