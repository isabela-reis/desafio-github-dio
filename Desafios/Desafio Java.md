Desafio em Java, proposto na matéria de Fundamentos de Ciências Exatas, em união com os conhecimentos obtidos na matéria de Construção de Algoritmos.

Desenvolva um programa em Java que informe se um ano é bissexto ou não. 

import java.util.Scanner; 
class Main {  
  public static void main(String args[]) { 
    
    int ano; 
    Scanner ler = new Scanner(System.in);

    System.out.println("Informe um ano");
    ano = ler.nextInt();

    if(ano % 400==0){
      System.out.println("O ano informado é bissexto.");
    }
    else if(ano % 4 ==0 && ano % 100!=0){
      System.out.println("O ano informado é bissexto.");
    }else{
      System.out.println("O ano informado não é bissexto."); 
    }
  } 
}
