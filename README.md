# Michael Ballester

Software developer interested in building practical systems that are easy to understand, test and operate.

## Focus

- Software engineering: architecture, design patterns, TDD and maintainable delivery
- Backend and web development
- AI-assisted development and automation
- Self-hosted infrastructure and homelab operations

## Background

I have worked mainly with PHP, Symfony, MySQL and API integrations.

I value clear architecture and maintainable delivery, with experience in hexagonal architecture, CQRS, SOLID principles, testing and clean code.

## Interests

- Software engineering, quality and continuous improvement
- Design patterns and test-driven development
- Arch Linux and Proxmox
- Automation, AI tooling and developer productivity

## Technologies

**Software:** PHP, Symfony, Python, JavaScript, TypeScript, MySQL, REST APIs and Git.

**Infrastructure:** Linux, Docker, Proxmox and CI/CD.

## Current direction

I am strengthening my foundations in software engineering while exploring how AI can improve development workflows without replacing engineering judgment.

I am especially interested in applying architecture, testing and automation to real projects, from web applications to self-hosted services.

## Contact

- [LinkedIn](https://www.linkedin.com/in/michaelballester/)
- [mike@mikebgdev.com](mailto:mike@mikebgdev.com)

<!-- repository-quality-20261101 -->
 ## Comprobaciones y publicación

 La verificación del repositorio está en `ci/verify.sh`. Necesita las dependencias de desarrollo descritas arriba; no utiliza datos ni credenciales de producción.

 ```sh
 bash ci/verify.sh
 ```

 El workflow **Quality** comprueba secretos y después ejecuta esas comprobaciones en pushes a la rama principal y en pull requests. El escaneo usa Gitleaks 8.30.1 con descarga verificada por SHA256; examina el historial Git disponible y el directorio actual. No imprime valores de secretos. Para la revisión completa local, usar un clon con historial completo y ejecutar `bash ci/check_secrets.sh`; se puede indicar `GITLEAKS_BIN` con esa versión instalada.

 La existencia del archivo de workflow no acredita que el runner esté disponible ni que la revisión haya pasado. Antes de integrar, comprobar los resultados **Secrets** y **Verify** del mismo SHA. Este workflow no despliega servicios. Conservar el procedimiento de entrega y rollback específico del proyecto.


<!-- license-adopted-20261101 -->
## Licencia

**CC-BY-4.0**, con el alcance indicado en [docs/LICENSING.md](docs/LICENSING.md). El texto completo está en [LICENSE](LICENSE). La concesión cubre las aportaciones propias; los recursos y componentes de terceros conservan sus licencias y atribuciones.
