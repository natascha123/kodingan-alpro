kodingan-alpro
==============
package alprolagi;

public class Alprolagi {

    public static void main(String[] args) {
        
        int[][] matrixA ={{1,2,3},{4,5,6},{7,8,9}};
        int[][] matrixB ={{4,5,6},{7,8,9},{1,2,3}};
        int[][]jumlahMatrix = new int[3][3];
        int[][]kaliMatrix= new int[3][3];
        
        System.out.println("Matrix A : ");
        for (int x = 0; x < matrixA.length; x++) {
        for (int y = 0; y < matrixA.length; y++) {
        System.out.print("  " + matrixA[x][y]);}
        System.out.println();}
        
       System.out.println("Matrix B : ");
        for (int x = 0; x < matrixB.length; x++) {
        for (int y = 0; y < matrixB.length; y++) {
        System.out.print("  " + matrixB[x][y]);}
        System.out.println();}
        
        System.out.println("Jumlah Matrix : " );
        for(int x = 0; x < matrixA.length; x++) {
        for(int y = 0; y < matrixB.length; y++) {
        jumlahMatrix[x][y] = matrixA[x][y] + matrixB[x][y];
        System.out.print("  " +  jumlahMatrix [x][y]); }
        System.out.println();}
        
      System.out.println("Hasil Perkalian Matrix : " );
      for(int x = 0; x < matrixA.length; x++) {
      for(int y = 0; y < matrixB.length; y++) {
      kaliMatrix[x][y] = matrixA[x][y] * matrixB[x][y];
      System.out.print("  " +  kaliMatrix [x][y]);}
      System.out.println();
      }}}
