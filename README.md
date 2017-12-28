# npm-command
记录在工作中遇到的npm的问题

**1. chrome的右上角总是显示'Disconnected from browserSync'的问题**

**问题描述：** im-h5的项目在本地跑起来以后，在chrome中刚开始是显示正常的，但没过多久，就显示'Disconnected from browserSync'。但是在webstorm的命令行窗口中，并没有显示任何异常。

**解决方法：** 
`
npm rm browser-sync && npm install browser-sync@latest
`
