# Como Executar o Projeto Localmente

## Pré-requisitos
- Node.js instalado (versão 18 ou superior)
- npm ou yarn instalado

## Passos para Executar

1. **Exportar o projeto**
   - No Lovable, clique no botão de menu (três pontos) no canto superior direito
   - Selecione "Download Code" ou "Export Project"
   - Extraia o arquivo ZIP em uma pasta no seu computador

2. **Instalar dependências**
   ```bash
   cd caminho/para/o/projeto
   npm install
   ```

3. **Executar o projeto**
   ```bash
   npm run dev
   ```
   - O projeto será aberto em `http://localhost:5173`

## Sobre o Armazenamento de Dados

### Como os dados são salvos
- Este projeto usa `localStorage` do navegador para armazenar todos os dados
- Os dados ficam salvos no navegador que você está usando
- **IMPORTANTE**: Os dados NÃO são salvos no servidor ou na nuvem

### O que acontece quando você desliga o computador?
- ✅ **Seus dados PERMANECERÃO salvos** quando você desligar o computador
- ✅ Os dados ficam armazenados localmente no seu navegador
- ✅ Quando você ligar novamente e abrir o sistema, todos os dados estarão lá
- ✅ O histórico de cadastros permanece intacto

### Quando os dados podem ser perdidos?
- ❌ Se você limpar o cache/histórico do navegador
- ❌ Se você usar outro navegador (os dados estão vinculados ao navegador)
- ❌ Se você usar outro computador
- ❌ Se você desinstalar o navegador

### Como fazer backup dos dados?
Para não perder seus dados, você pode:
1. Não limpar o cache do navegador
2. Sempre usar o mesmo navegador
3. Fazer backup manual exportando para Excel (funcionalidade já disponível no sistema)

## Sobre Funções Automáticas

### O computador precisa ficar ligado?
- ❌ **NÃO**, você pode desligar normalmente o computador
- ✅ Os dados ficam salvos mesmo com o PC desligado
- ✅ Quando você ligar novamente, tudo estará como você deixou
- ❌ Mas não haverá processos automáticos rodando quando o PC estiver desligado

### Limitações do sistema local:
- Não envia notificações automáticas
- Não faz backups automáticos
- Não sincroniza entre dispositivos
- Não roda tarefas agendadas quando o PC está desligado

### Para ter funcionalidades automáticas 24/7:
Você precisaria migrar para Lovable Cloud (backend na nuvem):
- ✅ Dados salvos permanentemente na nuvem
- ✅ Acesso de qualquer dispositivo
- ✅ Backups automáticos
- ✅ Possibilidade de notificações automáticas por email/WhatsApp
- ✅ Sistema funciona 24/7 mesmo com seu PC desligado

## Sistema de Numeração de Jogos

- Cada jogo cadastrado recebe um número automático (0001, 0002, etc.)
- O sistema gerencia automaticamente qual jogo está sendo alugado
- Você pode duplicar jogos rapidamente usando o botão de duplicar
- Ideal para cadastrar múltiplos jogos iguais de forma rápida

## Dúvidas Comuns

**Q: Posso desligar o PC sem perder dados?**
A: SIM! Os dados ficam salvos no navegador mesmo com o PC desligado.

**Q: Preciso manter o sistema aberto?**
A: Não, pode fechar a aba/navegador normalmente. Os dados permanecem.

**Q: Posso acessar de outro computador?**
A: Não com localStorage. Para isso, você precisa do Lovable Cloud.

**Q: Posso usar no celular?**
A: Sim, mas os dados do celular serão separados dos dados do computador.

**Q: Como faço para ter os dados sincronizados?**
A: Você precisa migrar para Lovable Cloud, que oferece banco de dados na nuvem.

**Q: E se eu quiser enviar notificações automáticas?**
A: Isso requer Lovable Cloud, que permite criar funções automáticas que rodam 24/7.
