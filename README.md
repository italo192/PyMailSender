Envio de E-mails usando Python
Este script Python permite enviar e-mails utilizando a biblioteca smtplib para configurar a conexão com um servidor SMTP e a biblioteca email para compor e enviar mensagens com conteúdo HTML.

Configuração
Antes de usar o script, é necessário configurar algumas variáveis no código:

Credenciais do E-mail
my_email: O endereço de e-mail do remetente.
my_password: A senha do e-mail remetente. Nota: É recomendável utilizar autenticação de dois fatores e gerar uma senha de aplicativo para a conta de e-mail.
E-mails de Destinatários
recipient_emails: Uma lista contendo os endereços de e-mail dos destinatários.
Configurações do Servidor SMTP
smtp_server: O endereço do servidor SMTP do provedor de e-mail.
smtp_port: A porta para se conectar ao servidor SMTP. Certifique-se de utilizar a porta correta, consultando a documentação do seu provedor de e-mail.
Conteúdo HTML do E-mail
html_content: O conteúdo HTML da mensagem que será enviado por e-mail.
Utilização
Clone o repositório ou baixe o script.
Abra o script em um editor de texto ou IDE Python.
Configure as variáveis mencionadas acima conforme necessário.
Execute o script.
Nota: É importante respeitar as políticas de segurança do provedor de e-mail, como permitir o acesso de aplicativos menos seguros para a conta de e-mail remetente.

Dependências
Certifique-se de ter as seguintes bibliotecas Python instaladas:

bash
Copy code
pip install secure-smtplib
pip install email
Erros Comuns
Caso ocorra algum erro durante o envio do e-mail, verifique a console para mensagens de erro detalhadas. Certifique-se de que todas as informações de autenticação e configuração do servidor SMTP estão corretas.

Aviso: O envio de e-mails em massa pode estar sujeito a limitações impostas pelo provedor de e-mail. Certifique-se de estar em conformidade com as políticas do seu provedor para evitar bloqueios ou restrições.
