# gitFundationClase3
Educativo y de Aprendizaje Personal

1. Github Plataform
    ```bash
    Powered By AI = Git hub Copilot
    Collaborations 
    Productivity
    Security = Analizador de Código incluido en la cuenta gratuitas
    Scale = 

2. Creación de Cuenta
    ```bash
    ¿Cómo crear una cuenta Personal?

3. Crear 2factores
    ```bash
    https://docs.github.com/es/authentication/securing-your-account-with-two-factor-authentication-2fa/configuring-two-factor-authentication

4. git y git hub
    ```bash
        Git                                      GitHub
    --------------------------------------   ----------------------------------------------
    Es un software de control de versiones   Es una plataforma basada en la web
    Está instalado en tu máquina local       Está alojado en la nube (online)
    Funciona desde la línea de comandos      Tiene una interfaz gráfica amigable
    Permite guardar versiones de archivos    Permite colaborar con otros usuarios en proyectos
    No necesita conexión a Internet          Requiere Internet para subir o clonar repositorios
    Trabaja en local                         Funciona como repositorio remoto
    Es independiente                         Es un servicio que depende de Git
    Puedes usarlo sin cuenta                 Necesitas una cuenta para usarlo
    No ofrece por sí mismo funciones como:   Ofrece funciones adicionales como:
    Pull requests, Issues, Wikis, CI/CD...   pull requests, gestión de ramas remotas, GitHub Actions, etc.
    Ideal para el manejo personal de versiones   Ideal para colaboración, comunidad y publicación de proyectos

5. Tipos de Cuentas
    ```bash
    Personal, organizacional, empresarial

        Tipo de Cuenta              Descripción
    --------------------------  ------------------------------------------------------------
    Cuenta Personal             Cuenta individual para usuarios desarrolladores.
                            Ideal para proyectos personales o aprendizaje.
                            Permite crear repositorios públicos y privados.

                            Ejemplo: 
                            Usuario: juan-dev
                            Repositorio: juan-dev/portafolio

    Cuenta de Organización      Cuenta para equipos de trabajo o empresas.
                            Permite gestión de múltiples usuarios y repositorios compartidos.
                            Tiene roles (administrador, colaborador) y control de permisos.

                            Ejemplo: 
                            Organización: OpenSourceTeam
                            Repositorio: OpenSourceTeam/app-web

    Cuenta Enterprise           Cuenta avanzada para grandes empresas.
                            Incluye características premium como seguridad avanzada,
                            integración con SAML, auditorías, políticas, soporte técnico,
                            y uso en GitHub Enterprise Server (autohospedado) o Cloud.

                            Ejemplo:
                            Empresa: Microsoft
                            Repositorio: microsoft/vscode

6. Resumen de tabla estilo comparativo
    ```bash
        Tipo de Cuenta     Público objetivo         Características clave                                 Ejemplo
    -----------------  -----------------------  ----------------------------------------------------  --------------------------
    Personal           Usuarios individuales    Repos privados/públicos, proyectos personales         juan-dev/portafolio
    Organización       Equipos de desarrollo    Múltiples colaboradores, roles y permisos             OpenSourceTeam/app-web
    Enterprise         Grandes empresas         Seguridad avanzada, integración empresarial           microsoft/vscode

7. Pasos para invitar colaboradores a un repositorio en GitHub
    ```bash
    🔹 Si usas una cuenta personal:
        Ingresa a GitHub e inicia sesión.

        Dirígete al repositorio al que quieres invitar personas.

        Haz clic en la pestaña "Settings" del repositorio.

        En el menú lateral izquierdo, selecciona "Collaborators".

        Haz clic en el botón "Add people".

        Escribe el nombre de usuario de GitHub de la persona que quieres invitar.

        Selecciona el usuario correcto de la lista y haz clic en "Add".

        El invitado recibirá una notificación por correo y en su cuenta de GitHub para aceptar la invitación.

        🔸 Si usas una cuenta de organización:
        Ve al repositorio dentro de la organización.

        Haz clic en "Settings".

        En la barra lateral, ve a "Manage access".

        Haz clic en "Invite a collaborator" o "Add team".

        Puedes:

        Invitar a usuarios directamente,

        O asignarlos a un equipo con permisos definidos.

        Selecciona los permisos del colaborador: Read, Write, Admin, etc.

        Haz clic en "Send Invitation".

        El colaborador debe aceptar la invitación para tener acceso.

8.  Tabla resumen: pasos para invitar colaboradores
    ```bash
    Paso  | Acción
    ----- | ----------------------------------------------------------------------------
    1     | Inicia sesión en GitHub
    2     | Ve al repositorio deseado
    3     | Haz clic en la pestaña "Settings"
    4     | Ve a "Collaborators" o "Manage access"
    5     | Haz clic en "Add people" o "Invite a collaborator"
    6     | Escribe el nombre de usuario del invitado
    7     | Asigna permisos (Read, Write, Admin)
    8     | Enviar invitación
    9     | El colaborador acepta la invitación

9. Roles en GitHub y sus permisos
    ```bash
        Acción                                          Read     Write    Maintainer   Admin
    ---------------------------------------------  -------  -------  -----------  -------
    Ver el código del repositorio                   ✅        ✅        ✅            ✅
    Clonar el repositorio                           ✅        ✅        ✅            ✅
    Crear issues (reportes de problemas)            ✅        ✅        ✅            ✅
    Comentar en issues y pull requests              ✅        ✅        ✅            ✅
    Crear ramas                                     ❌        ✅        ✅            ✅
    Enviar commits a ramas                          ❌        ✅        ✅            ✅
    Crear y cerrar pull requests                    ❌        ✅        ✅            ✅
    Etiquetar versiones (releases)                  ❌        ✅        ✅            ✅
    Mergear pull requests                           ❌        ✅        ✅            ✅
    Eliminar ramas                                  ❌        ✅        ✅            ✅
    Gestionar proyectos (projects y wikis)          ❌        ✅        ✅            ✅
    Gestionar issues/pull requests de otros         ❌        ❌        ✅            ✅
    Invitar colaboradores                           ❌        ❌        ❌            ✅
    Cambiar visibilidad del repositorio             ❌        ❌        ❌            ✅
    Eliminar el repositorio                         ❌        ❌        ❌            ✅
    Gestionar permisos y configuración avanzada     ❌        ❌        ❌            ✅

10. 🏢 Roles en una organización de GitHub
    ```bash
        Rol                  Puede hacer                                                                      No puede hacer
    -------------------  --------------------------------------------------------------------------------- ------------------------------------------
    Propietario (Owner)  - Acceso total a todos los repositorios                                          Nada restringido
                        - Administrar miembros, equipos, repos, settings, billing                        
                        - Invitar o eliminar miembros                                                    
                        - Cambiar roles                                                                  

    Administrador de Team- Administrar un equipo específico (agregar/quitar miembros)                     - Cambiar settings globales de la organización
                        - Gestionar repositorios asignados al equipo                                     - Ver información financiera o de billing
                        - Asignar roles dentro del equipo                                                

    Miembro              - Acceso solo a los repositorios y equipos asignados                             - No puede modificar configuraciones de la organización
                        - Puede tener roles específicos dentro de cada repo (Read, Write, Admin)         - No puede invitar ni eliminar miembros globales

    Facturación (Billing) - Administrar suscripciones y métodos de pago                                   - No tiene acceso a repositorios ni a la administración de equipos

11. 🧠 Resumen rápido en tabla de acciones y roles
    ```bash
        Acción                                 Owner    Admin Team   Member   Billing
    -------------------------------------       -------  -----------  -------  --------
    Ver todos los repositorios                   ✅        ❌            ❌       ❌
    Administrar la organización                  ✅        ❌            ❌       ❌
    Administrar equipos                          ✅        ✅            ❌       ❌
    Invitar/eliminar miembros                    ✅        ❌            ❌       ❌
    Ver y pagar facturación                      ✅        ❌            ❌       ✅
    Modificar roles de otros miembros            ✅        ❌            ❌       ❌
    Gestionar repositorios                       ✅        ✅*           ✅*      ❌

12. ✅ Cuentas Gratuitas:
    ```bash
    . Personal → GitHub Free

    . Organization → GitHub Free for Organizations

13. 💰 Cuentas de Pago:
    ```bash
        Cuenta   | Plan de Pago          | Descripción breve
    Personal     | 🧩 GitHub Pro        | Más funciones para desarrolladores individuales
    Organization | 👥 GitHub Team       | Colaboración profesional en equipos con más control
    Enterprise   | 🏢 GitHub Enterprise | Soluciones avanzadas para grandes empresas

14. 🧠 Resumen visual:
    ```bash
        Cuenta    | Plan                       | ¿Pago?
    ------------- | -------------------------- | ---------
    Personal      | GitHub Free                | ❌ Gratis
                  | GitHub Pro                 | ✅ Pago

    Organization  | GitHub Free for Orgs       | ❌ Gratis
                  | GitHub Team                | ✅ Pago

    Enterprise    | GitHub Enterprise          | ✅ Pago
