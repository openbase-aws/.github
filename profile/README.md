# openbase-aws

**openbase-aws** es una iniciativa independiente que adapta y mantiene forks de los servicios de [Supabase](https://github.com/supabase/supabase) para entornos **self-hosted profesionales en AWS**.

Nuestro objetivo es ofrecer una distribución robusta y modular que facilite el despliegue, la operación y la integración de los componentes de Supabase en arquitecturas empresariales en la nube, priorizando:

- Seguridad
- Escalabilidad
- Observabilidad
- Compatibilidad con servicios gestionados de AWS

---

## 🔧 ¿Qué es openbase-aws?

Una colección de forks selectivos de los servicios de Supabase, adaptados para:

- Despliegue optimizado con **AWS ECS, Fargate, EC2 o EKS**
- Integración con **API Gateway, Cognito, RDS, CloudWatch, Lambda**
- Configuración por infraestructura como código (IaC), compatible con **AWS CDK / Terraform**
- Autenticación y control de acceso centralizado
- Automatización de CI/CD para entornos multi-stage (dev/stage/prod)

---

## 📦 Repositorios principales

| Servicio           | Estado       | Descripción                                  |
|--------------------|--------------|----------------------------------------------|
| [`studio`](https://github.com/openbase-aws/studio) | 🔧 En desarrollo | UI adaptada con autenticación AWS IAM / básica |
| [`auth`](https://github.com/openbase-aws/auth)     | 🔧 En desarrollo | Fork de GoTrue adaptado a entornos AWS        |
| Otros servicios    | ☁️ Upstream   | Usamos directamente los servicios oficiales  |

---

## 🚀 Casos de uso

- Empresas que necesitan desplegar **Supabase en su VPC privada**
- Proyectos con requisitos de **compliance (GDPR, HIPAA, ISO)**
- Arquitecturas que exigen observabilidad avanzada (CloudWatch, X-Ray)
- Desarrolladores que desean una base de datos Postgres moderna con herramientas gestionadas en AWS

---

## 📄 Licencia

Todos los forks se mantienen bajo la licencia original [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0). Este proyecto no está afiliado ni respaldado por Supabase Inc.  
Consulta cada repositorio para detalles de licencia y cambios realizados.

---

## 🤝 Contribuciones

Este es un esfuerzo comunitario independiente. Si estás utilizando Supabase en AWS y necesitas personalizaciones o deseas colaborar, ¡eres bienvenido!

---

## 📬 Contacto

¿Tienes dudas o quieres colaborar?

- GitHub Issues y Discussions
- [Próximamente: web oficial y documentación extendida]
