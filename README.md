package Fundamentos_Java_aula_2_OO;

public class Aluno {
	int matricula ;
	String nome ;
	String cpf ;
	
	void info () {
		System.out.println("matricula " + matricula);	
		System.out.println("o cpf é " + cpf);
		System.out.println("o nome do aluno é " + nome);

}

}

// aba teste


package Fundamentos_Java_aula_2_OO;

public class teste {

	public static void main(String[] args) {
		Aluno a = new Aluno() ;
		a.matricula = 1001;
		a.cpf = "01533321078" ;
		a.nome = "Igor" ;
	
		Aluno b = new Aluno() ;
		b.matricula = 1002;
		b.cpf = "55533321270" ;
		b.nome = "Suelen" ;
	
		
		
		
	    a.info();
	    b.info();
		
		
		
		
		/*System.out.println("matricula " + a.matricula);	
	System.out.println("o cpf é " + a.cpf);
	System.out.println("o nome do aluno é " + a.nome);
	*/
	
	}

}

