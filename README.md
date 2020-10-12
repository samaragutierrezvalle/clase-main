# clase-main
public class main {
    public static void main(String[] args) {

        int [][] Arreglo1 = new int [3][6];
        int  restaF;
        Arreglo1 [0][0] = 9;
        Arreglo1 [0][1] = 13;
        Arreglo1 [0][2] = 5;
        Arreglo1 [0][3] = 2;
        Arreglo1 [0][4] = 5;
        Arreglo1 [0][5] = 6;
        Arreglo1 [1][0] = 12;
        Arreglo1 [1][1] = 3;
        Arreglo1 [1][2] = 5;
        Arreglo1 [1][3] = 5;
        Arreglo1 [1][4] = 1;
        Arreglo1 [1][5] = 5;
        Arreglo1 [2][0] = 48;
        Arreglo1 [2][1] = 5;
        Arreglo1 [2][2] = 3;
        Arreglo1 [2][3] = 4;
        Arreglo1 [2][4] = 1;
        Arreglo1 [2][5] = 5;
        for (int i = 0; i <3 ; i++) {
            for (int j = 0; j <6; j++) {
               System.out.print(Arreglo1[i][j]+" ");

            }
            System.out.println("");
            //System.out.println("La resta del arreglo es: "+cont);
        }


        //Resta
        for (int i = 0; i <3; i++) {
            restaF =0;
            for (int j = 0; j <6; j++) {
                restaF -= Arreglo1[i][j];
            }
            System.out.println("\n La resta de la fila ["+i+"] es: "+restaF);
        }
    }
}
