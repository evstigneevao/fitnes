# Прогнозирование вероятности оттока пользователей для фитнес-центров

Для этого проекта были использованы:
- Python;
- Pandas;
- Matplotlib;
- Seaborn;
- Scikit-learn;
- кластеризация;
- машинное обучение.

В ходе исследования проанализировано поведение клиентов ушедших в отток клиентов и выявлены их характерные признаки.

Затем данные были подготовлены для дальнейшего прогнозирования - удалены наиболее зависимые между собой признаки, после чего использовано машинное обучение двумя способами - логистической регрессией и случайным лесом и спрогнозирована вероятность оттока (на уровне следующего месяца) для каждого клиента.

Так же была проведена кластеризация пользователей, после чего были сформированы типичные портреты пользователей: выделены наиболее яркие группы, охарактеризованы их основные свойства; проанализированы основные признаки, наиболее сильно влияющие на отток.

В ходе исследования построена модель прогнозирования оттока пользователей. Для прогноза оттока клиентов фитнес-центра на уровне следующего месяца предпочтительнее использовать модель логистической регрессии.

Проведена кластеризация пользователей, по результатам которой клиенты были распределены на 5 кластеров. Было выделено 2 кластера надежных клиентов. 3 кластерам клиентов следует уделять большее внимание:

1) рассказать о проводимых групповых занятиях;

2) рассказать о партнерах, возможно клиент является его сотрудником и сможет получить скидку на покупку следующего абонемента;

3) рассказать о преимуществах более долгосрочного абонемента.
