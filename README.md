# Blog Culinário

### Descrição

O Blog Culinário é um projeto de website voltado para a apresentação de receitas de forma simples, organizada e fácil de navegar. O projeto foi planejado considerando requisitos, arquitetura de informação, wireframes, identidade visual, estrutura de pastas, infraestrutura e controle de versão.

### Objetivo

O objetivo é desenvolver a estrutura e o planejamento de um blog culinário composto por três páginas interligadas, preparando o projeto para a etapa posterior de desenvolvimento em HTML, CSS e JavaScript.

### Escopo

O projeto possui:

* Página inicial;
* Página de receita;
* Página de contato;
* Navegação entre as páginas;
* Wireframes;
* Identidade visual;
* Estrutura de pastas;
* Documentação;
* Controle de versão com Git e GitHub.

### Páginas do Projeto

#### Página Inicial

Apresenta o blog, receitas em destaque e acesso às demais páginas.
[Wireframe da Página Inicial](docs/wireframes/home.png)

#### Página de Receita

Apresenta uma receita com imagem, ingredientes e modo de preparo.
[Wireframe da Página de Receita](docs/wireframes/receita.png)

#### Página de Contato

Apresenta informações de contato e um formulário para envio de mensagens.
[Wireframe da Página de Contato](docs/wireframes/contato.png)

### Requisitos Funcionais

**RF01:** O sistema deverá apresentar a página inicial do blog.
**RF02:** O sistema deverá permitir a visualização de receitas.
**RF03:** O sistema deverá permitir a navegação entre as três páginas.
**RF04:** A página de receita deverá apresentar ingredientes e modo de preparo.
**RF05:** O sistema deverá possuir uma página de contato.

### Requisitos Não Funcionais

**RNF01:** O site deverá ser responsivo.
**RNF02:** A interface deverá ser simples e fácil de utilizar.
**RNF03:** O site deverá utilizar HTML semântico.
**RNF04:** Os arquivos deverão ser organizados de acordo com suas funções.
**RNF05:** O site deverá funcionar em navegadores modernos.

### Árvore de Navegação

```
Blog Culinário
│
├── Início
│   └── Receitas
│
├── Receita
│   ├── Ingredientes
│   └── Modo de preparo
│
└── Contato
```

### Wireframes

Os wireframes foram desenvolvidos durante a etapa de planejamento e representam a estrutura das páginas antes da implementação.

Os arquivos estão disponíveis na pasta:

```
docs/wireframes/
```

### Paleta de Cores

O projeto utiliza a regra de cores 60-30-10.


60%: Creme | HEX: #FFF8F0 - Fundo e áreas principais
30%: Verde sálvia | HEX: #7A9E7E - Navegação e elementos estruturais 
10%: Terracota | HEX: #C26046 - Botões e destaques

### Tipografia

* **Playfair Display:** Utilizada nos títulos.
* **Montserrat:** Utilizada nos textos, menus e botões.

### Estrutura do Projeto

```
blog-culinario/
│
├── README.md
│
├── assets/
│   ├── images/
│   └── icons/
│
├── css/
│   └── style.css
│
├── js/
│   └── script.js
│
├── pages/
│   ├── receitas.html
│   ├── receita.html
│   └── contato.html
│
├── docs/
│    └── wireframes/
│        ├── home.png
│        ├── receita.png
│        └── contato.png
│
└── index.html
```

### EAP — Estrutura Analítica do Projeto
                  
1.0 - Planejamento               
1.1 - Definição do tema          
1.2 - Definição do objetivo      
1.3 - Definição do escopo        
1.4 - Levantamento de requisitos 
2.0 - Arquitetura e UX           
2.1 - Pesquisa de referências    
2.2 - Árvore de navegação        
2.3 - Criação dos wireframes     
3.0 - Identidade visual          
3.1 - Definição das cores        
3.2 - Definição da tipografia    
4.0 - Estrutura técnica          
4.1 - Estrutura de pastas        
4.2 - Definição dos arquivos     
4.3 - Definição das tecnologias  
5.0 - Desenvolvimento            
5.1 - HTML                       
5.2 - CSS                        
5.3 - JavaScript                 
6.0 - Testes                     
6.1 - Testes de navegação        
6.2 - Testes de responsividade   
6.3 - Correção de problemas      
7.0 - Entrega                    
7.1 - Revisão                    
7.2 - Versionamento              
7.3 - Publicação no GitHub       

### Cronograma

O cronograma do projeto foi organizado por etapas semanais, distribuindo as atividades de forma sequencial para facilitar o acompanhamento do desenvolvimento.

Semana 1 - planejamento, definição de requisitos e arquitetura de navegação
Semana 2 - desenvolvimento dos wireframes, identidade visual e estrutura de pastas
Semana 3 - implementação da estrutura HTML e estilização com CSS
Semana 4 - implementação de JavaScript, testes, revisão e entrega final

### Equipe e Responsabilidades

O projeto utiliza os papéis do Scrum como referência para organização das atividades.

Product Owner - definir objetivos e prioridades do projeto
Scrum Master - organizar atividades e acompanhar prazos
UX/UI Designer - desenvolver arquitetura da informação, wireframes e identidade visual
Desenvolvedor - implementar o site
QA - realizar testes e verificar a qualidade do sistema

### Recursos Materiais

Para o desenvolvimento serão utilizados:

* Computador ou notebook;
* Conexão com a Internet;
* Visual Studio Code;
* Git;
* GitHub;
* Navegador Web;
* Ferramenta de criação de wireframes.

### Infraestrutura

O desenvolvimento será realizado localmente em um computador utilizando o Visual Studio Code. O Git será utilizado para controle de versão e o GitHub para armazenamento remoto do projeto.

A estrutura será:

```
Computador -> Visual Studio Code -> Git -> GitHub
```

### Plataforma Computacional

A plataforma escolhida é a Web.

As principais tecnologias utilizadas serão:

HTML5;
CSS3;
JavaScript;
Git;
GitHub.

A plataforma Web foi escolhida porque permite acessar o site por meio de navegadores em diferentes dispositivos.

### Controle de Versão

O projeto utiliza Git para controle de versão e GitHub para armazenamento do repositório.

Principais comandos utilizados:

```bash
git init
git add .
git commit -m "mensagem do commit"
git push
```

### Especificação de Hardware

O desenvolvimento será realizado em um computador ou notebook com configuração adequada para executar as ferramentas utilizadas no projeto.

* Processador: Dual Core ou superior.
* Memória RAM: 8 GB ou superior.
* Armazenamento: espaço disponível para os arquivos do projeto.
* Conexão com a Internet.

### Infraestrutura e Hospedagem

A versão final do site será hospedada no GitHub Pages, permitindo que o Blog Culinário seja acessado pela Internet através de um navegador.

### Mapeamento de Requisitos e Componentes

Os requisitos do projeto estão relacionados aos principais componentes da aplicação:

* **RF01:** Página inicial.
* **RF02:** Página de receitas.
* **RF03:** Menu de navegação entre as páginas.
* **RF04:** Página de conteúdo das receitas.
* **RF05:** Página de contato.

Os requisitos não funcionais são aplicados principalmente na estrutura HTML semântica, estilização com CSS, organização dos arquivos, responsividade e compatibilidade com navegadores modernos.

### Cronograma de Desenvolvimento

O desenvolvimento do projeto será realizado de forma sequencial, considerando as etapas já concluídas e as próximas atividades.

**07/08/2026:** Pesquisa de referências, estudo de UX e criação dos wireframes.
**Responsável:** Desenvolvedor.

**13/08/2026:** Definição da identidade visual, paleta de cores, tipografia e organização dos assets.
**Responsável:** Desenvolvedor.

**14/08/2026:** Atualização da documentação, arquitetura e planejamento do projeto.
**Responsável:** Desenvolvedor.

**15/08/2026:** Desenvolvimento da estrutura das páginas utilizando HTML semântico.
**Responsável:** Desenvolvedor.

**16/08/2026:** Implementação da identidade visual utilizando CSS.
**Responsável:** Desenvolvedor.

**17/08/2026:** Integração das páginas e dos recursos visuais.
**Responsável:** Desenvolvedor.

**18/08/2026:** Testes de navegação, funcionamento e responsividade.
**Responsável:** Desenvolvedor.

**19/08/2026:** Correções e revisão final do projeto.
**Responsável:** Desenvolvedor.

**20/08/2026:** Versionamento e publicação da versão final.
**Responsável:** Desenvolvedor.



### Próximas Etapas

Após a conclusão do planejamento, serão realizadas as seguintes atividades:

1. Desenvolvimento da estrutura HTML;
2. Aplicação dos estilos CSS;
3. Implementação das funcionalidades JavaScript;
4. Integração das páginas;
5. Testes de navegação e responsividade;
6. Correção de problemas;
7. Atualização da documentação;
8. Publicação da versão final.

### Status do Projeto

**Etapa atual:** Planejamento e estruturação da SA01.

**Situação:** Pronto para a etapa de desenvolvimento.

### Informações do Projeto

**Projeto:** Blog Culinário
**Curso:** Técnico em Desenvolvimento de Sistemas
**Unidade Curricular:** Projetos de Software
**Instituição:** SENAI