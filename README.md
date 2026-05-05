🔐 Ransomware em Python – Criptografia e Recuperação de Arquivos

📌 Visão Geral

Este projeto consiste na implementação de um ransomware educacional utilizando Python, com o objetivo de demonstrar, de forma prática, como ocorre o processo de criptografia e recuperação de arquivos em cenários de segurança ofensiva.

A solução foi desenvolvida e testada em ambiente controlado utilizando Kali Linux, com foco em aprendizado, análise de comportamento e aplicação de conceitos de cibersegurança.

🎯 Objetivos do Projeto
Aplicar conceitos de criptografia em um cenário prático
Simular o comportamento de ransomware em ambiente seguro
Demonstrar o ciclo completo: criptografia e descriptografia
Documentar evidências técnicas de forma estruturada
Utilizar o GitHub como portfólio técnico
🧪 Ambiente de Execução
Sistema operacional: Kali Linux
Linguagem: Python 3
Execução local
Arquivos de teste criados para simulação

🔐 Funcionamento do Ransomware

📍 Conceito
O ransomware é um tipo de malware que criptografa arquivos da vítima, impedindo o acesso até que uma ação seja realizada.
Neste projeto, esse comportamento foi simulado exclusivamente para fins educacionais.

⚙️ Fluxo de Execução
Criação de arquivos de teste no ambiente Kali Linux
Execução do script de criptografia (randsoware.py)
Conversão dos arquivos originais para versões criptografadas
Indisponibilidade do conteúdo original
Execução do script de descriptografia (descriptografia.py)
Recuperação dos arquivos ao estado original

📂 Evidências de Execução
Os testes foram realizados diretamente no ambiente Kali Linux, e as evidências (prints) demonstram:

Execução do processo de criptografia
Alteração dos arquivos após o ataque
Processo de descriptografia
Recuperação do arquivo original

Arquivo utilizado nos testes:

teste.test.txt
<img width="1366" height="653" alt="criacao de aruivo legivel txt correto" src="https://github.com/user-attachments/assets/b39cd09e-85bc-48a7-9bb7-c1228bfd217c" />
<img width="1366" height="653" alt="criacao de teste kali linux" src="https://github.com/user-attachments/assets/28043fa7-dd02-4d97-b159-4ffdfa78c1c0" />
<img width="1366" height="653" alt="arquivos descriptografados e criacao de chave que sera usada para resgate no novo arquivo desconpilado" src="https://github.com/user-attachments/assets/c50f5316-ece7-498e-a1eb-db52f5ca86c7" />
<img width="1366" height="653" alt="imagens randsoware" src="https://github.com/user-attachments/assets/836f57ed-3cad-408a-b4c7-96f270c9d691" />

🧩 Componentes

🔒 randsoware.py

Responsável por:
Identificar arquivos de teste
Aplicar o processo de criptografia
Substituir os arquivos originais

🔓 descriptografia.py

Responsável por:
Ler arquivos criptografados
Executar a descriptografia
Restaurar os dados ao formato original

📊 Resultados Obtidos
Criptografia bem-sucedida dos arquivos de teste
Indisponibilidade temporária dos dados
Recuperação completa após execução do script de descriptografia
Validação prática do ciclo de ataque e resposta

🛡️ Medidas de Mitigação
Backups periódicos
Uso de antivírus e EDR
Restrição de execução de scripts desconhecidos
Monitoramento de alterações em arquivos
Controle de permissões

📚 Competências Demonstradas
Programação em Python
Aplicação prática de criptografia
Simulação de ataque ransomware
Execução em ambiente Linux (Kali)
Documentação técnica estruturada

⚠️ Considerações Éticas
Este projeto foi desenvolvido exclusivamente para fins educacionais, em ambiente controlado e sem impacto em sistemas reais.

🚀 Possíveis Evoluções
Uso de algoritmos de criptografia mais robustos
Gerenciamento seguro de chaves
Simulação de mensagem de resgate
Monitoramento em tempo real

📎 Conclusão
O projeto demonstra, de forma prática, o funcionamento de um ransomware, desde a criptografia até a recuperação dos dados, reforçando a importância de estratégias de proteção e resposta a incidentes.
