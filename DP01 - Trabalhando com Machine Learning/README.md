<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="60px" src="https://hermes.dio.me/lab_projects/badges/87d332d0-5198-4a2f-b159-38c8c2976954.png"></a>
    <span> Machine Learning</span>
</h1>

<img align="right" src="https://raw.githubusercontent.com/alexklenio/DIO-Microsoft-Azure-AI-Fundamentals/main/imagens/DP01%20-%20Machine%20Learning/01.png" width=""/> 

...

## Aprendizado de maquina para a previsão de aluguel de bicicletas:
<img align="right" src="https://raw.githubusercontent.com/alexklenio/DIO-Microsoft-Azure-AI-Fundamentals/main/imagens/DP01%20-%20Machine%20Learning/02.png" width=""/> 

O tipo de tarefa é regressão e o nome de ativo de dados e aluguel de bicicletas, com fonte de dados da WEB.
<img align="right" src="https://raw.githubusercontent.com/alexklenio/DIO-Microsoft-Azure-AI-Fundamentals/main/imagens/DP01%20-%20Machine%20Learning/03.png" width=""/> 

<img align="right" src="https://raw.githubusercontent.com/alexklenio/DIO-Microsoft-Azure-AI-Fundamentals/main/imagens/DP01%20-%20Machine%20Learning/04.png" width=""/> 

<img align="right" src="https://raw.githubusercontent.com/alexklenio/DIO-Microsoft-Azure-AI-Fundamentals/main/imagens/DP01%20-%20Machine%20Learning/05.png" width=""/> 

...

Adocumentação do Learning é bem didática e traz todos os valores e configurações para que o trabalho automatizado seja criado:
<img align="right" src="https://raw.githubusercontent.com/alexklenio/DIO-Microsoft-Azure-AI-Fundamentals/main/imagens/DP01%20-%20Machine%20Learning/07.png" width=""/> 
<img align="right" src="https://raw.githubusercontent.com/alexklenio/DIO-Microsoft-Azure-AI-Fundamentals/main/imagens/DP01%20-%20Machine%20Learning/08.png" width=""/> 
<img align="right" src="https://raw.githubusercontent.com/alexklenio/DIO-Microsoft-Azure-AI-Fundamentals/main/imagens/DP01%20-%20Machine%20Learning/09.png" width=""/> 
<img align="right" src="https://raw.githubusercontent.com/alexklenio/DIO-Microsoft-Azure-AI-Fundamentals/main/imagens/DP01%20-%20Machine%20Learning/10.png" width=""/> 
<img align="right" src="https://raw.githubusercontent.com/alexklenio/DIO-Microsoft-Azure-AI-Fundamentals/main/imagens/DP01%20-%20Machine%20Learning/11.png" width=""/> 
<img align="right" src="https://raw.githubusercontent.com/alexklenio/DIO-Microsoft-Azure-AI-Fundamentals/main/imagens/DP01%20-%20Machine%20Learning/12.png" width=""/> 
<img align="right" src="https://raw.githubusercontent.com/alexklenio/DIO-Microsoft-Azure-AI-Fundamentals/main/imagens/DP01%20-%20Machine%20Learning/13.png" width=""/> 

...

Chegando na opção "examinar" basta enviar o seu trabalho de treinamento:
<img align="right" src="https://raw.githubusercontent.com/alexklenio/DIO-Microsoft-Azure-AI-Fundamentals/main/imagens/DP01%20-%20Machine%20Learning/14.png" width=""/> 

...

Após envio seu trabalho irá passar pelo proxesso de configuração das execuções e após 15, podendo o tempo ser menor, estará concluído:
<img align="right" src="https://raw.githubusercontent.com/alexklenio/DIO-Microsoft-Azure-AI-Fundamentals/main/imagens/DP01%20-%20Machine%20Learning/15.png" width=""/> 

<img align="right" src="https://raw.githubusercontent.com/alexklenio/DIO-Microsoft-Azure-AI-Fundamentals/main/imagens/DP01%20-%20Machine%20Learning/16.png" width=""/> 

...

Pipeline com as etapas do processo de aprendizado e os testes realizados
<img align="right" src="https://raw.githubusercontent.com/alexklenio/DIO-Microsoft-Azure-AI-Fundamentals/main/imagens/DP01%20-%20Machine%20Learning/17.png" width=""/> 

## Teste

Na página do modelo, cliquei na aba "Pontos de extremidade". Também é possível acessar pelo menu lateral em "Pontos de extremidade". Cliquei no ponto correspondente ao modelo gerado. Em seguida, acessei a aba "Testar".

Para o teste, utilizei o json abaixo:

``` JASON
{
  "input_data": {
    "data": [
       {
         "day": 1,
         "mnth": 1,   
         "year": 2022,
         "season": 2,
         "holiday": 0,
         "weekday": 1,
         "workingday": 1,
         "weathersit": 2, 
         "temp": 0.3, 
         "atemp": 0.3,
         "hum": 0.3,
         "windspeed": 0.3 
       }
     ]
  }
}
```

Resultado: 361.95

<img align="right" src="https://raw.githubusercontent.com/alexklenio/DIO-Microsoft-Azure-AI-Fundamentals/main/imagens/DP01%20-%20Machine%20Learning/18.png" width=""/> 
