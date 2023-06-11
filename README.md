VA1 - 2. domácí úkol
Druhý domácí úkol je zaměřený na Jetpack Compose, knihovnu Room, Dependency
Injection a také Material design. Vaším úkolem bude vytvořit aplikaci pro OS Android.
Popis aplikace
Aplikace pro evidenci kontaktů. Uživatel si může evidovat svoje kontakty. U každého
kontaktu je evidováno:
● Jméno - povinné pole
● Příjmení - povinné pole
● Telefon - povinné pole
● Typ kontaktu (osobní/pracovní) -povinné pole
● E-mailová adresa - nepovinné pole
V případě, že povinné pole není vyplněno, není možné kontakt přidat do databáze a uživatel
je na tuto skutečnost upozorněn.
Aplikace umožňuje:
● Přidat kontakt - všechny pole jsou řešena přes TextField (nebo jemu podobné),
kromě typu. Pro typ použijte metodu Spinner.
● Zobrazit seznam všech kontaktů:
○ Každá položka seznamu má vzhled viz obrázek níže.
○ Barva kolečka je generovaná hodně ze 6 různých barev (barvy si zvolte podle
vlastního uvážení).
● Aplikace si uchovává stav (seznam kontaktů) i po vypnutí
