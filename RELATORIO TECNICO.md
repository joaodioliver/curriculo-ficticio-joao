# Relatório Técnico — Currículo em HTML/CSS

## Visão Geral
Este repositório contém um currículo ficcional desenvolvido em HTML5 e CSS3, projetado para ser simples, responsivo e de fácil personalização.  
O arquivo principal é `index.html`, que já possui uma estrutura pronta para exibir informações pessoais, profissionais e acadêmicas.

## Estrutura do Projeto
```
index.html
```

- HTML semântico: Utiliza tags modernas (`<header>`, `<main>`, `<section>`, `<aside>`, `<footer>`) para melhor organização e acessibilidade.  
- CSS interno: Os estilos estão incluídos dentro do arquivo (`<style>`), mas podem ser facilmente separados em um arquivo `styles.css`.  
- Fonte: Usa a família `Inter`, carregada do Google Fonts.  
- Responsividade: Implementada com CSS Grid e media queries para adaptação em telas menores.  
- Suporte à impressão: Estilos dedicados em `@media print` permitem salvar o currículo em PDF diretamente do navegador.

## Estilo e Layout
- Cores principais:  
  - Fundo: `#f7f8fb`  
  - Cartão: `#ffffff`  
  - Acento (links e destaques): `#0b72ff`  
- Componentes:  
  - Card centralizado com sombra suave.  
  - Cabeçalho com avatar (personalizável), nome, título e contatos.  
  - Conteúdo principal dividido em duas colunas:  
    - Coluna esquerda: resumo, experiência, projetos.  
    - Coluna direita (aside): habilidades, educação, certificações e idiomas.  
  - Rodapé com dica de personalização.  

## Seções do Currículo
- Resumo: breve apresentação profissional.  
- Experiência: histórico de trabalho com cargos, períodos e responsabilidades.  
- Projetos: destaque para iniciativas acadêmicas ou pessoais.  
- Habilidades: lista de conhecimentos técnicos e interpessoais.  
- Educação: informações acadêmicas.  
- Certificações: cursos ou certificações relevantes.  
- Idiomas: níveis de proficiência.  

## Funcionalidade de Impressão
Um botão "Imprimir / Salvar PDF" foi incluído no cabeçalho.  
Ele chama `window.print()`, permitindo exportar o currículo para PDF com layout otimizado para impressão.

## Como Usar
1. Clone o repositório ou baixe o arquivo:  
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Abra o `index.html` em qualquer navegador moderno.  
3. Edite as informações diretamente no arquivo ou utilize um editor como VS Code.  
4. (Opcional) Extraia os estilos para um arquivo `styles.css` para facilitar manutenção.  

## Personalização
- Alterar cores em `:root` (variáveis CSS).  
- Substituir o avatar por uma imagem real.  
- Editar os textos com suas próprias informações.  
- Adaptar fontes ou adicionar bibliotecas externas.  

## Licença
Este projeto pode ser utilizado livremente para fins pessoais.  
Recomenda-se manter a atribuição e, se possível, contribuir com melhorias.  




