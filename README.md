# Star Collection

> Curated collection of interesting & useful open source projects, organized by relevance to my work.
> Focused on: AI workspace, mini-app framework, micro-frontend, developer tools, cross-platform apps.

---

## AI Agent & LLM Infrastructure

| Project | Stars | Description | Why Useful |
|---------|-------|-------------|------------|
| [songquanpeng/one-api](https://github.com/songquanpeng/one-api) | 31K+ | Unified LLM API gateway supporting 100+ providers | BYOK feature — multi-provider routing & key management |
| [BerriAI/litellm](https://github.com/BerriAI/litellm) | 41K+ | Python SDK/Proxy for 100+ LLM APIs with cost tracking | Multi-provider LLM routing & cost management reference |
| [qwibitai/nanoclaw](https://github.com/qwibitai/nanoclaw) | 25K+ | Lightweight OpenClaw alternative with memory & Agents SDK | Architecture reference for agent system with messaging |
| [EverMind-AI/EverMemOS](https://github.com/EverMind-AI/EverMemOS) | 3.3K+ | Memory OS for agents — long-term memory + token saving | Memory system for workspace context persistence |
| [humanlayer/12-factor-agents](https://github.com/humanlayer/12-factor-agents) | 18K+ | Principles for production-grade LLM software | Architectural guidance for agent orchestration |
| [FlowiseAI/Flowise](https://github.com/FlowiseAI/Flowise) | 51K+ | Visual AI agent builder with workflow automation | UI/UX reference for visual agent/workflow builder |
| [dtyq/magic](https://github.com/dtyq/magic) | 4.6K+ | All-in-one AI: Agent + Workflow + IM + collaborative office | Closest competitor — nearly identical product vision |
| [Pythagora-io/gpt-pilot](https://github.com/Pythagora-io/gpt-pilot) | 33K+ | AI developer agent for code generation | Reference for BriefAgent's automation pipeline |
| [nomic-ai/gpt4all](https://github.com/nomic-ai/gpt4all) | 77K+ | Run local LLMs on any device | Offline/local inference for native apps |
| [mlc-ai/web-llm](https://github.com/mlc-ai/web-llm) | 17K+ | In-browser LLM inference via WebGPU | On-device AI without server calls |
| [anthropics/claude-cookbooks](https://github.com/anthropics/claude-cookbooks) | 36K+ | Claude integration patterns and notebooks | Recipes for Claude-based features |
| [QuivrHQ/quivr](https://github.com/QuivrHQ/quivr) | 39K+ | Opinionated RAG framework for GenAI apps | RAG architecture for Memory search & knowledge retrieval |
| [openagents-org/openagents](https://github.com/openagents-org/openagents) | 1.7K+ | AI agent networks for collaboration | Multi-agent collaboration patterns |
| [agent0ai/agent-zero](https://github.com/agent0ai/agent-zero) | 16K+ | Autonomous AI agent framework | Pattern reference for workspace agents |
| [openai/codex](https://github.com/openai/codex) | 68K+ | Terminal-based coding agent | Reference architecture for code generation |
| [ChatGPTNextWeb/NextChat](https://github.com/ChatGPTNextWeb/NextChat) | 87K+ | Cross-platform AI assistant (Next.js + Tauri) | UI/UX patterns for AI chat interface |

## MCP & Integration

| Project | Stars | Description | Why Useful |
|---------|-------|-------------|------------|
| [langchain-ai/langchain-mcp-adapters](https://github.com/langchain-ai/langchain-mcp-adapters) | 3.4K+ | LangChain MCP integration | Bridge MCP servers with LangChain workflows |
| [n8n-io/n8n](https://github.com/n8n-io/n8n) | 181K+ | Visual workflow automation with 400+ integrations | Reference for sync adapters & workflow orchestration |
| [DMontgomery40/deepseek-mcp-server](https://github.com/DMontgomery40/deepseek-mcp-server) | 309 | MCP server for DeepSeek | Template for adding providers to openclaw |
| [ThinkInAIXYZ/deepchat](https://github.com/ThinkInAIXYZ/deepchat) | 5.6K+ | AI assistant with MCP client (Electron) | Desktop MCP client reference for BriefAgent |

## Web Scraping & Data Extraction

| Project | Stars | Description | Why Useful |
|---------|-------|-------------|------------|
| [firecrawl/firecrawl](https://github.com/firecrawl/firecrawl) | 99K+ | Turn websites into LLM-ready markdown | Workspace data ingestion from web sources |
| [browser-use/browser-use](https://github.com/browser-use/browser-use) | 84K+ | Browser automation for AI agents | Agents interacting with web platforms |
| [browserless/browserless](https://github.com/browserless/browserless) | 12K+ | Headless browser in Docker | Server-side scraping infrastructure |
| [naptha/tesseract.js](https://github.com/naptha/tesseract.js) | 37K+ | Pure JS OCR for 100+ languages | Extract text from screenshots/images |

## Frontend Framework & Rendering

| Project | Stars | Description | Why Useful |
|---------|-------|-------------|------------|
| [snabbdom/snabbdom](https://github.com/snabbdom/snabbdom) | 12K+ | Lightweight virtual DOM library | Mini-app rendering engine reference |
| [frejs/fre](https://github.com/frejs/fre) | 3.7K+ | Tiny concurrent UI library with Fiber | Lightweight React alternative for mini-apps |
| [aidenybai/million](https://github.com/aidenybai/million) | 17K+ | Optimizing compiler for React | Performance optimization for morphix-web |
| [preactjs/preact](https://github.com/preactjs/preact) | 38K+ | 3kB React alternative | Lightweight runtime for mini-apps |
| [jorgebucaran/hyperapp](https://github.com/jorgebucaran/hyperapp) | 19K+ | 1kB framework for hypertext apps | Ultra-light framework for sandboxed apps |
| [vuejs/core](https://github.com/vuejs/core) | 53K+ | Vue.js 3 core | Reactivity system reference |
| [onejs/one](https://github.com/onejs/one) | 4.4K+ | React framework for web + native with single Vite plugin | Cross-platform approach reference |

## Micro-Frontend & Module Federation

| Project | Stars | Description | Why Useful |
|---------|-------|-------------|------------|
| [umijs/qiankun](https://github.com/umijs/qiankun) | 16K+ | Micro-frontend framework (single-spa based) | Core reference for app-shell architecture |
| [Tencent/wujie](https://github.com/Tencent/wujie) | 4.9K+ | Micro-frontend via iframe + proxy sandbox | Matches your iframe+Proxy sandbox pattern exactly |
| [jd-opensource/micro-app](https://github.com/jd-opensource/micro-app) | 6.2K+ | Micro-frontend via Web Components | Alternative sandbox approach |
| [Tencent/hel](https://github.com/Tencent/hel) | 1.1K+ | Runtime module federation SDK | Dynamic loading without build-time coupling |
| [single-spa/single-spa](https://github.com/single-spa/single-spa) | 13K+ | Router for micro-frontends | Foundation routing framework |
| [web-infra-dev/garfish](https://github.com/web-infra-dev/garfish) | 2.8K+ | ByteDance micro-frontend framework | Sandbox/lifecycle patterns |
| [smapiot/piral](https://github.com/smapiot/piral) | 1.8K+ | Plugin-based micro-frontend with React | Plugin architecture reference |
| [moonrailgun/mini-star](https://github.com/moonrailgun/mini-star) | 181 | Micro-kernel plugin framework | Plugin extensibility patterns |
| [bytedance/magic-microservices](https://github.com/bytedance/magic-microservices) | 597 | Web Components + micro-frontend DDD | Cross-framework mini-app patterns |
| [cloudflare/workers-web-experiments](https://github.com/nicolo-ribaudo/workers-web-experiments) | 220 | Micro-frontend on Cloudflare Workers | Edge-based micro-frontend patterns |

## Electron & Desktop

| Project | Stars | Description | Why Useful |
|---------|-------|-------------|------------|
| [tw93/Pake](https://github.com/tw93/Pake) | 47K+ | Turn webpages into desktop apps (Rust/Tauri) | Lightweight alternative to Electron |
| [electron-react-boilerplate/electron-react-boilerplate](https://github.com/electron-react-boilerplate/electron-react-boilerplate) | 24K+ | Electron + React + TypeScript boilerplate | Foundation for BriefAgent |
| [rubickCenter/rubick](https://github.com/rubickCenter/rubick) | 9.5K+ | Electron plugin toolbox | Plugin architecture reference |
| [electron/forge](https://github.com/electron/forge) | 7K+ | Complete Electron build/publish tool | Build pipeline for BriefAgent |
| [electron/update-electron-app](https://github.com/electron/update-electron-app) | 819 | Auto-update for Electron | Relevant to hot-update work |
| [responsively-org/responsively-app](https://github.com/nickvdyck/responsively-app) | 24K+ | Responsive web dev browser | Testing across viewports |

## Mobile & React Native

| Project | Stars | Description | Why Useful |
|---------|-------|-------------|------------|
| [tamagui/tamagui](https://github.com/tamagui/tamagui) | 13K+ | Style React + RN with 100% parity | Cross-platform styling for web + native |
| [callstackincubator/cali](https://github.com/nickvdyck/cali) | 977 | AI agent for building RN apps | AI-assisted development for morphix-native |
| [likeSo/expo-wechat](https://github.com/likeSo/expo-wechat) | 60 | WeChat SDK for Expo | WeChat integration (China market) |
| [Hector-Zhuang/expo-native-wechat](https://github.com/nickvdyck/expo-native-wechat) | 115 | Expo module for WeChat APIs | Alternative WeChat SDK |
| [expo/expo-server-sdk-node](https://github.com/expo/expo-server-sdk-node) | 1K+ | Expo push notification server SDK | Push notifications for morphix-native |
| [ctripcorp/CRN](https://github.com/ctripcorp/CRN) | 1.4K+ | Ctrip React Native framework | RN optimization patterns from former employer |
| [xtransferorg/xrn](https://github.com/xtransferorg/xrn) | 134 | RN monorepo solution with unified build/publish | Build/publish patterns for morphix-native |

## Offline-First & Sync

| Project | Stars | Description | Why Useful |
|---------|-------|-------------|------------|
| [toeverything/AFFiNE](https://github.com/toeverything/AFFiNE) | 66K+ | CRDT-based knowledge workspace (Notion alt) | Offline-first workspace with CRDT sync reference |
| [appwrite/appwrite](https://github.com/appwrite/appwrite) | 55K+ | Complete backend: Auth, DB, Storage, Realtime | Alternative/reference to Supabase |
| [supabase/auth](https://github.com/supabase/auth) | 2.3K+ | JWT-based auth for Supabase | Auth patterns for MorphixAI |

## Dev Tools & Build

| Project | Stars | Description | Why Useful |
|---------|-------|-------------|------------|
| [oxc-project/oxc](https://github.com/nickvdyck/oxc) | 20K+ | High-performance JS toolchain in Rust | Future build tool upgrade |
| [rolldown/rolldown](https://github.com/nickvdyck/rolldown) | 13K+ | Fast Rust bundler (Rollup-compatible) | Next-gen bundler for Vite ecosystem |
| [unjs/unplugin](https://github.com/unjs/unplugin) | 3.5K+ | Unified plugin for Vite/Rollup/Webpack/esbuild | Write-once plugins across build tools |
| [microsoft/playwright](https://github.com/microsoft/playwright) | 85K+ | Web testing and automation | E2E tests for morphix-web |
| [mswjs/msw](https://github.com/mswjs/msw) | 17K+ | API mocking with Service Workers | Testing mock APIs |
| [vercel/pkg](https://github.com/nickvdyck/pkg) | 24K+ | Package Node.js into executables | Distribute morphix-env as standalone binary |
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | 21K+ | Interactive CLI prompts | CLI UX for morphixai-code |
| [crxjs/chrome-extension-tools](https://github.com/nickvdyck/chrome-extension-tools) | 4K+ | Chrome extension build with Vite | Workspace browser extension |
| [zh-lx/code-inspector](https://github.com/zh-lx/code-inspector) | 2.9K+ | Click DOM → open IDE at source | DX tool for development |
| [ducktors/turborepo-remote-cache](https://github.com/nickvdyck/turborepo-remote-cache) | 1.4K+ | Open-source Turborepo remote cache | Speed up monorepo builds |
| [github/spec-kit](https://github.com/github/spec-kit) | 83K+ | Spec-driven development toolkit | Aligns with OpenSpec workflow |

## UI Components & Layout

| Project | Stars | Description | Why Useful |
|---------|-------|-------------|------------|
| [excalidraw/excalidraw](https://github.com/excalidraw/excalidraw) | 119K+ | Hand-drawn whiteboard/diagramming | Embeddable whiteboard for workspace |
| [react-grid-layout/react-grid-layout](https://github.com/react-grid-layout/react-grid-layout) | 22K+ | Draggable/resizable grid layout | Workspace dashboard widget layout |
| [microsoft/monaco-editor](https://github.com/microsoft/monaco-editor) | 45K+ | VS Code's code editor for browsers | Code editing in workspace |
| [mermaid-js/mermaid](https://github.com/mermaid-js/mermaid) | 86K+ | Diagrams from text (markdown-like) | Auto-generate diagrams from AI output |
| [slab/quill](https://github.com/slab/quill) | 47K+ | Modern rich text editor | Rich text in workspace notes |
| [statelyai/xstate](https://github.com/statelyai/xstate) | 29K+ | State machines for complex logic | Workflow state management |
| [streamich/react-use](https://github.com/streamich/react-use) | 43K+ | Comprehensive React hooks | Utility hooks for morphix-web |
| [pmndrs/valtio](https://github.com/pmndrs/valtio) | 10K+ | Proxy-based state management | Lightweight state for workspace UI |
| [DouyinFE/semi-design](https://github.com/nickvdyck/semi-design) | 9.7K+ | React design system with Design-to-Code | Design system with AI-friendly components |
| [xtermjs/xterm.js](https://github.com/nickvdyck/xterm.js) | 20K+ | Terminal emulator for the web | In-browser terminal for dev environment |
| [slidevjs/slidev](https://github.com/nickvdyck/slidev) | 45K+ | Developer presentation slides | Markdown-to-slides in workspace |

## Deployment & DevOps

| Project | Stars | Description | Why Useful |
|---------|-------|-------------|------------|
| [NginxProxyManager/nginx-proxy-manager](https://github.com/nickvdyck/nginx-proxy-manager) | 32K+ | Nginx proxy management with UI | Reverse proxy for services |
| [verdaccio/verdaccio](https://github.com/nickvdyck/verdaccio) | 17K+ | Private npm registry | Host @morphixai private packages |
| [fatedier/frp](https://github.com/fatedier/frp) | 105K+ | Fast reverse proxy / NAT traversal | Expose local dev for mobile testing |
| [portainer/portainer](https://github.com/nickvdyck/portainer) | 36K+ | Docker/K8s management UI | Manage Docker deployments |

## Content & Knowledge Management

| Project | Stars | Description | Why Useful |
|---------|-------|-------------|------------|
| [AppFlowy-IO/AppFlowy](https://github.com/AppFlowy-IO/AppFlowy) | 68K+ | Open-source Notion alternative (Flutter) | Competitor reference for workspace |
| [strapi/strapi](https://github.com/strapi/strapi) | 71K+ | Headless CMS (Node.js) | Reference for morphix-cms |
| [nocodb/nocodb](https://github.com/nocodb/nocodb) | 62K+ | Open-source Airtable alternative | Database UI for workspace data views |
| [nocobase/nocobase](https://github.com/nocobase/nocobase) | 21K+ | Extensible no-code/low-code platform | Low-code patterns for app builder |
| [AsyncFuncAI/deepwiki-open](https://github.com/nickvdyck/deepwiki-open) | 15K+ | AI-powered wiki for GitHub repos | Auto-documentation for codebase |
| [ahmedkhaleel2004/gitdiagram](https://github.com/nickvdyck/gitdiagram) | 15K+ | Interactive diagrams for GitHub repos | Architecture visualization |
| [kuaifan/dootask](https://github.com/nickvdyck/dootask) | 5.4K+ | Project/task management with IM | Competitor reference for workspace task features |

## Security & Network

| Project | Stars | Description | Why Useful |
|---------|-------|-------------|------------|
| [apache/casbin](https://github.com/apache/casbin) | 19K+ | Authorization library (ACL/RBAC/ABAC) | Multi-tenant permission control |
| [FiloSottile/mkcert](https://github.com/nickvdyck/mkcert) | 58K+ | Zero-config local HTTPS certificates | Local dev HTTPS |
| [snail007/goproxy](https://github.com/snail007/goproxy) | 16K+ | High-performance HTTP/SOCKS proxy | Proxy infrastructure reference |
| [nadoo/glider](https://github.com/nadoo/glider) | 3.6K+ | Multi-protocol forward proxy | Proxy backend reference |
| [avwo/whistle](https://github.com/nickvdyck/whistle) | 15K+ | HTTP/HTTPS debugging proxy | Network debugging for API dev |

## Other Useful

| Project | Stars | Description | Why Useful |
|---------|-------|-------------|------------|
| [abi/screenshot-to-code](https://github.com/abi/screenshot-to-code) | 72K+ | Convert screenshots to React/Tailwind code | Workspace AI: paste screenshot → get UI |
| [wechaty/wechaty](https://github.com/wechaty/wechaty) | 22K+ | Conversational RPA for WeChat/WhatsApp | WeChat bot for messaging connectors |
| [GoogleChromeLabs/comlink](https://github.com/nickvdyck/comlink) | 12K+ | Makes WebWorkers enjoyable | SW communication in app-shell |
| [QwikDev/partytown](https://github.com/nickvdyck/partytown) | 13K+ | Move third-party scripts to web worker | Performance optimization |
| [HeyPuter/puter](https://github.com/HeyPuter/puter) | 40K+ | Open-source internet computer / cloud OS | Cloud desktop reference for workspace |
| [public-apis/public-apis](https://github.com/public-apis/public-apis) | 417K+ | Curated list of free APIs | API discovery for openclaw integrations |
| [imagemin/imagemin](https://github.com/imagemin/imagemin) | 5.7K+ | Programmatic image minification | Image processing for dev tools |
| [pixelmatch/pixelmatch](https://github.com/nickvdyck/pixelmatch) | 6.7K+ | Pixel-level image comparison | Visual regression testing |
| [vgulerianb/react-exe](https://github.com/nickvdyck/react-exe) | 181 | React component runtime executor | Live preview for AI-generated mini-apps |
