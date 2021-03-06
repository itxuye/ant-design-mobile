---
category: Components
type: Navigation
chinese: 抽屉
english: Drawer
---


从左侧滑出的模态，包含各种导航分类。

### 规则
- 是 Android 推荐的导航方式，常见于该平台应用。


## API ( 适用平台：WEB、React-Native )

| 成员        | 说明           | 类型      | 默认值       |
|------------|----------------|--------------------|--------------|
| children | 主要内容 | any | n/a |
| sidebar | 抽屉里的内容 | any | n/a |
| onOpenChange | open 状态切换时调用 | Function | n/a |
| position | 抽屉所在位置 | String | 'left', enum{'left', 'right', 'top'(`web only`), 'bottom'(`web only`)} |
| sidebarStyle (`web only`)| - | Object | {} |
| contentStyle (`web only`) | - | Object | {} |
| overlayStyle(`web only`) | - | Object | {} |
| dragHandleStyle(`web only`) | - | Object | {} |
| touch(`web only`) | 是否开启触摸手势 | Boolean | true |
| transitions(`web only`) | 是否开启动画 | Boolean | true |
| docked(`web only`) | 是否嵌入到正常文档流里 | Boolean | false |
| dragToggleDistance(`web only`) | 打开关闭抽屉时距 sidebar 的拖动距离 | Number | 30 |
| open(`web only`) | 开关状态 | Boolean | false |
| drawerWidth (`rn only`) | 抽屉宽度 | Number | 300 |
| drawerBackgroundColor (`rn only`) | 指定抽屉背景色 | String | - |
| openDrawer (`rn only`) | 打开drawer | Function | n/a |
| closeDrawer (`rn only`) | 关闭drawer | Function | n/a |
