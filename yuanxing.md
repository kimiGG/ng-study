#6面向对象的程序设计
##6.1理解对象
###6.1.1属性类型
###6.1.2定义多个属性
###6.1.2读取属性的特性
##6.2创建对象
###6.2.1工厂模式
###6.2.2构造函数模式
···
function Person(name,age,job){
        this.name = name;
        this.age = age;
        this.job = job;
        this.sayName = sayName;
    }
    function sayName(){
        alert(this.name);
    }
    var person1 =new Person("Nicholas",29,"Engineer");
    person1.sayName();
    var person2 = new Person("linlin",20,"Doctor");
    ···
###6.2.3原型模式
###6.2.4组合使用构造函数模式和原型模式
###6.2.5动态原型模式
###6.2.6寄生构造函数模式
###6.2.7稳妥构造函数模式
##6.3继承
###6.3.1原型链
###6.3.2借用构造函数
###6.3.3组合继承
###6.3.4原型式继承
###6.3.5寄生式继承
###6.3.6寄生组合式继承
##6.4小结
