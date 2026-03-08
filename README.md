```
██╗  ██╗███████╗██╗     ██╗ ██████╗ ███████╗
██║  ██║██╔════╝██║     ██║██╔═══██╗╚══███╔╝
███████║█████╗  ██║     ██║██║   ██║  ███╔╝ 
██╔══██║██╔══╝  ██║     ██║██║   ██║ ███╔╝  
██║  ██║███████╗███████╗██║╚██████╔╝███████╗
╚═╝  ╚═╝╚══════╝╚══════╝╚═╝ ╚═════╝ ╚══════╝
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Private Agent Control Plane  //  BSC
https://helioz.one
$ helioz --status
SYSTEM:         [ONLINE]
NETWORK:        BSC Mainnet
AGENTS:         12 live on public network
MODELS:         30+ across 8 providers
CLI:            v1.3.1 — npm install -g helioz
PRIVACY:        strict — your data never leaves your server
ARCHITECTURE:   control plane + self-hosted runtime
LICENSE:        MIT
$ cat /etc/helioz/about
Helioz is a private AI agent control plane built for the BSC ecosystem.
You create agents on the dashboard. You deploy them on your own server.
Your prompts never touch our infrastructure. Your API keys stay on your machine.
Your data remains under your control. This is not a promise — it is the architecture.
The control plane handles configuration, monitoring, and coordination.
The runtime executes on YOUR infrastructure — VPS, Docker, or local machine.
$ helioz system capabilities
CORE
├── Agent Builder         Design autonomous AI agents with custom prompts and models
├── Skill System          15+ modular skills — web search, chain reader, doc analyzer
├── Privacy Engine        Real-time privacy score, model allowlist, prompt redaction
├── Agent Playground      Sandboxed testing before production deployment
└── Deployment System     Push to VPS, Docker, local, or Helioz Cloud
RUNTIME
├── Agent Monitoring      Live status, error tracking, performance metrics
├── Run History           Full audit trail of every execution
└── Usage Dashboard       Token consumption, model utilization, cost tracking
INFRASTRUCTURE
├── Secret Manager        Per-agent encrypted credential storage
├── Model Router          30+ models — OpenAI, Anthropic, DeepSeek, Meta, Mistral, Google, Cohere, xAI
├── API Access            Full REST API with X-Helioz-Key authentication
└── CLI Terminal          helioz dashboard — full control from any terminal
$ helioz quickstart
  01  npm install -g helioz
  02  helioz auth set-key hlz_live_<your-key>
  03  helioz agent pull <agent-id>
  04  helioz agent start <agent-id>
  05  helioz dashboard
  From zero to running agent in 5 minutes.
$ ls /helioz/repos
helioz                  CLI tool — npm package — npmjs.com/package/helioz
helioz-dashboard        Control plane — web dashboard — helioz.one
helioz-docs             Documentation — guides, API reference, deployment
helioz-agent-runtime    Self-hosted runtime template — Docker, VPS, systemd
$ helioz network --bsc
BSC CAPABILITIES
├── Whale Tracking         Monitor large wallet movements
├── Yield Scanning         Find optimal DeFi farming opportunities
├── Token Launch Detection Detect new launches on PancakeSwap
├── Smart Contract Audit   Automated Solidity security analysis
├── MEV Monitoring         Identify extraction patterns and sandwich attacks
├── Liquidation Alerts     Monitor lending positions before liquidation
├── Bridge Monitoring      Track cross-chain bridge activity
└── Airdrop Hunting        Track eligibility across protocols
$ cat /helioz/links
Dashboard:     https://helioz.one
Install:       https://helioz.one/install
Docs:          https://helioz.one/docs
npm:           https://npmjs.com/package/helioz
CLI:           npm install -g helioz
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  Built for builders. Owned by operators.
  Your agents. Your data. Your infrastructure.
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
