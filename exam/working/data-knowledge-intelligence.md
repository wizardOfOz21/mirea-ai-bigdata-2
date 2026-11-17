# Факт → данные → информация → знания → мудрость; интеллект

```mermaid
%%{init: {"flowchart": {"wrappingWidth": 900, "nodeSpacing": 30, "rankSpacing": 45, "padding": 20}}}%%
flowchart TB
    F["<b>Факт</b><br>то, что действительно произошло или существует;<br>в ИИ — конкретное формальное утверждение об объекте"]
    D["<b>Данные</b> — форма<br>зарегистрированные символы и сигналы в формализованном виде;<br>их можно хранить, передавать и обрабатывать, не понимая смысла; могут содержать ошибки"]
    I["<b>Информация</b> — содержание<br>смысл, который получатель извлекает из данных, интерпретируя их;<br>уменьшает неопределённость; зависит от получателя и относится к конкретному случаю"]
    K["<b>Знания</b><br>закономерности предметной области для решения задач; факты + правила;<br>интерпретируемы, связны, активны, правдоподобны"]
    W["<b>Мудрость</b><br>оценка и выбор лучшего действия с учётом ценностей: почему, что лучше;<br>по Акоффу, только у человека"]
    INT["<b>Интеллект</b><br>способность приобретать, хранить и применять знания для достижения целей;<br>не уровень, а процесс переходов"]
    AI["<b>Искусственный интеллект</b><br>комплекс технологических решений, имитирующий когнитивные функции человека<br>и дающий результаты, как минимум сопоставимые с интеллектуальной деятельностью человека"]

    F -->|фиксация| D
    D -->|интерпретация получателем в контексте| I
    I -->|обобщение, выявление закономерностей| K
    K -.->|нужны для интерпретации| I
    K -->|оценка, выбор| W
    W ~~~ INT
    INT -.->|выполняет переходы между уровнями| K
    INT -->|имитируется| AI

    classDef fact fill:#f1f3f5,stroke:#495057,stroke-width:2px,color:#111
    classDef data fill:#e7f5ff,stroke:#1971c2,stroke-width:2px,color:#111
    classDef info fill:#ebfbee,stroke:#2b8a3e,stroke-width:2px,color:#111
    classDef know fill:#fff4e6,stroke:#e8590c,stroke-width:2px,color:#111
    classDef wis fill:#fff0f6,stroke:#c2255c,stroke-width:2px,color:#111
    classDef intel fill:#f3f0ff,stroke:#6741d9,stroke-width:2px,color:#111
    classDef ai fill:#e3fafc,stroke:#0c8599,stroke-width:2px,color:#111
    class F fact
    class D data
    class I info
    class K know
    class W wis
    class INT intel
    class AI ai
```

**Источники определений:**

- Данные, информация — ISO/IEC 2382 (по вторичным цитатам: [Squoring](https://support.squoring.com/documentation/16.3/reference_manual/ch07s73.html)); информация в праве РФ — [149-ФЗ, ст. 2](https://normativ.kontur.ru/document/1/504575-federalnyy-zakon-ot-27-07-2006-n-149-fz)
- Иерархия DIKW, мудрость — Акофф, 1989 ([ISKO](https://isko.org/cyclo/dikw))
- Знания, свойства знаний — инженерия знаний, Д. А. Поспелов ([studfile](https://studfile.net/preview/1529919/))
- Интеллект — Маккарти ([whatisai.pdf](https://www-formal.stanford.edu/jmc/whatisai.pdf))
- ИИ — Указ № 490, ГОСТ Р 59277-2020 ([Гарант](https://base.garant.ru/408559959))
