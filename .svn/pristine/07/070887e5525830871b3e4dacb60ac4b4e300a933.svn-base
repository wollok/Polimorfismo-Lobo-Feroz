import loboFeroz.*

object casaLadrillosMultitudinaria{
	var ladrillos = 10
	var capacidadMaxima = 3
	var ocupantes = [chanchitoTrabajador]
	
	method llega(chanchito){
		ocupantes.add(chanchito)
	}
	method seVa(chanchito){
		ocupantes.remove(chanchito)
	}
	method estaLlena() {
		return ocupantes.size() >= capacidadMaxima
	}
	method pesoOcupantes(){
		return ocupantes.sum({ocupante=>ocupante.peso()})
	}
	
	method resistencia(){
		return 2 * ladrillos
	}
	
	method minutos(){
		return casaPaja.minutos()+casaMadera.minutos()
	}
}
