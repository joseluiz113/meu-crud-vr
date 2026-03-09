📑 Seguradora VR - Sistema de Gestão de Frota
Este é um projeto de Realidade Virtual (WebVR) desenvolvido para a gestão dinâmica de frotas de veículos em uma seguradora. O sistema permite realizar todas as operações de um CRUD (Create, Read, Update, Delete) diretamente em um ambiente 3D imersivo.

Status do Projeto: 🚀 Finalizado para entrega acadêmica.

🚀 Funcionalidades (Verbos HTTP Simulados)
O sistema foi construído seguindo a lógica de uma API REST, utilizando o LocalStorage do navegador como banco de dados persistente:

[POST] Create: Adicione novos veículos à frota informando placa e cor através do painel lateral.

[GET] Read: Visualização em tempo real de todos os veículos cadastrados, renderizados como objetos 3D.

[PUT] Update: Clique em qualquer veículo na cena para editar suas informações (placa/cor) dinamicamente.

[DELETE] Delete: Remova veículos da frota e do banco de dados com apenas um clique.

🛠️ Tecnologias Utilizadas
A-Frame: Framework para criação de experiências de Realidade Virtual na Web.

JavaScript (ES6+): Lógica de manipulação de DOM, eventos e persistência de dados.

HTML5 & CSS3: Interface de controle (HUD) com design futurista/neon.

Web Storage API: Utilização de localStorage para persistência dos registros sem necessidade de backend.

🎨 Diferenciais do Projeto
Ambiente Imersivo: Cenário com iluminação ambiente e ponto de luz para realce metálico dos veículos.

Animações Fluídas: Os veículos possuem animação de flutuação (hovering) para uma estética moderna.

Mocks Iniciais: O sistema inicia com dados aleatórios pré-carregados caso o banco esteja vazio.

Design Responsivo: Painel de controle adaptado para não obstruir a visão da cena VR.

🔧 Como Rodar o Projeto
Clone este repositório:

Bash
git clone https://github.com/joseluiz113/meu-crud-vr.git
Abra o arquivo index.html em qualquer navegador moderno ou utilize uma extensão de Live Server
