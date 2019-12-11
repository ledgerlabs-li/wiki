# Proof-of-Work

Proof-of-Work \(PoW\) war der erste Konsens-Algorithmus einer Blockchain. Von Satoshi Nakamoto für den Einsatz in der Bitcoin-Blockchain entwickelt, verdanken wir PoW die hohen Mining-Aktivitäten und den damit einhergehenden Stromverbrauch. PoW ist bei genügend Netzwerkknoten ein sehr zuverlässiges System. Dies kann nicht von vielen Konsens-Mechanismen behauptet werden. Zu diesem Zeitpunkt wird PoW jedoch bereits als veraltete Technologie betrachtet. Ethereum wechselt vom PoW-Algorithmus zum Energie-effizienteren und wirtschaftlicheren System - Proof-of-Stake \(PoS\) \(Whiterspoon, 2018\).

## In a Nutshell

In PoW lösen Miner schwierige kryptografische Rätsel, um zu beweisen, dass eine gewisse Menge an Rechenleistung aufgewendet wurde, um Transaktionen zu validieren. Alle Miner arbeiten simultan an derselben Aufgabe und stehen im Wettbewerb zueinander. Findet einer der Miner die korrekte Lösung, teilt er diese mit dem gesamten Netzwerk und ein neuer Block wird generiert. Ist die Lösung korrekt, was leicht überprüfen lässt, erhält er eine Entlohnung. Die Miner versuchen nun den nächsten Transaktions-Block zu lösen, welcher auf dem vorhergehenden basiert. Proof-of-Work gewährleistet somit chronologische Ordnung von Transaktionsblöcken. Die Miner vertrauen dabei immer derjenigen Blockchain, die am längsten ist. Das heisst, sie schenken derjenigen Blockchain, in die bereits die meiste Rechenarbeit geflossen ist ihr Vertrauen. Eine Datenmanipulation wird dadurch extrem rechenintensiv und bedarf mehr als 50 Prozent der Rechenleistung des gesamten Netzwerks. Stark dezentralisierte Blockchains, welche den PoW-Algorithmus verwenden, werden deshalb als nicht manipulierbar angesehen.

![Proof-of-Work in 6 Schritten](../../.gitbook/assets/pow.PNG)

1. **Transaktion**: Neue, unverifzierte Transaktionen werden durch die Netzwerkknoten geteilt \(Broadcast\).
2. **Verbinden:** Die Miner verbinden sich mit der Sammlung aller Transaktionsdaten \(Mempool\), um diese zu verifizieren.
3. **Validieren:** Transaktionen werden ausgewählt, validiert und einem Block zugeordnet.
4. **Verketten:** Die Miner erweitern jeweils die längste Kette, in welche bereits am meisten Rechenleistung geflossen ist.
5. **Rätsel:** Die Miner lösen das Proof-of-Work-Rätsel bzw. suchen nach einem bestimmten Wert, der auf dem vorherigen Block basiert.
6. **Bestätigen:** Sobald ein Miner das Rätsel löst, teilt er die Lösung mit dem Netzwerk und wird dafür entlohnt. Der Block wird zur Blockchain hinzugefügt.

## Technische Funktionsweise

Um zu verstehen wie der Proof-of-Work Algorithmus technisch funktioniert, muss in erster Linie verstanden werden, aus welchen Bestandteilen die Datenstruktur einer Blockchain aufgebaut ist und wie ein Hash-Algorithmus funktioniert. 

![Technische Funktionsweise von Proof-of-Work](../../.gitbook/assets/pow_detail.png)



