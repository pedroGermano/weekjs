/**
 * 
 * Quando você deve usar o map:
 * 
 * -- Quando você precisa obter um novo array, 
 * com a mesma quantidade itens do array original.
 */

 Toda função sem retorno vai retornar undefined
<!-- 
 const products = [
  { name: 'Mouse Sem Fio', price: 30 },
  { name: 'Pen Drive', price: 25 },
  { name: 'Cartucho de Tinta', price: 50 },
  { name: 'Suporte Ergonômico para Notebook', price: 23 },
  { name: 'Repetidor de Sinal Wi-Fi', price: 44 }
]

const productsList = products.map(product => {
  if(product.price >= 30){
    return { 
      name: product.name,
      price: product.price / 2 
    } 
  }

  return product
})

console.log(productsList); -->


Quando você deve usar o filter: 

-- Quando você precisa obter um novo array, 
com uma quantidade de itens menor que a do array original