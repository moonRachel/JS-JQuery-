
首先：可以通过console.log()查看获取到的元素的不同之处
    
再有：JS获取到的是DOM元素，而JQuery返回的是JQuery对象，他是一个类数组对象属性0，1，2...中存着查到的DOM对象，它有一个length属性，表示查到的DOM对象总
数。jQuery对象执行一些方法时，会迭代在每一个DOM对象上执行该方法。
