#### 流程图 

```flow
st=>start: 机器人
op=>operation: 登陆操作
cond=>condition: 登陆成功 Yes or No?
e=>operation: 收消息
cond1=>condition: 是否通过验证 Yes or No?
e3=>end: 处理删除消息
e1=>end: 结束
st->op->cond->e->cond1->e1

cond(yes)->e
cond(no)->op
cond1(yes)->e1
cond1(no)->e3
```
