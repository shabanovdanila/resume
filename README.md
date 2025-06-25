# Шабанов Данила

📍 Россия, Воронеж | 📧 danila20041966@gmail.com
🔗 **GitHub:** [github.com/shabanovdanila](https://github.com/shabanovdanila)  
🔗 **Telegram:** [t.me/yayayayeah](https://t.me/yayayayeah)  

## О себе  
Начинающий iOS-разработчик с опытом написания приложений на UIKit и SwiftUI
Постоянно совершенствую свои навыки и стремлюсь применять их в реальных проектах.  

## Навыки  
**iOS:** Swift
**UI:** UIKit(frames, constraits), SwiftUI
**Работа с сетью:** REST, URLSession, Pagination, JWT  
**Многопоточность:** Swift Concurrency, GCD
**Архитектуры:** MVC, MVVM, MVP(MVP+R)
**Работа с памятью:** UserDefaults, KeyChain, Realm
**Общее:** ООП, Алгоритмы и структуры данных, SOLID, DI, Паттерны проектирования 
**Инструменты:** Git, GitHub, Xcode, SPM  

## Проекты

### StudyMeet
**Описание:** "StudyMeet" - платформа для поиска напарника для совместного обучения.

**Особенности:** 
- Регистрация пользователя. Чувствительные данные хранятся в Keychain хранилище.
- На главной странице при скроллинге объявлений работает пагинация для оптимизации.
- Реализована работа с JWT-токенами и обработкой 401 ошибки. Настроен сетевой слой с кастомным DI-контейнером.
- Чат(WebSockets; в разработке).
**Стек:** SwiftUI, async/await, URLSession, DI, Keychain, UserDefaults, MVVM, JWT

**Ссылка на проект:** [GitHub Repository](https://github.com/shabanovdanila/studymeet) 


### ShortenerLink
**Описание:** "ShortenerLink" - уменьшает размер ссылки по выбранному способу(разные api).

**Особенности:** 
- Всё работает на протоколах в связке с DI, что позволяет легко подставлять разные реализации, что удобно для тестов.
- Получен опыт работы с Combine
**Стек:** SwiftUI, async/await, URLSession, DI, Combine, MVVM

**Ссылка на проект:** [GitHub Repository](https://github.com/shabanovdanila/ShortenerLink) 


### Rick and Morty
**Описание:** "Rick and Morty" - база персонажей сериала Рик и Морти с возможностью добавления в избранное в память телефона

**Особенности:** 
- Работает пагинация при скроллинге главной страницы.
- При детальном просмотре карточки персонажа есть возможность добавить персонажа в избранное. Персонаж сохранится в память с помощью Realm. 
- Если нет доступа к интернету, то будет доступен только список избранных персонажей.
**Стек:** UIKit, async/await, URLSession, MVP+R, Realm

**Ссылка на проект:** [GitHub Repository](https://github.com/shabanovdanila/RickAndMorty) 

## Образование
- **Бакалавриат:** ВГУ — Фундаментальная информатика и информационные технологии (с 2022 года, на данный момент перехожу 4 курс)
- **Samsung IT School:** Курс по Android разработке на Java
- **Самообразование:** Бесплатные онлайн-курсы на платформe Stepik, YouTube, изучение документации, книги Василия Усова, swiftbook.me
