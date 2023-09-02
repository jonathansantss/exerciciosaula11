// this is a js file
// jonathan dos santos

//function imprimirOlaMundo( ) { 
 //   console.log("Ola Mundo!");
//}
//imprimirOlaMundo( )

//function imprimirnome(nome){
 //   console.log("Ola" + nome);
//}

//imprimirnome("jonathan");
//imprimirnome("felipe");
//imprimirnome("lidia");

//let lernome =prompt("Qual seu nome");
//imprimirnome(lernome); 

//const a = 1

//function imprimeVariavel ( ){
 //   const b = 2
 //   console.log('Variavel a', a)
  //  console.log('Variavel b', b)
//}
//imprimeVariavel()
//console.log('Variavel a', a)
//console.log('Variavel b', b)

//function calculaArea(altura, largura) {
 //   const area = altura * largura
 //   return area
//}

//ATRIBUI RETORNO Á UMA VARIAVEL
//const areaCalculada = calculaArea(2, 3)

//imprimir o retorno no console
//console.log(calculaArea(2, 3))

//function calcularespaço(Largura, altura) {
   // const espaço = Largura * altura
    //return espaço
//}
//const calcularespaço = espaçocalculado(4, 5)
//console.log(calcularespaço(4, 5))

function soma(soma1, soma2){
    const soma = soma1 + soma2;
    return soma;
}
const resultado = soma(3, 4);
console.log(somar(3, 4))

function array([]){
    const array3 = [1, 2, 3, 4]
    const divisao = 1 / 2
    const divisao2 = 4 / 2
    const array2 = [divisao, divisao2]
    return array2;
};

const resultado2 = array()
console.log(array())

function retornoPrimeiroEUltimo(meuarray = []){
    let novoArray = [];
    novoArray[0] = (meuarray[meuarray.length -1])/2;
    return novoArray;
}
let antigoArray =
[1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20];

console.log(retornaPrimeiroEultimo(antigoArray));
