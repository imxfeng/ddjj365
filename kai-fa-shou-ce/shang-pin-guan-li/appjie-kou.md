后台新建Api模块，提供app接口功能

1. 获取所有商品分类
   ```
   URL地址：http://m.ddjj365.com/Api/Goods/goodsCategoryList
   请求方式 Get或Post
   参数列表
   ```

| 参数 | 是否必须 | 说明 |
| :--- | :--- | :--- |
| parent\_id | 必须 | 付id |

成功示例

`{`

`"status": "success",   //状态`

`"msg": "获取成功",      //提示`

`"result": [        `

`{`

`"id": "1",       // 分类id`

`"name": "手机 、 数码 、 通信",  // 分类名称`

`"parent_id": "0",    // 父id`

`"parent_id_path": "0_1", // 家族图谱 id`

`"level": "1",    // 分类等级  1,2,3…. 更多级`

`"sort_order": "30",  // 排序 数字越大越靠前`

`"is_show": "1",  // 菜单是否显示  0 关闭  1开启`

`"filter_attr": "0",  // 帅选属性 有哪些`

`"image": ""  // 分类的 图片`

`},`





