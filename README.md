# CREDVALUE
COMO MELHORAR O BACKOFFICE
História 3 – Otimização do Backoffice

User Story:

As a analista de backoffice da CredValue
I need visualizar e gerenciar solicitações de clientes em uma única interface centralizada
So that eu possa reduzir o tempo de atendimento e aumentar a eficiência operacional

✅ Critérios de Aceitação (Gherkin)
Dado que sou um analista logado no sistema  
Quando acesso o painel de backoffice  
Então devo visualizar todas as solicitações em aberto organizadas por status  

Dado que estou analisando uma solicitação  
Quando atualizo o status (em análise, aprovado, reprovado)  
Então o sistema deve salvar automaticamente e refletir a mudança em tempo real  

Dado que existem múltiplas solicitações  
Quando utilizo filtros (data, status, cliente)  
Então devo conseguir localizar rapidamente a solicitação desejada  

Dado que uma solicitação é finalizada  
Quando marco como concluída  
Então ela deve sair da fila de pendentes e ir para o histórico  
