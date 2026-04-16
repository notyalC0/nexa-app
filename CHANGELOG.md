# Changelog

Todas as mudanças relevantes do Nexa ficam registradas aqui.

## 1.4.0

- Metas financeiras: nova aba dedicada com criação, edição, exclusão e progresso de metas
- Reserva de emergência: migração de `settings` para uma meta padrão persistida em banco
- Aportes em metas: transações agora aceitam vínculo opcional via `goal_id`
- Saldo real por competência: `transactions` agora distinguem `purchase_date` e `effective_date`
- Cartão de crédito: `effective_date` é calculada automaticamente pelo ciclo de fechamento e vencimento
- Health Score neutro para metas: aportes em metas comuns não penalizam score nem analytics; a reserva padrão preserva o comportamento anterior
- Análise atualizada: bloco de reserva foi substituído por lista de metas ativas com progresso e estimativa mensal
- Navegação principal: nova aba `Metas`
- Banco de dados: schema atualizado para v4 com tabela `goals` e suporte a `goal_id`

## 1.3.0

- Análise financeira: nova tela com resumo, gráfico de evolução (6 meses), gastos por categoria, gastos por cartão, orçamento vs salário e reserva de emergência
- Splash screen: animação de entrada com logo e transição suave
- Perfil do usuário: nome editável e avatar via galeria no card de perfil das configurações
- Badges visuais: cards de transação exibem ícone/cor da categoria e nome/cor do cartão vinculado
- Saudação personalizada: header da home usa o nome do usuário + widget de avatar
- Desativação de recorrência: ao desativar, ocorrências futuras são removidas automaticamente
- Reatividade do analytics: dados recalculam instantaneamente ao salvar/editar transações
- Correção: seletor de data bloqueia entrada manual (apenas date picker)
- Correção: labels de status não transbordam em campos compactos
- Correção: lista de transações reflete edições imediatamente (detecção de data-changes)
- Correção: health score não quebra quando meta de emergência é zero

## 1.2.0

- Ícones e splash screen nativos personalizados
- Versão inicial de notificações locais com lembrete diário configurável
