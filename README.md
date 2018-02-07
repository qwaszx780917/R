# R
#簡單小筆記 TEST

#使用範例資料
data(anscombe)
#使用資料中x1,y1變數畫出點散布圖
plot(y1 ~ x1, data = anscombe)
#建立回歸模型並assign到lmfit變數中
lmfit <- lm(y1~x1, data=anscombe) 
#在點散佈圖上加上迴歸線
abline(lmfit, col="red")
