# A seguir esta a lista de tópicos dividida entre os participantes do episodio especificado na nomeacao deste documento.






jaoleal:

1a.
*  [BIP 54: Consensus Cleanup](https://github.com/bitcoin/bips/pull/1800)     
* - [Interview with Antoine Poinsot](https://www.youtube.com/watch?v=-LGpW2PKwHA)
* - Resumo: "Resolve timewarp attack, novos limites de script para diminuir a maior quantidade de tempo possivel que um bloco pode fazer um node demorar 
para validar e uma mudancinha no numa restricao das transacoes em questao de tamanho e em coinbases"
* - "Pergunta 1" - "Resposta para a pergunta 1"

2a.
* [Awesome CTV+CSFS](https://github.com/arshbot/awesome-ctv-csfs)
* - Resumo: "Eh uma lista cobrindo varios assuntos relacionados a CTV e CSFS, mostra diversos projetos que podem ser possiveis com a ativacao do CTV, tem uma lista
mostrando tudo oq eh possivel ser feito com bitcoin, uma lista para ferramentas que integram com CTV e algumas que tambem com CSFS, algumas fontes de material 
sobre os opcodes e topicos de discussao"
* - "Pergunta 1" - "Resposta para a pergunta 1"

3a.
* [Bitcoin Core 29.0](https://github.com/bitcoin/bitcoin/blob/master/doc/release-notes/release-notes-29.0.md#notable-changes)
* - Resumo: "Nova versao do bitcoin: (vai ler la), destaco o novo comando RPC o getdescriptoractity"
* - "Pergunta 1" - "Resposta para a pergunta 1"

4a.
* [SwiftSync: “Near-stateless, fully parallelizable validation of the Bitcoin blockchain with hints about which outputs remain unspent.”](https://gist.github.com/RubenSomsen/a61a37d14182ccd78760e477c78133cd)
* - "links auxiliares
* - Resumo: "Apresenta um novo protocolo de sincronizacao da blockchain(Como assim sincronizacao ?) bitcoin para nodes, o protocolo se baseia no uso de aritmetica de 
hashes agregados e dicas sobre o tip para sincronizar na rede. Um node que esteja usando SwiftSync recolhe informacao sobre os UTXOs no TIP, vai 
interpretando blocos e adicionando outputs que ja foram canonicamente gastos no futuro no agregador de hashes e removendo eles assim que sao gastos em blocos, desta forma
ele consegue verificar que a chain esta correta e que as informacoes repassadas sao veridicas quando ao chegar ao tip o acumulador estiver zerado garantindo que mapeou
todos os UTXOs. Switft sync parece ser voltado para performance e diminuicao de tempo em que se eh gasto fazendo sincronizacao da rede alem de poder ser executado em
dispositivos leves como smartphones, minipcs e ate FPGAS sem muita dificuldade. Swift sync consegue fazer isso pois sua sincronizacao ja recebe um pseudo UTXO set e 
nao precisa fazer nenhum tipo de flush, ele nao precisa escrever em disco como a sincronizacao atual do bitcoin core fazendo com que a performance de sincronizacao
seja totalmente relacionado ao poder de cpu e a velocidade da memoria ram que possui."
* - "Pergunta 1" - "Resposta para a pergunta 1"

5a.
* a [DahLIAS: Discrete Logarithm-Based Interactive Aggregate Signatures](https://eprint.iacr.org/2025/692.pdf)
* - Resumo: "TLDR; eh um novo protocolo de assinatura interativa e agregada, N participantes onde N ∈ {1, . . . , N} de tamanho constante, que promete tambem reduzir espaco de disco e poder de processamento. "
* - "Pergunta 1" - "Resposta para a pergunta 1"


j-moreno-r-c:

1b.	
*   [Someone inscribed this 3.7MB bitcoin music track via slipstream](https://x.com/mononautical/status/1906647846398640531)      
* - [Tx on Mempool Space](https://mempool.space/tx/62d17dd978f04e547b0156412c1706d4589ed9fb8aeeef804d694c405c6e0a10)
* - Resumo:
* - "Pergunta 1" - "Resposta para a pergunta 1"

2b.	
* [MIT Hackathon - Vinteum resident wins track](https://x.com/Vinteum_org/status/1909000853052109294)     
* - [Sig4Sats](https://github.com/vstabile/sig4sats-script)
* - Resumo:
* - "Pergunta 1" - "Resposta para a pergunta 1"

3b. 
*  [The 68-bit Bitcoin puzzle has been cracked!](https://x.com/lianabitcoin/status/1909573460910649832) 
* - Resumo:
* - "Pergunta 1" - "Resposta para a pergunta 1"

4b.	 
* [bitcoin.softforks.org](https://bitcoin.softforks.org/)
* - Resumo:
* - "Pergunta 1" - "Resposta para a pergunta 1"

5b.	
* [Taplocks: Verifiable but unspendable tapleafs](https://x.com/rot13maxi/status/1909252898170564621)
* - Resumo:
* - "Pergunta 1" - "Resposta para a pergunta 1"

6b.	
*  [Bitcoin mining is highly centralized today.](https://x.com/0xB10C/status/1912154961938383166)
* - Resumo:
* - "Pergunta 1" - "Resposta para a pergunta 1"

7b.	
*  [Bitcoin Address Poisoning Attacks](https://blog.lopp.net/bitcoin-address-poisoning-attacks/)
* - Resumo:
* - "Pergunta 1" - "Resposta para a pergunta 1"

8b.	
* [Against Allowing Quantum Recovery of Bitcoin](https://mailing-list.bitcoindevs.xyz/bitcoindev/CADL_X_cF=UKVa7CitXReMq8nA_4RadCF==kU4YG+0GYN97P6hQ@mail.gmail.com/#r)

* - Resumo:
* - "Pergunta 1" - "Resposta para a pergunta 1"



## webpage estatica bitdevs:
https://saopaulobitdevs.org/2025-04-24-socratic-seminar-034


	[São Paulo BitDevs](https://saopaulobitdevs.org/)

[Eventos](https://saopaulobitdevs.org/events)[Meetup](https://www.meetup.com/saopaulobitdevs)

==============================================================================================================================================================

# Seminário Socrático 034

24 Apr 2025[Link to Meetup](https://www.meetup.com/clubebitcoinsp/events/307412088/)

## Avisos

- Entrem no grupo do Whatsapp [São Paulo Bitdevs](https://chat.whatsapp.com/HiaPqjmUqER5djFPR1Yl3T)!
- Respeite a privacidade dos participantes.
- Os meetups nunca são gravados. Queremos todos a vontade para participar e discutir os assuntos programados, de forma anônima se assim o desejarem.

## Agradecimentos

- Agradecemos à Vinteum pela casa, comidas e bebidas.

## Cronograma

### Warmup

- [Someone inscribed this 3.7MB bitcoin music track via slipstream](https://x.com/mononautical/status/1906647846398640531)✅
    - [Tx on Mempool Space](https://mempool.space/tx/62d17dd978f04e547b0156412c1706d4589ed9fb8aeeef804d694c405c6e0a10)
- [MIT Hackathon - Vinteum resident wins track](https://x.com/Vinteum_org/status/1909000853052109294)✅
    - [Sig4Sats](https://github.com/vstabile/sig4sats-script)
- [The 68-bit Bitcoin puzzle has been cracked!](https://x.com/lianabitcoin/status/1909573460910649832)✅

### Softforks

- [BIP 54: Consensus Cleanup](https://github.com/bitcoin/bips/pull/1800)✅
    - [Interview with Antoine Poinsot](https://www.youtube.com/watch?v=-LGpW2PKwHA)
- [Awesome CTV+CSFS](https://github.com/arshbot/awesome-ctv-csfs)✅
- [bitcoin.softforks.org](https://bitcoin.softforks.org/)✅
- [How CTV+CSFS improves BitVM bridges](https://delvingbitcoin.org/t/how-ctv-csfs-improves-bitvm-bridges/1591)✅

### Bitcoin

- [Bitcoin Core 29.0](https://github.com/bitcoin/bitcoin/blob/master/doc/release-notes/release-notes-29.0.md#notable-changes)✅
- [SwiftSync: “Near-stateless, fully parallelizable validation of the Bitcoin blockchain with hints about which outputs remain unspent.”](https://gist.github.com/RubenSomsen/a61a37d14182ccd78760e477c78133cd)✅
- [Against Allowing Quantum Recovery of Bitcoin](https://mailing-list.bitcoindevs.xyz/bitcoindev/CADL_X_cF=UKVa7CitXReMq8nA_4RadCF==kU4YG+0GYN97P6hQ@mail.gmail.com/#r)✅
- [Taplocks: Verifiable but unspendable tapleafs](https://x.com/rot13maxi/status/1909252898170564621)✅
- [Bitcoin Address Poisoning Attacks](https://blog.lopp.net/bitcoin-address-poisoning-attacks/)✅

### Mining

- [Bitcoin mining is highly centralized today.](https://x.com/0xB10C/status/1912154961938383166)✅

### Crypto

- [DahLIAS: Discrete Logarithm-Based Interactive Aggregate Signatures](https://eprint.iacr.org/2025/692.pdf)✅

==============================================================================================================================================================

[Contribua pelo Github](https://github.com/saopaulobitdevs/saopaulobitdevs.org)

[RSS Feed](https://saopaulobitdevs.org/feed.xml)


