class highspeed implements Runnable{
    static int ticket=10000;
    static int sum=0;
    int sold=0;
    Thread s;
    
    highspeed(String name){
        sold=0;
        s=new Thread(this,name);
        s.start();
    }
    public void run(){
        while(solded()==true){    
            sum=(int)(Math.random()*4)+1; 
            while(ticket<sum){   
                sum=(int)(Math.random()*(sum))+1;
            }
                sold+=sum;
                ticket-=sum;
            
             System.out.println(s.getName()+"售出"+sum+"張票");
        }
            System.out.println(s.getName()+"總共售出"+sold+"張票");
        }
    
        
     synchronized private static boolean solded(){
        if(ticket>0){
            return true;
        }else{
            return false;
        }
    }
}


public class hw2 {
    public static void main(String[] args){
        highspeed tA=new highspeed("機器A");
        highspeed tB=new highspeed("機器B");
        highspeed tC=new highspeed("機器C");
        highspeed tD=new highspeed("機器D");

    }
}
