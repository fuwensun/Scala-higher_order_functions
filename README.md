# Scala高阶函数


1,一般函数  
def fun（x:Int, y:Int）: Int = {x + y - C}  
函数名：  fun 
参数类型：(x:Int, y:Int） 
返回类型： Int  
函数体：  {x + y} 
        
2,高阶函数  
def FUN (Z :Int) = （x:Int, y:Int）=> x+y-Z 
def FUN (Z :Int):(Int,Int)=>Int  = （x:Int, y:Int）=> x+y-Z 
def FUN (Z :Int):(Int,Int)=>Int  =  {（x:Int, y:Int）=> x+y-Z } 
函数名：  FUN   
参数类型：(Z :Int)  
返回类型：(Int,Int)=>Int  
函数体：  {（x:Int, y:Int）=> x+y-Z }  （重点） 
