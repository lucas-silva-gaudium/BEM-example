# 📌 Resumo sobre BEM
##### A metodologia BEM (Block, Element, Modifier) organiza o CSS de forma mais clara, reutilizável e fácil de manter. Ela segue uma convenção de nomes que ajuda a entender a estrutura e a responsabilidade de cada classe no HTML/CSS:

- Bloco (.bloco): é um componente independente da interface (ex: .user-card).
- Elemento (.bloco__elemento): é uma parte do bloco que depende dele para existir (ex: .user-card__button).
- Modificador (.bloco__elemento--modificador): é uma variação de aparência ou comportamento do bloco ou elemento (ex: .user-card__button--following).

BEM evita conflitos, melhora a legibilidade e torna o código mais fácil de escalar em projetos grandes.