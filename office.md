# 办公软件 {#office-app}

## PPT

- mac下powerpoint从自动保存文件中恢复文件
  
  以防在某些特殊情况下（如电脑死机）的时候，丢失没有保存的内容，通过菜单栏`powerpoint -> 
  偏好设置 -> 保存 -> 勾选保存自动恢复信息，选择保存间隔（如5分钟)`，这样就会在每隔一定
  时间后对文件进行保存。默认情况下，当我们再打开ppt的时候会弹出恢复文件选项，选择最近时间的文件进行恢
  即可得到修改后的文件。
  
  但是，有时候不会自动弹出恢复选项。这时候我们到自动保存文件夹位置为`/Users/(username)/Library/Containers/com.Microsoft.Powerpoint/Data/Library/Preferences/AutoRecovery`下根据保存时间找到自动保存的文件，把文件扩展名改成`.ppt`恢复对未保存的修改。
  
## EXCEL

- 拖动公式时某个数值保持不变，`A1/B1`在向下拖动时变为`A2/B2`，如何保持`A1`不变

  `$`表示绝对引用，可设置公式参数不变，如`$A$1/B1`中保持`$A$1`不变。

## PS CC

- 无法使用修补工具，因为它不用于索引颜色图像

  需转换为RGB图像，点击菜单栏"图像 -> 模式 -> RGB"

- 去除图片中文字

  使用修补工具，具体步骤:选择修补工具，公共栏中选择修补项为源，关闭透明选项，然后用修补工具框选文字，拖动到无文字区域中与文字周围图案相似的位置，修补工具就会自动匹配目标位置的颜色。