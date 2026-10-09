# 🛡️ Cyber Exposure • Conscientização em Cibersegurança

## 👥 Integrantes
* JEFERSON LUIDY DOS SANTOS
* DIOGO RAFAEL RIBEIRO MOTIN
* HEITOR CHEMIM SELSKI CABRAL PRADA
* JHENIFER KAROLINE VIEIRA
* KEROLLYN ALANA DA SILVA BELTRAME
* FERNANDO BUENO PEDROSO DA SILVA
  
---

# 📖 Sobre o projeto

O **Cyber Exposure** é um site educacional criado para conscientizar as pessoas sobre os riscos de exposição de dados pessoais na internet.

A ideia do projeto surgiu para resolver um problema comum: muitas pessoas não entendem de forma prática como suas informações podem ser usadas indevidamente (consultas de CPF, vazamentos, venda de dados, phishing e ataques DDoS).

No site, o usuário consegue simular consultas, visualizar exemplos de vazamentos, “comprar” pacotes de dados fictícios, capturar credenciais (de forma controlada) e entender o impacto de um ataque DDoS. Tudo isso de forma visual e interativa, com dados 100% fictícios.

As informações de login, registro e captura de credenciais são salvas no **Firebase Firestore**, permitindo que o professor e os alunos visualizem os dados coletados durante as demonstrações.

---

# 🎯 Objetivo do sistema

Nosso objetivo foi desenvolver um sistema visual, interativo e educativo para facilitar a compreensão dos riscos de privacidade e segurança digital.

O sistema permite que o usuário:

* criar uma conta e fazer login;
* simular consultas de exposição de dados;
* visualizar como uma consulta de CPF poderia expor informações;
* simular a “compra” de pacotes de dados (CPF, placa + CNH e localização);
* experimentar a captura de credenciais (phishing controlado);
* entender exemplos reais de vazamentos e suas consequências;
* visualizar o impacto de um ataque DDoS de forma interativa;
* ver um score de exposição digital;
* aprender boas práticas de proteção.


---

# ✅ Funcionalidades implementadas

* Tela de login e criação de conta (Firebase Authentication)
* Controle de sessão e logout
* Consulta de exposição de dados (simulada)
* Demonstração de consulta de CPF
* Simulação de venda de dados (CPF, placa + CNH e localização)
* Captura de credenciais 
* Exemplos educativos de vazamentos
* Simulação interativa de ataque DDoS
* Score de exposição digital com gráfico
* Seção de dicas de proteção
* Interface moderna com visual cyber/neon
* Design responsivo (mobile e desktop)


---

# 🛠 Tecnologias utilizadas

### Front-End
* HTML5
* CSS3
* JavaScript 

### Estilização
* CSS customizado 
* Font Awesome
* Google Fonts (Orbitron, Share Tech Mono, Inter)

### Gráficos
* Chart.js

### Banco de Dados e Autenticação
* Firebase Authentication
* Firebase Firestore

### Hospedagem 
* Firebase Hosting / GitHub Pages / Netlify

---

# 🗂 Estrutura do projeto

```text
Cyber-Exposure/
│
├── index.html          # Aplicação principal 
├── README.md
│
└── (opcional)
    ├── assets/         # Imagens e ícones
    └── docs/           # Documentação extra


🗄 Banco de Dados
O projeto utiliza o Firebase Firestore para armazenar os dados.
Coleções criadas:
usuarios

nome
email
senha
criadoEm

capturas

email
senha
nome (quando houver)
tipo (login | conta_criada | captura)
data


💡 Como funciona o sistema

O usuário cria uma conta ou faz login.
Após autenticado, tem acesso a todas as seções do site.
Pode simular consultas de exposição, CPF e venda de dados.
Pode testar a captura de credenciais.
Pode interagir com a simulação de DDoS e visualizar o score de exposição.


🚧 Melhorias futuras
Pretendemos adicionar novas funcionalidades, como:

Painel administrativo para visualizar as capturas
Mais simulações de ataques (phishing avançado, engenharia social)
Quiz de conscientização
Histórico de simulações por usuário
Modo escuro/claro
Versão em inglês
Relatórios de exposição mais detalhados


📷 Demonstração
O sistema possui uma interface moderna, com visual cyber/neon, responsiva e fácil de utilizar. Todas as simulações são controladas e utilizam apenas dados fictícios, permitindo que qualquer pessoa entenda os riscos de exposição digital de forma prática e segura.

❤️ Agradecimentos
Este projeto foi desenvolvido como atividade acadêmica com o objetivo de colocar em prática os conhecimentos adquiridos sobre desenvolvimento web, autenticação, banco de dados, integração com Firebase e organização de projetos utilizando GitHub.
Esperamos continuar evoluindo este projeto e implementar novas funcionalidades futuramente.
Ambiente controlado — Todos os dados são fictícios.

//SE FICOU ATÉ AQUI VOCÊ É O CARA E UM DETALHE, NEM TENTE HACKEAR ESSE SITE AGENTE TEM ACESSO A TODOS OS IP QUE ACESSA O SITE E EU CRIEI UM CERTIFICADO ESPECIAL ENTÃO É MELHOR NÃO TENTAR PORQUE AS CONSEQUENCIAS SERÃO GRAVES!//
