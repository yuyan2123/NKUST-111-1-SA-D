```python
abstract class CShape{
    protected String color;
    public void setColor(String str){
        color = str;
    }
 
    public abstract void show();
}
class CTriangle extends CShape{
    double ca, cb, cc;
    public CTriangle(double a, double b, double c){
        ca=a;
        cb=b;
        cc=c;
    }
   
    public void show() {
       
        System.out.print("color="+color+"  ");
        System.out.print("area="+0.5*ca*cb);
    }
   
}

```
