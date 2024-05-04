# Jogo-do-Bicho-C-
Repositório do jogo do bicho com biblioteca random

#include <iostream>
#include <vector>
#include <algorithm>
#include <random>

using namespace std;

int main(){
vector<string> animais = {"Avestruz", "Águia", "Burro", "Borboleta", "Cachorro", "Cabra", "Carneiro", "Camelo", "Cobra", "Coelho", "Cavalo", "Elefante", "Galo", "Gato", "Jacaré", "Leão", "Macaco", "Porco", "Pavão", "Peru", "Touro", "Tigre", "Urso", "Veado", "Vaca"};
random_device rd;
shuffle(animais.begin(), animais.end(), rd);
cout << "O animal sorteado foi: " << animais[0] << endl;

  if(animais[0] == "Avestruz"){
    vector<int> numeros_avestruz = {1, 2, 3, 4};
    random_device rd2;
    shuffle(numeros_avestruz.begin(), numeros_avestruz.end(), rd);
    cout << "Número sorteado: " << numeros_avestruz[0] << endl;
  }

  if(animais[0] == "Águia"){
    vector<int> numeros_aguia = {5, 6, 7, 8};
    random_device rd2;
    shuffle(numeros_aguia.begin(), numeros_aguia.end(), rd);
    cout << "Número sorteado: " << numeros_aguia[0] << endl;
  }

  if(animais[0] == "Burro"){
    vector<int> numeros_burro = {9, 10, 11, 12};
    random_device rd2;
    shuffle(numeros_burro.begin(), numeros_burro.end(), rd);
    cout << "Número sorteado: " << numeros_burro[0] << endl;
  }

  if(animais[0] == "Borboleta"){
    vector<int> numeros_borboleta = {13, 14, 15, 16};
    random_device rd2;
    shuffle(numeros_borboleta.begin(), numeros_borboleta.end(), rd);
    cout << "Número sorteado: " << numeros_borboleta[0] << endl;
  }

  if(animais[0] == "Cachorro"){
    vector<int> numeros_cachorro = {17, 18, 19, 20};
    random_device rd2;
    shuffle(numeros_cachorro.begin(), numeros_cachorro.end(), rd);
    cout << "Número sorteado: " << numeros_cachorro[0] << endl;
  }

  if(animais[0] == "Cabra"){
    vector<int> numeros_cabra = {21, 22, 23, 24};
    random_device rd2;
    shuffle(numeros_cabra.begin(), numeros_cabra.end(), rd);
    cout << "Número sorteado: " << numeros_cabra[0] << endl;
  }

  if(animais[0] == "Carneiro"){
    vector<int> numeros_carneiro = {25, 26, 27, 28};
    random_device rd2;
    shuffle(numeros_carneiro.begin(), numeros_carneiro.end(), rd);
    cout << "Número sorteado: " << numeros_carneiro[0] << endl;
  }

  if(animais[0] == "Camelo"){
    vector<int> numeros_camelo = {29, 30, 31, 32};
    random_device rd2;
    shuffle(numeros_camelo.begin(), numeros_camelo.end(), rd);
    cout << "Número sorteado: " << numeros_camelo[0] << endl;
  }

  if(animais[0] == "Cobra"){
    vector<int> numeros_cobra = {33, 34, 35, 36};
    random_device rd2;
    shuffle(numeros_cobra.begin(), numeros_cobra.end(), rd);
    cout << "Número sorteado: " << numeros_cobra[0] << endl;
  }

  if(animais[0] == "Coelho"){
    vector<int> numeros_coelho = {37, 38, 39, 40};
    random_device rd2;
    shuffle(numeros_coelho.begin(), numeros_coelho.end(), rd);
    cout << "Número sorteado: " << numeros_coelho[0] << endl;
  }

  if(animais[0] == "Cavalo"){
    vector<int> numeros_cavalo = {41, 42, 43, 44};
    random_device rd2;
    shuffle(numeros_cavalo.begin(), numeros_cavalo.end(), rd);
    cout << "Número sorteado: " << numeros_cavalo[0] << endl;
  }

  if(animais[0] == "Elefante"){
    vector<int> numeros_elefante = {45, 46, 47, 48};
    random_device rd2;
    shuffle(numeros_elefante.begin(), numeros_elefante.end(), rd);
    cout << "Número sorteado: " << numeros_elefante[0] << endl;
  }

  if(animais[0] == "Galo"){
    vector<int> numeros_galo = {49, 50, 51, 52};
    random_device rd2;
    shuffle(numeros_galo.begin(), numeros_galo.end(), rd);
    cout << "Número sorteado: " << numeros_galo[0] << endl;
  }

  if(animais[0] == "Gato"){
    vector<int> numeros_gato = {53, 54, 55, 56};
    random_device rd2;
    shuffle(numeros_gato.begin(), numeros_gato.end(), rd);
    cout << "Número sorteado: " << numeros_gato[0] << endl;
  }

  if(animais[0] == "Jacaré"){
    vector<int> numeros_jacare = {57, 58, 59, 60};
    random_device rd2;
    shuffle(numeros_jacare.begin(), numeros_jacare.end(), rd);
    cout << "Número sorteado: " << numeros_jacare[0] << endl;
  }

  if(animais[0] == "Leão"){
    vector<int> numeros_leao = {61, 62, 63, 64};
    random_device rd2;
    shuffle(numeros_leao.begin(), numeros_leao.end(), rd);
    cout << "Número sorteado: " << numeros_leao[0] << endl;
  }

  if(animais[0] == "Macaco"){
    vector<int> numeros_macaco = {65, 66, 67, 68};
    random_device rd2;
    shuffle(numeros_macaco.begin(), numeros_macaco.end(), rd);
    cout << "Número sorteado: " << numeros_macaco[0] << endl;
  }

  if(animais[0] == "Porco"){
    vector<int> numeros_porco = {69, 70, 71, 72};
    random_device rd2;
    shuffle(numeros_porco.begin(), numeros_porco.end(), rd);
    cout << "Número sorteado: " << numeros_porco[0] << endl;
  }

  if(animais[0] == "Pavão"){
    vector<int> numeros_pavao = {73, 74, 75, 76};
    random_device rd2;
    shuffle(numeros_pavao.begin(), numeros_pavao.end(), rd);
    cout << "Número sorteado: " << numeros_pavao[0] << endl;
  }

  if(animais[0] == "Peru"){
    vector<int> numeros_peru = {77, 78, 79, 80};
    random_device rd2;
    shuffle(numeros_peru.begin(), numeros_peru.end(), rd);
    cout << "Número sorteado: " << numeros_peru[0] << endl;
  }

  if(animais[0] == "Touro"){
    vector<int> numeros_touro = {81, 82, 83, 84};
    random_device rd2;
    shuffle(numeros_touro.begin(), numeros_touro.end(), rd);
    cout << "Número sorteado: " << numeros_touro[0] << endl;
  }

  if(animais[0] == "Tigre"){
    vector<int> numeros_tigre = {85, 86, 87, 88};
    random_device rd2;
    shuffle(numeros_tigre.begin(), numeros_tigre.end(), rd);
    cout << "Número sorteado: " << numeros_tigre[0] << endl;
    cout << "A prática do jogo do bicho é considerada uma contravenção penal no Brasil. Segundo o artigo 50 do Decreto-Lei nº 3.688/1941, quem “explorar ou realizar jogo de azar em lugar público ou acessível ao público” pode ser punido com prisão simples de três meses a um ano e multa(Fonte:https://canalcienciascriminais.com.br/participar-de-jogo-do-bicho-e-crime/)";
  }

  if(animais[0] == "Urso"){
    vector<int> numeros_urso = {89, 90, 91, 92};
    random_device rd2;
    shuffle(numeros_urso.begin(), numeros_urso.end(), rd);
    cout << "Número sorteado: " << numeros_urso[0] << endl;
  }

  if(animais[0] == "Veado"){
    vector<int> numeros_veado = {93, 94, 95, 96};
    random_device rd2;
    shuffle(numeros_veado.begin(), numeros_veado.end(), rd);
    cout << "Número sorteado: " << numeros_veado[0] << endl;
  }

  if(animais[0] == "Vaca"){
    vector<int> numeros_vaca = {97, 98, 99, 00};
    random_device rd2;
    shuffle(numeros_vaca.begin(), numeros_vaca.end(), rd);
    cout << "Número sorteado: " << numeros_vaca[0] << endl;
  }

return 0;
}
