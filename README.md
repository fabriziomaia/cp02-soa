# Checkpoint 2 - API SOAP - Arquitetura SOA e Web Services

## Alunos
- rm551869 - Fabrizio Maia  
- rm551684 - Victor Asfur

## Descrição
Este projeto aplica os conceitos de SOA com Java 17, Maven e SOAP, com um servidor e dois clientes.

## Como Executar

### 1. Execute o servidor:
Classe: `Loader` no projeto WinerySys  
Publica os serviços:
- http://localhost:8085/WineStockService?wsdl
- http://localhost:8086/WineWarningService?wsdl

### 2. Compile os clientes:
```bash
mvn clean install
```

### 3. Execute:
- WineStockClient → `ApplicationClient1`
- WineOrderClient → `ApplicationClient2`

## Tecnologias
Java 17, Maven, JAX-WS, SOAP

## Entrega
Repositório GitHub enviado para:
- profcarlos.oliveira@fiap.com.br
- pf2308@fiap.com.br
