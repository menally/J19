import java.util.ArrayList;
public class Main {
    public static void main (String[] args){
        int lugar = 1;
                ArrayList<Integer> promedio = new ArrayList<> ();
        promedio.add(9);
        promedio.add(8);
        promedio.add(5);
        promedio.add(6);
        System.out.println("Registro de promedio");
        for (Integer p : promedio){
            if (p >=6){
                System.out.println("promedio" + promedio + ":Es mayor a 6");
            } else {
                System.out.println("promedio"+ promedio + ": Es menor de 6");
            }
        }

    }
}