# Jimmy 哥美股动态监控台

作者：jimmy哥

在线网址：[https://jchen8877.github.io/jimmy-stock-monitor-project/](https://jchen8877.github.io/jimmy-stock-monitor-project/)

这是可公开部署的动态网页。股票图表和行情条由 TradingView 官方嵌入组件提供；用户自选代码、模拟账户和成交记录保存在各自浏览器中，不会同步给站点所有者。模拟成交价由用户参照图表手动填写。

## 本地预览

在 Chrome 打开 `index.html` 并保持联网。

## GitHub Pages

站点通过 GitHub Pages 从 `main` 分支根目录发布。后续提交到 `main` 会自动更新网站。

## 数据说明

TradingView 图表是动态的，但交易所数据覆盖和延迟因市场而异，以组件显示为准；页面不读取图表数据来计算建议或模拟成交。免费行情不能保证覆盖全美股市场的完整实时逐笔数据。Hyperliquid、Polymarket 和资讯搜索请求由访客浏览器直接发起，受其接口、跨域策略和限流影响。

资金流与大中小单分析不在公开版提供，避免把分钟线估算误当成真实订单流。所有交易均为本地纸面模拟，不会发送真实订单；非投资建议。
