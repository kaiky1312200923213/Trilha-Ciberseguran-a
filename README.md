# Trilha de Cibersegurança — Roadmap pessoal

**Autor:** Kaiky Yoshio Ono Marins  
**Portfólio geral:** [kaikysec.vercel.app](https://kaikysec.vercel.app/)  
**Aplicação:** [Abrir a Trilha de Cibersegurança](https://kaikysec.vercel.app/trilha.html)  
**Categoria:** JavaScript · Aplicação web · Cibersegurança

## Visão geral

Aplicação web para organizar uma jornada de estudos em cibersegurança. O conteúdo é dividido em oito fases, desde fundamentos de Linux até áreas como Web/AppSec, Red Team, Blue Team e certificações.

## Problema e proposta

Cursos, laboratórios e materiais de estudo costumam ficar espalhados por diferentes plataformas. A proposta deste projeto é reunir uma sequência de estudos em uma interface única e permitir que a pessoa acompanhe o próprio progresso.

## Funcionalidades implementadas

- Navegação entre oito fases de estudo.
- Lista de cursos, materiais e laboratórios por fase.
- Estados por atividade: quero fazer, fazendo e concluído.
- Progresso geral e progresso por fase.
- Opção para ocultar atividades concluídas.
- Backup e restauração do progresso em arquivo JSON.
- Interface responsiva para computador e celular.

## Implementação técnica

O projeto é uma aplicação estática construída com HTML, CSS e JavaScript. O estado de cada atividade é salvo no armazenamento local do navegador, sem depender de uma conta ou banco de dados remoto. A exportação e importação em JSON permitem transferir o progresso manualmente.

## Tecnologias

- HTML5
- CSS3
- JavaScript
- Vercel
- Armazenamento local do navegador

## Como executar

1. Clone ou baixe este repositório.
2. Abra o arquivo `trilha.html` em um navegador moderno.
3. O progresso será guardado no navegador utilizado.

Não é necessário instalar dependências ou executar um processo de build.

## Limitações e próximos passos

- O progresso fica somente no navegador e dispositivo utilizados; não existe sincronização em nuvem.
- Os links para cursos e plataformas externas podem mudar e devem ser conferidos.
- Uma evolução possível é adicionar testes automatizados e sincronização opcional entre dispositivos.

## Outros arquivos

- `trilha.html` — aplicação da trilha.
- `index.html` — página do portfólio pessoal.
- `vercel.json` — cabeçalhos HTTP de segurança da hospedagem.

© 2026 Kaiky Yoshio Ono Marins. Todos os direitos reservados.
