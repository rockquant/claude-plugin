# RockQuant para Claude Code

Plugin oficial da [RockQuant](https://rockquant.io) para o Claude Code. Conecta o servidor MCP `https://mcp.rockquant.io/mcp` e traz uma skill de uso:

- **RockBuilder**: estratégias, backtests, otimização, walk-forward e Monte Carlo.
- **RockBots**: leitura da mesa de agents (contas, agents, missões, eventos, risco, resultado). Somente leitura.
- **RockSense**: painel de leitura emocional por período.
- **Central de ajuda**: busca e leitura de artigos.

Nada aqui é recomendação de investimento.

## Instalar

```
/plugin marketplace add rockquant/claude-plugin
/plugin install rockquant@rockquant
```

Depois, rode `/mcp`, escolha `rockquant` e **Authenticate** para entrar com a sua conta RockQuant.

Cada produto exige o plano Pro correspondente. Mais detalhes em [rockquant.io/mcp](https://rockquant.io/mcp).

## Sem o plugin

```
claude mcp add --transport http rockquant https://mcp.rockquant.io/mcp
```

## Revogar o acesso

No [Portal RockQuant](https://portal.rockquant.io/seguranca), em **Segurança** › **Apps conectados**.

## Privacidade

[rockquant.io/privacidade](https://rockquant.io/privacidade) · [Termos](https://rockquant.io/termos)
