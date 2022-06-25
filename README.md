 linha de codigos c++
 
 #include <iostream>
 #include <iomanip>

 using namespace std;


 int main() {

  /// Entrada de dados
     double A, B, C, D,E;

  /// (A e B são os números), (C e D são os pesos) e (E é a soma dos pesos)
     cin >> A >> B >> C >> D;

      E = (C + D);

     double media;
     
     media = (A*C + B*C)/E;
   /// Apresentação de resultado
      
  cout << "Media = " << setprecision(5)<< media << endl;
  
     return 0;

 }
