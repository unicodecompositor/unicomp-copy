# UniComp — Replit Agent Index

> Подробный контекст проекта: **`UNICOMP_CONTEXT.md`** (читай первым!)

## Quick Start
- `npm run dev` → порт 5000
- `npm run build` → dist/
- `npm run test` → Vitest

## Stack
React 18 + TypeScript + Vite + Tailwind + shadcn/ui

## Core Files
| Файл | Описание |
|:-----|:---------|
| `src/lib/unicomp-parser.ts` | Парсер + все типы (1908 строк) |
| `src/lib/render-utils.ts` | 2D Canvas рендер + деформации |
| `src/lib/SuperTransformer.ts` | WebGL шейдеры (taper/shear/rotate) |
| `src/lib/transform-tools.ts` | Жесты → параметры трансформации |
| `src/lib/animation-engine.ts` | Keyframe движок |
| `src/components/UniCompRenderer.tsx` | Главный canvas компонент |
| `src/pages/Index.tsx` | Главная страница (state management) |

## Replit Config
- Port: 5000, Host: 0.0.0.0
- allowedHosts: [".replit.dev", "localhost"]
- Deploy: Static (dist/)
