# Bijli Manager (APK)

Offline app, no login. Data is saved on the phone.

## APK banane ke steps (sirf phone/browser se)
1. GitHub pe naya repo banao (e.g. `bijli-manager`).
2. Is zip ke andar ki **saari files** repo me upload karo (`.github` folder bhi).
3. Repo > **Actions** tab > "Build APK" chalne do (5-8 min). Na chale to "Run workflow".
4. Green tick ke baad us run me khulo > neeche **Artifacts** > `bijli-manager-apk` download karo.
5. Zip kholo, `app-debug.apk` phone me install karo (Unknown sources allow karna padega).

## App badalna ho
`www/index.html` edit karke commit karo. APK dobara apne aap ban jayegi.

Note: purani APK ke upar nayi APK install ho jati hai aur data bacha rehta hai (appId same rehna chahiye).
