# szkolapackage zadanko;
import java.util.Random;
/**
 *
 * @author Student
 */
public class Player {
    private String imie ;
    private Random r = new Random();
    void setName(String imie){
        this.imie = imie;
    }
    public String getName(){
        return imie;
    }
    int guess(){    
        return r.nextInt(6)+1;        
    }
   
}
