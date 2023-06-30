# camunda-archetype-servlet-war-example

First of all we need to add camunda archetype-servlet-war to our intellij maven project

![image](https://github.com/ghailen/camunda-archetype-servlet-war-example/assets/36199753/18bcd69b-219f-4bea-b4f8-fd4903630bf8)

![image](https://github.com/ghailen/camunda-archetype-servlet-war-example/assets/36199753/b4cdad43-4449-4cac-a8e2-baf8a804d0c7)

![image](https://github.com/ghailen/camunda-archetype-servlet-war-example/assets/36199753/9f64c71e-e6e2-41ea-a08c-d251339ad6ab)

We can found to many dependancies here : like junit , H2 database ...

![image](https://github.com/ghailen/camunda-archetype-servlet-war-example/assets/36199753/7efdf08d-0593-4d22-8e42-8ce51603da73)


The default bpmn file named process.bpmn
the structure of the project is like this :
Resources folder contains the bpmn files
Webapp folder contains forms file: 
![image](https://github.com/ghailen/camunda-archetype-servlet-war-example/assets/36199753/c11ca22e-56ad-46b4-9924-94db9a203282)

Lets here add a task (a user task which will be executed by a user)
and add a name to the process :
![image](https://github.com/ghailen/camunda-archetype-servlet-war-example/assets/36199753/c0ffd883-2b33-48b5-be2c-d6b95b11c2fc)


Now lets save the new bpmn file and run : 
-maven clean
-maven install

a war was generated :
![image](https://github.com/ghailen/camunda-archetype-servlet-war-example/assets/36199753/42e1965e-df36-4c98-8b0d-4b0f4ad1ebe4)

