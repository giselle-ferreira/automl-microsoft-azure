# automl-microsoft-azure

## Passo 1 
- Criar uma conta no [https://azure.microsoft.com/pt-br/free](https://azure.microsoft.com/pt-br/free)
- O cadastro é inicializado ao clicar no botão "Experimentar gratuitamente" (É necessário informar um número de cartão de crédito)

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/65ec85c8-0e65-4ec7-99ca-3dae6d5c70f5)

## Passo 2 
- Acessar a plataforma do Azure em [portal.azure.com](portal.azure.com)
- Buscar por "Azure Machine Learning" no campo de busca e selecionar o card referido.

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/268bc950-6675-43f7-a7b0-f878ec8e5d26)

## Passo 3
- Clicar em "Criar", para criar um novo workspace

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/ee3f5e69-ca7e-481a-97c6-3e5b94239db7)


## Passo 4
- Criar um novo "resource group", criar um "nome", a "região", e clicar em "Examinar e criar"

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/baa93339-7a6d-4103-9472-8642ea15471f)

- Aguardar até que a validação seja aprovada, e então clicar em "criar"
  
![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/48f345fc-3c51-49d4-94e6-2d217c5e09be)

## Passo 5
- A implantação fica em andamento e pode ser acompanhada na tela que é aberta automaticamente

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/fe5f7747-7039-4525-b093-0d17a6149500)

- Esta é a tela de finalização do deploy. Agora podemos clicar em "ir para o recurso".
   
![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/0bba7339-c866-4aa5-a254-2aa83120247b)

- Na tela do recurso, clicar em "Iniciar estúdio"
  
![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/f163bd85-4275-481c-b771-b98972acc889)

## Passo 6
- Neste passo, caso ainda não tenha, será necessário criar um "workspace", seguindo os passos abaixo. No meu caso, meu workspace já estava criado.

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/3bc637a3-4fcc-4028-acdc-643cb051fa1e)


![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/7acf0326-5334-471b-9877-0d25712efe2c)

## Passo 7
- Entrar no ambiente "Automated ML" e clicar em criar um "new ML automated job"

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/d36beebe-f666-4b4f-b811-962ac26daabe)

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/37bc5857-71d7-4550-b15e-15e358586003)

## Passo 7
- Preencher os dados do job com as informações (fornecidas pela documentação da Microsoft)

- 7.1 -> Preenchimento das informações básicas
  
![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/03857d50-4b3a-4ad2-abbb-a531f2968a7a)

- 7.2 -> Escolha do tipo de tarefa (Regressão) e criação do dataset

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/44e58420-dd67-4c26-995b-adbcb0b235bf)


- 7.3 -> Preenchimento das informações do dataset

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/86b9b033-5042-4f21-9852-1f795e5332b8)

- 7.4 -> Escolha da fonte dos dados

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/06238e45-cca4-4825-a40c-ac363d057e3c)

- 7.5 -> Inclusão da url do dataset. A url passa por uma verificação e validação.

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/fa37fc73-e064-4be5-8920-f1e1139f8f56)

- 7.6 -> Os dados devem estar com as seguintes configurações

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/3b2030c6-08b4-422d-8265-dd8bdbb2134c)

- 7.7 -> Ele traz uma visualização do schema. Não é necessário alterar nenhuma informação.

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/c7cd6ac2-dcbd-40fb-9ca2-497b45c76120)

- 7.8 -> Por fim, ele traz todas informações para review, e clicamos em "criar", para criar o dataset.

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/3dba151a-e6d4-4ac8-969d-8485f527a7e2)

- 7.9 -> Para avançar, selecionamos o dataset, e clicamos em "next"

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/b615675d-30b7-4c53-8a33-284f2040c411)

- 7.10 -> Configurações da tarefa

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/c362fa19-26c8-4a5e-ad97-664085dcfaba)

- 7.11 -> Não é necessário setar nenhuma informação diferença da parte de Computação

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/31efafef-e201-4872-94d5-677eac379505)

- 7.12 -> As informações são trazidas e podemos enviar o trabalho de treinamento

![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/e59c9084-09e2-47b7-86c8-146125f37356)

## Passo 8
- O modelo inicia o treinamento
  
![image](https://github.com/giselle-ferreira/automl-microsoft-azure/assets/84051263/a788dc15-9ccc-42bb-ac97-eee69e4d54cd)

















