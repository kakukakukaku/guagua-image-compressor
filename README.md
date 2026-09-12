# 瓜瓜图压

一个完全在浏览器本地运行的图片压缩与尺寸调整工具。图片不会上传到服务器。

## 功能

- 批量导入 JPG、PNG、WebP 图片
- 保留原尺寸，或指定像素与画面比例
- 设置最长边与目标文件大小
- 输出 JPG、WebP、PNG
- 输出文件必须小于原文件；PNG 必要时会自动缩小像素尺寸
- 调整裁剪焦点
- 单张或批量下载处理结果

## 本地开发

```bash
pnpm install
pnpm dev
```

## 构建 GitHub Pages

```bash
pnpm build:pages
```

生成的静态网站位于 `docs` 目录，可直接通过 GitHub Pages 发布。
