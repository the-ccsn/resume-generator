# 静态资源

美名其曰静态资源

其实就是存一些default的东西。比如没有照片，但是模板需要招牌的情况下，总不能放一张贴吧熊，QQ企鹅，知乎刘看山上去，因此需要一张假照片。可能还需要根据不同尺寸做适配。

再比如职业简历之类，得有一套默认凑数的乱数假文（Lorem Ipsum）来凑数。这些资源都是需要预设的。

## 假照片

初步打算用SVG导出png，尽一切减少二进制污染

尺寸初步参考https://zhuanlan.zhihu.com/p/62805181 后续找到更可靠的来源再替换预设

初期先支持一寸就可以了 `295px*413px` / `2.5cm*3.5cm`


## 假信息

不行就faker.py吧