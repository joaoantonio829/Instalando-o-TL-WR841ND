# Guia de Configuração do Roteador TL-WR841ND

Este guia ajuda você a configurar o roteador TP-Link TL-WR841ND utilizando o emulador oficial da TP-Link.

## # Roteador: TL-WR841ND

![TL-WR841ND](https://th.bing.com/th/id/OIP.U_sYhqsLd3TkLLD1YtG7AQHaFj?cb=iwp2\&rs=1\&pid=ImgDetMain)

---

## # Etapa 1: Quick Setup

Explore a função de configuração rápida:

* Escolha o tipo de conexão: IP dinâmico (geralmente o mais comum), IP estático ou PPPoE (se houver login e senha do provedor).

![TIPO DE CONEXAO](https://github.com/user-attachments/assets/063b1350-32c8-4dd7-8aeb-7c7beafcfe39)

---

## # Etapa 2: Configurações de Rede

### WAN

![WAN](https://github.com/user-attachments/assets/ad78f371-81a1-4c49-a3b1-d705d903fb78)

* Selecione o tipo de conexão (automática ou manual).
* Insira IP, gateway e DNS, se necessário.

### LAN

* O endereço padrão é `192.168.0.1`.
* Caso altere, use o novo IP para acessar o roteador.

![LAN](https://github.com/user-attachments/assets/8a82d1df-6ffd-4376-909e-50f1efbceb51)

---

## # Etapa 3: Wireless

### Wireless Settings

![image](https://github.com/user-attachments/assets/bdad34f2-911d-4b84-8b3b-3fb9517f3965)

### Wireless Security

* Selecione WPA2-PSK.
* Crie uma senha segura.

![image](https://github.com/user-attachments/assets/0964418b-1fc6-492d-b149-7ac99aa4052e)

---

## # Etapa 4: DHCP

* Ative o servidor DHCP para distribuir IPs automaticamente.
* Defina o intervalo de IPs (ex: de 192.168.0.100 a 192.168.0.199).
* Desative se já existir outro servidor DHCP na rede.
* CODIGO DE EXEMPLO "Primary DNS ESecondary DNS" FOI O DO GOOGLE DNS

![DHCP](https://github.com/user-attachments/assets/e00a1bf6-3f49-4ff9-b80d-b13cb8803f8b)

---

## # Etapa 5: Segurança

* Ative o firewall.
* Use filtros de IP ou MAC para controlar o acesso.
* Ative a proteção SPI Firewall.
* Desative o SIP ALG apenas se você tiver problemas com serviços de voz sobre IP (VoIP), como o Zoiper ou WhatsApp Web com chamadas travando.


![SEGURANÇA](https://github.com/user-attachments/assets/9d5681a3-5fc2-4c97-a1e3-3a029e3e2bd0)

---

## # Ferramentas do Sistema

Acesse **System Tools** para:

* Fazer backup ou restaurar configurações.
* Atualizar o firmware.
* Reiniciar o roteador.

```md
[ Print das ferramentas do sistema ]
```

---

## # Logout

* Finalize a sessão clicando em **Logout** no canto superior direito.

```md
[ Print do botão de logout ]
```
