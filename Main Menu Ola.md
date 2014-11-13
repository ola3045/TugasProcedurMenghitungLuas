TugasProcedurMenghitungLuas
===========================
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package id.co.blits.tugasola;

/**
 *
 * @author Star
 */
public class MainMenu {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        System.out.println("<<<~~~~~~ MENGHITUNG LUAS ~~~~~~>>>"+"\n");
        PersegiPanjang ola = new PersegiPanjang();
        ola.panjang=30;
        ola.lebar=18;
        ola.tampilPersegiPanjang();
        
        Lingkaran nisa = new Lingkaran();
        nisa.jarijari= 4 ;
        nisa.tampilLingkaran();
        
        Segitiga fahrunnisa = new Segitiga();
        fahrunnisa.alas= 10 ;
        fahrunnisa.tinggi=20;
        fahrunnisa.tampilSegitiga();
    
    
    
    }
    
}
