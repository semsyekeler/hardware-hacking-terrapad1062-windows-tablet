# Глава IV: За Пределами Возможного - Больше, чем просто планшет


Этот проект — не просто история ремонта, а доказательство того, насколько многофункциональным может стать устройство благодаря творческому подходу. Этот отремонтированный и оптимизированный планшет теперь далеко превзошел стандартное устройство и превратился в набор инструментов, сформированных под мои личные нужды.

## 🎸 Сценарий 1: Портативная гитарная студия

*   **Идея:** Одно из главных преимуществ планшета на базе Windows — это гибкость запуска настольных приложений. Используя эту гибкость, я решил превратить планшет в электрогитарную студию, которую можно взять с собой куда угодно.
*   **Сложность:** При прямом подключении электрогитары к компьютеру с Windows стандартные звуковые драйверы создают высокую задержку (latency), что приводит к заметной задержке между игрой ноты и ее прослушиванием. Это делает невозможным ритмически правильную игру.
*   **Решение:**
    1.  **Оборудование:** Был изготовлен специальный **AUX-сплиттер** с одним концом для гитарного входа (красный) и другим для выхода на наушники/колонки (зеленый). Этот адаптер направляет сигнал гитары на микрофонный вход компьютера, а звуковой выход компьютера — в наушники.
    2.  **Драйвер:** Вместо обычно используемого для этих целей драйвера ASIO4ALL, был установлен **FlexASIO GUI**, который предлагает более широкую поддержку оборудования и имеет простой в использовании интерфейс. FlexASIO обходит медленные драйверы Windows, снижая задержку до незаметного уровня.
        *   [Ссылка для скачивания FlexASIO GUI (v0.35)](https://github.com/flipswitchingmonkey/FlexASIO_GUI/releases/download/v0.35/FlexASIO.GUIInstaller_0.35.exe)
    3.  **Процессор:** С программой **Guitar Rig 7** планшет превратился в огромный арсенал звуков с практически неограниченным количеством моделей усилителей, симуляций кабинетов и педалей эффектов.
*   **Результат:** Благодаря этой настройке я могу добавлять бесчисленные тона и эффекты к своей электрогитаре где угодно, с практически нулевой задержкой.

<p align="center">
  <img src="../../assets/images/guitar_and_tablet_setup_birdview_photo.jpg" width="750">
</p>
<p align="center">
  <i>Фото 1: Вся система в рабочем состоянии: планшет, гитара, наушники и сплиттер.</i>
</p>

<p align="center">
  <img src="../../assets/images/aux_splitter_gitar_and_speaker.jpg" width="400">
</p>
<p align="center">
  <i>Фото 2: Самодельный AUX-сплиттер, разделяющий гитарный сигнал (красный разъем) и выход на наушники.</i>
</p>


## 💻 Сценарий 2: Беспроводной и сенсорный монитор для кодинга

*   **Идея:** Во время кодинга мне часто нужен второй экран для справочной документации или предварительного просмотра работающего приложения. Это устраняет необходимость постоянно переключаться между окнами, ускоряя рабочий процесс.
*   **Решение:** Программа **[Space Desk](https://www.spacedesk.net/)** превратила планшет в беспроводной второй монитор для моего основного компьютера.
*   **Преимущества использования:** Главное преимущество этой установки — сохранение сенсорной функции планшета. Возможность прокручивать справочный код на планшете пальцем, пока я пишу код на основном экране, или выбирать сообщение об ошибке, просто коснувшись его, невероятно ускорила мой рабочий процесс.
*   **Профессиональный совет (Использование в портретном режиме):** Для эффективного использования планшета в портретном режиме выполните следующие шаги:
    1.  В настройках Windows на самом планшете включите "Блокировку поворота" (отключите автоповорот).
    2.  Откройте приложение Space Desk на планшете и подключитесь к основному компьютеру. Изначально экран будет в ландшафтном режиме.
    3.  Перейдите в "Параметры дисплея" на вашем основном компьютере, выберите второй монитор, который представляет планшет, и измените "Ориентацию дисплея" на "Портретную".

<p align="center">
  <img src="../../assets/images/tablet_as_a_second_monitor.jpg" width="700">
</p>
<p align="center">
  <i>Установка, повышающая производительность благодаря сенсорному и вертикальному второму экрану во время кодинга.</i>
</p>

## ⚡ Сценарий 3: Мобильная инженерная лаборатория

*   **Идея:** Как будущему инженеру, мне часто нужно быстро протестировать идею схемы или принцип работы компонента, который приходит мне в голову.
*   **Сложность:** Профессиональные программы для симуляции обычно требуют мощных настольных компьютеров.
*   **Неожиданный результат:** Верите или нет, но одним из самых удивительных результатов этого проекта стало то, что профессиональная программа для симуляции электронных схем **Proteus 8**, известная своим потреблением ресурсов, смогла работать на этом планшете плавно, по крайней мере, на базовом уровне.
*   **Результат:** Это превратило планшет в "мобильную лабораторию", где я могу быстро собрать и протестировать идею схемы, которая пришла мне в голову, в библиотеке или кафе.

---
Надеюсь, это руководство вдохновит вас на ваши собственные проекты. Спасибо за чтение.

 **[← Предыдущая глава: ПО и Оптимизация](./3_PO_i_Optimizatsiya.md)|[Следующая глава: Выводы и личные достижения →](./5_Chemu_Menya_Nauchil_Etot_Proekt.md)**