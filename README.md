# WebGIS Prototype - setmapgeo.com

Este projeto é um protótipo de WebGIS desenvolvido para explorar funcionalidades básicas de visualização e manipulação de mapas interativos usando a biblioteca Leaflet. Atualmente, o projeto está em fase embrionária e serve como base para futuras implementações e melhorias.

## Visão Geral

O WebGIS Prototype utiliza APIs públicas, como a API de Localidades do IBGE, para listar estados e municípios brasileiros, permitindo ao usuário aplicar zoom em áreas específicas do mapa. Além disso, o projeto integra camadas de diferentes fontes de mapas, como OSM (OpenStreetMap), satélite e híbrido, para melhorar a experiência de visualização.

## Funcionalidades Atuais

- **Mapa Interativo**: Implementado com a biblioteca Leaflet, permitindo zoom e navegação pelo mapa.
- **Seleção de Estado e Município**: Utiliza a API de Localidades do IBGE para preencher listas de estados e municípios, permitindo zoom no local selecionado.
- **Troca de Camadas de Mapa**: Opções para visualizar diferentes tipos de camadas, incluindo OSM, Satélite, Híbrido e Imagem.
- **Botão 'INICIAR'**: Ainda sem funcionalidade, mas destinado a futuras implementações de análise ou visualização adicional.

## Tecnologias Utilizadas

- **Leaflet**: Biblioteca JavaScript para mapas interativos.
- **HTML/CSS/JavaScript**: Estrutura básica da aplicação.
- **APIs**:
  - **IBGE API**: Para listar estados e municípios brasileiros.
  - **Nominatim**: Para geocodificação e obtenção de coordenadas de locais selecionados.

## Requisitos de Instalação

Para rodar este projeto localmente, siga os passos abaixo:

1. Clone o repositório:

   ```bash
   git clone https://github.com/seu-usuario/webgis-prototype.git
   ```

2. Navegue até o diretório do projeto:

   ```bash
   cd webgis-prototype
   ```

3. Abra o arquivo `index.html` no seu navegador para visualizar o protótipo.

## Próximos Passos

Este projeto está em desenvolvimento inicial. As seguintes funcionalidades estão previstas para futuras atualizações:

- **Implementação do Backend**: Desenvolvimento de endpoints para processar imagens de satélite ou análises GIS específicas.
- **Funcionalidade do Botão 'INICIAR'**: Integrar o botão a uma funcionalidade que traga dados adicionais ou análises específicas para a área visualizada.
- **Melhorias na Interface do Usuário**: Refinar o design e a usabilidade da aplicação.
- **Segurança e Otimização**: Implementar boas práticas de segurança e otimização para garantir uma experiência de usuário suave.
