# Exercises
1. You can print a string by simply typing your string surrounded by double-quotation marks. You can also just use the “print” function which doesn’t add a new line:

	scala> "Hello, World!"
	res5: String = Hello, World!

	scala> print("Hello, World!”)
	Hello

1.1 Scala seems to support integers, strings, and doubles in REPL natively. If a integer is too large then it returns an error. You can also “add” two datatypes, the resultant type depends on the types added:

	scala> "A" + "B"
	res10: String = AB

	scala> "A" + 1
	res11: String = A1

	scala> "A" + 1.0
	res12: String = A1.0

	scala> 1 + 1
	res13: Int = 2

	scala> 1 + 1.0
	res14: Double = 2.0

2. Answer:

	scala> (res15 * 9/5) + 32
	res16: Double = 72.5

3. Answer:

	scala> (res19 - 32)*(5/9)
	res20: Double = 0.0

	scala> (res19 - 32.0)*(5.0/9.0)
	res21: Double = 2.361111111111111

4. Answer:

	scala> :load Hello.scala
	Loading Hello.scala...
	Hello Jesse!

5. There is an error here, you must use just “:paste” and not “:paste -raw”

6. Answer:	
	scala> :paste
	// Entering paste mode (ctrl-D to finish)

	println("Hello Jesse!")

	// Exiting paste mode, now interpreting.

	Hello Jesse!