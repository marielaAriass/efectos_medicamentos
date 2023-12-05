# Efectos_medicamentos
Proyecto Final para la clase Topicos Selectos de Ciencias de Datos 2024-1, para la Universidad Nacional Autónoma de México | UNAM, en la Escuela Nacional de Estudios Superiores Unidad Campus Morelia | ENES Morelia.

Los contenidos de este repositorio están autorizados bajo la Licencia Pública General GNU versión 3. Visite https://www.gnu.org/licenses/gpl-3.0.html para obtener más información.

### Datos
Los datos se encuentran disponibles [aquí](https://www.kaggle.com/datasets/jithinanievarghese/drugs-side-effects-and-medical-condition). Contienen detalles de varios medicamentos utilizados para afecciones como acné , cáncer , enfermedades cardíacas , etc.y sus efectos secundarios.

Los datos están almacenados en el archivo `drugs_side_effects.csv`
Descripción de las columnas:
- `drug_name`. Nombre de medicamentos
- `medical_condition`. Nombre de la condición medica para la que se ocupa el medicamento
- `side_effects`. Descripción de los efectos secundarios
- `generic_name`. Nombre químico del medicamento
- `drug_classes`. Clase de medicamento es un conjunto de medicamentos con estructura química similar, el mismo mecanismo de acción (es decir, unión al mismo objetivo biológico), un modo de acción relacionado y/o se utilizan para tratar la misma enfermedad.
- `brand_names`. Marcas en la que los medicamentos se venden
- `activity`. Actividad reciente de los visitantes del sitio en relación con otros medicamentos de la lista. Los datos se obtuvieron de [este link](https://www.drugs.com)
- `rx_otc`. Venta libre o con receta:
  - OTC = medicamento que se puede comprar sin receta médica.
  - Rx = Receta necesaria
  - Rx/OTC = Recetada o sin receta.
- `pregnancy_category`.
  - A = Estudios adecuados y bien controlados no han logrado demostrar un riesgo para el feto en el primer trimestre del embarazo (y no hay evidencia de riesgo en los trimestres posteriores).
  - B = Los estudios de reproducción animal no han logrado demostrar un riesgo para el feto y no existen estudios adecuados y bien controlados en mujeres embarazadas.
  - C = Los estudios de reproducción animal han demostrado un efecto adverso en el feto y no existen estudios adecuados y bien controlados en humanos, pero los beneficios potenciales pueden justificar su uso en mujeres embarazadas a pesar de los riesgos potenciales.
  - D = Existe evidencia positiva de riesgo fetal humano basada en datos de reacciones adversas provenientes de experiencias o estudios de investigación o comercialización en humanos, pero los beneficios potenciales pueden justificar su uso en mujeres embarazadas a pesar de los riesgos potenciales.
  - X = Los estudios en animales o humanos han demostrado anomalías fetales y/o existe evidencia positiva de riesgo fetal humano basado en datos de reacciones adversas de la experiencia de investigación o comercialización, y los riesgos involucrados en el uso en mujeres embarazadas superan claramente los beneficios potenciales.
  - N = La FDA no ha clasificado el medicamento.
- `csa`. Lista de Ley de Sustancias Controladas (CSA)
  - M = El medicamento tiene múltiples listas. El cronograma puede depender de la forma farmacéutica exacta o la concentración del medicamento.
  - U = Se desconoce el horario de CSA.
  - N = No está sujeto a la Ley de Sustancias Controladas.
  - 1 = Tiene un alto potencial de abuso. Actualmente no tiene ningún uso médico aceptado en el tratamiento en los Estados Unidos. Existe una falta de seguridad aceptada para su uso bajo supervisión médica.
  - 2 = Tiene un alto potencial de abuso. Tiene un uso médico actualmente aceptado en tratamiento en los Estados Unidos o un uso médico actualmente aceptado con restricciones severas. El abuso puede provocar una dependencia psicológica o física grave.
  - 3 = Tiene un potencial de abuso menor que aquellos en los cuadros 1 y 2. Tiene un uso médico actualmente aceptado en tratamiento en los Estados Unidos. El abuso puede conducir a una dependencia física moderada o baja o una dependencia psicológica alta.
  - 4 = Tiene un bajo potencial de abuso en relación con los del programa 3. Tiene un uso médico actualmente aceptado en el tratamiento en los Estados Unidos. El abuso puede conducir a una dependencia física o psicológica limitada en relación con los del programa 3.
  - 5 = Tiene un bajo potencial de abuso en relación con los del programa 4. Tiene un uso médico actualmente aceptado en el tratamiento en los Estados Unidos. El abuso puede conducir a una dependencia física o psicológica limitada en relación con las del cuadro 4.
- `alcohol`.
  - X = Interactúa con el alcohol.
- `related_drugs`. 
- `medical_condition_description`.
- `rating`. Qué tan efectivo encontraban el medicamento considerando los efectos positivos/adversos y la facilidad de uso (1 = no efectivo, 10 = más efectivo).
- `no_of_reviews`.
- `drug_link`.
- `medical_condition_url`.
  
