# Ponderada K6 - Semana 7 Módulo 9

O k6 é uma ferramenta de teste de carga eficaz e fácil de usar, projetada para avaliar a performance de aplicações web e serviços sob condições de tráfego intenso. Nesse contexto, sua simplicidade e eficiência permitem que desenvolvedores e equipes de QA testem rapidamente a capacidade dos sistemas de suportar altos volumes de acesso, assegurando assim a confiabilidade e o alto desempenho das aplicações em momentos críticos. Logo, ao identificar proativamente gargalos e potenciais problemas de performance, o k6 desempenha um papel fundamental na manutenção da qualidade da experiência do usuário e na otimização dos recursos operacionais.

## K6 no contexto do projeto

O k6 assume papel fundamental no projeto em parceria com a Track.co, haja vista que auxilia na construção e garantia de um sistema de testes automatizados robusto e eficiente, garantindo, assim, a qualidade da plataforma da startup. Nesse cenário, os testes de carga podem gerar insights valiosos, bem como a identificação de possíveis gargalos na plataforma que estejam afetando de forma negativa o desempenho e a entrega da Track aos clientes. 

## Teste com K6

Para a ponderada, foi testado o endpoint de **Listagem das distribuições**, através da url ```http://localhost:8080/distrbuitions```. A seguir, estão algumas prints da execução do teste, partindo da definição de dois cenários:

**Cenário 1:** 100 requisições por segundo num período de 30 segundos.
<img src="./assets/cenario1.png"/>

**Cenário 2:** 1000 requisições por segundo num período
de 30 segundos.
<img src="./assets/cenario2.png"/>
