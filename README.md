VITESSE-LITE

shims.d.ts  
为项目内所有的 vue 文件做模块声明，毕竟 ts 默认只识别 .d.ts、.ts、.tsx 后缀的文件；
（即使补充了 Vue 得模块声明，IDE 还是没法识别 .vue 结尾的文件，这就是为什么引入 vue 文件时必须添加后缀的原因，不添加编译也不会报错）

.vscode
  - extensions.json 会建议用户安装配置的扩展
  - settings 使用工作区的配置
test
  - 测试库 vitest 配置

auto-imports.d.ts
  - 配置全局自动按需导入 无需手动import

components.d.ts
  - 配置组件自动按需导入 无需手动import

.npmrc
  - 管理这个项目的npm安装
  - example registry=https://registry.npm.taobao.org


部署地址-自动化部署
https://app.netlify.com/sites/illustrious-beignet-4c5875/overview
