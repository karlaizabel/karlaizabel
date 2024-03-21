Nome: <Karla Izabel e Maria Leticia>
Matricula: <>

Questao 12:
  <int main(void) {
  
  float aloha[10], coisas[10][5], *pf, value = 2.2;
  int i=3;
  aloha[2] = value;
  scanf("%f", &aloha);
  aloha = "value";//Inválido pois não é possível atribuir uma string a um array de floats
  printf("%f", aloha);//Inválido pois não é possível imprimir um array de floats
  coisas[4][4] = aloha[3];
  coisas[5] = aloha;//Inválido pois não é possível atribuir
  pf = value;// Inválido pois não é possível atribuir o value a um ponteiro de float 
  pf = aloha;
  printf("Hello World\n");
  return 0;}
  >
---------------------------


Questao 13:
  <//A memory leak, em tradução livre, vazamento de memória, ocorre quando o programa não libera para o sistema operacional memória que não é mais utilizada. 
  O problema surge a partir do gerenciamento na alocação dinamica.
  Exemplos:>
---------------------------
Questao 14: 
<O uso de ponteiros para funções em C serve principalmente para definir, em tempo de execução,
qual função será executada, sem a necessidade de escrever o nome da função, de forma explícita naquele ponto do código.
Exemplo:















































































































>

