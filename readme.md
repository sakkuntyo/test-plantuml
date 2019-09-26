## what's this

This repository for checking plantuml display via pegmatite

## Operating environment

- [Pegmatite](https://chrome.google.com/webstore/detail/pegmatite/jegkfbnfbfnohncpcfcimepibmhlkldo)(Chrome Extension)

## test source

```uml
@startuml
Alice -> Bob: Authentication Request
Bob --> Alice: Authentication Response
 
Alice -> Bob: Another authentication Request
Alice <-- Bob: another authentication Response
@enduml
```
