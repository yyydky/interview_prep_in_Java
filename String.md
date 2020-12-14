1. String vs. StringBuffer vs. StringBuilder

- String: immutable
- StringBuilder: single thread, unsynchronized
- StringBuffer: multiple threads

2. String str = "i"; vs. String str = new String("i");
- https://medium.com/edureka/java-string-pool-5b5b3b327bdf
- string constant pool
- stack

3. reverse string
StringBuilder (or StringBuffer) sb = new StringBuilder();
sb.append("abcdefg");
System.out.println(sb.reverse());

4. cheatsheet
- https://docs.oracle.com/javase/7/docs/api/java/lang/String.html
- indexOf
- charAt
- replace
- trim
- split
- getBytes
- length
- toLowerCase
- toUpperCase
- substring
- equals


