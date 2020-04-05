# 8700K-AsusZ370I-UHD630 for macOS Mojave
## 硬件配置
| 硬件 | 型号 | 价格 | 入手 |
| --- | --- | --- | --- |
| CPU | i7 8700K | ￥2153 | 天猫 |
| 主板 | Asus ROG Strix Z370-i | ￥1649 | 京东 |
| 内存 | 影驰 8GB DDR4 3000MHz | ￥484 | 天猫 |
| 固态 | Crucial BX300 240GB<br>Samsung PM981 256GB | ￥324<br>￥543 | 京东<br>天猫 |
| 显示器 | AOC LV273HUPX 27英寸4K | ￥1949 | 京东 |
| 电源 | 全汉 MS450 SF电源 | ￥369 | 京东 |
| 散热 | 利民APX100RH<br>暴力熊散热硅脂 | ￥297<br>￥39.8 | 京东<br>天猫 |
| 机箱 | 屌丝伯 U1 Plus | ￥344 | 京东 |
| 线材 | 飞利浦 DP线1.2版 4K高清线 | ￥52 | 京东 |

## Install Info
* HighSierra无法安装在PM981上，看大家都说无法正常在10.13上工作，理论上10.14也该也还是不可以，我是安装在BX300上的
* 机型设置为iMac18.1, Macmini8,1都可以
* UHD630在10.14.1原生驱动，不需要添加任何驱动，也不需要在Clover配置，睡眠DP音频都没问题
* 声卡驱动使用[AppleALC](https://github.com/vit9696/AppleALC)+[Lilu](https://github.com/vit9696/Lilu)，Clover注入ID 5



## 2019.04.21

- Update clover to v4901

- 更换机型为Mac mini8