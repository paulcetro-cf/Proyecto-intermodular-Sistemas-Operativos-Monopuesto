# Proyecto-intermodular-Sistemas-Operativos-Monopuesto

Este repositorio contiene la documentación y los procedimientos técnicos realizados para el despliegue de un entorno de trabajo basado en **Windows 11 Pro** para una empresa de gestoría empresarial y fiscal.

##  Autor
* **Nombre:** Nicky Cetro Fernández
* **Módulo:** Sistemas operativos monopuestos

---

##  Contexto del Proyecto
El proyecto plantea la infraestructura de software para una **gestoría empresarial y fiscal** enfocada en la optimización de costes y el asesoramiento eficiente. Se ha seleccionado **Windows 11 Pro** por su interfaz intuitiva, soporte nativo para herramientas administrativas y avanzadas funciones de seguridad.

##  Software Implementado
Se ha seleccionado un stack tecnológico específico para el sector fiscal y contable:

| Software | Uso Principal |
| :--- | :--- |
| **Microsoft Office 365** | Herramienta central de gestión (Excel como pilar contable). |
| **Sage / Wolters Kluwer** | Gestión directa de contabilidad, IVA e IRPF. |
| **Adobe Acrobat Reader** | Visualización y firma digital de notificaciones oficiales. |
| **KeePass 2** | Gestión segura y cifrada (AES-256) de contraseñas de sedes electrónicas. |
| **Navegadores** | Microsoft Edge / Google Chrome para acceso a la AEAT y Seguridad Social. |

---

##  Proceso de Instalación y Configuración

### 1. Instalación Limpia
1. **Arranque:** Inicio desde USB booteable con imagen ISO de Windows 11.
2. **Edición:** Selección de Windows 11 Pro y tipo de instalación "Personalizada".
3. **Particionado:** Formateo de la partición principal con sistema de archivos **NTFS**.
4. **Post-instalación:** Configuración de red local y creación de cuenta de usuario local.

### 2. Configuración del Sistema
* **Identificación:** Nombramiento de equipos bajo el esquema `Empleado (Número)` para facilitar el soporte técnico.
* **Localización:** Configuración regional en España, zona horaria de Madrid y teclado QWERTY.
* **Red:** Obtención de IP automática mediante **DHCP** para comunicación con el servidor.

---

##  Seguridad y Cumplimiento de Datos
Dada la sensibilidad de la información fiscal, se han aplicado las siguientes medidas:

* **Cifrado:** Implementación de **BitLocker** para proteger los discos duros ante robos físicos.
* **Gestión de Usuarios:** Estructura basada en el **principio de mínimo privilegio**.
    * El
