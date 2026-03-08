<div align="center">

# 🏥 iTuto — Sistema ERP para Instituições Sociais

Sistema de gestão completo desenvolvido para **Associações e Institutos Sociais**

![Next.js](https://img.shields.io/badge/Next.js-16-black?style=for-the-badge&logo=next.js)
![React](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5.7-3178C6?style=for-the-badge&logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?style=for-the-badge&logo=tailwindcss)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-6-2D3748?style=for-the-badge&logo=prisma)
![PWA](https://img.shields.io/badge/PWA-Instalável-5A0FC8?style=for-the-badge&logo=pwa)

</div>

---

## 📋 Sobre o Projeto

O **iTuto** é um sistema de gestão (ERP) completo, criado para atender as necessidades de **institutos sociais e associações de assistência social**. O sistema foi projetado para ser a solução única de toda a operação de uma instituição — do cadastro de assistidos e voluntários até o atendimento clínico com prontuário eletrônico e painel de chamada hospitalar por voz.

> ⚠️ **Transparência:** Este projeto foi desenvolvido por [**@millersantosbr**](https://github.com/millersantosbr) com o auxílio de **Inteligência Artificial (IA)**. A IA foi utilizada como ferramenta de apoio ao longo de todo o desenvolvimento — incluindo geração de código, resolução de bugs, elaboração de documentação e tomada de decisões técnicas. A concepção, o planejamento, as regras de negócio e as decisões finais são de autoria do desenvolvedor.

---

## 🎯 Finalidade

O iTuto foi idealizado para **organizações sociais, ONGs e institutos de assistência social** que precisam de um sistema robusto e profissional para gerenciar suas operações do dia a dia, sem depender de múltiplas ferramentas desconectadas.

**Problemas que o iTuto resolve:**

- 📁 Controle manual e descentralizado de cadastros
- 🏥 Falta de sistema clínico integrado com prontuário eletrônico
- 📊 Ausência de gestão financeira e do estoque (almoxarifado)
- 📢 Chamada de pacientes feita manualmente por voz
- 🔐 Dificuldade no controle de acesso e permissões por perfil de usuário

---

## ✨ Funcionalidades Principais

### 📌 Gestão Institucional
- **Cadastro de Assistidos** — CRUD completo com dados pessoais, histórico e status
- **Cadastro de Voluntários** — Área de atuação, disponibilidade e dados de contato
- **Dashboard Executivo** — Visão geral com gráficos, indicadores e alertas

### 💰 Gestão Financeira
- Registro de receitas e despesas com categorização
- Controle de teto orçamentário por categoria
- Gestão de parcelas e vencimentos
- Indicador de consumo de caixa

### 📦 Almoxarifado
- Controle de estoque com entrada/saída de produtos
- Gestão por lotes com controle de validade (PEPS — Primeiro que Entra, Primeiro que Sai)
- Alerta automático de estoque mínimo
- Bloqueio de itens vencidos

### 🏥 Módulo Clínico Completo
- **Recepção** — Criação de fichas com triagem por classificação de risco (Emergência, Urgente, Pouco Urgente, Não Urgente) e prioridade legal (Idoso, Gestante, PCD, Lactante)
- **Consultório do Médico** — Visualização de pacientes aguardando, chamada de pacientes e abertura de prontuário
- **Prontuário Eletrônico** — Campos completos segundo padrão médico (queixa, sinais vitais, hipótese diagnóstica, conduta, prescrição...)
- **Documentos Médicos** — Impressão de Receita, Encaminhamento, Solicitação de Exames e Atestado Médico (design clássico para impressão A4)
- **Painel de Chamadas (TV)** — Tela pública fullscreen com chamada por voz via TTS (Text-to-Speech), som de notificação "Ding-Dong" 🔔 e fila de espera

### 🔐 Controle de Acesso (RBAC)
- 4 perfis de usuário: **Admin**, **Coordenador**, **Voluntário**, **Médico**
- Sidebar dinâmica que exibe apenas os módulos permitidos para cada perfil
- Proteção de rotas via middleware

### ⚙️ Administração
- Painel administrativo com geração de logs do sistema
- Tela de auditoria com registro de todas as ações dos usuários
- Configurações do sistema (dados da instituição, consultórios, permissões, voz TTS, backup)
- Upload de logomarca institucional

---

## 📸 Galeria de Telas

<details>
<summary><b>🔐 Login</b></summary>
<br>
<img src="https://raw.githubusercontent.com/millersantosbr/iTuto/main/Galeria%20iTuto/Login.png" alt="Tela de Login" width="100%">
</details>

<details>
<summary><b>📊 Painel do Diretor (Dashboard)</b></summary>
<br>
<img src="https://raw.githubusercontent.com/millersantosbr/iTuto/main/Galeria%20iTuto/Paineldodiretor.png" alt="Painel do Diretor" width="100%">
</details>

<details>
<summary><b>👥 Cadastro de Assistidos</b></summary>
<br>
<img src="https://raw.githubusercontent.com/millersantosbr/iTuto/main/Galeria%20iTuto/CadastrodeAssistidos.png" alt="Cadastro de Assistidos" width="100%">
</details>

<details>
<summary><b>🤝 Cadastro de Voluntários</b></summary>
<br>
<img src="https://raw.githubusercontent.com/millersantosbr/iTuto/main/Galeria%20iTuto/CadastrodeVoluntarios.png" alt="Cadastro de Voluntários" width="100%">
</details>

<details>
<summary><b>🏥 Recepção Clínica</b></summary>
<br>
<img src="https://raw.githubusercontent.com/millersantosbr/iTuto/main/Galeria%20iTuto/TeladeRecep%C3%A7%C3%A3o.png" alt="Tela de Recepção" width="100%">
</details>

<details>
<summary><b>📋 Nova Ficha (Recepção)</b></summary>
<br>
<img src="https://raw.githubusercontent.com/millersantosbr/iTuto/main/Galeria%20iTuto/AbrirNovaFichaRecep%C3%A7%C3%A3o.png" alt="Abrir Nova Ficha na Recepção" width="100%">
</details>

<details>
<summary><b>🩺 Tela do Consultório</b></summary>
<br>
<img src="https://raw.githubusercontent.com/millersantosbr/iTuto/main/Galeria%20iTuto/Teladeconsult%C3%B3rio.png" alt="Tela do Consultório" width="100%">
</details>

<details>
<summary><b>👨‍⚕️ Consultório — Visão do Médico</b></summary>
<br>
<img src="https://raw.githubusercontent.com/millersantosbr/iTuto/main/Galeria%20iTuto/TeladoConsultorioVis%C3%A3odoM%C3%A9dico.png" alt="Tela do Consultório - Visão do Médico" width="100%">
</details>

<details>
<summary><b>📝 Prontuário Eletrônico</b></summary>
<br>
<img src="https://raw.githubusercontent.com/millersantosbr/iTuto/main/Galeria%20iTuto/Prontuario.png" alt="Prontuário Eletrônico" width="100%">
</details>

<details>
<summary><b>💊 Receita Médica</b></summary>
<br>
<img src="https://raw.githubusercontent.com/millersantosbr/iTuto/main/Galeria%20iTuto/receita.png" alt="Receita Médica" width="100%">
</details>

<details>
<summary><b>📄 Encaminhamento</b></summary>
<br>
<img src="https://raw.githubusercontent.com/millersantosbr/iTuto/main/Galeria%20iTuto/Encaminhamento.png" alt="Encaminhamento" width="100%">
</details>

<details>
<summary><b>🔬 Solicitação de Exames</b></summary>
<br>
<img src="https://raw.githubusercontent.com/millersantosbr/iTuto/main/Galeria%20iTuto/Exames.png" alt="Solicitação de Exames" width="100%">
</details>

<details>
<summary><b>📃 Atestado Médico</b></summary>
<br>
<img src="https://raw.githubusercontent.com/millersantosbr/iTuto/main/Galeria%20iTuto/Atestado.png" alt="Atestado Médico" width="100%">
</details>

<details>
<summary><b>📺 Painel de Chamadas (TV)</b></summary>
<br>
<img src="https://raw.githubusercontent.com/millersantosbr/iTuto/main/Galeria%20iTuto/PaineldeChamadas.png" alt="Painel de Chamadas" width="100%">
<br><br>
<img src="https://raw.githubusercontent.com/millersantosbr/iTuto/main/Galeria%20iTuto/paineldechamadasultimoschamados.png" alt="Painel de Chamadas - Últimos Chamados" width="100%">
</details>

<details>
<summary><b>🏢 Status dos Consultórios</b></summary>
<br>
<img src="https://raw.githubusercontent.com/millersantosbr/iTuto/main/Galeria%20iTuto/StatusConsult%C3%B3rio.png" alt="Status do Consultório" width="100%">
</details>

<details>
<summary><b>💰 Gestão Financeira</b></summary>
<br>
<img src="https://raw.githubusercontent.com/millersantosbr/iTuto/main/Galeria%20iTuto/Gest%C3%A3oFinanceira.png" alt="Gestão Financeira" width="100%">
</details>

<details>
<summary><b>📦 Gestão de Almoxarifado</b></summary>
<br>
<img src="https://raw.githubusercontent.com/millersantosbr/iTuto/main/Galeria%20iTuto/Gest%C3%A3odeAlmoxarifado.png" alt="Gestão de Almoxarifado" width="100%">
</details>

<details>
<summary><b>📋 Cadastro de Consultórios</b></summary>
<br>
<img src="https://raw.githubusercontent.com/millersantosbr/iTuto/main/Galeria%20iTuto/CadastrodeConsultorios.png" alt="Cadastro de Consultórios" width="100%">
</details>

<details>
<summary><b>🔍 Tela de Auditoria</b></summary>
<br>
<img src="https://raw.githubusercontent.com/millersantosbr/iTuto/main/Galeria%20iTuto/TeladeAuditoria.png" alt="Tela de Auditoria" width="100%">
</details>

<details>
<summary><b>⚙️ Tela de Configurações</b></summary>
<br>
<img src="https://raw.githubusercontent.com/millersantosbr/iTuto/main/Galeria%20iTuto/TeladeConfigura%C3%A7%C3%B5es.png" alt="Tela de Configurações" width="100%">
</details>

<details>
<summary><b>🔐 Permissões por Tipo de Usuário</b></summary>
<br>
<img src="https://raw.githubusercontent.com/millersantosbr/iTuto/main/Galeria%20iTuto/Permiss%C3%B5es_por_tipo_de_usu%C3%A1rio.png" alt="Permissões por Tipo de Usuário" width="100%">
</details>

---

## 🛠️ Stack Técnica

| Camada | Tecnologias |
|:---|:---|
| **Frontend** | Next.js 16 (App Router) · React 19 · TypeScript 5.7 · Tailwind CSS 4 |
| **Componentes UI** | shadcn/ui (Radix UI) · Lucide React · Recharts · Embla Carousel |
| **Formulários** | React Hook Form · Zod (validação) |
| **Backend** | Node.js (Server Actions + API Routes) · NextAuth.js v5 (Auth.js) |
| **Banco de Dados** | Microsoft SQL Server · Prisma ORM 6 |
| **Autenticação** | Credentials Provider + bcrypt (hash de senhas) + JWT |
| **TTS (Voz)** | Google Translate TTS (proxy via API Route) · Web Audio API |
| **Tempo Real** | SSE (dev) + Polling automático (produção) |
| **PWA** | manifest.json + Service Worker (instalável em mobile e desktop) |
| **Infraestrutura** | PM2 (VPS Linux) · Turbopack (bundler) |
| **Design** | Dark/Light mode · Google Sans Flex · Tema esmeralda (#059669) |

---

## 📐 Arquitetura e Destaques Técnicos

### 🔊 Sistema de Chamada por Voz (TTS)
O painel de atendimento em TV anuncia os pacientes **por voz** em português brasileiro:

> *"Senha 068, paciente Miller, por favor se dirija ao Consultório 01"*

- Som de notificação "Ding-Dong" hospitalar (Web Audio API)
- Anúncio de voz via Google TTS (proxy server-side)
- Repetição automática do anúncio
- Overlay de ativação (política de autoplay dos navegadores)

### ⚡ Atualização em Tempo Real (Dual Strategy)
- **Desenvolvimento:** Server-Sent Events (SSE) para atualização instantânea
- **Produção (VPS):** Polling automático a cada 5 segundos direto do banco
- Múltiplos dispositivos acessando simultaneamente (recepção, consultório, TV, tablet)

### 🧾 Documentos Médicos para Impressão
Receitas, encaminhamentos, atestados e solicitações de exames com:
- Design clássico formal tipo receituário com tipografia **Lora**
- Cabeçalho institucional dinâmico com logo
- Layout otimizado para impressão A4

### 🛡️ Sistema de Permissões (RBAC)

| Perfil | Cadastros | Almoxarifado | Financeiro | Auditoria | Config | Clínica |
|:---|:---:|:---:|:---:|:---:|:---:|:---:|
| Admin | CRUD | CRUD | CRUD | Ver | CRUD | CRUD |
| Coordenador | CRU | CRU | Ver | Ver | — | CR |
| Voluntário | Ver | CR | — | — | — | — |
| Médico | Ver | — | — | — | — | VE |

---

## 🗂️ Estrutura de Pastas

```
iTuto/
├── app/                        # Páginas e rotas (App Router)
│   ├── login/                  # Tela de login
│   ├── home/                   # Dashboard principal
│   ├── assistidos/             # Módulo de Assistidos
│   ├── voluntarios/            # Módulo de Voluntários
│   ├── almoxarifado/           # Gestão de Estoque
│   ├── financeiro/             # Gestão Financeira
│   ├── auditoria/              # Logs de auditoria
│   ├── configuracoes/          # Configurações do sistema
│   ├── admin/                  # Painel de administração
│   ├── clinica/                # MÓDULO CLÍNICO
│   │   ├── recepcao/           #   Recepção e triagem
│   │   ├── medico/             #   Consultório do médico
│   │   ├── painel/             #   Painel de chamada (TV)
│   │   ├── prontuario/         #   Prontuário eletrônico
│   │   ├── receita/            #   Impressão de receita
│   │   ├── encaminhamento/     #   Impressão de encaminhamento
│   │   ├── exames/             #   Solicitação de exames
│   │   └── atestado/           #   Atestado médico
│   └── api/                    # API Routes
├── components/                 # Componentes reutilizáveis (57 shadcn/ui)
├── lib/                        # Lógica de negócio e Server Actions
├── prisma/                     # Schema do banco de dados
├── public/                     # Assets estáticos e PWA
└── manutencao/                 # Scripts shell para VPS Linux
```

---

## 🗄️ Banco de Dados

O sistema utiliza **Microsoft SQL Server** com **Prisma ORM**, contendo **19 modelos** que cobrem todos os módulos:

`User` · `Assistido` · `Voluntario` · `Produto` · `Lote` · `Movimentacao` · `Transacao` · `OrcamentoCategoria` · `Ficha` · `Consultorio` · `Prontuario` · `Receita` · `MedicamentoReceita` · `Encaminhamento` · `SolicitacaoExame` · `Atestado` · `Configuracao` · `LogAuditoria`

---

## 🤖 Sobre o Uso de IA no Desenvolvimento

Este projeto foi desenvolvido com o apoio de **Inteligência Artificial**. A IA foi utilizada como ferramenta de auxílio em:

- ✅ **Geração e revisão de código** — componentes React, Server Actions, lógica de negócio
- ✅ **Resolução de bugs e debugging** — análise de erros, correções e otimizações
- ✅ **Arquitetura e decisões técnicas** — escolha de stack, modelagem de banco de dados, padrões de projeto
- ✅ **Documentação** — documentação técnica, guias de setup, changelogs
- ✅ **Design de interface** — layouts, acessibilidade e responsividade

A **idealização do projeto**, as **regras de negócio** e as **decisões finais** são de autoria de **Miller Santos** ([@millersantosbr](https://github.com/millersantosbr)).

---

## 📄 Licença

Este projeto é de uso privado, desenvolvido especificamente para **Associações e Institutos Sociais**.

---

<div align="center">

**Desenvolvido por [Miller Santos](https://github.com/millersantosbr)**

*Com o auxílio de Inteligência Artificial*

</div>

