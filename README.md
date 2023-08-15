# ICYA 4710 _Modelación en Hidrología

A lo largo del curso vamos a utilizar python 3.9. Para ello, recomiendo la instalación de Anaconda y de jupyterlab para trabajar con notebooks. En Windows, se pueden seguir los siguientes pasos:

1. Descargar e instalar [Anaconda](https://repo.anaconda.com/archive/Anaconda3-2023.07-2-Windows-x86_64.exe)
2. Una vez instalado, ir a Inicio -> Todas las aplcaciones -> Anaconda3 -> Anaconda Powershell Prompt
3. Luego de abierta la terminal, ejecutar el siguiente comando:
  ```powershell
  conda create -n icya4710 -y python==3.9 numpy pandas matplotlib jupyterlab
  ```
4. Activar el nuevo environment:
   ```powershell
   conda activate icya4710
   ```
5. Ahora, abra jupyterlab ejecutando el siguiente comando en la terminal:
   ```powershell
   jupyter lab
   ```
