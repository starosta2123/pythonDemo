# demo1
Метод def setUp(self) вызывается ПЕРЕД каждым тестом.
Метод def tearDown(self) вызывается ПОСЛЕ каждого теста

setUp – подготовка прогона теста; вызывается перед каждым тестом.
tearDown – вызывается после того, как тест был запущен и результат записан. Метод запускается даже в случае исключения (exception) в теле теста.
setUpClass – метод вызывается перед запуском всех тестов класса.
tearDownClass – вызывается после прогона всех тестов класса.
setUpModule – вызывается перед запуском всех классов модуля.
tearDownModule – вызывается после прогона всех тестов модуля.
