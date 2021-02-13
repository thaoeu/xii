# XII

XII 输入法即标杆杆输入法，xii 的首码作“标杆杆”.

码表基于 [fcitx-table-flypy](https://github.com/rydesun/fcitx-table-flypy)修改,采用 Dvorak 而非 Qwerty 布局.

## 特性：

1. 保留小鹤音形大多数特性,单字四码,词组前字首码加尾字首码,尽可能降低选词次数,降低重码率.

## ToDo

1. 适配手机端码表,目前已有 Rime 下 Dvorak 的皮肤,但使用 mb2txt 生成的 yaml 码表尚不生效.

2. 增加中文符号适配,由于 Dvorak 布局占用了原本的逗号句号顿号位,故需对空位加以处理.

3. 适当增加英文词组,由于英文单词的特殊性,外加一次键位转换,大多不会和原码表冲,使得添加一些英文词组成为可能.
