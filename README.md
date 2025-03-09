# cPalz

cPalz die ultimative Programmiersprache für die Pfalz. Denn es gibt für einen Menschen nichts besseres als in der Pfalz zu leben.

WIP

## Klassen und Funktionen
Beispiel in Java:
```java
public class Main {
  int x = 5;

  public static void main(String[] args) {
    Main myObj = new Main();
    System.out.println(myObj.x);
  }
}
```
Umsetzung in cPalz:
```text
oeffentlich klasse Main {
  zaahl a = 5;

  oeffentlich test() {
    schreib(a);
  }
}// ToDo
```

## Einfache Datentypen
|Name in anderen Programmiersprachen |Name in cPalz| Wert|
|--------|--------|--------|
|  bool  |    wohr    | True / False |
|  double  |    kommazaal    |  |
|  int  |    zaahl    |  |
|  array  |    lischd    |  |
|  string  |    text    |  |
|  No  |    dubbeglaas    | Enthält ein Schbbe |
|  No  |    dubbe    | Ein 38stel eines Schobbes |
|  No  |    schobbe    | 500 |

## Selektionen
|Name in anderen Programmiersprachen |Name in cPalz|
|--------|--------|
|  if a == b:  |    mänschd (a is b) {}    |
|  else if a == b:  |    mänschd des (a is b) {}    |
|  else:  |    bischddadoganzsicher {}    |

## Switch Statements
Beispiel in Java:
```java
int day = 4;
switch (day) {
  case 6:
    System.out.println("Today is Saturday");
    break;
  case 7:
    System.out.println("Today is Sunday");
    break;
  default:
    System.out.println("Looking forward to the Weekend");
}
```
Umsetzung in cPalz:
```text
zaahl daach = 4;
schalder (daach) {
  option 6:
    schreib("Samsdaach");
    uffhere;
  option 7:
    schreib("Sundach");
    uffhere;
  schunschd:
    schreib("Looking forward to the Weekend");
}
```

## Schleifen
Wie jede richtige Programmiersprache haben wir auch Schleifen.
|Name in anderen Programmiersprachen |Name in cPalz|
|--------|--------|
|  for (int i = 1; i <= 10; i++) {}  |    schleife (zaahl p = 0; p <= 10; p++) {}    |
|  while ( i <= 10) { i++;}  |    solang ( i <= 10) { i++;}    |
|  do {things(); } while ( i <= 10)  |    mach {} solang ( i <= 10)    |

## Sichtbarkeiten
Auch cPalz nutzt Sichtbarkeiten für Vartiablen, Funktionen und Klassen
|Name in anderen Programmiersprachen |Name in cPalz|
|--------|--------|
|  public  |    oeffentlich    |
|  protacted  |    gschuetzt    |
|  private  |    privad    |

## Kommentare
Sind wichtig, deshalb haben wir sie hier ebenfalls.
|Setzzung in anderen Programmiersprachen |Name in cPalz|
|--------|--------|
|  // Ein Kommentar  |    // Ein Kommentar    |
| /* Kommentar über mehrere Zeilen */  |    /* Kommentar über mehrere Zeilen */    |
| # Kommentar   |    Machen wir hier nicht    |
