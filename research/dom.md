# DOM (The Document Object Model)
Dom (The Document Object Model) е апликативен програмски интерфејс (API) за HTML и XML документи. Ја дефинира логичката структура на документите и начинот на пристап и манипулирање со документот.<p>&nbsp;</p>
**Дом претставува документ со логично стебло, каде секоја гранка на дрвото завршува во јазол а секој јазол содржи предмети.**
## Стандарди на DOM(The Document Object Model)
* Ниво 1 на DOM обезбедува целосен модел за целокупниот документ на ХТМЛ, вклучувајќи ги сите средства кои се користат за промена на тој домунет. 
* Ниво 2 воведува фукнција getElementByld (Овој метод го враќа елементот што го содржи пренесеното име. Како што знаеме, идентификацијата треба да биде единствена, па затоа е многу корисен метод за да се добие само саканиот елемент.). 
* Ниво 3 додава поддршка за управување со настани како XPath.
* Ниво 4 кое објавуа слика за животниот стандард на WHATWG(е заедница на луѓе кои се заинтересирани да ја развиваат мрежата преку стандарди и тестови.)
<p>&nbsp;</p>

## Употреба на DOM
Програмерите преку DOM(The Document Object Model) можат да градат документи, да се движат низ нивната структура и да додаваат, изменуваат или бришат елементи и содржина. Може да се пристапи, да се смени, избрише или додадат сe што се наоѓа во документ на HTML или XML.
* W3C како спецификација е една важна цел за DOM е да обезбеди стандарден програмски интерфејс што може да се користи во широк спектар на околини и апликации.

## Структура на DOM
* Во ДОМ, документите имаат логичка структура која наликуваат на дрво, поточно шума која може да содржи повеќе од едно дрво.
<p>&nbsp;</p> 
- Една важна карактеристика на моделите на структура на ДОМ е структурниот изоморфизам односно ако се користат две имплементации на модел на документ за да се создаде претстава за истиот документ, тие ќе создадат ист модел на структура, со точно исти предмети и односи.

#### DOM содржи:
* Интерфејсите и предметите што се користат за претставување и манипулирање со документ.
* Семантиката на овие интерфејси и објекти - вклучувајќи ги и однесувањето и атрибутите.
* Односите и соработките помеѓу овие интерфејси и објекти.

Со манипулирање на ДОМ, имате бесконечни можности. Може да креирате апликации што ги ажурираат податоците на страницата без да имате потреба од освежување. Исто така, можете да креирате апликации што можат да ги прилагодува корисникот, а потоа да го промените изгледот на страницата без освежување. Може да влечете, преместувате и бришете елементи во секое време.