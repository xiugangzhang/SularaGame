# SularaGame
## 试玩链接：http://htmlpreview.github.io/?https://github.com/xiugangzhang/SularaGame/blob/master/SularaGame.html

![image](https://github.com/xiugangzhang/SularaGame/blob/master/preview.jpg)
<br>     
<br>     
 1.棋盘设置：使用HTML5的canvas标签绘制整个棋盘<br>
 2.点击事件：当页面被点击时，获取点击的x,y像素点,根据此像素点进行判断，再在合适位置绘制黑红棋子，棋子均是使用canvas绘制的<br>      
 3.保存落子记录：将数据存入一个二维数组，x和y表是落子坐标，1为白棋，2为黑棋，0代表此处无棋子，只有没有棋子的才能落子<br>      
 4.判断输赢：每次落子后以此坐标分别向左右，上下，右下，右上进行判断，设参数count，遇到同色棋子+1，遇到空格或不同色棋子终止，当count=5时，游戏结束<br>
