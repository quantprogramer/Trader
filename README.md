# Trader App Desktop
Додаток який автоматизує створення відео та опублікування їх в соціальній мережі [TikTok](https://tiktok.com/). Також він автоматично чи по нажиманню кнопки продажі аккаунта чи по заданням автоматичного барєру потрібних підписників для продажі буде виставляти ці аккаунти по заданному шаблону на торгову площатку [FunPay](https://funpay.com/)
## Розробляти разом з нами

Щоб розпочати розробку додатку на сам перед вам потрібно:
- Встановлений node.js на ваш пристрій.
- Обовязкова мова програмування Rust.
- Модуль Trader App Backend для запитів на сервер та FunPay.
- Модуль Trader App Game для самих відео.

Після того як все було готове та встановленне можна розпочинати. Для початку створіть форк цього репозиторію. Перейдіть до себе на сторінку GitHub та встановіть його де себе локально на пристрій. Відкрийте проект в зручному для вас редакторі коду та встановіть всі залежності для node.js командою:
```shell
npm install
```
Коли вже все було встановленне не забудьте користуватися git правильно та перейдіть на гілку розробки:
```shell
git checkout dev
```
Потім берете завдання із Kanban таблиці яке хочете реалізувати та пишете код до поки він не буде готовим та протестований вами і коли ви вже впевнені пушете все в гілку реліз робите коміт в якому буде описаний тип завдання ід завдання та короткий тайтл і пуште його до себе в репозиторій. Приклади команд:
```shell
git commit -m "Text" # Приклад коммітів в гілці dev
```
```shell
git merge realise dev # Приклад зєднання гілок
```
```shell
git checkout realise
git commit -m "QUEST #1032: Realise button with function of add new tiktok user to app"
# Це приклад фінального коміту який вказує що ви зробили завдання
```
```shell
git push {} # Замість {} має бути силка на ваш репозиторій
```
Після виконання завдання та пушу його на ваш репозиторій відправте пул запит на наш репозиторій заповніть короткий тайтл про саме завдання та його ід і ожидайте review кода якщо все пройде гладко ваша зміна змерджеться з основним репозиторієм якщож ні то вам напишуть що не так і що потрібно пофіксити ви це фіксите та знову пул запит і так до поки ваше завдання не приймут.