# Aetheria: The Cosmic Code Architect

**Transforming Git Repositories into Interactive Constellations**

Aetheria is a premium, high-fidelity visualization platform that reimagines software development as a journey through the stars. By mapping GitHub commit histories into a dynamic, interactive 2D constellation, Aetheria provides developers and project managers with a stunning "big picture" view of their project's evolution, technical debt, and architectural trajectory.

![Aetheria Preview](https://images.unsplash.com/photo-1462331940025-496dfbfc7564?auto=format&fit=crop&q=80&w=2022&ixlib=rb-4.0.3)

---

## ✨ Core Features & Functionalities

### 1. **Cosmic Constellation Mapping**
- **Visualization**: Every commit is rendered as a star in a vast nebula. The project history forms a connected constellation, allowing you to trace the "DNA" of your codebase.
- **Categorization**: 
  - 🔵 **Features**: Sky-blue nodes representing new capabilities.
  - 🔴 **Bug Fixes**: Pulsing red nodes highlighting stabilization efforts.
  - 🟡 **Maintenance**: Golden nodes for refactoring and architectural updates.
  - 🟢 **Documentation**: Emerald nodes for knowledge base enhancements.

### 2. **The Cosmic Narrator (AI Temporal Analysis)**
- **Functionality**: When a commit is selected, an AI-driven "HUD" (Heads-Up Display) initializes.
- **Deep Insight**: Instead of just showing raw diffs, the Narrator generates a cinematic story explaining the **impact** of the change on the project's lifecycle and system entropy.

### 3. **Stellar Pulse (Risk & Debt Detection)**
- **Functionality**: Toggle the "Stellar Pulse" to scan the constellation for technical debt.
- **Risk Analysis**: Identifies "code smells" such as hacks, workarounds, leaking logs, and incomplete implementation.
- **Auto-Fix Recommendations**: Provides immediate architectural suggestions to resolve detected risks, helping maintain code quality.

### 4. **Recommended Decision Path**
- **Navigation**: Selecting any historical point dynamically calculates and highlights a pulsing teal "Recommended Path" to the latest deployment.
- **Purpose**: Helps engineers understand the direct lineage of the current production state from any point in the past.

### 5. **Supernova (Automated Release Manifest)**
- **Functionality**: Trigger a "Supernova" event to synthesize the entire project history into a professional markdown report.
- **Cinematic Effect**: Features a full-screen cinematic explosion before presenting a categorized summary of Features, Bug Fixes, and Growth.
- **Export**: Instantly download a `stellar_release_notes.md` file ready for documentation or distribution.

### 6. **Deep Space Filter**
- **Functionality**: A granular slider that allows you to "cut through the noise."
- **Focus**: Higher levels filter out minor commits (typos, small fixes), isolating only the major "stars" or architectural shifts that define the project.

### 7. **3D Cinematic Entry Portal**
- **UX**: A high-performance 3D interactive login system featuring perspective card-flip transitions (`preserve-3d`) and an immersive atmospheric background.

---

## 🛠 Tech Stack

- **Frontend**: React 18 + Vite (Optimized with manual chunking)
- **3D Graphics**: Three.js + @react-three/fiber (Stabilized v8/v9)
- **Styling**: Tailwind CSS with Advanced Glassmorphism Utilities
- **Icons**: Lucide React
- **Integration**: GitHub REST API (v3) with PAT support for rate-limit bypassing.

---

## 🚀 Getting Started

1. **Clone & Install**:
   ```bash
   git clone <repo-url>
   cd dsatm-3
   npm install
   ```

2. **Launch Dev Server**:
   ```bash
   npm run dev
   ```

3. **Access**:
   Open [http://localhost:5173](http://localhost:5173) in your browser.

4. **Usage**:
   - Log in via the 3D Portal.
   - Enter a GitHub repository URL (e.g., `facebook/react`).
   - Click **Commence Scanning** to generate your constellation.

---

## 🪐 Philosophy
Aetheria is built on the belief that code is more than just text—it's a living, breathing map of human creativity and technical evolution. By visualizing this evolution through the lens of cosmic discovery, we empower teams to navigate complex architectures with absolute clarity.
