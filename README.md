🛠️ Script de Manutenção e Otimização do Windows

Script Batch (.BAT) para manutenção preventiva do Windows, com foco em limpeza, diagnóstico e recuperação do sistema, preservando os dados dos principais navegadores (Microsoft Edge, Google Chrome e Mozilla Firefox).

Funcionalidades
Limpeza segura de arquivos temporários do usuário.
Proteção dos perfis dos navegadores para evitar perda de favoritos, senhas e configurações.
Execução do Disk Cleanup (cleanmgr).
Limpeza do cache DNS (ipconfig /flushdns).
Reset da pilha Winsock para correção de problemas de rede.
Verificação e reparo de arquivos do sistema com SFC /scannow.
Recuperação da imagem do Windows utilizando DISM /RestoreHealth.
Otimização de SSD por meio do comando TRIM.
Geração de relatório com os 10 processos que mais consomem memória.
Verificação do espaço livre em disco.
Criação automática de logs detalhados para auditoria e acompanhamento das atividades executadas.
Requisitos
Windows 10 ou superior.
Execução como Administrador para acesso completo às rotinas de manutenção.
Observações
O script não remove senhas, favoritos, cookies ou configurações dos navegadores.
Não altera o Gerenciador de Credenciais do Windows.
Após o reset do Winsock, recomenda-se reiniciar o computador para aplicar as alterações.
Tecnologias Utilizadas
Batch Script (.BAT)
PowerShell
Ferramentas nativas do Windows (SFC, DISM, CleanMgr, Netsh, WMIC e Optimize-Volume)
