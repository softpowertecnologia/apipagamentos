## Seja Bem Vindo(a)

Documentação oficial da API de Pagamentos Avant Digital

Dúvidas entrar em contato através do email ajuda@softpower.net.br

Última atualização 23/10/2019

### Pagador

Módulo de pagadores

- Parameters (É necessário enviar todos os campos para a API, mesmo que eles estejam em branco.)

```markdown
{
  "cpf_cnpj": "string",
  "nome": "string",
  "sobrenome": "string",
  "email": "user@example.com",
  "cep": "string",
  "endereco": "string",
  "numero": "string",
  "complemento": "string",
  "bairro": "string",
  "cidade": "string",
  "estado": "string"
}
```

- Responses

Códigos

- 201

```markdown
Pagador inserido com sucesso!
```

Example Value | Model

```markdown
{
  "status": true,
  "dados": [
    {
      "codigo": "string",
      "cpf_cnpj": "string",
      "nome": "string",
      "sobrenome": "string",
      "email": "string",
      "cep": "string",
      "endereco": "string",
      "numero": "string",
      "complemento": "string",
      "bairro": "string",
      "cidade": "string",
      "estado": "string",
      "status": 0,
      "insercao": "string",
      "alteracao": "string"
    }
  ],
  "mensagem": "string"
}
```

- 400

```markdown
Erro na requisição enviada. Verifique a mensagem de retorno
```

Example Value | Model

```markdown
{
  "status": false,
  "dados": {},
  "mensagem": "string"
}
```

- 401

```markdown
Sem autorização
```

- 500

```markdown
Erro desconhecido na API. Tente novamente mais tarde ou entre em contato com o suporte
```

Example Value | Model

```markdown
{
  "status": false,
  "dados": {},
  "mensagem": "string"
}
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/softpowertecnologia/apipagamentos/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
