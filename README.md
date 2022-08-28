# Link Preview Node API Backend

## Install deps

In the root project folder run the following command

```sh
$ npm install
```

and run

```sh
$ npm start
```

## Get a link preview

```sh
$ curl -d '{"url":"https://www.chip.de/downloads/TeleGuard-Android-App_183620101.html"}' -H "Content-Type: application/json" http://localhost:48656/preview
```

## Response

```js
{
    "title": "TeleGuard - Android App",
    "description": "TeleGuard - Android App 2.2.0 Deutsch: Die kostenlose Android-App \"TeleGuard\" ist ein privater Messenger, welcher hohen Wert auf Anonymität legt.",
    "image": "https://www.chip.de/ii/1/2/6/4/7/8/8/0/5/b828d165c4b518c8.jpg",
    "url": "https://www.chip.de/downloads/TeleGuard-Android-App_183620101.html",
    "siteName": "CHIP Online"
}
```