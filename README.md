# I 5 Rompiscatole

Una skill per Claude, tutta in italiano. Prima di prendere una decisione
importante la fai esaminare da cinque rompiscatole. Ognuno ragiona per conto
suo, poi si giudicano a vicenda senza sapere chi ha scritto cosa. Alla fine
arriva una decisione chiara.

Il capo dei rompiscatole è **Super Squalo**: l'avvocato del diavolo, quello che
trova il punto debole che nessuno vuole vedere.

## Chi sono i cinque

1. **Super Squalo, il capo dei rompiscatole.** "Chi paga?", "l'hai provato o lo
   stai immaginando?", "cosa succede se va male?".
2. **Il Concreto.** La strada più semplice che funziona. Cosa fai domani mattina.
3. **Il Contabile.** Soldi, tempo, fatica. Fa i conti anche quando nessuno li
   ha chiesti.
4. **La Voce del Pubblico.** Si mette nei panni di chi riceve il risultato.
5. **Il Ricercatore.** Cerca chi l'ha già fatto. Esempi veri, dati, errori già
   pagati da altri.

## Come funziona

1. **Il Segretario.** Prima di tutto riscrive bene la tua domanda: cosa vuoi
   decidere, i fatti, i vincoli, cosa manca. Te la fa vedere. Tu correggi o
   scrivi **vai**. Così nessuno decide con un'informazione mancante.
2. **I pareri.** I cinque ragionano ognuno per conto suo.
3. **La revisione alla cieca.** Si danno i voti a vicenda senza sapere chi ha
   scritto cosa.
4. **La decisione.** Il presidente tira le somme: decisione, piano, dove sono
   d'accordo e dove no. L'ultima parola è di Super Squalo.
5. **Secondo grado.** Non sei d'accordo? Scrivi **secondo grado:** e spiega cosa
   non hanno considerato. Ogni punto viene accolto, accolto in parte o
   respinto. Si cambia idea per un fatto nuovo, mai per farti contento.
6. **Terzo grado.** L'ultimo esame. Un Giudice nuovo controlla come si è
   ragionato, come la Cassazione. Poi decidi tu.

Hai fretta o la domanda è piccola? Scrivi **rompiscatole veloce:** e salta la
revisione alla cieca. Costa circa la metà.

## Come si usa

Scrivi per esempio:

> rompiscatole: conviene lasciare il lavoro per fare YouTube a tempo pieno?

Funziona anche con "smontami questa idea", "devo decidere se...", "dammi un
secondo parere".

## Come si installa

**Nell'app Claude** (serve un abbonamento a pagamento):

1. Scarica questo repository con il pulsante verde **Code**, poi
   **Download ZIP**.
2. In Claude vai su **Impostazioni**, poi **Capacità**, poi **Skill**.
3. Carica lo zip.

**In Claude Code:**

```
git clone https://github.com/super-squalo/rompiscatole ~/.claude/skills/rompiscatole
```

Poi apri una sessione nuova.

**In ChatGPT, Gemini o altri:** apri il file `SKILL.md`, copia tutto e incollalo
come istruzioni di un GPT o di un Gem. Lì i cinque non lavorano davvero
separati, quindi il risultato è un po' più debole.

## Quanto consuma

Il giro completo usa cinque assistenti in parallelo: consuma circa dieci volte
una risposta normale. Per questo c'è il Segretario: si spende poco all'inizio
per avere tutte le informazioni, così non serve rifare il giro.

## Da sapere

I cinque rompiscatole sono lo stesso assistente con ruoli diversi, non persone
vere. Consigliano, non decidono al posto tuo. Per soldi, contratti e salute
serve sempre un professionista vero.

---

Fatta da [Super Squalo](https://supersqualo.it). Idea ispirata al "LLM Council"
di Andrej Karpathy e al progetto claude-council (licenza MIT). Riscritta da zero
in italiano.

Licenza MIT.
