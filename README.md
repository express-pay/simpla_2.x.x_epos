# Расширение Simpla 2.x.x сервиса «Экспресс Платежи: E-POS»
Расширение CMS Simpla для интеграции с сервисом «Экспресс Платежи». Расширение позволяет выставить счет в системе E-POS, получить и обработать уведомление о платеже в системе E-POS.

<a href="https://express-pay.by/cms-extensions/simpla">Инструкция для установки и настройки</a>

<a href="https://downgit.github.io/#/home?url=https://github.com/express-pay/simpla_2.x.x_epos/tree/main/ExpressPayEpos">Скачать ZIP</a>

## Минимальные требования для установки плагина:
* Simpla 2.3.1 и выше;

## Установка плагина
1. Скопируйте каталог "ExpressPayEpos" в payment.
2. Войдите в личный кабинет администратора, откройте "Настройки - Оплата" и создайте новый вид оплаты,
при этом выбрать "Экспресс Платежи: E-POS" в качестве платежного модуля для оплаты через E-POS.
3. Заполните поля настроек.
4. Выберите способы доставки при которых будет доступна данная оплата.
5. Установите флажок "Активен".
6. Сохраните изменения.

## Тестовый стенд
* Токен: a75b74cbcfe446509e8ee874f421bd65
* Номер услуги: 5
* Секретное слово для подписи счетов: sandbox.expresspay.by
* Использовать тестовый режим: Да
* Адрес тестового API: https://sandbox-api.express-pay.by

## Адрес для обработки URL уведомлений от сервиса «Экспресс Платежи»
```
http://{адрес_сайта}/payment/ExpressPayEpos/callback.php?result=notify
```
