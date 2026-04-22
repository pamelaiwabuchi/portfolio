Pode criar até 9 instancias simultaneamente
Nomes e tags - nome da instancia (máquina virtual), pode ser nome do projeto, nome do time, etc. - 1DSM2026P
Par de chaves - recomendação empresarial: fazer 1 chave para cada instância. - 1DSM20261
No terminal: ir até a pasta Download após gerar novo par de chaves e rodar o comando:
cat .\1DSM20261.pem - sendo este o nome do seu arquivo e vai retornar o hash

Para criar grupo de segurança:
Permitir tráfego HTTPS da Internet
Permitir tráfego HTTP da Internet
Permitir tráfego SSH de

- Qualquer lugar: significa que qualquer IP pode acessar. Caso contrário, se há a necessidade de conexão em um lugar físico por ser algo sigiloso ou algo semelhante, o ideal é especificar o IP.

Cada instância pode ter até 30GB de SSD.
Recomendação: entre 20 e 30

Endereço IPv4 público: o IP pelo qual qualquer pessoa pode acessar meu site. 
Endereços IPv4 privados: IP local da AWS , na Virgínia

estado da instancia: 
Interromper instancia - parar. Ele sai do estado executando e fica no estado parado.
Encerrar - deletar instancia. 

em conectar:
cliente SSH - 

Na barra lateral, clicar em "New Terminal Console" e rodar o comando `htop` 
Ele roda via terminal, sem interface para economizar recursos. 

bitvise






