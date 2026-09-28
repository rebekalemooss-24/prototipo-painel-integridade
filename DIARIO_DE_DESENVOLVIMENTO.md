# Diário de Desenvolvimento

## 28/09/2026 - Preparação para portfólio

### Objetivo

Transformar o protótipo existente em uma demonstração honesta e apresentável, sem sugerir que dados fictícios ou funcionalidades planejadas já constituem um sistema de IA em produção.

### Alterações realizadas

- inclusão de aviso visível sobre o uso de dados sintéticos;
- implementação da exportação da visão filtrada em CSV;
- criação de documentação com escopo, tecnologias, execução, limitações e próximos passos.

### Decisões técnicas

- a exportação foi implementada no navegador com `Blob` e `URL.createObjectURL`, mantendo o projeto sem dependências;
- o CSV utiliza ponto e vírgula e marcador UTF-8 para melhorar a abertura em planilhas configuradas em português;
- a exportação respeita a aba e os filtros atualmente selecionados.

### Conceitos praticados

- transformação de objetos JavaScript em dados tabulares;
- escape de valores para o formato CSV;
- geração e download de arquivos no navegador;
- comunicação responsável de limitações em projetos analíticos.

### Pendências

- testar visualmente em diferentes tamanhos de tela;
- validar o arquivo CSV exportado;
- publicar uma demonstração no GitHub Pages;
- adicionar uma captura de tela ao README.
