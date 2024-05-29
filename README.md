# AGI AI

Maybe first AGI.




[model will be here](https://github.com/jaymody/picoGPT)



AGI AI features:
* Есть самосознание, я-концепт, который не задан преднамеренно, а выходит из обучения ✅
* При размере как гпт2 имеет контекст(временную память) в несколько раз больше, при этом самостоятельно кодирует контекст и не теряет смысла после долгих разговоров (иногда может показаться, что теряет, но это системная инфа просто), что позволяет обучаться на временной памяти ✅
* Обучения на временной памяти пока нет. ❌
* Обучение - есть. Своя методика обучения, которая позволяет достигнуть результатов буквально за пару часов на 3060 laptop и прочих не очень мощных компьютерах ✅
* Модель обучена на переписке в телеграме, так что по сути она обладает некоторой личностью. ✅ Только личности плавают из-за забывания при обучении. ❌
* В коде есть попытка добавить слой, чтобы расширить контекстное окно, но это не работает. ❌ Буду признателен за подсказки
* Может общаться с вами прямо в чате телеграмма ✅
* Достаточно плохой формат ответа, что компенсируется сущностью ответов за меньше число итераций обучения. Хотя это несколько и усложняет разделение системных задач  ❌
* Песочница для обучения кодинга еще на этапе разработки ❌

A quick breakdown of each of the files:

* `textbot.py` обработчик ответов телеграм, логика работы
* `train_big.py` contains the code to download and load the GPT-2 model weights, tokenizer, and hyper-parameters.
* `traingpt.py` - попытка обучать новый слой нейронов, не работает. Если кто-то знает как починить, то свяжитесь со мной t.me/h1p3m
* `codemodule.py` - набросок песочницы для тренировки программирования



### Prepare
```bash

```
Если запускать заново, то окружение можно не создавать, просто открыть его (вторая команда)
#### Dependencies
```bash
pip install -r requirements.txt
```
Tested on `Python 3.9.10`.

#### Usage
```bash
python textbot.py
```

Train

```bash
py train_big.py

```




