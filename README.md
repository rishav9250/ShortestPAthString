# ShortestPAthString
here is a code of Shortest Path in java.


public class StringShortestpath {
    public static float ShortestPath(String str){
        int x=0;
        int y=0;
        for(int i=0;i<str.length();i++){
            char dir = str.charAt(i);
            if(dir == 'E'){
                x++;
            }
                else if(dir=='W'){
                    return x--;
                }
                    else if(dir=='N'){
                        return y++;
                    }
                    else{
                        y--;
                    }
                     int X2=x*x;
                     int Y2=y*y;
                     return (float)Math.sqrt(X2+Y2);   
                }
                    

                
            }
        
    public static void main(String[] args) {
        String str ="WNEENESENNN";
    System.out.println(ShortestPath(str));
    }
}
    


