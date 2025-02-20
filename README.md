# GoBus

[![Go Report Card](https://goreportcard.com/badge/github.com/user/gobus)](https://goreportcard.com/report/github.com/user/gobus)
[![GoDoc](https://godoc.org/github.com/user/gobus?status.svg)](https://godoc.org/github.com/user/gobus)

GoBus é uma biblioteca leve de publicação/assinatura (pub/sub) em Go que utiliza generics para trabalhar com diferentes tipos de eventos. Inclui um sistema de confirmação (ACK) para garantir o processamento confiável de mensagens.

### Componentes

- **EventBus**: Componente central que gerencia tópicos, roteia eventos e controla confirmações
- **Publisher**: Serviços que publicam eventos em tópicos específicos
- **Subscriber**: Serviços que consomem e processam eventos, enviando confirmações

## Características

- Uso de Generics para suporte a diferentes tipos de eventos
- Sistema de confirmação de processamento (ACK/NACK)
- Totalmente thread-safe
- Sem dependências externas
- API simples e intuitiva

## Instalação

```bash
go get github.com/user/gobus