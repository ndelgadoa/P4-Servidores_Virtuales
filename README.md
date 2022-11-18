# P4-Servidores_Virtuales

- 39 lines (35 sloc)  3.28 KB

Crea dos sitios web que compartirán IP y puerto, pero tendrán nombres DNS distintos para acceder a ellos. El nombre del primer dominio será daw.gimbernat.eug.es y el segundo tunombreyapellidos.gimbernat.eug.es, donde “tunombreyapellidos” contiene la inicial de tu nombre, el primer apellido, y la inicial de tu segundo apellido. De esta manera, si tu nombre es: Francisco Mesas Cervilla, el domino quedaría: fmesasc.gimbernat.eug.es. • En el primer caso, daw.gimbernat.eug.es tendrá su directorio base en /var/www/daw/ conteniendo una página llamada index.html que ponga el nombre de la clase como título con un archivo css para aplicarle estilos al título. • En el segundo caso, fmesasc.gimbernat.eug.es tendrá su directorio base en /var/www/fmesasc/ (el equivalente para vuestros nombres), conteniendo una página llamada index.html que contenga vuestro currículum aplicándole un estilo css para que se visualice correctamente. Para ello, tendrás que crear un archivo de configuración (copiado de 000-default.conf) para cada uno de los dominios. Recuerda que con a2ensite puedes crear los enlaces simbólicos necesarios para añadir esta configuración a la ejecución de apache.

![image](https://user-images.githubusercontent.com/113515284/202307162-38ad0e96-9f4d-4207-88e3-c840eca7d352.png)

![image](https://user-images.githubusercontent.com/113515284/202307740-a6ff9273-32db-442a-a062-d220f95a6480.png)

![image](https://user-images.githubusercontent.com/113515284/202308100-f639538c-5051-41a6-9907-f5af9b42e44f.png)

![image](https://user-images.githubusercontent.com/113515284/202309083-ee25e26f-b268-4710-b8dd-86719e6e503d.png)

![image](https://user-images.githubusercontent.com/113515284/202310555-7007e5be-02b4-4907-8cb0-c6dedc61877b.png)

![image](https://user-images.githubusercontent.com/113515284/202311075-f40a8a5d-4249-4107-b72b-5ea27933351b.png)

![image](https://user-images.githubusercontent.com/113515284/202664737-d593ebee-0d85-4873-ad2d-eec1a0baa918.png)

![image](https://user-images.githubusercontent.com/113515284/202665015-5f31ad36-2e2f-4421-a1c6-28fc5d7eb4df.png)




![image](https://user-images.githubusercontent.com/113515284/202512172-a8c4863f-795c-4648-8d50-4772efcbd124.png)


![image](https://user-images.githubusercontent.com/113515284/202317694-f4b1c006-aa02-4b0c-a23d-a5fbe89fbc78.png)
![image](https://user-images.githubusercontent.com/113515284/202317800-b49887cd-f492-4b73-9e1a-fcd79325bdd2.png)

![image](https://user-images.githubusercontent.com/113515284/202664426-5f9430a3-a49f-42ce-8775-3dfc68730700.png)
![image](https://user-images.githubusercontent.com/113515284/202664518-ca5ab05e-fe9d-430e-846d-0341b78d259f.png)

![image](https://user-images.githubusercontent.com/113515284/202666103-595b3440-883c-4468-9074-59ec7ece15f0.png)

![image](https://user-images.githubusercontent.com/113515284/202666117-08c47982-db53-4e9c-99b8-97c5c6420ec3.png)






