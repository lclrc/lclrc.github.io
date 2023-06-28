# 中文说明

## 触发方式
1. 复制内容后出现悬浮球, 点按悬浮球开始
  - 连续复制同一条内容不会弹出球, 如有需求请用控制中心按钮
3. 选择文本后弹出编辑菜单, 选择HammerIt开始
4. 控制中心按钮
  - 全屏OCR并分词(需要申请百度API)
  - 全屏OCR并翻译(需要申请百度API)
  - 对剪贴板最近一条记录进行分词

## 悬浮球(复制文字或图片后出现)
1. 点按进入分词窗口
2. 长按直接进入翻译窗口

## 分词窗口
1. 复制: 点击后复制所选词并关闭窗口
2. 复制+: 点击后复制所选词并自动清空选词, 可以继续下一次复制+. 适合配合剪贴板复制多条片段
3. 选序/原序: 点击切换最终是按原文顺序输出还是选择顺序输出
4. 翻译: 现在支持内置DeepL翻译, 百度api翻译

## 与一些应用集成
- QQ/Tim/微信
- Twitter
- Things3

## DeepL支持的语种
|   |  |
| -- | -- |
| zh | fr |
| en | es |
| ja | pt |
| ko | it |
| de | pl |
| ru | tr |
| ar | id |

## Google支持的语种
|   |  |  |  |
| -- | -- | -- | -- |
| zh | fr | en | es |
| ja | pt | ko | it |
| de | ru | ar | sv |
| ro | th | sk | nl |
| da | el | fi | pl |
| cs | tr | lt | lv |
| uk | bg | id | ms |
| sl | et | vi | fa |
| hi | te | ta | ur |
| tl | km | lo | bn |
| my | no | sr | hr |
| mn | iw |

## 百度Api支持的语种
* 文字翻译: https://fanyi-api.baidu.com/doc/21
* 图片OCR和翻译: https://fanyi-api.baidu.com/doc/26

## TODO
- [ ] 支持更多翻译接口
- [x] OCR
- [ ] ~~Cephei支持后重写设置~~


# For English

## Trigger method
1. Copy the content and the floating Ball appears, tap it to start
  - Continuously copying the same content will not pop up the ball. If necessary, please use the Control Center button.
3. Select the text and the edit menu appears, select HammerIt to start
4. Control center button
  - Full screen OCR and word segmentation(need to apply Baidu API now)
  - Full screen OCR and translation(need to apply Baidu API now)
  - Segment the most recent record on the clipboard

## Floating Ball(Appears after copying text or images)
1. Tap to enter the word splitting window
2. Long press to enter the translation window directly

## Word Separation Window
1. Copy: Click to copy the selected word and close the window
2. Copy+: Click to copy the selected word and clear the selection automatically, you can continue to copy+. Suitable for copying multiple clips with clipboard
3. Select order/original order: click to switch whether the final output is in the original order or the selected order
4. Translation: now support Built-in DeepL translation and Baidu api translation

## Integration with some Apps
- QQ/Tim/Wechat
- Twitter
- Things3

## DeepL supported language
|   |  |
| -- | -- |
| zh | fr |
| en | es |
| ja | pt |
| ko | it |
| de | pl |
| ru | tr |
| ar | id |

## Built-in Google supported language
|   |  |  |  |
| -- | -- | -- | -- |
| zh | fr | en | es |
| ja | pt | ko | it |
| de | ru | ar | sv |
| ro | th | sk | nl |
| da | el | fi | pl |
| cs | tr | lt | lv |
| uk | bg | id | ms |
| sl | et | vi | fa |
| hi | te | ta | ur |
| tl | km | lo | bn |
| my | no | sr | hr |
| mn | iw |

## Baidu Api supported language
* text translate: https://fanyi-api.baidu.com/doc/21
* picture ocr and translate: https://fanyi-api.baidu.com/doc/26

## TODO
- [ ] Support more translation interfaces
- [x] OCR
- [ ] ~~Rewrite settings when `Cephei` supports~~
