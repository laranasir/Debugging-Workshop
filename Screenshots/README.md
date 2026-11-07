Jeg brugte breakpoints i IntelliJ til at sætte programmet på pause og undersøge koden.
Med Evaluate Expression så jeg, at getRandomInteger(1) kun gav 0.
Jeg ændrede grænsen til 2 og brugte Step Over til at se, at den lodrette retning blev valgt.
Jeg satte et breakpoint med betingelsen hitCount == 3 for at undersøge isSunk().
Her viste debuggeren false ved 3 træffere, så jeg ændrede > til >=.
Jeg undersøgte fejlen ArrayIndexOutOfBoundsException og så, at x og endPoint.x var 10.
Jeg begrænsede skibets startkoordinater, så hele skibet kan være inden for pladen.
Jeg rettede også spillerens skud, så koordinaterne kan være fra 0 til 9.
Til sidst kørte jeg spillet og kontrollerede, at det kunne vise Ship sunk! uden fejl.