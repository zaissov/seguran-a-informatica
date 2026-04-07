# Plano Hardcore de Estudo em Cybersecurity – 6 Meses (Alfred Basta, Nadine Basta e Mary Brown)

Este repositório acompanha meu progresso no estudo intensivo de cibersegurança e testes de invasão, baseado na 2ª edição de **Segurança de Computadores e Teste de Invasão**.

## Objetivo

Preparar para trabalho remoto em cibersegurança e testes de invasão, com estudo teórico + prática diária, usando MacBook e laboratório virtual.

## Livro Base

**Segurança de Computadores e Teste de Invasão – Alfred Basta, Nadine Basta e Mary Brown (2ª edição norte-americana)**

* Publicação original: 2013
* Tradução em português: 2014/2015
* Nível: Avançado/Hard
* Uso: Referência principal, substituindo livros introdutórios.

## Ferramentas Necessárias

* Kali Linux VM, VirtualBox / VMware
* Wireshark, tcpdump, Nmap, Recon-ng, Maltego, Burp Suite, OWASP ZAP, Metasploit, John the Ripper, THC Hydra
* Sysinternals, ELK Stack, OpenSSL, GDB, Snapshots VM

## Estrutura do Repositório

* `/semanas` → Checklists semanais em Markdown baseados nos capítulos do livro
* `/projetos` → Projetos práticos por semana
* `/logs` → Capturas de telas, logs, relatórios
* `/cheatsheets` → Comandos principais e dicas rápidas

## Checklist Semanal por Capítulos do Livro

### Semana 1–2: Capítulo 1 – Ética e Raqueamento

* [ ] Estudar ética de raqueamento e impacto do raqueamento antiético
* [ ] Mapear comunidades e categorias de hackers
* [ ] Criar diagrama de perfis de hackers
* [ ] Simular cenários de raqueamento ético em laboratório
* [ ] Exercícios de revisão e projeto prático

### Semana 3–4: Capítulo 2 – Reconhecimento

* [ ] Reconhecimento legal, questionável e ilegal
* [ ] Engenharia social: técnicas, prevenção e simulação
* [ ] Rastreio de pegadas na internet e redes sociais
* [ ] Enumeração de rede e DNS
* [ ] Projeto prático em laboratório

### Semana 5–6: Capítulos 3–4 – Escaneamento e Farejadores

* [ ] Tipos de escaneamento TCP/UDP/IP/ping
* [ ] Uso de Wireshark, tcpdump, Snort, Cain & Abel, Kismet
* [ ] Testes de detecção de farejadores
* [ ] Proteção via SSL, PGP, SSH
* [ ] Projeto prático em Markdown

### Semana 7–8: Capítulo 5 – Vulnerabilidades TCP/IP

* [ ] IP spoofing, sequestro de conexão, ataques TCP SYN e ICMP
* [ ] Configuração de firewall e IPSec
* [ ] Projeto prático em laboratório

### Semana 9–10: Capítulo 6 – Criptografia e Senhas

* [ ] Criptografia simétrica e assimétrica
* [ ] Criptoanálise, hashes, ataques de dicionário e força bruta
* [ ] Teste de keyloggers e engenharia social em laboratório seguro
* [ ] Projeto prático em Markdown

### Semana 11–12: Capítulos 7–9 – Falsificação, Sequestro de Sessão e Raqueamento de Redes

* [ ] Falsificação de IP, ARP, DNS e Web
* [ ] Ferramentas: Mausezahn, Ettercap, Arpspoof, Hunt
* [ ] Teste de firewalls, VPNs e proteção de redes
* [ ] Projeto prático integrado

### Semana 13–14: Capítulos 10–12 – Cavalos de Troia, DoS e Buffer Overflow

* [ ] Simulação de cavalos de Troia em VM segura
* [ ] Ataques DoS e DDoS (simulados em laboratório isolado)
* [ ] Estouro de buffer em C/heap/stack
* [ ] Projeto prático detalhado e relatório

### Semana 15–16: Capítulos 13–14 – Explorações de Programação e E-mail

* [ ] Vulnerabilidades em C/C++, .NET, Java, JavaScript, HTML5
* [ ] Ataques e proteção em servidores de e-mail (SMTP, POP, IMAP)
* [ ] Proteção de navegadores e e-mails
* [ ] Projeto prático documentado

### Semana 17–18: Capítulos 15–17 – Aplicações Web, Windows e UNIX/Linux

* [ ] Teste de vulnerabilidades web (DVWA, OWASP Top 10)
* [ ] Teste de contas padrão, senhas, permissões e kernel em Windows/Linux
* [ ] Exploração segura e documentação de defesa
* [ ] Projeto prático integrado

### Semana 19–20: Capítulo 18 – Tratamento de Incidentes e Projeto Final

* [ ] Simular incidentes de segurança em laboratório
* [ ] Detecção, contenção, erradicação e recuperação
* [ ] Criar plano formal de resposta a incidentes
* [ ] Projeto final: pentest completo integrado com rede simulada (Windows + Linux + DVWA)
* [ ] Relatório final em Markdown e documentação completa

## Dicas GitHub

* Criar uma branch por semana ou módulo
* Marcar tarefas concluídas com `[x]`
* Commit diário com notas, resultados e screenshots
* Atualizar `/logs` com evidências práticas
* Manter README atualizado com progresso
* Criar cheatsheets para cada ferramenta em `/cheatsheets`
