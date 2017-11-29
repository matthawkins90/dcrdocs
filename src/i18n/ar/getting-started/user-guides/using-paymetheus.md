# محفظة الدفع من ويندوز

هذا الدليل يفترض انك تلقائيا لتعيين محفظة الدفع باستخدام [هذا الدليل](paymetheus.md).

---

## النظرة العامة

تقدم علامة التبويب "نظرة عامة" ملخصا سريعا لاجمالي DCR (قابل للإنفاق والمؤمن), وعدد الحسابات والمعاملات  فضلا عن قائمة نشاط الحساب الأخير.

![Overview tab](/img/Paymetheus-overview.png)  

---

## الحسابات

تعرض علامة التبويب في محفظتك ويسمح لك بإضافة الجديد منها.  أنها تسمح لك للحفاظ على سجلات منفصلة من dcr الخاص بك. هذه الميزة هي الأكثر لأولئك الذين يديرون الشركات و ترغب في الاحتفاظ حسابات منفصلة على سبيل المثال. سيتم نقل dcr عبر الحسابات إنشاء معاملة على سلسلة كتلة.

![Overview tab](/img/Paymetheus-accounts.png)  

---

## المخطوطات

الاستخدام الحالي ل PoS في التجمعات. هو كما في الإصدار 0.8.0 ليتم إعداد المخطاطات.  ثم راجع قسم شراء التذاكر أدناه للحصول على مزيد من المعلومات. سيتم استخدامه لمزيد من الميزات المتقدمة في المستقبل.

![جدول المخطوطات](/img/Paymetheus-import-script.png)  

---

## إنشاء المعاملات

في هذا الجدول يمكنك معرفة كيفية إرسال الرسوم لعنوان أخر. من خلال نسخ ما وصل الى عنوانك من خلال مربع النص ونوع في كمية من فكري كنت ترغب في إرسال. حيث سيتم سرد الرسوم المقدرة أيضا. يمكنك النقر فوق زر '+' لإرسال Decred إلى عناوين متعددة وذلك في  معاملة واحدة إذا كنت ترغب في ذلك.

![Create transaction tab](/img/Paymetheus-send.png)  

---

## جدول شراء التذاكر

قابلية الدفع يمكن فيها شراء التذاكر من قبل للدليل على التعدين حصة باستخدام دليلها شراء التذاكر الميزات. ولاحظ أن الدفع يمكن فقط * شراء * تذاكر، فإنه لا يمكن القيام التصويت الفعلي وذلك سوف يحتاج إما لإعداد [منفردا PoS] (/ التعدين / إثبات-of-stake.md) استخدام PoS [تجمع حصة](/mining/proof-of-stake.md#list-of-stakepools).

> للاشتراك في التجمع, تابع الجدول العام لعنوان الذي يمكن استخدامه للحصول على > 1-من-2 متعدد التوقيع النصي. حيث أن التوقيع النصي المتعدد سوف يتم بالحصول على> التجمع   وذلك جنبا إلى جنب مع عنوان P2SH لإعطاء حقوق التصويت له.

لا تقلق إن لم تفهم ما ذكر هنا. ماذا تعني بإنشاء العنوان الذي يمكنه إدخالك الى المحفظتين. واحدة من المحافظ يجب أن تكون متاحة وذلك من خلال إستخدام العنوان. وهذا يعني أن التجمع يمكن التصويت به ويمكن أيضا من خلال المحفظة الخاصة بك لإيقاف عملها.

إذا لم يتم إعطاءك التجمع لدخولك من خلال الأموال.  فإن كل ما تقومون به هو منح حقوق التصويت إلى التجمع. بحيث لا يقوم التجمع بلمس أي من أموالك.

تجمع الحصص الرسمي  [وضع هنا](/mining/proof-of-stake.md#list-of-stakepools). وتدير جميع مجموعات الأسهم نفس الشيفرة الأساسية، ولكنها قد تختلف في مقدار التكرار المتاح.  مزيد من التكرار يساوي فرصة أقل من الأصوات الفائتة (على الرغم من أن جميع الأصوات حيث أن العديد من الأصوات الفائتة ناجمة عن عمال المناجم (في بعض الأحيان سوف يجدون حلا سريعا للكتل حول الأصوات لم يكن لديك الوقت لنشر حول الشبكة).   لكي تصبح من أجل ضمان تجمع واحد فإن من المستحسن أن تضاف إلى تجمعات صغيرة. مع الضمان بأنهم لا يستطيعون الحصول على أي من أموالك, يمكنهم اختيار التصويت ضد رغباتكم. فعل ذلك سيكون لهم ضمن القائمة السوداء. ولكن الحفاظ على الأحجام والوسائل المنخفضة سوف تكون ذات صعوبات أكبر في التأثير وذلك نتيجة لأي تصويت. من خلال نشر التذاكر حول التجمعات، فإنه يجعل الشبكة الأكثر مركزية.

![إنشاء حساب تصويت](/img/Paymetheus-create-voting-account.png)

هناك قدر معقول من المعلومات هنا، لذلك سنذهب من خلال كل من الخيارات.

* ** صعوبة التذاكر** - السعر الحالي للتذكرة.
* ** كتل حتى إعادة الهدف ** - عندما يصل هذا 0، يتم احتساب سعر تذكرة جديدة.
* ** حساب المصدر ** - هذا الحساب يستخدم لشراء تذاكر والحصول على مكافأة.
* ** تذاكر لشراء ** - عدد التذاكر التي تم شرائها.
* ** رسوم التذاكر (DCR/kB)** - حيث يتم إدخال التذاكر في تجمع التصويت بأمر من رسومهم. وفي أوقات ارتفاع الطلب،سوف تحتاج إلى زيادة هذه القيمة من أجل الحصول على التذاكر الخاصة بك لتعد مقبولة. يمكنك رؤية رسوم التذاكر الحالية  [هنا](https://www.dcrstats.com). 33
* ** رسوم سبليت  (DCR/kB)** -  يتم إستخدام الدفع "split" للمعاملات وذلك لتجنب توازن الكتل, المبلغ المطلوب بالضبط لتذكرة من الرصيد في محفظتك.   ويتعين تأكيد "الانقسام" مرة واحدة على الأقل و يمكنك إعادة استخدام رصيدك. حيث يمكن  أن يؤدي ذلك إلى منع رصيدك بالكامل لعدة دقائق في حين يحدث هذا التأكيد. دون انقسام، سيكون لديك لإنتظار تأكيده صفقة التذكرة, والتي يمكن أن تستغرق عدة ساعات. بحيث يمكن ترك هذا في 0.01. أنها لا تؤثر على فرصك على شراء التذاكر والتصويت معهم.

* ** انتهاء الصلاحية (كتل) ** - في كثير من الأحيان سوف تزيد رسوم التذاكر خلال نافذة التي قد توقفت عن طريق ارتفاع الرسوم. من خلال إعداد إنتهاء الصلاحية, سوف يتم إلغاء التذاكر التي لم يتم استخراجها من قبل كتلة معينة حتى تتمكن من المحاولة مرة أخرى مع ارتفاع الرسوم إذا كنت ترغب في ذلك. وفي حال كان هذا فارغ، فإنها لن تنتهي حتى نهاية النافذة.

* ** تفضيل حصة البرك** - تلقائياُ سيتم الإعداد مع PoS.  انظر أدناه للحصول على مزيد من المعلومات.
* ** عنوان التصميم** - فإن عنوان Decred الذي سوف يجري للتصويت. بشكل منفرد أو تجمع العمالين المخصص فقط.
* **عنوان رسوم البرك** - بالنسبة لأولئك الذين يستخدمون تجمعات مخصصة
* ** رسوم البرك (%)** - لهؤلاء الذين يستخدمون تجمعات مخصصة

![شراء التذاكر](/img/Paymetheus-ticket-purchasing.png)  

لإعداد شراء التذاكر بسهولة لمجمع حصة، انقر فوق  'Manage pools button'.  إذا لم تكن قد فعلت ذلك من قبل، فسوف تحتاج إلى التسجيل في مجموعة أسهم (انظر أعلاه). بمجرد التسجيل، ثم بتسجيل الدخول، وابحث عن مفتاح API الخاص بك، وقم بنسخه. وحدد بركة التي قمت بالتسجيل بها مع من القائمة المنسدلة. الصق المفتاح في صندوق  'API key' و إنقرعلى  'Save'. سترى مجموعة من الحروف والأرقام تظهر في المربع السفلي. ثم إنقر على 'Close'. والأن يمكنك شراء  التذاكر من خلال الضغط على  'Purchase'  في الأسفل!

![إدارة تعدين الحصص](/img/Paymetheus-manage-stake-pool.png)

ملاحظة: في حين يمكنك شراء تذاكر باستخدام الدفع، فإنه لا يمكن التصويت بالنسبة لك لذلك يجب عليك إما استخدام البرك أو تشغيل الخاصة بك لتصويت المحفظة التي تحتاج إلى أن تكون على الانترنت 24/7. إذا كنت تفضل الحصص المنفردة قم بالتحقق من [dcrdدليل إعدادات](/getting-started/user-guides/dcrd-setup.md), [dcrwallet ودليل إعدادت](/getting-started/user-guides/dcrd-setup.md) and [PoS دليل تعدين](/mining/proof-of-stake.md)  للحصول على المزيد من المعلومات

---

## طلب الدفع

في هذا المكان يمكن أن تولد عناوين المحفظة لإعطاءهت لغير أشخاص ليتمكنوا من إرسال DCR إليك. ببساطة قم باختيار الحساب الذي تريد وضع الأموال به واضغط على إنشاء عنوان. وقم بنسخ العنوان (حيث تقع في السطر العلوي الذي يبدأ مع Ds) وتقاسم ذلك مع الشخص الآخر. عناويين Decred يمكن إستخدامها للعديد من المرات إذا كنت تريد, ولكن للأسباب الخاصة فإنه من الأفضل إنشاء واحدة جديدة لكل من المعاملات. وهنالك ما يقارب  1.4E48 ( 14 تليها 47 الأصفار) أي العناوين المتاحة لذلك لا داعي للقلق حول نفادها.

![طلب الدفع](/img/Paymetheus-receive.png)  

---

## تاريخ المعاملات

تعرض علامة التبويب هذه قائمة بجميع المعاملات التي حدثت. وتجزئة هذه المعاملات يمكن إستخدامها مع [مستكشف الكتل] (/getting-started/using-the-block-explorer.md)  لرؤية المزيد من المعلومات حول المعاملات.

![تاريخ المعاملات](/img/Paymetheus-transactions.png)  

---

## حصة التعدين

هذا الجدول يظهر بعض الإستراتيجيات لشبكة PoS:

بند                         | الوصف
:-----------------------------:|:------------------------------------------------------------:
عدد التذاكر الفعالة       | العدد الإجمالي للتذاكر التي يحق لها التصويت عبر الشبكة
عدد التذاكر في البركة | العدد الإجمال للتذاكر ينتظر أن يتم إدخاله في برك التصويت
صعوبة التذاكر            | تكلفة التذكرة ( ردها على تذكرة التصويت / انتهاء الصلاحية)
تملك التذاكر في البرك     | عدد التذاكر الخاصة بك في البرك
تملك التذاكر الحية           | عدد تذاكرك المؤهلة للتصويت
تملك تذاكر غير صحيحة       | عدد التذاكر المنتظرة لتكون صحيحة قبل أن تصبح حية (256 كتلة, ~17 ساعة)
التذاكر المفقودة               | التذاكر التي يتم التصويت لها بسبب محفظة التصويت أو حصة التعدين بحال كانتا مطفأتان او عامل PoW لم يقم بالتنجيم بشكل صحيح.
تم إلغاء التذاكر              | التذاكر التي غابت عن التصويت وكان لديهم سعر التذكرة ردها (ناقص رسوم التذكرة)، يجب أن يكون نفس التذاكر المفقودة
تذاكر التصويت                | تذاكر مدى الحياة صوتت من قبل هذه المحفظة
مجموع الدعم المكتسب         | دعم DCR لمدى الحياة المكتسبة من هذه المحفظة