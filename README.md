Файлы
conftest.py содержит весь необходимый код для перехвата неудачных тестовых случаев и создания скриншота страницы на случай, если какой-либо тестовый пример не пройдет.

pages/base.py содержит реализацию шаблона PageObject для Python.

pages/elements.py содержит вспомогательный класс для определения веб-элементов на веб-страницах.

tests/test_auth_page.py содержит несколько тестов для Ростелекома (https://b2c.passport.rt.ru/auth/realms/b2c/protocol/openid-connect/auth?client_id=account_b2c&redirect_uri=https://b2c.passport.rt.ru/account_b2c/login&response_type=code&scope=openid&state=312322e5-94fa-41eb-880e-6e97327a1605&theme&auth_type)
