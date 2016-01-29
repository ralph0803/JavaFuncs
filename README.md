# QuickCode
Some no-brainer codes for Java

打印Hello World：
public class HelloWorld {
    public static void main(String[] args){
        System.out.println("Hello World!");
    }
}

打印array元素：System.out.println(Arrays.toString(target));
打印ArrayList元素：直接System.out.println(target);

声明ArrayList：ArrayList<Integer> pointX = new ArrayList<Integer>();
声明String：String[] str = new String[10];
声明int：int a = 0;
char初始化：char target = '\0';

array的长度：target.length;
String的长度：target.length();
list的长度：target.size();

取array中的元素：target[i];
取arrayList中的元素：target.get(i);
取String中的元素：target.charAt(i);

单维的hash用HashSet，二维用HashMap，HashSet初始化格式和Set, List一样，但HashSet的值不可以重复，List的值可以重复。

String的subset：target.substring(5,13);
array的subset：Arrays.copyOfRange(target, start, end);

String转array：target.toCharArray();
String转int：int foo = Integer.parseInt("1234");
int转String：String.valueOf(target);
int转char："" + target;
char转int：int x = Character.getNumericValue(element.charAt(2));
array转list：Arrays.asList(target); // 但target必须是primitive type，比如Integer，Character，Double，而不是int, char, double
list转array：target.toArray(new Object[size]);

String append：target1 + target2;
String append from the front：target = target1 + target;

二维数组的长和宽：第一维（长）：target.length; 第二维（宽）：target[0].length;

check检查String或List是否为空：target.isEmpty();


