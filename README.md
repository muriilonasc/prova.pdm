# prova.pdm
let aluno = { //criando um aluno
    nome : "Murilo Nascimento da Silva", //indicando o nome do aluno
    idade: 16, // inserindo a idade do aluno
    cursando:["MAT" ,"PORT","QUI","FIS","ART"], // colocando as materias do aluno
    presença:["24-02-10","24-02-11","24-02-12","24-02-13","24-02-14","24-02-15","24-02-16","24-02-17","24-02-18","24-02-19","24-02-20"], // os dias de presença do aluno
    ra:"24135678" // adicionando o rs do aluno
}
function validarAluno(){ //validando aluno
    if (nome.aluno< 10 ) { //se o nome do aluno tiver menos de 10 caracteres 
        nome.returnValue = false; //retorna falso, o nome não é validado
      }
      if (idade.aluno<14){ //se a idade do aluno for menor que 14
        idade.returnValue = false; // a idade não é validada
      }
      if (cursando.aluno<3){ //se o aluno estiver cursando menos de 3 materias 
        cursando.returnValue = false; // os cursos não são validados
      }
      if (presença.aluno<2){ //se o aluno tiver menos de duas presenças 
        presença.returnValue = false; // presença não é validada
      }
      if(ra.aluno<7){ // se o ra do aluno for menor que 7 
        ra.returnValue = false; //o ra não é validado
      }

}

MuriloNascimento da Silva
Kaua Oliveira 
