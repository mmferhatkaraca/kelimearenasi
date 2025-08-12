# Kelime Arenası — GitHub Actions ile Android APK/AAB Derleme

1) Bu klasörü projenin köküne koy.
2) GitHub repo ayarlarında Secrets ekle:
   - UNITY_LICENSE
   - UNITY_EMAIL
   - UNITY_PASSWORD
3) main branch'ına push et veya Actions -> Run workflow de.
4) Artifacts kısmından APK/AAB indir.

Notlar:
- unityVersion değerini projendeki Unity LTS sürümüyle eşleştir.
- Keystore ile imzalı AAB için game-ci/unity-builder dokümantasyonundaki keystore ayarlarını Secrets olarak gir.
