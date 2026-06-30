# 🛡️ Agente de Auxílio à Segurança Bancária

<img width="1907" height="870" alt="image" src="https://github.com/user-attachments/assets/2bd8f097-5667-41ed-9c41-4ecbc5eb03c5" />

---

## 🔗 Acesso ao NotebookLM

O caderno temático desenvolvido para este projeto pode ser acessado através do link abaixo:

**NotebookLM:**
https://notebooklm.google.com/notebook/7feae437-ede3-4fd0-9af0-f57912c70e4a

> **Observação:** caso o compartilhamento esteja indisponível, toda a documentação do projeto, incluindo objetivos, fontes, prompts e guia de estudo, encontra-se neste repositório.

---

## 📖 Sobre o projeto

Este projeto foi desenvolvido utilizando o **NotebookLM** como ferramenta de aprendizagem ativa para criar um agente especializado em **segurança digital bancária**.

O objetivo não foi apenas reunir documentos sobre cibersegurança, mas construir uma base de conhecimento capaz de orientar usuários na proteção de suas contas bancárias, prevenção de golpes digitais e adoção de boas práticas de segurança.

O projeto faz parte de um desafio prático da DIO para **Bootcamp Bradesco - GenAI, Dados & Cyber**, cujo foco é demonstrar a capacidade de realizar curadoria de fontes, engenharia de prompts e organização do conhecimento utilizando Inteligência Artificial.

---

# 🎯 Objetivos

O agente foi projetado para auxiliar usuários a:

* Identificar golpes bancários comuns;
* Compreender boas práticas de segurança digital;
* Proteger contas bancárias utilizando autenticação multifator e outras camadas de segurança;
* Entender seus direitos relacionados à proteção de dados;
* Saber como agir em situações de fraude, invasão ou vazamento de informações.

---

# 🧠 Objetivos de aprendizagem

Durante o desenvolvimento deste projeto procurei compreender como a qualidade da curadoria de fontes influencia diretamente a capacidade de uma IA responder com precisão e confiabilidade.

Além disso, busquei desenvolver habilidades de engenharia de prompts, organização do conhecimento e documentação técnica utilizando o NotebookLM.

---

# 📚 Curadoria das fontes

As fontes foram selecionadas buscando equilibrar:

* Boas práticas internacionais de segurança;
* Legislação brasileira;
* Contexto do sistema bancário nacional;
* Proteção contra golpes digitais;
* Educação em segurança da informação.

| Fonte                         | Objetivo                               | Link                                                                                                                              |
| ----------------------------- | -------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| OWASP MFA Cheat Sheet         | Autenticação Multifator                | https://cheatsheetseries.owasp.org/cheatsheets/Multifactor_Authentication_Cheat_Sheet.html                                        |
| LGPD                          | Proteção de Dados                      | https://www.gov.br/mcti/pt-br/acesso-a-informacao/lei-geral-de-protecao-de-dados-pessoais-lgpd/09-2025_protecao-de-dados.pdf      |
| Banco Central                 | Segurança do Pix e prevenção a fraudes | https://www.bcb.gov.br/estabilidadefinanceira/pix-seguranca                                                                       |
| FEBRABAN Tech                 | Segurança no setor bancário brasileiro | https://www.youtube.com/watch?v=RgX4SgF7V64                                                                                       |
| CISA - Nine Ways to Stay Safe | Boas práticas de cibersegurança        | https://www.youtube.com/watch?v=laR7kRUIydA                                                                                       |

---

# 💬 Engenharia de Prompts

Durante os testes foram realizados diversos refinamentos de prompts para melhorar a qualidade das respostas.

## Exemplo 1

### Prompt inicial

> Como proteger minha conta bancária?

**Problema**

Resposta muito genérica.

---

### Prompt refinado

> Quais práticas reduzem significativamente o risco de fraudes bancárias utilizando apenas as fontes disponíveis?

**Resultado**

Respostas mais objetivas, contextualizadas e fundamentadas nas fontes.

---

## Exemplo 2

### Prompt inicial

> O que fazer após sofrer um golpe?

**Problema**

As respostas variavam bastante.

---

### Prompt refinado

> Elabore um plano de ação para um usuário que sofreu fraude bancária, considerando medidas imediatas, proteção dos dados pessoais e comunicação com a instituição financeira.

**Resultado**

Resposta estruturada em etapas, facilitando a tomada de decisão.

---

# ⚠️ Cicatrizes (Troubleshooting)

Durante a construção do NotebookLM alguns desafios foram encontrados:

* Fontes excessivamente técnicas geravam respostas pouco didáticas;
* Documentos normativos nem sempre explicavam conceitos para usuários comuns;
* Vídeos institucionais possuíam pouco conteúdo técnico;
* O equilíbrio entre fontes nacionais e internacionais foi essencial para melhorar a contextualização.

Esses problemas foram resolvidos por meio da substituição de fontes e refinamento contínuo dos prompts.

---

# 📝 Resumo estruturado

O agente identifica cinco categorias principais de ameaças.

Depois apresenta mecanismos de proteção.

Por fim orienta quais medidas devem ser tomadas caso o usuário seja vítima de fraude.

## Principais ameaças

* Phishing
* Engenharia Social
* Malware
* Ransomware
* Vazamento de Dados

---

## Principais mecanismos de proteção

* Autenticação Multifator (MFA)
* Senhas fortes
* Biometria
* Atualizações de segurança
* Monitoramento de atividades suspeitas

---

## O que fazer em caso de fraude

1. Contatar imediatamente o banco;
2. Bloquear cartões e acessos;
3. Alterar senhas;
4. Registrar boletim de ocorrência, quando necessário;
5. Verificar possibilidades de recuperação da transação, como o MED no Pix;
6. Monitorar movimentações da conta.

---

# 📚 Glossário

**MFA**
Autenticação utilizando dois ou mais fatores independentes.

**LGPD**
Lei Geral de Proteção de Dados.

**MED**
Mecanismo do Banco Central que possibilita a análise e eventual devolução de valores em casos específicos de fraude envolvendo Pix.

**Phishing**
Golpe que busca obter informações confidenciais por meio de mensagens falsas.

**Engenharia Social**
Manipulação psicológica utilizada para convencer vítimas a fornecer informações ou realizar ações.

---

# 🚀 Prompts reutilizáveis

* Como identificar um golpe bancário antes de se tornar vítima?
* Quais boas práticas aumentam a segurança de uma conta bancária?
* Elabore um checklist de segurança digital para usuários de internet banking.
* Explique a diferença entre phishing, malware e engenharia social.
* O que devo fazer imediatamente após perceber uma fraude em minha conta bancária?
* Como a LGPD protege meus dados em instituições financeiras?

---

# 📌 Considerações finais

Este projeto demonstrou como a qualidade da curadoria de fontes influencia diretamente o desempenho de sistemas baseados em IA.

Mais do que reunir documentos, o desafio consistiu em construir uma base de conhecimento consistente, capaz de gerar respostas úteis, contextualizadas e fundamentadas para auxiliar usuários na proteção de suas informações bancárias.

---

# 👨‍💻 Autor

Rafael Monteiro

Projeto desenvolvido durante o Bootcamp Bradesco - GenAI, Dados & Cyber da DIO.
