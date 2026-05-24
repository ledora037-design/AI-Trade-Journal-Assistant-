# Personal AI Trade Journal

A highly interactive, beautifully crafted trading companion and behavioral psychology ledger designed for cryptocurrency traders. Log perpetual swap contract positions, track emotional states during trade entry, and leverage client-side AI analysis to surface cognitive edges and performance leaks.

---

## 🌟 Key Features

### 1. Digital Trade Ledger (The Journal)
- **Comprehensive Position Logging**: Easily log perpetual contract details including ticker coin name, order direction (**Long** or **Short**), manual entry & exit price fills, total size (USDT), and active leverage.
- **Cognitive State Tracking**: Choose from primary emotional triggers (**Calm**, **Confident**, **FOMO**, **Greedy**, **Fearful**, **Revenge Trading**) at execution time to document your neural state during the heat of market activity.
- **Interactive Input Presets**: Standard contract guidelines and smart preloads with defensive constraints prevent invalid mathematical inputs.

### 2. Analytical Intelligence Panel (The Dashboard)
- **Equity Curve Growth History**: Displays a clean, interactive line chart showing cumulative profit and loss margins over time using highly customizable curves.
- **Wins vs. Losses Distribution**: Beautifully balanced circular pie distributions highlighting hit-rate frequencies and net performance consistency.
- **Symbol & Contract Performance**: Grouped vertical bars representing net P&L metrics per traded ticker coin, allowing you to quickly spot profitable avenues.
- **Cognitive Edge Assessment**: Visualizes average trade profitability filtered by logged emotional state, uncovering which emotions are generating the bulk of your capital or causing drawdowns.
- **Faceted Search Log & Inline Drawers**: Filter lists by token search queries, specific emotions, or contract sides. Expand row items to read customized trade notes and trigger technical/cognitive audits.

### 3. Progressive Psychological Assessments (Cognitive Insights)
- **Overwhelming Composure Metrics**: Identifies dominant emotions across all historical trades.
- **Edge Strengths & Warning Flags**: Generates logical lists detailing operational execution behavior based on leverage thresholds, side distribution, and psychological indicators.
- **Systematic Directives for Trade Plays**: Actionable, structured rules to follow on your upcoming order books in order to manage capital risk.

### 4. Resilient Security & Storage (System Settings)
- **Client-Side Enclave Pattern**: All logged metrics, execution history, and API credentials are kept safely stored within your browser's secure `localStorage`, ensuring complete privacy.
- **Real-Time AI Integrations**: Support for direct, secure integration with **Anthropic (Claude)** or **OpenAI** API keys.
- **Smart On-Device Failure Fallback**: If keys are absent or direct queries encounter network errors, a smart local rule engine processes metrics on-device, offering instant, resilient feedback.
- **Data Management utilities**: Instantly reset the sandbox memory to represent standard pre-populated demo trades or purge local databases clean with a single action.

---

## 🛠️ Tech Stack & Framework Architecture

- **Runtime & Compilation**: React 18+ with Vite tooling environment. Fully typed with **TypeScript**.
- **User Interface Styling**: Tailored **Tailwind CSS** utility alignments and spacious structural visual hierarchy.
- **Animation Framework**: Fluid layout transition blocks driven by **Motion** (`motion/react`) featuring spring-based easing.
- **Iconography**: Clean, light, high-contrast symbols imported from **Lucide React**.
- **Engine Data Visualization**: Precise SVG charts designed through **Recharts** wrapper engines.

---

## 🚀 Execution & Setup Guide

### Core System Installation
To compile, run, and host the client application locally, proceed with standard Node Package Manager routines:

```bash
# 1. Install required packages
npm install

# 2. Start the rapid local dev server
npm run dev

# 3. Complete lint and compile check
npm run lint
npm run build
```

The development server launches locally, serving the preview application dynamically.

### Key Environment Strategy
Define essential parameters in local `.env.example` configurations. For full API-authenticated pipelines, users can securely configure developer credentials inside the UI's **Settings View** tab, storing variables locally in browser state.
