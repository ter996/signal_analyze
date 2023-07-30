# signal_analyze

Программа позволяет проводить автоматический анализ тестовых записей ЭКГ (электрокардиографических) приборов на предмет соответствия требуемым характеристикам по качеству записаемого сигнала.
Основные испытания включают в себя: тест на уровень шумов, корректность записи амплитуд, АЧХ, входные сопротивления и др.

## Используемые библиотеки:
 - pandas
 - numpy
 - matplotlib
 - datetime
 - json
 - scipy
 - jupyter botebook


## Описание работы
На входе файл .txt в котором находится 3-х или 12-ти канальная запись ЭКГ. По числу каналов выбирается jupyter notebook для 3 или 12 каналов соответственно (main_3_ch.ipynb или  main_12_ch.ipynb).
На выходе в ноутбуке выводится пандосовский датафрейм с результатами тестов, а также в процессе обработки создаются графики для визуального контроля и корректировок анализа. Программа состоит из главного модуля, где хранится вся подкапотная часть и основного файла для непосредственно анализа, построения графиков и получения результатов.
