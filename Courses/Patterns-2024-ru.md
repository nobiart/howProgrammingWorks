# 🚀 Patterns 2024 Тренинг с наставниками

***Rethinking GRASP, SOLID, and GoF for JavaScript and Node.js***

> Translations: [EN](./Patterns-2024.md), [UA](./Patterns-2024-ua.md), [RU](./Patterns-2024-ru.md)

Практический тренинг по переосмыслению и применению паттернов GoF, SOLID и GRASP в асинхронном программировании на JavaScript и Type для прикладных и системных разработчиков бекенда и фронтенда, с примерами для Node.js и браузерных приложений.

Понимание этих концепций нельзя просто извлечь из коробки (или книги) и поместить себе в голову. Такое понимание сильно различается для разных языков и платформ.
Слепой перенос знаний и практик из C++ или Java в **JavaScript** и C# приводит к мертвым церемониям.
Однако их можно возродить с помощью практики, привязать к реалиям и переосмыслить, чтобы они не стали бесполезными монстрами.

## 💡 Уникальность программы наставничества
  
От автора первого курса по асинхронному программированию на JavaScript, прочитанному в Киевском политехническом институте еще 17 лет назад, множества докладов и лекций по Node.js. За эти годы собрано множество опыта, отзывов, практики и курс перерабатывался практически каждый год, вбирая самые новые пактики. Тимур Шемсединов так же является контрибьютором мноджества платформ и библиотек в открытом коде, среди которых Node.js, Metarhia, geoip-lite, MDN, HowProgrammingWorks, metasync... Тимур один из первых, кто начал портировать в JavaScript абстракции параллельного программирования из C++, C#, Java, Go и других языков.

Автор утверждает, что это самые важные вещи, которые следует учить и практиковать:

* 📂 Системы модульности, внедрение зависимостей (DI) и инверсия управления (IoC)
* 📦 Декомпозиция абстракций и принципы GRASP с современной интерпретацией
* 🧩 Паттерны «Банды четырех» (GoF) переосмысленные для JavaScript и TypeScript
* 🔮 Принципы изоляции и SoC (Разделение ответственностей)
* 👷🏻‍♂️ Разделение прикладного и системного кода (разные специальности)
* 🧩 Принципы SOLID: SRP, OCP, ISP, DIP, LSP с адаптацией для разных парадигм
* 🌟 Мультипарадигменное программирование и создание доменных языков (DSL)
* 🧩 Контрактное программирование и декларативное моделирование через схемы
* 🏛️ Чистая архитектура (Clean) и слоеная архитектура (Onion или Layered)

## 📖 Структура курса

### 📦 Unit 1: Structure and Modularity

Структура и модульность. Почему нужно переосмыслить и адаптировать GoF, SOLID и GRASP для современного JavaScript/TypeScript. Как это сделать?

> Мы научимся применять паттерны и принципы на практических задачах, которые встречаются в типичных проектах, а также проведем параллели между теорией из классических книг и ежедневной практикой, покажем, что все эти знания нужны не только на собеседованиях, а позволяют улучшить характеристики кода ваших проектов и понимание между специалистами в коллективе.

Что мы получаем как результат этого юнита:

+ Начинаем писать код, который удобно покрывать тестами.
+ Наш код становится лучше для читения и понимания.
+ После оптимизации наш медленный код становится быстрее и ест меньше памяти.
+ Код становится модульный, надежный и готовый к интеграции.
+ Как изменить код, чтобы снизит время, необходимое для его поддержки.

> Для каждой недели подготовлены задания, некоторые из них предусматривают рефакторинг готовых примеров кода, другие - написание кода, третьи - оптимизацию и исследование характериатстик кода.

**🗓️ Week 1: Характеристики кода и стратегии оптимизации**

> Существует путь, который ведет к радикальному улучшению структуры и характеристик кода. Мы рассмотрим принципы и шаблоны GoF, SOLID, GRASP, как их применять и что они дают. Характеристики кода: читаемость, надежность, тестируемость, поддерживаемость, повторное использование, гибкость, безопасность. Оптимальное использование вычислительных ресурсов: процессор, память, ввод-вывод и когнитивные ресурсы разработчиков.

**🗓️ Week 2: Встроенные возможности в языке и платформе**

> JavaScript имеет встроенные контракты: Thenable, Iterable, AsyncIterator, Callback-last, Callable, Cancelable, Observable, но культура разработки через контракты и интерфейсы не очень распространена в сообществе. Как улучшить производительность разработки с помощью подхода, основанного на знаниях. Как шаблоны могут помочь нам в этом: реализовывать новые фичи быстро и эффективно, быть производительными, делать ежедневную работу интересной, быть мотивированными и не выгорать.

**🗓️ Week 3: Инстанцирование: порождающие шаблоны и техники**

> Порождающие шаблоны: Constructor, Singleton, Factory, Pool, Builder, Prototype, Flyweight, другие шаблоны и техники. Давайте найдем связанные принципы и переосмыслим прикладное значение GRASP: Creator; GRASP: Polymorphism, SOLID: ISP; Aggregation и Composition. Как экономить память и другие ресурсы; как эффективно применять оптимизацию и кэширование. Как разрабатывать крайне быстрый код и минимизировать latency, сделать код кросс-платформенным и понятным для коллег.

**🗓️ Week 4: Изоляция и разделение ответственности (SoC)**

> Separation of Concerns (SoC) — это общий инженерный принцип, направленный на создание гибких, надежных и легко модифицируемых систем. Мы можем использовать шаблоны GoF: Mediator, Bridge, Abstract factory, Strategy (в JavaScript реализации: Map<PropertyKey, Implementation>); Системы модульности; GRASP принципы Information Expert, Indirection, и Protected variations; SOLID: SRP. Это улучшит тестируемость кода и снизит затраты на интеграцию.

### 📦 Unit 2: Execution and Contracts

Для построения структуры приложения из модулей и программных компонентов, нам нужен контрактный подход к программированию, он позволяет разрабатывать части системы независимо, масштабировать команду, улучшать управляемость проектами и делать план разработки более предсказуемым.

> Мы будем применять три типа связывания: связывание через данные, связывание через вызовы и связывание через события.  Мы научимся управлять зацеплением между компонентами программных систем и проектировать их таким образом, чтобы иметь возможность собирать из них приложения, откладывая решения о компоновке. Другими словами, наша задача на этапе проектирования не прибить все гвоздями, а дать архитектору возможность позднего маневра.

+ Научимся создавать структуру кода.
+ Научимся создавать структуру коллектива, соответствующую структуре кода. (По закону Конвея: «организации проектируют системы, которые копируют структуру коммуникаций в этой организации»).
+ Отрабатываем написание хорошо поддерживаемых приложений.

**🗓️ Week 5: Контракты: интерфейсы для взаимодействия компонентов**

> Паттерны: Adapter (Wrapper), Facade, Bridge, Composite, Proxy, Promisify; Front controller; GRASP: Low Coupling and High Cohesion; SOLID: LSP (Liskov); and SOLID: OCP (Open-Closed). Применение контрактов открывает возможность пошагового рефакторинга, устранения технического долга и повышения стабильности подсистем; снижения зависимости (связанности) между слоями и модулями. На уровне управления проектом это позволяет масштабировать команду, управлять приоритетами и принимать архитектурные решения.

**🗓️ Week 6: Ослабление зацепления в коде через события и сообщения**

> Следующий мощный подход — это применение шин событий внутри приложения и между подсистемами. Это распространено в пользовательских интерфейсах, распределенных системах, совместном доступе к разделяемым ресурсам. На базе асинхронного и событийного программирования построено решением с неблокирующим вводом-выводом в Node.js. Мы рассмотрим GRASP: Pure Fabrication and Low Coupling; AsyncQueue and queueing systems, Async collections, и другие.

**🗓️ Week 7: Streams: Потоки данных и преобразования**

> Реактивное программирование развилось в отдельную парадигму; потоки и сигналы основаны на GoF: Observer; GRASP: Pure Fabrication и Event-driven подходе с потоками данных и операторами преобразования данных. Это широко используется в сетевых протоколах, доступе к данным и файловым системам, разработке игр, финансовых и аналитических системах, управлении встроенными системами, телеметрии и других областях. Это дает выразительный синтаксис, более высокий уровень абстракции, гибкость и производительность для улучшения пользовательского опыта.

**🗓️ Week 8: Обработка ошибок: исключения Exceptions and Soft Failures**

> Мы рассмотрим лучшие практики обработки ошибок как с исключениями, так и доменными (мягкими) ошибками. Gracefully recover и мягкие ошибки повысят общую производительность системы. Мы будем использовать Chain of Responsibility, SOLID, Promises, fallback mechanisms to handle non-critical errors; GRASP: Protected Variations and Custom JavaScript-specific AggregateError and Error.prototype.cause, а также сериализацию ошибок для передачи по сети.

### 📦 Unit 3: Runtime for Applications

Объединение всех рассмотренных техник и подходов в реальных условиях. В этом юните мы рассмотрим, как основные концепции построения структуры приложений, контрактное программирование и шаблоны превращаются в работающие и масштабируемые приложения.

> Этот модуль сосредоточен на том, как вопросы среды исполнения ложатся на задачи структуры и архитектуры приложений. Вы получите навык внедрения техник программирования, превращающих программное решение в цифровую платформу, рассчитанную на долгую эксплуатацию; это включает поддержку смены инструментария, расширения коллектива, постоянное интенсивное наращивание функциональности и нагрузок.

**🗓️ Week 9: Семантика: выразительные DSL**

> Для улучшения выразительности кода и ясности семантики любое сложное программное обеспечение требует создания DSL (языков, специализированных для предметной области). При разработке DSL можно использовать хорошо известные синтаксисы, такие как JSON, JSON5, Markdown и даже сам JavaScript. Мы рассмотрим паттерны: Command, Interpreter, State, Strategy, Visitor. DSL делает код понятным для аналитиков предметной области и даже опытных пользователей. Это улучшает общение и понимание, ускоряет разработку, адаптацию решений к новым требованиям, упрощает обучение и передачу знаний, скрывает технические сложности и позволяет специалистам сосредоточиться на своей области, улучшая общую предсказуемость проекта.

**🗓️ Week 10: All-agnostic как стратегия по умолчанию**

> Разработка систем, независимых от фреймворков, платформ, протоколов, баз данных и облачных решений, как стандартный подход для обеспечения гибкости и свободы архитектурных решений. Такой подход устраняет зависимость от поставщиков облачных решений и фреймворков. Конечно, не нужно реализовывать все аспекты агностичного подхода, но некоторые из них принесут значительные выгоды в масштабировании системы и в процессе ее эксплуатации. Мы будем использовать изоляцию, GRASP: Controller; SOLID: DIP; принципы IoC и DI; интерфейсы и паттерн Strategy для отвязки от конкретных реализаций.

**🗓️ Week 11: Масштабирование приложений и архитектурные стили**

> На этой неделе мы рассмотрим, как проектировать системы, которые могут	 масштабироваться и развиваться эффективно, используя различные архитектурные стили: DDD, слоеная архитектура, SOA, Микросервисм, событийная архитектура, монолитная, порты и адаптеры, чистая архитектура, Event-Sourcing, CQRS, Pipeline, Peer-to-Peer, Client-Server архитектура и как применять SOLID, GRASP и GoF для реализации архитектуры.

**🗓️ Week 12: Методология: как начать применять концепции**

> Заключительная часть программы тренинга сосредоточена на практическом применении всех знаний в комплексе. Мы рассмотрим, как начать внедрять концепции и шаблоны, изученные на курсе, в реальных проектах. Этот модуль предоставляет практические стратегии для создания дорожной карты по их внедрению. Как выявить необходимость в шаблонах и принципах и учесть возможные негативные аспекты. Рефакторинг унаследованных систем, внедрение новых методов разработки и активностей в коллективе. Как спланировать собственное обучение и наладить развитие команды с использованием знаний из этого тренинга.

##  Тарифные планы

* Minimal: обучение в общей группе без наставника, но с групповыми семинарами
* Standard: обучение с наставником в небольших группах (10 человек)
* Professional: обучение с наставником, индивидуально и в группах, дополнительные материалы
* Exclusive: персонализированный учебный трек с автором курса и приглашенными экспертами

[👉 Купить: https://nodeua.com/Patterns-2024-buy.html](https://nodeua.com/Patterns-2024-buy.html)