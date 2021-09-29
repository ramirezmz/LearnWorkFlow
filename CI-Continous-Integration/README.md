# INTEGRAÇÃO CONTINUA
Nico Steppat

![](./images/img01.png)

Continuous Integration (CI) is a development practice that require developers to integrate code into a shared repository several times a day.

ThoughtWorks


* Ferramentas não importa
* Commit tudo necessário para construção do projeto
	* código,
	* scripts,
	* migrações, schemas,
	* IDES Configs
* NÃO comitar o que pode ser construído (gem, jar, image, modules)
* clone e começar (deve ser fácil)

## ORGANIZAÇÃO DOS REPOSITÓRIOS

Multi-repo
Mono-repo
Meta-repo

## Branching Models / Strategy / Policy

![](./images/img05.png)


![](./images/img06.png)

## Branching Models
Git flow
Github flow
Trunk Based Development
Gitlab flow
Pull request flow
Feature branch flow
One flow

"Everyone Commits To the Mainline Every Day" - Martin Fowler

* Commits simples e lançáveis, orientado às tarefas.
* Branches atrasam integração, seguram o código.
* Branches de vida curta -> merges mais simples.
* Muitos branches, mais burocracia.
* Estratégias devem ser combinadas pela equipe.

### Branchings Models

* Temporários (branches locais)
* Features Branches: para implementar alguma funcionalidade ou tarefa.
* Historical Branches(Master e Develop)
* Environment Branches (Staging e Production)
* Maintenance Branches (Release e Hotfix)

### Trunk-Based Development
![](./images/img05.png)

"Trunk-Based Development is a branching model that reduces this distance (between branches) to the minimum."
https://trunkbaseddevelopment.com/


### Feature Branch Workflow (Master + Feature Branches)

![](./images/img08.png)

![](./images/img09.png)

pull = é um pedido para nosso commit entrar no Master

[Github Flow](https://guides.github.com/introduction/flow/) (Master + Feature Branch + Pull Request)

### Gitlab Flow (Feature Branch + Pull Request +ENV Branches)

![](./images/img10.png)


### Git Flow (Feature Branches + Pull Request + Maintenance Branches + Historical Branches)

![](./images/img11.png)
https://danielkummer.github.io/git-flow-cheatsheet/index.pt_BR.html




### Fontes usadas

* Livro: Continuous Integration, de Paul M. Duvall
* Artigo da ThoughtWorks: Continuous integration
* Artigo do Martin Fowler: Continuous Delivery
* Série de artigos da Caelum:
* Branches e integração contínua: o problema de feature branches
* Integração Contínua - Builds rápidos com Grids e paralelismo
* Integração contínua: deploys e aprovações sem dor de cabeça para o cliente
* Artigo no CodeBetter: Check in Dance