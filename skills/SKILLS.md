# Catálogo de Skills y Repos para Claude Code

Investigado por 24 agentes el 2026-10-09. Las estrellas son aproximadas. Los repos con pocas estrellas son nuevos o experimentales, así que revísalos antes de instalarlos.

**Instalar una skill:** clona el repo y copia la carpeta que contiene `SKILL.md` a `~/.claude/skills/` (o a `.claude/skills/` del proyecto). Los plugins se instalan con `/plugin marketplace add owner/repo`.

---

## 1. Skills para sitios web con IA: diseño, animación, 3D y QA (40)

### Diseño y gusto ("taste")
1. [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill): inteligencia de diseño UI/UX profesional (~134k ★)
2. [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill): evita el diseño genérico, el "AI slop" (~94k ★)
3. [pbakaus/impeccable](https://github.com/pbakaus/impeccable): lenguaje de diseño y comandos para mejorar el diseño del agente (~79k ★)
4. [anthropics/skills](https://github.com/anthropics/skills): oficiales: frontend-design, web-artifacts-builder, theme-factory, canvas-design, webapp-testing (~180k ★)
5. [h3nryprod01/design-taste](https://github.com/h3nryprod01/design-taste): fusión de impeccable, taste y emil-kowalski: tipografía, color y motion
6. [JaimeJunr/claude-code-frontend-skills](https://github.com/JaimeJunr/claude-code-frontend-skills): marketplace que agrupa frontend-design, Impeccable, UI UX Pro Max y Taste
7. [Bbasche/design-review](https://github.com/Bbasche/design-review): revisa la UI como un director de diseño
8. [ihlamury/design-skills](https://github.com/ihlamury/design-skills): restricciones de UI tomadas de sistemas de diseño top, para Tailwind
9. [uxKero/anydesign](https://github.com/uxKero/anydesign): convierte una imagen, URL o Figma en un design.md con tokens
10. [Manavarya09/design-extract](https://github.com/Manavarya09/design-extract): extrae el design system de cualquier web a Tailwind v4/shadcn (~4k ★)
11. [MengTo/Skills](https://github.com/MengTo/Skills): skills de diseño web de Meng To

### Animación y motion
12. [AThevon/genjutsu](https://github.com/AThevon/genjutsu): GSAP, Motion, Three.js, micro-interacciones y anti-slop
13. [iart-ai/web-animation-skills](https://github.com/iart-ai/web-animation-skills): GSAP, SVG, Lottie, transiciones de página, 60fps
14. [frankxai/awesome-motion-design-agent-skills](https://github.com/frankxai/awesome-motion-design-agent-skills): lista de skills de motion (GSAP, Motion, Remotion, Rive)
15. [yuzhang-ai/web-animation-skill](https://github.com/yuzhang-ai/web-animation-skill): buenas prácticas de animación web
16. [armel474/gsap-skills](https://github.com/armel474/gsap-skills): GSAP + ScrollTrigger + React
17. [jonathanhatchi/framer-motion-skill](https://github.com/jonathanhatchi/framer-motion-skill): Framer Motion v12+
18. [AIwithhassan/lets-scroll](https://github.com/AIwithhassan/lets-scroll): landings "fly-through" guiadas por el scroll
19. [agiwhitelist/auteur](https://github.com/agiwhitelist/auteur): dirige un sitio como una película: Three.js, GSAP y linter anti-slop

### 3D y visual
20. [viettranx/3dviz-pro-max](https://github.com/viettranx/3dviz-pro-max): escenas Three.js/Blender (223 recetas)
21. [skinnye/3d-web-pack](https://github.com/skinnye/3d-web-pack): pack para webs 3D: Three.js, R3F, WebGPU
22. [camilleroux/genart-skill](https://github.com/camilleroux/genart-skill): arte generativo con p5.js/Three.js
23. [hassancs91/claude-image-generation](https://github.com/hassancs91/claude-image-generation): generación de imágenes en 3 niveles
24. [alonw0/web-asset-generator](https://github.com/alonw0/web-asset-generator): favicons, iconos e imágenes OG

### Componentes y frameworks
25. [21st-dev/magic-mcp](https://github.com/21st-dev/magic-mcp): genera UI desde más de 10k componentes React/Tailwind
26. [Jpisnice/shadcn-ui-mcp-server](https://github.com/Jpisnice/shadcn-ui-mcp-server): MCP con el contexto de shadcn/ui
27. [magicuidesign/magicui](https://github.com/magicuidesign/magicui): componentes animados (~22k ★)
28. [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills): React/Next.js best practices y deploy (Vercel)
29. [incluud/astro-agent-skills](https://github.com/incluud/astro-agent-skills): skills para Astro
30. [spences10/svelte-skills-kit](https://github.com/spences10/svelte-skills-kit): Svelte/SvelteKit
31. [jezweb/claude-skills](https://github.com/jezweb/claude-skills): Tailwind v4, React y Cloudflare

### Marca y diseño en Figma
32. [plugin87/ux-ui-agent-skills](https://github.com/plugin87/ux-ui-agent-skills): tokens DTCG, 52 componentes, WCAG 2.2 (~1.5k ★)
33. [senlindesign/claude2figma](https://github.com/senlindesign/claude2figma): de Claude a Figma con tokens enlazados
34. [rampstackco/claude-skills](https://github.com/rampstackco/claude-skills): 59 skills: marca, diseño, SEO y contenido
35. [vstorm-co/content-skills](https://github.com/vstorm-co/content-skills): copywriting con la voz de la marca

### QA, rendimiento y SEO
36. [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp): automatización de navegador (~38k ★)
37. [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp): trazas de rendimiento y depuración (~53k ★)
38. [danielsogl/lighthouse-mcp-server](https://github.com/danielsogl/lighthouse-mcp-server): auditorías Lighthouse
39. [priyankark/a11y-mcp](https://github.com/priyankark/a11y-mcp): accesibilidad con axe-core
40. [JeffLi1993/seo-audit-skill](https://github.com/JeffLi1993/seo-audit-skill): auditoría SEO técnica

---

## 2. Repos para planificar (32)

### Desarrollo guiado por especificaciones (spec-driven)
1. [github/spec-kit](https://github.com/github/spec-kit): /specify → /plan → /tasks (~140k ★)
2. [Fission-AI/OpenSpec](https://github.com/Fission-AI/OpenSpec): SDD ligero: proponer, especificar, archivar (~71k ★)
3. [bmad-code-org/BMAD-METHOD](https://github.com/bmad-code-org/BMAD-METHOD): agentes PM, arquitecto y dev (~54k ★)
4. [gemini-cli-extensions/conductor](https://github.com/gemini-cli-extensions/conductor): specify, plan, implement
5. [Pimzino/claude-code-spec-workflow](https://github.com/Pimzino/claude-code-spec-workflow): requisitos, diseño y tareas
6. [shotgun-sh/shotgun](https://github.com/shotgun-sh/shotgun): specs y PRD que conocen tu código
7. [wirelessr/kiro-workflow-prompts](https://github.com/wirelessr/kiro-workflow-prompts): el flujo de Kiro para cualquier agente
8. [sudokar/openspec-plus](https://github.com/sudokar/openspec-plus): extensiones para OpenSpec
9. [hllj/sdd-superpowers](https://github.com/hllj/sdd-superpowers): cadena de 9 skills, de brainstorm a review

### Flujos de trabajo
10. [obra/superpowers](https://github.com/obra/superpowers): brainstorm, write-plan, execute-plan (~297k ★)
11. [gsd-build/get-shit-done](https://github.com/gsd-build/get-shit-done): meta-prompting y spec-driven (archivado)
12. [docutray/devflow-skill](https://github.com/docutray/devflow-skill): investigación, épicas y specs
13. [clankercode/ultra-skills](https://github.com/clankercode/ultra-skills): planificación jerárquica de sistemas grandes
14. [EveryInc/claude_commands](https://github.com/EveryInc/claude_commands): comandos para planes de implementación

### Tareas y PRD
15. [eyaltoledano/claude-task-master](https://github.com/eyaltoledano/claude-task-master): de PRD a tareas (~28k ★)
16. [automazeio/ccpm](https://github.com/automazeio/ccpm): de PRD a GitHub Issues, con worktrees en paralelo (~8.4k ★)
17. [cjo4m06/mcp-shrimp-task-manager](https://github.com/cjo4m06/mcp-shrimp-task-manager): tareas con dependencias
18. [lazzyms/prd-erd-skills](https://github.com/lazzyms/prd-erd-skills): de idea a PRD y ERD
19. [Vann4799/ai-prd-generator](https://github.com/Vann4799/ai-prd-generator): PRD a partir de una entrevista
20. [WaitesWireless/claude-product-management-plugin](https://github.com/WaitesWireless/claude-product-management-plugin): PR/FAQ, BRD y PRD

### Arquitectura y ADR
21. [jhagberg/skill-adr-rfcs](https://github.com/jhagberg/skill-adr-rfcs): ADR (MADR 4.0) y RFC
22. [EvolveHQ/docflow](https://github.com/EvolveHQ/docflow): flujo de documentación basado en ADR
23. [architecture-decision-record/architecture-decision-record](https://github.com/architecture-decision-record/architecture-decision-record): plantillas de ADR (~17k ★)

### Memoria y contexto
24. [upstash/context7](https://github.com/upstash/context7): documentación actualizada de librerías (~62k ★)
25. [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem): memoria entre sesiones (~99k ★)
26. [coleam00/context-engineering-intro](https://github.com/coleam00/context-engineering-intro): context engineering y PRP (~14k ★)
27. [vanzan01/cursor-memory-bank](https://github.com/vanzan01/cursor-memory-bank): modos VAN, PLAN, CREATIVE e IMPLEMENT
28. [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers): incluye Sequential Thinking

### Investigación y orquestación
29. [exa-labs/exa-mcp-server](https://github.com/exa-labs/exa-mcp-server): búsqueda web y de código
30. [firecrawl/firecrawl-mcp-server](https://github.com/firecrawl/firecrawl-mcp-server): scraping y crawl
31. [Socialpranker/deepdive](https://github.com/Socialpranker/deepdive): investigación profunda en 12 fases
32. [ruvnet/ruflo](https://github.com/ruvnet/ruflo): enjambres multi-agente; antes se llamaba claude-flow (~74k ★)

---

## 3. Repos para escribir código (37)

### Oficiales
1. [anthropics/claude-code](https://github.com/anthropics/claude-code): Claude Code y sus plugins (~150k ★)
2. [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official): directorio oficial de plugins
3. [anthropics/claude-cookbooks](https://github.com/anthropics/claude-cookbooks): recetas oficiales
4. [anthropics/claude-code-security-review](https://github.com/anthropics/claude-code-security-review): revisión de seguridad de PRs
5. [anthropics/claude-code-action](https://github.com/anthropics/claude-code-action): Claude en GitHub Actions

### Calidad de código (TDD, debugging, review)
6. [obra/superpowers-marketplace](https://github.com/obra/superpowers-marketplace): plugins de superpowers
7. [LerianStudio/ring](https://github.com/LerianStudio/ring): 89 skills: TDD, debugging y review en paralelo
8. [multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills): CLAUDE.md basado en las ideas de Karpathy
9. [affaan-m/ECC](https://github.com/affaan-m/ECC): antes everything-claude-code: skills, memoria y seguridad
10. [trailofbits/skills](https://github.com/trailofbits/skills): auditoría de seguridad
11. [lackeyjb/playwright-skill](https://github.com/lackeyjb/playwright-skill): pruebas e2e

### Agentes y comandos
12. [wshobson/agents](https://github.com/wshobson/agents): 202 agentes, 184 skills (~40k ★)
13. [VoltAgent/awesome-claude-code-subagents](https://github.com/VoltAgent/awesome-claude-code-subagents): más de 100 subagentes
14. [contains-studio/agents](https://github.com/contains-studio/agents): agentes organizados por departamento
15. [SuperClaude-Org/SuperClaude_Framework](https://github.com/SuperClaude-Org/SuperClaude_Framework): comandos y personas (~24k ★)
16. [davila7/claude-code-templates](https://github.com/davila7/claude-code-templates): CLI con plantillas (~32k ★)
17. [disler/claude-code-hooks-mastery](https://github.com/disler/claude-code-hooks-mastery): hooks
18. [UfoMiao/zcf](https://github.com/UfoMiao/zcf): configuración sin esfuerzo

### Reglas y CLAUDE.md
19. [PatrickJS/awesome-cursorrules](https://github.com/PatrickJS/awesome-cursorrules): reglas por lenguaje (~40k ★)
20. [centminmod/my-claude-code-setup](https://github.com/centminmod/my-claude-code-setup): memory bank y hooks
21. [luongnv89/claude-howto](https://github.com/luongnv89/claude-howto): guía visual con plantillas (~42k ★)
22. [CreatmanCEO/claude-code-antiregression-setup](https://github.com/CreatmanCEO/claude-code-antiregression-setup): evita que Claude rompa código que ya funciona

### Backend y servicios
23. [stripe/ai](https://github.com/stripe/ai): skills y MCP oficiales de Stripe
24. [cloudflare/skills](https://github.com/cloudflare/skills): Workers, D1, R2 y Agents SDK
25. [supabase/agent-skills](https://github.com/supabase/agent-skills): Postgres y auth

### Herramientas
26. [ccusage/ccusage](https://github.com/ccusage/ccusage): uso y costo de tokens
27. [musistudio/claude-code-router](https://github.com/musistudio/claude-code-router): enrutar a varios modelos
28. [smtg-ai/claude-squad](https://github.com/smtg-ai/claude-squad): varios agentes en paralelo
29. [winfunc/opcode](https://github.com/winfunc/opcode): GUI para Claude Code
30. [sirmalloc/ccstatusline](https://github.com/sirmalloc/ccstatusline): barra de estado

### Índices para descubrir más
31. [hesreallyhim/awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code): (~55k ★)
32. [VoltAgent/awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills): más de 1000 skills

### Servidores MCP para programar
33. [github/github-mcp-server](https://github.com/github/github-mcp-server): MCP oficial de GitHub (~33k ★)
34. [oraios/serena](https://github.com/oraios/serena): edición semántica de código con LSP (~30k ★)
35. [bytebase/dbhub](https://github.com/bytebase/dbhub): MCP para Postgres, MySQL y SQLite
36. [timescale/pg-aiguide](https://github.com/timescale/pg-aiguide): skills de Postgres
37. [docker/mcp-gateway](https://github.com/docker/mcp-gateway): MCPs en contenedores

---

## Stack recomendado para una "super página"
1. **Planificar:** spec-kit o superpowers (brainstorm y plan) + context7
2. **Diseñar:** ui-ux-pro-max + taste-skill + impeccable + anthropics frontend-design
3. **Animar:** genjutsu / gsap-skills + magic-mcp / magicui
4. **Construir:** vercel agent-skills (Next.js) + shadcn MCP
5. **Verificar:** playwright-mcp + chrome-devtools-mcp + lighthouse + a11y
