# Info-crawler-for-SIPO
SIPO is for China and Global patent examination information inquiry

## Background story
* This is my first time to push code to github.
* This is also my first time to write some Python code.
* I am a full stack web developer (Java, Node, React).

## What is this script used for
* Mr Gao suffered a lot from pulling patent information from [China and global patent information inquiry](http://cpquery.sipo.gov.cn/txnQueryOrdinaryPatents.do?select-key:shenqingh=&select-key:zhuanlimc=&select-key:shenqingrxm=%E5%8F%B0%E5%B7%9E%E9%A3%9E%E8%B7%83%E5%8F%8C%E6%98%9F%E6%88%90%E8%A1%A3%E6%9C%BA%E6%A2%B0%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8&select-key:zhuanlilx=&select-key:shenqingr_from=&select-key:shenqingr_to=&verycode=12&inner-flag:open-type=window&inner-flag:flowno=1508269710587) since he had to step into every patent for details and copy.
* This script is going to create an excel file for the results

## Difficulties
* Page data has been encrypted, so I have to go through a lot of code to find out how to decrypt
* I never touched BeautifulSoup and Python programming before

## Packages used here
* [Beautifulsoup](https://www.crummy.com/software/BeautifulSoup/)
* [xlsxwriter](http://xlsxwriter.readthedocs.io/)
* [pyinstaller](http://www.pyinstaller.org/)

If you do not know how to use this, feel free to ask!
