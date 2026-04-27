# 🐾 Jornada Dev: Medicina Veterinária ➔ Machine Learning com Python

## 📖 Contexto e Objetivos
Este caderno temático documenta minha transição de carreira da **Medicina Veterinária** para a **Ciência de Dados/Programação**. O objetivo principal é dominar os fundamentos de Python (sintaxe, controle de fluxo e estruturas de dados) e boas práticas de engenharia de software (documentação e diagramação) para criar soluções tecnológicas aplicadas à saúde animal.

### Objetivos de Estudo:
* Implementar lógicas clínicas (como triagem e cálculos de doses) em Python.
* Aprender a documentar projetos como "produtos com manuais de instruções"
* Dominar ferramentas de visualização técnica (Mermaid) e hospedagem de documentação (MkDocs).

## 📚 Curadoria de Fontes
1. [Guia de Sobrevivência em Documentação (Py_Live #058):](https://www.youtube.com/watch?v=ZkD8-xqL5Vs) Vídeo focado em por que documentar é o maior diferencial de um desenvolvedor Júnior.
2. [Documentação Oficial do Python (v3.14.4):](https://docs.python.org/pt-br/3/tutorial/index.html) A fonte definitiva para aprender a sintaxe elegante e poderosa da linguagem;
3. [Documentação Oficial do Mermaid:](https://mermaid.ai/open-source/intro) Guia para criação de diagramas baseados em texto para documentação técnica.

## 🧠 Engenharia de Prompts e "Cicatrizes"
Nesta seção, registro o raciocínio lógico utilizado para extrair conhecimento da IA durante este caderno.
### Perguntas Estratégicas e Variações:
* **Prompt Inicial:** "Sou Veterinária e estou começando com Python. Me dê exercícios de nível básico a avançado."
  * **Resposta:** A IA sugeriu projetos como "Triagem Automatizada" e "Calculadora Veterinária", ligando a lógica de controle de fluxo (`if/else`) à rotina clínica.

* **Prompt de Aprofundamento:** "Como estruturar condições `if/else` para triagem?"
  * **Refinamento**: Foi necessário pedir para a IA explicar como combinar critérios.
  * **Solução:** Aprendi a usar operadores lógicos (`and`, `or`, `not`) para lidar com múltiplos parâmetros vitais simultaneamente.

### Cicatrizes (Troubleshooting):
* **Dificuldade:** Traduzir o "*feeling*" clínico em regras matemáticas rígidas.
* **Raciocínio:** Percebi que um projeto não é apenas código; ele precisa de um *manual*. Se a IA gera uma documentação automática, ela pode "alucinar" funcionalidades que o código não tem.
* **Lição:** A documentação deve nascer antes ou junto com o código para manter o escopo claro.

## 🛠️ Miniguia de Estudo
### 1. Resumo Estruturado: O Fluxo do Desenvolvimento
* **O Código:** *Python* é ideal por ser interpretado e possuir uma biblioteca padrão extensiva;
* **A Lógica:** O uso de `if`, `elif` e `else` permite criar ramificações de decisão, como classificar um animal em **"Prioridade Vermelha"** ou **"Verde"**;
* **A Documentação:** Deve ser vista como o **manual de instruções** do produto. Ferramentas como **MkDocs** transformam arquivos Markdown em sites profissionais, e o comando `mkdocs gh-deploy` facilita a hospedagem no **GitHub**.
* **A Visualização:** O **Mermaid** permite criar fluxogramas técnicos (*Flowcharts*) diretamente no **Markdown**, facilitando a comunicação da lógica de triagem.

### 2. Glossário de Conceitos-Chave
* **Markdown:** Linguagem de marcação simples para estruturar textos e manuais;
* **Mermaid:** Ferramenta que gera diagramas (ER, Sequência, Fluxo) a partir de texto;
* **MkDocs:** Gerador de sites estáticos focado em documentação de projetos;
* **Operadores Lógicos:** `and` (ambas verdadeiras), `or` (uma verdadeira), `not` (inverte a lógica);
* **Requisitos Funcionais:** O que o sistema deve fazer (ex: "calcular administração de medicamento no animal").

### 3. Prompts Reutilizáveis para Revisão
* *"Estou em migração de carreira de [ÁREA] para a Programação, iniciando por Python. Me dê ideias de exercícios e projetos baseados na [ATUAL PROFISSÃO] para fixar aprendizados de níveis básico, intermediário e avançado."*
* *"Gere um diagrama Mermaid do tipo Flowchart para a seguinte lógica de código: [COLE SEU CÓDIGO AQUI]."*
* *"Analise este script Python e sugira como posso tratar erros usando try/except para [DADOS DA SUA ÁREA] inválidos."*
