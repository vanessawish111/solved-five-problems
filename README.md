Download Link: https://assignmentchef.com/product/solved-five-problems
<br>
Find ten errors (there are more than ten) in the attached file (Find ten erros.java). The errors are both syntactic (compiler errors) and logical (bugs). For each error, identify theline and briefly explain how to x it.

Write the output of the following method called with the parametersq(nums,0,nums.length-1), where nums is an array initialized as follows:

int[] nums = {5, 7, 3, 1, 4, 7} ;

Include all output from entrance to the method to nal exit, including the output of allrecursive calls.

public static void q(int[] nums, int p, int r) {if (p &lt; r) {int x = nums[p];int i = p – 1;int j = r + 1;while (i &lt; j) {do {j–;} while (nums[j] &gt; x);do {i++;} while (nums[i] &lt; x);if (i &lt; j) {int tmp = nums[i];nums[i] = nums[j];nums[j] = tmp;}}for (int n = p; n &lt;= r; n++) {System.out.print(nums[n] + ” “);}System.out.println(“
p=” + p + ” j=” + j + ” r=” + r);q(nums, p, j);q(nums, j + 1, r);for (int n = p; n &lt;= r; n++) {System.out.print(nums[n] + ” “);}System.out.println();}}

1 public class Mean2 {3     public static void main(String[] args)4     {5         int N = args[0];6         int[] a = new int[N];7         for(int i = 0; i &lt; N; i++)8             a[i] = StdIn.readInt();9         int sum = a[0];10         for(int i = 1; i &lt;= N; i++)11             sum = sum + a[i];12         StdOut.println(“Mean: ” + sum/N);13     }14 }

Identify (in ten words or less, each) three bugs and a performanceproblem in this code. Use the line numbers to refer to the code, and circle your answers.

Write a method named sqrt that takes a double parameter and returns its square root with a margin of error 0.01.For example, the square root of 3 is 1.73

So, within a margin of error of .01 means that your answer should be between 1.72 and 1.74

There should be no calls to other methods inside your sqrt method

The attached program implements a linked list for integer numbers. There is one method that needs to be implemented

The LinkedList add method

Please review the code to see how the linked list is defined and used. Then add the code such that when the program is run is produces the following output

run:

Next object value = 1

Next object value = 2

Next object value = 3


