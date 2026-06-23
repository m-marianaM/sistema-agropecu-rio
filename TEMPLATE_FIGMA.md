# 🎨 Template Figma - Sistema Agropecuário

## 📐 Estrutura de Design System

### Paleta de Cores

```
PRIMARY COLORS:
- Verde Principal: #2D6A4F (Verde Escuro - Natureza/Agricultura)
- Verde Claro: #52B788 (Verde Médio - Crescimento)
- Verde Muito Claro: #D8F3DC (Verde Pastel - Fundo)

SECONDARY COLORS:
- Marrom Terra: #8B6F47 (Solo/Fazenda)
- Laranja Harvest: #FF9F1C (Colheita/Energia)
- Azul Céu: #4A90E2 (Confiança/Tecnologia)

NEUTRAL COLORS:
- Cinza Escuro: #2C3E50 (Texto)
- Cinza Médio: #95A5A6 (Secundário)
- Cinza Claro: #ECF0F1 (Fundo)
- Branco: #FFFFFF (Base)

SEMANTIC COLORS:
- Sucesso: #27AE60 (Verde)
- Alerta: #F39C12 (Amarelo)
- Erro: #E74C3C (Vermelho)
- Info: #3498DB (Azul)
```

### Tipografia

```
FAMILY: Inter + Roboto

HEADINGS:
- H1: 48px, Weight: 700, Color: #2C3E50
- H2: 36px, Weight: 700, Color: #2C3E50
- H3: 28px, Weight: 600, Color: #2C3E50
- H4: 20px, Weight: 600, Color: #2C3E50

BODY:
- Body Large: 16px, Weight: 400, Line-height: 1.6
- Body Medium: 14px, Weight: 400, Line-height: 1.5
- Body Small: 12px, Weight: 400, Line-height: 1.4

BUTTONS:
- Button Text: 14px, Weight: 600, Uppercase
```

### Componentes Base

#### 1. Button
```
Estados:
- Primary (Fundo: #2D6A4F, Texto: #FFF)
- Secondary (Fundo: #52B788, Texto: #FFF)
- Outline (Fundo: transparent, Border: #2D6A4F)
- Disabled (Fundo: #95A5A6, Cursor: not-allowed)

Tamanhos:
- Small: 32px height, 12px padding
- Medium: 40px height, 16px padding
- Large: 48px height, 20px padding

Radius: 8px
```

#### 2. Input Field
```
Altura: 40px
Padding: 12px 16px
Border: 1px solid #ECF0F1
Border Focus: 2px solid #2D6A4F
Background: #FFFFFF
Radius: 6px
Font: 14px

Variações:
- Text
- Email
- Number
- Date
- Select
- Textarea
```

#### 3. Card
```
Padding: 24px
Background: #FFFFFF
Border: 1px solid #ECF0F1
Shadow: 0px 2px 8px rgba(0,0,0,0.08)
Radius: 12px

Variações:
- Default
- Highlighted (Border: #52B788)
- Elevated (Shadow: 0px 4px 16px rgba(0,0,0,0.12))
```

#### 4. Badge
```
Padding: 4px 12px
Border-radius: 20px
Font: 12px, Weight: 600

Variações:
- Success: Background #D4EDDA, Color #155724
- Warning: Background #FFF3CD, Color #856404
- Error: Background #F8D7DA, Color #721C24
- Info: Background #D1ECF1, Color #0C5460
```

#### 5. Modal
```
Overlay: rgba(0,0,0,0.5)
Width: 90% (max 600px)
Padding: 32px
Header: H3, Weight 600
Close Button: Top-right, 24px icon
Footer: Right-aligned buttons
Radius: 12px
```

---

## 📱 Wireframes e Telas Principais

### Tela 1: Login / Autenticação
```
┌─────────────────────────────────┐
│                                 │
│     LOGO + "AGROPECUÁRIO"      │
│                                 │
│  ┌──────────────────────────┐  │
│  │  E-mail                  │  │
│  │  [________________]      │  │
│  │                          │  │
│  │  Senha                   │  │
│  │  [________________]      │  │
│  │                          │  │
│  │  [✓] Lembrar-me         │  │
│  │                          │  │
│  │      [ENTRAR]            │  │
│  │                          │  │
│  │   Não tem conta?         │  │
│  │   Solicitar acesso       │  │
│  └──────────────────────────┘  │
│                                 │
└─────────────────────────────────┘

Cores:
- Fundo: Gradiente #2D6A4F → #52B788
- Card: #FFFFFF
- Botão: #2D6A4F com hover #1F4D38
```

### Tela 2: Dashboard Principal
```
┌────────────────────────────────────────────┐
│ LOGO │  Bem-vindo, João Silva  │ MENU      │
├────────────────────────────────────────────┤
│ SIDEBAR                                    │
│ ├─ Dashboard                              │
│ ├─ Plantios                               │
│ ├─ Rebanho                                │
│ ├─ Recursos                               │
│ ├─ Financeiro                             │
│ ├─ Relatórios                             │
│ └─ Configurações                          │
│                                            │
│  CONTEÚDO PRINCIPAL                       │
│  ┌────────────┬────────────┬────────────┐ │
│  │ KPI 1      │ KPI 2      │ KPI 3      │ │
│  │ Plantios   │ Rebanho    │ Receita    │ │
│  │ 1250 há    │ 450 cabeças│ R$ 45.5k   │ │
│  └────────────┴────────────┴────────────┘ │
│                                            │
│  ┌──────────────────────────────────────┐ │
│  │ GRÁFICO: Produção (últimos 6 meses)  │ │
│  │                                      │ │
│  │   [Linha crescente]                  │ │
│  │                                      │ │
│  └──────────────────────────────────────┘ │
│                                            │
│  ┌──────────────┬──────────────────────┐  │
│  │ Alertas      │ Atividades Recentes  │  │
│  │ • Talhão 5   │ • Plantio T3         │  │
│  │   irrigação  │ • Aplicação Defensivo│  │
│  │ • Rebanho 2  │ • Inventário Máquinas│  │
│  │   vacinação  │                      │  │
│  └──────────────┴──────────────────────┘  │
└────────────────────────────────────────────┘

Grid: 12 colunas, Gutters: 16px
```

### Tela 3: Módulo Plantios
```
┌────────────────────────────────────────────┐
│ LOGO │  PLANTIOS  │ [+ NOVO PLANTIO]      │
├────────────────────────────────────────────┤
│                                            │
│  FILTROS: [Status ▼] [Talhão ▼] [Buscar] │
│                                            │
│  ┌──────────────────────────────────────┐ │
│  │ TALHÃO │ CULTURA │ ÁREA │ STATUS │ AÇ │
│  ├──────────────────────────────────────┤ │
│  │ T-001  │ Milho   │ 150  │ ✓ Ativo│ ••│ │
│  │ T-002  │ Soja    │ 200  │ ⏱ Plantio  │ │
│  │ T-003  │ Trigo   │ 120  │ ⚠ Alerta   │ │
│  │ T-004  │ Algodão │ 180  │ ✓ Ativo│ ••│ │
│  └──────────────────────────────────────┘ │
│                                            │
│  [← Anterior] Página 1 de 5 [Próximo →]   │
└────────────────────────────────────────────┘

MODAL ao clicar em "NOVO PLANTIO":
┌─────────────────────────────┐
│ NOVO PLANTIO            [✕] │
├─────────────────────────────┤
│                             │
│ Talhão*                     │
│ [____________ ▼]            │
│                             │
│ Cultura*                    │
│ [____________ ▼]            │
│                             │
│ Data de Plantio*            │
│ [____/____/____]            │
│                             │
│ Área (ha)*                  │
│ [________________]          │
│                             │
│ Observações                 │
│ [________________]          │
│ [________________]          │
│                             │
│       [CANCELAR]  [SALVAR]  │
└─────────────────────────────┘
```

### Tela 4: Detalhes do Plantio
```
┌────────────────────────────────────────────┐
│ LOGO │  PLANTIO: Talhão T-001  │           │
├────────────────────────────────────────────┤
│  [◄ Voltar]                                │
│                                            │
│  ABAS: [Detalhes] [Histórico] [Operações] │
│                                            │
│  ┌──────────────┐  ┌────────────────────┐ │
│  │ STATUS: ATIVO│  │ Cultura: Milho     │ │
│  └──────────────┘  │ Área: 150 ha       │ │
│                    │ Data Plantio: 10/05│ │
│  MAPA DO TALHÃO    │ Previsão Colheita: │ │
│  ┌──────────────┐  │ 15/11 (180 dias)   │ │
│  │              │  │                    │ │
│  │  [TALHÃO]    │  │ Fase: VEGETATIVA   │ │
│  │              │  │ Dias desde plantio:│ │
│  │              │  │ 45 dias (25%)      │ │
│  └──────────────┘  └────────────────────┘ │
│                                            │
│  ATIVIDADES REGISTRADAS                   │
│  • 05/05 - Plantio realizado (150 ha)    │
│  • 10/05 - Aplicação Herbicida           │
│  • 15/05 - Irrigação 1ª fase             │
│                                           │
│  PRÓXIMAS AÇÕES RECOMENDADAS             │
│  ⚠ Irrigação em 5 dias                    │
│  ⚠ Aplicação fungicida em 10 dias        │
│                                           │
│            [REGISTRAR OPERAÇÃO]           │
└────────────────────────────────���───────────┘
```

### Tela 5: Módulo Rebanho
```
┌────────────────────────────────────────────┐
│ LOGO │  REBANHO  │ [+ NOVO ANIMAL]         │
├────────────────────────────────────────────┤
│                                            │
│  FILTROS: [Tipo ▼] [Status ▼] [Buscar]   │
│                                            │
│  ┌──────────────────────────────────────┐ │
│  │ ID  │ TIPO  │ CATEGORIA │ STATUS │ AÇ│
│  ├──────────────────────────────────────┤ │
│  │ B-01│ Gado  │ Matriz    │ ✓ Saudável│ │
│  │ B-02│ Gado  │ Cria      │ ✓ Saudável│ │
│  │ B-03│ Suíno │ Maternidade│⚠ Em trat. │ │
│  │ B-04│ Gado  │ Reprodutor│ ✓ Saudável│ │
│  │ B-05│ Aves  │ Postura   │ ✓ Saudável│ │
│  └──────────────────────────────────────┘ │
│                                            │
│  [← Anterior] Página 1 de 8 [Próximo →]   │
└────────────────────────────────────────────┘
```

### Tela 6: Dashboard Financeiro
```
┌────────────────────────────────────────────┐
│ LOGO │  FINANCEIRO  │ [PERÍODO: JUN 2026]  │
├────────────────────────────────────────────┤
│                                            │
│  ┌──────────────┬──────────────┐          │
│  │ RECEITA      │ DESPESA      │          │
│  │ R$ 125.450   │ R$ 78.200    │          │
│  │ ▲ 15% vs mês │ ▼ 8% vs mês  │          │
│  └──────────────┴──────────────┘          │
│                                            │
│  ┌──────────────────────────────────────┐ │
│  │ FLUXO DE CAIXA (Últimos 6 meses)    │ │
│  │                                      │ │
│  │         /\        /\                 │ │
│  │    /\  /  \  /\  /  \    /\          │ │
│  │   /  \/    \/  \/    \  /            │ │
│  │                                      │ │
│  └──────────────────────────────────────┘ │
│                                            │
│  RECEITAS POR PRODUTO                     │
│  ┌──────────────────────────────────────┐ │
│  │ Milho         R$ 65.000  |████████░░│ │
│  │ Soja          R$ 35.000  |█████░░░░░│ │
│  │ Gado          R$ 18.000  |██░░░░░░░░│ │
│  │ Outros        R$ 7.450   |░░░░░░░░░░│ │
│  └──────────────────────────────────────┘ │
│                                            │
│  DESPESAS POR CATEGORIA                   │
│  ┌──────────────────────────────────────┐ │
│  │ Insumos       R$ 35.000  |████████░░│ │
│  │ Combustível   R$ 18.500  |████░░░░░░│ │
│  │ Manutenção    R$ 12.300  |███░░░░░░░│ │
│  │ Salários      R$ 9.200   |██░░░░░░░░│ │
│  │ Outros        R$ 3.200   |░░░░░░░░░░│ │
│  └──────────────────────────────────────┘ │
└────────────────────────────────────────────┘
```

### Tela 7: Relatórios e Exportação
```
┌────────────────────────────────────────────┐
│ LOGO │  RELATÓRIOS  │ [+ NOVO RELATÓRIO]   │
├────────────────────────────────────────────┤
│                                            │
│  RELATÓRIOS DISPONÍVEIS                    │
│                                            │
│  ┌────────────────────────────────────┐   │
│  │ 📊 Produtividade Plantios          │   │
│  │ Período: JAN - JUN 2026            │   │
│  │ Status: Pronto para download       │   │
│  │                 [VISUALIZAR] [⬇]  │   │
│  └────────────────────────────────────┘   │
│                                            │
│  ┌────────────────────────────────────┐   │
│  │ 📈 Performance Financeira          │   │
│  │ Período: JAN - JUN 2026            │   │
│  │ Status: Pronto para download       │   │
│  │                 [VISUALIZAR] [⬇]  │   │
│  └────────────────────────────────────┘   │
│                                            │
│  ┌────────────────────────────────────┐   │
│  │ 🐄 Saúde do Rebanho                │   │
│  │ Período: MAI - JUN 2026            │   │
│  │ Status: Pronto para download       │   │
│  │                 [VISUALIZAR] [⬇]  │   │
│  └────────────────────────────────────┘   │
│                                            │
└────────────────────────────────────────────┘
```

---

## 🎯 Componentes Específicos para Agricultores

### KPI Card
```
┌────────────────────┐
│ ÍCONE              │
│                    │
│ Plantios Ativos    │
│ 1.250 hectares     │
│                    │
│ ↑ 12% desde mês    │
│ passado            │
└────────────────────┘

Ícone: Folha/Planta (verde)
Altura: 160px
Cor destaque: #52B788
```

### Alert Component
```
┌─────────────────────────────────┐
│ ⚠ Ação Necessária               │
│                                 │
│ Talhão T-005: Baixa umidade     │
│ detectada. Irrigação necessária │
│ nas próximas 48 horas.          │
│                                 │
│  [AGENDAR OPERAÇÃO] [Descartar] │
└─────────────────────────────────┘

Tipo: Warning (fundo: #FFF3CD, borda: #F39C12)
```

### Timeline de Operações
```
● 05/06 - Plantio
  └─ 150 ha de Milho
     Operador: João Silva

● 10/06 - Aplicação Herbicida
  └─ T-001, T-002
     Operador: Maria Santos

● 15/06 - Irrigação 1ª Fase
  └─ 3 horas de aplicação
     Volume: 45.000 litros
```

---

## 📐 Grid e Responsividade

```
DESKTOP (1920px):
- Sidebar: 250px
- Conteúdo: 12 colunas de 120px
- Gutters: 16px

TABLET (768px):
- Sidebar: colapsível (60px)
- Conteúdo: 8 colunas
- Stack quando necessário

MOBILE (375px):
- Sidebar: drawer
- Conteúdo: full width
- Stack em 1 coluna
```

---

## 🎬 Animações e Transições

```
- Hover buttons: 200ms ease-out
- Modal appear: 300ms ease-out (fade + scale)
- Expandir card: 250ms ease-in-out
- Carregamento: Skeleton screens com shimmer
- Transição página: Fade 150ms
```

---

*Este template deve ser implementado no Figma com componentes reutilizáveis e variações.*
*Total de screens recomendadas: 25-30 (incluindo variações de estado)*