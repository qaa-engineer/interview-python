# interview-python
Популярные вопросы на собеседовании про Python

<div class="td-post-content tagdiv-type">

<p>Многие начинающие ученые в области данных начали свое путешествие по науке о данных с языка программирования Python. Почему Python? Потому что он легок в освоении и сегодня его используют многие компании. Более того, этот язык универсальный и предназначен не только для специалистов по обработке данных, но также используется и в целях разработчиков.</p>
<p>Когда вы подаете заявку на должность специалиста по обработке данных, многие компании просят пройти собеседование на работу на знание этого языка. Я попытаюсь изложить вопросы, которые собрал из многих источников и собственного опыта. Постараюсь выбрать наиболее популярные.</p>
<h3 id="h-1-python">1. Что такое&nbsp;Python?</h3>
<p>Python — это язык программирования с объектами, модулями, потоками, исключениями и автоматическим управлением памятью. Python предназначен для высокой читабельности. Он часто использует английские ключевые слова, в то время как другие языки используют пунктуацию, и у него меньше синтаксических конструкций, чем у других языков.</p>
<h3 id="h-2-python">2. Каковы преимущества использования Python?</h3>
<p>Они заключаются в том, что он прост, удобен, портативен, расширяем, имеет встроенную структуру данных и открытый исходный код.</p>
<h3 id="h-3-python">3. Как Python интерпретируется как&nbsp;язык?</h3>
<p>Интерпретируемый язык — это любой язык программирования, который не находится в машинном коде до выполнения. Таким образом, Python им и является.</p>
<h3 id="h-4-python">4. Как интерпретируется Python?</h3>
<p>Программа Python запускается непосредственно из исходного кода, написанным программистом. Язык преобразует его в промежуточный код, который снова переводится на машинный язык, который затем уже должен быть выполнен.</p>
<h3 id="h-5-python">5. Как в Python управляется память?</h3>
<ul><li>Память в Python управляется приватным пространством кучи Python. В ней расположены все объекты и структуры данных Python. Об этой куче заботится сам интерпретатор Python, а программист не имеет к ней доступа.</li><li>Менеджер памяти Python заботится о выделении частного пространства кучи.</li><li>Память для пространства кучи Python предоставляется встроенным сборщиком мусора, который перерабатывает и освобождает всю неиспользуемую память.</li></ul>
<h3 id="h-6-pep-8">6. Что такое PEP&nbsp;8?</h3>
<p>PEP расшифровывается как Python Enhancement Proposal (Предложение по улучшению Python). Это набор правил, которые определяют, как форматировать код для максимальной читабельности.</p>
<h3 id="h-7-python">7. Как писать комментарии на&nbsp;Python?</h3>
<p>Комментарии начинаются с символа #.</p>
<p><code>#Пример комментария</code></p>
<h3 id="h-8-python">8. Как прокомментировать несколько строк в&nbsp;Python?</h3>
<p>Многострочные комментарии появляются на нескольких строках. Все строки, подлежащие комментарию, должны иметь префикс #. Можно использовать метод быстрого доступа, чтобы прокомментировать несколько строк. Все, что нужно сделать, — это удерживать клавишу ctrl и щелкнуть левой кнопкой мыши в том месте, где вы хотите включить символ #, и ввести # только один раз. Это закомментирует все строки, на которых щелкнули курсором.</p>
<h3 id="h-9-python">9. Что такое строки документации в&nbsp;Python?</h3>
<p>Docstrings не являются комментариями, это с<em>троки документации</em>. Они заключены в тройные кавычки. Такие строки не привязаны ни к одной переменной, и поэтому иногда служат в качестве комментариев.</p>
<pre class="wp-block-code"><code class="hljs python"><span class="hljs-string">""" 
Это строка документации
Она используется для документирования
"""</span></code></pre>
<h3 id="h-10-python">10. Обязательны ли отступы в&nbsp;Python?</h3>
<p>Отступ в Python является обязательным и является частью его синтаксиса.</p>
<p>Все языки программирования имеют некоторый способ определения объема и масштаба блока кодов — в Python это отступ. Отступ обеспечивает лучшую читабельность кода, и именно поэтому он обязателен.</p>
<h3 id="h-11-python">11. Что такое функция в&nbsp;Python?</h3>
<p>Функция — это блок кода, который выполняется только при его вызове. Для определения функции Python используется ключевое слово def. Если функция возвращает что-то, ей нужно ключевое слово return.</p>
<pre class="wp-block-code"><code class="hljs python"><span class="hljs-function"><span class="hljs-keyword">def</span> <span class="hljs-title">example</span><span class="hljs-params">(a)</span>:</span>
   <span class="hljs-keyword">return</span> a*<span class="hljs-number">2</span></code></pre>
<h3 id="h-12-python">12. Что такое локальные и глобальные переменные в&nbsp;Python?</h3>
<p><strong><em>Глобальная переменная:</em></strong></p>
<p>Переменные, объявленные вне функции или в глобальном пространстве, называются глобальными. Они могут быть доступны любой функции в программе.</p>
<p><strong><em>Локальная переменная:</em></strong></p>
<p>Любая переменная, объявленная внутри функции, называется локальной. Она присутствует в локальном пространстве, а не в глобальном.</p>
<pre class="wp-block-code"><code class="hljs python"><span class="hljs-comment">#Пример глобальной переменной</span>
a = <span class="hljs-number">1</span>

<span class="hljs-comment">#Пример локальной переменной</span>
<span class="hljs-function"><span class="hljs-keyword">def</span> <span class="hljs-title">sample</span><span class="hljs-params">()</span>:</span>
   <span class="hljs-comment">#Локальная переменная</span>
   a = <span class="hljs-number">1</span></code></pre>
<h3 id="h-13">13. Что такое лямбда-функция?</h3>
<p>Анонимная или неназванная функция называется лямбда-функцией. Она может иметь любое количество параметров, но только один оператор. Она часто используется как одноразовая функция, а не многоразовая.</p>
<pre class="wp-block-code"><code class="hljs bash"><span class="hljs-comment">#Пример лямбда-функции</span>

<span class="hljs-built_in">test</span> = lambda x,y: x*y
<span class="hljs-built_in">print</span>(<span class="hljs-built_in">test</span>(2,4))</code></pre>
<h3 id="h-14-python">14. Почему лямбда-формы в Python не имеют операторов?</h3>
<p>Потому что они используются для создания нового объекта функции, а затем возвращают его во время выполнения.</p>
<h3 id="h-15-python">15. Какие типы данных поддерживаются в&nbsp;Python?</h3>
<p>Python имеет пять стандартных типов данных −</p>
<p>• число (целочисленные и с плавающей запятой);</p>
<p>• строка;</p>
<p>• список;</p>
<p>• кортеж;</p>
<p>• словарь.</p>
<h3 id="h-16">16. Что такое&nbsp;индексы?</h3>
<p>Чтобы получить доступ к элементу из упорядоченных последовательностей, мы используем его индекс, который является номером позиции этого конкретного элемента. Индекс обычно начинается с 0, то есть первый элемент имеет индекс 0, второй — 1 и так далее.</p>
<pre class="wp-block-code"><code class="hljs nginx"><span class="hljs-comment">#Пример использования индекса</span>

<span class="hljs-attribute">list_ex</span> = [<span class="hljs-number">1</span>,<span class="hljs-number">2</span>, <span class="hljs-string">'Test'</span>]
print(list_ex[<span class="hljs-number">0</span>])</code></pre>
<h3 id="h-17">17. Что такое отрицательные индексы и почему они используются?</h3>
<p>Когда мы используем индекс для доступа к элементам из конца списка, это называется обратным индексированием. При нем индексация элементов начинается с последнего элемента с индексом -1. Второй последний элемент имеет индекс “-2” и так далее. Они называются отрицательными.</p>
<pre class="wp-block-code"><code class="hljs nginx"><span class="hljs-comment">#Пример использования индекса</span>

<span class="hljs-attribute">list_ex</span> = [<span class="hljs-number">1</span>,<span class="hljs-number">2</span>, <span class="hljs-string">'Test'</span>]
print(list_ex[-<span class="hljs-number">1</span>])</code></pre>
<h3 id="h-18-python">18. Что такое словарь в&nbsp;Python?</h3>
<p>Словарь Python — это один из поддерживаемых типов данных. Это неупорядоченная коллекция элементов. Элементы в словарях хранятся в виде пар ключ-значение. Словари индексируются по ключам. Тип данных представлен в виде <code>{}</code>.</p>
<pre class="wp-block-code"><code class="hljs ini"><span class="hljs-comment">#Пример словаря</span>

<span class="hljs-attr">dictionary</span> = {<span class="hljs-string">'key'</span> : <span class="hljs-string">'value'</span>}
</code></pre>
<h3 id="h-19">19. Как получить доступ к значениям в&nbsp;словаре?</h3>
<p>Вы можете получить доступ к значениям в словаре, индексируя их с помощью ключа. Индексация представлена в виде <code>[]</code>.</p>
<pre class="wp-block-code"><code class="hljs python"><span class="hljs-comment">#Доступ к словарю</span>

dictionary = {<span class="hljs-string">'key'</span> : <span class="hljs-string">'value'</span>}
print(dictionary[<span class="hljs-string">'key'</span>])</code></pre>
<h3 id="h-20">20. Как получить список всех ключей в&nbsp;словаре?</h3>
<p>Можно использовать атрибут, который есть у словаря — keys().</p>
<pre class="wp-block-code"><code class="hljs python">dictionary = {<span class="hljs-string">'key'</span> : <span class="hljs-string">'value'</span>, <span class="hljs-string">'key1'</span>: : <span class="hljs-string">'value1'</span>}
print(dictionary.keys())</code></pre>
<h3 id="h-21">21. В чем разница между списком и кортежем?</h3>
<p>Разница между списком и кортежем заключается в том, что список является изменяемым, а кортеж — нет. Кортеж может быть хэширован, например, в качестве ключа для словарей. Список определяется с помощью <code>[]</code>, а кортеж — с помощью <code>()</code>&nbsp;.</p>
<pre class="wp-block-code"><code class="hljs ini"><span class="hljs-comment">#Пример списка и кортежа</span>

<span class="hljs-comment">#Список</span>
<span class="hljs-attr">list_ex</span> = [<span class="hljs-number">1</span>,<span class="hljs-number">2</span>,<span class="hljs-string">'test'</span>]

<span class="hljs-comment">#Список изменяем</span>
<span class="hljs-attr">list_ex[0]</span> = <span class="hljs-number">100</span>

<span class="hljs-comment">#Кортеж</span>
<span class="hljs-attr">tuple_ex</span> = (<span class="hljs-number">1</span>,<span class="hljs-number">2</span>,<span class="hljs-string">'test)

#Кортеж неизменяем
tuple_ex[0] = 100 #Вернет ошибку</span></code></pre>
<h3 id="h-22-python">22. Что такое итераторы в&nbsp;Python?</h3>
<p>В Python итераторы используются для итерации группы элементов, контейнеров, таких как список или строка. Под итерацией подразумевается, что что-то может быть зациклено с помощью оператора.</p>
<h3 id="h-23-1">23. Что делает [::&nbsp;-1}?</h3>
<p>[:: -1] используется для обратного порядка любого итерируемого объекта.</p>
<pre class="wp-block-code"><code class="hljs makefile"><span class="hljs-comment">#Пример печати с конца</span>

string = 'this is a string'
<span class="hljs-section">print(string[::-1])</span></code></pre>
<h3 id="h-24-python">24. Как можно использовать тернарные операторы в&nbsp;Python?</h3>
<p>Тернарный оператор — это оператор, который используется для отображения условных операторов. Он состоит из истинных или ложных значений с утверждением, которое нужно проверить.</p>
<pre class="wp-block-code"><code class="hljs python"><span class="hljs-comment">#Пример тернарного оператора</span>

a = <span class="hljs-number">1</span>

<span class="hljs-comment">#Значения true</span>
<span class="hljs-keyword">if</span> a &lt; <span class="hljs-number">1</span>:
   print(<span class="hljs-string">'Less'</span>)
<span class="hljs-comment">#Если не выполнилось предыдущее значение</span>
<span class="hljs-keyword">else</span>:
   print(<span class="hljs-string">'More'</span>)</code></pre>
<h3 id="h-25-break">25. Как работает&nbsp;break?</h3>
<p>Оператор break позволяет завершить цикл, когда выполняется некоторое условие, и управление передается следующему оператору.</p>
<pre class="wp-block-code"><code class="hljs python"><span class="hljs-comment">#Пример break</span>

<span class="hljs-keyword">for</span> i <span class="hljs-keyword">in</span> range(<span class="hljs-number">5</span>):
   <span class="hljs-keyword">if</span> i &lt; <span class="hljs-number">3</span>:
      print(i)
   <span class="hljs-keyword">else</span>:
      <span class="hljs-keyword">break</span></code></pre>
<h3 id="h-26-pass-python">26. Каков смысл оператора pass в&nbsp;Python?</h3>
<p>Оператор pass в Python используется, когда выражение требуется синтаксически, но вы не хотите, чтобы какая-либо команда или код выполнялись.</p>
<pre class="wp-block-code"><code class="hljs python"><span class="hljs-comment">#Пример pass</span>

<span class="hljs-keyword">for</span> i <span class="hljs-keyword">in</span> range(<span class="hljs-number">10</span>):
   <span class="hljs-keyword">if</span> i%<span class="hljs-number">2</span> == <span class="hljs-number">0</span>:
      print(i)
   <span class="hljs-keyword">else</span>:
      <span class="hljs-keyword">pass</span></code></pre>
<h3 id="h-27-map-python">27. Что такое функция map в&nbsp;Python?</h3>
<p>map() — это функция, которая принимает другую в качестве аргумента, а затем применяет её ко всем элементам итератора, передаваемым ей в качестве другого аргумента. Функция вернет объект map, поэтому нам нужно преобразовать его в объект списка.</p>
<pre class="wp-block-code"><code class="hljs python"><span class="hljs-comment">#Пример функции map</span>

<span class="hljs-function"><span class="hljs-keyword">def</span> <span class="hljs-title">number_exponential</span><span class="hljs-params">(num)</span>:</span>
   <span class="hljs-keyword">return</span> num**<span class="hljs-number">2</span>

number_list = [<span class="hljs-number">2</span>,<span class="hljs-number">3</span>,<span class="hljs-number">4</span>,<span class="hljs-number">5</span>]

print(list(map(number_exponential, number_list)))</code></pre>
<h3 id="h-28-enumerate-python">28. Что такое функция enumerate в&nbsp;Python?</h3>
<p>Метод enumerate() добавляет счетчик к итерируемому и возвращает его в виде объекта перечисления (enumerate). Объект будет состоять из счетчика и итерационных значений.</p>
<pre class="wp-block-code"><code class="hljs python"><span class="hljs-comment">#Пример enumerate</span>

iter_example = [<span class="hljs-string">'test'</span>, <span class="hljs-string">'test2'</span>, <span class="hljs-string">'test3'</span>]
<span class="hljs-keyword">for</span> idx, val <span class="hljs-keyword">in</span> enumerate(iter_example):
   print(idx)
   print(val)</code></pre>
<h3 id="h-29-python">29. Что такое абстракции у словаря и списка в&nbsp;Python?</h3>
<p>Они представляют собой синтаксические конструкции, облегчающие создание словаря или списка на основе существующих итеруемых. Создание происходит циклом внутри самого объекта.</p>
<pre class="wp-block-code"><code class="hljs python"><span class="hljs-comment">#Абстракция словаря</span>

dict_comprehension = {key:val <span class="hljs-keyword">for</span> key, val <span class="hljs-keyword">in</span> emumerate(<span class="hljs-string">'sample'</span>)}
print(dict_comprehension)

<span class="hljs-comment">#Абстракция списка</span>

list_comprehension = [i <span class="hljs-keyword">for</span> i <span class="hljs-keyword">in</span> range(<span class="hljs-number">5</span>)]
print(list_comprehension)</code></pre>
<h3 id="h-30-slicing-python">30. Что такое slicing в&nbsp;Python?</h3>
<p>Slicing (отсечение) — это механизм выбора диапазона элементов из таких типов последовательностей, как список, кортеж, строки и т.д. Такое отсечение выполняется методом индексации.</p>
<pre class="wp-block-code"><code class="hljs nginx"><span class="hljs-comment">#Пример отсечения</span>

<span class="hljs-attribute">list_example</span> = [<span class="hljs-number">1</span>,<span class="hljs-number">2</span>,<span class="hljs-number">3</span>,<span class="hljs-number">4</span>,<span class="hljs-string">'test'</span>,<span class="hljs-string">'test2'</span>]
print(list_example[<span class="hljs-number">1</span>:<span class="hljs-number">4</span>])</code></pre>
<h3 id="h-31-not">31. Каков смысл not в операторе?</h3>
<p>Операторы — это специальные функции. Они принимают одно или несколько значений и дают соответствующий результат. <code>not</code> вернет обратное логическое значение.</p>
<pre class="hljs python"><code class="hljs">print(<span class="hljs-keyword">not</span> <span class="hljs-number">1</span> == <span class="hljs-number">2</span>)</code></pre>
<h3 id="h-32-python">32. Каков смысл <code>//</code> в&nbsp;python?</h3>
<p>Это оператор целочисленного деления, который используется для деления двух операндов с результатом, показывающим только цифры перед десятичной точкой.</p>
<pre class="hljs php"><code class="hljs"><span class="hljs-keyword">print</span>(<span class="hljs-number">5</span><span class="hljs-comment">//2)</span></code></pre>
<h3 id="h-33">33. Как добавить новое значение в объект&nbsp;списка?</h3>
<p>Это можно сделать с помощью атрибута append(), который есть у списка. При передачи какого-то значения в этот атрибут, оно будет помещено в конец последовательности.</p>
<pre class="wp-block-code"><code class="hljs makefile">list_example = [1,2,3,4,5]
list_example.append(6)
print(list_example)</code></pre>
<h3 id="h-34">34. Что такое поверхностная копия?</h3>
<p><em>Поверхностная копия</em> используется при создании нового типа экземпляра и сохраняет значения, скопированные в новом. Также она используется для копирования ссылочных указателей. Это означает, что когда мы копируем объект в другую переменную, он будет привязан.</p>
<pre class="wp-block-code"><code class="hljs makefile"><span class="hljs-comment">#Пример поверхностной копии</span>

list_example = [1,2,3,4,5]
another_list = list_example
another_list[0] = 100
print(list_example)</code></pre>
<h3 id="h-35">35. Что такое глубокая&nbsp;копия?</h3>
<p><em>Глубокая копия</em> используется для хранения значений, которые уже скопированы. Глубокая копия не копирует ссылочные указатели на объекты. Она создает ссылку на объект, и новый объект, на который указывает другой, сохраняется. В отличие от неглубокой копии, изменения, внесенные в исходную копию, не повлияют ни на одну другую копию, использующую объект. Это значит, что они не привязаны.</p>
<pre class="wp-block-code"><code class="hljs makefile"><span class="hljs-comment">#Пример глубокой копии</span>

list_example = [1,2,3,4,5]

<span class="hljs-comment">#Создание глубокой копии с помощью атрибута .copy</span>
another_list = list_example.copy()
another_list[0] = 100
print(list_example)</code></pre>
<h3 id="h-36-python">36. Как создать пустой класс в&nbsp;Python?</h3>
<p>Пустой класс — это класс, который не имеет никакого кода, определенного в его блоке. Он может быть создан с помощью ключевого слова <em>pass</em>. Однако объекты этого класса можно создать и вне самого класса. В Python команда <code>pass</code> ничего не делает при ее выполнении, это null.</p>
<pre class="wp-block-code"><code class="hljs python"><span class="hljs-class"><span class="hljs-keyword">class</span> <span class="hljs-title">sample</span>:</span>
    <span class="hljs-keyword">pass</span>
test=sample()
test.name=<span class="hljs-string">"test1"</span>
print(test.name)</code></pre>
<h3 id="h-37-self-python">37. Что означает ключевое слово self в&nbsp;Python?</h3>
<p>Ключевое слово self используется в качестве первого параметра функции внутри класса, представляющего экземпляр класса. Объект или экземпляр класса автоматически передается методу, которому он принадлежит, и принимается в ключевом слове “self”. Пользователи могут использовать другое имя для первого параметра функции, которая указывает на объект класса, но рекомендуется использовать ключевое слово “self”, так как оно ближе к соглашению Python.</p>
<h3 id="h-38-do-while">38. Будет ли цикл do-while работать, если вы не закончите его точкой с&nbsp;запятой?</h3>
<p>Это <strong>вопрос с подвохом</strong>! Во-первых, Python не поддерживает встроенный цикл do-while. Во-вторых, завершение циклов do-while является необходимостью для таких языков, как C++.</p>
<h3 id="h-39">39. Как преобразовать список в&nbsp;строку?</h3>
<p>В этом случае мы могли бы использовать атрибут&nbsp;.join() из строкового объекта. Здесь мы передали объект списка в атрибут:</p>
<pre class="wp-block-code"><code class="hljs nginx"><span class="hljs-attribute">list_example</span> = [<span class="hljs-string">'apple'</span>, <span class="hljs-string">'grape'</span>, <span class="hljs-string">'orange'</span>]
print(<span class="hljs-string">' '</span>.join(list_example))</code></pre>
<h4 id="h-40">40. Что такое оператор членства?</h4>
<p>Это оператор, который может подтвердить, является ли значение членом в другом объекте. Операторы членства бывают “in” и “not in”.</p>
<pre class="wp-block-code"><code class="hljs python"><span class="hljs-comment">#Пример операторов членства</span>

print(<span class="hljs-string">'me'</span> <span class="hljs-keyword">in</span> <span class="hljs-string">'membership'</span>)
print(<span class="hljs-string">'mes'</span> <span class="hljs-keyword">not</span> <span class="hljs-keyword">in</span> <span class="hljs-string">'membership'</span>)</code></pre>
<h3 id="h-41-python">41. Что такое операторы тождественности в&nbsp;Python?</h3>
<p>Они показывают нам, тождественны ли два значения. Операторы — “is” и “is not”.</p>
<pre class="wp-block-code"><code class="hljs python"><span class="hljs-comment">#Пример операторов тождественности</span>
print(<span class="hljs-number">1</span> <span class="hljs-keyword">is</span> <span class="hljs-string">'1'</span>)
print(<span class="hljs-number">2</span> <span class="hljs-keyword">is</span> <span class="hljs-keyword">not</span> <span class="hljs-string">'2'</span>)</code></pre>
<h3 id="h-42-python">42. Как обрабатывать входные данные в&nbsp;Python?</h3>
<p>Для получения входных данных от пользователя можно использовать функцию input(). Она будет принимать входные данные от пользователя и возвращать их в строковый объект.</p>
<pre class="hljs bash"><code class="hljs"><span class="hljs-built_in">test</span> = input(<span class="hljs-string">'input a number: '</span>)<br><span class="hljs-built_in">print</span>(<span class="hljs-built_in">test</span>)</code></pre>
<h3 id="h-43-zip">43. Что делает функция&nbsp;zip()?</h3>
<p>Она вернет итератор кортежей, сформирует n-пару значений из перечисляемых, передаваемых функции. n — это число итерируемых, которые передают функции.</p>
<pre class="wp-block-code"><code class="hljs python"><span class="hljs-comment">#Пример функции Zip</span>

print(list(zip([<span class="hljs-number">1</span>,<span class="hljs-number">2</span>,<span class="hljs-number">3</span>], [<span class="hljs-string">'apple'</span>, <span class="hljs-string">'grape'</span>, <span class="hljs-string">'orange'</span>], [<span class="hljs-string">'x'</span>, <span class="hljs-number">2</span>, <span class="hljs-keyword">True</span>])))

<span class="hljs-keyword">for</span> num, fruit, thing <span class="hljs-keyword">in</span> zip([<span class="hljs-number">1</span>,<span class="hljs-number">2</span>,<span class="hljs-number">3</span>], [<span class="hljs-string">'apple'</span>, <span class="hljs-string">'grape'</span>, <span class="hljs-string">'orange'</span>], [<span class="hljs-string">'x'</span>, <span class="hljs-number">2</span>, <span class="hljs-keyword">True</span>]):
    print(num)
    print(fruit)
    print(thing)</code></pre>
<h3 id="h-44-range">44. В чем разница между тем, когда функция range() принимает один аргумент, два и&nbsp;три?</h3>
<p>Когда мы передаем только один аргумент, функция принимает его в качестве стоп-значения. Здесь начальное значение равно 0, а шаговое +1. Итерация с диапазоном всегда будет останавливаться на единицу перед стоп-значением.</p>
<pre class="hljs python"><code class="hljs"><span class="hljs-keyword">for</span> i <span class="hljs-keyword">in</span> range(<span class="hljs-number">5</span>):<br>   print(i)</code></pre>
<p>Когда мы передаем два аргумента, первый из них является начальным значением, а второй — стоп значением.</p>
<pre class="hljs python"><code class="hljs"><span class="hljs-keyword">for</span> i <span class="hljs-keyword">in</span> range(<span class="hljs-number">1</span>,<span class="hljs-number">5</span>):<br>   print(i)</code></pre>
<p>Используя три аргумента, первый аргумент является начальным, второй — стоп, а третий — значением шага.</p>
<pre class="hljs python"><code class="hljs"><span class="hljs-keyword">for</span> i <span class="hljs-keyword">in</span> range(<span class="hljs-number">1</span>,<span class="hljs-number">10</span>,<span class="hljs-number">2</span>):<br>   print(i)</code></pre>
<h3 id="h-45">45. Напишите лучший код для перестановки двух чисел&nbsp;местами.</h3>
<p>Вы можете выполнить перестановку с помощью одной строки.</p>
<pre class="wp-block-code"><code class="hljs makefile">a = 1
b = 2

<span class="hljs-comment">#Перестановка чисел</span>
a, b = b, a</code></pre>
<h3 id="h-46">46. Как можно объявить несколько назначений в одной строке&nbsp;кода?</h3>
<p>Есть два способа это сделать. Первый — это отдельное объявление переменной в той же строке:</p>
<pre class="hljs"><code class="hljs">a, b, c = 1,2,3</code></pre>
<p>Другой способ — объявить переменную в той же строке только с одним значением:</p>
<pre class="hljs ini"><code class="hljs"><span class="hljs-attr">a</span>=b=c=<span class="hljs-number">1</span></code></pre>
<h3 id="h-47">47. Как вырваться из бесконечного цикла?</h3>
<p>Чтобы прервать процесс, нужно нажать Ctrl+C.</p>
<h3 id="h-48-with-python">48. Что делает оператор <code>with</code> в&nbsp;Python?</h3>
<p>Оператор <code>with</code> в Python гарантирует, что код очистки выполняется при работе с неуправляемыми ресурсами путем инкапсуляции общих задач подготовки и очистки. Он может быть использован, чтобы открыть файл, сделать что-то, а затем автоматически закрыть его. Также он может пригодиться для открытия соединения с базой данных, выполнения некоторой обработки, а затем автоматического закрытия, чтобы гарантировать, что ресурсы закрыты и доступны для других. <code>with</code> выполнит очистку ресурсов, даже если выдается исключение.</p>
<pre class="wp-block-code"><code class="hljs python"><span class="hljs-comment">#Пример оператора with</span>

<span class="hljs-keyword">with</span> open(<span class="hljs-string">'database.txt'</span>) <span class="hljs-keyword">as</span> data:
    print(data)</code></pre>
<h3 id="h-49-except-try-except">49. Когда выполняется except, в блоке try-except?</h3>
<p>Блок try-except обычно используется, когда мы хотим что-то выполнить, если возникли ошибки. except выполняется, когда код в блоке try вызвал ошибки.</p>
<pre class="wp-block-code"><code class="hljs python">a = (<span class="hljs-number">1</span>,<span class="hljs-number">2</span>,<span class="hljs-number">3</span>)
<span class="hljs-keyword">try</span>:
   a[<span class="hljs-number">0</span>] = <span class="hljs-number">2</span>
<span class="hljs-keyword">except</span>:
   print(<span class="hljs-string">'There is an error'</span>)</code></pre>
<h3 id="h-50-while-for">50. Где вы будете использовать <code>while</code> вместо&nbsp;<code>for</code>?</h3>
<p>Для простого повторяющегося цикла, либо тогда, когда не нужно перебирать список элементов, например записи базы данных и символы в строке.</p>
<h3 id="h-51-python">51. Что такое модули&nbsp;Python?</h3>
<p>Это независимые скрипты Python с расширением&nbsp;.py, которые можно повторно использовать в других кодах Python или скриптах с помощью оператора import. Модули могут состоять из функций, классов и переменных, а также некоторого выполняемого кода. Они помогают не только упорядочить коды Python, но и сделать их менее сложными и более эффективными.</p>
<pre class="hljs nginx"><code class="hljs"><span class="hljs-attribute">import</span> <span class="hljs-comment">#имя модуля</span></code></pre>
<h3 id="h-52-pythonpath">52. Что такое PYTHONPATH?</h3>
<p>PYTHONPATH — это переменная окружения, которая при импорте проверяется на наличие импортированных модулей в различных каталогах. Интерпретатор использует её, чтобы определить, какой модуль следует загрузить.</p>
<h3 id="h-53-python">53. Назовите пример режимов обработки файлов с помощью&nbsp;Python?</h3>
<p>Существуют следующие режимы:</p>
<ul><li>Режим только для чтения (‘r’): открыть файл для чтения. Это режим по умолчанию.</li><li>Режим только для записи (‘w’): открыть файл для записи. Если файл содержит данные, они будут потеряны. Создается новый файл.</li><li>Режим чтения-записи (‘rw’): открыть файл для чтения, режим записи. Это режим обновления.</li><li>Режим добавления (‘a’): открыть для записи, добавить в конец файла, если файл существует.</li></ul>
<h3 id="h-54-pickling-unpickling">54. Что такое pickling и unpickling?</h3>
<p>Модуль pickle принимает любой объект Python, преобразует его в строковое представление и сохраняет в файл с помощью функции dump, такой процесс называется pickling. Процесс извлечения исходных объектов Python из сохраненного строкового представления называется unpickling.</p>
<pre class="wp-block-code"><code class="hljs perl">import pickle

a = <span class="hljs-number">1</span>

<span class="hljs-comment">#Процесс pickling</span>
pickle.dump(a, <span class="hljs-keyword">open</span>(<span class="hljs-string">'file.sav'</span>, <span class="hljs-string">'wb'</span>))

<span class="hljs-comment">#Процесс unpickling</span>
file = pickle.load(<span class="hljs-keyword">open</span>(<span class="hljs-string">'file.sav'</span>, <span class="hljs-string">'rb'</span>))</code></pre>
<h3 id="h-55-python-numpy">55. Являются ли массивы Python NumPy лучше&nbsp;списков?</h3>
<p>Мы используем массивы Python NumPy вместо списка по следующим трем причинам:</p>
<p>1. меньший объем памяти;</p>
<p>2. быстрее;</p>
<p>3. удобнее.</p>
<h3 id="h-56-numpy">56. Как вычислять процентили с помощью&nbsp;NumPy?</h3>
<p>Медиана — это 50 процентиль по определению. 25 процентиль указывает, что 25% наблюдаемых меньше числа в процентиле, то есть n процентов наблюдаемых значений меньше значения в процентиле n.</p>
<p>Мы можем вычислить его с помощью NumPy, используя следующий код:</p>
<pre class="wp-block-code"><code class="hljs python"><span class="hljs-keyword">import</span> numpy <span class="hljs-keyword">as</span> np

a = np.array([i <span class="hljs-keyword">for</span> i <span class="hljs-keyword">in</span> range(<span class="hljs-number">100</span>)])
p = np.percentile(a, <span class="hljs-number">50</span>) <span class="hljs-comment">#Возвращает 50-ый перцентиль - медиану</span>

print(p)</code></pre>
<h3 id="h-57-python">57. Как получить текущий рабочий каталог с помощью&nbsp;Python?</h3>
<p>Работая с Python, вам может понадобиться читать и записывать файлы из различных каталогов. Чтобы узнать, в каком вы сейчас работаете, можно использовать метод getcwd() из модуля os:</p>
<pre class="hljs nginx"><code class="hljs"><span class="hljs-attribute">import</span> os<br>os.getcwd()</code></pre>
<h3 id="h-58">58. Что вы видите снизу? Что произойдет, если мы выполним этот&nbsp;код?</h3>
<pre class="wp-block-code"><code class="hljs makefile">a = '1'
b = '2'
c = '3's = a + ‘[‘ + b + ‘:’ + c + ‘]’
print(s)</code></pre>
<p>Это конкатенация строк. Если даже одна из переменных не является строкой, она вызовет ошибку типа (TypeError). Выполнив этот код, мы получим результат конкатенации.</p>
<h3 id="h-59">59. Как бы вы произвели рандомизацию содержимого списка на&nbsp;месте?</h3>
<p>Мы можем воспользоваться функцией shuffle() из модуля random:</p>
<pre class="wp-block-code"><code class="hljs javascript"><span class="hljs-keyword">from</span> random <span class="hljs-keyword">import</span> shuffle
list_example = [<span class="hljs-number">1</span>,<span class="hljs-number">2</span>,<span class="hljs-number">3</span>,<span class="hljs-number">4</span>,<span class="hljs-number">5</span>,<span class="hljs-number">6</span>,<span class="hljs-number">7</span>,<span class="hljs-number">8</span>]
shuffle(list_example)</code></pre>
<h3 id="h-60-python">60. Что такое приведение в&nbsp;Python?</h3>
<p>Приведение — это процесс преобразования значения переменной из одного типа в другой. В Python это можно сделать с помощью таких функций, как list(), int (), float() и str(). Примером может служить преобразование строки в целочисленный объект:</p>
<pre class="hljs ini"><code class="hljs"><span class="hljs-attr">a</span> = <span class="hljs-string">'1'</span><br>b = int(a)</code></pre>
<h3 id="h-61">61. Объясните ошибку</h3>
<pre class="wp-block-code"><code class="hljs sql">from numpy imprt stdev

ImportError Traceback (most recent <span class="hljs-keyword">call</span> <span class="hljs-keyword">last</span>)
&lt;ipython-<span class="hljs-keyword">input</span><span class="hljs-number">-26</span><span class="hljs-number">-685</span>c12521ed4&gt; <span class="hljs-keyword">in</span> &lt;<span class="hljs-keyword">module</span>&gt;
<span class="hljs-comment">----&gt; 1 from numpy import stdev</span>

ImportError: cannot <span class="hljs-keyword">import</span> <span class="hljs-keyword">name</span> <span class="hljs-string">'stdev'</span> <span class="hljs-keyword">from</span> <span class="hljs-string">'numpy'</span></code></pre>
<p>В приведенном выше коде мы пытаемся импортировать несуществующую функцию из модуля numpy. В этом причина.</p>
<h3 id="h-62-python">62. Как можно удалить переменные в&nbsp;Python?</h3>
<p>Для удаления переменной мы можем использовать функцию del(). Считается хорошей практикой, убрать что-то лишнее, что не используется.</p>
<pre class="hljs ini"><code class="hljs"><span class="hljs-attr">a</span> = <span class="hljs-number">1</span><br>del a</code></pre>
<h3 id="h-63-pandas-python">63. Что такое pandas в&nbsp;Python?</h3>
<p>Pandas — это пакет Python, предоставляющий быстрые, гибкие и функциональныеструктуры данных, предназначенные для того, чтобы сделать работу с “реляционными” или “помеченными” данными простой и интуитивно понятной. Он призван стать фундаментальным строительным блоком высокого уровня для практического анализа реальных данных в Python.</p>
<h3 id="h-64-append-extend">64. В чем разница между методами append() и extend()?</h3>
<p>Они используются для добавления элементов в конец списка.</p>
<ul><li>append(элемент): добавляет элемент в конец списка;</li><li>extend(другой список): добавляет элементы другого списка в конец первого.</li></ul>
<h3 id="h-65-python">65. Как получить текущую версию&nbsp;Python?</h3>
<p>Мы можем узнать текущую версию Python с помощью sys.version:</p>
<pre class="hljs nginx"><code class="hljs"><span class="hljs-attribute">import</span> sys<br>sys.version</code></pre>
<h3 id="h-66-args-kwargs">66. Что значит *args, **kwargs? И зачем нам их использовать?</h3>
<p>Мы используем *args, когда неуверены, сколько аргументов будет передано функции, или если хотим передать сохраненный список или кортеж аргументов функции. **kwargs используется, когда мы не знаем, сколько аргументов ключевых слов будет передано, а также он может быть использован для передачи значений словаря в качестве аргументов ключевых слов. Идентификаторы args и kwargs необязательны, вы можете изменить их на другие, типа *другой **пример, но лучше использовать имя по умолчанию.</p>
<pre class="wp-block-code"><code class="hljs python"><span class="hljs-comment">#Пример *args</span>
<span class="hljs-function"><span class="hljs-keyword">def</span> <span class="hljs-title">sample</span><span class="hljs-params">(*args)</span>:</span>
    print(args)

sample(<span class="hljs-string">'time'</span>, <span class="hljs-number">1</span>, <span class="hljs-keyword">True</span>)

<span class="hljs-comment">#Пример **kwargs</span>
<span class="hljs-function"><span class="hljs-keyword">def</span> <span class="hljs-title">sample</span><span class="hljs-params">(**kwargs)</span>:</span>
    print(kwargs)

sample(a = <span class="hljs-string">'time'</span>, b = <span class="hljs-number">1</span>)</code></pre>
<h3 id="h-67-help-dir-python">67. Что за функции help() и dir() в&nbsp;Python?</h3>
<p>Функция help() отображает строку документации и справку для своего аргумента.</p>
<pre class="wp-block-code"><code class="hljs cpp"><span class="hljs-function"><span class="hljs-keyword">import</span> numpy
<span class="hljs-title">help</span><span class="hljs-params">(numpy.<span class="hljs-built_in">array</span>)</span></span></code></pre>
<p>Функция dir() отображает все элементы объекта (любого вида).</p>
<pre class="wp-block-code"><code class="hljs cpp"><span class="hljs-function"><span class="hljs-keyword">import</span> numpy
<span class="hljs-title">dir</span><span class="hljs-params">(numpy.<span class="hljs-built_in">array</span>)</span></span></code></pre>
<h3 id="h-68">68. Что означает одинарное и двойное подчеркивание перед именем&nbsp;объекта?</h3>
<p><strong>Одиночное подчеркивание</strong> — имена в классе с подчеркиванием перед ними просто указывают другим программистам, что атрибут или метод предназначен для закрытого использования, однако с самим именем ничего особенного не делается.</p>
<p><strong>Двойное подчеркивание</strong> (искажение имени) — любой идентификатор вида __spam (не менее двух ведущих подчеркиваний, не более одного завершающего) заменяется на _имякласса__spam, где имя класса — это текущее спрятанное имя с подчеркиванием перед ним. Это искажение выполняется без учета синтаксической позиции идентификатора, поэтому его можно использовать для определения экземпляра закрытого класса и его переменных, методов, а также глобальных и других переменных, хранящихся в экземплярах, частных для этого класса в экземплярах других.</p>
<h3 id="h-69">69. Каков результат нижеприведенного запроса?</h3>
<pre class="wp-block-code"><code class="hljs makefile">ss = “Python Programming!”
print(ss[5])

<span class="hljs-section">Ответ: ‘n’</span></code></pre>
<h3 id="h-70-python">70. Напишите программу на Python, чтобы создать треугольник из&nbsp;звезд</h3>
<pre class="wp-block-code"><code class="hljs python"><span class="hljs-function"><span class="hljs-keyword">def</span> <span class="hljs-title">star_triangle</span><span class="hljs-params">(r)</span>:</span>
   <span class="hljs-keyword">for</span> x <span class="hljs-keyword">in</span> range(r):
      print(<span class="hljs-string">' '</span>*(r-x<span class="hljs-number">-1</span>)+<span class="hljs-string">'*'</span>*(<span class="hljs-number">2</span>*x+<span class="hljs-number">1</span>))

star_triangle(<span class="hljs-number">7</span>)</code></pre>
<div class="wp-block-image"><figure class="aligncenter"><img src="https://cdn-images-1.medium.com/max/533/0*L_5YEG4oOWwOhYk3.png" alt="" class="td-animation-stack-type0-1"></figure></div>
<h3 id="h-71">71. Что плохого в следующем коде:</h3>
<pre class="wp-block-code"><code class="hljs python">counter = <span class="hljs-number">0</span>

<span class="hljs-function"><span class="hljs-keyword">def</span> <span class="hljs-title">increment</span><span class="hljs-params">()</span>:</span>
   counter += <span class="hljs-number">1</span>

increment()</code></pre>
<p>В Python нет объявлений переменных, поэтому он должен сам определить их область действия. Если внутри функции имеется обращение к переменной, то она считается локальной. Переменная counter выше является глобальной, поэтому код выбрасывает ошибку.</p>
<h3 id="h-72">72. Как разделить строку на&nbsp;список?</h3>
<p>Мы можем использовать атрибут split(). Он принимает разделитель в качестве аргумента и возвращает список, состоящий из результатов разделения строки на его основе.</p>
<pre class="hljs ini"><code class="hljs"><span class="hljs-attr">text</span> = <span class="hljs-string">'hello again world !'</span><br>text.split(<span class="hljs-string">' '</span>)</code></pre>
<h3 id="h-73-python">73. Напишите программу на Python, чтобы проверить, является ли последовательность, которую вы вводите, палиндромом</h3>
<pre class="wp-block-code"><code class="hljs makefile">a=input(<span class="hljs-string">"enter the sequence: "</span>)
b=a[::-1]

if a==b:
   print(<span class="hljs-string">"palindrome"</span>)
<span class="hljs-section">else:</span>
   print(<span class="hljs-string">"Not a Palindrome"</span>)</code></pre>
<h3 id="h-74">74. Что такое генератор?</h3>
<p>Генератор Python создает последовательность значений для итерации, часто с помощью функции. Мы определяем функцию с помощью <code>yield</code>&nbsp;, которая используется для получения значения по одному, а затем используем цикл for для итерации.</p>
<pre class="wp-block-code"><code class="hljs python"><span class="hljs-function"><span class="hljs-keyword">def</span> <span class="hljs-title">squares</span><span class="hljs-params">(n)</span>:</span>
    i=<span class="hljs-number">1</span>
    <span class="hljs-keyword">while</span>(i&lt;=n):
        <span class="hljs-keyword">yield</span> i**<span class="hljs-number">2</span>
        i+=<span class="hljs-number">1</span>
<span class="hljs-keyword">for</span> i <span class="hljs-keyword">in</span> squares(<span class="hljs-number">7</span>):
    print(i)</code></pre>
<h3 id="h-75-python">75. Напишите программу на Python для проверки, является ли число&nbsp;простым</h3>
<pre class="wp-block-code"><code class="hljs perl">a=<span class="hljs-keyword">int</span>(input(<span class="hljs-string">"enter a number"</span>))     
<span class="hljs-keyword">if</span> a&gt;<span class="hljs-number">1</span>:
    <span class="hljs-keyword">for</span> <span class="hljs-keyword">x</span> in range(<span class="hljs-number">2</span>,a):
        <span class="hljs-keyword">if</span>(a%x)==<span class="hljs-number">0</span>:
            <span class="hljs-keyword">print</span>(<span class="hljs-string">"not prime"</span>)
            <span class="hljs-keyword">break</span>
    <span class="hljs-keyword">else</span>:
        <span class="hljs-keyword">print</span>(<span class="hljs-string">"Prime"</span>)
<span class="hljs-keyword">else</span>:
    <span class="hljs-keyword">print</span>(<span class="hljs-string">"not prime"</span>)</code></pre>
<h3 id="h-76-_-python">76. Какова цель одинарной переменной подчеркивания ( ‘ _ ’ ) в&nbsp;Python?</h3>
<p>Она предназначена для хранения результата последнего выполненного выражения (/statement) в сеансе интерактивного интерпретатора. Этот прецедент был установлен стандартным интерпретатором CPython, а другие последовали этому примеру.</p>
<h3 id="h-77-python">77. Каковы типы наследования в&nbsp;Python?</h3>
<p>Python поддерживает различные типы наследования. Ими являются:</p>
<ul><li>единичное наследование;</li><li>многоуровневое наследование;</li><li>иерархическое наследование;</li><li>множественное наследование.</li></ul>
<h3 id="h-78">78. Что такое распаковка кортежа?</h3>
<p>Это процесс распаковки его значений и их ввода в несколько различных переменных.</p>
<pre class="wp-block-code"><code class="hljs makefile">tup = (1,2,3)

<span class="hljs-comment">#Процесс распаковки кортежа</span>
a,b,c = tup</code></pre>
<h3 id="h-79-python">79. Освобождается ли вся память при выходе из&nbsp;Python?</h3>
<p>Выход из Python освобождает все, кроме:</p>
<p>1. модулей с циклическими ссылками;</p>
<p>2. объектов, на которые ссылаются глобальные пространства имен;</p>
<p>3. части памяти, зарезервированной библиотекой C.</p>
<h3 id="h-80-return">80. Является ли функция допустимой, если она не имеет оператора return?</h3>
<p>Функция, которая ничего не возвращает, возвращает объект None. Ключевое слово return необязательно обозначает конец функции, оно просто завершает ее, если присутствует. Обычно блок кода помечает функцию, и там, где заканчивается блок, заканчивается и тело функции.</p>

</div>
