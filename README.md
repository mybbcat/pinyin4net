pinyin4net
=============================================

Pinyin4net can help you convert ���� to zh��ng w��n.

Getting started
---------------------------------------------

using Pinyin4net;

...
string[] pinyinStr = PinyinHelper.ToHanyuPinyinStringArray(someChineseChar);
...


Features
---------------------------------------------

* Convert Chinese to Hanyu Pinyin system.
* Support both Simplified Chinese and Tranditional Chinese.
* Multiple options for output format
** All uppercase or lowercase
** Can out put Unicode �� or v or u:
** With tone numbers (l��3) or tone marks (l��) or without tone (l��)

Acknowledgments 
---------------------------------------------

Most code of pinyin4net is based on the code of project [pinyin4j](http://pinyin4j.sourceforge.net/). Thanks [Li Min](http://www.eng.nus.edu.sg/LCEL/people/limin/) for the great code ^_^.