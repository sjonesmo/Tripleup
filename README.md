Tripleup
========
// JavaScript Document
function tripleup(array){
	for(i=0;i<array.length-2;i++){
		if(array[i] == (array[i+1]-1) && array[i] == (array[i+2]-2)){
			return true;
		}
	}
	return false;}
