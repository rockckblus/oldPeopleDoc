# 普通按钮 2-3 字

`import myButton from "../../myCom/button/buttonSmall.vue";`

```
<my-button textStr="打卡" type="default" :click="closeDaKa" ></my-button>
```

# 配置参数

| prop    | type   | required | default   | description                               |
| ------- | ------ | -------- | --------- | ----------------------------------------- |
| textStr | String | y        | -         | 按钮文字                                  |
| type    | String | y        | `default` | 类型：`default` / `disabled`,打开关闭按钮 |
| click   | Object | n        | -         | 点击事件带入方法                          |
