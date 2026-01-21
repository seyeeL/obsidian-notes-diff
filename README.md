# Notes Diff

Obsidian 插件，用于对比文件差异，类似 Git diff 的视图。

<img width="2880" height="1704" alt="70821a4cca5d644515d5b321394d01ad" src="https://github.com/user-attachments/assets/769536e8-1d0b-4d85-87ff-342977b9fb8e" />

## 功能

- 双文件对比：左右分屏显示差异，绿色表示新增，红色表示删除
- 多文件对比：同时对比最多 3 个文件
- 字符级高亮：在修改的行内高亮具体改动的字符
- 相似文件查找：自动查找文件名相似的文件

## 使用

### 右键菜单
- 单个文件：设为比较源 / 与比较源对比 / 清除比较源
- 选中两个文件：直接对比

### 命令面板
- 比较两个文件
- 选择文件与当前文件比较
- 查找相似文件名并对比
- 清除比较源

### 对比视图
- 绿色背景：新增内容
- 红色背景：删除内容
- 黄色背景（多文件）：某个文件独有
- 蓝色背景（多文件）：部分文件共有
- 对比视图中可以直接删除文件（有确认提示）

## 安装

1. 手动安装：将 `main.js`、`manifest.json`、`styles.css` 放到 `.obsidian/plugins/notes-diff/` 目录。
2. brat插件安装

## 限制

- 仅支持桌面端
- 对比视图只读

## 示例图

<img width="2870" height="1686" alt="f3c7fcd27a46e34cf373fde24b2c02cc" src="https://github.com/user-attachments/assets/0402ef65-b6b8-47f4-a576-6516c7116a11" />

<img width="500" alt="467833ae6e0a5e72bb34b5c5abe08b95" src="https://github.com/user-attachments/assets/e7397048-4e5b-4ff1-a7d5-11bdabf82183" />




## License

MIT
