* Descripción de la implementación
La solución fue implementada en Java usando Maven, siguendo los pasos a continuación
1.- Obtener fecha inicio, fecha fin y rango generado por la clase Valores
2.- Generar todos los Ufs para el rango indicado por las fechas previamente obttenidas
3.- Concatenar la lista obtenida el paso 2 con la lista (lista usada fuente para completar las "lagunas") de la clase Valores 
4.- Eliminar duplicados en la lista obtenida en el paso 3 y ordenar el resultado
5.- Guardar en el archivo de salida valores.json

* Tecnología y librerías utilizadas
- Java y Maven
- Librerias:
import com.google.gson.JsonArray;
import com.google.gson.JsonObject;
import com.previred.desafio.tres.uf.DatosUf;
import com.previred.desafio.tres.uf.Valores;
import com.previred.desafio.tres.uf.vo.Uf;
import com.previred.desafio.tres.uf.vo.Ufs;
import java.io.FileWriter;
import java.util.*;
import java.util.stream.Collectors;
import java.util.stream.Stream;

* Detalles de compilación y ejecución
La compilación y ejecución se hizo a través de Maven y usando la herramienta Intellij IDEA Community



