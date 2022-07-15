# vueProj
Vue学习笔记

事件触发指令：
@click 点击事件
@keyUp 键盘按键抬起
@keyDown 键盘按键按下

event.key或event.keyCode ↓：
keycode 是键盘按键的编码 如13代表的是回车
console.log(e.keyCode);
key 是按键的名字 如回车是Enter
console.log(e.key);

Vue常用按键名称:
1，回车：enter
2，空格：space
3，删除：delete
4，退出：esc
5，换行：tab
6，上下左右：left right up down           
使用按键名称时，如果按键名由多个单词拼成，需要在单词中间加-，首字母小写。如按键名：CapsLock，需要写成@keyUp.caps-lock
 系统修饰键用法特殊（ctrl，alt,shift,win)：
如果配合keyup 需要同时按下任意其他键，然后松开其他键，可以正常触发
修饰符可以连写，如 keyup.ctrl.y 指定必须同时按ctrl+y后松开y才能触发事件

代码块中使用debugger  相当于断点。