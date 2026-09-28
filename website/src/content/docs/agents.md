---
title: agents
navOrder: 5
---

<div class="prompt-line"><span class="prompt">$</span> <a href="/">cd ..</a></div>

<div class="section-rule" id="agents">
  <span class="dashes">──</span>
  <a href="/docs/agents/" class="label">agents</a>
  <span class="dashes-grow"></span>
</div>

<section class="supported">
  <p class="lockfile-intro">agents are auto-detected by the presence of their config directory in <code>$HOME</code>. target them explicitly with <code>--agent &lt;name&gt;</code>.</p>

  <h3 class="sub-label">skills · 74 supported</h3>
  <ul class="bullet-list">
    <li><span class="bullet">▸</span><strong class="key">adal</strong><span class="val">AdaL · <code>~/.adal/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">aider</strong><span class="val">AiderDesk · <code>~/.aider-desk/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">aider-desk</strong><span class="val">AiderDesk · <code>~/.aider-desk/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">amp</strong><span class="val">Amp · <code>~/.config/agents/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">antigravity</strong><span class="val">Antigravity · <code>~/.gemini/antigravity/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">antigravity-cli</strong><span class="val">Antigravity CLI · <code>~/.gemini/antigravity-cli/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">astrbot</strong><span class="val">AstrBot · <code>~/.astrbot/data/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">augment</strong><span class="val">Augment Code · <code>~/.augment/skills/</code> · alias: <code>amplify</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">autohand-code</strong><span class="val">Autohand Code CLI · <code>~/.autohand/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">bob</strong><span class="val">IBM Bob · <code>~/.bob/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">claude</strong><span class="val">Claude Code · <code>~/.claude/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">cline</strong><span class="val">Cline · <code>~/.cline/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">codearts-agent</strong><span class="val">CodeArts Agent · <code>~/.codeartsdoer/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">codebuddy</strong><span class="val">CodeBuddy · <code>~/.codebuddy/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">codemaker</strong><span class="val">Codemaker · <code>~/.codemaker/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">codestudio</strong><span class="val">Code Studio · <code>~/.codestudio/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">codex</strong><span class="val">Codex · <code>~/.codex/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">command-code</strong><span class="val">Command Code · <code>~/.commandcode/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">continue</strong><span class="val">Continue · <code>~/.continue/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">copilot</strong><span class="val">GitHub Copilot · <code>~/.copilot/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">cortex</strong><span class="val">Cortex Code · <code>~/.snowflake/cortex/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">crush</strong><span class="val">Crush · <code>~/.config/crush/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">cursor</strong><span class="val">Cursor · <code>~/.cursor/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">deepagents</strong><span class="val">Deep Agents · <code>~/.deepagents/agent/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">devin</strong><span class="val">Devin · <code>~/.config/devin/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">dexto</strong><span class="val">Dexto · <code>~/.agents/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">droid</strong><span class="val">Droid (Factory) · <code>~/.factory/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">eve</strong><span class="val">Eve · <code>agent/skills/</code> · explicit only (no auto-detect)</span></li>
    <li><span class="bullet">▸</span><strong class="key">firebender</strong><span class="val">Firebender · <code>~/.firebender/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">forgecode</strong><span class="val">ForgeCode · <code>~/.forge/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">gemini-cli</strong><span class="val">Gemini CLI · <code>~/.gemini/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">goose</strong><span class="val">Goose · <code>~/.config/goose/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">hermes-agent</strong><span class="val">Hermes Agent · <code>~/.hermes/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">iflow-cli</strong><span class="val">iFlow CLI · <code>~/.iflow/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">inference-sh</strong><span class="val">inference.sh · <code>~/.inferencesh/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">jazz</strong><span class="val">Jazz · <code>~/.jazz/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">junie</strong><span class="val">Junie · <code>~/.junie/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">kilo</strong><span class="val">Kilo Code · <code>~/.kilocode/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">kimi-cli</strong><span class="val">Kimi Code CLI · <code>~/.config/agents/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">kiro-cli</strong><span class="val">Kiro CLI · <code>~/.kiro/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">kode</strong><span class="val">Kode · <code>~/.kode/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">lingma</strong><span class="val">Lingma · <code>~/.lingma/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">loaf</strong><span class="val">Loaf · <code>~/.agents/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">mcpjam</strong><span class="val">MCPJam · <code>~/.mcpjam/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">mistral-vibe</strong><span class="val">Mistral Vibe · <code>~/.vibe/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">moxby</strong><span class="val">Moxby · <code>~/.moxby/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">mux</strong><span class="val">Mux · <code>~/.mux/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">neovate</strong><span class="val">Neovate · <code>~/.neovate/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">ona</strong><span class="val">Ona · <code>~/.ona/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">opencode</strong><span class="val">OpenCode · <code>~/.config/opencode/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">openclaw</strong><span class="val">OpenClaw · <code>~/.openclaw/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">openhands</strong><span class="val">OpenHands · <code>~/.openhands/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">omp</strong><span class="val">OMP Agent · <code>~/.omp/agent/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">pi</strong><span class="val">Pi · <code>~/.pi/agent/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">pochi</strong><span class="val">Pochi · <code>~/.pochi/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">promptscript</strong><span class="val">PromptScript · <code>~/.agents/skills/</code> · explicit only (no auto-detect)</span></li>
    <li><span class="bullet">▸</span><strong class="key">qoder</strong><span class="val">Qoder · <code>~/.qoder/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">qoder-cn</strong><span class="val">Qoder CN · <code>~/.qoder-cn/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">qwen-code</strong><span class="val">Qwen Code · <code>~/.qwen/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">raxol</strong><span class="val">Raxol · <code>~/.raxol/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">reasonix</strong><span class="val">Reasonix · <code>~/.reasonix/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">replit</strong><span class="val">Replit · <code>~/.config/agents/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">roo</strong><span class="val">Roo · <code>~/.roo/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">rovodev</strong><span class="val">Rovo Dev · <code>~/.rovodev/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">tabnine-cli</strong><span class="val">Tabnine CLI · <code>~/.tabnine/agent/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">terramind</strong><span class="val">Terramind · <code>~/.terramind/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">tinycloud</strong><span class="val">Tinycloud · <code>~/.tinycloud/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">trae</strong><span class="val">Trae · <code>~/.trae/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">trae-cn</strong><span class="val">Trae CN · <code>~/.trae-cn/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">universal</strong><span class="val">Universal · <code>~/.config/agents/skills/</code> · explicit only (no auto-detect)</span></li>
    <li><span class="bullet">▸</span><strong class="key">warp</strong><span class="val">Warp · <code>~/.agents/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">windsurf</strong><span class="val">Windsurf · <code>~/.codeium/windsurf/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">zed</strong><span class="val">Zed · <code>~/.zed/skills/</code></span></li>
    <li><span class="bullet">▸</span><strong class="key">zencoder</strong><span class="val">Zencoder · <code>~/.zencoder/skills/</code> · alias: <code>zenflow</code></span></li>
  </ul>

  <h3 class="sub-label">references</h3>
  <p class="lockfile-intro"><code>rosie install --ref</code> appends into the project's agent-instructions file. detection order, first match wins:</p>
  <ul class="bullet-list">
    <li><span class="bullet">▸</span><strong class="key">AGENTS.md</strong><span class="val">preferred · the cross-tool standard</span></li>
    <li><span class="bullet">▸</span><strong class="key">CLAUDE.md</strong><span class="val">Claude Code</span></li>
    <li><span class="bullet">▸</span><strong class="key">GEMINI.md</strong><span class="val">Gemini CLI</span></li>
    <li><span class="bullet">▸</span><strong class="key">.github/copilot-instructions.md</strong><span class="val">GitHub Copilot</span></li>
  </ul>
  <p class="lockfile-intro" style="margin-top:.75rem;">if none exist, rosie creates <code>AGENTS.md</code>.</p>
</section>
