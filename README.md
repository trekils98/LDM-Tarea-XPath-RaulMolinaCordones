# LDM-Tarea-XPath-RaulMolinaCordones

Reto1:
/bibliotecaTecnica/recurso[disponible=true() and categoria="CSS"]/titulo /string()

Dentro de recurso filtro los resultados con [ ] poniendo que unicamente los disponibles y de categoria CSS


Reto2:
/bibliotecaTecnica/recurso[@formato!="PDF"]/@id /string()

Dentro de recurso filtro para que unicamente salgan de formato distinto != a PDF, como el valor PDF es el por defecto
unicamente aparece uno.


Reto3:
/bibliotecaTecnica/recurso[anio>2015]/autor[1] /string()

Dentro de recurso filtro para que unicamente salgan mayores de 2015 y en el paso a autor pongo [1] para que
unicamente aparezca uno por recurso filtrado.


Reto4:
/bibliotecaTecnica/recurso[(categoria="XPath" or categoria="XSLT") and nivel=5 ]/titulo /string()

Dentro de recurso filtro para que la categoria sea XPath o XSLT entre parentesis para que or se haga antes que and y
posteriormente filtro por el nivel enseñando despues el titulo
