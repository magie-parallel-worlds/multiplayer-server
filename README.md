
---

### 📁 3. `multiplayer-server`

```markdown
# 🌐 Multiplayer Server / 多人游戏服务器

Real-time, room-based multiplayer backend for Magie’s Parallel Worlds.  
“马吉的平行世界”实时多人游戏后端，基于房间机制。

## 🧩 功能边界 / Scope
- Room creation & management  
  房间创建与管理
- Turn-based synchronization  
  回合同步
- Reconnection & state recovery  
  断线重连与状态恢复
- WebSocket communication via Socket.IO  
  基于 Socket.IO 的通信

## ⚙️ 技术栈 / Tech Stack
- Node.js
- Socket.IO
- Redis (for room state)
- TypeScript

## 🚀 本地开发 / Development
```bash
git clone https://github.com/magie-parallel-worlds/multiplayer-server.git
cd multiplayer-server
npm install
npm run dev
# Server runs on http://localhost:4000
