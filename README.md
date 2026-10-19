# power-ah

按下电源键，喷出满屏的「啊」。

## 玩法

- 短按电源键：喷出一个字，放大淡入再飘散消失
- 长按（约 0.4 秒）：持续喷发，随机位置/大小/角度涌出，松开停止
- 右上角输入框可换成任意字（默认「啊」）

## 使用

直接双击打开 `index.html` 即可，无需安装、无任何依赖。

## 技术

单文件 HTML + CSS + JS；用 Pointer 事件 + 定时器区分短按/长按。
长按效果：
<img width="1902" height="872" alt="image" src="https://github.com/user-attachments/assets/7407b9b3-e316-44b4-8b9b-4c1cc5591002" />
可以多在输入框里输入些文字，长按特别解压
