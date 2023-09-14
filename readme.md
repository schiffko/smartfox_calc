# Einheiten
Spannung:
    Einheit: V => Volt

Srom:
    Einheit: A => Ampere

Leistung:
    Einheit: W => Watt



# Umformung kW <-> W
2 Eingabefelder. 1mal für kW und 1mal für W
Nach dem Eingeben in das jeweilige Feld, soll jeweils der andere Wert ausgegeben werden:

1. Eingabe: kW, Ausgabe: W, Berechnung: x*1000
Bsp: 1,5kW * 1000 = 1500W

2. Eingabe: W, Ausgabe: kW, Berechnung: x/1000
Bsp: 1500W / 1000 = 1,5kW

Eingabefeld:
<input id="wattInput" type="text" onchange="calcKw()" />




# Berechnung Leistung aus Strom und Spannung
Aus Strom und Spannung die Leistung berechnen


2 Eingabefelder
1. Eingabefeld Strom in A
2. Eingabefeld Spannung in V

1 Ausgabefeld für Leistung in W

Berechnung: Strom * Spannung = Leistung
Bsp.: 10A * 230V = 2300W