### Что такое попарное тестирование?

Попарное тестирование — это техника [тест-дизайна](https://www.softwaretestinghelp.com/how-to-write-test-plan-document-software-testing-training-day3/), которая обеспечивает полное тестовое покрытие.

_ISTQB_ определяет попарное тестирование как технику [тест-дизайна методом черного ящика](https://www.softwaretestinghelp.com/black-box-testing/), при которой тест-кейсы создаются таким образом, чтобы выполнить все возможные отдельные комбинации каждой пары входных параметров.

Результат работы приложения зависит от многих факторов, например, входных параметров, переменных состояний и конфигураций среды. Для определения возможных значений могут быть полезны такие техники, как [анализ граничных значений и использование классов эквивалентности](https://www.softwaretestinghelp.com/what-is-boundary-value-analysis-and-equivalence-partitioning/). Однако тестировать все возможные комбинации значений для всех факторов — непрактично. Поэтому, чтобы удовлетворить все факторы, генерируется подмножество комбинаций. 

Техника попарного тестирования очень помогает при разработке тестов для приложений, включающих множество параметров. Тесты разрабатываются таким образом, что для каждой пары входных параметров существуют все возможные комбинации этих параметров. Тестовые наборы (тест-сьюты, Test suite) охватывают все комбинации. Поэтому техника хоть и не обеспечивает исчерпывающее тестирование, но все же является эффективной [для поиска ошибок](https://www.softwaretestinghelp.com/tips-to-find-valid-defects-in-any-application/).

эта техника имеет и некоторые ограничения. Она не сработает, если:

-   выбранные для тестирования значения некорректны;
-   мало внимания уделяется комбинациям, которые могут привести к ошибке с высокой долей вероятности;
-   взаимодействие между переменными недостаточно изучено.

[[Pairwise online tools]]

#Test #Тестирование #PairwiseTesting 