[![en](https://img.shields.io/badge/lang-en-red.svg)](README.en.md)


# Yandex Практикум: Курс "Специалист по Data Science плюс".

## Описание проектов
| Название (ссылка) | Описание | Стек |
|:--|:--|:--|
|[Определение возраста покупателей.](https://github.com/mrBrain101/Yandex_Practicum_projects/tree/36f2bd133f2abf91b3201dbf43496f72bc177f05/CV_Age_by_Photo_Prediction )| Для определения возраста по фотографии была построена модель ResNet50 c инициализацией весов imagenet и заданной "головой".|Tensorflow.<br>PIL.<br>Pandas.<br>Matplotlib.<br>Seaborn.<br>Numpy.|
|[Поиск изображений по запросу.](https://github.com/mrBrain101/Yandex_Practicum_projects/tree/36f2bd133f2abf91b3201dbf43496f72bc177f05/CV_NLP_Prompt_image_matching)| Для демонстрационной версии была обучена MVP-модель, способная по векторному представлению изображения и векторному представлению текста, выдать число от 0 до 1 — показать, насколько текст и картинка подходят друг другу.| PyTorch, TorchVision. <br>Scikit-Learn: LinearRegression, ElasticNet. <br>CatBoostRegressor.<br>Spacy.<br>PIL.<br>Transformers.<br>Pandas. <br>Matplotlib. <br>Seaborn. <br>Numpy. <br>OS, Requests.|
|[Защита клиентских данных.](https://github.com/mrBrain101/Yandex_Practicum_projects/tree/36f2bd133f2abf91b3201dbf43496f72bc177f05/Math_Customer_Data_Protection)| Была доказана эффективность алгоритма защиты данных с помощью умножение независымых признаков на обратимую матрицу.<br> Было доказано, теоретически и практически, что эффективность линейной регрессии при такой трансформации предикторов не снижается.|Scikit-Learn: LinearRegression.<br>Pandas. <br>Matplotlib. <br>Numpy.<br>Latex.|
|[Прогнозирование оттока клиентов банка.](https://github.com/mrBrain101/Yandex_Practicum_projects/tree/36f2bd133f2abf91b3201dbf43496f72bc177f05/ML_Bank_Churn)| Была подобрана модель случайного леса, её гиперпараметры и оптимальный метод для борьбы с дисбалансом классов для максимизации метрики _F1_.|Pandas.<br>Numpy.<br>Matplotlib, matplotlib_venn, Plotly, Cufflinks, Seaborn.<br>Requests.<br>Scikit-Learn.|
|[Прогнозирование риска ДТП.](https://github.com/mrBrain101/Yandex_Practicum_projects/tree/36f2bd133f2abf91b3201dbf43496f72bc177f05/ML_Car_Accident_Risk_Prediction)| Была создана MVP система оценки риска ДТП по выбранному маршруту.|CatBoost.<br>Scikit-Learn's pipelines, DecisionTreeClassifier, RandomForestClassifier.<br>SQLAlchemy.<br>Pandas.<br>PhiK.<br>Optuna.<br>Plotly.<br>Matplotlib.<br>Seaborn.<br>Numpy.<br>OS.|
|[Предсказание стоимости подержанных автомобилей.](https://github.com/mrBrain101/Yandex_Practicum_projects/tree/36f2bd133f2abf91b3201dbf43496f72bc177f05/ML_Car_Price_Prediction)| Для прогнозирования цены подержанного автомобиля покупателя была создана модель LightGBM с RMSE 1532 евро и коэффициентом R2 0,89.|Scikit-Learn's LinearRegression, DecisionTreeRegressor, HistGradientBoostingRegressor.<br>CatBoost.<br>LightGBM.<br>Optuna hyperparameter search. <br>PhiK correlation analisys. <br>Pandas. <br>Scipy. <br>Matplotlib. <br>Seaborn. <br>Numpy. <br>OS, Requests.|
|[Прогнозирование оттока клиентов отеля.](https://github.com/mrBrain101/Yandex_Practicum_projects/tree/36f2bd133f2abf91b3201dbf43496f72bc177f05/ML_Hotel_%D0%A1hurn)| Была разработана прибыльная система предсказаний отмены бронирования.<br>Был проведён исследовательский анализ и составлен портрет "ненадёжного" клиента.|Pandas.<br>Numpy.<br>Matplotlib, matplotlib_venn, Plotly, Cufflinks, Seaborn.<br>OS, Requests, Multiprocessing.<br>Scikit-Learn's HalvingGridSearchCV, DecisionTreeClassifier, RandomForestClassifier, HistGradientBoostingClassifier.|
|[Мэтчинг товаров.](https://github.com/mrBrain101/Yandex_Practicum_projects/tree/36f2bd133f2abf91b3201dbf43496f72bc177f05/ML_Matching)| Для максимизации метрики $accuracy@5$ при мэтчинге товаров, был разработан алгоритм `FAISS` с индексом `IVF1600,Flat`.|Scikit-Learn's KMeans, MiniBatchKMeans. <br>FB's FAISS. <br>Spotify's ANNOY. <br>Pandas. <br>Scipy. <br>PhiK. <br>Matplotlib. <br>Seaborn. <br>Numpy. |
|[Прогнозирование рентабельности расположения нефтяных скважин. ](https://github.com/mrBrain101/Yandex_Practicum_projects/tree/36f2bd133f2abf91b3201dbf43496f72bc177f05/ML_Oil_Economy_Bootstrap)|Для прогнозирования рентабельности нефтяных скважин была построена модель линейной регрессии.|Scikit-Learn's LinearRegression, Pipeline, StandardScaler, r2_score, mean_squared_error. <br>Pandas. <br>Matplotlib. <br>Seaborn. <br>Numpy. <br>OS. <br>Requests.<br>TQDM.|
|[Предсказание стоимости жилья.](https://github.com/mrBrain101/Yandex_Practicum_projects/tree/36f2bd133f2abf91b3201dbf43496f72bc177f05/ML_SPARK_Realty_Price_Prediction)|Для определения цен на недвижимость были построены модели регрессии.|PySpark: SQL, MLib.<br>Pandas. <br>Numpy.<br>Matplotlib. <br>Seaborn.|
|[Предсказание температуры звезд.](https://github.com/mrBrain101/Yandex_Practicum_projects/tree/36f2bd133f2abf91b3201dbf43496f72bc177f05/ML_Star_Temp_Prediction)|Для предсказания абсолютной температуры на поверхности звезды была разработана полносвязная нейронная сеть прямого распроранения.|PyTorch (пользовательский класс, совместимый с Scikit-Learn Pipeline).<br>Scikit-Learn's pipelines.<br>Pandas.<br>PhiK.<br>Plotly.<br>Matplotlib.<br>Seaborn.<br>Numpy.<br>OS, Requests.|
|[Прогнозирование оттока клиентов в телекоме.](https://github.com/mrBrain101/Yandex_Practicum_projects/tree/36f2bd133f2abf91b3201dbf43496f72bc177f05/ML_Telecom_Churn_Prediction)|Для предсказания оттока клиентов, была построена модель, с _ROC AUC_ = 0.84, _accuracy_ - 0.77.|OS, Multiprocessing, SQLAlchemy, Psycopg2.<br>Pandas, Numpy.<br>Phik, Shap.<br>Matplotlib, Seaborn.<br>Scikit-Learn, CatBoost, Category Encoders.<br>ydata_synthetic.<br>Optuna, TQDM.|
|[Прогнозирование спроса (временные ряды).](https://github.com/mrBrain101/Yandex_Practicum_projects/tree/36f2bd133f2abf91b3201dbf43496f72bc177f05/ML_Time_Series_Analysis_Taxi)|Была разработана модель прогнозирования кол-ва заказов такси Prophet.|Prophet.<br>Scikit-Learn. <br>LSTM on PyTorch. <br>CatBoost.<br>Pandas. <br>Statsmodels. <br>PhiK. <br>Matplotlib. <br>Seaborn. <br>Numpy.|
|[Классификация токсичных комментариев.](https://github.com/mrBrain101/Yandex_Practicum_projects/tree/36f2bd133f2abf91b3201dbf43496f72bc177f05/NLP_Toxic_Commentaries_Classification)|Для классификации токсичных комментариев была использована модель оценки токсичности комментариев _toxic-bert_ и применена логистическая регрессия: _F1_= 0.93. |PyTorch.<br>NLTK.<br>Spacy.<br>Detoxify.<br>Bert, ToxicBert.<br>Scikit-Learn: LogisticRegression, TfidfVectorizer, CountVectorizer. <br>CatBoostClassifier.<br>Transformers.<br>Pandas. <br>Matplotlib. <br>Seaborn. <br>Wordcloud.<br>Numpy. <br>IO, OS, Requests.|
|[Статистический анализ поведения клиентов приложения для самокатов.](https://github.com/mrBrain101/Yandex_Practicum_projects/tree/36f2bd133f2abf91b3201dbf43496f72bc177f05/Stats_Scooter_App_Research)|Был проведён анализ поведения клиентов сервиса аренды самокатов.|Pandas, Numpy.<br>Matplotlib, Seaborn, Cufflinks.<br>Scipy, Math.|

## Сертификат
![Сертификат](z_Certificate_ru/certificate_ru_Page_1.jpg)

## Программа
![Программа](z_Certificate_ru/certificate_ru_Page_2.jpg)
