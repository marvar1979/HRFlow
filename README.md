# HRFlow — Human Resources Management

HRFlow es una aplicación web profesional de gestión de Recursos Humanos construida con HTML5, CSS3, JavaScript y JSON.

## Módulos incluidos
- Dashboard ejecutivo
- Empleados / expediente laboral
- Departamentos
- Organigrama
- Asistencia
- Vacaciones y licencias
- Contratos
- Evaluaciones de desempeño
- Onboarding
- Documentos y vencimientos
- Comunicados internos
- Reportes
- Auditoría local
- Configuración
- Importación / exportación de backup JSON
- PWA / cache offline bajo servidor HTTP
- Roles demostrativos

## Credenciales demo
- HR Admin: `admin@hrflow.local` / `Admin123!`
- HR Manager: `hr@hrflow.local` / `Hr123!`
- Manager: `manager@hrflow.local` / `Manager123!`
- Recruiter: `recruiter@hrflow.local` / `Recruit123!`
- Payroll: `payroll@hrflow.local` / `Payroll123!`
- Employee: `employee@hrflow.local` / `Employee123!`

## Ejecución
Se recomienda VS Code + Live Server. También puede abrirse directamente; en ese caso se usa `js/data-seed.js` como respaldo cuando el navegador bloquea `fetch()` de JSON.

## Importante para uso empresarial real
Esta edición es un front-end funcional y robusto de demostración. Los cambios se almacenan en `localStorage` del navegador y las credenciales demo están en los datos estáticos. Para manejar información real de empleados en una empresa debe conectarse a un backend seguro con base de datos centralizada, autenticación robusta, autorización en servidor, cifrado, gestión de archivos y auditoría centralizada.
