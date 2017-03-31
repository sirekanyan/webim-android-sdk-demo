# Webim SDK demo
[ ![Download](https://api.bintray.com/packages/webim/maven/WebimSdkAndroid/images/download.svg) ](https://bintray.com/webim/maven/WebimSdkAndroid/_latestVersion)

Приложение, демонстрирующее возможности *Webim Android SDK*. Данное приложение опубликовано в [Google Play](https://play.google.com/store/apps/details?id=ru.webim.demo.client).

[Онлайн консультант Webim](https://webim.ru) — это многофункциональный сервис для консультирования посетителей вашего сайта через всплывающее окно чата — его можно бесплатно скачать и установить в виде универсального скрипта или CMS модуля на нужные страницы, а кроме того интегрировать в фирменное мобильное приложение. Библиотека *Webim Android SDK* предоставляет разработчикам мобильных приложений на платформе Google Android средства для интеграции в эти приложения чата между их пользователями и операторами компании-разработчика на основе технологий, применяющихся в онлайн консультанте Вебим.

Данное приложение создано с целью демонстрации, с одной стороны, возможностей нашего SDK, с другой - того, как правильно наш SDK использовать. Во время интеграции чата в ваше собственное приложение, ориентируйтесь на это демо-приложение - оно значительно упростит вам интеграцию.

## Установка SDK
Поддерживается Android версии  4.+ (Android API 15+)
Чтобы начать использовать *Webim Android SDK*, добавьте зависимость в build.gradle вашего приложения
```
compile 'com.webimapp.sdk:webimclientsdkandroid:3.0.0'
```
А также добавьте в AndroidManifest.xml следующие разрешения:
```
<uses-permission android:name="android.permission.INTERNET"/>
```
