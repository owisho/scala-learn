# scala-learn

### scala基础知识
类:   
  构造函数中参数如果用var修饰表示公开且可修改；如果使用val修饰表示公开但是不可修改；无修饰符表示私有不可被直接访问；
高阶函数:   
  使用其他函数作为参数、或返回一个函数作为结果的函数   
函数嵌套:   
     
柯里化:   
  函数有多个参数列表；只提供一个参数的时候会使用当前剩余参数生成一个新的函数   
样例类:   
  样例类(case class)默认有一个apply方法来负责对象创建，不使用关键字new     
  样例类的构造函数参数是公开的val     
  使用sealed 修饰符描述的抽象类，所有子类必须和它的定义位于相同的文件内     
模式匹配:   
  match {    
		case     
	}     
  对应于 case class等    
单例对象:    
  使用object 定义的对象     
  伴生对象、伴生类 与class 同名的object；object 主要作用放置与实例无关的方法和属性；伴生类和伴生对象必须在相同的文件内     
