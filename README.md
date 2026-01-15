# 🛡️ AuditFlow - Gestão de Melhorias de Auditoria

O **AuditFlow** é uma plataforma desenvolvida para transformar relatórios de auditoria em planos de ação executáveis. Ele permite o registro de achados, atribuição de responsáveis e o upload de evidências diretamente no banco de dados.

## 🛠️ Tecnologias Utilizadas

- **Frontend:** React.js (Vite) + Tailwind CSS
- **Backend:** Node.js + Express
- **Database & Auth:** Supabase (PostgreSQL)
- **Storage:** Supabase Bucket (para armazenamento de evidências)

## 🏗️ Arquitetura do Sistema



## 🚀 Funcionalidades Principais

- **Dashboard de Conformidade:** Visão geral do status das melhorias (Pendente, Em progresso, Concluído).
- **Gestão de Ações (CAPA):** Criação e edição de planos de ação baseados em auditorias.
- **Upload de Evidências:** Armazenamento seguro de PDFs/Imagens que comprovam a execução da melhoria.
- **Autenticação:** Controle de acesso por níveis (Administrador, Auditor, Responsável).
- **Alertas de Prazo:** Sistema que identifica ações próximas do vencimento.

## 🗄️ Modelo de Dados (Supabase)

O banco de dados utiliza as seguintes tabelas principais:
- `auditorias`: Registra o evento da auditoria (data, tipo, auditor).
- `melhorias`: Contém a descrição do problema, ação proposta e prazo.
- `usuarios`: Gerencia perfis e permissões.

## 🔧 Como Rodar o Projeto

1. Clone o repositório: `git clone https://github.com/seu-usuario/audit-flow.git`
2. Instale as dependências: `npm install`
3. Configure as variáveis de ambiente (`.env`) com suas chaves do Supabase.
4. Execute o servidor: `npm run dev`
