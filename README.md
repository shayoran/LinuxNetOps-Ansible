# LinuxNetOps - Ansible Infrastructure Automation

Projeto de automação e auditoria de infraestrutura desenvolvido com Ansible, focado na gestão centralizada e validação de sistemas Linux.

## 📂 Estrutura do Projeto
- `inventory.ini`: Ficheiro de inventário com a definição dos alvos de execução.
- `playbook.yml`: Playbook principal estruturado em fases de aprovisionamento, instalação de ferramentas de diagnóstico e auditoria de portas em escuta.

## 🚀 Funcionalidades
1. **Bootstrap & Setup:** Atualização automática de pacotes do sistema base.
2. **Ferramentas de Rede:** Instalação de utilitários essenciais (`curl`, `net-tools`, `dnsutils`).
3. **Auditoria de Segurança:** Registo automático das portas ativas num ficheiro de relatório local.
