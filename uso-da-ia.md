# Registro de uso da IA

## 1. Estrutura e página inicial

- **Prompt/contexto:** Criar um site institucional estático em português para a Metalúrgica Horizonte Ltda., empresa fictícia, usando os dados oficiais do briefing e pelo menos as páginas Início, Serviços e Contato.
- **Gerado:** Estrutura inicial da página inicial, chamadas, números, diferenciais e proposta de imagem para o destaque.
- **Mantido:** Estrutura semântica, navegação relativa, números e diferenciais que constam no briefing.
- **Alterado/descartado:** A primeira proposta considerava fotografia externa e texto promocional não confirmado. Foi descartada antes de integrar ao site; a página usa uma ilustração SVG original e texto restrito ao briefing.

## 2. Requisitos e páginas internas

- **Prompt/contexto:** Aplicar o checklist R1–R11: menu consistente com página atual destacada, metadados em pt-BR, uma folha de estilos, layout responsivo, tabela de capacidade, contato e perguntas frequentes. Não inventar clientes, certificações, números ou endereços.
- **Gerado:** Conteúdo para `servicos.html` e `contato.html`, incluindo tabela de produção por turno e FAQ.
- **Mantido:** Quatro serviços, capacidade por turno, endereço, telefone, e-mail, horário e mercados, conforme os dados informados.
- **Alterado:** FAQ responde somente sobre serviços, mercados e horário, sem criar políticas ou promessas. A tabela apresenta as capacidades com a unidade e a estrutura dadas no briefing.

## 3. Estilos e validação

- **Prompt/contexto:** Aplicar a identidade visual azul `#3776AB`, amarelo `#FFD43B`, azul-escuro `#1F2937` e cinza-claro `#F3F4F6`, com CSS responsivo compartilhado.
- **Gerado:** Regras de layout e apresentação em `styles.css`.
- **Mantido:** Variáveis de cor, navegação responsiva, tabela com rolagem em telas estreitas e preferência por movimento reduzido.
- **Verificado:** Conferir `lang`, viewport, títulos, descrições, H1 único, texto alternativo, links relativos e conteúdo contra o briefing. Corrigir qualquer divergência antes de aceitar o código.

Não foram incluídos dados pessoais, senhas nem informações reais de empresas.