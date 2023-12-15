# Создание и использование компонента.

Ваша задача — создать новый компонент `MainGoal`, который выводит абзац текста, 
описывающий вашу основную цель курса (например, «Моя главная цель: углубленное изучение React с нуля»).
Вам придется создать этот новый компонент с нуля, а затем использовать его в JSX-коде компонента приложения.

Готовое приложение может выглядеть так:
![img.png](img.png)

(обратите внимание на текст «My main goal: Learn react from the ground up» внизу) 
Важно! Ваш компонент должен называться `MainGoal` и его также необходимо экспортировать. 
Для этого просто добавьте ключевое слово экспорта перед компонентом `MainGoal`. 
Компонент `MainGoal` также должен содержать текст «My main goal:» 
(за которым следует ваша основная цель курса).

[Ссылка на код](https://codesandbox.io/p/sandbox/exersice-3-building-using-a-component-pq3lr6?layout=%257B%2522sidebarPanel%2522%253A%2522EXPLORER%2522%252C%2522rootPanelGroup%2522%253A%257B%2522direction%2522%253A%2522horizontal%2522%252C%2522contentType%2522%253A%2522UNKNOWN%2522%252C%2522type%2522%253A%2522PANEL_GROUP%2522%252C%2522id%2522%253A%2522ROOT_LAYOUT%2522%252C%2522panels%2522%253A%255B%257B%2522type%2522%253A%2522PANEL_GROUP%2522%252C%2522contentType%2522%253A%2522UNKNOWN%2522%252C%2522direction%2522%253A%2522vertical%2522%252C%2522id%2522%253A%2522clq78ajm30006356k0o0u3dpo%2522%252C%2522sizes%2522%253A%255B70%252C30%255D%252C%2522panels%2522%253A%255B%257B%2522type%2522%253A%2522PANEL_GROUP%2522%252C%2522contentType%2522%253A%2522EDITOR%2522%252C%2522direction%2522%253A%2522horizontal%2522%252C%2522id%2522%253A%2522EDITOR%2522%252C%2522panels%2522%253A%255B%257B%2522type%2522%253A%2522PANEL%2522%252C%2522contentType%2522%253A%2522EDITOR%2522%252C%2522id%2522%253A%2522clq78ajm30002356kxdlp4ila%2522%257D%255D%257D%252C%257B%2522type%2522%253A%2522PANEL_GROUP%2522%252C%2522contentType%2522%253A%2522SHELLS%2522%252C%2522direction%2522%253A%2522horizontal%2522%252C%2522id%2522%253A%2522SHELLS%2522%252C%2522panels%2522%253A%255B%257B%2522type%2522%253A%2522PANEL%2522%252C%2522contentType%2522%253A%2522SHELLS%2522%252C%2522id%2522%253A%2522clq78ajm30003356kmcbsdync%2522%257D%255D%252C%2522sizes%2522%253A%255B100%255D%257D%255D%257D%252C%257B%2522type%2522%253A%2522PANEL_GROUP%2522%252C%2522contentType%2522%253A%2522DEVTOOLS%2522%252C%2522direction%2522%253A%2522vertical%2522%252C%2522id%2522%253A%2522DEVTOOLS%2522%252C%2522panels%2522%253A%255B%257B%2522type%2522%253A%2522PANEL%2522%252C%2522contentType%2522%253A%2522DEVTOOLS%2522%252C%2522id%2522%253A%2522clq78ajm30005356k68jbqhg0%2522%257D%255D%252C%2522sizes%2522%253A%255B100%255D%257D%255D%252C%2522sizes%2522%253A%255B50%252C50%255D%257D%252C%2522tabbedPanels%2522%253A%257B%2522clq78ajm30002356kxdlp4ila%2522%253A%257B%2522id%2522%253A%2522clq78ajm30002356kxdlp4ila%2522%252C%2522tabs%2522%253A%255B%255D%257D%252C%2522clq78ajm30005356k68jbqhg0%2522%253A%257B%2522tabs%2522%253A%255B%257B%2522id%2522%253A%2522clq78ajm30004356ktbzkcpdx%2522%252C%2522mode%2522%253A%2522permanent%2522%252C%2522type%2522%253A%2522UNASSIGNED_PORT%2522%252C%2522port%2522%253A0%252C%2522path%2522%253A%2522%252F%2522%257D%255D%252C%2522id%2522%253A%2522clq78ajm30005356k68jbqhg0%2522%252C%2522activeTabId%2522%253A%2522clq78ajm30004356ktbzkcpdx%2522%257D%252C%2522clq78ajm30003356kmcbsdync%2522%253A%257B%2522tabs%2522%253A%255B%255D%252C%2522id%2522%253A%2522clq78ajm30003356kmcbsdync%2522%257D%257D%252C%2522showDevtools%2522%253Atrue%252C%2522showShells%2522%253Atrue%252C%2522showSidebar%2522%253Atrue%252C%2522sidebarPanelSize%2522%253A15%257D)