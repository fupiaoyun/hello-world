# hello-world
My first repository

# 这是第一级标题`<h1>`
## 这是第二级标题`<h2>`

fun main(args: Array<String>) {
   println("Hello World!")

   println("sum = ${sum(34, 67)}")
   println("sum = ${sum(34, 67)}")
   println("sum = ${sum(34, 6, 57, 34)}")

   printSum(237, 57)
   printSum(234, 567, 8)
   vars(1, 4, 6, 78, 0, 6, 9, 8)


   val sumLambda: (Int, Int) -> Int = { x, y -> x + y }
   println("sumLambda = ${sumLambda(3, 6)}")


//    if (args.size < 2) {
//        println("Two integers expected")
//        return
//    }
   testFor()


   val a: Int = 1000
   println(a === a)//true 值相等，对象地址相等

   //经过了装箱，创建了两个不同的对象
   val boxedA: Int? = a
   val anotherBoxedA: Int? = a

   //虽然经过了装箱，但是值是相等的，都是10000
   println(boxedA === anotherBoxedA) //  false，值相等，对象地址不一样
   println(boxedA == anotherBoxedA) // true，值相等
}
