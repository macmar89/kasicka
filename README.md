function scitaj(a, b) {
	return a + b
};

let vysledok = scitaj (5, 12);


function vacsie(a,b) {
	if (a > b) {
  	console.log(a + ' je väčšie')
  } else {
  	console.log(b + ' je väčšie')
  }
};



let pole = [88 ,35, 74, 134, 80, 14];
let poleScitaj = pole[0] + pole[3];



 function najvacsie(pole) {
	let a = pole[0];

  for (let i = 0; i < pole.length; i++) {
  	if (a < pole[i]) {
    	a = pole[i]
    };
  };
	console.log('Najvacsie číslo je ' + a + '. Ak sa mi to podarí. :)'); 
};

najvacsie(pole);

 function scitajPole(pole) {
	let a = 0;
  for (let i = 0; i < pole.length; i++) {
  	a = a + pole[i]
  };
	console.log('Súčet čísel v poli jeeeee ' + a ); 
};

scitajPole(pole);

/*  console.log('Najvacsie číslo je ' + a + '. Ak sa mi to podarí. :)'); 
		  console.log('prve číslo je ' + a)	*/ 















