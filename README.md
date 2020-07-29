# Desafio - EnderecoFind

Desafio da implementação de um app em flutter.

## Desafio
Implementar utilizando a linguagem Dart e o Framwork Flutter a seguinte aplicação:

![](https://github.com/iramarJunior/Desafio_EnderecoFind/blob/master/img/prototipo.png)

## Requisitos
- Consumir a API da ViaCEP;
- Utilizar o endereço ```viacep.com.br/ws/{CEP}/json/``` para obter o retorno;

## Links
- [Imagem do aplicativo no Figma](https://www.figma.com/file/1lhIRMzMTw6PSXLtj4ApJI/Projeto-CEP?node-id=0%3A1)
- [API ViaCEP](https://viacep.com.br/)

## API ViaCEP
Enviar a requisição do tipo: GET para:
```
https://viacep.com.br/ws/01001000/json/
```
Retorno Esperado:
```JSON
{
  "cep": "01001-000",
  "logradouro": "Praça da Sé",
  "complemento": "lado ímpar",
  "bairro": "Sé",
  "localidade": "São Paulo",
  "uf": "SP",
  "unidade": "",
  "ibge": "3550308",
  "gia": "1004"
}
```
