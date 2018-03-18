## Структурна лінгвістика

### 1. Побудуйте ланцюжок походження слів за зразком:

оженитися: (о + (женити + ся))

1. (не+(((с+(при+йнят))+лив)+ість))
2. (а+((тип+ов)+ий))
3. (без+(((від+(по+від))+альн)+о)) 
4. (мор+е+(плав+ання))
5. ((о+((по+дат)+к)+ув)+ати)
6. (((пере+(в+тіл))+ити)+ся)
7. (((((с+хил)+и)+вши))+сь)
8. (трьох+((ярус+н)+ий))
9. (під+сніж+ник)
10. ((((з+ужит)+к)+ован)+ий)

### 2. Перевірте роботу [SnowballStem](http://snowballstem.org/) для спільнокореневих слів. Напишіть ваші спостереження.

1. truth, truthful, truthfulness, countertruth, untruthful, truthology
	truth, truth, truth, countertruth, untruth, trutholog
	truthological -> trutholog
2. flaw, flaws, flawed, flawless, flawlessness, flawlessly,
	flaw, flaw, flaw, flawless, flawless, flawless,  
3. лес, лесной, лесник, лесничий, лесничество, пролесье
	лес, лесн, лесник, леснич, лесничеств, пролес
4. окно, окошко, подоконник, оконный, окнище
	окн, окошк, подоконник, окон, окнищ
	
	Для російської мови стемер не виходить за рамки частини мови, відсікає закінчення. 
	Словотворчі суфікси лишаються (4), важко прослідкувати спорідненість слів. 
	Для англійської мови стирається різниця між частинами мови. 
	Більш поширені суфікси (-fulness) відсікаються, менш поширені (-ology) лишаються. 
	У випадку 2 втратилася різниця між словом та його антонімом.
	В усіх випадках префікси лишаються без змін. 
	Це не дуже передбачуваний інструмент, який для різних мов вимагає різних підходів. В цілому дозволяє позбутися флексій ціною частини значення.

### 3. Визначте частину мови виділеного слова і зв'язок до його батька (за зразком):

{I} like turtles.: pronoun, nsubj(like, I)  
I {like} turtles.: verb, root(ROOT, like)  
I like {turtles}.: noun, dobj(like, turtles)


1. We can {but} hope that everything will be fine. : conjunction, CC, cc(can, but)
2. It's sad {but} true. : conjunction, CC/CCONJ, cc(sad, but)
3. Jack brings nothing {but} trouble. : preposition, CC/ADP, case(trouble, but)
4. {As} we were talking, I realised how to solve the issue. : preposition, IN/ADP, mark(talking, as)
5. This hot dog isn't {as} big as usual. : adverb, RB/ADV, advmod(big, as)
6. This hot dog isn't as big {as} usual. : preposition, IN/ADP, case(usual, as)
7. This hot dog isn't as big {as} I expected. : preposition, IN/ADP, mark(expected, as)
8. I work {as} a teacher. : preposition, IN/ADP, prep(work, as)
9. Let's do it this {way}! : noun, NN, npadvmod(do, way)
10. This is {way} too much! : adverb, ADV, advmod(much, way)
11. The prices are going {down}. : particle, PRT, prt(going, down)
12. Someone pushed him and he fell {down} the stairs. : preposition, ADP, prep(fell, down)
13. I’ve been feeling rather {down} lately. : ADV, advmod(feeling, down)
14. It's not easy to {down} a cup of coffee in one gulp. : verb, xcomp(easy, down) 
15. Bring a {down} jacket and a pair of gloves, and you'll be fine. : adjective, ADJ, amod(jacket, down)

### 4. Визначте частину мови виділеного слова, його лему і зв'язок до його батька (за зразком):

{Я} люблю черепашок.: займенник, я, nsubj(люблю, Я)  
Я {люблю} черепашок.: дієслово, любити, root(ROOT, люблю)  
Я люблю {черепашок}.: іменник, черепашка, dobj(люблю, черепашок)  

1. Рада міністрів Європейського союзу затвердила угоду про спрощений порядок видачі {віз} для України. : іменник, NOUN/NN, віза, nmod(видачі, віз) 
2. Батько Себастьяна {віз} на санях їх театральний гурт до Львова. : дієслово, VERB/VBD, везти, root(ROOT, віз)
3. А ще дивний елемент інтер’єру – {віз} із продукцією одного з херсонських виробників. : іменник, NOUN/NN, віз, appos(елемент, віз)
4. У цю мить {повз} Євгена пролетів останній вагон товарняка. : прийменник, повз, ADP/IN, prep(пролетів, повз) або case(Євгена, повз)
5. Кліпнув очима і побачив малого песика, який саме пробігав {повз} у бік села. : прийменник, повз, ADP/IN, prt(пробігав, повз)
6. Степанко перестав кричати, тільки ламкий стогін {повз} йому із грудей. : дієслово, повзти, VERB/VBD, ccomp(кричати, повз)
7. Часу не {гай} – декларацію подай! : дієслово, гаяти, root(ROOT, гай)
8. І коляд заспівали, і {гай} врятували. : іменник, гай, dobj(врятували, гай)
9. {Гай}, чи ви забулися, братове? : вигук, гай, INTJ, advmod(забулися, гай) 
10. Ось присіла на {край} ліжка. : іменник, край, nmod(присіла, край)
11. Поставив ту кузню не {край} дороги, як було заведено, а на Красній горі, біля Прадуба. : прийменник, край, case(край, дороги)
12. Розповідаючи про передній {край} лінґвістики, фон Лібіх, як завжди, мислив широко і глобально. : іменник, край, ADP/IN, nmod(розповідаючи, край)
13. Не {край} мені серце. : дієслово, краяти, ROOT(root, край)
14. І {щойно} тоді додаємо до борщу смажену цибулю. : частка, щойно, PART, advmod(тоді, щойно) #ADV?
15. Бо {щойно} я задрімав, віддавши тіло подушці з периною, як мене розбудив поштовх у бік. : прислівник, щойно, ADV, advmod(задрімав, щойно) 

### 5. Побудуйте синтаксичну структуру речень за зразком:

Я люблю черепашок.  
nsubj(люблю, Я)  
root(ROOT, люблю)  
dobj(люблю, черепашок)

1. Пригадую, уже згодом, коли я відбував свій термін у таборі № 36 у Кучино Пермської області, я отримав від Михасі листівку з жартівливим описом того, як Київ готується до святкування свого 1500-ліття.
Пригадую,		root(ROOT, Пригадую)
уже 			advmod(згодом, уже) 
згодом,			advmod(отримав, згодом)
коли 			advmod(відбував, коли) #mark?
я 				nsubj(відбував, я)
відбував 		advcl(отримав, відбував)
свій 			det(термін, свій)
термін 			dobj(відбував, термін)
у 				case(таборі, у)
таборі 			compound(відбував, таборі)
№ 				compound(36, №)
36 				nmod(36, відбував)
у 				case(області, у)
Кучино 			compound(Пермської, Кучино)
Пермської 		compound(області, Пермської)
області, 		nmod(відбував, області)
я 				nsubj(отримав, я)
отримав			ccomp(пригадую, отримав)
від 			case(Михасі, від)
Михасі 			nmod(отримав, Михасі)
листівку 		dobj(отримав, листівку)
з 				case(описом, з)
жартівливим 	amod(описом, жартівливим)
описом 			nmod(листівку, описом)
того, 			nmod(описом, того) # складений сполучник ?
як 				mark(готується, як) 
Київ 			nsubj(готується, Київ)
готується 		acl(того, готується)
до 				case(святкування, до)
святкування 	nmod(готується, святкування)
свого 			det(1500-ліття, свого) #nmod:poss ???
1500-ліття.		nmod(святкування, 1500-ліття)


2. 6C приземляється на плече, перекочуючись, пролітає метрів п’ятдесят і витягується на снігу за кілька кроків від забризканої палаючими уламками посадкової смуги.
6C 				nsubj(приземляється, 6C)
приземляється 	root(ROOT, приземляється)
на 				case(плече, на)
плече, 			nmod(приземляється, плече)
перекочуючись, 	advmod(приземляється, перекочуючись)
пролітає 		conj(приземляється, пролітає)
метрів 			dobj(пролітає, метрів)
п’ятдесят 		nummod(метрів, п’ятдесят)
і 				cc(пролітає, i)
витягується 	conj(пролітає, витягується)
на 				case(снігу, на)
снігу 			obl(витягується, снігу) # nmod?
за 				case(кроків, за)
кілька 			det(кроків, кілька)
кроків 			obl(витягується, кроків)
від 			case(смуги, від)
забризканої 	acl(смуги, забризканої)
палаючими 		amod(уламками, палаючими)
уламками 		nmod(забризканої, уламками)
посадкової 		amod(смуги, посадкової)
смуги.			nmod(кроків, смуги)


3. Дівчина стояла там, де й була, і намагалася привести до ладу скуйовджене волосся, вкрай розлючена тим, що це побачили водії, які чекали на переїзді.
Дівчина 		nsubj(стояла, дівчина)
стояла 			root(ROOT, стояла)
там, 			advmod(стояла, там)
де 				advmod(була, де)
й 				discourse(була, й)
була, 			advcl(стояла, була)
і 				сс(стояла, і)
намагалася 		conj(намагалася, стояла)
привести 		xcomp(намагалася, привести)
до 				advmod(привести, до)
ладу 			mwe(до, ладу)
скуйовджене 	amod(волосся, скуйовджене)
волосся, 		dobj(привести, волосся)
вкрай 			advmod(розлючена, вкрай)
розлючена 		xcomp(стояла, розлючена)
тим, 			obl(розлючена, тим)
що 				mark(побачили, що) 
це 				dobj(побачили, це)
побачили		acl(розлючена, побачили) 
водії, 			nsubj(побачили, водії)
які 			det(чекали, які)
чекали			acl(побачили, чекали)
на 				case(переїзді, на)
переїзді.		obl(чекали, переїзді) # nmod?


### 6. Виберіть одне cлово зі списку та побудуйте лексико-семантичні зв'язки до трьох різних значень цього слова. Фактично, потрібно побудувати WordNet-подібні вузли. Значення слів можна перевірити у [СУМі](http://sum.in.ua/) та [Словниках України](http://lcorp.ulif.org.ua/dictua/).

Слова на вибір: вік, стіна, добро, серце, центр, куля, міст, ланцюг, бік, дух.


Ланцюг
1. Ряд металевих кілець, послідовно з'єднаних одне з одним. Виріб, що складається з окремих твердих ланок, які шарнірно з'єднані між собою.
гіпонім: велосипедний ланцюг, якірний ланцюг, ланцюжок годинника, паперовий ланцюг (гірлянда)
гіперонім: з'єднання, зв'язок
сестринські: ланець, ретязь, ланцюжок (ювелірний виріб), цеп
голоніми: ланка, кільце
мероніми: виріб 
2. Те, що сковує волю, свободу, пригнічує кого-, що-небудь. 
гіперонім: обмеження
сестринські: кайдани, ланці, пута, окови
3. сукупність однорідних предметів, явищ або істот, розташованих одне поруч з одним, одне за одним і т. ін.
гіпонім: ланцюжок хімічних реакцій, електричний ланцюг, живий ланцюг 
гіпероніми: ряд, послідовність
сестринські: низка, лінія, ярус, галерея, вервечка


