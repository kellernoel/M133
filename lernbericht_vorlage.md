# Lern-Bericht
Noel Keller

## Einleitung

Im Projekt ging es darum, eine oder mehrere xhtml-Seiten, miteinander zu verknüpfen.

## Was habe ich gelernt?

Ich habe gelernt, wie ich in jsf eine andere xhtml-Seite verlinken kann.

## Beschreibung


```xhtml
  <h:link value="Schritt 1" outcome="#{SitzVer.weiterleitung()}"/>
```

```Java
  public String weiterleitung() {
        return "schritt1.xhtml";
  }
```

![jsf](https://user-images.githubusercontent.com/74292626/187196112-a2fcbd66-e770-48fb-bf94-9ffa670ad3b4.gif)

Beim oberen Code wird ein Link erstellt, mit dem Namen "Schritt 1". Ausserdem holt es von der Methode im unteren Code den String "schritt1.xhtml" und kommt somitauf die Seite mit dem Namen schritt1.xhtml.


## Verifikation

✍️ Erklären Sie kurz und bündig, inwiefern die von Ihnen verwendeten Medien zeigen, was Sie gelernt haben.

# Reflektion zum Arbeitsprozess

👍 Überlegen Sie sich jeweils etwas, was gut an Ihrer Arbeit lief; 

👎 und etwas, was nicht gut lief.

**VBV**: ✍️ Formulieren Sie davon ausgehend einen *handelbaren* Verbesserungsvorschlag.
