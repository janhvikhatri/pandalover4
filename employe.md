# pandalover4
class Emlpoyee
{ private string name,address; 
private int year,salary;
public Employee(String n,int y,int sal,string add) 
{
name=n; 
year=y;
salary=sal; 
address=add; 
}
public string getName() 
{ 
return name; 
} 
public int getYear() 
{ 
return year;
} 
public int getSalary()
{ 
return salary;
} 
public String getAddress()
{
return address;
} }
class Emp { public static void main(String[] args) { Employee e1 = new Employee("Robert",1994,500000,"64C- wallsStreet"); 
Employee e2 = new Employee("Sam",2000,740000,"68d- wallsStreet"); 
Employee e3 = new Employee("John",1999,600000,"26B- wallsStreet");
system.out.println("Name\tYear of joining\tSalary\tAddress"); 
system.out.println(e1.getName()+"\t"+e1.getYear()+"\t\t\t"+e1.getSalary()+"\t"+e1.getAddress());
system.out.printl…
}
}
