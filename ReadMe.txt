import static org.junit.Assert.assertTrue;
import static org.junit.jupiter.api.Assertions.*;

import org.junit.jupiter.api.Test;

class InfoEstudianteTest {
	
	@Test
	public void promediarEs() {
		System.out.println(" prueba de promediar español ");
		assertTrue(InfoEstudiante.promediarEs() == 2.5);
	}
	
	@Test
	public void promediarIn() {
		System.out.println(" prueba de promediar español ");
		assertTrue(InfoEstudiante.promediarIn() == 4.5);
	}
	
	
	@Test
	public void promediarSemestre() {
		System.out.println(" prube a de promediar Semestre");
		assertTrue(InfoEstudiante.promediarSemestre() == 3.5);
	}

}
