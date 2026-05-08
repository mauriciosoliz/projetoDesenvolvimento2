# Meu “Identity Provider”
#### Sistema web para sincronizar usuários e grupos com aplicações cloud (Confluence e Jira)

Mauricio da Costa Soliz

Este artigo tem como objetivo apresentar o projeto final na unidade curricular Projeto de Desenvolvimento II do cursos de Análise e Desenvolvimento de Sistemas do Centro Universitário Senac-RS.

-----

## Resumo do Projeto
O projeto “Meu Identity Provider” consiste no desenvolvimento de um sistema web que simplifica a execução e a integração de REST APIs voltadas à sincronização de usuários e grupos com aplicações em nuvem (Confluence e Jira). A solução busca oferecer uma interface gráfica intuitiva que substitua a necessidade de interação via terminal, facilitando o trabalho de engenheiros de suporte e administradores de sistemas.

## Definição do Problema
Atualmente, engenheiros de suporte enfrentam dificuldades ao interagir diretamente com REST APIs por meio do terminal. Esse processo exige conhecimento técnico aprofundado, consome tempo e pode gerar erros de execução. Há, portanto, a necessidade de uma ferramenta que automatize e simplifique a interação com essas APIs, proporcionando maior produtividade e menor risco operacional.

## Objetivos
O objetivo geral desse projeto é desenvolver um sistema web que permita a execução de REST APIs via interface gráfica, oferecendo recursos de autenticação, sincronização e gerenciamento de usuários e grupos em aplicações cloud.

Como objetivos específicos desse projeto, a fim de alcançar o objetivo geral, podemos citar alguns mais importantes, sendo eles:
* Criar um painel web para gerenciamento de chamadas REST APIs.
* Disponibilizar funcionalidades para sincronização de usuários e grupos com aplicações em nuvem (Confluence e Jira).
* Reduzir o tempo de operação e os erros associados ao uso manual de chamadas REST APIs via terminal.
* Proporcionar uma experiência de uso simples e acessível para equipes de suporte.

## Stack Tecnológico
O desenvolvimento do sistema “Meu Identity Provider” utilizará tecnologias consolidadas e acessíveis, garantindo zero custo de infraestrutura e simplicidade na implementação:

* **Hospedagem: InfinityFree** 
Será utilizado o serviço **InfinityFree**, uma plataforma de hospedagem gratuita que oferece suporte a PHP e MySQL. Essa escolha garante praticidade para o desenvolvimento inicial, permitindo que o sistema esteja disponível online sem custos adicionais, atendendo bem às necessidades de prototipagem, testes, e implementação da solução.
* **Banco de Dados Relacional: MySQL**
O **MySQL** será empregado para armazenamento de dados de usuários, grupos e registros de sincronização. Como um banco de dados relacional amplamente adotado, oferece robustez, compatibilidade com diversas aplicações cloud e facilidade de integração com PHP.
* **Backend: PHP**
A camada de backend será implementada em **PHP**, linguagem consolidada para aplicações web e com excelente integração com o MySQL. O PHP possibilitará a criação das APIs necessárias para comunicação entre o frontend e o banco de dados.

* **Frontend: Página Web Responsiva (HTML, CSS e JavaScript)**
A interface será desenvolvida como uma página web responsiva, garantindo acessibilidade tanto em desktops quanto em dispositivos móveis. Serão utilizados **HTML5, CSS3 e JavaScript** para estruturar e dinamizar a aplicação, buscando oferecer uma experiência simples, intuitiva e amigável aos engenheiros de suporte.

## Descrição da Solução
O sistema “Meu Identity Provider” será disponibilizado como uma aplicação web hospedada no serviço InfinityFree, garantindo acesso remoto aos usuários e permitindo que engenheiros de suporte utilizem a ferramenta sem necessidade de instalação local.

A solução contará com uma **interface web responsiva**, construída em **HTML5, CSS3 e JavaScript**, que possibilitará a interação direta com REST APIs de forma simplificada. A interface será projetada para oferecer formulários de cadastros (usuários e grupos), botões de execução de chamadas e visualização de resultados, eliminando a dependência de interações via terminal.

O **backend em PHP** será responsável por processar as requisições feitas no frontend, implementar as chamadas REST APIs externas e a comunicação com o banco de dados. Essa camada também será a responsável pela validação de dados e registro de logs de execução.

O **banco de dados MySQL** armazenará informações essenciais, tais como:
* Cadastro de usuários e grupos;
* Registros de sincronizações realizadas;
* Logs de chamadas às APIs (incluindo resultados e possíveis erros).

Com essa arquitetura, o sistema permitirá que engenheiros de suporte realizem operações de forma mais intuitiva, com menor risco de erro e maior produtividade. Além disso, por ser uma aplicação responsiva, poderá ser acessada em diferentes dispositivos (computadores, tablets e smartphones), aumentando a flexibilidade de uso.

## Arquitetura
abcdefghijklmnopqrstuwxyz

## Validação
abcdefghijklmnopqrstuwxyz

## Estratégia
abcdefghijklmnopqrstuwxyz

## Consolidação dos Dados Coletados
abcdefghijklmnopqrstuwxyz

## Conclusão
abcdefghijklmnopqrstuwxyz

## Limitações do Projeto e Perspectivas Futuras
abcdefghijklmnopqrstuwxyz

## Referências Bibliográficas
abcdefghijklmnopqrstuwxyz
