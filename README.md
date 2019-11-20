# 取り扱い説明書

やってほしいことざっくり

- 自分の割り当てられた章のスライド（必要ならテキストデータも）を読んで分からないところの質問を考える    
- 質問に対応する回答をテキストデータから探す  
- Googleフォームに記入していただく  
     
よろしくお願いします。



# 1.slideフォルダ  

### ファイル名とスライドの対応   
chapt01 ⇒ 1章  という感じです。

### 説明
スライドのデータです. 基本的にはこれを見て質問を考えてください。  
スライドだけ見ても内容がざっくりしすぎで分からない場合はテキストデータも見ながら考えてくださっても大丈夫です。

質問を考える際の状況、モチベとしては
「あなたは今機械学習を勉強する（している）人で、先生がスライドをもとに授業を行い、わからないところを質問する」
と考えると質問が浮かびやすいかもしれません。
   
        
            
               

# 2.textdataフォルダ  


### ファイル名とスライドとの対応

edit_chap01.tex　⇒　1章のスライドに対応するテキストデータ　という感じです。  
  
tex形式ですが、github上で閲覧できますのでご安心ください。     
ファイル名をクリックして中央右側にある「Raw」「Blame」「History」の「Raw」を  
押すと画面の大きさに応じて改行して表示されスクロールがないので読みやすくなると思います。  


### 説明（ファイル名中の記号に関して）

#### ①章番号とスライド番号を表す%chapXX/Y(Y)
例）      
%chap01/1　⇒　1章のスライド1枚目のテキストの開始位置を示す　      
%chap03/7　⇒　3章のスライド7枚目のテキストの開始位置を示す   
     
ただし、以下2点注意です!!   
   
- %chap03/0のようにスライド番号に0がある ⇒ 0のときはスライドが存在しないのでこの部分のテキストで質問を考え無いようにお願いします。0のものは無視してください   

- 説明の順序関係で、スライド番号が前後している場合がありますのでご了承ください。例） %chap03/7 の次に %chap03/5 が来るなど   
    
         
             
#### ② 図を表す %figureX.Y 式を表す %equationX.Y 

特に気にせず、ここで何か図が入るんだな、式が入るんだなという感じでスルーしてくださってOKです。

      
            
               
#### ③ 数式記号　$\bm{w}$　など

特に気にせず、読み進めて下さい。      

       
      
          
# 3.考えた質問の提出先

以下のGoogleフォームからお願いします。

https://docs.google.com/forms/d/e/1FAIpQLSftHPj1Btmz-sBQw8zqblFP1CjXbLZZp1qCUveu1nn_hMJbYg/viewform?usp=sf_link

(ctrl押しながらクリックで別タブで開く)

# 4.質問と回答を作る方法


質問を考えていただく方針ですが
１．割り当てられた〇〇章の××スライドを読む
２．分からないことを質問する感じで、質問内容を考える
（すでに熟知していて質問することがない！という場合は、自分がそのことに関して初心者になった気持ちで考えてくださるようにお願いします。）
３．考えた質問内容に対する回答を、スライドに対応するテキストデータから探す。
４．回答となる箇所があれば、それをコピペして回答とする。無かったら別の質問を考える（２．に戻る）

という感じでお願いします。
なかなか質問が浮かばない、またはスライドがざっくりしすぎで分からない場合はテキストデータを見てから質問を考えてくださっても構いません。
    
### 重要注意事項

回答は必ずテキストデータの該当部分のコピペでお願いします。勝手に語尾など付けないでください。
           

# 4.何か分からない事などある場合

LINEでもTwitterでも連絡ください。24時間対応しているので多分すぐ返信できます。     

    
         
            

# 5.最後に

各ファイルのデータは荒木先生の所有物になりますので、外部への持ち出しなどはしないようにお願いします。
