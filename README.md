# Array_List
Addition of variable and automatic expanding and shrinking of Array Size. 
import java.util.*;
class ArrayList{
public static void main(String args[]){
ArrayList<String> a1=new ArrayList<String>();
a1.add("a");
a1.add("b");
a1.add("c");
a1.add("f");
a1.add("d");
a1.add(1,"g");
System.out.println("Sixe of array="+a1.size());
a1.remove("a");
a1.remove("c");
System.out.println("value of Array are="+a1);
System.out.println("After DEleting the items remaining capacity is="+a1.size());
}
}
