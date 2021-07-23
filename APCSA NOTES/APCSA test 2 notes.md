APCSA test 2 notes

doing *str0 = new String("str")* makes a new obj w/ diff place in mem
if 
    ```
    String str1 = "str"; 
    String str2 = "str"; 
    ```
Then
	```str1 == str2 != str0```
## Boxing notes(same 4 doubles)
```Integer(int value)```(int to Integer)(manual)
```int intValue(Integer Value)```(Integer to int)(manual)
```Integer Value = value```(auto)
```int value = Value```(Integer to int)(auto)
## Math Class notes
 - Math class defined in ```java.lang``` pkg(dont need import)
 - Math class is static/don't need to create object
 - All Math methods return double except for abs(int)
 - Random
	 - ```(int) (Math.random()*a)+b```, range is $b\to(a+b-1)$