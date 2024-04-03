# MIniprojeto1_p2
import java.util.Scanner;

public class Academia {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        System.out.println("Olá! Eu sou o seu assistente e vou te ajudar com o cadastro, eu me chamo Personal X.");
        System.out.println("Vamos começar o seu cadastro na academia.\n");
        
        System.out.println("Digite seu nome: ");
        String nome = scanner.nextLine();
        
        System.out.print("Okay, agora digite sua idade: ");
        int idade = scanner.nextInt();
        scanner.nextLine();
        
    
    System.out.print("Agora digite o seu e-mail: ");
        String email = scanner.nextLine();

        System.out.print("Seu telefone: ");
        String telefone = scanner.nextLine();
        
        System.out.print("Estamos quase terminando me informe o seu genero (Masculino/Feminino): ");
        String genero = scanner.nextLine();
        
        System.out.print("Para finalizar, digite seu objetivo na academia: ");
        String objetivo = scanner.nextLine();
        
        System.out.println("\nObrigado por fornecer suas informações. Aqui está um resumo do seu cadastro:");
        System.out.println("Nome: " + nome);
        System.out.println("Idade: " + idade);
        System.out.println("E-mail: " + email);
        System.out.println("Telefone: " + telefone);
        System.out.println("Gênero: " + genero);
        System.out.println("Objetivo: " + objetivo);
        
        System.out.println("\nSeu cadastro foi concluído com sucesso! Bem-vindo à academia.");
        
        scanner.close();
    }
}
