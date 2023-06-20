# spring-security-jwtauthentication
This is an education Java Spring application that implements registration using a jwt token, as well as logging out and revoking old tokens.

When user is registered or logging in a jwt token is generated.

<img width="672" alt="Снимок экрана 2023-06-20 в 11 15 21" src="https://github.com/lavrentyevn/spring-security-jwtauthentication/assets/111048277/078c4b3f-fd9a-479a-8354-51da4ae71228">

Only the latest token is working when user is trying to access secured data as all the old tokens are expired and revoked when a new token is created.

<img width="661" alt="Снимок экрана 2023-06-20 в 11 17 24" src="https://github.com/lavrentyevn/spring-security-jwtauthentication/assets/111048277/af256455-8025-4611-806c-aa6292a47ecf">

Logging out is also implemented.

<img width="877" alt="Снимок экрана 2023-06-20 в 11 23 49" src="https://github.com/lavrentyevn/spring-security-jwtauthentication/assets/111048277/c6de71fe-e3ed-4061-af5e-2c990a9ca6e4">
