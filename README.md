local articles = {
    {text="1.1 УК За завдання тілесних ушкоджень з необережності (1)", penalty=1, code="1.1 УК"},
    {text="1.2 УК За навмисне завдання тілесних ушкоджень цивільному (2)", penalty=2, code="1.2 УК"},
    {text="1.3 УК За завдання тілесних ушкоджень з необережності державному службовцю під час виконання (3)", penalty=3, code="1.3 УК"},
    {text="1.4 УК За навмисне завдання тілесних ушкоджень державному службовцю під час виконання (4)", penalty=4, code="1.4 УК"},
    {text="1.5 УК За умисне завдання тяжких тілесних ушкоджень співробітнику Міністерства Юстиції під час виконання (7)", penalty=7, code="1.5 УК"},
}

local articlesChapter2 = {
    {text="2.1 УК За вооружений напад на громадянську особу (5)", penalty=5, code="2.1 УК"},
    {text="2.2 УК За збройний напад на державного службовця під час виконання (6)", penalty=6, code="2.2 УК"},
}

local articlesChapter3 = {
    {text="3.1 УК За спробу руйнування цілісності штату (6)", penalty=6, code="3.1 УК"},
    {text="3.2 УК За руйнування цілісності штату (6)", penalty=6, code="3.2 УК"},
    {text="3.3 УК За спробу захоплення влади штату (6)", penalty=6, code="3.3 УК"},
    {text="3.4 УК За захоплення влади штату (6)", penalty=6, code="3.4 УК"},
}

local articlesChapter4 = {
    {text="4.1 УК За співучасть у злочин проти громадянина (4)", penalty=4, code="4.1 УК"},
    {text="4.2 УК За співучасть у злочині проти державного службовця (5)", penalty=5, code="4.2 УК"},
    {text="4.3 УК За співучасть у державному перевороті чи його спробі (6)", penalty=6, code="4.3 УК"},
}

local articlesChapter5 = {
    {text="5.1 УК Створено оружня (2)", penalty=2, code="5.1 УК"},
    {text="5.2 УК За носіння вогнепальної зброї у відкритому вигляді (2)", penalty=2, code="5.2 УК"},
    {text="5.3 УК Розповсюдження створеної зброї (5)", penalty=5, code="5.3 УК"},
    {text="5.4 УК За носіння вогнепальної зброї у відкритому вигляді без наявності ліцензії на її використання (5)", penalty=5, code="5.4 УК"},
}

local articlesChapter6 = {
    {text="6.1 УК За вживання наркотичних речовин (3)", penalty=3, code="6.1 УК"},
    {text="6.2 УК За зберігання наркотичних речовин (5)", penalty=5, code="6.2 УК"},
    {text="6.3 УК За купівлю наркотичних речовин (5)", penalty=5, code="6.3 УК"},
    {text="6.4 УК За продаж наркотичних речовин (6)", penalty=6, code="6.4 УК"},
    {text="6.5 УК За зберігання відмичок від тюремних дверей (4)", penalty=4, code="6.5 УК"},
    {text="6.6 УК За покупку відмичок від тюремних дверей (5)", penalty=5, code="6.6 УК"},
    {text="6.7 УК За продаж відмічок від тюремних дверей (5)", penalty=5, code="6.7 УК"},
    {text="6.8 УК За посів галюциногенних рослин та їх насіння (3)", penalty=3, code="6.8 УК"},
    {text="6.9 УК За зберігання галюциногенних рослин та їх насіння (3)", penalty=3, code="6.9 УК"},
    {text="6.10 УК За купівлю галюциногенних рослин та їх насіння (4)", penalty=4, code="6.10 УК"},
    {text="6.11 УК За продаж галюциногенних рослин та їх насіння (4)", penalty=4, code="6.11 УК"},
    {text="6.12 УК За продаж підроблених документів (нові документи) (6)", penalty=6, code="6.12 УК"},
    {text="6.13 УК За купівлю або продаж вогнепальної зброї поза офіційними амунаціями (6)", penalty=6, code="6.13 УК"},
    {text="", penalty=6, code="6.13 УК"},
}

local articlesChapter7 = {
    {text="7.1 УК За образу чи неадекватну поведінку у бік громадянина (2)", penalty=2, code="7.1 УК"},
    {text="7.2 УК За образу чи неадекватну поведінку у бік державних службовців (3)", penalty=3, code="7.2 УК"},
    {text="7.3 УК За образу чи неадекватну поведінку у бік перших осіб штату (5)", penalty=5, code="7.3 УК"},
}

local articlesChapter8 = {
    {text="8.1 УК За участь у несанкціонованому мітингу (3)", penalty=3, code="8.1 УК"},
    {text="8.2 УК За вооружение несанкціонований мітинг (6)", penalty=6, code="8.2 УК"},
    {text="8.3 УК За очолення несанкціонованих мітингів/мітингу (6)", penalty=6, code="8.3 УК"},
}

local articlesChapter9 = {
    {text="9.1 УК За загрози у будь-якій формі у бік громадянина (2)", penalty=2, code="9.1 УК"},
    {text="9.2 УК За загрози у будь-якій формі у бік державного службовця (3)", penalty=3, code="9.2 УК"},
    {text="9.3 УК За загрози у будь-якій формі на покуту на життя та здоров'я у бік гражданина (5)", penalty=5, code="9.3 УК"},
    {text="9.4 УК За загрози у будь-якій формі на покуту на життя та здоров'я у бік державного службовця (6)", penalty=6, code="9.4 УК"},
    {text="", penalty=6, code="8.6 УК"},
}

local articlesChapter10 = {
    {text="10.1 УК За крадіжку чи спробу крадіжки боєприпасів із військових об'єктів (5)", penalty=5, code="10.1 УК"},
    {text="10.2 УК За організацію чи участь у теракті (6)", penalty=6, code="10.2 УК"},
    {text="10.3 УК За захоплення державних установ (6)", penalty=6, code="10.3 УК"},
    {text="10.4 УК За взяття громадян у заручники або їх викрадення (6)", penalty=6, code="10.4 УК"},
    {text="10.5 УК За посягання на волю, примус до чогось або когось (6)", penalty=6, code="10.5 УК"},
}

local articlesChapter11 = {
    {text="11.1 УК За порушення статтею, що належить до державної измени Конституції штату (6)", penalty=6, code="11.1 УК"},
}

local articlesChapter12 = {
    {text="12.1 УК За проституцію (3)", penalty=3, code="12.1 УК"},
    {text="12.2 УК За зґвалтування (4)", penalty=4, code="12.2 УК"},
    {text="12.3 УК За проституцію у стані алкогольного сп'яніння (4)", penalty=4, code="12.3 УК"},
    {text="12.4 УК За згвалтування у стан алкогольного сп'яніння (5)", penalty=5, code="12.4 УК"},
    {text="12.5 УК За залучення проституцією або примус заняття проституцією (6)", penalty=6, code="12.5 УК"},
}

local articlesChapter13 = {
    {text="13.1 УК За вимагання коштів (3)", penalty=3, code="13.1 УК"},
    {text="13.2 УК За вимагання у стан алкогольного сп'яніння (4)", penalty=4, code="13.2 УК"},
}

local articlesChapter14 = {
    {text="14.1 УК За підрізання на машині та спробу вивести транспортний засіб (2)", penalty=2, code="14.1 УК"},
    {text="14.2 УК Проникнення у службове авто, без дозволу на це від співробітника державних організацій (2)", penalty=2, code="14.2 УК"},
    {text="14.3 УК За перешкоду та втручання у роботі державних службовців (4)", penalty=4, code="14.3 УК"},
}

local articlesChapter15 = {
    {text="15.1 УК За ігнорування спец. сирен та не пропуск патрульної машини (3)", penalty=3, code="15.1 УК"},
    {text="15.2 УК За спробу втечі з місця злочину (3)", penalty=3, code="15.2 УК"},
    {text="15.3 УК За непокору при проханні зупинитися біля мегафону (3)", penalty=3, code="15.3 УК"},
    {text="15.4 УК За відмову від пред'явлення документів, що підтверджують особу (3)", penalty=3, code="15.4 УК"},
    {text="15.5 УК За відмову чи неможливість сплатити штраф (4)", penalty=6, code="15.5 УК"},
    {text="15.6 УК За непокору державному службовцю (4)", penalty=4, code="15.6 УК"},
}

local articlesChapter16 = {
    {text="16.1 УК За дію під час якої громадянин пише неправдиву позовну заяву (2)", penalty=2, code="16.1 УК"},
    {text="16.2 УК За спробу викликати хвилювання в штаті через суд, маючи при цьому високий стан у штаті (3)", penalty=3, code="16.2 УК"},
    {text="16.3 УК За непокору працівникові прокуратури під час прямих обов'язків прокуратури (3)", penalty=3, code="16.3 УК"},
    {text="16.4 УК За наклеп у бік прокурора/судді або особи, яка проводитиме дізнання (3)", penalty=3, code="16.4 УК"},
    {text="16.5 УК За надання неправдивих показань суду або особі, яка проводитиме дізнання (3)", penalty=3, code="16.5 УК"},
    {text="16.6 УК За неявку на судове засідання на повестці дня суду (5)", penalty=5, code="16.6 УК"},
    {text="16.7 УК За невиконання судової ухвали чи постанови прокуратури (5)", penalty=5, code="16.7 УК"},
    {text="16.8 УК За спробу уникнення покарання (5)", penalty=5, code="16.8 УК"},
    {text="16.9 УК За поширення свідомо неправдивої інформації від імені прокуратури чи суду (6)", penalty=6, code="16.9 УК"},
    {text="16.10 УК За зрив суду (6)", penalty=6, code="16.10 УК"},
}

local articlesChapter17 = {
    {text="17.1 УК За проникнення на приватну територію (2)", penalty=2, code="17.1 УК"},
    {text="17.2 УК За проникнення на територію Поліцейського департаменту (3)", penalty=3, code="17.2 УК"},
    {text="17.3 УК За проникнення на територію Військових об'єктів чи В'язниці Суворого Режиму (3)", penalty=3, code="17.3 УК"},
    {text="17.4 УК За проникнення на територію Федерального бюро розслідувань (4)", penalty=4, code="17.4 УК"},
}

local articlesChapter18 = {
    {text="18.1 УК За псування приватного майна (2)", penalty=2, code="18.1 УК"},
    {text="18.2 УК За псування державного майна (3)", penalty=3, code="18.2 УК"},
}

local articlesChapter19 = {
    {text="19.1 УК За видачу себе за іншого громадянина (3)", penalty=3, code="19.1 УК"},
    {text="19.2 УК За підроблення документів, що засвідчують вашу особу (4)", penalty=4, code="19.2 УК"},
}

local articlesChapter20 = {
    {text="20.1 УК За крадіжку приватного майна (2)", penalty=2, code="20.1 УК"},
    {text="20.2 УК За пограбування громадянина (4)", penalty=4, code="20.2 УК"},
}

local articlesChapter21 = {
    {text="21.1 УК За викрадення повітряного засобу (6)", penalty=6, code="21.1 УК"},
    {text="21.2 УК За викрадення водного транспорту (6)", penalty=6, code="21.2 УК"},
    {text="21.3 УК За викрадення наземного транспорту (6)", penalty=6, code="21.3 УК"},
}

local articlesChapter22 = {
    {text="22.1 УК За хибний виклик патрульної машини на місце (2)", penalty=2, code="22.1 УК"},
    {text="22.2 УК За помилковий виклик патрульної машини з неадекватною причиною чи місцезнаходженням (4)", penalty=4, code="22.2 УК"},
}

local articlesChapter23 = {
    {text="23.1 УК За спробу висування себе адвокатом (2)", penalty=2, code="23.1 УК"},
    {text="23.2 УК За висування себе як адвокат на допиті чи інших розглядах щодо громадянина, який вчинив те чи інше порушення кодексу (3)", penalty=3, code="23.2 УК"},
}

local articlesChapter24 = {
    {text="24.1 УК За натяки на дачу хабара (2)", penalty=2, code="24.1 УК"},
    {text="24.2 УК За спробу дачі хабара (3)", penalty=3, code="24.2 УК"},
    {text="24.3 УК За дачу хабара (5)", penalty=5, code="24.3 УК"},
    {text="24.4 УК За отримання хабара співробітником держ. організацій (6)", penalty=6, code="24.4 УК"},
    {text="24.5 УК За спробу підкупу чи підкуп судді, прокурора (6)", penalty=6, code="24.5 УК"},
}

local articlesChapter25 = {
    {text="25.1 УК За незаконне призначення та/або володіння малою недоторканністю (2)", penalty=2, code="25.1 УК"},
    {text="25.2 УК За незаконне призначення та/або володіння високою недоторканністю (4)", penalty=4, code="25.2 УК"},
    {text="25.3 УК За незаконне призначення та/або володіння абсолютною недоторканністю (6)", penalty=6, code="25.3 УК"},
}

local articlesChapter26 = {
    {text="26.1 УК За незаконний видобуток каменю на шахті, тобто без спеціального дозволу (1)", penalty=1, code="26.1 УК"},
    {text="26.2 УК За незаконний видобуток льону та бавовни, тобто без спеціального дозволу (1)", penalty=1, code="26.2 УК"},
}

local articlesChapter27 = {
    {text="27.1 УК За підробку будь-яких офіційних документів (4)", penalty=4, code="27.1 УК"},
}
