<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>PHONE TECH ACADEMY</title>
<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;600;800&display=swap" rel="stylesheet">
<style>
:root{--bg:#0b0d10;--sf:#161a20;--ln:#2a313b;--tx:#e8edf3;--mu:#8f9aa8;--ac:#1e90ff;--ok:#2ecc71;--er:#ff5c5c;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:light){:root:not([data-theme="dark"]){--bg:#0b0d10}}
*{box-sizing:border-box}html{scroll-padding-top:env(safe-area-inset-top,0px)}
body{margin:0;background:var(--bg);color:var(--tx);font-family:Cairo,system-ui,sans-serif;line-height:1.7}
header{display:flex;gap:10px;align-items:center;justify-content:space-between;padding:12px 16px;border-bottom:1px solid var(--ln);position:sticky;top:env(safe-area-inset-top,0px);background:var(--bg);z-index:5;flex-wrap:wrap}
.logo{font-weight:800;font-size:18px;color:var(--tx);text-decoration:none}.logo b{color:var(--ac)}
nav{display:flex;gap:6px;flex-wrap:wrap}
a.nv,button{font:inherit;color:var(--tx);background:var(--sf);border:1px solid var(--ln);border-radius:8px;padding:6px 12px;cursor:pointer;text-decoration:none}
a.nv.on,button.pri{background:var(--ac);border-color:var(--ac);color:#fff}
a:focus-visible,button:focus-visible,input:focus-visible{outline:2px solid var(--ac);outline-offset:2px}
main{max-width:900px;margin:0 auto;padding:20px 16px 60px}
h1{font-size:clamp(28px,6vw,46px);line-height:1.2;margin:.3em 0}
h2{font-size:22px;margin:1.4em 0 .5em}
.mu{color:var(--mu)}
input{width:100%;font:inherit;color:var(--tx);background:var(--sf);border:1px solid var(--ln);border-radius:8px;padding:10px 14px;margin:10px 0}
.grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(220px,1fr));gap:12px}
.card{display:block;background:var(--sf);border:1px solid var(--ln);border-radius:10px;padding:14px;color:var(--tx);text-decoration:none}
a.card:hover{border-color:var(--ac)}
.tag{display:inline-block;font-size:13px;color:var(--ac);border:1px solid var(--ac);border-radius:6px;padding:0 8px}
ol,ul{padding-inline-start:22px}
.q{background:var(--sf);border:1px solid var(--ln);border-radius:10px;padding:14px;margin:12px 0}
.q label{display:block;padding:6px 0;cursor:pointer}
.warn{border-inline-start:4px solid var(--er);background:var(--sf);padding:10px 14px;border-radius:6px}
.none{border:1px dashed var(--ln);border-radius:10px;padding:14px;color:var(--mu)}
.ib{display:inline-flex;width:44px;height:44px;border-radius:12px;align-items:center;justify-content:center;background:rgba(30,144,255,.14);color:var(--ac);margin-bottom:8px}.ib svg{width:26px;height:26px;fill:none;stroke:currentColor;stroke-width:1.6;stroke-linecap:round;stroke-linejoin:round}.ib.big{width:76px;height:76px;margin:0;border-radius:18px}.ib.big svg{width:44px;height:44px}.th{display:flex;gap:14px;align-items:center;margin:14px 0}.th h1{margin:0;font-size:clamp(24px,5vw,38px)}.hero{padding:40px 22px;border:1px solid var(--ln);border-radius:18px;background:radial-gradient(circle at 85% 0,rgba(30,144,255,.28),transparent 55%),var(--sf)}.dl{display:grid;gap:10px;grid-template-columns:repeat(auto-fit,minmax(250px,1fr))}.dl div{background:var(--sf);border:1px solid var(--ln);border-radius:10px;padding:10px 14px;font-size:15px}.dl b{display:block;color:var(--ac)}.card{transition:border-color .2s,transform .2s}a.card:hover{transform:translateY(-2px)}.wk a{margin-inline-end:6px}.logo{display:flex;align-items:center;gap:8px}.logo img{display:block;height:42px;width:auto}
.hero{display:grid;grid-template-columns:1.3fr 1fr;gap:20px;align-items:center}.hl{width:100%;max-width:320px;margin:auto;filter:drop-shadow(0 0 28px rgba(30,144,255,.5))}
.stats{display:flex;gap:10px;flex-wrap:wrap;margin-top:18px}.stats div{border:1px solid var(--ln);border-radius:10px;padding:8px 14px;background:rgba(0,0,0,.35)}.stats b{display:block;font-size:24px;color:var(--ac);line-height:1.2}.stats span{font-size:13px;color:var(--mu)}
footer{text-align:center;color:var(--mu);font-size:13px;padding:24px 16px;border-top:1px solid var(--ln)}
@media(max-width:640px){.hero{grid-template-columns:1fr}.hl{max-width:220px;order:-1}}
.ok{color:var(--ok)}.bad{color:var(--er)}
body{background:radial-gradient(1100px 480px at 50% -160px,rgba(30,144,255,.2),transparent),var(--bg);background-attachment:fixed}
header{background:rgba(11,13,16,.72);backdrop-filter:blur(14px);-webkit-backdrop-filter:blur(14px)}
a.nv{border-color:transparent;background:transparent;color:var(--mu);font-weight:600;transition:.2s}a.nv:hover{color:var(--tx)}a.nv.on{background:rgba(30,144,255,.16);color:#6cb8ff;border:1px solid rgba(30,144,255,.45)}
.hero{padding:46px 28px;position:relative;overflow:hidden;border-color:#24415f;background:linear-gradient(rgba(30,144,255,.07) 1px,transparent 1px) 0 0/32px 32px,linear-gradient(90deg,rgba(30,144,255,.07) 1px,transparent 1px) 0 0/32px 32px,radial-gradient(circle at 85% 10%,rgba(30,144,255,.38),transparent 55%),#10151c}
.hero h1{font-weight:800;background:linear-gradient(90deg,#fff,#6cb8ff);-webkit-background-clip:text;background-clip:text;color:transparent}
.hero a.nv{border:1px solid var(--ln);color:var(--tx);padding:10px 22px;border-radius:10px;background:rgba(0,0,0,.3)}.hero a.nv.on{background:linear-gradient(135deg,#1e90ff,#0a64d6);color:#fff;border-color:transparent;box-shadow:0 6px 24px rgba(30,144,255,.42)}
h2{display:flex;align-items:center;gap:10px;font-weight:800}h2:before{content:"";width:4px;height:22px;border-radius:2px;background:var(--ac)}
.card,.q{background:linear-gradient(180deg,#1a2029,#12161c)}a.card:hover{border-color:var(--ac);box-shadow:0 8px 28px rgba(30,144,255,.2)}.ib{box-shadow:inset 0 0 0 1px rgba(30,144,255,.3),0 0 18px rgba(30,144,255,.16)}
.tag.lv1{color:var(--ok);border-color:var(--ok)}.tag.lv2{color:#f5b942;border-color:#f5b942}.tag.lv3{color:#ff7a59;border-color:#ff7a59}
.steps3{display:grid;gap:12px;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));margin-top:18px}.steps3 a{display:grid;grid-template-columns:auto 1fr;gap:0 12px;align-items:center;background:var(--sf);border:1px solid var(--ln);border-radius:12px;padding:14px;color:var(--tx);text-decoration:none;transition:.2s}.steps3 a:hover{border-color:var(--ac)}.steps3 b{grid-row:span 2;width:38px;height:38px;border-radius:50%;background:var(--ac);display:flex;align-items:center;justify-content:center}.steps3 span{color:var(--mu);font-size:14px}
.q label{border-radius:8px;padding:8px 10px}.q label:hover{background:rgba(30,144,255,.1)}button:hover{border-color:var(--ac)}button.pri{box-shadow:0 6px 20px rgba(30,144,255,.35)}
ol li{margin:8px 0}ol li::marker{color:var(--ac);font-weight:800}.warn{background:rgba(255,92,92,.08)}
@media(prefers-reduced-motion:reduce){*{transition:none!important}}
</style>
</head>
<body>
<header>
<a class="logo" href="#home"><img id="lg" alt="" height="42"> PHONE TECH <b>ACADEMY</b></a>
<nav id="nav"></nav>
<button id="lang" aria-label="Language"></button>
</header>
<main id="app"></main><footer>PHONE TECH ACADEMY · Learn Mobile Repair From Zero To Professional</footer>
<script>
var L="ar";try{L=localStorage.getItem("pta-lang")||"ar"}catch(e){}
var T={
 ar:{home:"الرئيسية",tools:"الأدوات",learn:"الدروس",quiz:"اختبار",slogan:"تعلّم صيانة الهواتف من الصفر إلى الاحتراف",sub:"مكتبة أدوات وشروحات عملية ودروس متدرجة، بالعربية والإنجليزية.",search:"ابحث عن أداة…",none:"لا توجد نتائج.",steps:"طريقة الاستخدام",err:"الأخطاء الشائعة",safe:"نصائح السلامة",lvl:"مستوى الصعوبة",vid:"فيديوهات تعليمية",novid:"لا توجد فيديوهات تعليمية متاحة حالياً.",back:"رجوع إلى الأدوات",pt:"مكوّنات الأداة وأجزاؤها",st:"الإعدادات الصحيحة",wk:"الأدوات التي تعمل معها",s1:"تعرّف على الأدوات وطريقة استخدامها",s2:"تدرّج من المبتدئ إلى المحترف",s3:"اختبر نفسك واحفظ نتائجك",lv_e:"سهل",lv_m:"متوسط",lv_h:"صعب",pickq:"اختر مستوى الاختبار (5 أسئلة لكل مستوى، النجاح من 3 فأكثر)",l1:"المبتدئ",l2:"المتوسط",l3:"المحترف",soon:"قيد الإعداد",check:"صحّح الإجابات",score:"نتيجتك",reset:"إعادة الاختبار",saved:"أفضل نتيجة محفوظة",start:"ابدأ بالأدوات",qt:"اختبار: أساسيات الملتيميتر",pass:"نجحت. يمكنك الانتقال للدرس التالي.",fail:"راجع صفحة الملتيميتر ثم أعد المحاولة."},
 en:{home:"Home",tools:"Tools",learn:"Lessons",quiz:"Quiz",slogan:"Learn Mobile Repair From Zero To Professional",sub:"A library of tools, practical guides and graded lessons in Arabic and English.",search:"Search for a tool…",none:"No results.",steps:"How to use",err:"Common mistakes",safe:"Safety tips",lvl:"Difficulty",vid:"Video tutorials",novid:"No tutorial videos are available right now.",back:"Back to tools",pt:"Components and parts",st:"Correct settings",wk:"Works together with",s1:"Learn the tools and how to use them",s2:"Progress from beginner to professional",s3:"Test yourself and keep your scores",lv_e:"Easy",lv_m:"Medium",lv_h:"Hard",pickq:"Choose a level (5 questions each, pass with 3 or more)",l1:"Beginner",l2:"Intermediate",l3:"Professional",soon:"In preparation",check:"Check answers",score:"Your score",reset:"Retake quiz",saved:"Best score saved",start:"Browse tools",qt:"Quiz: Multimeter basics",pass:"Passed. You can move to the next lesson.",fail:"Review the multimeter page and try again."}
};
var TOOLS=[
{id:"multimeter",n:["الملتيميتر","Multimeter"],c:["أجهزة القياس والفحص","Measurement"],lv:["مبتدئ","Beginner"],
 d:["جهاز يقيس الجهد والمقاومة والاستمرارية، وهو أول أداة لتشخيص أعطال الدوائر.","A device that measures voltage, resistance and continuity. It is the first tool for diagnosing circuit faults."],
 s:[["اختر وضع القياس المناسب (فولت، أوم، أو استمرارية).","Select the right mode (volts, ohms or continuity)."],["وصّل المجس الأسود بمنفذ COM والأحمر بمنفذ الفولت/الأوم.","Plug the black probe into COM and the red into the V/Ω port."],["للاستمرارية: افصل الطاقة ولامس طرفي المسار؛ الصفير يعني اتصالاً.","For continuity: power off, touch both ends of the trace; a beep means a connection."],["للجهد: المجس الأسود على الأرضي والأحمر على نقطة القياس.","For voltage: black probe on ground, red on the test point."]],
 e:[["قياس المقاومة والبورد تحت الطاقة.","Measuring resistance while the board is powered."],["استخدام مجسات سميكة على نقاط دقيقة فيحدث ماس كهربائي.","Using thick probes on tiny pads, causing shorts."]],
 f:[["افصل البطارية قبل قياس المقاومة أو الاستمرارية.","Disconnect the battery before resistance or continuity tests."]]},
{id:"hotair",n:["محطة الهواء الساخن","Hot Air Station"],c:["أجهزة اللحام","Soldering"],lv:["متوسط","Intermediate"],
 d:["تسخّن المكونات الصغيرة بتيار هواء لرفعها أو لحامها دون لمسها.","Heats small components with an air stream to remove or solder them without touching them."],
 s:[["ثبّت الهاتف على سطح مقاوم للحرارة وأزل البطارية.","Secure the phone on a heat-resistant surface and remove the battery."],["اضبط الحرارة والتدفق تدريجياً حسب المكوّن.","Set temperature and airflow gradually to suit the component."],["ضع الفلكس وحرّك الفوهة بحركة دائرية فوق المكوّن.","Apply flux and move the nozzle in small circles above the part."],["ارفع المكوّن عندما يلين اللحام ثم اترك اللوحة تبرد.","Lift the part once the solder flows, then let the board cool."]],
 e:[["حرارة عالية جداً تتلف المكونات المجاورة.","Too much heat damages nearby components."],["تثبيت الفوهة في مكان واحد.","Holding the nozzle still in one spot."]],
 f:[["الفوهة ساخنة جداً؛ لا تلمسها. اعمل في مكان جيد التهوية.","The nozzle is very hot; never touch it. Work in a ventilated area."]]},
{id:"solderingiron",n:["كاوي اللحام","Soldering Iron"],c:["أجهزة اللحام","Soldering"],lv:["متوسط","Intermediate"],
 d:["أداة لصهر القصدير وربط الأسلاك والمكونات بالنقاط النحاسية.","A tool that melts solder to join wires and components to copper pads."],
 s:[["سخّن الكاوي ثم نظّف الرأس وغطّه بطبقة رقيقة من القصدير.","Heat the iron, clean the tip and tin it with a thin layer of solder."],["ضع الرأس على النقطة والطرف معاً لثوانٍ قليلة.","Touch the tip to pad and lead together for a few seconds."],["غذِّ اللحام على الوصلة لا على الرأس.","Feed solder onto the joint, not the tip."],["ارفع الكاوي واترك الوصلة تبرد دون تحريك.","Remove the iron and let the joint cool undisturbed."]],
 e:[["إطالة اللمس فيتلف المسار.","Touching too long lifts the pad."],["رأس متسخ يمنع انتقال الحرارة.","A dirty tip blocks heat transfer."]],
 f:[["ضع الكاوي دائماً على حامله وافصله عن الكهرباء بعد العمل.","Always rest the iron in its stand and unplug it after use."]]},
{id:"pry",n:["أدوات فتح الشاشات","Screen Opening Tools"],c:["أدوات الفك والتركيب","Disassembly"],lv:["مبتدئ","Beginner"],
 d:["شفرات وأدوات بلاستيكية رفيعة لفصل الشاشة والغطاء عن الهيكل دون كسر.","Thin blades and plastic picks that separate the screen and back cover from the frame without breaking them."],
 s:[["أزل البراغي المرئية وسخّن الحواف لتليين اللاصق.","Remove visible screws and warm the edges to soften adhesive."],["أدخل الشفرة الرقيقة من الحافة بعمق أقل من 3 مم.","Insert the thin blade at the edge, less than 3 mm deep."],["اقطع اللاصق تدريجياً حول المحيط بأداة بلاستيكية.","Slide around the perimeter gradually with a plastic pick."],["افتح الشاشة ببطء وافصل كابل البطارية أولاً.","Lift the screen slowly and disconnect the battery connector first."]],
 e:[["إدخال الشفرة عميقاً فتتقطع الكابلات.","Inserting the blade too deep and cutting flex cables."]],
 f:[["لا تثقب البطارية أبداً؛ فهي قابلة للاشتعال.","Never puncture the battery; it can catch fire."]]},
{id:"tweezers",n:["الملاقط الدقيقة","Precision Tweezers"],c:["أدوات الفك والتركيب","Disassembly"],lv:["مبتدئ","Beginner"],
 d:["ملاقط لالتقاط البراغي والمكونات الصغيرة. يُفضَّل مضادة للكهرباء الساكنة.","Tweezers for picking up screws and tiny parts. Anti-static types are preferred."],
 s:[["اختر شكل الرأس المناسب (مدبب أو مسطح أو منحنٍ).","Pick the tip shape: pointed, flat or curved."],["أمسك الملقاط كالقلم وبضغط خفيف.","Hold it like a pen, with light pressure."],["التقط المكوّن من حافته لا من وسطه.","Grab a part by its edge, not its centre."]],
 e:[["ضغط شديد يقذف البراغي بعيداً.","Squeezing too hard launches screws away."]],
 f:[["لا تستخدم ملاقط معدنية قرب البطارية المتصلة.","Avoid metal tweezers near a connected battery."]]},
{id:"microscope",n:["الميكروسكوب الإلكتروني","Digital Microscope"],c:["أجهزة الرؤية والفحص","Inspection"],lv:["محترف","Professional"],
 d:["يكبّر اللوحة لرؤية المسارات والوصلات الدقيقة وفحص جودة اللحام.","Magnifies the board so you can inspect fine traces and solder joints."],
 s:[["ثبّت اللوحة وفعّل الإضاءة الحلقية.","Fix the board and switch on the ring light."],["اضبط التركيز بدءاً من أقل تكبير.","Focus starting from the lowest magnification."],["ازداد التكبير تدريجياً حتى ترى الوصلة المطلوبة.","Increase magnification until the joint is clear."]],
 e:[["إضاءة قوية تسبب انعكاساً يخفي التفاصيل.","Harsh light causes glare that hides detail."]],
 f:[["ارفع العدسة قبل تحريك اللوحة لتجنب الاصطدام.","Raise the lens before moving the board to avoid contact."]]}
];
var LV=[["l1",["مقدمة في صيانة الهواتف","التعرف على أجزاء الهاتف","التعرف على أدوات الصيانة","أساسيات الكهرباء والإلكترونيات","التعرف على الملتيميتر","أساسيات فك وتركيب الهواتف"],["Intro to phone repair","Parts of a phone","Repair tools","Electricity and electronics basics","Meet the multimeter","Disassembly basics"]],
["l2",["تغيير الشاشات","تغيير البطاريات","إصلاح منافذ الشحن","إصلاح المايك والسماعة","أعطال الإضاءة","أعطال الشحن","أساسيات اللحام","قراءة المخططات"],["Screen replacement","Battery replacement","Charging port repair","Mic and speaker repair","Backlight faults","Charging faults","Soldering basics","Reading schematics"]],
["l3",["إصلاح اللوحة الأم","إصلاح المسارات المقطوعة","تغيير الآيسيهات","تشخيص الأعطال المعقدة","تحليل الدوائر الإلكترونية","إصلاح أعطال الشبكة","الميكروسكوب والباور سبلاي","صيانة اللوحات المتقدمة"],["Motherboard repair","Repairing broken traces","IC replacement","Complex fault diagnosis","Circuit analysis","Network faults","Microscope and power supply","Advanced boards"]]];
var QL="e";var QZ={
e:[{q:["أي أداة تقيس الجهد والمقاومة؟","Which tool measures voltage and resistance?"],o:[["الملتيميتر","Multimeter"],["الملقاط","Tweezers"],["كاوي اللحام","Soldering iron"]],a:0},
{q:["أي أداة تلتقط البراغي الصغيرة؟","Which tool picks up tiny screws?"],o:[["الميكروسكوب","Microscope"],["الملقاط الدقيق","Precision tweezers"],["الملتيميتر","Multimeter"]],a:1},
{q:["أول خطوة قبل فتح الهاتف للإصلاح:","First step before opening a phone for repair:"],o:[["إطفاء الهاتف","Power the phone off"],["تسخين اللوحة","Heat the board"],["فتح الشاشة بقوة","Force the screen open"]],a:0},
{q:["لماذا نفضّل أدوات الفتح البلاستيكية؟","Why prefer plastic opening tools?"],o:[["لتجنب الخدش والماس الكهربائي","To avoid scratches and shorts"],["لتسخين الشاشة","To heat the screen"],["لأنها تقطع المعدن","Because they cut metal"]],a:0},
{q:["هل يُلمس رأس الكاوي أثناء عمله؟","Can you touch a working iron tip?"],o:[["نعم","Yes"],["لا، فهو شديد السخونة","No, it is extremely hot"],["فقط بقفاز قماشي","Only with a cloth glove"]],a:1}],
m:[{q:["ما وظيفة الفلكس في اللحام؟","What does flux do in soldering?"],o:[["يلوّن الوصلة","Colours the joint"],["يساعد القصدير على الانسياب ويزيل الأكاسيد","Helps solder flow and removes oxides"],["يبرّد الكاوي","Cools the iron"]],a:1},
{q:["قبل قياس المقاومة داخل اللوحة:","Before measuring resistance on a board:"],o:[["افصل الطاقة والبطارية","Disconnect power and battery"],["شغّل الهاتف","Power the phone on"],["اشحن الهاتف","Charge the phone"]],a:0},
{q:["لماذا يُخفَّض تدفق الهواء قرب المكونات الصغيرة؟","Why lower airflow near small parts?"],o:[["لتتطاير أسرع","So they blow away faster"],["لئلا تتطاير أو تتحرك","So they do not blow away or shift"],["لتبرد اللوحة","To cool the board"]],a:1},
{q:["وضع الديود في الملتيميتر يفحص:","Diode mode on a multimeter tests:"],o:[["الديودات ومسارات الحماية","Diodes and protection paths"],["قوة الإشارة","Signal strength"],["سعة التخزين","Storage size"]],a:0},
{q:["إطالة ملامسة الكاوي للنقطة قد تسبب:","Leaving the iron on a pad too long can:"],o:[["تقوية الوصلة","Strengthen the joint"],["رفع المسار النحاسي","Lift the copper pad"],["لا شيء","Do nothing"]],a:1}],
h:[{q:["لماذا قد تكون المقاومة داخل اللوحة غير دقيقة؟","Why can in-circuit resistance be inaccurate?"],o:[["بسبب مسارات موازية عبر مكونات أخرى","Parallel paths through other components"],["لأن المجسات ملونة","Probes are coloured"],["لأن الشاشة مفتوحة","The screen is open"]],a:0},
{q:["قراءة قريبة من صفر أوم بين خط التغذية والأرضي تدل غالباً على:","A near-zero ohm reading between a supply rail and ground usually means:"],o:[["لوحة سليمة","A healthy board"],["ماس كهربائي","A short circuit"],["بطارية مشحونة","A charged battery"]],a:1},
{q:["منفذ 10A في الملتيميتر يُستخدم لـ:","The 10A port on a multimeter is for:"],o:[["قياس الجهد","Measuring voltage"],["التيار العالي فقط","High current only"],["فحص الاستمرارية","Continuity checks"]],a:1},
{q:["قراءة ديود سليم بالاتجاه المعاكس تكون عادة:","A healthy diode read in reverse typically shows:"],o:[["OL (لا توصيل)","OL (no conduction)"],["صفر","Zero"],["صفير مستمر","A steady beep"]],a:0},
{q:["احتياط حماية المكونات المجاورة عند الهواء الساخن:","Protecting neighbouring parts when using hot air:"],o:[["رفع الحرارة للأقصى","Max out the heat"],["تغطيتها بشريط مقاوم للحرارة وخفض الهواء","Cover with heat-resistant tape and lower airflow"],["إزالة الفلكس","Remove all flux"]],a:1}]};
var LOGO="data:image/png;base64,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
