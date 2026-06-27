# 🛡️ DevSecOps Pipeline — Varredura Automatizada de Segurança

Este projeto demonstra a implementação prática de uma esteira de **DevSecOps** utilizando **GitHub Actions**. O objetivo principal é automatizar a análise estática e de composição de segurança a cada alteração de código.

## 🚀 Tecnologias e Ferramentas
* **Python 3.10**: Linguagem base da aplicação.
* **GitHub Actions**: Automação do pipeline de CI/CD.
* **Bandit (SAST)**: Varredura do código-fonte para identificar falhas (como credenciais expostas).
* **Safety (SCA)**: Análise de dependências em busca de pacotes desatualizados ou vulneráveis.

## 🔄 Ciclo do Projeto Realizado
1. **Identificação**: O pipeline detectou uma senha estática no `app.py` e um pacote Django vulnerável no `requirements.txt`.
2. **Remediação**: O código foi corrigido utilizando variáveis de ambiente (`os.getenv`) e as dependências foram atualizadas para versões seguras.
3. **Validação**: A esteira rodou novamente sobre o código limpo, validando o sucesso da correção de segurança com sucesso absoluto.

Responsável:

Natan

Estudante de Engenharia de Software
Futuro Especialista e Engenheiro de Segurança Cibernética
