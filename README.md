# INFORME DE LABORATORIO 5

**UNIVERSIDAD DE LAS FUERZAS ARMADAS**

**DEPARTAMENTO DE ELECTRICA Y ELECTRÓNICA**

**FUNDAMENTOS DE CIRCUITOS ELECTRICOS**

Nombres : Martin Coronel, Jefferson Chicaiza, Tito Obando 

NRC: 10133

**1.OBJETIVOS**

***Objetivo General***

- Analizar el voltaje y la corriente solicitados en los diferentes componentes de un circuito cerrado, mediante una práctica de laboratorio para comprender cómo funciona el teorema de Thevenin y un circuito Equivalente. 

***Objetivo Especificos***

- Conocer los conceptos del teorema de Thevenin para mantener una idea calra de lo que tarta. 
- Realizar un circuito cerrado en un protoboard siguiendo la estructura dada por el docente, para analizar la corriente y voltaje de un circuito Equivalente a Thevenin.
- Medir  con el multimetro valores de las corrientes y volatje tanto en el circuito original como en el equivalente.  
- Comparar los valores calculados con los valores medidos para  determinar mayor validez a nuestro analisis.

**2.MARCO TEORICO**

![image](https://user-images.githubusercontent.com/94098157/149372776-f3897e7a-77c8-43ca-92af-aa8c60a54170.png)

**3.MATERIAL Y EQUIPO REQUERIDO**

![image](https://user-images.githubusercontent.com/94098157/149267370-3b8cdaf7-4598-4605-8de1-b2c4551c7b79.png)

**4.EXPLICACIÓN DEL PROCEDIMIENTO**

*1.Arme el circuito que se muestra en la figura 5.1.*

![image](https://user-images.githubusercontent.com/94098157/149267912-4a9799c3-8417-44a1-b663-91c953d5b082.png)

![image](https://user-images.githubusercontent.com/94098157/149267987-8a3f50c1-b34e-43c2-b399-4ce0955e8d4b.png)

Primeramente se observa el funcionamiento del circuito eléctrico en base al diagrama propuesto por el docente. 

*2.Mida el voltaje y la corriente en el resistor R5, anote los resultados en la tabla 5.2.*

![image](https://user-images.githubusercontent.com/94098157/149268048-c9722d84-e38e-4ae9-b652-026f6281cef6.png)
Aquí se observa la medición del voltaje en R5.

![image](https://user-images.githubusercontent.com/94098157/149268119-e30f9d9f-c6ca-485d-9a2b-780e0d8bf859.png)
De la misma manera, se observa la corriente que actúa en la resistencia R5.

*3.Desconecte el resistor R5 y mida el voltaje en el circuito abierto. Anote el valor medido en la tabla 5.1.*

![image](https://user-images.githubusercontent.com/94098157/149268247-3ddd7456-733b-4965-a172-d4fd52ee301a.png)
Aquí se muestra el voltaje obtenido al remover la resistencia R5 y medirlo a partir de un circuito abierto y evidentemente ese valor representa el voltaje de Thevenin.

*4.Anule el efecto de las fuentes de alimentación. Desconecte R5 y desde el circuito abierto resultante mida la resistencia equivalente. Anote el valor medido en la tabla 5.1.*

![image](https://user-images.githubusercontent.com/94098157/149269300-369dbb81-1b64-486c-afa6-80cb679edcc1.png)
Haciendo corto a cada una de las fuentes de alimentación del circuito es decir reemplazandolas a partir de sus resistencias internas que equivalen a cero. 

*5.Implemente el circuito equivalente de Thévenin, agregue el resistor R5 y mida la corriente y el voltaje en el mismo, anote los resultados en la tabla 5.2*

![image](https://user-images.githubusercontent.com/94098157/149268939-893da561-2816-464e-ae08-f3015baa3adb.png)

![image](https://user-images.githubusercontent.com/94098157/149268954-19c46edd-bc8b-46f1-81bd-a424f01ef984.png)

Aquí se muestra el circuito equivalente de Thevenin con el circuito original, evidentemente la corriente y el voltaje son valores muy aproximados a los valores del circuito original en R5. 

*CIRCUITO DE THEVENIN ARMADO ANALITICAMENTE* 

Primeramente, se remueve la resistencia R5 del circuito  

![image](https://user-images.githubusercontent.com/94098157/149271991-6523d72b-bd0b-4d86-9443-2d9ee658ba30.png)

Se calcula el voltaje en R3 mediante el método de tensiones en los nodos es importante mencionar que R4 ya no pertenece al circuito cerrado dado que una de sus ramas ya no conecta al circuito. 

![image](https://user-images.githubusercontent.com/94098157/149274325-2eb5461f-3696-423d-a86f-1b1f80eb2b0f.png)

![image](https://user-images.githubusercontent.com/94098157/149274450-f75675ce-ecd1-4dc8-985e-7ca38295ee00.png)

Mediante Symbolab se pudo obtener el valor de V1 al que equivale a “X” para luego reemplazar y obtener una de las corrientes que pasa por R3, finalmente obtener su voltaje. 

![image](https://user-images.githubusercontent.com/94098157/149274560-6c5dbdb9-e2e9-45d4-a061-f99001f6a6ba.png)

Después hacemos corto a cada una de las fuentes de voltaje para obtener la resistencia equivalente de todo el circuito.

![image](https://user-images.githubusercontent.com/94098157/149275362-0c57ef91-1004-41c1-8781-e45112c50167.png)

![image](https://user-images.githubusercontent.com/94098157/149275923-2bf1ccaf-8803-4467-b9ee-42af33585bd6.png)

Finalmente se realiza el circuito equivalente de Thevenin 

![image](https://user-images.githubusercontent.com/94098157/149276820-6ad33190-cae0-4def-8759-9462e2a0a219.png)

Aquí se calcula el voltaje y la corriente del circuito equivalente al original en la resistencia de carga o R5 

![image](https://user-images.githubusercontent.com/94098157/149332902-d671aa80-b9a1-484d-a655-c14dfd0ade12.png)

Finalmente se muestra los datos puestos en las respectivas tablas 

![image](https://user-images.githubusercontent.com/94098157/149340807-410898a5-19c5-4799-8c18-c9fc9d83a23d.png)

![image](https://user-images.githubusercontent.com/94098157/149340829-a35dcca5-4e4c-4ec7-9f48-7b9fb19ddb3a.png)

**5. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR**

Evidentemente se muestra que tanto el circuito Equivalente de Thevenin  y el circuito original lanzan valores muy similares en los voltajes y corrientes respecto a la resistencia de carga R5. Por lo que el margen de error tiende a ser cero. 

![image](https://user-images.githubusercontent.com/94098157/149342137-574459d1-5ca8-4523-9b67-7f4f6129e2cb.png)

**6. VIDEO:**

https://www.youtube.com/watch?v=F_JLDdxXVqc

**7. CONCLUSIONES**
- Tener los conceptos claros en lo que ue se refiere a corriente y al definición del teorema de thevenin  nos ayudó a medir de forma precisa la correinte, voltaje y la resistencia equivalente del circuito original.  
- Se pudo observar que el teorema de thevenin es un metodo muy eficiente para realizar circuitos equivalentes. 
- Los valores analiticos, experimentales y simulados muestran una gran semejanza entre ellos, lo que signfica que la corriente y voltaje obtenidos del circuito cerrado y equivalente son en cierta manera precisos.
 
**8. BIBLIOGRAFÍA**

Floyd, T. (2007). *Principios de circuitos electricos* (Ed. 8va). Pearson EDUCATION
