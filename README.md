# Java-HW4

1.

public static int maxSum(int array[]) {

public static int sum(int array[]) {
int result = 0;
for (int i = 0; i < array.length; i++)
result += array[i];
return result;
}

public static int max(int array[]) {
int result = array[0];
for (int i = 1; i < array.length; i++)
if (array[i] > result)
result = array[i];
return result;
}
}

2. public static void shift(int array[], int offset) {

public static void swap(int array[], int from, int to) {
int temp = array[from];
array[from] = array[to];
array[to] = temp;
}
}

3.1. public static int mode(int array[]) {

public static int sum(int array[]) {
int result = 0;
for (int i = 0; i < array.length; i++)
result += array[i];
return result;
}
}

3.2 public static int mode100(int array[]) {

public static int sum(int array[]) {
int result = 0;
for (int i = 0; i < array.length; i++)
result += array[i];
return result;
}
}
