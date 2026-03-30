## Regras de Negócio

Nome    | Descrição |
:------ | :-------- |
---|---|


## Requisitos Funcionais

Codigo | Nome | Descrição | Categoria | Prioridade |
:----- | :--- | :-------- | :-------- | :--------- |
||Monitorar sensores de invasão|Permitir que o usuário monitore sensores de invasão|Funcionais||
||Monitorar sensores de incêndio|Permitir que o usuário monitore sensores de incêndio|Funcionais||
||Monitorar sensores de inundação|Permitir que o usuário monitore sensores de inundação|Funcionais||
||Monitorar sensores de níveis de monóxido de carbono|rmitir que o usuário monitore sensores de níveis de monóxido de carbono|Funcionais||
||Verificar o estado do alarme|o usuário pode verificar o estado do alarme|Funcionais||
||Armar ou desarmar o sistema|o usuário pode armar ou desarmar o sistema|Funcionais||
||Reconfigurar zonas de segurança|o usuário pode reconfigurar zonas de segurança|Facilidade e Suporte||
||Visualizar imagens de câmeras instaladas na casa | "miniaturas" de todas as câmeras simultaneamente e escolher uma para ampliar, controlando remotamente o deslocamento e a aproximação da lente (pan e zoom) através do navegador|Funcionais||
||Controle de dispositivos eletrônicos, como luzes e eletrodomésticos|O usuário deve ser capaz de ajustar a temperatura do ar-condicionado enquanto volta para casa ou programar o sistema para acender e apagar luzes em intervalos aleatórios durante uma viagem para simular presença humana|Funcionais||
||Montar a planta da casa|O usuario pode montar sua plante com base em seção de objetos e redimensionamento dele|Funcionais||

## Requisitos Não Funcionais

Codigo   | Nome | Descrição | Categoria | Classificação | Permanência |
:------  | :--- | :-------- | :-------- | :--------     | :---------- |
||Protocolo 802.11n|Utilizar protocolo 802.11n para comunicação de hardware|Implementação|||
||Acesso via Internet| O Usuario deve conseguir acessar o sistema pela sua casa|Funcionais|||
||Alerta imediato contra invasões|O sistema deve ser capaz de contatar automaticamente um órgão de vigilância ou o telefone celular do proprietário quando uma situação crítica for detectada|Confiabilidade|||
||Criptografia|site totalmente seguro e criptografado, garantir que o sistema seja invulnerável a intrusos que tentem desarmá-lo via Internet|Implementação|||
||Responsivo|O site pode ser acessado pelo celular|Funcionais|||
||Ativação de sensor|ativação de um sensor deve ser reconhecida em menos de um segundo|Desempenho|||
||Priorização de Eventos|O sistema deve implementar uma priorização para os eventos detectados|Facilidade e Suporte|||
||Economia de Energia|Equilibrar o poder computacional com a vida útil da bateria, garantindo que o aplicativo seja eficiente em termos de energia|Implementação|||
||Gerenciar membros da familila|Sistema suporte o acesso simultâneo de múltiplos membros da família, possivelmente com diferentes níveis de permissão (ex: nem todos podem reconfigurar o sistema).|Facilidade e Suporte||
||Monitoramento ininterrupto|O sistema de monitoramento de sensores deve operar ininterruptamente|Funcionais||
||Detecção de Falhas de comunicação|Falhas de comunicação devem ser detectadas e reportadas imediatamente|Confiabilidade||
||Detecção de Perda de energia |Perda de energia devem ser detectadas e reportadas imediatamente|Confiabilidade||
||Objetos de montagem| O sistema deve possuir uma interface com ícones representando paredes, janelas e portas seriam "esticados" e posicionados sobre uma grade. Sensores e câmeras seriam então arrastados e soltos sobre essa planta para definir sua localização física no ambiente. Vinod e Jamie, da equipe de engenharia, ressaltam que a interface precisa ser consistente e simples o suficiente para que o proprietário não precise ler extensos manuais para operá-la|Interface|||

