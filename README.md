# Vue2 + Vite 项目模板

> 基于 Vite 构建的 Vue2 开发模板，集成 ESLint、Prettier、Husky、Lint-Staged 和 Commitizen，适合快速启动企业级前端项目。
## 🛠 技术栈

| 工具                                   | 说明                                |
| -------------------------------------- | ----------------------------------- |
| Vue                                    | `^2.7.16`（支持 Composition API） |
| Vite                                   | `^6.3.5`（极速构建工具）          |
| ESLint                                 | `^8.57.1`（代码检查）             |
| Prettier                               | `^3.5.3`（代码格式化）            |
| Husky & Lint-Staged                    | Git 提交前校验和格式化              |
| Commitizen & cz-conventional-changelog | 规范 Git 提交信息                   |

---

## 📦 安装依赖

```bash
pnpm install
```

---

## 🚀 开发模式

```bash
pnpm dev
```

启动本地开发服务器，默认访问地址：[http://localhost:5173](http://localhost:3000)

---

## 🔨 构建生产环境包

```bash
pnpm build
```

输出目录：`dist/`

---

## 🧪 单元测试

```bash
pnpm test        # 执行一次测试
pnpm test:watch  # 监听文件变化执行测试
```

---

## 📜 代码规范

### ✅ 格式化代码

```bash
pnpm format
```

### 🐞 检查代码问题

```bash
pnpm lint
pnpm lint:fix   # 自动修复部分问题
```

---

## 📥 Git 提交规范

使用 [Conventional Commits](https://www.conventionalcommits.org/) 规范提交信息：

```bash
git cz
```

或使用命令行交互式提交：

```bash
pnpx git-cz
```

---

## 🧰 额外脚本说明

| 脚本名称                                                                 | 描述                         |
| ------------------------------------------------------------------------ | ---------------------------- |
| `prepare`                                                              | 安装 Husky Git Hooks         |
| [lint-staged](file://e:\github\tpl\vue2-vite-demo\node_modules\lint-staged) | 在提交前自动格式化和检查代码 |

---

## 📁 项目结构

```bash
.
├── public/             # 静态资源
├── src/                # 源码目录
│   ├── assets/         # 静态资源
│   ├── components/     # Vue 组件
│   ├── App.vue         # 根组件
│   └── main.js         # 入口文件
├── .eslintrc.cjs       # ESLint 配置
├── .prettierrc.json    # Prettier 配置
├── vite.config.js      # Vite 配置
└── package.json
```

---

## 📝 License

MIT © [aiwa]

---

你可以将上面的内容保存为 `README.md` 文件放在项目根目录中。如果你需要我帮你生成带 logo 或者 GitHub Action 集成的高级 README，也可以告诉我！