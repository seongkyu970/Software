## Extended Syntax in GitHub Flavored Markdown
1. Tables
> pipes \|와 hyphens \- 을 이용하여 테이블을 작성할 수 있다.  
> 하이픈은 각 열의 헤더를 만드는 데 사용되며 파이프는 각 열을 구분하고 테이블 앞에 빈 줄을 포함해야 한다.
>> ex :)  
>> \| First Header | Second Header |  
>> \| ------------ | -------------- |  
>> \| item1        | item2      |  
>> \| item3        | item3     |  
>> | First Header | Second Header |
>> | ------------ | -------------- |
>> | item1        | item2      |
>> | item3        | item3     |
> 테이블 양쪽 끝 pipes는 선택 사항이며 셀의 너비가 다를 수 있고 열 내에서 정렬할 필요는 없다.
> 머리글 행의 각 열에는 최소한 세 개의 hypens가 있어야한다.
2. Task Lists
> Task Lists를 만들기 위해선 list items(\-,\*,\+) 뒤에 \[ ]을 추가하고 작업을 완료로 표시하려면 \[x]를 추가하면된다.
>> ex :)  
>> \- [x] Finish my task  
>> \* [ ] Next Tasks  
>> \+ [ ] Sleep  
>> - [x] Finish my task 
>> * [ ] Next Tasks
>> + [ ] Sleep
3. Strikethorough
> 단어나 문장 앞뒤로 \~~ 를 포함시키면 Strikethrough text를 사용할 수 있다.
>> ex :) \~~ Strikethorough ~~  
>> ~~This was mistaken text~~ 
4. Autolinks
> www가 발견되고 그 뒤에 유효한 도메인이 있을 때 http는 자동으로 삽입되며 링크로 인식한다.
>> www.github.com
7. Disallowed Raw HTML
> GFM에서 아래와 같은 HTML 태그들은 HTML 결과를 만들 때 Filtering 된다.
>> * <title>
>> * <textarea>
>> * <style>
>> * <xmp>
>> * <iframe>
>> * <noembed>
>> * <noframes>
>> * <script>
>> * <plaintext>
> Filtering is done by replacing the leading < with the entity &lt;. These tags are chosen in particular as they change how HTML is interpreted in a way unique to them.  
> 이것은 일반적으로 다른 마크다운 콘텐츠 에서 바람직하지 않다. 
