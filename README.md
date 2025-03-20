FD-OPGAVE-SKABELON


Udfordringer:

Generelle udfordringer: Jeg har haft udfordringer hele vejen igennem projektet, både med opsætning, styling og struktur. Det er svært at pege på én ting, der virkelig træder frem, men samlet set har det været en lærerig opgave. 

Tidspres: Som altid var tid en hindring. Jeg nåede ikke at lave alle sider færdige, og der er stadig nogle mangler på visse komponenter.


Successer:

Næsten alt er responsivt:Jeg fik næsten hele designet til at være responsivt, hvilket jeg er ret tilfreds med.

Bedre forståelse af CSS: Gennem projektet har jeg fået en bedre forståelse for, hvordan CSS fungerer, især når det gælder organisering af styles og arbejde med komponent-styling.

Dynamisk komponentstruktur: Jeg har brugt Astro-komponenter til at genbruge kode og minimere brugen af HTML og CSS.


Kodeeksempler:

Her er eksempeler på, hvordan jeg har brugt CSS:

Data-varianter: InfoSection.astro -> Dette komponenter har jeg implementeret på adskellige sektioner. Jeg har både kunne style farve, tekst og generel styling af komponentet. 

Popover: Popover.astro -> Dette komponent har jeg lave til en login sektion som kommer frem og forsvinder når jeg trykker på login knappen. 

Scroll-effekt: ScrollingCard.astro / ScrollingContent.astro -> Her viser jeg hvordan jeg min scroll-effekt fungerer og jeg har implementeret scroll-snap


CSS-struktur:

Jeg har delt min CSS op i globalt og komponent-specifikt:

Global CSS (src/styles/global.css):

Her har jeg lagt fælles styles som farver, typografi og reset-styles.

Den bruges til overordnede layoutjusteringer.

Komponentspecifik CSS (i .astro-filer):

Hvis en style kun gælder for én komponent, har jeg lagt den direkte i .astro-filen i et <style>-tag.

På den måde påvirker det ikke resten af siden.


PS 
(Mine checkmarks på Checklist.astro vises ikke på chrome, men gør i live-server...)