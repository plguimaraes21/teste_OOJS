# teste_OOJS
Atividade da aula de orientação de objetos, simulando a criação de diversos tipos de contas bancárias e operações disponíveis em cada uma.

Criei uma classe ContaBancaria, que possui os parâmetros agencia, numero, tipo e saldo;
Dentro de ContaBancaria, construi o getter e o setter de saldo;
Dentro de ContaBancaria, adicionei os métodos sacar e depositar;
Criei uma classe-filha chamada ContaCorrente que herda todos esses parâmetros e ainda possua o parâmetro cartaoCredito;
Ainda em ContaCorrente, construi o getter e o setter de cartaoCredito;
Ainda em ContaCorrente, fiz com que o tipo seja 'conta corrente' por padrão;
Criei uma classe-filha chamada ContaPoupanca que herda todos os parâmetros de ContaBancaria;
Criei uma classe-filha chamada ContaUniversitaria que herda todos os parâmetros de ContaBancaria;
E, dentro da ContaUniversitaria, fiz com que o método saque seja capaz de sacar apenas valores menores que 500 reais.
