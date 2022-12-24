#                            CSS Important topic
## িসেলর হল সাধারণ HTML এিলেম (h1h6, p etc)
িডকলােরশেনর আবার ইিট অংশ থাকেব-
Declaration={Properties: Value}
একািধক Declaration থাকেত পাের যা সিমেকালন িদেয় পৃথক থাকেব।
আরও সহজ ভােব লখা যায়-
"HTML tag" { "CSS Property" : "Value" ; }
াইলশীট ববহােরর পিতঃ
এইচিটএমএল ডকুেমে াইলশীট ববহােরর িতনিট পিত রেয়েছ - internal, external এবং inline। একটা
এইচিটএমএল পেজ <head> টােগর িভতর <style> টাগ িদেয় িসএসএস কাড যাগ কের পজ াইিলং করা
যায়-এটা হে ইারনাল িসএসএস। আর যিদ িসএসএস কাড বিশ হেয় যায় তখন িসএসএস কাড আলাদা ফাইেল
লখা হয় এবং <head> টােগর িভতর <link> টাগ িদেয় সংযু করা হয়-এই পিত হে এটানাল িসএসএস।
আমরা ওেয়ব পজ িডজাইন করেত এটানাল িসএসএস বিশ ববহার করব। আর এইচিটএমএল-এর িতটা
এিলেমের সােথ এককভােব াইল িনধারণ করা হল-ইনলাইন িসএসএস। য কান এইচিটএমএল ডকুেমে আপিন
াইলশীট ববহার করেত পােরন।এখন আমরা ধরাবািহকভােব এই িতনিট পিত িনেয় আেলাচনা করবঃ
১.ইারনাল িসএসএসঃ
ইারনাল িসএসএস সাধারণত তখনই ববহার করা হয় যখন একিট এইচিটএমএল ডকুেমের জন একিট িডজাইন
দরকার। ইারনাল িসএসএস-এ <head> টােগর িভতর <style> টাগ িদেয় িসএসএস কাড যাগ করা হয়।যমন-
<html>
<head>
<style type="text/css">
h1{color:#ff00ff;}
12














</body>
</html>
১১. হায়াইট স পািটঃ
হায়াইট স পািটর মাধেম একিট লখা এক লাইেন চলেত থাকেব যতন না আপিন break <br /> টাগ না
িদেবন। </br> টাগ িদেল তারপর থেক িনেচ লাইন যােব।
white-space propertyয মানেলা ববহার করেত পাের-
ভলু
normal
nowrap
Pre
pre-line
pre-wrap
বণনা
পাশাপািশ অেনকেলা whitespace একিট whitespace-এ পিরণত হেব। টট মুিড়েয়(
wrap) যােব যখন েয়াজন। এটা িডফ ।
পাশাপািশ অেনকেলা whitespace একিট whitespace-এ পিরণত হেব। টট মুিড়েয়
পিরবতী লাইেন যােব না । িক এক লাইেন চলেত চলেত যিদ <br /> টাগ পায় তেব মুিড়েয় যােব।
কািডং-এ যতেলা Whitespace থাকেব তার সবই াউজাের দখা যােব।
Text will only wrap on line breaks Acts like the <pre> tag in HTML
পাশাপািশ অেনকেলা whitespace একিট whitespace-এ পিরণত হেব। টট মুিড়েয়(
wrap) যােব যখন েয়াজন হেব িক লাইন ক হেব না।
কািডং-এ যতেলা Whitespace থাকেব তার সবই াউজাের দখা যােব। টট মুিড়েয়(
wrap) যােব যখন েয়াজন হেব িক লাইন ক হেব না।
একিট উদাহরণ দখুন-
<html>
<head>
<style type="text/css">
p
{
white-space:nowrap;
}
27
</style>
</head>
<body>
<p>
This is some text. This is some text. This is some text.
This is some text. This is some text. This is some text.
This is some text. This is some text. This is some text.
This is some text. This is some text. This is some text.
</p>
</body>
</html>
১২.ওয়াড িসং পািটঃ
Word Spacing property-এর মাধেম পাশাপািশ শেলার মেধ white space এর পিরমান কমােনা
বা বাড়ােনা যায়। এর মান px, pt, cm, em একেক হেত পাের। নেগিটভ মান ববহার করা যেত পাের।
একিট উদাহরণ দখুন-
<html>
<head>
<style type="text/css">
p
{
word-spacing:30px;
}
</style>
</head>
<body>
28
<p>
This is some text. This is some text.
</p>
</body>
</html>
আউটপুটঃ
অধায়-িতন
[িসএসএস পিরমাপক পািট ]
এইচিটএমএল- এ আমরা height ও width এিিবউেটর মাধেম িবিভ এিলেমের আকার িনধারণ কের
িদেয়িছ। িক আমরা যখন িসএসএস িশখব তখন এইচিটএমএল িদেয় এই কাজেলা আর করব না। িসএসএস-এ মাট
ছয়িট পািটর সাহােয কান এিলেমের আকার িনধারণ করা হয়। এই ছয়িট পািটর মােঝ মূলত ১ ও ৬ নাারটাই
বিশ ববহার করা হয়।
পািট
1.height
2.max-height
3.max-width
4.min-height
5.min-width
িসএসএস-এর সকল আকার িনধারক পািট
বণনা
এিলেমের height িনেদশ কের
এিলেমের সরেা height িনেদশ কের
এিলেমের সরেা width িনেদশ কের
এিলেমের সরিন height িনেদশ কের
এিলেমের সরিন width িনেদশ কের
মান
auto
length
%
none
length
%
none
length
%
length
%
length
%
29
6.width
এিলেমের width িনেদশ কের
auto
length
%
উপেরর এই ছয়িট পািটেত ববত ভলু েলার মান ও বণনা িনে দওয়া হল-
None No maximum height, maximum width. এটা িডফ মান।
Auto াউজার িনেজই হাইট কালকুেলট কের। এটা িডফ মান।
Length px, cm একক ববহার কের।
% পুেরা উইেা কনেটের জন িসেল হেব।
ধারাবািহকভােব িনে এেদর আেলাচনা করা হলঃ
1+6.height and width Property:
কান এিলেমের height ও width িনণয় করা হয় এই পািট েয়র ারা। যমন-
<html>
<head>
<style type="text/css">
div{ height:250px; width:200px; background:#887733}
</style>
</head>
<body>
<div><h3>This is a Block</h3></div>
</body>
</html>
আউটপুটঃ
30
2.CSS max-height Property:
এিলেমের সরেা হাইট িনেদশ কের। যমন-
<html>
<head>
<style type="text/css">
p{max-height:50px; background-color:yellow;}
</style>
</head>
<body>
<p>The maximum height of this paragraph is set to 50px. The maximum
height of this paragraph is set to 50px. The maximum height of this
paragraph is set to 50px. The maximum height of this paragraph is set to
50px. The maximum height of this paragraph is set to 50px. The maximum
height of this paragraph is set to 50px. The maximum height of this
paragraph is set to 50px. The maximum height of this paragraph is set to
50px. The maximum height of this paragraph is set to 50px. The maximum
height of this paragraph is set to 50px.</p>
31
</body>
</html>
3.CSS max-width Property:
এিলেমের max-width িনেদশ কের। যমন-
<html>
<head>
<style type="text/css">
p{max-width:100px; background-color:yellow;}
</style>
</head>
<body>
<p>The maximum width of this paragraph is set to 100px.</p>
</body>
</html>
4.CSS min-height Property:
এিলেমের min-height িনেদশ কের। যমন-
<html>
<head>
<style type="text/css">
32
p
{
min-height:100px;
background-color:yellow;
}
</style>
</head>
<body>
<p>The minimum height of this paragraph is set to 100px.</p>
</body>
</html>
5.CSS min-width Property:
এিলেমের min-width িনেদশ কের। যমন-
<html>
<head>
<style type="text/css">
p{min-width:150px; background-color:yellow;}
33
</style>
</head>
<body>
<p>The minimum width of this paragraph is set to 150px.</p>
</body>
</html>
অধায়-চার
[ফ পািট ]
আমার লখা এইচিটএমএল বইিটেত আিম বেলিছলাম ফের পিরপূণ িনয়ন পাওয়া যােব িসএসএস ববহােরর সময়।
ফ ওেয়ব পেজর জন অত পূণ একিট িবষয়। ওেয়ব পেজর অিধকাংশ জায়গা জুেড় ফ িবদমান তাই একিট
সুর ও আকষণীও ওেয়ব পজ তিরর জন ফের  অপিরসীম। এ অধােয় আমরা ফ সিকত যাবতীয় িবষয়
আেলাচনা করেবা। িসএসএস- এ ফ সিকত ছয়িট পািট সট করা যেত পাের। এেলা হলঃ
পািট
1.font
2.font-family
3.font-size
4.font-style
5.font-variant
6.font-weight
বণনা
সকল font properties-এর জন একিট িডকলােরশন।
টেটর জন font family িনধারণ কের।
টেটর জন font size িনধারণ কের।
টেটর জন font style িনধারণ কের।
ফ Variant এর সাহােয আপিন ফ ক small caps এ পিরবিতত করেত
পােরন।
একিট ফ কী পিরমাণ মাটা দখা যােব তা বাঝােনার জন ববহার করা হয় font-
weight পািট।
িতিট পািট সেক িনেচ আেলাচনা করা হলঃ
১.ফ পািটঃ
ফের িবিভ পািটর মান িভ িভ িডকলােরশেন না িদেয় একই িডকলােরশেনর মাধেম লখার জন font-
property ববহার করা হয়। যমনঃ একিট সাধারণ িডকলােরশন-
p{
34
font-size:larger;
font-style:italic;
font:varient:small-caps;
font-family:Arial;
}
font-property ববহার কের সহজভােব িনেচর মত লখা যায়-
p{font: larger italic small-caps Arial }
িতিট মানেক স িদেয় আলাদা করেত হেব।
একিট উদাহরণ দখুনঃ
<html>
<head>
<style type="text/css">
p{font:15px arial,sans-serif;}
</style>
</head>
<body>
<p >This is a paragraph. This is a paragraph. This is a paragraph. This is a
paragraph. This is a paragraph. This is a paragraph. This is a paragraph. This
is a paragraph.</p>
</body>
</html>
35
২.ফ ফােমিল পািটঃ
কান ফ ফােমিল বা ফ প ববহার করেত চান তা িনেদশ করেত পােরন এ পািটর মাধেম। [ফ ফােমিল বা
ফ প এবং জেনিরক ফ ফােমিল সেক িবািরত জানেত আমার লখা এইচিটএমএল বইিট পড়ুন]
একিট উদাহরণ দখুনঃ
<html>
<head>
<style type="text/css">
p{font-family:"Times New Roman",Times,serif;}
</style>
</head>
<body>
<h1>CSS font-family</h1>
<p >This is a paragraph, shown in the Times New Roman font.</p>
</body>
</html>
ফের নােমর মােঝ স থাকেল তােক অবশই উিিত িচের মােঝ রাখেত হেব। অন ে এই িনয়ম না মানেলও
চলেব। তেব উিিত িচ ববহার করা উম। Single অেনকেলা ফ একসােথ ববহােরর িনয়ম-
h1{font-family:”Arial Black”,Arial}
এেে আপিন জেনিরক ফ ফােমিলর নাম ও ববহার করেত পােরন।
িসএসএস-এ ই ধরেণর ফ ফেমিল নাম রেয়েছ-
1.family-name – ফের নাম।যমন-Arial, times new roman ইতািদ।
2.generic-family – জেনিরক ফ ফেমিলর নাম। যমন-serif, sans-serif ইতািদ। গেবষনায় দখা
িগেয়েছ serif fonts হেত sans-serif fonts যা computer monitor এ খুব সহেজ পড়া যায় ।
36
৩.ফ সাইজ পািটঃ
ফের আকার িনধারণ করা হয় font-size পািটর মাধেম। এই পািটর জন চার ধরেণর মান ববহার করা যেত
পাের- অাবসুেলট, আেপিক, শতকরা ও দঘ।
অাবসুেলট সাইজঃ
কান াউজাের টট সাইজ পিরবতেনর সুেযাগ দয় না। এটা accessibility এর জন একিট বড় সমসা। যিদ
আউটপুট সাইজ আেগই জানা থােক তেব অাবসুেলট সাইজ ববহার করা যেত পাের।
আেপিক সাইজঃ টট সাইজ পিরবতেনর সুেযাগ দয়।
নাটঃ আপিন যিদ font size specify কের না দন তেব িডফ ফের য সাইজ তাই দখা যােব। আর এই
িডফ সাইজ হল- 16px (16px=1em).
font size property-য সকল মান ববহার করেত পাের-
ভলু
xx-small ফ সাইজ হেব xx-small সাইজ
x-small ফ সাইজ হেব extra small সাইজ
small
ফ সাইজ হেব small সাইজ
medium ফ সাইজ হেব medium size. এটা িডফ।
large
ফ সাইজ হেব large size
x-large ফ সাইজ হেব extra large size
xx-large ফ সাইজ হেব xx-large size
আেপিক মানঃ আেগর উপাদােনর সােপে বতমান উপাদােনর আকার ছাট বা বড় হেয় থােক।
smaller parent এিলেমের চেয় ছাট আকােরর ফ পেত এই মান ববহার করেত হেব।
larger parent এিলেমের চেয় বড় আকােরর ফ পেত এই মান ববহার করেত হেব।
দঘ মান
length
িনি সাইেজর ফ পেত px, cm, etc একক ববহার করা হয়।
শতকরা মান
% parent এিলেমের সােপে ফ সাইজ িনধারণ করা হয়।
একিট উদাহরণ দখুনঃ
<html>
37
বণনা
অাবসুেলট মান
<head>
<style type="text/css">
h1 {font-size:250%;}
h2 {font-size:20px;}
p {font-size:4em;}
</style>
</head>
<body>
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<p>This is a paragraph.</p>
</body>
</html>
আউটপুটঃ
৪.ফ াইল পািটঃ
ফেফস অথাৎ ফিট কমন দখা যােব তার জন ববহার করা হয় font-style পািট। এর িতনিট ভালু হেত
আেছ-
ভলু
normal
italic
াভািবক ফেফস দখােব। এটা default
ইটািলক দখােব।
38
বণনা
oblique ফেফস Oblique ভাসেন দখােব।
একিট উদাহরণ দখুনঃ
<html>
<head>
<style type="text/css">
p.normal {font-style:normal;}
p.italic {font-style:italic;}
p.oblique {font-style:oblique;}
</style>
</head>
<body>
<p class="normal">This is a paragraph, normal.</p>
<p class="italic">This is a paragraph, italic.</p>
<p class="oblique">This is a paragraph, oblique.</p>
</body>
</html>
আউটপুটঃ
39
৫.ফ ভািরেয় পািটঃ
font-variant property িনধারণ কের আপনার ফ small-caps-এ দখােব িক দখােব না। িসএসএস
ফ Variant এর সাহােয আপিন ফ ক small caps এ পিরবিতত করেত পােরন। small-caps বলেত
বুঝায় বড় হােতর অরেলার সাইজ হেব ছাট হােতর অেরর সাইেজর সমান। এর িট ভলু হেত পাের-
ভলু
normal
বণনা
াউজার সাধারণ ফ কাশ করেব। এটা িডফ মান।
small-caps এটা ববহাের বড় হােতর অরেলার সাইজ হেব ছাট হােতর অেরর সাইেজর সমান।
একিট উদাহরণ দখুনঃ
<html>
<head>
<style type="text/css">
p.normal {font-variant:normal;}
p.small {font-variant:small-caps;}
</style>
</head>
<body>
<p class="normal">My name is Hege Refsnes.</p>
<p class="small">My name is Hege Refsnes.</p>
</body>
</html>
আউটপুটঃ
40
অেনক ফের ে small-caps ভািরয়া থােক না । যিদ কান ফের লকাপ ভাসন পাওয়া না যায় তেব তা
বড় হােতর অর ববহার কের।
৬.ফ ওেয়ট পািটঃ
একিট ফ কী পিরমাণ মাটা দখা যােব তা বাঝােনার জন ববহার করা হয় font-weight পািট। সাধারণত
িবিভ ফের bold, dark, heavy ইতািদ ভাসন থােক। তাই এসব শ িদেয় font-weight কাশ না কের
িসএসএেস font-weight পািটর মান িনেদশ করা হয় সংখা িদেয়। যমন- ৪০০ অথ হল নরমাল ফ, ৭০০িহল
বা। এসব সংখা ছাড়াও কেয়কিট কীওয়াডএর মাধেম মান িনেদশ করা যেত পাের।এেলা হল-lighter,
bolder, normal এবং bold। lighter ও bolder ববহার করা হেল াউজার normal ও বা ভাসেনর
কাছাকািছ ফ ভাসন ববহার করেব। যমন-
ভলু
normal
bold
font-weight property-য সকল মান ববহার কের-
বণনা
নরমাল characters িডফাইন কের। এটা িডফ।
বা characters িডফাইন কের।
bolder Defines thicker characters
lighter Defines lighter characters
একিট উদাহরণ দখুনঃ
<html>
<head>
<style type="text/css">
p.normal {font-weight:normal;}
p.light {font-weight:lighter;}
p.thick {font-weight:bold;}
41
p.thicker {font-weight:900;}
</style>
</head>
<body>
<p class="normal">This is a paragraph.</p>
<p class="light">This is a paragraph.</p>
<p class="thick">This is a paragraph.</p>
<p class="thicker">This is a paragraph.</p>
</body>
</html>
আউটপুটঃ
42
অধায়-পঁাচ
[িল পািট]
িসএসএস িল পািট unordered, ordered এমনিক ইেমজেকও List Marker িহেসেব ববহােরর
সুেযাগ দয়। ।িসএসএস িদেয় িল ক এইচিটএমএল হেত অেনক বিশ কামাইজ করা যায়। এ অধােয় আমরা িল
িনেয় যাবতীয় িকছু আেলাচনা করেবা।
পািট
1.list-style
িলের জন ববত সকল পািটঃ
বণনা
list-style property একিট িডকলােরশেনই সকল list properties ক তুেল
ধের
2.list-style-image list-style-image property িল আইেটমেক ইেমজ ারা িরেস কের।
3.list-style-
position
list-style-position property িনধারণ কের িলের আইেটমেলা াভািবক অবা
থেক inside না Outside-এ থাকেব।
4.list-style-type
default number-এর ordered বা unordered িল
এর bullets/discs হেত িভ াইল ববহার করা যায়।
িনে সকল পািট িনেয় িবািরত আেলাচনা করা হলঃ
১.িল াইল পািটঃ
list-style property একিট িডকলােরশেনই সকল list properties ক তুেল ধের। আর এই list-
style-type এর মাধেম এমন একটা ববা করা যায় যখন আপনার list-style image লাড িনেব না তখন
অন list-style দখােব। list-style shorthand property ববহােরর ম হল-
list-style-type> list-style-position >list-style-image
যিদ কান পািটর ভলু বাদ যায় তেব কান সমসা হেব না। এেে ঐ পািটর িডফ ভলু ধের নওয়া হেব।
একিট উদাহরণ দখুনঃ
<html>
<head>
<style type="text/css">
43
ul {list-style:square url("sqpurple.gif");}
</style>
</head>
<body>
<ul>
<li>Coffee</li>
<li>Tea</li>
<li>Coca Cola</li>
</ul>
</body>
</html>
আউটপুটঃ
যিদ ইেমজ লাড না হয় তেব িনেচর মত আউটপুট দখােব।
২.িল াইল ইেমজ পািটঃ
44
ইেমজেক list item marker িহেসেব দখােত list-style-image property ববহার করা হয়। list-
style-image property িল আইেটমেক ইেমজ ারা িরেস কের। .কান কারেণ ইেমজ লাড না হেল এই
পািট ববহার করা হয়। সাধারণত image ক bullet points িহসােব unordered িল এর জন ববহার
করা যায়।normal bullet এর পিরবেত image ক ববহার করা যায়।সবেচেয় ভাল হয় Unordered
িল এর ে image ক ববহার করা। িনেচর উদাহরণ দখুনঃ
<html>
<head>
<style type="text/css">
ul {list-style-image:url('sqpurple.gif');}
</style>
</head>
<body>
<ul>
<li>Coffee</li>
<li>Tea</li>
<li>Coca Cola</li>
</ul>
</body>
</html>
আউটপুটঃ
45
যিদ ইেমজ লাড না হয় তেব িনেচর মত আউটপুট দখােব।
৩.িল াইল পিজশান পািটঃ
list-style-position property িনধারণ কের িলের আইেটমেলা াভািবক অবা থেক inside না
Outside-এ থাকেব। list-style-position এর ভলু inside িদেল তখন িলেলা মািজন হেত িভতেরর
িদেক থাকেব আর Outside িদেল normal িল Position এ থাকেব। Outside ভলুিট একিট default
ভালু।
ul { list-style-position: inside; }
ol { list-style-position: outside; }
একিট উদাহরণ দখুনঃ
<html>
<head>
<style type="text/css">
ul.a {list-style-position:inside;}
ul.b {list-style-position:outside;}
</style>
</head>
<body>
<p>The following list has list-style-position: inside:</p>
<ul class="a">
46
<li>Earl Grey Tea - A fine black tea</li>
<li>Jasmine Tea - A fabulous "all purpose" tea</li>
<li>Honeybush Tea - A super fruity delight tea</li>
</ul>
<p>The following list has list-style-position: outside:</p>
<ul class="b">
<li>Earl Grey Tea - A fine black tea</li>
<li>Jasmine Tea - A fabulous "all purpose" tea</li>
<li>Honeybush Tea - A super fruity delight tea</li>
</ul>
<p>"list-style-position: outside" is the default setting.</p>
</body>
</html>
আউটপুটঃ
47
৪.িল াইল টাইপ পািটঃ
আপিন যিদ default number এর ordered িল বা unordered িল এর bullets/discs হেত
িভ াইল ববহার করেত চান তাহেল আপিন িল এর জন িবিভ ধরেনর াইল ববহার করেত পােরন। এই
কাজিট করা হয় িনেচ list-style-type property-এর মাধেম। যমনঃ
ol { list-style-type: upper-roman; }
ul { list-style-type: circle; }
একিট উদাহরণ দখুনঃ
<html>
<head>
<style type="text/css">
ul.a {list-style-type:circle;}
ul.b {list-style-type:square;}
ol.c {list-style-type:upper-roman;}
ol.d {list-style-type:lower-alpha;}
</style>
</head>
<body>
<p>Example of unordered lists:</p>
<ul class="a">
<li>Coffee</li>
<li>Tea</li>
<li>Coca Cola</li>
48
</ul>
<ul class="b">
<li>Coffee</li>
<li>Tea</li>
<li>Coca Cola</li>
</ul>
<p>Example of ordered lists:</p>
<ol class="c">
<li>Coffee</li>
<li>Tea</li>
<li>Coca Cola</li>
</ol>
<ol class="d">
<li>Coffee</li>
<li>Tea</li>
<li>Coca Cola</li>
</ol>
49
</body>
</html>
আউটপুটঃ
list-style-type property য সকল ভলু ববহার করেত পাের তােদর নাম ও বণনা িনে দওয়া হলঃ
ভলু
বণনা
armenian
circle
cjk-ideographic
decimal
decimal-leading-zero
disc
georgian
hebrew
hiragana
hiragana-iroha
katakana
katakana-iroha
Armenian numbering িচ কাশ কের।
Circle িচ কাশ কের।
plain ideographic numbers িচ কাশ কের।
াভািবক নাার কাশ কের। এটা <ol> এর জন িডফ।
নাােরর েত ০ থাকেব (01, 02, 03, ইতািদ.)
ভরাট বৃ কাশ কের।এটা <ul> এর জন িডফ।
Georgian numbering িচ কাশ কের।
Hebrew numbering িচ কাশ কের।
Hiragana numbering িচ কাশ কের।
Hiragana iroha numbering িচ কাশ কের।
Katakana numbering িচ কাশ কের।
Katakana iroha numbering িচ কাশ কের।
50
lower-alpha
lower-greek
ছাট হােতর অর কাশ কের (a, b, c, d, e ইতািদ)
ছাট হােতর ীক অর কাশ কের
lower-latin
lower-roman
none
square
upper-alpha
upper-latin
upper-roman
অধায়-ছয়
[িলংক পািট]
িসএসএস এর মাধেম এনকর টাগ বা িলংেক আমরা ইেফ যাগ করেত পাির। িলংেক িবিভ CSS property
(color, font-family, background, etc.) ববহার কের িবিভ াইল িনধারণ করা যায়। িক িলের
শাল াইল িনধারণ করা হয় িলের অবার উপর িভি কের।
িলের চারিট অবা হল-
 a:linkএকিট সাধারণ িলংক যা িভিজট করা হয় িন।
 a:visitedএকটা িলংক যা পূের িভিজট করা হেয়েছ
 a:hoverএিট একিট িলংক যার ঊপর মাউস রাখার সােথ সােথ িভজুয়াল ইেফ দখােব।
 a:activeএিট একিট িলংক যটা বতমােন সিয় আেছ। অনভােব বলা যায় ইউজার যখন িলংেক িক
কের রসপের জন অেপা কের স সমেয়র ইেফ।
নাটঃ িলের জন িবিভ াইল িদেত চাইেল িনেচর িনয়ম েলা মেন চলেত হেব-
 a:hover-ক a:link এবং a:visited এর পের াপন করেত হেব।
 a:active –ক a:hover-এর পের াপন করেত হেব।
একিট উদাহরণ দখুন-
<html>
<head>
51
ছাট হােতর লািটন অর কাশ কের (a, b, c, d, e, ইতািদ)
ছাট হােতর রামান অর কাশ কের (i, ii, iii, iv, v, ইতািদ)
কান িচ দখােব না।
Square িচ কাশ কের।
বড় হােতর অর কাশ কের (A, B, C, D, E, ইতািদ )
বড় হােতর লািটন অর কাশ কের (A, B, C, D, E, ইতািদ)
বড় হােতর রামান অর কাশ কের (I, II, III, IV, V, ইতািদ)
<style type="text/css">
a:link {color:#FF0000;} /* unvisited link */
a:visited {color:#00FF00;} /* visited link */
a:hover {color:#FF00FF;} /* mouse over link */
a:active {color:#0000FF;} /* selected link */
</style>
</head>
<body>
<p><b><a href="default.asp" target="_blank">This is a link</a></b></p>
to be effective.</p>
</body>
</html>
উপেরর কাডেলা index.html নােম সভ কের আউটপুট দখুন।
িবিভ াইেলর িলের উদাহরণ দখুনঃ
<html>
<head>
<style type="text/css">
a.one:link {color:#ff0000;}
a.one:visited {color:#0000ff;}
52
a.one:hover {color:#ffcc00;}
a.two:link {color:#ff0000;}
a.two:visited {color:#0000ff;}
a.two:hover {font-size:150%;}
a.three:link {color:#ff0000;}
a.three:visited {color:#0000ff;}
a.three:hover {background:#66ff66;}
a.four:link {color:#ff0000;}
a.four:visited {color:#0000ff;}
a.four:hover {font-family:monospace;}
a.five:link {color:#ff0000;text-decoration:none;}
a.five:visited {color:#0000ff;text-decoration:none;}
a.five:hover {text-decoration:underline;}
</style>
</head>
<body>
<p>Mouse over the links to see them change layout.</p>
53
<p><b><a class="one" href="default.asp" target="_blank">This link changes
color</a></b></p>
<p><b><a class="two" href="default.asp" target="_blank">This link changes
font-size</a></b></p>
<p><b><a class="three" href="default.asp" target="_blank">This link changes
background-color</a></b></p>
<p><b><a class="four" href="default.asp" target="_blank">This link changes
font-family</a></b></p>
<p><b><a class="five" href="default.asp" target="_blank">This link changes
text-decoration</a></b></p>
</body>
</html>
উপেরর কাডেলা index.html নােম সভ কের আউটপুট দখুন।
অধায়-সাত
[বাকউ পািট]
আপনার সাইেটর বাকউ অেনক বিশ পূণ। HTML-এ ধু bgcolor ববহার কের পুেরা
Background –এর রঙ বদলােনা যায়। িক িসএসএস এর মাধেম আপিন যেকান HTML এিলেমের
(Heading, Paragraph, Link, Table, Span etc. এর background color or image সট
করেত পােরন। তাছাড়া background image িকভােব দিশত হেব স িবষয়িট আপিন িনয়ন করেত পারেবন।
আপিন পছমত এিটেক horizontally, vertically repeat করেত পােরন।তাছাড়া
আপিন background ক fixed position এ রাখেত পােরন বা scroll করেত পােরন। আমরা এ অধােয়
বাকউ িনেয় িবািরত আেলাচনা করেবা।
পািট
1.background
িসএসএস-এ ববত সকল বাকউ পািট
বণনা
সকল background properties-ক একিট িডকলােরশেনর মাধেম তুেল
ধরা যায়।
54
2.background-
attachment
3.background-color
4.background-image
5.background-position
6.background-repeat
এই পািট িনধারণ কের পজ িলং-এর সােথ সােথ background ইেমজিট
fixed থাকেব না পেজর সােথ সােথ ল করেব।
background-color property কান এিলেমের background
color িনধারণ কের।
background-image property ববহার কের কান এিলেমের
বকউে ইেমজ সট করা যায়।
ইেমজেক িঠক কান ােন াপন করেবন তা বেল দওয়া যেত পাের
background-position Property ববহার কের।
কান বাকাউ ইেমজ repeat হেব িক না, হেল কান িদেক িক পিরমাণ হেব তা
িনধারণ করা হয় CSS-এর background-repeat পািটর মাধেম।
১.বাকাউ পািটঃ
বাকাউ পািটর মাধেম সকল background properties-ক একিট িডকলােরশেনর মাধেম তুেল ধরা যায়।
background পািটর অডার হল- background-color>background-image>background-
repeat>background-attachment>background-position. এেদর কানটার ভলু বাদ পড়েল
সমসা নই।
একিট উদাহরণ দখুন-
<head>
<style type="text/css">
body
{
background: #00ff00 url('smiley.gif') no-repeat fixed center;
}
</style>
</head>
55
২.বাকাউ এটাচেম পািটঃ
background-attachment property িনধারণ কের পজ িলং-এর সােথ সােথ background
ইেমজিট fixed থাকেব না পেজর সােথ সােথ ল করেব। আপিন াউজার উইেার লবার ল কন।
বাকাউ ইেমজও পজ িলের সােথ সােথ ল হে। এখন আপিন চােন পজ ল করেবন িক বাকাউ
ইেমজ যন ির থােক। এিট করা সব background-attachment পািটর মাধেম। পেজর টেটর
সােপে ির এ বাকাউ ইেমজেক বলা হয় Watermark। ইেমজেক Watermark করার জন িনেচর মত
কাড িলখুন-
একিট উদাহরণ দখুন-
<html>
<head>
<style type="text/css">
body
{
background-image:url('22.png');
background-repeat:repeat;
background-attachment:fixed;
}
div{height:1200px; width:960px; background:#112200; margin:0 auto;}
</style>
</head>
<body>
<div>
<p>This is a division</p>
</div>
56
</body>
</html>
উপেরর উদাহরণিট ভালভােব াকিটচ কের দখুন।
background-attachment property িনেচর িট মান ববহার কের-
ভলু
বণনা
scroll
fixed
বাকাউ ইেমজও পজ িলের সােথ সােথ ল হেব। এটা িডফ। .
বাকাউ ইেমজ িফড থাকেব।
৩.বাকাউ কালার পািটঃ
background-color property কান এিলেমের background color িনধারণ কের। কান
এিলেমের বাকাউ হল ঐ এিলেমের মাট সাইেজর সমান, যােত padding এবং border অভু থাকেব
িক margin থাকেব না। সাধারণত background color এবং text color একসােথ
background-color পািটর সােথ ববহার করা যায় যােত টট ভাল পড়া যায়।
body
{
background-color:yellow;
}
h1
{
background-color:#00ff00;
}
p
{
background-color:rgb(255,0,255);
}
৪.বাকাউ ইেমজ পািটঃ
background-image property ববহার কের কান এিলেমের বকউে ইেমজ সট করা যায়।
57
Body { background-image: url(largePic.jpg); }
p { background-image: url(smallPic.jpg); background-color:#00ff00 }
এর ফেল background এ এক ছিব এবং Paragraph এ আেরক ছিব দখা যােব।
url('URL')
none
ইেমেজর 'URL'।
কান বাকউ ইেমজ থাকেব না। এটা িডফ।
৫.বাকাউ পিজশান পািটঃ
কান বাকাউ ইেমজেক িঠক কান ােন াপন করেবন তা বেল দওয়া যেত পাের background-position
Property ববহার কের। এর মান িহেসেব ববহার করা যেত পাের- দঘ , শতকরা হার ও িকওয়াড।শতকরা হার
ববহার করা হয় দঘ/ অবান িনেদেশর জন। যমন- ০%০% ববহার করেল ঐ ইেমজ াউজার উইেার একদম
উপেরর বাম কানায় অবান করেব। আবার ৫০%৫০% ববহার করেল তার অবান হেব মধিবুেত। দেঘর
পিরমাপসমূহ (যমন 4em 50%) হল Vertical অবান িনেদশক। কী ওয়াড বাবহােরর বলায় আনুভূিমক। লিক
মােনর পিরবতন ঘটােনা যেত পাের, সেে কান অসুিবধা হেব না। কারণ কীওয়াডেলার িতনিট (Top, Middle,
Bottom) উল (vertical) অবান িনেদশক, আর অন িতনিট (Left, Right, Center) আনুভূিমক
অবান িনেদশক। যমন-
Body{background-position: top left}
এ িডকলােরশনেক অনভােবও লখা যায়।
Body{background-position: left top}
বা, Body{background-position: ০% ০%}
background-position Property-ত ববত মানসমূহ-
ভলু
িকওয়াড
left top
left center
left bottom
right top
right center
right bottom
center top
center center
বণনা
যিদ আপিন ধু একিট keyword ববহার কেরন অন ভলু হেব "center"
58
center bottom
শতকরা হার
x% y%
থম মানটা horizontal অবান এবং িতীয় ভলুটা the vertical অবান িনেদশ
কের। আপিন যিদ একিট মান িঠক কের দন তেব অপর মানিট ৫০% হেব।িডফ মান হল-
0% 0%।
দঘ
xpos ypos
থম মানটা horizontal অবান এবং িতীয় ভলুটা the vertical অবান িনেদশ
কের। এই মান িপেল বা অন কান একেক হেত পাের। আপিন যিদ একিট মান িঠক কের
দন তেব অপর মানিট ৫০% হেব। আপিন % এবং positions এ করেত পােরন।
একিট উদাহরণ দখুন-
<html>
<head>
<style type="text/css">
body
{
background-image:url('smiley.gif');
background-repeat:no-repeat;
background-attachment:fixed;
background-position:center;
}
</style>
</head>
<body>
59
<p><b>Note:</b> For this to work in Firefox and Opera, the background-
attachment property must be set to "fixed".</p>
</body>
</html>
৬. বাকাউ িরিপট পািটঃ
কান বাকাউ ইেমজ িরিপট হেব িক না, হেল কান িদেক িক পিরমাণ হেব তা িনধারণ করা হয় CSS-এর
background-repeat পািটর মাধেম। background-repeat পািটর মানেলা হেত পাের-
ভলু
বণনা
repeat
বাকাউ ইেমজ vertically এবং horizontally িরিপট হেব। এটা িডফ।
repeat-x বাকাউ ইেমজ ধু horizontally িরিপট হেব।
repeat-y বাকাউ ইেমজ ধু vertically িরিপট হেব।
no-repeat বাকাউ ইেমজ িরিপট হেব না।
60
অধায়-আট
[পিজশান পািট]
িসএসএস পিজশন এর মাধেম আমরা এইচিটএমএল এিলেমস এর সিঠক (exact) পিজশন িনেদশ করেত পাির।
এর মাধেম আমরা একিট এিলেমের িপছেন আেরকিট এিলেম াপন করেত পাির এবং আরও িনধারণ করেত পাির য
যিদ এিলেম কনেট বিশ বড় হয় তেব িক ঘটেব। top, bottom, left, এবং right পািট ববহার কের
এিলেমের অবান িঠক করা যায়। িক যতন না position property সট করা হেব ততণ এইসব পািট
কাজ করেব না। তারা positioning method-এর উপর িভি কের িবিভভােব কাজ কের থােক। চার ধরেণর
positioning method আেছ যা িনপ-
1.Static Positioning
2.Fixed Positioning
3. Relative Positioning
4. Absolute Positioning
উদাহরণসহ িনে আেলাচনা করা হলঃ
1.Static Positioning:
HTML এিলেমেলা সাধারনত ািটক positioned হয়, অথাৎ কান একিট HTML উপাদােনর পিজশন
াপািট যিদ ািটক কের দওয়া হয়; তাহেল তা HTML উপাদান সমূেহর সাধারণ এবং ভািবক পিজশন িনেদশ
করেব। এেে top, bottom, left, এবং right াপািট সমূহ িডােরশন করেলও এ অনুযায়ী কান কাজ
হেব না; অথাৎ top, bottom, left, and right াপািট সমূহ িনিয় হেয় যােব। তাই বলা যায় static
positioned পািটেলা top, bottom, left, এবং right পািট ারা ভািবত হয় না।
61
একিট উদাহরণ দখুন-
<html>
<head>
<style>
.static{
position:static;
left:100px;
top:70px;}
</style>
</head>
<body >
<p class="static">The CSS positioning properties allow you to position an
element. </p>
<p>The CSS positioning properties allow you to position an element. </p>
</body>
</html>
আউটপুটঃ
62
কাড িবেষণঃ উপেরর উদাহরণিটেত ল কন আমরা িট পারাাফ িনেয়িছ এবং একটার পিজসান ািটক কের
িদেয়িছ এবং অনটা াভািবক অবায় আেছ িক তারপরও িট পারাােফর আউটপুেট কান পিরবতন নাই , এটা থেক
বুঝা যায় য, তাই বলা যায় static positioned পািটেলা top, bottom, left, এবং right পািট
ারা ভািবত হয় না।
2.Fixed Positioning:
কান একিট HTML উপাদানেক মিনটর িেনর সােপে কান িনিদ ােন িরভােব াপন করার জন পিজশন
িফড ববহার করা হয়। একটা এিলেমের পিজশন যিদ িফড কের দন তাহেল সটা াউজােরর উইেা সােপে
অবান করেব এবং াউজার যিদ ল কেরন তবুও সটা ির (fixed) থাকেব। এজন থেম position:fixed;
িডােরশন কের, এর পর top, bottom, left, and right াপািট সমূহ িডােরশন করেত হয়। Fixed
positioned elements েলা অনান এিলেমেক overlap করেত পাের।
একিট উদাহরণ দখুনঃ
<html>
<head>
<style type="text/css">
p.pos_fixed
{
position:fixed;
top:30px;
right:5px;
63
}
</style>
</head>
<body>
<p class="pos_fixed">Some more text</p>
<p><b>Note:</b> IE7 and IE8 supports the fixed value only if a
!DOCTYPE is specified.</p>
<p>Some text</p><p>Some text</p><p>Some text</p><p>Some text</p><p>Some
text</p><p>Some text</p><p>Some text</p><p>Some text</p><p>Some
text</p><p>Some text</p><p>Some text</p><p>Some text</p><p>Some
text</p><p>Some text</p><p>Some text</p><p>Some text</p>
</body>
</html>
উইেাটা ল করেলও ডানপােশর some more text লখািট ল করেব না।
64
3. Relative Positioning:
এইচিটএমএল উপাদান সমূেহর াভািবক অবােনর সােপে top, bottom, left, and right াপািট
ববহােরর মাধেম কান বর অবান িনধারেণর জন িরেলিটভ পিজশন াপািট ববহার করা হয়। পিজশন িরেলিটভ
াপািটর েত সকল িহসাব  হয় ঐ উপাদানিটর াভািবক অবান থেক। অথাৎ পিজশিনং না করা হেল উপাদানিট
য ােন অবান করেতা সখান থেক। relatively positioned এিলেমের উপাদানেলা অনান এিলেমের
উপাদানেক মুভ বা ওভারলাপ করেত পাের।
একিট উদাহরণ দখুন-
<html>
<head>
<style type="text/css">
h2.pos_left
{
position:relative;
left:-20px;
}
h2.pos_right
{
position:relative;
left:20px;
}
</style>
</head>
<body>
<h2>This is a heading with no position</h2>
<h2 class="pos_left">This heading is moved left according to its normal
position</h2>
<h2 class="pos_right">This heading is moved right according to its normal
position</h2>
<p>Relative positioning moves an element RELATIVE to its original
position.</p>
</body>
65
</html>
িরেলিটভ পিজশন এর ে য সকল পািট ববহার করা হয় তােদর িকছু শত দখুনঃ
Move Left - এেে left এর জন negative value ববহার করেত হেব।
Move Right - এেে left এর জন positive value ববহার করেত হেব।
Move Up - এেে top এর জন negative value ববহার করেত হেব।
Move Down - এেে left এর জন positive value ববহার করেত হেব।
.
4. Absolute Positioning:
HTML উপাদান সমূেহর কৃত অবান িনধারেণর জন পিজশন এবসিলউট াপািট ববহার করা হয়। কান একিট
HTML উপাদােনর পিজশন াপািট যিদ এবসিলউট কের দওয়া হয় তাহেল তার অবান ভািবক েম িনেদিশত হয়
না, এেে top, bottom, left, and right াপািট সমূেহর মাধেম ঐ উপাদানিটর অবান িনধািরত হয়।
এেে অন একিট উপাদােনর উপেরও ওভারলাপ কের ঐ উপাদানিটর অবান িনধারণ করা সব হয়।
উদাহরন:
<html>
<head>
<style type="text/css">
h2
{
position:absolute;
left:100px;
top:150px;
}
</style>
</head>
<body>
<h2>This is a heading with an absolute position</h2>
66
<p>With absolute positioning, an element can be placed anywhere on a page.
The heading below is placed 100px from the left of the page and 150px from
the top of the page.</p>
</body>
</html>
িসএসএস-এ ববত আরও িকছু পিজশান পািট
িপ পািট (Clip Property):
কান উপাদােনর কান অংশ দৃশমান হেব তা িনধারণ করা হয় Clip পািটর মাধেম। যমন- কান ইেমেজর সাইজ
অেনক বড় হেল তার কতটুকু দখা যােব তা এই পািটর মাধেম িনধারণ করা যায়। এর িসনটা হল-
Clip: sClip
এখােন sClip এর মান হেত পাের িট-
shape একিট এিলেম িপ করেব যার মান হেত পাের- rect (top, right, bottom, left)
auto কান িিপং হেব না। এটা িডফ।
কান সাইেডর মান দয়া না হেল তা auto িহেসেব ধের নয়,অথাৎ স িদকটা clip কের না। িপ পািট কাজ কের না
যিদ "overflow:visible" িলখা হয়। কান ইেমজেক িপ করােনার জন িনেচর মত ইেমজ িডকলােরশন ববহার
করা যেত পাের-
<html>
<head>
<style type="text/css">
img
{
position:absolute;
67
clip:rect(0px,60px,200px,0px);
}
</style>
</head>
<body>
<img src="w3css.gif" width="100" height="140" />
</body>
</html>
কাসর পািট (cursor Property):
আমরা উইেাজ, িলনা ববহার সময় িবিভ মাউস কাসর আইকন দেখিছ। িবিভ পিরিিত সােপে মাউস কাসর
এর আইকন িবিভ হয়। জনসাধারন যখন আপনার site visit করেব সখােনও িবিভ পিরিিত সােপে মাউস এর
আইকন িবিভ কের তরী করা যায়। এিট বিশ ববত হয় িলের জন। যা িসএসএস ারা করা সব । যমন-
p { cursor: wait }
h4 { cursor: help }
h5 { cursor: crosshair }
য কাসর ববহার করেবন তার URL –ও লখা যেত পাের-
P{cursor: url(“sajkdg.cur”) url(“sdjg.cur”),text}
কাসর পািট য সকল মান ববহার করেত পাের-
cursor: auto
cursor: inherit
cursor: crosshair
cursor: default
cursor: help
cursor: move
cursor: pointer
cursor: progress
68
cursor: text
cursor: wait
cursor: e-resize
cursor: ne-resize
cursor: nw-resize
cursor: n-resize
cursor: se-resize
cursor: sw-resize
cursor: s-resize
cursor: w-resize
একিট উদাহরণ দখুন-
<html>
<body>
<p>Mouse over the words to change the cursor.</p>
<span style="cursor:auto">auto</span><br />
<span style="cursor:crosshair">crosshair</span><br />
<span style="cursor:default">default</span><br />
<span style="cursor:e-resize">e-resize</span><br />
<span style="cursor:help">help</span><br />
<span style="cursor:move">move</span><br />
<span style="cursor:n-resize">n-resize</span><br />
<span style="cursor:ne-resize">ne-resize</span><br />
<span style="cursor:nw-resize">nw-resize</span><br />
<span style="cursor:pointer">pointer</span><br />
<span style="cursor:progress">progress</span><br />
<span style="cursor:s-resize">s-resize</span><br />
<span style="cursor:se-resize">se-resize</span><br />
<span style="cursor:sw-resize">sw-resize</span><br />
<span style="cursor:text">text</span><br />
<span style="cursor:w-resize">w-resize</span><br />
<span style="cursor:wait">wait</span><br />
</body>
</html>
ওভারেা পািট(Overflow Property):
69
যিদ এিলেম কনেট বের মােঝ এিলেম কনেট না ধের তেব িক ঘটেব তা িনধারণ করা হয় overflow
পািটর মাধেম। অনভােব বলা যায়- top left, height ও width পািটর মাধেম িনধারণকৃত বের মােঝ
কনেট না ধরেল তার িক হেব তা িনধারণ করা হয় overflow পািটর মাধেম। এই পািটর চারিট মান হেত পাের-
visible
পুেরা কনেট আঁটােনার জন উপাদােনর আকার পিরবতন করেব।এিট িডফ মান।
hidden এিট ববহার করা হেল সাইেজর বিশ টট দখা যােব না।
scroll কনেট উপাদােনর িনধািরত আকােরর চেয় বিশ বা কম যাই হাক না কন সবসময় লবার দশন করেব।
auto
কনেট িনধািরত উপাদােনর আকােরর চেয় বিশ হেলই কবল লবার দখােব।
<html>
<head>
<style type="text/css">
div.scroll
{
background-color:#00FFFF;
width:100px;
height:100px;
overflow:scroll;
}
div.hidden
{
background-color:#00FF00;
width:100px;
height:100px;
overflow:hidden;
}
</style>
</head>
<body>
<p>The overflow property specifies what to do if the content of an element exceeds
the size of the element's box.</p>
<p>overflow:scroll</p>
<div class="scroll">You can use the overflow property when you want to have better
control of the layout. The default value is visible.</div>
70
<p>overflow:hidden</p>
<div class="hidden">You can use the overflow property when you want to have better
control of the layout. The default value is visible.</div>
</body>
</html>
আউটপুটঃ
জড ইনেড (Z-index Property):
পিজশন এবসিলউট (position:absolute) কের এবং top, bottom, left, and right ইতািদ
াপািট ববহার কের একািধক HTML উপাদানেক পরেরর উপর ওভারলাপ করা যায়।
একািধক HTML উপাদানেক পরেরর উপর ওভারলাপ করা কান উপাদান কার উপের
অবান করেব তা জড ইনেড (Z-index) াপািট ববহার কের িনধারণ করা হয়। (Z-
index) াপািটর মান িহেসেব আমরা auto এবং কান সংখা যমন 1,2,3,-1 ভিতৃ
ববহার
করা হয়।
71
আমরা দেখিছ p o s i t i o n a b s o l u t e এর সােথ t o p b o t t o m l e f t
:
,
,
,
a n d r i g h t ইতািদ পািট িমিশেয় িবিভ উপাদানেক ওভারলাপ করা যেত পাের। িবিভ উপাদান
ওভারলাপ করােনা হেল কানিট কার উপের অবান করেব তা জড ইনেড (Z -i n d e x ) াপািট ববহার কের
িনধারণ করা হয়।
z-index পািট ই ধরেণর মান ববহার করেত পাের-
auto Sets the stack order equal to its parents. This is default
number Sets the stack order of the element. Negative numbers are allowed
একিট উদাহরণ দখুন-
দশনঃ
72
অধায়-নয়
[ব পািট]
িসএসএস এর ে িতিট ক লেভল উপাদানেক একিট ব িহেসেব ধের নয়া হয়। এই বের আেছ িকছু পািট।
িসএসএস-এ এসব পািট ও তার ববহারেক ব মেডল বেল অিভিহত করা হয়। এই বের িবিভ পািট পিরবতন কের
িবেশষ কের কান উপাদােনর চারপােশ বডার বা ইনেড তিরর জন ব মেডল বাঝা খুব দরকার। িডজাইন ও
লআউেটর জন "box model" খুবই পূণ। "box model" আসেল একিট ব যা HTML উপাদানেক
িঘের থােক। ব মেডেলর উপাদানল হল-
1.margins 2.borders 3.padding 4. contents
ব মেডেলর গঠন নে দখােনা হলঃ
73
Margin - Margin বলেত এইচিটএমএল এিলেম এর border এর চারপােশর অংশেক বা এিলেমের
চারপােশর অংশেক বাঝায়
Border - padding এবং content-এর চারপােশর অংশই হল বডার। বডার বাকউ কালার ারা ভািবত
হয়।
Padding – বডার এবং কনেটের মােঝর ফঁাকা ানই হল padding । padding বডার বাকউ কালার ারা
ভািবত হয়।
Content – যখােন এইচিটএমএল এিলেম যমন-টট , ইেমজ ইতািদ থােক।
কান কনেটের জন িফড কান এিরয়া িনধারণ করেত আমরা িসএসএস- এ সাধারণত width and height
পািট ববহার কের থািক। িক পুেরা এিরয়া িনধারণ করেত padding, border and margin ববহার করেত
হেব।
৩০০ িপেল কনেট এিরয়ার জন িডকলােরশন দখুনঃ
width:250px;
padding:10px;
border:5px solid gray;
margin:10px;
িহসাব কের দখা যাকঃ
250px (width)
+ 20px (left and right padding)
+ 10px (left and right border)
74
+ 20px (left and right margin)
= 300px
িনেচর সু েয়াগ কের িহসাব কনঃ
Total element width = width + left padding + right padding + left border +
right border + left margin + right margin
Total element height = height + top padding + bottom padding + top border
+ bottom border + top margin + bottom margin
একিট উদাহরণ দখুনঃ
<html>
<head>
<style type="text/css">
div.ex
{
width:220px;
padding:10px;
border:5px solid gray;
margin:0px;
}
</style>
</head>
<body>
<img src="250px.gif" width="250" height="1" /><br /><br />
75
<div class="ex">The line above is 250px wide.<br />
The total width of this element is also 250px.</div>
</body>
</html>
আউটপুটঃ
পািট
margin
িসএসএস-এ ববত সকল Margin Properties:
বণনা
সকল মািজন পািটেক একিট পািট-ত িনেয় আসা যায় margin shorthand
property ("margin") ববহার কের।
margin-bottom এিলেমের bottom margin-এর জন ববহার করা হয়।
margin-left এিলেমের left margin -এর জন ববহার করা হয়।
margin-right এিলেমের right margin -এর জন ববহার করা হয়।
margin-top এিলেমের top margin -এর জন ববহার করা হয়।
ধারাবািহকভােব পািটেলা িনে আেলাচনা করা হলঃ
1.Margin - Shorthand property
সকল margin property ক একিট property-ত িনেয় আসা যায় margin shorthand
property ("margin")ববহার কের। margin পািট top>right>bottom>left এই ম মেন চেল।
margin property চারিট ভলু িনেয় গিঠত।
 margin:25px 50px 75px 100px;
76
িবািরত কাড হেব িনেচর মতঃ
o top margin is 25px
o right margin is 50px
o bottom margin is 75px
o left margin is 100px
িডকলােরশনঃ
কান margin property এর ভালু িনধারণ কের না িদেল তার মান হেব িবপরীত িদেকর মােনর সমান। যমনঃ
Img{margin:1cm 2cm} হয় তেব,
Img{margin:1cm 2cm 1cm 2cm } হেব।
 margin:25px 50px 75px;
o top margin is 25px
o right and left margins are 50px [িবপরীত িদেকর মান ববহার কেরেছ]
o bottom margin is 75px
 margin:25px 50px;
o top and bottom margins are 25px
o right and left margins are 50px
 margin:25px;
o all four margins are 25px
একিট উদাহরণ দখুনঃ
<html>
77
<head>
<style type="text/css">
p
{
background-color:yellow;
}
p.margin
{
margin-top:100px;
margin-bottom:100px;
margin-right:50px;
margin-left:50px;
}
</style>
</head>
<body>
<p>This is a paragraph with no specified margins.</p>
<p class="margin">This is a paragraph with specified margins.</p>
</body>
</html>
78
margin property য সকল মান ববহার করেত পােরঃ
auto
াউজার িনেজই মািজন সট কের িনেব। এটা াউজােরর উপর িনভর কের।
length px, pt, em একেক fixed margin ববহার করা যায়।
%
এিলেমের সােপে শতকরায় মািজন কাশ করা হয়।
2. Border Property:
এইচিটএমএল এিলেমস এর চারপােশ য বডার দখা যায় তা িসএসএস বডার এর মাধেম সুনভােব
customize (style, color)করা যায়।
িসএসএস-এ ববত সকল বডার পািট:
পািট
1.border
2.border-bottom
3.border-bottom-
color
4.border-bottom-
style
5.border-bottom-
width
6.border-color
7.border-left
বণনা
border shorthand property ("border":) সকল border
properties-ক একিট িডকলােরশেনর মাধেম কাশ কের।
border-bottom shorthand property(border-bottom:)
সকল bottom border properties-ক একিট িডকলােরশেনর মাধেম
কাশ কের।
border-bottom-color property কান এিলেমের bottom
border-এর কালার িনধারণ কের।
Sets the style of the bottom border
Sets the width of the bottom border
Sets the color of the four borders
border-left shorthand property সকল left border
properties ক একিট িডকলােরশেনর মাধেম কাশ কের।
8.border-left-color Sets the color of the left border
9.border-left-style Sets the style of the left border
10.border-left-
width
Sets the width of the left border
11.border-right
12.border-right-
color
13.border-right-
style
Sets all the right border properties in one declaration
Sets the color of the right border
Sets the style of the right border
79
14.border-right-
width
Sets the width of the right border
15.border-style Sets the style of the four borders
16.border-top
Sets all the top border properties in one declaration
17.border-top-color Sets the color of the top border
18.border-top-style Sets the style of the top border
19.border-top-width Sets the width of the top border
20.border-width Sets the width of the four borders
1.border property:
border shorthand property ("border":) সকল border properties-ক একিট
িডকলােরশেনর মাধেম কাশ কের।
িডকলােরশেনর ম হল border-width>border-
style>border-color। কান ভালু বাদ পড়েল সমসা নই, এেে ঐ পািটর িডফ মান বসেব।
একিট উদাহরণ দখুন-
2.border-bottom property:
border-bottom shorthand property(border-bottom:) সকল bottom border
properties-ক একিট িডকলােরশেনর মাধেম কাশ কের। িডকলােরশেনর ম হল border-bottom-
width>border-bottom-style> border-bottom-color.কান ভালু বাদ পড়েল সমসা নই।
80
3.border-bottom-color:
border-bottom-color property কান এিলেমের bottom border-এর কালার িনধারণ কের।
4.border-bottom-style property:
border-bottom-style property কান এিলেমের বডােরর bottom অংেশর াইল িনধারণ কের।
81
border-bottom-style property য সকল মান ববহার করেত পােরঃ
nonehiddendotteddashedsoliddoublegrooveridgeinsetout
setinherit
5.border-bottom-width property:
border-bottom-width property কান এিলেমের বডােরর bottom অংেশর শতা িনধারণ কের।
িবঃ ঃ border-bottom-width পািট িডকলার করার আেগ border-style পািট িডকলার করেত হেব।
border-bottom-width পািটেত য সকল মান ববহার করা যায়- thin medium t h i c k
অথবা সরাসির কান সংখা ববহার করেত পােরন।
6.border-color property:
border-color property ববহার কের বডােরর রঙ িনধারণ করা হয়। এর মান HTML এ ববত িতনিট
রেঙর নাম ববহােরর পিত আনুসাের হেব। "border-color" property এককভােব কাজ করেত পাের না,
এর সােথ "border-style" property ববহার করেত হয়, যা থেম িডার করেত হয়। You can also
82
set the border color to "transparent" Specifies that the border color should
be transparent. This is default.
কান এিলেমের border-width চারিদেকই হেত পাের। যমনঃ
 border-color:red green blue pink;
o top border is red
o right border is green
o bottom border is blue
o left border is pink
 border-color:red green blue;
o top border is red
o right and left borders are green
o bottom border is blue
 border-color:dotted red green;
o top and bottom borders are red
o right and left borders are green
 border-color:red;
o all four borders are red
83
7.border-left property:
border-left shorthand property সকল left border properties ক একিট িডকলােরশেনর
মাধেম কাশ কের। িডকলােরশেনর ম হল border-left-widthborder-left-
styleborder-left-color.
8.border-left-color property:
b o r d e r -l e f t -c o l o r p r o p e r t y বামিদেকর বডােরর রঙ িনধারণ কের।
84
9.border-left-style property:
border-left-style property বামিদেকর বডােরর াইল িনধারণ কের।
border-bottom-style property য সকল মান ববহার করেত পাের border-left-style
property-ও সই সকল মান ববহার করেত পারেব।
10.border-left-width property:
এর সকল কাজ border-bottom-width property এর মেতাই।
85
11.border-right property:
এর সকল কাজ border-left property-এর মেতাই।
12.border-right-color property:
এর সকল কাজ border-left-color property-এর মেতাই।
13.border-right-style property:
এর সকল কাজ border-bottom-style property ও border-left-style property এর মত।
14.border-right-width property:
এর সকল কাজ border-bottom-width property ও border-left-width property এর
মেতাই।
15.border-style Properties:
বডােরর াইল কমন হেব তা border-style:-এর মাধেম কাশ করা হয়। য ভলু েলা ববহার করা যায় তা
িনপঃ
ভলু
বণনা
none
hidden
dotted
dashed
solid
double
groove
ridge
inset
outset
কান বডার দখা যােব না।
The same as "none", except in border conflict resolution for
table elements
একিট dotted border দখা যােব।
একিট dashed border দখা যােব।
একিট solid border দখা যােব।
একিট double border দখা যােব।
3D grooved border দখা যােব। যার ইেফ border-color-এর উপর িনভর কের।
3D ridged border দখা যােব। যার ইেফ border-color-এর উপর িনভর কের।
3D inset border দখা যােব। যার ইেফ border-color-এর উপর িনভর কের।
3D outset border দখা যােব। যার ইেফ border-color-এর উপর িনভর কের।
86
িনে উদাহরণসহ দখােনা হলঃ
87
চারিদেকর বডােরর জন চারিট মান সট করা যেত পােরঃ
 border-style:dotted solid double dashed;
o top border is dotted
o right border is solid
o bottom border is double
o left border is dashed
 border-style:dotted solid double;
o top border is dotted
o right and left borders are solid
o bottom border is double
 border-style:dotted solid;
o top and bottom borders are dotted
o right and left borders are solid
88
 border-style:dotted;
o all four borders are dotted
িনেচর উদাহরণ দখুনঃ
Output:
16.border-top property:
The border-top shorthand property sets all the top border properties in one
declaration.ম হলঃ border-top-width border-top-style border-top-color.
89
17.border-top-color property:
এর কাজ border-left-color property: এর মেতাই।
18.border-top-style property:
এর কাজ border-bottom-style property ও border-left-style property-এর মত।
19.border-top-width property:
এর সকল কাজ border-bottom-width property এর মত।
20.border-width property:
বডােরর শতা িনধারণ করেত border-width property ববহার করা হয়। "border-width"
property এককভােব কাজ করেত পাের না, এর সােথ "border-style" property ববহার করেত হয়,
যা থেম িডার করেত হয়। এর মান ইভােব িডফাইন করা যায়-১.িপেল ২. pre-defined values । pre-
defined value েলা হলঃ
ভালু
thin
medium
thick
length
বণনা
thin border িনেদশ কের।
medium border িনেদশ কের। এটা default
thick border িনেদশ কের।
ইামত মান দওয়া যেত পাের।
কান এিলেমের border-width চারিদেকই হেত পাের। যমনঃ
90
ঃ
9
িসএসএস পািডং বলেত বাঝায় এিলেম এর border এবং তার content এর মােঝর অংশেক।িসএসএস
পািডং ববহার কের আপিন এইচিটএমএল এিলেম (paragraphs, tables ইতািদ ) এর default
পািডং পিরবতন করেত পােরন। Padding এর উপর background color এর ভাব রেয়েছ।
সকল CSS Padding Properties
পািট
1.padding
বণনা
padding shorthand property(padding:) সকল padding
properties ক একিট িডকলােরশেনর মাধেম তুেল ধের।
2.padding-bottom কান এিলেমের বটেমর পািডং িনধারণ কের।
3.padding-left
কান এিলেমের বাম পােশর পািডং িনধারণ কের।
4.padding-right কান এিলেমের ডান পােশর পািডং িনধারণ কের।
5.padding-top
কান এিলেমের টেপর পািডং িনধারণ কের।
সকল CSS Padding Properties েলা য ভালু ববহার করেত পাের-
length px, pt, em একেক fixed padding ববহার করা যায়।
%
এিলেমের সােপে শতকরায় পািডং কাশ করা হয়।
ধারাবািহকভােব CSS Padding Properties েলা িনে বণনা করা হলঃ
1.padding shorthand property:
padding shorthand property(padding:) সকল padding properties ক একিট
িডকলােরশেনর মাধেম তুেল ধের। padding shorthand property চারিট ভলু ববহার কের। যমনঃ
 padding:10px 5px 15px 20px; [সিঠক েম সাজােনা]
o top padding is 10px
o right padding is 5px
o bottom padding is 15px
o left padding is 20px
92
 padding:10px 5px 15px;
o top padding is 10px
o right and left padding are 5px
o bottom padding is 15px
 padding:10px 5px;
o top and bottom padding are 10px
o right and left padding are 5px
 padding:10px;
o all four paddings are 10px
2.CSS padding-bottom Property:
The padding-bottom property sets the bottom padding (space) of an
element.
3.CSS padding-left Property:
The padding-left property sets the left padding (space) of an element.
93
4.CSS padding-right Property
The padding-right property sets the right padding (space) of an element.
5.CSS padding-top Property
The padding-top property sets the top padding (space) of an element.
৪. িসএসএস আউটলাইন পািটঃ
কান এিলেমের বডােরর চারপােশ আেরকিট বডারই হল আউটলাইন।
িসএসএস-এ ববত সকল Outline Properties:
পািট
1.outline
বণনা
সকল আউটলাইন পািটেক একিট িডকলােরশেনর মাধেম তুেল
ধের।
2.outline-color আউটলাইেনর কালার সট কের।
ভলু
outline-color
outline-style
outline-width
color_name
94
hex_number
rgb_number
invert
3.outline-style আউটলাইেনর াইল িনধারণ কের।
none
dotted
dashed
solid
double
groove
ridge
inset
outset
4.outline-width আউটলাইেনর সতা িনধারণ কের।
ধারাবািহকভােব িনে এেদর বণনা দওয়া হলঃ
১.আউটলাইন শটহা পািটঃ
সকল আউটলাইন পািটেক একিট িডকলােরশেনর মাধেম তুেল ধের। এেদর ম হল outline-coloroutline-
style outline-width.
Thin/medium
thick/length
২.আউটলাইন কালার পািটঃ
আউটলাইেনর কালার সট কের। o u t l i n e -s t y l e p r o p e r t y ক o u t l i n e -
c o l o r p r o p e r t y -এর আেগ িডকলার করেত হেব।
95
color আউটলাইেনর কালার িনধারণ কের।
invert িবপরীত কালার দশন কের। এটা িনিত কের বাকউ কালার ছড়াই আউটলাইন দখা যােব। এটা িডফ।
৩. আউটলাইন াইল পািটঃ
outline-style property আউটলাইেনর াইল িনধারণ কের।
o u t l i n e -s t y l e p r o p e r t y -ত ববত মানসমূহঃ
মান
বণনা
none
dotted
dashed
solid
double
groove
ridge
inset
outset
কান আউটলাইন হেব না
ডেটড আউটলাইন হেব
ডাসড আউটলাইন হেব
সিলড আউটলাইন হেব
ডাবল আউটলাইন হেব
3D grooved আউটলাইন হেব
3D ridged আউটলাইন হেব
3D inset আউটলাইন হেব
3D outset আউটলাইন হেব
একিট উদাহরণ দখুন-
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html>
<head>
<style type="text/css">
p {border:1px solid red;}
96
p.dotted {outline-style:dotted;}
p.dashed {outline-style:dashed;}
p.solid {outline-style:solid;}
p.double {outline-style:double;}
p.groove {outline-style:groove;}
p.ridge {outline-style:ridge;}
p.inset {outline-style:inset;}
p.outset {outline-style:outset;}
</style>
</head>
<body>
<p class="dotted">A dotted outline</p>
<p class="dashed">A dashed outline</p>
<p class="solid">A solid outline</p>
<p class="double">A double outline</p>
<p class="groove">A groove outline</p>
<p class="ridge">A ridge outline</p>
<p class="inset">An inset outline</p>
<p class="outset">An outset outline</p>
specified.
97
</body>
</html>
আউটপুটঃ
৪. িসএসএস আউটলাইন উইথ পািটঃ
আউটলাইেনর সতা িনধারণ কের। o u t l i n e -s t y l e p r o p e r t y ক outline-width
property -এর আেগ িডকলার করেত হেব।
outline-width property-ত ববত মান সমূহ-
মান
বণনা
thin
Specifies a thin outline
medium Specifies a medium outline. This is default
thick
Specifies a thick outline
length Allows you to define the thickness of the outline
This example demonstrates how to set the width of an outline.
98
99
অধায়-দশ
[টিবেল িসএসএস-এর ববহার]
িসএসএস-এর মাধেম টিবলেক কীভােব আকষণীয় করা যায় আমরা এখােন সটাই আেলাচনা করব-
টিবল বডারঃ
টিবেলর বডােরর াইল িনণয় করেত border property ববহার করা হয়। যমন-
100
টিবেল ল কন এখােন ডাবল বডার আেছ, কারণ table, th, এবং td এিলেমের separate border
আেছ। একক বডার দখােত border-collapse property ববহার কন।
কলা বডারঃ
101
102
অধায়- এগার
[িসএসএস াট ও িয়ার পািট]
িসএসএস াট পািটঃ
HTML-এ align attribute- এর মেতাই কাজ কের াট পািট। ট ারা ছিব ক ওেয়ব পেজর এক পােশ বা
অন পােশ অবান করােনা যায় এবং এর সাহােয খুব সহেজ টট ক ছিবর চারপােশ Wrapping করা
যায়। যমনিট দখা যায় magazines বা সংবাদপে িবিভ আকােরর ছিবর চারপােশ টট এর অবান । াট
পািটর চারিট মান ববহার করা যায়।যথা- left, right, none, inherit. এেলার মাধেম উপাদােনর অবান
িনেদশ করা হয়।
103
Output:
দখুন ইেমজিট টেটর ডানপােশ অবান করেছ।
িসএসএস িয়ার পািটঃ
Clear পািটর মাধেম িনেদশ করা যেত পাের সই উপাদােনর পােশ অন কান উপাদান float করেত পারেব িক
না। এিট কবল ক লেভল উপাদােনর েই ববহার করা যােব। এর মান িহেসেব left, right, none ও both
ববত হেত পাের। যমন-
P{clear: both}পারাােফর কান পােশই াট হেত পারেব না।
P{clear: left}কবল বা পােশ াট হেত পারেব না।
P{clear: right} কবল ডানপােশ াট হেত পারেব না।
P{clear: none} Default. Allows floating elements on both sides
104
অধায়-বার
[িসএসএস িসেলর]
িসএসএস িসেলর ক িসএসএস এর দিপ বলা হয়।িবিভ ধরেনর িসেলর আেছ,এসব িদেয় এইচিটএমএল পেজর
এিলেম িসেল করা যায় এবং িসেল করার পর িনেজর ইেমত াইিলং করা যায়।িসএসএস িসেলর এর বাপাের
খুব গভীর এবং  ধারনা থাকেত হেব। াইলশীেট <BODY>অংেশ ববত উৎসসমূেহর সােথ নতুন িসেলর যাগ
করা যেত পাের Class ও ID ববহার কের।িসেলর িনেয় কাজ করার আেগ িকছু টাম জানেত হেব যমনঃ
১.এইচিটএমএল এিলেম ২.এিিবউট এই িট সেক আমরা জািন।
৩.ল সট বা লঃ
ল সেটর মধ পািট ও তার মান দয়া হয়। এিট থােক কান িডকলােরশন েকর মধ। িডকলােরশন ক  হয়
সেক বােকট { িদেয় ও শষ হয় } িদেয়। এর মােঝ একািধক িডকলােরশন থাকেত পাের যা সিমেকালন িদেয় পৃথক
থাকেত পাের। িডকলােরশন েকর আেগ অথাৎ { এর আেগ যা িকছু থােক তাই িসেলর। আপিন য html উপাদােনর
পািট পিরবতন করেত চান সিটেক িসেলর িহেসেব ববহার করেত হেব। এরপর িডকলােরশন েকর মােঝ য িনয়ম
দেবন তা েয়াগ হেব ঐ িসেলেরর ে। যমন িনেচর উদাহরেণ h1 হল িসেলর , আর {} এর মােঝ ল সট।
পুেরা {} িডকলােরশন ক।
105
h4{background-color:white;font-size:12px;}
p{color:red;}
এখােন h4, p এসব হে িসেলর,h4 এর ারা এইচিটএমএল পেজর <h4></h4> এর িভতের যা আেছ তা
িসেল করেব বা বলা যায় h4 এিলেম িসেল করেব। h4 এর পর সেক ােকট যখান থেক  হেয়েছ এবং p
এর আেগ যখােন সেক ােকট শষ হেয়েছ এইটুকু িডেয়ােরশন ক। সেক ােকেটর িভতের সবটুকু হে
িডেয়ােরশন। background-color হে াপািট এবং white হে এর ভালু। আর পুেরাটা অথাৎ h4 থেক
 কের এর সেক ােকট যখােন শষ হেয়েছ এইটুকু ল বা ল সট। উপেরর কােড িট ল আেছ h4 এবং p।
িনেচ িবিভ িসেলর এর নাম এবং এরা িকভােব কাজ কের তা দয়া হল:
১.ইউিনভাসাল িসেলরঃ
ইউিনভাসাল িসেলর এইচিটএমএল পেজর িতিট এিলেম ক িসেল কের।যমন িনেচর কাডিট সব এইচিটএমএল
এিলেম এর রং লাল কের দেব।
*{color:red;}
২.আইিড িসেলরঃ
HTML element-এর জন একিট াইল িনধারণ করেত CSS আপনােক আপনার িনজ selector ববহােরর
সুেযাগ িদেয়েছ যা "id" এবং "class" নােম পিরিচত। ID িসেলর একটা এিলেমের াইল িদেত বাবত হয়।
ID িসেলর HTML এিলেমের id attribute ববহার কের এবং এটা একটা “#”-এর মাধেম িডফাইন করা
হয়। একিট ID নাম নাার িদেয়  করা যােব না এটা Firefox.-এ কাজ করেব না।
106
৩.িসএসএস াস িসেলরঃ
িসএসএস এর মাধেম এইচিটএমএল এিলেম এর অসংখ াইল দয়া যায়। মূলত a group of elements-এর
style িদেত িসএসএস class selector ববহার করা হয়। class selector ববহার কের HTML
elements-এর জন কেতােলা particular style িনধারণ করা যায় same class-এর মাধেম। class
selector ববহার কের HTML-এর class attribute এবং এটা একিট ডট(".")-এর মাধেম িডফাইন করা
হয়। Class ববহার করা খুব সাধারন। সাধারন িসএসএস কাড এর অংশেক বিধত (extension) করেত হেব।
আর এই বিধত অংশেক অবশই এইচিটএমএল টাগ এ Class এর মান িহসােব বসােত হেব। Class Selector
এর সাধারন গঠনঃ
Selector/HTML Element . Class Name {Declaration}
নাটঃ class নাম সংখা িদেয়  করেবন না তাহেল এটা ইারেনট এেারার এ কাজ করেবনা।
107
৪.টাইপ িসেলর:
p, a হে এখােন টাইপ িসেল। p িসেলর এইচিটএমএল পেজর সব <p> এিলেম ক িসেল করেব এবং এেদর
বাকাউ রং কমলা কের দেব আর a িসেলর এইচিটএমএল সব িলংক ক িসেল কের রং খেয়ির কের দেব।
৫.িডেসনেড িসেলরঃ
এক িসেলেরর মােঝ আেরক িসেলর থাকেল িতীয় িসেলেরর কান পািট পিরবতন করেত চাইেল িডেসনেড
িসেলর ববহার করেত হয়। যমনঃ
li a {
text-decoration: none;
color:red;
}
এইচিটএমএল ফাইল
108
ধন আপিন li এিলেম এর অধীন a এিলেম ক টােগট করেত চােন তখন িসএসএস ল িলখেত হেব উপেরর
মত।এই কােডর ভাব আপনার এইচিটএমএল পেজর ধু li এর অধীন a ত িগেয় পরেব। এ রকম িডকলােরশেনর
ে িসেলর েটার মােঝ ধু একিট স থাকেব, কমা , সিমেকালন বা ফুলপ থাকেব না।
৬.direct children িসেলরঃ
div#menu> ul { border: 1px solid black; }
এই লিট যিদ উপেরর এইচিটএমএল পেজ েয়াগ কেরন তাহেল ul এিলেম এর উপর একটা বডার হেব তেব
Children লখািটর উপর বডার আসেবনা যিদও এটা আেরকটা ul এর মেধ আেছ। কারন Children লখািট য
ul এর মেধ আেছ সটা menu আইিডর direct children নয়। আেরকিট উদাহরণঃ div ul>li>p
এর অথ হল div এর অধীেন ul এবং তার চাই li । আবার li এর িডেসে হেব p।
৭.িপং িসেলরঃ
াইলশীেট ববত কােডর পিরমাণ কমােত াইেলর িসেলর এবং তৎসংা িনেদশসমূহ একটা পেপ উেখ করা
যায়। যিদ একািধক এিলেমের একই াইল করেত চান তখন িপং িসেলর ববহার করেবন।ধন আপিন চােন
আপনার পেজর সব হিডং এবং িলংক এর রং একই হেব তখন িনেচর মত কের িলখেত পােরন।
h1,h2,h3,h4,a{color:red;}
উপেরা কাডেক আমরা সাধারনভােব িলখতাম-
<style type=”text/css”>
H1{color:red;}
H2{color:red;}
H3{color:red;}
H4{color:red;}
a{color:red;}
</style>
িডকলােরশনসমূহ প করাঃ
<style type=”text/css”>
H1{color : red}
H1{font-family : Arial, Arial black}
109
H1{font-size : 16pt}
</style>
এখেন h1 িসেলেরর জন িতনিট িডকলােরশন দয়া হেয়েছ। এ িতন িডকলােরশনেক প িহেসেব কাশ করা যেত
পাের এভােব-
<style type=”text/css”>
H1{color : red; font-family : Arial, Arial black; font-size : 16pt }
</style>
িবঃঃ িসেলেরর প গঠেনর সময় িসেলরসমূহেক পৃথক করা হয় কমা(,) িদেয় এবং িডকলােরশন িনেয় প গঠেনর
সময় পৃথক করা হয় সিমেকালন (;) িদেয়।
অধায়-তর
িসএসএস িসউেডা াস ও িসউেডা এিলেম
িসএসএস িসউেডা াসঃ
িসএসএস িসউেডা াস ববহার কের িবিভ উপাদােনর অবান, অবা ইতািদ িসেলর ারা িসেল কের শাল
ইেফ দওয়া হয়। াস িসেলেরর মত িসউেডা াস ববহার কের ডকুেমের িবিভ এিলেম িসেল করা যায়।
নিভেগশন বােরর িবিভ মনু িবিভ অবায় কমন দখােব তা িসউেডা াস ারা িনধারণ করা হয়। এছাড়া িবিভ
চাই িসেলেরর ফা চাই িসেল করা সহ আেরা অেনক ধরেণর কাজ িসউেডা াস ারা করা যায়।
িসএসএস িসউেডা ােসর সাধারণ গঠন-
Selector: pseudo class {property: value;}
িসএসএস াসেক িসউেডা ােসর সােথ ববহার করা যায়। যমন-
110
Selector. Class: pseudo class {property: value;}
a.red:visited{color:#FF0000;}
<a class="red" href="css_syntax.asp">CSS Syntax</a>
িসউেডা ােসর কারেভদঃ
১.এংকর িসউেডা াস (Anchor Pseudo class)
২.ফা চাই িসউেডা াস (First child Pseudo-class)
৩.লাুেয়জ িসউেডা াস (lang Pseudo-class)
৪.ফাকাস িসউেডা াস(focus Pseudo-class)
িবিভ িসউেডা ােসর বণনা িনে দওয়া হল-
১.এংকর িসউেডা াসঃ িলংক তিরর জন আমরা সাধারণত এংকর টাগ(<a></a>) ববহার কের থািক এবং
িসএসএস ববহার কের াইল িনধারণ করা হয়। িক আমরা যিদ চাই িবিভ অবার উপর িনভর কের িবিভ ইেফ
(যমনঃ িলংেকর উপর মাউস িনেয় গেল একধরেনর ইেফ, িলংক িভিজট করেল আেরক ধরেণর ইেফ ইতািদ)
দখােত চাই তেব িসএসএস এংকর িসউেডা াস ববহার করেত হেব। িসএসএস-এ মাট চারিট এংকর িসউেডা াস
রেয়েছ-
 a:linkএকিট সাধারণ িলংক যা িভিজট করা হয় িন।
 a:visitedএকটা িলংক যা পূের িভিজট করা হেয়েছ
 a:hoverএিট একিট িলংক যার ঊপর মাউস রাখার সােথ সােথ িভজুয়াল ইেফ দখােব।
 a:activeএিট একিট িলংক যটা বতমােন সিয় আেছ। অনভােব বলা যায় ইউজার যখন িলংেক িক
কের রসপের জন অেপা কের স সমেয়র ইেফ।
একিট উদাহরণ দখুন-
<html>
<head>
<style type="text/css">
a:link {color:#0000FF;} /* unvisited link */
a:visited {color:#FF0000;} /* visited link */
111
a:hover {color:#00FF00;} /* mouse over link */
a:active {color:#000000;} /* selected link */
</style>
</head>
<body>
<a href="http://www.webtechnologyblog.com"
target="_blank">WebTechnologyBlog</a>
</body>
</html>
নাটঃ a:hover-ক অবশই a:link-এর পের িলখেত হেব, এছাড়া a:visited কারকর হেব না। এবং
a:active –ক অবশই a:hover-এর পের িলখেত হেব এছাড়া a:active কারকর হেব না।
২.ফা চাই িসউেডা াসঃ কান এিলেমের থম উপাদান (থম চাই) এর পািট পিরবতন করেত এই াস
ববহার করা হয়। যমন-
<body>
<p>This is first child paragraph</p>
<h2>This is heading</h2>
<p> This is second child paragraph </p>
</body>
এখােন body এর মেধ ইিট পারাাফ এিলেম চাই িহেসেব আেছ। এখন যিদ ধুমা থম পারাাফ
এিলেমের জন াইল তির করেত চাওয়া হয় তাহেল p এর ফা চাই িসউেডা াস িসেলর ববহার করেত হেব।
যমন-
<html>
<head>
112
<style type="text/css">
p:first-child
{
color:blue;
}
</style>
</head>
<body>
<p>This is first child paragraph</p>
<h2>This is heading</h2>
<p> This is second child paragraph </p>
</body>
</html>
এর ফেল থম পারাােফর টেটর রঙ নীল হেব।
Note: For :first-child to work in IE8 and earlier, a <!DOCTYPE> must be
declared.
ফা চাই িসউেডা ােসর কেয়কিট উদাহরণ দখুন-
In the following example, the selector matches the first <i> element in all <p>
elements:
<html>
<head>
<style type="text/css">
p > i:first-child
{
font-weight:bold;
}
</style>
</head>
<body>
113
<p>I am a <i>strong</i> man. I am a <i>strong</i> man.</p>
<p>I am a <i>strong</i> man. I am a <i>strong</i> man.</p>
</body>
</html>
In the following example, the selector matches all <i> elements in <p>
elements that are the first child of another element:
<html>
<head>
<style type="text/css">
p:first-child i
{
color:blue;
}
</style>
</head>
<body>
<p>I am a <i>strong</i> man. I am a <i>strong</i> man.</p>
<p>I am a <i>strong</i> man. I am a <i>strong</i> man.</p>
</body>
</html>
৩.লাুেয়জ িসউেডা াসঃ িবিভ ভাষার জন িবেশষ িকছু িনয়ম িনধারণ করেত লাুেয়জ িসউেডা াস ববহার করা
হয়। িনেচর উদাহরেণ লাুেয়জ িসউেডা াস ববহার কের q element-এ কােটশান িচ দওয়া হেয়েছ
lang="no"-এর সাহােয।
উপেরর িতনিট িসউেডা াস ছাড়াও আরও একিট
114
Note: IE8 supports the :lang pseudo-class only if a <!DOCTYPE> is specified.
৪.ফাকাস িসউেডা াসঃ কান এিলেমেক ফাকাস কেরত :focus িসউেডা াস ববহার করা হয়। ঐ সকল
এিলেমের ে ফাকাস িসউেডা াস ববহার করা হয় যারা ইউজার ইনপুেটর উপর িনভরশীল যমন- টট িফ,
পাসওয়াড িফ ইতািদ। একিট উদাহরণ দখুন-
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html>
<head>
<style type="text/css">
input:focus
{
background-color:yellow;
}
</style>
</head>
115
<body>
<form action="form_action.asp" method="get">
First name: <input type="text" name="fname" /><br />
Last name: <input type="text" name="lname" /><br />
<input type="submit" value="Submit" />
</form>
</body>
</html>
আউটপুটঃ
আমরা যিদ অংেশর িফিটেত িক কির তেব বাকউ হলুদ হেয় যােব অথাৎ ফাকাস করেব।
িসএসএস িসউেডা এিলেমঃ িসএসএস িসউেডা ােসর মেতাই িসএসএস িসউেডা এিলেম ববহার কের িবিভ
উপাদােনর অবান, অবা ইতািদ িসেলর ারা িসেল কের শাল ইেফ দওয়া হয়। াস িসেলেরর মত িসউেডা
এিলেম ববহার কের ডকুেমের িবিভ এিলেম িসেল করা যায়।
িসএসএস িসউেডা এিলেমের সাধারণ গঠন হল-
Selector: pseudo-element {property: value;}
িসএসএস class-ক pseudo-elements-এর সােথ ববহার করা যায়। যমন-
Selector.class: pseudo-element {property: value;}
116
কান পারাােফর থম অর বা থম লাইন কমন দখােব তা িসউেডা ইিলেম ারা িনধারণ করা হয়। এছাড়া কান
পারাাফ বা হিডং এর েত কান ইেমজ, বা িবেশষ কান টট যু করা সহ আেরা অেনক ধরেণর কাজ িসউেডা
ইিলেম ারা করা যায়।
িসউেডা এিলেমের কারেভদঃ
১.থম অর িসউেডা ইিলেম-(First letter Pseudoelement)
২.থম লাইন িসউেডা ইিলেম-(First first line Pseudoelement)
৩.িবেফার িসউেডা ইিলেম (Before Pseudo element)
৪.আফটার িসউেডা ইিলেম (After Pseudo element)
িনে িসএসএস িসউেডা এিলেমেলা িনেয় আেলাচনা করা হল-
১.থম অর িসউেডা ইিলেমঃ থম অর িসউেডা ইিলেমের মাধেম কান পারাােফর বা হিডং এর থম
অরেক িনধািরত াইেল দখােনা যায়।যমন-
P:first-letter{font-weight:bold}
এর ফেল িতিট পারাােফর থম অর বা দখােব।
আউটপুটঃ
first-letter pseudo-element ধুমা এিলেমের ে ববহার করা যায়। িনেচর পািটেলা first-
letter pseudo-element-এ ববহার করা যায়-
 font properties
117
 color properties
 background properties
 margin properties
 padding properties
 border properties
 text-decoration
 vertical-align (only if "float" is "none")
 text-transform
 line-height
 float
 clear
২.থম লাইন িসউেডা ইিলেমঃ থম লাইন িসউেডা ইিলেমের মাধেম কান পারাােফর থম লাইনেক িনধািরত
াইেল দখােনা যায়।যমন-
P:first-line{font-style:bold}
এর ফেল িতিট পারাােফর থম লাইন বা দখােব।
এর ফেল িতিট পারাােফর থম লাইেনর কালার লাল দখােব।
first-line pseudo-element ধুমা block-level elements-এর ে ববহার করা যায়।
িনেচর পািটেলা first-line pseudo-element-এ ববহার করা যায়-
 font properties
 color properties
 background properties
 word-spacing
 letter-spacing
 text-decoration
118
 vertical-align
 text-transform
 line-height
 clear
৩.িবেফার িসউেডা ইিলেমঃ িবেফার িসউেডা ইিলেম ববহার কের কান কনেটের সামেন আেরকিট কনেট ইনসাট
করা যায়। এটা আমােদর অেনক কােজ লাগেব। িনেচর উদাহরেণ আমরা দিখেয়িছ কীভােব িতিট হিডং-এর সামেন
একিট ইেমজ ইনসাট করা যায়।
ইেমজ ইনসােটর জন িলখেত হেবঃ
Selector:before{content:url(image_name.image_format);}
অনান ে িলখেত হেব-
Selector:before{content:” য কনেটেক অন কনেটের সামেন দখােত চান তা এই কােটসােনর মােঝ
িলখুন।”;}
119
একিট উদাহরণ দখুনঃ
p:before
{
content:"Read this -";
background-color:yellow;
color:red;
font-weight:bold;
}
৪.আফটার িসউেডা ইিলেমঃ আফটার িসউেডা ইিলেম ববহার কের কান কনেটের পের আেরকিট কনেট ইনসাট
করা যায়। এটা আমােদর অেনক কােজ লাগেব। িনেচর উদাহরেণ আমরা দিখেয়িছ কীভােব িতিট হিডং-এর পের একিট
ইেমজ ইনসাট করা যায়।
অনান ে িলখেত হেব-
Selector: after {content:” য কনেটেক অন কনেটের পের দখােত চান তা এই কােটসােনর মােঝ
িলখুন।”;}
একিট উদাহরণ দখুনঃ
120
Output:
িসেলর
:link
:visited
:active
:hover
:focus
:first-letter
:first-line
:first-child
:before
:after
িসএসএস-এ ববত সকল িসউেডা াস/ এিলেম
উদাহরেণর বণনা
a:link
a:visited
a:active
a:hover
িভিজট করা হয়িন এমন িলংক।
িভিজট করা হেয়েছ এমন িলংক।
সিয় িলংক।
মাউস ওভাের িলংেকর ইেফ।
input:focus ইনপুেটর কান এিলেমেক ফাকাস কের।
p:first-
letter
িতটা পারাােফর থম বণেক িসেল কের।
p:first-line িতটা পারাােফর থম লাইনেক িসেল কের।
p:first-child িতটা পারাােফর থম চাইেক িসেল কের।
পারাােফর সামেন নুতন কান এিলেম ইনসাট কের।
p:before
p:after
:lang(language) p:lang(it)
পারাােফর িপছেন নুতন কান এিলেম ইনসাট কের।
Selects every <p> element with a lang attribute
value starting with "it"
উদাহরণ
121
অধায়-চৗ
[িসএসএস িডসে ও িভিজিবিলিট পািট]
িসএসএস িডসে পািটঃ
কান উপাদান কীভােব ডকুেমে দিশত হেব তা িনেদশ করা হয় display পািটর মাধেম।এই পািট সব উপাদান
ও িমিডয়ার ে ববত হেত পাের। িডসে াপািটর বশ িকছু value হেত পাের, এেদর মেধ সবেচেয় বিশ
বাবত হয়,
 িডসে নান -(display:none)
 িডসে ইন লাইন -(display:inline)
 িডসে ক – (display:block)
িডসে নান -(display:none) কান িবেশষ উপদানেক দশন না করার জন িডসে নান ববহার করা হয়,
এজন Declaration করেত হয় display:none;।এর মান দওয়া হেল কান ব তির হেব না এবং ীন-এ
িকছু দখা যােব না। ওই উপাদােনর চাই যারা তােদর জনও কান ব তির হেব না। যমন-
<html>
<head>
<style type="text/css">
h1.hidden {display:none;}
</style>
</head>
<body>
122
<h1>This is a visible heading</h1>
<h1 class="hidden">This is a hidden heading</h1>
<p>Notice that the hidden heading does not take up space.</p>
</body>
</html>
কাড িবেষণঃ display:none ববহােরর ফেল This is a hidden heading লখািট উজাের দখা যােব
না।
িডসে ইন লাইন -(display:inline) িস এস এস এর মাধেম এইচিটএমএল উপাদান সমূহেক একই লাইেন
দশেনর জন িডসে ইন লাইন ববহার করা হয়। এর ফেল উপাদানিট ইনলাইন উপাদান িহেসেব দিশত হেব অথাৎ
এর আেগ বা িপেছ লাইন ক তির হেব না। এটা মূলত সবেচেয় বিশ বাবত হয় নিভেগশন বাের।এইচিটএমএল
উপাদান সমূহেক একই লাইেন দশেনর জন Declaration করেত হয় display:inline।
<html>
<head>
<style type="text/css">
li{display:inline;}
</style>
</head>
<body>
<p>Display this link list as a horizontal menu:</p>
<ul>
<li><a href="../html/index.php" target="_blank">HTML</a></li>
123
<li><a href=" index.php " target="_blank">CSS</a></li>
<li><a href="../js/ index.php " target="_blank">JavaScript</a></li>
<li><a href="../xml/ index.php " target="_blank">XML</a></li>
</ul>
</body>
</html>
আউটপুটঃ
কাড িবেষণঃ display:inline ববহােরর ফেল িল আইেটমেলা এক লাইেন দখাে।
িডসে ক – (display:block) িস এস এস এর মাধেম এইচিটএমএল উপাদান সমূহেক একই কলােম
দশেনর জন িডসে ক ববহার করা হয়। এর মান দয়া হেল ঐ উপাদান একিট ক িহেসেব কাজ করেব, অথাৎ সিট
ক লেভল উপাদােনর মেতাই আেগ বা িপেছ লাইন ক তির করেব। এটা সবেচেয় বিশ বাবত হয় ভািটকাল
নিভেগশন বাের।
িনেচর উদাহরেণ display পািটর ববহার দখােনা হল-
<html>
<head>
<style>
ul
{
list-style-type:none;
margin:0;
124
padding:0;
}
a
{
display:block;
width:60px;
}
</style>
</head>
<body>
<ul>
<li><a href="#home">Home</a></li>
<li><a href="#news">News</a></li>
<li><a href="#contact">Contact</a></li>
<li><a href="#about">About</a></li>
</ul>
</body>
</html>
125
আউটপুটঃ
কাড িবেষণঃ display: block ববহােরর ফেল িল আইেটমেলা লালি (ভািটকাল) দখাে এবং এরা একিট
ক তির কেরেছ।
িভিজিবিলিট পািটঃ
কান উপাদান াউজাের দখা যােব (visible), না িক দখা যােব না (hidden) তা িনধারণ করা হয় visibility
পািটর মাধেম। এর িট মান হেত পাের-visible ববহার করা হেল ঐ উপাদান দৃশমান হেব, আর hidden
ববহার করা হেল তা দখা যােব না।
কান উপাদানেক দশন করার জন Declaration করেত হয়
visibility:visible;। visibility:hidden ববহার করা হেল ঐ উপাদান দখা না গেলও তার জন য
পিরমাণ জায়গা বরা আেছ তা ফঁাকা দখা যােব অথাৎ লআউেটর উপর ভাব থেক যােব। display :none
ববহার করা হেল সই উপাদান দখা যায় না এবং স ান দখল কের নয় অন উপাদান। display পািটর সােথ
visibility পািটর পাথক এখােনই। িনেচর উদাহরেণ এিট দখােনা হল-
<html>
<head>
<style type="text/css">
h1.hidden {visibility:hidden;}
</style>
</head>
<body>
<h1>This is a visible heading</h1>
126
<h1 class="hidden">This is a hidden heading</h1>
<p>Notice that the hidden heading still takes up space.</p>
</body>
</html>
আউটপুটঃ
127
===সমা=