# Huvudrubrik som H1
Rubriker fungerar som HTML H1 till H6 men med * framför Rubriken
Exempelvis \* H1 Rubriuk \** H3 Rubrik

### UnderRubrik som H3
Vanlig Text med *kursiverad text* och ***fet text***.

Markdown förstår html
Så vi kan använda exempelvis  \<span style="color:blue">span</span> för att färglägga 
<span style="color:blue">some *blue* text</span>

Oordnad Punktlista ges - framför ordet

\- Punkt 1

\- Punkt 2

\- Punkt 3

	- Punkt 3a

	- Punkt 3b

\- Punkt 4

Ordnad Punktlista anges med siffra och punkt ex 1.

1. Punkt 1

2. Punkt 2

3. Punkt 3

	- Punkt 3a

4. Punkt 4

Kod ska vara intenderad med minst 1 tab eller 4 mellanslag.

	public staic void main(String args[])
	{
		for( String arg : args)
			System.out.println(arg);
	}

En linje görs med 3 streck \---
---

Länkar görs med \[länktext](URL)

Exemeplvis [Markdown Guide](https://www.markdownguide.org/basic-syntax/)

Bilder \![Bildtext](/sökväg bildfil)
![javascript logo](/javascript.jpg)

