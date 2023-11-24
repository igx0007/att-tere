use('db_barbie_filmes');

db.getCollection('filmes').insertMany([
  {
    _id: 1,
    titulo:"Homem Aranha:atraves do aranha verso",
    descriçao:"Depois de ser transportado através do multiverso, o herói deverá unir forças com a mulher-aranha Gwen Stacy (Hailee Steinfeld) e um novo time de Homens-Aranhas de dimensões paralelas para enfrentar um inimigo poderoso e mortal",
    imagem:"/homemaranha.png",
  },
  {
    _id: 2,
    titulo:"Os Mercenários 4",
    descriçao:" No quarto filme da franquia Os Mercenários, a equipe enfrentará um traficante de armas que comanda um enorme exército privado. Munidos com todas as armas inimagináveis, os Mercenários são a última linha de defesa do mundo",
    imagem:"/mercenarios.png",
  },
  {
    _id: 3,
    titulo:"Leo",
    descriçao:"Leo (Adam Sandler) é um velho lagarto que está há anos preso com uma tartaruga (Bill Burr) em um terrário na sala de aula de uma escola. Então, ao descobrir que tem apenas mais um ano de vida, Leo planeja fugir das quatro paredes de vidro para viver o restante de seu tempo no mundo fora. Porém, nada vai como planejado, já que ele se envolve com os problemas da turma. No final, seus últimos desejos não são nada como imaginava - ou planejava - mas o resultado o surpreende.",
    imagem:"/leo.png",
  },
  {_id: 4,
    titulo:"Oppenheimer",
    descriçao:" é a primeira biografia completa do “pai da bomba atômica”. J. Robert Oppenheimer foi o brilhante e carismático físico que liderou os esforços para desenvolver uma arma nuclear em favor de seu país durante a guerra.",
    imagem:"/Oppenheimer.png",
  },
  {id: 5,
    titulo:"Guardiões da Galáxia Vol. 3",
    descriçao:"Peter Quill (Chris Pratt) ainda se recupera da perda de sua amada Gamora (Zoe Saldaña) após os acontecimentos de Vingadores: Ultimato (2019), quando precisa reunir os Guardiões da Galáxia para defender o universo e proteger um de seus companheiros.",
    imagem:"/guardioes.png",
  },
]);
