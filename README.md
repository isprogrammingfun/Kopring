# Kopring
일단 해보는 코프링
## 📁패키지 구조

DDD 구조를 따라 아래와 같이 구성할 예정입니다.

```
.
└── src/
    ├── presentation
    │   └── controller
    ├── application/
    │   └── dto
    │   └── application-service
    ├── domain/
    │   ├── domain-service
    │   ├── domain-repository interface
    │   └── model
    └── infrastructure/
        ├── entity
        ├── repository (jpa)
        ├── mapper
        └── domain-repository implementation
```

presentation~domain 계층은 Kotlin, infrastructure 계층은 Java를 사용할 예정입니다.
