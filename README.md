# mooc-work-answer

[![stars](https://img.shields.io/github/stars/11273/mooc-work-answer)](https://github.com/11273/mooc-work-answer)
[![forks](https://img.shields.io/github/forks/11273/mooc-work-answer)](https://github.com/11273/mooc-work-answer)
[![issues](https://img.shields.io/github/issues/11273/mooc-work-answer?style=plastic)](https://github.com/11273/mooc-work-answer/issues)

+ __智慧执教 【考试+测验+作业+刷课】__

+ __仅适用于: <https://mooc.icve.com.cn/>__

+ __详细刷课技术参考__ [技术篇](https://www.52pojie.cn/thread-1338063-1-1.html)

 ---

## 实现功能

| 功能 | 介绍                                    | 完成 |
| ---- | --------------------------------------- | ---- |
| 刷课 | 基本没有什么大问题                      | ✅    |
| 测验 | 可实现100分，部分需要到职教网站手动提交 | ✅⛔   |
| 作业 | 可实现100分，部分需要到职教网站手动提交 | ✅⛔   |
| 考试 | 可实现100分，部分需要到职教网站手动提交 | ✅⛔   |

## 运行环境

+ python3
+ 运行所需 pip 包请自行切换到本项目根目录使用以下命令进行安装

  ```pip
   pip install -r requriements.txt
  ```

1. 需要两个账号
   + 一个是你需要刷课的账号，一般你自己都有，
   + 另一个需要你注册一个小号(<https://www.icve.com.cn/portal/register/register.html>) 随便注册一个，然后运行
2. 目前只是初次提交，已实现自动刷课以及答题考试100分，详细教程后面会出

## 使用方法

1. 填入 __大号 小号__ 账号密码
2. 里面配置暂时无法自定义，熟悉 `python` 可自行修改，有时间再更新，目前默认 __刷课+测验+考试+测验__
3. 运行 `StartWork.py`

## 部分问题
>
> 1. __运行全部成功，但部分作业考试测验显示未做 ？__
>
>> 由于部分作业数量显示不正常，导致无法完全正确提交，需要前往官网，手动点进去提交，但是答题答案已经选上去了，注意：_官网提交请注意时长停留久一点，不然提交完一个作业就几秒就做完了_，如需强制提交请将最下面代码的 `if my_count == daan_count:` 改为 `if True:`

## BUG 提交

+ 请详细提供 __错误信息__ 以及错误出现的 __代码行__
+ [![Email](http://rescdn.qqmail.com/zh_CN/htmledition/images/function/qm_open/ico_mailme_11.png "QQ Email")](http://mail.qq.com/cgi-bin/qm_share?t=qm_mailme&email=KBkbHhsQEBgZHxpoWVkGS0dF)

## 免责声明

⚠️本项目仅限于学习交流使用，项目中使用的代码及功能如有侵权或违规请联系作者删除

⚠️本项目接口数据均来自于mooc，请勿用于其它商业目的

⚠️如使用本项目代码造成侵权与作者无关
