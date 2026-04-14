# Help Desk Processual — Coelho Diniz

Sistema de documentação e controle de tarefas para agências de publicidade, desenvolvido para organizar e acompanhar a rotina operacional da equipe de criação e mídia.

## Para que serve

Este sistema centraliza todos os processos semanais de produção de material publicitário em um único painel interativo, permitindo que a equipe:

- **Acompanhe o status de cada tarefa** com checklists por etapa, organizados por categoria de material e dia da semana.
- **Registre aprovações formalmente** com carimbo de data e hora, garantindo rastreabilidade de quem aprovou o quê e quando.
- **Visualize o progresso geral** da semana em tempo real, com barras e percentuais atualizados automaticamente.
- **Consulte orientações de processo** para cada módulo, com descrições sobre pontos críticos, regras e sequência obrigatória de execução.
- **Gestão de Tempo em Tempo Real**: Temporizadores automáticos por tarefa que permitem medir com precisão o tempo gasto em cada etapa do processo.
- **Dashboard de Desempenho**: Painel analítico com gráficos visuais (barras e progresso global) para acompanhamento de métricas de produtividade.
- **Exportação de Relatórios**: Função de download de relatório oficial no formato A4 Paisagem (Landscape) com formatação em negrito de alta visibilidade.

## Módulos cobertos

**Materiais de campanha:**
- Ofertas Diárias e Ofertas Especiais
- Cartaz Frente de Loja
- Placas do Dia
- Instagram (stories e feed)
- G1
- ANÚNCIOS JORNAL DIÁRIO DO AÇO
- VT's TV Coelho Diniz

**Rotina semanal:**
- Terça-feira — Preparação de ofertas TV (quinta a domingo)
- Quarta-feira — Aprovação e programação completa
- Quinta-feira — Conferência de postagens
- Sexta-feira — Ofertas TV + programação (segunda a quarta)
- Segunda-feira — Conferência de postagens

## Tecnologias e Funcionalidades

### Cronometragem Inteligente
O sistema utiliza um motor de tempo com **exclusividade mútua**: ao iniciar uma tarefa, qualquer outra tarefa ativa é pausada automaticamente. Além disso, ao concluir uma tarefa (check), o sistema inicia automaticamente o cronômetro da tarefa seguinte, otimizando o fluxo de trabalho.

### Relatórios PDF
O botão "Gerar PDF" no Dashboard cria um documento otimizado para auditoria, utilizando estilos de impressão (Media Print) que removem elementos desnecessários da UI e destacam as métricas em negrito de alto contraste no formato horizontal.

## Como usar

Abra o arquivo `index.html` diretamente no navegador. Não requer servidor ou instalação. Todo o progresso é salvo automaticamente no navegador via `localStorage`.

---
*Documentação atualizada em 12 de Abril de 2026*
