<style>
  /* 1. 彻底隐藏 Docsify 的顶部导航栏区域 */
  .app-nav { display: none !important; }
  /* 2. 强行把内容区域拉到最顶部，消除上方的 padding */
  .content { padding-top: 0 !important; }
  /* 3. 消除 Docsify 主容器的所有内边距和最大宽度限制 */
  #main { max-width: 100% !important; padding: 0 !important; }
  .markdown-section { padding: 0 !important; max-width: 100% !important; }
  /* 4. 让外层容器完美撑满整个浏览器的可视高度 */
  .iframe-container { width: 100%; height: 100vh;  overflow: hidden; }
</style>

<div class="iframe-container">
  <iframe src="slog.html" width="100%" height="100%" frameborder="0"></iframe>
</div>
