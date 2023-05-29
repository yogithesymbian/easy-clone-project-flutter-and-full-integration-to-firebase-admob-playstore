# easy-clone-project-flutter-and-full-integrattion-to-firebase-admob-playstore

0. first on first `ctrl + f` and replace all for `your_package_name_here` text on this readme, to your project unique name. [ ]

1. GO TO `pubspec.yaml` rename name and descriptions. its on <b>line 1 and line 2</b>. [ ]

2. then run these command [ ]

```
flutter pub run change_app_package_name:main com.yodev.your_package_name_here
```

3. GO TO <b>Android Manifiest</b> and change label apps [ ]

4. then run these command [ ]

```
flutterfire configure && keytool -genkey -v -keystore ~/Sites/mobile/flutter/deployment/keystore/your_package_name_here.jks -keyalg RSA -keysize 2048 -validity 10000 -alias upload && cd android && ./gradlew signingReport && ..
```

```
Password : **************

What is your first and last name?
  [Unknown]:  YoDevEastBorneo
What is the name of your organizational unit?
  [Unknown]:  FlutterDeveloper
What is the name of your organization?
  [Unknown]:  YODEV
What is the name of your City or Locality?
  [Unknown]:  Samarinda
What is the name of your State or Province?
  [Unknown]:  East Borneo
What is the two-letter country code for this unit?
  [Unknown]:  ID
```

6. Find `key.properties` and replace with the package name `your_package_name_here.jks`

7. Copy sha1 and sha-256 to firebase.
8. Generate icon in `appicon.co` and background `in canva`

9. create admob, change key on `AndroidManifiest.xml` and `ad_helper.dart`

10. create `privacy policy`

11. replace icon `drawable`

12. change splash screen image in `assets/images/`

13. change retrofit ( API ) .

14. run apps

15. check integration `firebase` and `admob`

16. then run these command

`flutter build appbundle --release`

17. screenshot apps

18. deployment `play console`

```
- [x]
Before Release Note: ( short desc & full desc )
    - [ ] adorable baby ****** ******
        - [ ] shine your life with a baby make your best day by the day
Release Note:
<en-US>
shine your life with a baby make your best day by the day
</en-US>
    - [ ] ******** on your phone as ********
        - [ ] ******** is one of best ******** from YODev
            - [ ] ******** is HD if you have set ******** from YODev.
```

custom the name or you can use chatgpt to generate tranquility words with best grammer fix also enhancement/grows your apps.
