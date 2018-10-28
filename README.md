# python3_utils

### 代码并非原创 只是在原有的基础上修改使其能够在Python3上运行  代码来自网上 如果侵犯著作权请联系18507584705@163.com 删除代码

## 用法

### captcha - 图片验证码

```
from captcha import captcha
# 实例化对象
capt = captcha.Captcha.instance()
# 返回图片名字 验证码文字 验证码图片二进制流
name, text, pic = capt.generate_captcha()

```


### torndb


执行 `sudo apt-get install torndb `后 替换 /usr/local/lib/python3.6/dist-packages/torndb.py文件
> 该文件是通过torndb0.3 版本修改 如果不是这个版本可能不行 请注意


