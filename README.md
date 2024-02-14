> 项目 fork 自 https://github.com/mckaywrigley/chatbot-ui, 具体文档可以跳过去查看

### 本地调试/线上部署

1. 配置 env
   - 运行命令 `cp .env.local.example .env.local`
   - 更新 `NEXT_PUBLIC_SUPABASE_URL`, `NEXT_PUBLIC_SUPABASE_ANON_KEY`, `SUPABASE_SERVICE_ROLE_KEY` 值为线上 supabase project 的设置，同时注释 `NEXT_PUBLIC_OLLAMA_URL`
   - 运行 `npm run dev` 本地调试， 运行 `npm run build,npm start`
