# 7. PROGRAMACIÓN ORIENTADA A OBJETOS (POO)
Objetivo: Verificar el dominio teórico y técnico del paradigma programación orientada a
objetos, mediante ejercicios para desarrollar su código y preguntas de respuesta
múltiple.

Indicaciones: Pedir responder cada una de las preguntas de manera acertada, breve y
clara, según sea el caso.

1. La Programación Orientada a Objetos es: (Valor 1 punto)

        c. Un paradigma que se basa en el uso de objetos.
      
2. Se refieren a características principalmente físicas y de estado de un objeto: (Valor 1 punto)

       b. Atributos
       
3. Sirve para derivar de una clase ya existente a otra clase: (Valor 1 punto)

        a. Herencia
                
4. De las siguientes opciones, selecciona las ventajas de la Programación Orientada a Objetos: (Valor 1 punto)

        b. Simplicidad
        c. Ahorra memoria
        d. Reutilización de código
        
5. Las clases normalmente cuentan con: (Valor 1 punto)

       c. Nombre de clase, atributos y métodos.
        
6. En programación, se utiliza para modelar un conjunto de objetos: (Valor 1 punto)

        b. Clase
          
7. ¿Qué son los métodos?

        a. Las propiedades presentes en un objeto.
        
8. Identifica las partes de una clase:

![image](https://user-images.githubusercontent.com/102439883/187043010-c909ef8e-7e49-45e0-9fe1-02048fb737af.png)

9. Deberás crear un programa que forme parte de un módulo para el sistema de una
estética de perros. El programa deberá de contener lo siguiente: (Valor 2 puntos)

a. Una clase RecibeMascota.

b. Los atributos: nombre de perro, edad, raza, tamaño y nombre de dueño.

c. Crear el método main en donde contendrá el código para realizar el
siguiente procedimiento:

  i. Crear un arreglo dinámico de tipo de la clase.
  
  ii. Hacer una instancia para crear un objeto de tipo de la clase.
  
  iii. Asignar valores a los atributos de la clase con datos que tú prefieras.
  
  iv. Agregar el objeto creado al arreglo.
  
  v. Imprimir la cantidad de perros que se encuentran en la estética con el
  siguiente mensaje: Perros actuales en la estética: “Número de
  perros”.

                  import java.util.ArrayList;
                  public class RecibeMascota {
                      String nombre; // Nombre de la mascota,
                      int edad; // Edad de la mascota
                      String sexo; // sexo
                      String nombreTutor; // Nombre completo del tutor
                      public static void main(String args[]) {
                        // Creamos un arreglo de tipo RecibeAlumno
                          ArrayList<RecibeAlumno> alumnosActuales = new ArrayList();

                          // Hacemos una instancia y creamos un objeto de tipo RecibeMascota
                          RecibeMascota miMascota = new RecibeMascota();
                          miMascota.nombre = "Manolo";
                          miMascota.edad = 18;
                          miMascota.sexo = "macho";
                          miMascota.raza = "puerquito";
                          miMascota.tamaño = "mediano";
                          miMascota.nombreTutor = "Paco Beristain";
                          mascotasActuales.add(miMascota);
                          System.out.println("Alumnos actuales en la clase: " + mascotasActuales.size());
                      }

                  }

       

