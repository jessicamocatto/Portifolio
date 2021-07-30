Algoritmo "Auto_Posto"
const
     ma = 2
tipo
    posto = registro
    nome: caractere
    cpf: inteiro
    combustivel: inteiro
    qtd: real
    valor: real
    fimregistro
Var
   ranga:vetor[1..ma] de posto
   i: inteiro
   tip: caractere
   preco, valor: real
Inicio
      para i de 1 ate ma faca
      escreval("           POSTO IPIRANGA           ")
      escreval("Digite o nome do cliente: ")
      leia(ranga[i].nome)
      escreval("Digite o CPF:")
      leia(ranga[i].cpf)
      escreval("Digite o tipo de combustivel:")
      escreval("[1]Diesel - R$ 2,499")
      escreval("[2]Etanol- R$ 2,499")
      escreval("[3]Gasolina- R$ 4,499")
      leia(ranga[i].combustivel)
      escolha ranga[i].combustivel
      caso 1
           escreval("Diesel")
           tip:= "Diesel"
           preco:= 2.49
      caso 2
           escreval("Etanol")
           tip:= "Etanol"
           preco:=  2.49
      caso 3
           escreval("Gasolina")
           tip:= "Gasolina"
           preco:= 4.49
      fimescolha
      escreval("Digite a quantidade:")
      leia(ranga[i].qtd)
      
      ranga[i].valor:= preco * ranga[i].qtd
      
      escreval("Valor total: ", ranga[i].valor)
      limpatela
      fimpara

      escreval("           POSTO IPIRANGA           ")
      escreval("[1]-Diesel,[2]-Etanol,[3]-Gasolina")
      para i de 1 ate ma faca
      escreval("Nomedo cliente: ",maiusc(ranga[i].nome))
      escreval("CPF: ",ranga[i].cpf)
      escreval("Tipo de combustivel: ",tip)
      escreval("Litros: ",ranga[i].qtd)
      escreval("Valor total:",ranga[i].valor)
      escreval("______________________")
      fimpara
Fimalgoritmo