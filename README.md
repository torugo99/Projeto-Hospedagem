# 馃捇 | Projeto: Sistema de Hospedagem - Desafio DIO.

### Projeto integrador feito para por em pr谩tica as de C#:

Seja bem vindo ao meu projeto chamado "Sistema de Hospedagem", feito totalmente para meus estudos e aperfei莽oamento como profissional. 鉂わ笍

- Colocando em pr谩tica conceitos obtidos durante a aula.

- Utilizando a linguagem: C#.


### 馃幀 | Preview: 
Aqui inserimos os dados Iniciais que 茅 pedido:
No caso estamos inserindo 4 h贸spede na reserva. 

```cs
Pessoa p1 = new Pessoa(nome: "H贸spede 1", sobrenome: "");
Pessoa p2 = new Pessoa(nome: "H贸spede 2", sobrenome: "");
Pessoa p3 = new Pessoa(nome: "H贸spede 3", sobrenome: "");
Pessoa p4 = new Pessoa(nome: "H贸spede 4", sobrenome: "");

hospedes.Add(p1);
hospedes.Add(p2);
hospedes.Add(p3);
hospedes.Add(p4);
```
Temos o total de 4 h贸spede, podemos inserir nome e sobrenome.

<br>
Aqui inserimos os dados necessario para calcular o valor da nossa reserva:

```cs
Suite suite = new Suite(tipoSuite: "Premium", capacidade: 4, valorDiaria: 20);

Reserva reserva = new Reserva(diasReservados: 02);
```
Dando no console ```dotnet run``` podemos ter a resposta:

```
H贸spedes: 4
Valor di谩ria: R$ 40
```
Existem algumas valida莽玫es que foram criadas a pedido do desafio como:
- Verificar a capacidade com total de de h贸spede.
- Da um desconto de 10% se caso a hospedagem for igual ou maior que 10 dias.

<b>[Certificado do Projeto](https://www.dio.me/certificate/C835B0A8/share)</b>


## 馃懇鈥嶐煉? Meus Links:

- Github: [Victor Hugo.](https://github.com/torugo99)
- LinkedIn: [Victor Hugo.](https://www.linkedin.com/in/victor-hugo99/)
- Meu Site: [Victor99dev.](http://victor99dev.site/)

### 馃榾 | Cr茅ditos e Agradecimentos:

- Obrigado a DIO a essa oportunidade de UP na minha carreira! 鉂わ笍
