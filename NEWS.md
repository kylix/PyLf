# Release Notes
This file records the **main** changes in *PyLf* library.

## v0.5.2 (2017-12-30)
* **将0作为*word_spacing*的缺省值**
* **修复当生成图片数超过*worker*时文字出现大范围重叠的漏洞**

## v0.5.1 (2017-12-14)
* fix #2

## v0.5.0 (2017-12-14)
* **改进算法使得参数*text*可为*iterable***

## v0.4.0 (2017-12-5)
* Add *ValueError* raised by *pylf.handwrite()* to prevent dead loop in some corner cases
* Improve docstring
* **将黑色作为*template*的缺省颜色**
* **字体宽度从由*font_size*决定改为由每个字符自己的信息决定**
* **将(lambda c: False)作为*template*的缺省*is_half_char***
* **将是否在常见非开头字符集中作为*template*的缺省*is_end_char***