using System; 

class minhaClasse {
    static void Main(string[] args) { 
        string[] valores = Console.ReadLine().Split();
        int A = int.Parse(valores[0]);
        int B = int.Parse(valores[1]);
        int Q, S;
            
        Q= A / B;
        S= (A % B);
            
        if (S<0) {
            double  Q1, S1 = 0.0;

            S1 = S + Math.Sqrt(B * B);
            Q1 = (A - S1) / B;
            Console.WriteLine("{0} {1}", Q1,S1);
        } else {
            Console.WriteLine("{0} {1}", Q, S);
        }
    }
}
