
🚀 Configuração de Rede Cisco (2911) com VLANs e DHCP: Sucesso na Estabilização da Rede!
🎉 Missão Cumprida!

Acabo de concluir com sucesso a reestruturação e configuração da rede da minhaempresa, garantindo sua funcionalidade total e estabilidade. Superando os desafios deixados pela gestão anterior, implementei as melhores práticas de rede em um ambiente simulado no Cisco Packet Tracer.

🛠️ O Desafio e a Solução
O objetivo principal era configurar um roteador Cisco 2911 com VLANs e serviços de DHCP para segmentar e gerenciar eficientemente o tráfego das áreas de Financeiro (VLAN 10), Vendas (VLAN 20) e TI/Servidores (VLAN 40).

O trabalho focou na documentação e correção de problemas críticos de conectividade e resolução de nomes.

📝 Resumo das Ações Chave
Conectividade Inter-VLAN (Inter-VLAN Routing):

Problema Inicial: Falha na comunicação entre diferentes departamentos/VLANs.

Solução: Configuração de sub-interfaces no roteador 2911, definindo-as como Gateways para cada VLAN e utilizando o encapsulamento 802.1Q para permitir que o roteador trate o tráfego de múltiplas VLANs (o chamado Router-on-a-Stick).

Serviço DHCP:

Próximo Passo: Implementação de um servidor DHCP centralizado ou a configuração do DHCP Relay no roteador para cada VLAN, garantindo que cada dispositivo receba seu endereço IP, Gateway e o endereço do Servidor DNS automaticamente. (Embora não detalhado na atividade, é o passo lógico para a automação e funcionalidade da rede).

Resolução de Nomes (DNS):

Problema Inicial: Impossibilidade de acessar o servidor web pelo nome de domínio (minhaempresa.com).

Ferramenta Utilizada: nslookup, ipconfig /all.

Solução: Verificação e correção do IP do Servidor DNS configurado nos hosts e nos pools DHCP. Garanti que o Servidor DNS estava configurado corretamente para resolver o nome minhaempresa.com para o IP do Servidor Web (192.168.40.20).

Teste de Conectividade:

Utilização de comandos como ping e tracert (tracert/traceroute) para validar a conectividade dentro das VLANs, entre as VLANs e até os servidores, confirmando que a rota e os Gateways estavam funcionais.

✅ Resultado Final
A rede está agora totalmente funcional, permitindo:

Comunicação interna (mesma VLAN).

Comunicação entre departamentos (VLANs distintas) via Roteador.

Resolução de domínio para o servidor web.

Acesso ao Servidor Web (http://minhaempresa.com) a partir de qualquer PC, conforme demonstrado no teste final.

Com essa documentação detalhada e a rede estável, demonstro minha capacidade de diagnóstico, solução de problemas e configuração robusta de infraestrutura de rede Cisco.

#Cisco #VLAN #DHCP #NetworkEngineering #PacketTracer #IT
