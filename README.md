Simulando um ataque de Brute Force com Medusa
# Configuração do Ambiente

## Máquina Virtual Kali Linux

### Especificações

- 2 GB RAM
- 2 vCPUs
- Rede Host-Only

### Ferramentas Instaladas

- Nmap
- Medusa
- Burp Suite
- Wireshark

## Máquina Virtual Metasploitable 2

### Especificações

- 1 GB RAM
- Rede Host-Only

### Serviços Disponíveis

- FTP
- SMB
- Apache
- MySQL
- DVWA

## Configuração da Rede

As duas máquinas foram conectadas utilizando uma rede Host-Only do VirtualBox.

### Validação

No Kali:

```bash
ip a
```

No Metasploitable:

```bash
ifconfig
```

Teste de conectividade:

```bash
ping <IP-DO-METASPLOITABLE>
```

Resultado esperado:

Recebimento de respostas ICMP sem perda de pacotes.
