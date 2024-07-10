# LG_DX_School_BX_project

<P> Good sleep, Good life </P>

### Project Outline

The LG Electronics BX Project aims to enhance customer engagement by leveraging our diverse industry portfolio. We are focused on solving the challenge of increasing touchpoints with LG Electronics' customers. Our approach involves developing a smart mattress product to address this issue.

## Environment

- Java must be installed to use the konlp packages (for extracting Korean nouns for word clouds).
- The stopword.txt file contains Korean stop words.
- The requirements.txt file should include all the Python libraries that your notebooks rely on, and these libraries will be installed using the following command:
```
pip install -r requirements.txt
```
- In some cases, the word cloud for Korean text may appear with corrupted fonts. To resolve this issue, use the NanumGothic.ttf font file from NanumFontSetup_TTF_GOTHIC. For more details, refer to wordcloud_policy.ipynb.

## Data

At BX School, we studied web crawling using the Selenium and BeautifulSoup (bs4) packages in Python. We applied these skills to implement data collection, gathering information as follows.

|Data|purpose|Link|
|------|---|---|
|빅카인즈|To analyze the frequency of words related to "Deep sleep" and "sleepless" in a given text|https://www.bigkinds.or.kr/|
|오늘의 집|To find out the satisfaction or pain points in customers who buy smart appliances or smart mattresses|https://ohou.se/|
|네이버 블로그|Similar reason above case.|https://m.search.naver.com/search.naver?ssc=tab.m_blog.all&sm=mtb_jum&query=%EB%B8%94%EB%A1%9C%EA%B7%B8|
|앱 리뷰(구글, APP)|To identify pain points or satisfaction levels among users of the LG ThinQ App|https://play.google.com/store/games?hl=ko|

##