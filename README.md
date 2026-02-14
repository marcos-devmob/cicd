#  Flutter CI/CD Pipeline Demo

Projeto criado com foco em estudo prático de CI/CD para aplicações Flutter utilizando Bitrise e Firebase App Distribution.

O objetivo principal deste repositório é demonstrar a configuração completa de uma pipeline mobile profissional, incluindo resolução de problemas reais de integração.

---

##  Sobre o Projeto

Aplicação base do Flutter utilizada como ambiente de testes para implementar:

- Integração contínua (CI)
- Entrega contínua (CD)
- Build automatizada
- Distribuição automática de APK
- Configuração de webhooks
- Troubleshooting de integração OAuth

O foco do projeto não é a complexidade da aplicação, mas sim a automação do fluxo de entrega.

---

##  Tecnologias Utilizadas

- Flutter
- Dart
- Bitrise (CI/CD)
- Firebase App Distribution
- GitHub
- Git

---

## Fluxo da Pipeline

1. Push na branch `main`
2. Webhook dispara automaticamente o Bitrise
3. Build do projeto Flutter
4. Geração do APK
5. Upload automático para Firebase App Distribution
6. Disponibilização para testers

---

##  Integrações Configuradas

- Conexão via OAuth com GitHub
- Webhooks configurados manualmente
- Trigger configurado para Push na branch `main`
- Workflow automatizado no Bitrise

---

##  Problemas Resolvidos Durante a Implementação

Durante a configuração da pipeline, foram identificados e solucionados:

- Perda de acesso da GitHub App após renomear o repositório
- Atualização do remote local do Git
- Reconfiguração de OAuth
- Falha de disparo automático devido à ausência de webhook
- Validação manual de triggers e workflows

Esses ajustes reforçam o entendimento prático de integração entre GitHub e Bitrise.

---

##  Objetivo

Demonstrar conhecimento em:

- Automação de builds Flutter
- Configuração de pipelines mobile
- Integração com Firebase
- Distribuição de builds fora da Play Store
- Debug e troubleshooting de CI/CD
- Boas práticas de versionamento

---

##  Próximos Passos

- Implementação de versionamento automático
- Separação por flavors (dev/prod)
- Assinatura automática de builds
- Deploy automatizado por ambiente

---

##  Autor

Marcos Aurélio  
Desenvolvedor Flutter em transição de carreira  
GitHub: https://github.com/marcos-devmob
