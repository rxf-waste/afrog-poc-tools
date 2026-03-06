# afrog-poc-tools

afrog poc yaml生成工具
基于afrog缩写的POC生成工具，可快速编写POC.

afrog-poc参考文档

https://github.com/zan8in/afrog/blob/main/docs/afrog-poc-guide.md

https://github.com/zan8in/afrog/blob/main/docs/requires-gating-guide.md



## PoC info

填写名称、作者、漏洞严重程度、标签、参考链接、描述、指纹等信息。

<img width="689" height="588" alt="image" src="https://github.com/user-attachments/assets/0e0b6b0e-b61d-4817-894c-069b2946f8a9" />


指纹不填写则代表不启用指纹功能，strict无指纹则不扫描，opportunistic无指纹也进行扫描


<img width="685" height="206" alt="image" src="https://github.com/user-attachments/assets/7747239b-a17b-44e7-82b3-daaf1f273e46" />

## 设置变量 set

可根据自己的需求去设置变量

<img width="917" height="673" alt="image" src="https://github.com/user-attachments/assets/d15c3fc9-8f1d-48aa-bae4-b3239ae5d14e" />


## HTTP

贴入请求包，会自动生成到yaml文档中。

<img width="1294" height="674" alt="image" src="https://github.com/user-attachments/assets/bbc4a646-9ff2-46ac-bbfc-f6077d60a291" />


## rules

规则配置

根据填入http请求包，设置所需要捕捉的响应包，以判断漏洞的存在，可添加多个匹配条件。

<img width="645" height="454" alt="image" src="https://github.com/user-attachments/assets/f88a4f54-bf4e-4679-92eb-85e37f9ecf3c" />


## 字典枚举（规则级）


可根据自己的需求，加入字典


<img width="652" height="315" alt="image" src="https://github.com/user-attachments/assets/fd89fc00-77bd-453a-b3fb-e11e8d585726" />


## 参考

页面样式参考
https://github.com/lenawook313-sketch/afrog-poc-generation?tab=readme-ov-file

个人非常喜欢该作者的html布局风格，简洁明了，只是在样式上参考该作者布局，并非原封不动抄袭。
该源码是采用go所编写，有极强的兼容性。


后续有任何bug问题，欢迎反馈。

![c0cea9603fa7188fd7868f8a8cfa757d](https://github.com/user-attachments/assets/381e9a04-f892-4070-9453-0c7ba38dd072)

