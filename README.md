# juandavidespitialeon- actividad 6

## 1) Lee la Información que se compartió en la misma guía y desarrolla un resumen de lo entendido, anexo agrega pantallazos de la información del paso a paso que se te muestra.
Lo que se puede leer en la guia es como actualizar mi dispositivo,  y ver que no tengan virus pero tambien se menciona como verificar si estan cifrados mis archivos, como instalar programas de manera segura  y ver que mi dispositivo tenga un bloqueo de acceso, desafortunamente la guia unicamente habla a detalle de las primeras 2, mi entendimiento es que es recomendable estar actualizado porque si llegamos a tener versiones viejas del sistema es mucho mas facil y probable que alguien pueda entrar en nuestros archivos por culpa del rapido crecimiento de los "hackers", pero asi mismo los sitemas intentan mantenerse al la par para no ser tan sencillos de vulnerar, estar actualizado tampoco nos vuelve inmunes pero por lo menos disminuye las posibilidades , tambien debemos procurar no causarnos daño a nosotros mismo a travez de enlaces sospechosos o intentando instalar aplicaciones de sitios no verificados esto obviamente podria "infectarnos" de un virus o varios.

## 1.1) como actualizar tus dispositivos 
primero nos metemos a configuracion

<img width="554" height="312" alt="image" src="https://github.com/user-attachments/assets/aca4d35f-b18d-4507-b987-f8fa48724134" />

luego nos metemos en "windows update" y verificamos estar con la ultima actualizacion


<img width="1600" height="890" alt="image" src="https://github.com/user-attachments/assets/23cbdcd4-3afa-4e33-b0e1-64897ff7346a" />
en este caso el sistema esta al dia, pero si no pues la idea seria buscar actualizaciones y descargarlas, tambien existe la opcion de actualizar el sistema automaticamente pero si no estoy mal ya es una funcion implementada en la mayoria de dispositivos modernos

## 1.2) Como comprobar que tus dispositivos estan protegidos (antivirus)
nuevamente entramos a la configuracion


<img width="554" height="312" alt="image" src="https://github.com/user-attachments/assets/aca4d35f-b18d-4507-b987-f8fa48724134" />

pero en esta ocasion entramos a la privacidad y seguridad


<img width="251" height="45" alt="image" src="https://github.com/user-attachments/assets/92406e48-721a-4839-a529-060c3ed44cac" />
 y buscamos la opcion de "seguridad e windows"

 <img width="1082" height="173" alt="image" src="https://github.com/user-attachments/assets/4e4e918a-8985-4d3e-8db8-9235013e174d" />

ingresamos a la opcion de "proteccion contra virus y amenazas"

<img width="1149" height="256" alt="image" src="https://github.com/user-attachments/assets/b2c42043-ef3e-473d-b3b0-efdd7fa20e10" />

despues hacemos un examen rapido 

<img width="552" height="480" alt="image" src="https://github.com/user-attachments/assets/b697e2dd-0fde-40b9-b603-8842006394fd" />

este se encargara de revisar todos los archivos y nos alertara de cualquier rareza

<img width="549" height="198" alt="image" src="https://github.com/user-attachments/assets/0a002e0d-ac24-4df0-9cd3-770693b2dda1" />

en este caso salio bien sin ninguna amenaza detectada

<img width="447" height="373" alt="image" src="https://github.com/user-attachments/assets/390619a4-7bdc-470f-8624-ad85cc6aaf08" />

## 2) ¿Qué es VirtualBox?, ¿Qué es WSL?, ¿Qué es VMWARE?, ¿Qué es QEMU? Y ¿Qué es KVM?. Desarrolle la búsqueda de cada una de las tecnologías presentadas y proceda a explicar sus características, diferencias, ventajas y aplicaciones.

Explicacion general creada por IA 
# Glosario de Tecnologías de Virtualización y Entornos Operativos

> **Nota de autoría:** Este documento fue generado de forma automática por un asistente de Inteligencia Artificial (IA) a petición del usuario.

Este documento ofrece un resumen rápido sobre el funcionamiento y propósito de **VirtualBox**, **WSL**, **VMware**, **QEMU** y **KVM**.

---

### VirtualBox
* **Definición:** Es un software de virtualización de tipo 2 (se ejecuta sobre un sistema operativo principal) desarrollado por Oracle.
* **Propósito:** Permite crear máquinas virtuales (VM) para instalar y usar sistemas operativos completos de forma aislada.
* **Características:** Es gratuito, de código abierto y muy popular entre usuarios domésticos por su interfaz visual intuitiva.

### WSL (Windows Subsystem for Linux)
* **Definición:** Es una característica de Windows que permite ejecutar un entorno de Linux nativo directamente en Windows, sin la carga de una máquina virtual tradicional.
* **Propósito:** Está diseñado para desarrolladores que necesitan herramientas de línea de comandos de Linux dentro de Windows.
* **Características:** Traduce de forma eficiente las llamadas del sistema de Linux para el núcleo de Windows, ofreciendo un gran rendimiento.

### VMware
* **Definición:** Es una familia de productos de virtualización (como VMware Workstation o ESXi) orientados tanto al usuario de escritorio como a entornos corporativos.
* **Propósito:** Crear entornos virtuales de alto rendimiento y estabilidad comercial para servidores y estaciones de trabajo.
* **Características:** Destaca por su optimización avanzada de recursos, gestión de redes complejas y herramientas empresariales.

### QEMU (Quick Emulator)
* **Definición:** Es un emulador y virtualizador de código abierto extremadamente flexible.
* **Propósito:** Capaz de emular arquitecturas de hardware completamente diferentes (por ejemplo, ejecutar código ARM en un ordenador x86).
* **Características:** Funciona mediante emulación pura por software, lo que puede ser lento a menos que se combine con un acelerador por hardware.

### KVM (Kernel-based Virtual Machine)
* **Definición:** Es un módulo que convierte al propio núcleo de Linux en un hipervisor de tipo 1 (con acceso directo al hardware).
* **Propósito:** Gestionar máquinas virtuales en Linux con un rendimiento prácticamente nativo.
* **Características:** Suele combinarse con **QEMU**, donde KVM acelera el procesador/memoria y QEMU se encarga de simular los componentes virtuales de disco, red y periféricos.

## Comparacion

| Tecnología | caracteristica | Diferencias  | Ventajas  | Aplicaciones |
| :--- | :--- | :--- | :--- | :--- |
| **VirtualBox** | es gratuito y de codigo abierto | Gratuito, emula hardware completo por software mediante una interfaz gráfica sencilla. | • Fácil de usar.<br>• Multiplataforma (Windows, macOS, Linux).<br>• Gran comunidad y soporte. | • Estudiantes y aprendizaje.<br>• Probar sistemas operativos de forma rápida.<br>• Entornos de desarrollo aislados simples. |
| **WSL** |un traductor eficiente del sistema linux | No es una máquina virtual completa; comparte el núcleo o corre un núcleo Linux optimizado dentro de Windows. | • Consumo mínimo de recursos.<br>• Rendimiento muy rápido.<br>• Integración directa con el sistema de archivos de Windows. | • Desarrolladores en Windows que necesitan herramientas Linux (Docker, Git, Bash).<br>• Entornos de programación web. |
| **VMware** | tiene una optimizacion avanzada de recursos y maneja redes complejas. | Software comercial de alto rendimiento con gestión avanzada de redes y recursos empresariales. | • Máximo rendimiento gráfico y de CPU.<br>• Muy estable y robusto.<br>• Funciones avanzadas de clonación y snapshots. | • Entornos corporativos y centros de datos.<br>• Administradores de sistemas y redes profesionales.<br>• Pruebas de software a gran escala. |
| **QEMU** |funciona como Emulador pero es algo lento| Puede emular arquitecturas de hardware distintas a la del procesador real (ej. emular ARM en x86). | • Flexibilidad extrema.<br>• Soporta casi cualquier arquitectura.<br>• Es de código abierto y ligero. | • Desarrollo de sistemas embebidos y firmware.<br>• Depuración de kernels.<br>• Ejecución de software antiguo o de otros procesadores. |
| **KVM** | es un acelerador por hardware | Convierte el núcleo de Linux en un hipervisor. Se usa junto con QEMU para el hardware virtual. | • Rendimiento casi nativo (acceso directo al hardware).<br>• Excelente escalabilidad.<br>• Integrado en el ecosistema Linux. | • Servidores en la nube (infraestructura cloud).<br>• Virtualización empresarial en servidores Linux.<br>• Usuarios avanzados de Linux. |

## 3) Explicar y simular las siguientes arquitecturas 

# Laboratorio: Configuración de Switch en Python

**Institución:** Fundación Universitaria Compensar  
**Herramientas:** Python 3, Netmiko, Cable Consola / SSH  

---

## 1. Conexión Inicial y Protocolo
* **Herramienta:** Reemplazo de PuTTY mediante la librería `netmiko` en Python.
* **Protocolo Utilizado:** **UART / RS-232 (Serial)** para la interfaz física de consola a `9600 baudios`. *(Si usas red, indicar SSH mediante puerto TCP 22)*.

---

## 2. Memoria NVRAM y Dirección MAC

### NVRAM (Non-Volatile RAM)
Memoria no volátil del switch donde se almacena el archivo `startup-config`. A diferencia de la RAM, conserva los datos al reiniciar el equipo.
* **Comando ejecutado:** `show startup-config`

### Dirección MAC (Media Access Control)
Dirección física única de 48 bits (6 bytes) grabada en la tarjeta de red (NIC) del switch. Sirve para conmutar tramas a nivel de **Capa 2 (Enlace de Datos)** en el modelo OSI.
* **Comando ejecutado:** `show version` o `show mac address-table`

---

## 3. Configuración de Interfaces VLAN

Se crearon las interfaces virtuales con sus respectivas submáscaras:

| VLAN | Dirección IP | Máscara Decimal | Prefijo |
| :--- | :--- | :--- | :--- |
| **VLAN 10** | `192.168.10.1` | `255.255.255.0` | `/24` |
| **VLAN 20** | `172.16.0.1` | `255.255.0.0` | `/16` |
| **VLAN 30** | `10.0.0.1` | `255.0.0.0` | `/8` |

---

## 4. Comandos Principales de Exploración
* `show running-config`: Muestra la configuración actual en memoria RAM.
* `show ip interface brief`: Muestra el estado operativo de todas las interfaces.
* `copy running-config startup-config`: Guarda los cambios en la NVRAM.


# Laboratorio: Configuración de Router e Instalación de Máquinas Virtuales

**Institución:** Fundación Universitaria Compensar  
**Herramientas:** Python 3, Netmiko, VirtualBox, VMware Workstation, QEMU  

---

## Punto 2: Configuración Básica de Router

### 1. Conexión Inicial y Protocolo
* **Protocolo:** **RS-232 / UART (Serial)** mediante interfaz de consola a 9600 baudios.
* **Explicación:** Se emula la terminal de PuTTY desde Python usando `netmiko`, enviando los caracteres ASCII de la CLI directamente al microprocesador del router a través del puerto serie.

### 2. Inspección de Memoria NVRAM y MAC
* **NVRAM:** Almacena la configuración de arranque (`startup-config`). Comando: `show startup-config`.
* **Dirección MAC:** Identificador de Capa 2 grabado en las interfaces físicas (GigabitEthernet) del router para resolver tramas Ethernet en la red local. Comando: `show interfaces`.

### 3. Configuración de Interfaces VLAN (Router-on-a-Stick)
Para que el router interconecte 2 VLANs a través de un solo cable, se definieron subinterfaces virtuales con la encapsulación IEEE 802.1Q:

| Subinterfaz | VLAN Asociada | Dirección IP (Gateway) | Máscara |
| :--- | :--- | :--- | :--- |
| **GigabitEthernet0/0/0.10** | VLAN 10 | `192.168.10.254` | `255.255.255.0` (`/24`) |
| **GigabitEthernet0/0/0.20** | VLAN 20 | `172.16.255.254` | `255.255.0.0` (`/16`) |

---

## Punto 3: Instalación de Máquina Virtual Ubuntu

Se probó la ejecución de **Ubuntu Server/Desktop** sobre 3 hipervisores distintos:

### 1. Oracle VirtualBox
* **Tipo de Hipervisor:** Tipo 2 (Hosted).
* **Pasos principales:**
  1. Crear nueva VM tipo `Linux` -> `Ubuntu (64-bit)`.
  2. Asignar RAM (mínimo 2048 MB) y 2 CPUs.
  3. Crear disco VDI dinámico (20 GB).
  4. Montar ISO de Ubuntu en la unidad óptica virtual e iniciar la instalación GUI.

### 2. VMware Workstation / Player
* **Tipo de Hipervisor:** Tipo 2 (Hosted, alto rendimiento de I/O).
* **Pasos principales:**
  1. Seleccionar *Create a New Virtual Machine*.
  2. Usar el asistente *Easy Install* apuntando a la ISO de Ubuntu.
  3. Definir espacio en disco virtual (formato `.vmdk`).
  4. Iniciar y completar la configuración de usuario y paquetes.

### 3. QEMU (Quick Emulator)
* **Tipo de Hipervisor:** Emulador/Hipervisor tipo 1/2 (vía KVM en Linux o ejecutable directo en Windows).
* **Comandos de creación e instalación vía terminal:**
  ```bash
  # 1. Crear la imagen de disco virtual en formato qcow2
  qemu-img create -f qcow2 ubuntu_disk.qcow2 20G

  # 2. Iniciar la instalación desde la ISO
  qemu-system-x86_64 -hda ubuntu_disk.qcow2 -cdrom ubuntu-22.04-live-server-amd64.iso -boot d -m 2048 -smp 2


# Laboratorio de Redes y Virtualización

**Institución:** Fundación Universitaria Compensar  
**Lenguaje / Herramientas:** Python 3, Netmiko, Cable Consola (RS-232), VirtualBox, VMware Workstation, QEMU  

---

## Punto 1: Configuración de Switch en Python

### 1. Conexión Inicial y Protocolo
* **Herramienta:** Reemplazo de PuTTY mediante el script de Python con la librería `netmiko`.
* **Protocolo:** Conexión Serial **RS-232 / UART** a 9600 baudios a través del puerto de consola (COM).

### 2. Memoria NVRAM y Dirección MAC
* **NVRAM:** Memoria no volátil donde se aloja el archivo `startup-config`. Mantiene la configuración guardada tras reiniciar el equipo.
* **Dirección MAC:** Dirección física de 48 bits (Capa 2 del modelo OSI) grabada en la tarjeta de red del switch para la conmutación de tramas.

### 3. Código Python Aplicado (`script_switch.py`)

```python
from netmiko import ConnectHandler

device = {
    'device_type': 'cisco_ios_serial',
    'serial_settings': {
        'port': 'COM3',
        'baudrate': 9600
    }
}

def configurar_switch():
    net_connect = ConnectHandler(**device)
    net_connect.enable()
    
    # Consultar NVRAM y MAC
    print(net_connect.send_command("show startup-config")[:200])
    print(net_connect.send_command("show version")[:300])
    
    # Configurar VLANs (Máscaras /24, /16 y /8)
    config_commands = [
        'interface vlan 10', 'ip address 192.168.10.1 255.255.255.0', 'no shutdown',
        'interface vlan 20', 'ip address 172.16.0.1 255.255.0.0', 'no shutdown',
        'interface vlan 30', 'ip address 10.0.0.1 255.0.0.0', 'no shutdown', 'exit'
    ]
    net_connect.send_config_set(config_commands)
    net_connect.send_command("copy running-config startup-config")
    net_connect.disconnect()

if __name__ == '__main__':
    configurar_switch()
  








 


