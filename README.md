# com.javarush.task.task09.task0914
Группа перехвата исключений

1. Есть три исключения последовательно унаследованные от Exception:
2. class Exception1 extends Exception
3. class Exception2 extends Exception1
4. class Exception3 extends Exception2
5. Есть метод, который описан так:
public static void method1() throws Exception1, Exception2, Exception3
6. Напиши catch, который перехватит все три Exception1, Exception2 и Exception3
