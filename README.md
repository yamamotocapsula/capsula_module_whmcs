# WHMCS Sample Third Party Payment Gateway Module #

## Summary ##

Os módulos Payment Gateway permitem integrar soluções de pagamento com o WHMCS
plataforma.

Existem dois tipos de módulo de gateway:

* Gateways de terceiros - são soluções de pagamento em que ocorre o checkout

em um site remoto, geralmente hospedado pelo próprio gateway de pagamento.

* Merchant Gateways - são soluções de pagamento em que os detalhes do cartão de crédito

são coletados - geralmente dentro do aplicativo WHMCS, embora mais e mais
geralmente isso é feito remotamente, normalmente via iframe, com uma página hospedada
remotamente pelo gateway de pagamento, permitindo armazenamento em token.

Os arquivos de exemplo aqui demonstram como sugerimos um gateway de pagamento de terceiros
módulo para WHMCS ser estruturado e implementado.

Para mais informações, consulte a documentação em:
https://developers.whmcs.com/payment-gateways/

## Conteúdo recomendado do módulo ##

A estrutura recomendada de um módulo de gateway de terceiros é a seguinte.

``` 
 modules/gateways/
  |- callback/gatewaymodule.php
  |  gatewaymodule.php
```

## Requerimentos mínimos ##

Para obter os requisitos mínimos mais recentes do sistema WHMCS, consulte:
https://docs.whmcs.com/System_Requirements

Recomendamos que seu módulo siga os mesmos requisitos mínimos sempre que
possível.

## Recursos úteis

* [Developer Resources](https://developers.whmcs.com/)
* [Hook Documentation](https://developers.whmcs.com/hooks/)
* [API Documentation](https://developers.whmcs.com/api/)

[WHMCS Limited](https://www.whmcs.com)

## BRASIL

Feita as traduções do modulo e atualizado algumas funções prar o PHP 7.2

Funções podendo melhorar o empenho do módulo dentro do WHMCS

* [ Site ](https://capsula.com.br)

