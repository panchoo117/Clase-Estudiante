# Clase-Estudiante
// Clase que representa a un estudiante
public class Estudiante {

    // Atributos
    private String nombre;
    private int edad;
    private double promedio;

    // Constructor
    public Estudiante(String nombre, int edad, double promedio) {
        this.nombre = nombre;
        this.edad = edad;
        this.promedio = promedio;
    }

    // Métodos
    public void mostrarInformacion() {
        System.out.println("Nombre: " + nombre);
        System.out.println("Edad: " + edad);
        System.out.println("Promedio: " + promedio);
        System.out.println("-------------------------");
    }

    public void actualizarPromedio(double nuevoPromedio) {
        this.promedio = nuevoPromedio;
        System.out.println("Promedio actualizado para " + nombre);
    }
}
