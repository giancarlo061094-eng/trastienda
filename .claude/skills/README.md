# Skills de diseño

Skills de Claude Code instaladas desde GitHub. Se cargan automáticamente al abrir
este repo con Claude Code (también se pueden invocar con `/<nombre>`).

| Skill | Para qué sirve | Origen | Licencia |
|---|---|---|---|
| `ui-ux-pro-max` | Base de datos buscable de estilos, paletas, tipografías, guías UX y stacks; genera un design system completo (`--design-system`) | [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | MIT |
| `design-system` | Arquitectura de tokens (primitivo → semántico → componente), variables CSS y specs de componentes | [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | MIT |
| `frontend-design` | Dirección estética distintiva para UI, evitando el look genérico de IA | [anthropics/skills](https://github.com/anthropics/skills) | Apache-2.0 |
| `theme-factory` | 10 temas (paleta + tipografía) aplicables a cualquier artefacto | [anthropics/skills](https://github.com/anthropics/skills) | Apache-2.0 |
| `canvas-design` | Pósters y piezas visuales en PNG/PDF con filosofía de diseño | [anthropics/skills](https://github.com/anthropics/skills) | Apache-2.0 |
| `algorithmic-art` | Arte generativo con p5.js | [anthropics/skills](https://github.com/anthropics/skills) | Apache-2.0 |
| `web-artifacts-builder` | Artefactos HTML complejos con React + Tailwind + shadcn/ui | [anthropics/skills](https://github.com/anthropics/skills) | Apache-2.0 |
| `interface-design` | Diseño de dashboards, paneles y apps con memoria de decisiones de diseño | [Dammyjay93/interface-design](https://github.com/Dammyjay93/interface-design) | MIT |
| `baseline-ui` | Reglas base para evitar los errores típicos de UI generada por IA | [ibelick/ui-skills](https://github.com/ibelick/ui-skills) | MIT |
| `improve-ui` | Auditoría y mejora de una UI existente | [ibelick/ui-skills](https://github.com/ibelick/ui-skills) | MIT |
| `fixing-accessibility` | Corrige problemas de accesibilidad | [ibelick/ui-skills](https://github.com/ibelick/ui-skills) | MIT |
| `fixing-motion-performance` | Corrige animaciones lentas o con jank | [ibelick/ui-skills](https://github.com/ibelick/ui-skills) | MIT |
| `fixing-metadata` | Metadatos, SEO y Open Graph | [ibelick/ui-skills](https://github.com/ibelick/ui-skills) | MIT |
| `create-design-md` | Genera un `DESIGN.md` con el sistema visual del proyecto | [ibelick/ui-skills](https://github.com/ibelick/ui-skills) | MIT |
| `web-design-guidelines` | Revisa el código contra las Web Interface Guidelines de Vercel | [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills) | MIT |

Ajuste local: en `ui-ux-pro-max/SKILL.md` las rutas `${CLAUDE_PLUGIN_ROOT}/.claude/skills/...`
se cambiaron a `.claude/skills/...` para que el script funcione instalado en el proyecto
(ejecutar desde la raíz del repo). Requiere Python 3 sin dependencias externas.
