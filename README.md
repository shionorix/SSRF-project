# SSRF-project
Uwaga! Do wykonania zadań potrzebne będzie konto na Portswiggerze oraz narzędzie BurpSuite.
# Zadanie 1
Mamy daną aplikację sklepu, która umożliwia użytkownikowi sprawdzenie dostępności produktu na magazynie poprzez odwołanie się do endpointu API odpowiedzialnego za sprawdzanie statusu dostępności wybranej rzeczy.
Aby rozwiązać zadanie, należy dostać się do interfejsu admina i usunąć użytkownika carlos. 

https://portswigger.net/web-security/ssrf/lab-basic-ssrf-against-localhost

# Zadanie 2
W tej samej aplikacji sklepu okazuje się, że urządzenia będące w tej samej sieci co serwer, całkowicie mu ufają. Wiemy, że adres to 192.168.0.X, a dostęp możemy uzyskać na porcie 8080. 
Aby rozwiązać zadanie, należy dostać się do interfejsu admina i usunąć użytkownika carlos.

https://portswigger.net/web-security/ssrf/lab-basic-ssrf-against-backend-system

# Zadanie 3
W aplikacji zastosowano filtrowanie typu blacklist: pewne elementy nie mogą pojawić się w adresie, do którego chcemy uzyskać dostęp.
Aby rozwiązać zadanie zmień adres http://localhost/admin tak, aby udało się do niego dostać, a następnie usuń użytkownika carlos

https://portswigger.net/web-security/ssrf/lab-ssrf-with-blacklist-filter

# Zadanie 4
Strona sklepu łączy się z wewnętrzną usługą w określony sposób. Aby rozwiązać zadanie, dostań się do panelu admina http://localhost:80/admin omijając filtry, a następnie usuń użytkownika carlos.

https://portswigger.net/web-security/ssrf/lab-ssrf-with-whitelist-filter

# Zadanie 5
Aby rozwiązać zadanie, dostań się do panelu admina, znajdującego się na interfejsie http://192.168.0.12:8080/admin używając przekierowania oraz usuń użytkownika carlos.

https://portswigger.net/web-security/ssrf/lab-ssrf-filter-bypass-via-open-redirection

# Zadanie 6
W aplikacji sklepu kliknięcie przycisku Check stock powoduje przetwarzanie pliku XML. Serwer posiada endpoint z metadanymi pod adresem http://169.254.169.254/. 
Aby rozwiązać zadanie, odnajdź SecretAccessKey serwera.

https://portswigger.net/web-security/xxe/lab-exploiting-xxe-to-perform-ssrf

