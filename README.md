# 1c
Внешняя обработка для связи 1С v8.3.13 (в режиме Управляемое приложение) и ноды Erachain
<br>Для работы обработки необходимо установить кошелек Erachain с сервера  https://erachain.org/home-developers
<br>После запуска кошелька
  1. Создайте адрес (следуя указаниям ноды) сохраните Seed. <br>
  2. Загрузить все блоки (загрузка должна начаться автоматически). <br>
  3. Синхронизировать кошелек (Левая панель-> Счета ->Мои счета -> Синхронизировать кошелек). <br>
  4. Настроить работу RPC и WEB для этого зайти в настройки (меню: файл-> настройки -> основные):<br>
        разрешить работу RPC, RPC порт:9068 <br>
        разрешить работу WEB, WEB порт:9067 <br>
   <br>
  Для нормальной работы в последующем рекомендую запускать кошелек и параметром:  -nogui <br>
  В настоящее время реализован механизм отправки актив <br>
  
