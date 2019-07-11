# Language-and-Intelligent-Technology-Competition
Language and Intelligent Technology Competition



### Raw Data 
#### Important Fields  
- question_type: "DESCRIPTION","YES OR NO", "Entity" etc 
- question_id: question id 
- fact_or_opinion: the question is about fact or opinion, this is relate to question_type "DESCRIPTION"
- documents: at most 5 documents originate from search result  
- is_selected: if this search result is select as a true answer 
- title: the title of search result 
- paragraphs: some related paragraphs from search result page 
- answers: the paragraph from the documents whose is_selected field is true 

tips: baidu zhidao fields is same as baidu search fields. 



#### Data Sample 

###### Language-and-Intelligent-Technology-Competition/2019/MRC/models/DuReader/data/raw/trainset/search.train.json 
```json 
{
  "documents":[
    {
      "is_selected":true,
      "title":"如何做茄子卤面",
      "paragraphs":[
        "<p><img src=\"23857019472\" \/><\/p><p>做法：<\/p><p>&nbsp; 1.茄子切小丁。<\/p><p>&nbsp; &nbsp;2.五花肉切小丁。<\/p><p>&nbsp; &nbsp;3.准备好豆酱。<\/p><p>&nbsp; &nbsp;4.油热后翻炒肉丁和茄子。<\/p><p>&nbsp; &nbsp;5.添适量水，煮开。<\/p><p>&nbsp; &nbsp;6.加黄豆酱拌匀，煮开即可。<\/p><p>&nbsp; &nbsp;7.水开后煮面条。<\/p><p>&nbsp; &nbsp;8.煮好的面过冷水。<\/p><p>&nbsp; &nbsp;9.盛适量的酱，拌匀即可食用。<\/p><p><img src=\"23857056418\" \/><\/p>",
        "茄子卤面的做法如下一、材料虾仁100g、茄子150g、面条350g、食盐适量、酱油适量、味精适量、姜适量、蚝油适量、调和油适量、柿子椒适量、洋葱适量、黑木耳适量、苦菜适量、香菇适量、胡萝卜适量、鸡蛋1只。二、做法1、虾去头去皮去肠，洗净备用。2、干香菇提前洗干净泡发，切成块继续放在水里泡。3、茄子去皮切成片。4、木耳、黄花菜提前泡发好回刀。洋葱、胡萝卜、辣椒切成块。5、炒锅放油加热，茄子入锅煎后盛出。6、炒锅放油加热，姜丝入锅煸香后，加虾仁、洋葱、茄子、辣椒、胡萝卜、木耳、黄花菜酱油、蚝油入锅翻炒。7、香菇连同泡香菇的水一同入锅。8、再加适量的水，盖上锅盖烧开，加盐、味精，搅拌均匀。9、淋入芡汁、鸡蛋，搅拌均匀，再煮开后关火。10、煮锅加水烧开，煮熟面条。11、面条出锅，配上卤、黄瓜即可。",
        "<p>准备：<\/p><p>圆茄子（挑选小一点嫩一点的茄子）、西红柿、五花肉。<\/p><p>配料：<\/p><p>盐、鸡精、白糖、姜片、大料、酱油、香油、五香粉、香菜段各适量。<\/p><p>做法：<\/p><p>1、茄子洗净去蒂后，切丁，西红柿洗净切丁，五花肉切丁；<\/p><p>2、茄丁放碗中，加少许盐腌制（片刻后用手攥出腌出的汤汁）；<\/p><p>3、炒锅油热后，放入姜片，五花肉，大火翻炒，肉微变色改为中火，煸炒至出油，下大料炒至发胀，盛出；<\/p><p>4、另起锅，放入茄子，不断翻炒至锅发干，放入西红柿丁翻炒片刻，加盐、白糖和将要，改用小火，加盖焖3分钟；<\/p><p>5、倒入五花肉，放鸡精和香叶，翻炒均匀出锅；<\/p><p><img src=\"1059364928\" \/><\/p>"
      ]
    },
    {
      "is_selected":true,
      "title":"茄子打卤面的做法",
      "paragraphs":[
        "准备： 圆茄子（挑选小一点嫩一点的茄子）、西红柿、五花肉。 配料： 盐、鸡精、白糖、姜片、大料、酱油、香油、五香粉、香菜段各适量。 做法： 1、茄子洗净去蒂后，切丁，西红柿洗净切丁，五花肉切丁； 2、茄丁放碗中，加少许盐腌制（片刻后用手攥出腌出的汤汁）； 3、炒锅油热后，放入姜片，五花肉，大火翻炒，肉微变色改为中火，煸炒至出油，下大料炒至发胀，盛出； 4、另起锅，放入茄子，不断翻炒至锅发干，放入西红柿丁翻炒片刻，加盐、白糖和将要，改用小火，加盖焖3分钟； 5、倒入五花肉，放鸡精和香叶，翻炒均匀出锅；",
        "<p>1、茄子不去皮切成小丁，西红柿也切成丁。并准备好葱花和姜末；<br \/>2、准备好肉馅，我家肉馅分装成一小块一小块的放在冰箱里冻着，吃的时候拿出来一块；<br \/>3、起锅做油，油热后放入大料葱花和姜末煸炒出香味后放入肉馅；<br \/>4、肉馅变色后放入茄子丁继续炒五分钟；<br \/>5、茄子稍微变软后放入西红柿丁继续翻炒，把西红柿炒得基本没型后加入酱油和料酒；<br \/>6、加入水煮开后大火炖十分钟，茄子炖懒后倒入水淀粉勾芡；出锅钱倒入适量的盐，关火后淋一点香油即可；<br \/>7、面条煮熟后，用凉水过的透透的，浇上卤，上面再来点黄瓜丝和一小撮香菜。对了，吃的时候再来两瓣蒜。<\/p><p><img src=\"33914332917\" \/><\/p>"
      ]
    },
    {
      "is_selected":true,
      "title":"卤面的做法,
      西红柿茄子素卤面怎么做好吃",
      "paragraphs":[
        "前言这几日同宝贝上火，似乎缺了麻辣油就吃不下饭了！！",
        "1.茄子洗净，不要去皮，切成丝。2.装入容器中，用适量的盐将茄子的水分煞出来。约20分钟左右。3.然后攥出水分，装盘备用。4.洋葱切丝。5.西红柿切丝。6.蒜切碎备用。7.锅中放油，先将茄子过油。8.煸炒至茄子丝结黄茄。9.放入洋葱丝煸炒。10.煸炒至洋葱变软放入西红柿丝继续煸炒。11.放入番茄沙司，煸炒均匀。12.放入白糖、盐、美极鲜调味。13.加入少许的水，中火炖5分钟。14.最后加入蒜碎，关火，拌匀。15.煮面。16.煮好的面条直接放入一个较大的碗中，浇上‘西红柿茄子素卤’就尽情的享用吧。"
      ]
    },
    {
      "is_selected":false,
      "title":"茄子打卤面怎么做好吃",
      "paragraphs":[
        "茄子打卤面怎么做好吃材料一个中等大小的茄子，四两猪肉馅，两个鸡蛋，葱姜少许。做法先将茄子切成小丁待用。鸡蛋摊成鸡蛋片，如图 2 ，然后切成小方片。锅里放油稍多一点儿，茄子吃油，直接放进茄子丁，加点盐（稍多，要拌面）腾烂（炒软）盛出。再放少许油炒香葱姜放入肉末，加料酒生抽炒熟，变色即可，再放进茄子丁，鸡蛋片，加鸡精和水开锅即可。最后淋上花椒油撒些香菜末。"
      ]
    },
    {
      "is_selected":false,
      "title":"茄子面条卤怎么做_百度知道",
      "paragraphs":[
        "茄子肉切丁，肉要肥一点，肉爆炒出油，加佐料，盐多放些，放茄丁炖好既成",
        "1.提前泡发木耳。2.提前将花生米洗干净用冷水浸泡2个小时。3.泡过的花生米入微波炉加工至6、7分熟。4.猪肉切碎。5.胡萝卜洗干净切成丝。6.胡萝卜入煮锅焯水。7.木耳入煮锅焯水。8.茄子洗干净切成片。9.炒锅放油加热，茄子入锅煎。煎好后盛出。10.炒锅放油加热，葱姜入锅煸香后猪肉入锅翻炒。11.加酱油翻炒。12.茄子入锅翻炒。13.花生米入锅翻炒。 加适量水，盖上锅盖焖一会儿。14.木耳入锅翻炒。15.加盐、味精翻炒。16.加枸杞翻炒。17.淋入芡汁，茄子卤就好了。18.黄瓜洗干净切成丝。19.将面条儿煮熟。20.面条儿配上茄子卤，再配上黄瓜、胡萝卜作菜码儿，即可享用茄子卤捞面。",
        "茄子切丁，加肉丁，放油锅里，翻炒，最后加点面酱，出锅叫好了。",
        "回答多了你不满意，回答少了你简单，最后那个，你们是刷分的吧，就你这样还问问题，食屎去吧"
      ]
    }
  ],
  "question":"茄子卤面的做法",
  "answers":[
    "1、虾去头去皮去肠，洗净备用。2、干香菇提前洗干净泡发，切成块继续放在水里泡。3、茄子去皮切成片。4、木耳、黄花菜提前泡发好回刀。洋葱、胡萝卜、辣椒切成块。5、炒锅放油加热，茄子入锅煎后盛出。6、炒锅放油加热，姜丝入锅煸香后，加虾仁、洋葱、茄子、辣椒、胡萝卜、木耳、黄花菜酱油、蚝油入锅翻炒。7、香菇连同泡香菇的水一同入锅。8、加适量的水，盖上锅盖烧开，加盐、味精，搅拌均匀。9、淋入芡汁、鸡蛋，搅拌均匀，煮开后关火。10、煮锅加水烧开，煮熟面条。。11、面条出锅，配上卤、黄瓜。",
    "1.茄子不去皮切成小丁，西红柿切成丁。并准备好葱花和姜末。2.准备好肉馅，3.起锅做油，油热后放入大料葱花和姜末煸炒出香味后放入肉馅。4.肉馅变色后放入茄子丁继续炒五分钟。5.茄子稍微变软后放入西红柿丁继续翻炒，把西红柿炒得基本没型后加入酱油和料酒。6、加入水煮开后大火炖十分钟，茄子炖懒后倒入水淀粉勾芡。出锅钱倒入适量的盐，关火后淋一点香油。",
    "1.茄洗净要皮切丝。2.装入容器用适量盐茄水煞约20钟左右。3.攥水装盘备用。4.洋葱切丝。5.西红柿切丝。6.蒜切碎备用。7.锅放油先茄油。8.煸炒至茄丝结黄茄。9.放入洋葱丝煸炒。10.煸炒至洋葱变软放入西红柿丝继续煸炒。11.放入番茄沙司煸炒均匀。12.放入白糖、盐、美极鲜调味。13.加入少许水火炖5钟。14.加入蒜碎关火拌匀。15.煮面。16.煮面条直接放入较碗浇西红柿茄素卤。"
  ],
  "question_type":"DESCRIPTION",
  "question_id":181534,
  "fact_or_opinion":"OPINION"
}

```



###### Language-and-Intelligent-Technology-Competition/2019/MRC/models/DuReader/data/raw/trainset/zhidao.train.json
```json 
{
  "documents":[
    {
      "is_selected":true,
      "title":"如何做茄子卤面",
      "paragraphs":[
        "<p><img src=\"23857019472\" \/><\/p><p>做法：<\/p><p>&nbsp; 1.茄子切小丁。<\/p><p>&nbsp; &nbsp;2.五花肉切小丁。<\/p><p>&nbsp; &nbsp;3.准备好豆酱。<\/p><p>&nbsp; &nbsp;4.油热后翻炒肉丁和茄子。<\/p><p>&nbsp; &nbsp;5.添适量水，煮开。<\/p><p>&nbsp; &nbsp;6.加黄豆酱拌匀，煮开即可。<\/p><p>&nbsp; &nbsp;7.水开后煮面条。<\/p><p>&nbsp; &nbsp;8.煮好的面过冷水。<\/p><p>&nbsp; &nbsp;9.盛适量的酱，拌匀即可食用。<\/p><p><img src=\"23857056418\" \/><\/p>",
        "茄子卤面的做法如下一、材料虾仁100g、茄子150g、面条350g、食盐适量、酱油适量、味精适量、姜适量、蚝油适量、调和油适量、柿子椒适量、洋葱适量、黑木耳适量、苦菜适量、香菇适量、胡萝卜适量、鸡蛋1只。二、做法1、虾去头去皮去肠，洗净备用。2、干香菇提前洗干净泡发，切成块继续放在水里泡。3、茄子去皮切成片。4、木耳、黄花菜提前泡发好回刀。洋葱、胡萝卜、辣椒切成块。5、炒锅放油加热，茄子入锅煎后盛出。6、炒锅放油加热，姜丝入锅煸香后，加虾仁、洋葱、茄子、辣椒、胡萝卜、木耳、黄花菜酱油、蚝油入锅翻炒。7、香菇连同泡香菇的水一同入锅。8、再加适量的水，盖上锅盖烧开，加盐、味精，搅拌均匀。9、淋入芡汁、鸡蛋，搅拌均匀，再煮开后关火。10、煮锅加水烧开，煮熟面条。11、面条出锅，配上卤、黄瓜即可。",
        "<p>准备：<\/p><p>圆茄子（挑选小一点嫩一点的茄子）、西红柿、五花肉。<\/p><p>配料：<\/p><p>盐、鸡精、白糖、姜片、大料、酱油、香油、五香粉、香菜段各适量。<\/p><p>做法：<\/p><p>1、茄子洗净去蒂后，切丁，西红柿洗净切丁，五花肉切丁；<\/p><p>2、茄丁放碗中，加少许盐腌制（片刻后用手攥出腌出的汤汁）；<\/p><p>3、炒锅油热后，放入姜片，五花肉，大火翻炒，肉微变色改为中火，煸炒至出油，下大料炒至发胀，盛出；<\/p><p>4、另起锅，放入茄子，不断翻炒至锅发干，放入西红柿丁翻炒片刻，加盐、白糖和将要，改用小火，加盖焖3分钟；<\/p><p>5、倒入五花肉，放鸡精和香叶，翻炒均匀出锅；<\/p><p><img src=\"1059364928\" \/><\/p>"
      ]
    },
    {
      "is_selected":true,
      "title":"茄子打卤面的做法",
      "paragraphs":[
        "准备： 圆茄子（挑选小一点嫩一点的茄子）、西红柿、五花肉。 配料： 盐、鸡精、白糖、姜片、大料、酱油、香油、五香粉、香菜段各适量。 做法： 1、茄子洗净去蒂后，切丁，西红柿洗净切丁，五花肉切丁； 2、茄丁放碗中，加少许盐腌制（片刻后用手攥出腌出的汤汁）； 3、炒锅油热后，放入姜片，五花肉，大火翻炒，肉微变色改为中火，煸炒至出油，下大料炒至发胀，盛出； 4、另起锅，放入茄子，不断翻炒至锅发干，放入西红柿丁翻炒片刻，加盐、白糖和将要，改用小火，加盖焖3分钟； 5、倒入五花肉，放鸡精和香叶，翻炒均匀出锅；",
        "<p>1、茄子不去皮切成小丁，西红柿也切成丁。并准备好葱花和姜末；<br \/>2、准备好肉馅，我家肉馅分装成一小块一小块的放在冰箱里冻着，吃的时候拿出来一块；<br \/>3、起锅做油，油热后放入大料葱花和姜末煸炒出香味后放入肉馅；<br \/>4、肉馅变色后放入茄子丁继续炒五分钟；<br \/>5、茄子稍微变软后放入西红柿丁继续翻炒，把西红柿炒得基本没型后加入酱油和料酒；<br \/>6、加入水煮开后大火炖十分钟，茄子炖懒后倒入水淀粉勾芡；出锅钱倒入适量的盐，关火后淋一点香油即可；<br \/>7、面条煮熟后，用凉水过的透透的，浇上卤，上面再来点黄瓜丝和一小撮香菜。对了，吃的时候再来两瓣蒜。<\/p><p><img src=\"33914332917\" \/><\/p>"
      ]
    },
    {
      "is_selected":true,
      "title":"卤面的做法,
      西红柿茄子素卤面怎么做好吃",
      "paragraphs":[
        "前言这几日同宝贝上火，似乎缺了麻辣油就吃不下饭了！！",
        "1.茄子洗净，不要去皮，切成丝。2.装入容器中，用适量的盐将茄子的水分煞出来。约20分钟左右。3.然后攥出水分，装盘备用。4.洋葱切丝。5.西红柿切丝。6.蒜切碎备用。7.锅中放油，先将茄子过油。8.煸炒至茄子丝结黄茄。9.放入洋葱丝煸炒。10.煸炒至洋葱变软放入西红柿丝继续煸炒。11.放入番茄沙司，煸炒均匀。12.放入白糖、盐、美极鲜调味。13.加入少许的水，中火炖5分钟。14.最后加入蒜碎，关火，拌匀。15.煮面。16.煮好的面条直接放入一个较大的碗中，浇上‘西红柿茄子素卤’就尽情的享用吧。"
      ]
    },
    {
      "is_selected":false,
      "title":"茄子打卤面怎么做好吃",
      "paragraphs":[
        "茄子打卤面怎么做好吃材料一个中等大小的茄子，四两猪肉馅，两个鸡蛋，葱姜少许。做法先将茄子切成小丁待用。鸡蛋摊成鸡蛋片，如图 2 ，然后切成小方片。锅里放油稍多一点儿，茄子吃油，直接放进茄子丁，加点盐（稍多，要拌面）腾烂（炒软）盛出。再放少许油炒香葱姜放入肉末，加料酒生抽炒熟，变色即可，再放进茄子丁，鸡蛋片，加鸡精和水开锅即可。最后淋上花椒油撒些香菜末。"
      ]
    },
    {
      "is_selected":false,
      "title":"茄子面条卤怎么做_百度知道",
      "paragraphs":[
        "茄子肉切丁，肉要肥一点，肉爆炒出油，加佐料，盐多放些，放茄丁炖好既成",
        "1.提前泡发木耳。2.提前将花生米洗干净用冷水浸泡2个小时。3.泡过的花生米入微波炉加工至6、7分熟。4.猪肉切碎。5.胡萝卜洗干净切成丝。6.胡萝卜入煮锅焯水。7.木耳入煮锅焯水。8.茄子洗干净切成片。9.炒锅放油加热，茄子入锅煎。煎好后盛出。10.炒锅放油加热，葱姜入锅煸香后猪肉入锅翻炒。11.加酱油翻炒。12.茄子入锅翻炒。13.花生米入锅翻炒。 加适量水，盖上锅盖焖一会儿。14.木耳入锅翻炒。15.加盐、味精翻炒。16.加枸杞翻炒。17.淋入芡汁，茄子卤就好了。18.黄瓜洗干净切成丝。19.将面条儿煮熟。20.面条儿配上茄子卤，再配上黄瓜、胡萝卜作菜码儿，即可享用茄子卤捞面。",
        "茄子切丁，加肉丁，放油锅里，翻炒，最后加点面酱，出锅叫好了。",
        "回答多了你不满意，回答少了你简单，最后那个，你们是刷分的吧，就你这样还问问题，食屎去吧"
      ]
    }
  ],
  "question":"茄子卤面的做法",
  "answers":[
    "1、虾去头去皮去肠，洗净备用。2、干香菇提前洗干净泡发，切成块继续放在水里泡。3、茄子去皮切成片。4、木耳、黄花菜提前泡发好回刀。洋葱、胡萝卜、辣椒切成块。5、炒锅放油加热，茄子入锅煎后盛出。6、炒锅放油加热，姜丝入锅煸香后，加虾仁、洋葱、茄子、辣椒、胡萝卜、木耳、黄花菜酱油、蚝油入锅翻炒。7、香菇连同泡香菇的水一同入锅。8、加适量的水，盖上锅盖烧开，加盐、味精，搅拌均匀。9、淋入芡汁、鸡蛋，搅拌均匀，煮开后关火。10、煮锅加水烧开，煮熟面条。。11、面条出锅，配上卤、黄瓜。",
    "1.茄子不去皮切成小丁，西红柿切成丁。并准备好葱花和姜末。2.准备好肉馅，3.起锅做油，油热后放入大料葱花和姜末煸炒出香味后放入肉馅。4.肉馅变色后放入茄子丁继续炒五分钟。5.茄子稍微变软后放入西红柿丁继续翻炒，把西红柿炒得基本没型后加入酱油和料酒。6、加入水煮开后大火炖十分钟，茄子炖懒后倒入水淀粉勾芡。出锅钱倒入适量的盐，关火后淋一点香油。",
    "1.茄洗净要皮切丝。2.装入容器用适量盐茄水煞约20钟左右。3.攥水装盘备用。4.洋葱切丝。5.西红柿切丝。6.蒜切碎备用。7.锅放油先茄油。8.煸炒至茄丝结黄茄。9.放入洋葱丝煸炒。10.煸炒至洋葱变软放入西红柿丝继续煸炒。11.放入番茄沙司煸炒均匀。12.放入白糖、盐、美极鲜调味。13.加入少许水火炖5钟。14.加入蒜碎关火拌匀。15.煮面。16.煮面条直接放入较碗浇西红柿茄素卤。"
  ],
  "question_type":"DESCRIPTION",
  "question_id":181534,
  "fact_or_opinion":"OPINION"
}
```


###### Language-and-Intelligent-Technology-Competition/2019/MRC/models/DuReader/data/raw/devset/search.dev.json
```json 
{
  "documents":[
    {
      "is_selected":true,
      "title":"2017年好看小说排行榜_小说推荐吧_百度贴吧",
      "paragraphs":[
        "2017年好书排行榜。读书十几年,
        晒晒让我沉醉的那些书单本书单没有主次,
        不要在意序号。1.《将夜》 作者:猫腻(起点白金作家) 简介:与天斗,
        其乐无穷。 故事概要: 主角宁缺带着从死人堆中挖出来的小侍女桑桑,
        报仇雪恨的故事。 推荐理由:一.文笔牛逼:猫腻的文读者很舒服,
        不喜欢小白文的人无法错过的好书。二.剧情牛逼:猫腻对文章的构思非常巧妙,
        不看到最后,
        你根本不知道结局会怎样。三.人物牛逼:莫山山与叶红鱼,
        是故事中宁缺的两位红颜知己。四.最后她们没有和宁缺走在一起,
        是一件自认为很遗憾的事。(嗯……这是以男人的角度。)无法让人忘怀的地方:书院。 书院有夫子,
        喜欢书中一句话,
        世间无夫子,
        万古如长夜。(希望没有记错。) 书院有大师兄,
        大师兄李慢慢为人仁爱,
        曾因为君子可以欺之以方困扰,
        后在宁缺受到危险时,
        终于学会了杀人。 书院有二师兄,
        二师兄君陌,
        一直以小师叔为榜样的君陌,
        一直想把号称天下第一剑的柳白斩于剑下。书院有三师姐,
        三师姐余帘,
        额……突然想到既然是推书,
        就不能写太详细,
        毕竟透剧会被人弹丁丁。咳咳总而言之,
        这是一本不容错过的好书。 2.《择天记》 作者:猫腻too(嗯……别误会,
        我只是想表达也是猫腻。) 相对将夜,
        这是一本正在写的新书,
        值得一看。 最近还在影视改编,
        据说主角陈长生,
        饰演是鹿晗,
        我也很喜欢鹿晗的小清新,
        但是我觉得演陈长生气质方面两种美,
        有点毁剧,
        当然还没上映,
        如此谈论未免为时尚早。 3.《冒牌大英雄》 作者:七十二编。这本书,
        猥琐流的神书,
        背景机甲宇宙什么的。写这本书的作者一本封神,
        所以这本书真的非常牛逼。而且这本书已经完本。喜欢猥琐流的,
        本人强烈推荐看这本书,
        超赞。 4.《无限恐怖》 作者:zhttty 无限流开山之祖的神书。 喜欢无限流的,
        不容错过。 5.《恐怖搞校》作者:大宋红福坊这本书将无限流和校园相结合,
        非常有创意。 6.《大国医》 作者:美味宋罗汤 这是一部历史类的书,
        也是我唯一看过的历史类。 当然如果《寻秦记》算历史类的,
        那么这本是第二本。 讲述主角洗了糊涂成为一代国医的故事。 文风幽默风趣,
        很好看。 红颜知己也多,
        啧啧。 7.《龙魔导》 作者:想屠神的疯子 作品简洁:什么?你要考哈弗? 当其他童鞋正忙备战高考的时候。 李山已经学会了精神力的发散运用。李山:“高考很难么?这么多答案让我筛选……” 什么?你要结婚了? 当其他童鞋正为求得白富美沾沾自喜时。 李山在头疼,
        今天去找精灵女友还是猫女又或者…… 李山:“不要这么看着我,
        我很纯洁的,
        就拉拉小手。”故事概述:主角李山在一款叫做凯撒大陆的游戏中赢得了一台虚拟现实游戏仓。但是却发现使用这台游戏仓后,
        在游戏中获得的属性加成竟然影响着现实世界。后来在主角的一再证实下,
        终于证明他参加的并不是游戏,
        而是另一个现实世界。至此,
        主角潇洒的一生就此起航。 推荐理由:1.文笔不错,
        刻画生动,
        有将夜之风。2.人物不错,
        主角是一位拥有正义感的猥琐男。(丫的这个评论我笑了。)3.剧情不错,
        进展有些慢,
        但是也有一种娓娓道来的感觉,
        很喜欢。 先推荐这么多(未完待续)",
        "大家喜欢这个书单的话就顶高高,
        我继续更新,
        哇哈哈哈。(还有许多珍藏的说~)",
        "我靠,
        我怎么看到写的书了,
        楼主慧眼如炬,
        我也觉得《将夜》写的不错。",
        "书名:《第十三座消失的城》作者:城渡文案:她是瘾城的守护者,
        也是半生花店的甩手掌柜,
        她带着花店四处游历,
        走走停停,
        为瘾城招揽能人异士,
        也借此从无名转而盛名,
        想起了万年前的记忆,
        重遇了那方幽静。 她的半生花店有无数世间买不到或不曾见过的花种,
        她的花只卖给有缘人。来到她花店的人从不知她叫什么,
        只是世人皆称小妖,
        便以小妖之名而盛,
        皆不知她本为妖,
        数以万年。 她总是淡然处之,
        有人问起她:\"小妖,
        何事才能掀起你的波澜?\" 答之:”人生除死之外,
        一切都很简单。“而她,
        已死过一次。网站链接:http:\/\/www.s4yd.com\/modules\/article\/articleinfo.php?id=143",
        "这栋楼怎么可以塌了,
        顶起,
        吼嘿吼",
        "将夜这本书,
        就像看到一个漂亮的苹果,
        咬了一口发现美味的很,
        于是一口吞了剩余的,
        却发现全是虫子。文青、造作到让你反胃,
        为了凑字更是啰里啰嗦刻意拖慢剧情。这本书比喻一个人的话,
        就像一个夹着腿内八字走路的男人,
        简直倒胃口!",
        "这个贴吧是被腐女和基佬攻占了么",
        "书不错呦,
        还有没有了!!!!!",
        "千苒君笑的《凤求凰》就写不错还有部天衣有风写的《凤囚凰》这两部都可以看看个人比较喜欢",
        "继续前,
        感叹下第七本已经烂尾了……这心情……8.《寻秦记》作者:黄易故事简述:第一本穿越小说(可能是第二本,
        咳咳……或者第三本,
        但反正很早。)讲述主角项少龙,
        一个特种兵回到大秦王朝还未统一天下的时候。故事的内容就如作者名字的第一个字一般,
        很x故事逻辑严谨,
        剧情跌宕起伏,
        每一个女主人公刻画的都非常深刻。9.《仙鸿路》"
      ]
    },
    {
      "is_selected":false,
      "title":"小说排行榜,
      小说排行榜2017前十名-搜狗小说",
      "paragraphs":[
        "玄幻小说排行榜  奇幻小说排行榜  武侠小说排行榜  仙侠小说排行榜  都市小说排行榜  悬疑小说排行榜  游戏小说排行榜  竞技小说排行榜  历史小说排行榜  军事小说排行榜  科幻小说排行榜  灵异小说排行榜  古言小说排行榜  言情小说排行榜  穿越小说排行榜  总裁小说排行榜  青春小说排行榜  耽美小说排行榜"
      ]
    },
    {
      "is_selected":true,
      "title":"2017最好看的穿越小说 穿越小说排行榜前10名",
      "paragraphs":[
        "近年来,
        穿越小说、穿越剧以时尚、前卫的姿态进入到公众的视野当中,
        并且席卷了中国的电视荧屏,
        形成一股强烈的“穿越”之风。这么多的穿越小说中,
        好看的完结穿越小说有哪些?以下是小编推荐给大家的关于2017最好看的穿越小说,
        来看看有没有你喜欢的吧!",
        "一: 【我们住在一起】 投资银行的简称,
        并不是真的银行,
        是券商的说,
        一般就是给一些发展还不错的公司做做上市啦、再融资啦、发行债券啦、并购重组啦之类的玩意儿,
        包括了北漂,
        合租,
        职场(投行),
        隐身富二代,
        女菜鸟变业务精英等职业。 二: 【月都花落,
        沧海花开】 作者:君子以泽 此书古风韵味十足,
        像是一部“诗作”。结局中性,
        不喜也不悲,
        却让人哭得眼肿。明月和沧海相互倾慕,
        却只能遥遥相望,
        真真让人唏嘘。薇薇最后闭眼前看到自己变年轻又见到师尊的幻境,
        兴许也是薇薇和胤泽互相的思念而产生的。期待薇薇胤泽来世再续前缘,
        期待沧海的花快开。 三: 【天定风华】 作者:天下归元 【天定风华】1、2、3讲述的是君珂的故事,
        又名【天定风流】,
        【千金笑】。【天定风华】4、5、6讲述的是太史阑的故事,
        又名【凤倾天阑】。君珂与太史阑为好友,
        同时穿越,
        降落地点不同,
        穿越后10年两人才相遇。典型的穿越剧,
        精彩又好看。 四: 【寻找爱情的邹小姐】 作者: 匪我思存 重量级言情作家匪我思存的大作【寻找爱情的邹小姐】延续其一贯的“虐恋”风格,
        讲述了一堆都市爱人的苦情恋。作品中的故事经历跌宕起伏,
        主人公更是命运多舛,
        其中的爱情故事更是有很多传奇的结局。每一对恋人的爱情都是不一样的,
        都是独一无二的,
        每个人只有在自己的感情里才能有自己真实的感受。只要心中有爱,
        爱就无处不在。就像书中表达的,
        我们为了爱奔波劳碌,
        甚至终其一生的追求爱情,
        然而在百转千回、峰回路转之后,
        我们期许的爱情其实一直在那里。",
        "五: 【应许之日】",
        "作者: 辛夷坞",
        "【应许之日】是以封澜这一大龄女起伏不断的生活为主线展开的描述。封澜和她的男友分手之前夕迎来的是男友和其他女人的结婚请柬。然而作为一个餐厅的老板娘,
        封澜竟然喜欢上餐厅里的服务员丁小野,
        然而丁小野也不爱她,
        他是一个猎手,
        亲手捕获鲜活的猎物,
        封澜就是他的猎物。而读完【应许之日】,
        并没有阴险,
        没有所谓的捕获,
        而是有一种很暖的感觉。作者辛夷坞尝试过多种风格的写作,
        而此部【应许之日】更是一部献给每个为爱执着人的一大力作。",
        "六: 【星光的彼端】",
        "作者: 青罗扇子",
        "范冰冰说,
        一个人的诋毁和赞美同样多;千颂伊,
        不会陷入嫉妒的深渊,
        不会自己落水了还要拉上别人共同踏入泥潭。深谙电影与文学中国女作家青罗扇子,
        文风以大气励志,
        时尚深刻,
        【星光的彼端】也正是延续了这样的文风,
        并且文中多体现的是如何真正理解爱,
        如何去爱别人。文中主人公宋微与黄锦立两人之间爱恨纠结,
        涉及名利、事业、女性自立自强。“一个女人只会伤心三次。第一次,
        她想要的是他的爱,
        但不被公平对待;第二次,
        她退而求其次,
        只想要一份尊重,
        却被践踏努力;到了第三次,
        她已经什么都想不要了——因为这次,
        她只为自己加冕为王。多么富有哲理。一个不懂得如何去爱的人,
        是否还能有机会再爱一次?青罗扇子说:有时爱一个人,
        不是因为他给了你幻想,
        而是你明白了自己的尊严与骄傲。",
        "七: 【他来了,
        请闭眼】",
        "在继【如果蜗牛有爱情】之后,
        此部作品是丁墨再次创作出的超人气甜蜜爱情故事,
        作为网络写手,
        他独特的甜宠悬爱风格吸引了一大批读者,
        其文思巧妙、其开篇就给人一种【神探夏洛克】的感觉,
        因为薄靳言和傅子遇丝毫不逊于卷福和花生。作品中对大神薄小猫才华横溢与智慧过人的描写以及其骄傲、盛气凌人的描写固然入木三分,
        情绪与性格等内在描写非常到位,
        但是,
        在看过作品后最让人动容的是大神对瑶瑶毫无保留的、纯真热烈的、至死不渝的爱。",
        "八: 【何以笙箫默】",
        "电视剧的热播让这部剧面向了更多人群,
        此剧的原著小说感觉名字深奥而又极富玄机,
        蕴含着何以琛对默笙没有说出口的爱恋。在小说里,
        默笙的名字来自徐志摩的【再别康桥】 ,
        而默笙,
        可理解为沉默的箫笙,
        也代表着默默的爱意。小说从头看到尾或许会感觉这个故事很老套,
        但是却真正体现了有些事情只能意会不能言传。只有真正理解了主人公之间的感情,
        才觉得即便老套的故事也能体现出不一样的内心深处的感情。",
        "九: 【岁月是朵双生花】",
        "作者: 唐七公子",
        "读唐七的小说,
        往往在一开始找不到感觉,
        似乎它并不是多么的引人入胜,
        还感觉作者的描写非常啰嗦,
        但是,
        伴随着阅读的深入却会感觉此书越来越有意思,
        是一部非常不错的作品。该小说通过讲述女主角怀孕以后,
        由于车祸问题失忆了的故事。女主人公在失忆以后有了新的喜欢的人,
        但并没有得到。她有一个非常可爱的孩子,
        但是在发生车祸失忆之后却不记得孩子的爸爸。经过很多波折,
        小说有了一个完满的结局那便是主人公原来的爱人和记忆都回来了。",
        "十: 【夏有乔木 雅望天堂】",
        "籽月总是把爱情写得如此之抵死纠缠,
        甚至感觉残忍不堪,
        正因为其残忍,
        其结局的不完美,
        才容易引起人们的深思。在小说中,
        每一个人都付之一炬,
        最后全部坍塌。正因为此,
        所谓的爱坍塌了、信仰坍塌了,
        甚至付出了生命。一直以来,
        籽月作为国内一线青春畅销书的新锐作家,
        最擅长用最朴实的文字来塑造丰满的人物形象,
        她让我们感觉青春要用最真挚的情感来纪念。此小说非常值得一遍遍的去阅读,
        因为每一遍都有不同的感受,
        甚至读过后的感动会让人泣不成声。",
        "十一: 【忘川】",
        "此时在经过作者时隔六年的创作之后中终于完结,
        这是一部持续了六年的武林传奇,
        而作者顶着的“武侠言情天后”的标签,
        笑言:“纯粹是为了图书上架时方便分类而已。【忘川】承载了太多作者与读者的期待,
        该作品的诞生也极具戏剧性。",
        "十二: 【满满都是我对你的爱】",
        "作者: 顾西爵",
        "【满满都是我对你的爱】里的一些小段子便足以让网友为之疯狂,
        被万千网友誉为\"最萌最有爱,
        百看而不厌\"。【满满都是我对你的爱】最早是在2013年7月中旬第一次登载,
        便产生了超强的口碑效应,
        所以辛夷坞在读了本书后欢笑推荐,
        和安东尼【这些都是你给我的爱】一样温暖有爱。",
        "十三: 【欢喜记】",
        "作者: 石头与水",
        "与【千金记】是姐妹篇,
        此小说说明了一个很重要的道理便是可怜之人必有可恨之处。因为憋屈而死的赵长卿在重生之际,
        下定决心决定不再活的那样令人可怜可恨了。此文依然是深受读者喜爱的重生文,
        依然是以东穆江山为背景。",
        "十四: 【金陵春】",
        "周少瑾重生了,
        前世背叛她的表哥程辂自然被三振出局了,
        可她还有程许,
        程诣,
        程举等许多个表哥……这是个我与程家不得不说的故事!只看内容简介便知道此书又是一个重生的故事,
        重生的故事不管如何描述总是引来好奇的读者一观。"
      ]
    },
    {
      "is_selected":true,
      "title":"2017年第一季,
      超好看的小说大盘点",
      "paragraphs":[
        "文章 阅读",
        "2017年的第一季度刚刚过去,
        大家在这三个月里有读到什么好书吗?培根曾说过:“孤独寂寞时,
        阅读可以消遣。高谈阔论时,
        知识可供装饰。处世行事时,
        知识意味着才干。”不论你是一个尚且在学海中遨游的学生,
        还是一个已经工作多年的成熟社会人,
        读书从来不该带有功利的意味,
        而是该从中看到世界万事万物的运行轨迹,
        也该从中体味生活和成长进步。",
        "一年的52周里,
        即使每周坚持阅读一本书,
        总共也不过52本而已,
        更遑论现代人一直有着拖延症的通病,
        我们阅读的书籍实在太少了。在浩如烟海的出版物之中,
        小编为你精心挑选了几本极富趣味性、又不乏内涵的小说,
        希望能够让各位在有限的阅读时间里享受到更多的乐趣。",
        "《大唐悬疑录:长恨歌密码》 by:唐隐",
        "作品简介:杨贵妃究竟死于马嵬驿,
        还是逃生日本?",
        "大诗人白居易根据杨贵妃的秘闻写就名篇《长恨歌》,
        不想竟引来杀身之祸。各路僧、道、官、匪先后出动,
        齐齐盯上了《长恨歌》中的明文暗码……",
        "推荐理由:《大唐悬疑录》系列中,
        女神探裴玄静踏入了一个关乎国家兴衰的阴谋杀局之中,
        她历经艰辛,
        只为找到最终的真相。她曾说“身为大唐的子民,
        我知道大唐的荣光从来不是幻觉。我相信,
        并且愿意用生命去维护它”。",
        "这个故事中有为了天下人至死不渝的信仰,
        有为了爱人出生入死的爱情,
        有为了友人以一己之力对抗朝廷的大义,
        也有一个繁华落尽、残阳如血的大唐,
        推理解谜的同时,
        也展现了说不尽的人间百态、道不完的苦乐辛酸。",
        "《风雪追击》 by:东野圭吾",
        "作品简介:以暴风雪中的滑雪场为背景,
        讲述一个突然被指认为杀人凶手的男孩,
        为了洗清嫌疑而进行自救的故事。作者将缜密的故事逻辑与快节奏的滑板运动结合起来,
        带来一种奇特的、充满紧张感的阅读体验。没有血腥暴力,
        却让人陷入人性的思考,
        直戳人心:如果有一天,
        毫无征兆地被指控为凶手,
        你该怎么办?",
        "推荐理由:东野圭吾毫无争议是中国读者最为喜爱的悬疑大师,
        但看图书销售网站排行榜上永远挂着他一本又一本的小说便可下此结论。也许东野圭吾的文笔不是最佳,
        也许他的推理剧情显得过于简单,
        但他着实是一个讲故事的高手,
        他的书简单易看,
        真真正正称得上是让人想一口气看完的小说,
        无疑会给读者带来畅快淋漓的阅读体验。",
        "《草原动物园》 by:马伯庸",
        "作品简介:这是一位传教士带着“半个动物园”勇闯蒙古草原的奇幻故事。光绪末年,
        在京城的美国传教士柯罗威,
        突发奇想要去赤峰修建一座草原动物园。他带着雄狮、大象、鹦鹉、蟒蛇以及一对虎纹马、五只狒狒一起奔赴草原。草原上,
        盗梦少女预知未来、通晓动物语言的少年涅槃重生、神秘的狼变月夜现身。这是一部关于信仰的动物寓言,
        一场巨大的变革在勇士之地上演,
        一段史诗般的全新冒险自此展开……",
        "推荐理由:这是一场奇幻的梦境。梦境被心理学家视为对现实的逃避与反击,
        其本身仿佛就带着某种奇幻又虚无缥缈的意味,
        梦境也是文人想象力的源泉,
        在梦境之上构筑起的小说王国亦能够带领我们逃离现实世界。这种描写寻梦之旅的小说外国有《牧羊少年奇幻之旅》,
        我们有马伯庸的新书《草原动物园》,
        且看看马伯庸如何带我们走入这场梦境。",
        "《有匪2:离恨楼》 by:priest",
        "作品简介:周翡没有等来段九娘,
        却一头撞上青龙主郑罗生。\"南北双刀\"传人、\"山川剑\"后人、芙蓉神掌……竟全在衡山脚下这一间小小的\"三春客栈\"凑齐了。\"山川剑\"亡故,
        一把剑鞘却被多方争夺;忠武将军死后,
        家眷南渡时遭北斗追杀;齐门生变,
        至今下落不明;而衡山这样大的门派,
        竟也人去楼空……然而洗墨江边冲天的火光,
        已经让周翡来不及细想这一切了。二十年了,
        风雨飘摇的夹缝里,
        这一隅的桃源,
        真能长久吗?",
        "推荐理由:也许由于对坚强勇敢的女孩子的偏爱,
        《大唐悬疑录》中的裴玄静与《有匪》中的周翡都曾让小编为之欢呼与落泪。这是一个江湖故事,
        也是一个浑身傲骨的女孩子如何在乱世之中摸爬滚打的故事。那个曾经不知天高地厚的水草精,
        终究长成了一个鬓似鸦羽、眉目宛然的红衣女侠,
        也终是在冷铁卷刃前得以窥见了天光。",
        "声明:本文由入驻搜狐公众平台的作者撰写,
        除搜狐官方账号外,
        观点仅代表作者本人,
        不代表搜狐立场。"
      ]
    },
    {
      "is_selected":false,
      "title":"2017年最好看的小说。推荐下。_百度知道",
      "paragraphs":[
        "女人30+保鲜攻略 作者: 蓝一薰 简介: 有人说,
        30几岁是女人最具风采、最懂生活的年龄。因为她们大多已经为人妻为人母,
        褪去了青涩、任性和幼稚之后,
        更加懂得珍惜生活,
        她们开始客观审视自己的过往,
        同时理性地规划着自己的未来。也有人说女人30岁开始,
        就成了凋萎的年龄,
        就像一朵鲜花有花期一样,
        虽然它有开得最美的时候",
        "楼主,
        请问是言情的还是耽美的!",
        "prist《默读》"
      ]
    }
  ],
  "entity_answers":[
    [
      "将夜",
      "择天记",
      "冒牌大英雄",
      "无限恐怖",
      "恐怖搞校",
      "大国医",
      "龙魔导"
    ],
    [
      "长恨歌密码",
      "风雪追击",
      "草原动物园",
      "离恨楼"
    ],
    [
      "我们住在一起",
      "月都花落",
      "沧海花开",
      "天定风华",
      "寻找爱情的邹小姐",
      "应许之日",
      "星光的彼端",
      "他来了",
      "请闭眼"
    ],
    [
      "金陵春",
      "女人30+保鲜攻略",
      "凤倾天阑",
      "寻找爱情的邹小姐",
      "忘川",
      "将夜",
      "凤囚凰",
      "无限恐怖",
      "有匪2:离恨楼",
      "夏有乔木 雅望天堂",
      "他来了,
      请闭眼",
      "千金笑",
      "牧羊少年奇幻之旅",
      "沧海花开",
      "龙魔导",
      "月都花落",
      "草原动物园",
      "凤求凰",
      "仙鸿路",
      "岁月是朵双生花",
      "有匪",
      "离恨楼",
      "千金记",
      "我们住在一起",
      "天定风流",
      "神探夏洛克",
      "择天记",
      "恐怖搞校",
      "风雪追击",
      "满满都是我对你的爱",
      "如果蜗牛有爱情",
      "天定风华",
      "第十三座消失的城",
      "星光的彼端",
      "何以笙箫默",
      "大唐悬疑录",
      "长恨歌密码",
      "欢喜记",
      "大国医",
      "请闭眼",
      "大唐悬疑录:长恨歌密码",
      "他来了",
      "默读",
      "月都花落,
      沧海花开",
      "应许之日",
      "寻秦记",
      "再别康桥",
      "冒牌大英雄"
    ]
  ],
  "question":"2017有什么好看的小说",
  "answers":[
    "1.《将夜》2.《择天记》3.《冒牌大英雄》4.《无限恐怖》5.《恐怖搞校》6.《大国医》7.《龙魔导》。",
    "《大唐悬疑录：长恨歌密码》、《风雪追击》、《草原动物园》、《有匪2：离恨楼》。",
    "我们住在一起、月都花落，沧海花开、天定风华、寻找爱情的邹小姐、应许之日、星光的彼端、他来了，请闭眼。"
  ],
  "question_type":"ENTITY",
  "question_id":186572,
  "fact_or_opinion":"OPINION"
}
``` 




###### Language-and-Intelligent-Technology-Competition/2019/MRC/models/DuReader/data/raw/devset/zhidao.dev.json
```json 
{
  "documents":[
    {
      "is_selected":true,
      "title":"手账是什么",
      "paragraphs":[
        "手账，指用于记事的本子。日本有一个很有趣的现象，无论男女老少，都随身携带一个称为“手帐”的笔记本，随时随地就掏出来记点什么。如果你要和他（她）约定一件什么事情的时候，对方一定先掏出手帐看一下。在通讯科技如此发达的日本，却人人都依赖这样原始的记录方式，这不禁让人惊讶。　　如果不是亲眼所见，外国人真的很难相信“手帐”对日本人的重要性。手帐并不是　　单纯的备忘录，除了提醒自己一些家人、朋友、客户的生日、约会，更重要的是安排自己每天的工作、生活，兼具日记功能。手帐大都制作精美，带有日历和笔，可以夹些名片和纸片，不同的页面划分具有超强的整理功能，以满足不同类型的需要。比如主妇专用手帐就会包含家政开支的内容等。总之，日本的手帐简直无所不能。难怪小小的一个本本，让商家费足了心思。特别近年来，手帐热潮不断升温。除了在杂志中以专题出现外，更是在作家笔下上升为“手帐哲学”，甚至有“手帐的使用方法决定你的人生”的说法。是否有些太夸张了？　　现在是日本的年底，又到了手帐热卖的季节。大大小小的百货、超市、书店、便利店等都设了专柜，摆满了花花绿绿的、保管让你挑得眼花缭乱的手帐。许多国际知名品牌如BURBERRY、GUCCI、PRADAD等也瞄准这块市场，纷纷推出自家个性手帐。有不同的大小、设计、品牌、价钱、页数可供选择，总有一本是你的心头好。再有喜欢与众不同的人，就只好自己动手制作一本绝版的手帐了。没有手帐，新的一年怎么开始？　　是日本人健忘吗？应该说他们喜欢按部就班，凡事都提前很久就作好计划，然后反复确认。就算家人之间也是如此。这也许是日本人“岛民性格”的一个表现吧。处于随时都可能发生的地震、台风的地理位置，只有未雨绸缪地作好防范，晚上才能睡得安稳。",
        "手账，指用于记事的本子。"
      ]
    },
    {
      "is_selected":false,
      "title":"手账干嘛用的",
      "paragraphs":[
        "就是手账书皮里面用的本子，有很多分类，例如记账、记单词、周记、日记等，还有空白和格子纸等"
      ]
    },
    {
      "is_selected":false,
      "title":"手账到底是什么,
      怎么做",
      "paragraphs":[
        "谢谢您的提问 如果你还有其他疑问可以继续问我 如果你对我的答案表示认同 也别忘了采纳我哦 谢谢您了！"
      ]
    },
    {
      "is_selected":false,
      "title":"手账要用些什么东西?",
      "paragraphs":[
        "您好,
        会计学堂晓海老师为您解答会计手工帐的流程，包括手工账需要哪些材料，看看对你有帮助吗？ 会计流程：给原始凭证分类---填制会计凭证---登记会计账簿---记账凭证汇总---记总账---对账结账---编制会计报表---报税，纳税。1、给原始凭证分类：拿来原始凭证后，要检查是否合乎入账手续。2、编制记账凭证：根据原始凭证的分类，我们就可以做凭证了，凭证也叫传票。记账凭证编写完毕，还要进行审核。3、登记账簿：凭证审核无误后，就应该登记账簿了。先给凭证按时间顺序编号，再根据记账凭证上的科目，逐笔登记到对应的账簿上。账簿中只有现金和银行存款日记账要做到日清月结，现金账的余额要和库存也就是保险柜中的现金数目核对，银行账的余额要和银行对账单定期核对，其他的明细账是每个月结一次就行了。记账凭证做完了，记账就是抄账，把凭证上的内容抄到账簿上就完事了，很简单。4、记帐凭证汇总：就是把记账凭证的科目和金额汇集到一起，汇总的顺序是：按凭证上的编号排好顺序，然后根据凭证上的科目做丁字账，一个科目一个科目的抄写，最后合计，看借方总合计数是否等于贷方总合计数，相等了，说明平了，然后把数据抄写在记账凭证汇总表上。5、登记总账：根据试算平衡的记账凭证汇总表，登记总账。登记总账和明细账有点不同，在明细账上，借方、贷方各自记一行，而总账是借贷方在一行上。还有，明细账是按照凭证记的，总账是按着汇总登记的。如果业务量小，一个月汇总一次，登记一次总账就可以，这些都看具体的情况。总账和明细账的关系：它们是相互制约的关系。总账，就是记各个明细账总数的，明细账，是总账的细分类。总账记的是会计的一级科目，而明细账除了一级科目，还有二级科目，比如固定资产一级科目，固定资产的项目就是它的二级科目。还有费用帐、低值易耗品账、应交税金账等等。到了月末，各个明细账的余额必须等于相对应的总账余额，如果不等，那多半是明细账记错了或记落了。6、对账、结账：记完总账就该对账和结账了，只要凭证是正确的，登记完的账也应该是正确的，但是手工记账，要经常对账，做到账证相符、账账相符、账实相符、账表相符。结账就是结算出把一段时间内本期的发生额合计和余额，然后将余额结转下期或者转入新账。7、编制会计报表：记完总账后，试算平衡了，就可以编制财务会计报表了。一般两张报表，资产负债表和利润表，还有一张是现金流量表，因为小企业很少有要这张表的。整个流程就是这样，这就是会计每个月要做的事情欢迎点我的昵乐-向会计学堂全体老师提问",
        "要买一个手账本，买许多手掌胶带，再进行装饰。最好在网上买"
      ]
    },
    {
      "is_selected":true,
      "title":"手账是什么?",
      "paragraphs":[
        "日程簿，日程表",
        "其实就是财政开支的一种记录，不过侧重于私人和家庭的。。*^_^*"
      ]
    }
  ],
  "question":"手账是什么",
  "answers":[
    "记事的本子。",
    "财政开支的一种记录，侧重于私人和家庭。",
    "日程簿，日程表。"
  ],
  "question_type":"DESCRIPTION",
  "fact_or_opinion":"FACT",
  "question_id":191572
}
```




###### Language-and-Intelligent-Technology-Competition/2019/MRC/models/DuReader/data/raw/testset/search.test.json
``` json
{
  "documents":[
    {
      "title":"win7如何创建局域网 局域网设置图文教程 ",
      "paragraphs":[
        "　　在公司开会的时候，想分享同一份资料;在玩游戏的时候，想大家一起玩，都可以用局域网来完成。创建局域网可能会很麻烦，但是如果创建临时局域网却十分简单。本次小编就为大家演示具体操作方法：",
        "相关文章：",
        "　　电脑高手教你怎样提高局域网速度",
        "　　win7如何设置局域网共享无需输入用户名和密码",
        "　　具体方法",
        "　　第一步：打开网络和共享中心，方法有两个：右键点击任务栏右下角网络图标，点击打开网络和共享中心;",
        "　　或者，从开始菜单进入控制面板点击查看网络状态和任务。相关文章推荐：华硕笔记本网卡驱动win7。",
        "　　第二步：在网络共享中心点击设置新的连接或网络，这个新的连接也就是我们所要的局域网。",
        "　　第三步：在界面中，滑动条拉到最底部，选择设置无线临时网络，再点击下一步，如下图。",
        "　　第四步：选择好后在界面上，会出现设置临时无线网的说明，无异议后，点击下一步。",
        "　　第五步：在设置临时网络界面，输入网络名和安全密钥，注意由于宽带的密码是八位数，所以临时网络的密码也是八位数，完成再点击下一步。",
        "　　第六步：稍等一会儿，如果出现下图时，说明已经创建好局域网了，界面上也有提醒如何共享文件，如果你有需要可以点击进去，不过共享的前提是另一方也输入密码连接了局域网。",
        "　　后记：在家里，你可以告知朋友密码一起玩游戏;在公司，你就可以告知同事密码加入局域网传输资料。这个临时网络的设置前提是电脑有无线网卡，没有无线网卡的台式机就需要外接无线网卡使用。",
        "　　其他相关教程推荐，windows7无线网络连接设置。更多精品Win7教程敬请关注windows7之家。",
        "　　为了更加方便用户重装系统，windows7之家现推出windows系统之家重装大师，windows之家系统重装大师内集成了windows之家更新的各类最新 windows系统，包括XP\/Win7\/Win8\/Win10等系统。完美激活让您在也不用烦恼了，强烈推荐大家使用!",
        "　　下载地址：http:\/\/chongzhuang.windowszj.com\/"
      ]
    },
    {
      "title":"win7怎么创建局域网 用于玩局域游戏",
      "paragraphs":[
        "建立主机：控制面板，所有控制面板项，网络和共享中心",
        "下面设置新的链接或网络，出现窗口向下拉，最下面有设置无线临时。。。。。。",
        "出现提示，再点下一步。输入网络名称（随便写）",
        "出现正在设置。。。。。。",
        "然后别的电脑（分机）能找到这台电脑。",
        "貌似，当设置后为局域网主机，不能上互联网。"
      ]
    },
    {
      "title":"win7笔记本间怎么建立无线局域网－－打游戏",
      "paragraphs":[
        "win7笔记本间怎么建立无线局域网－－打游戏",
        "一、打开网络和共享中心。（点击桌面右下角的无线图标弹出的窗口底部有打开网络和共享中心）",
        "二、点左边的\"管理无线网络\"。、再选择“添加”",
        "三、选择“创建临时网络”",
        "四、下一步。",
        "五、自己随便输入一个网络名。和密码再钩选下面的保存这个网络。不然不能长期使用。",
        "六、下一步……",
        "到这里。你的无线局域网就已建立完成了。",
        "这时候再打开网络和共享中心里面的管理无线网络就能看到你自己刚建立的无线网络了。",
        "（如果没有，则请重复以上步骤）",
        "不过到这还没呢。还有下文。",
        "这时候单击桌面右下角的无线图标在无线网络连接那应该就能看到你自己建的那个无线网了。…",
        "然后点击连接。就会显示等待用户连接、",
        "这时候就其它人加进来。你们就已经连网了。你们的无线局域网不过这时候还不能连机打游戏。还差最后一步",
        "打开到网络和共享中心。找到左边更改适配器设置。",
        "右击无线网络连接。再属性。找到ip4协议如图",
        "点击属性。再点使用下面的ip地址。",
        "再照图设置。 要求每台机子都要照图设置。但ip的最后那个数要不同。就是IP不能相同。但前三格要一样的。",
        "到此确定后你们就可以通过无线局域网连机打游戏了……"
      ]
    },
    {
      "title":"win7怎么建立局域网玩CS?",
      "paragraphs":[
        "win7建立局域网玩CS的方法如下：",
        "1、首先需要确保两台电脑在同一个工作组内，局域网内能相互访问（具体搜索WIN7组建局域网）",
        "2、打开网上邻居--属性--本地连接--属性--Internet协议(TCP\/IP)--属性--IP地址设为同一网段即可",
        "例如：",
        "A设为192.168.0.1",
        "B 设为192.168.0.2",
        "C 设为192.168.0.3",
        "D 设为192.168.0.4",
        "子网掩码统一设为255.255.255.0",
        "如果通过以上设置好，局域网内相互能复制传送文件，基本上就可以打CS了。",
        "3、将控制面板--安全中心--Windows防火墙关闭，如装瑞星等各类防火墙的最好全部关闭。",
        "打开高级安全window 防火墙 -----点击-----入站规则------点击右边------新建规则------程序,
        下一步------找到CS路径,
        下一步------允许连接,
        下一步------全选,
        下一步------名称,
        叙述随意写...完成...进CS局域网..你们就可以一起玩了...",
        "打开高级安全window 防火墙 -----点击-----入站规则------点击右边------新建规则------程序,
        下一步------找到CS路径,
        下一步------允许连接,
        下一步------全选,
        下一步------名称,
        叙述随意写...完成...进CS局域网..你们就可以一起玩了...望最佳答案!!!",
        "cs一般都可以直接联，不行的话可以去弄虎克局域网平台。我们都是这样联魔兽的。"
      ]
    }
  ],
  "question":"win7如何建立局域网玩游戏",
  "question_type":"DESCRIPTION",
  "fact_or_opinion":"FACT",
  "question_id":394867
}
```





###### Language-and-Intelligent-Technology-Competition/2019/MRC/models/DuReader/data/raw/testset/zhidao.test.json

``` json 
{
  "documents":[
    {
      "title":"大皇帝ipad能玩吗",
      "paragraphs":[
        "我都是免费几分钟测试可以玩而已。我都想找到。ipad有个arkvpn软件可以玩几个钟"
      ]
    },
    {
      "title":"苹果iPad Mini大皇帝不能登录怎么办",
      "paragraphs":[
        "如果我们遇到了游戏大皇帝不能登录怎么办，先看看不能登录的原因，是不是密码输入不对，如果是忘记密码，在登录框那里有个忘记密码提示，点击进入，按照提示选择密码管理，可以找回密码，如果忘记密码保护，也能进行帐号申诉，从而找回密码。如果不是以上的常规问题，建议重新下载。",
        "iPad mini4配置高"
      ]
    },
    {
      "title":"苹果怎么玩游族大皇帝",
      "paragraphs":[
        "你要到app store 下载该游戏，就可以玩了，首先要有帐号哦"
      ]
    },
    {
      "title":"怎么样才能在苹果手机上玩360游戏中的大皇帝",
      "paragraphs":[
        "下个xy苹果助手，不用越狱就可以玩",
        "请稍候",
        "你好朋友苹果后，用360手机助手下载安装这游戏就可以了"
      ]
    },
    {
      "title":"如何在ipad上继续玩360游戏？",
      "paragraphs":[
        "页游吗？直接打开safiri登陆。"
      ]
    }
  ],
  "question":"大皇帝ipad能玩吗",
  "question_type":"YES_NO",
  "fact_or_opinion":"FACT",
  "question_id":403770
}
```





### Preprocessed Data 
After the dataset is downloaded, there is still some work to do to run the baseline systems. DuReader dataset offers rich amount of documents for every user question, the documents are too long for popular RC models to cope with. In our baseline models, we preprocess the train set and development set data by selecting the paragraph that is **most related to the answer string,**  while for inferring(no available golden answer), we select the paragraph that is **most related to the question string**. The preprocessing strategy is implemented in utils/preprocess.py. To preprocess the raw data, you should first segment 'question', 'title', 'paragraphs' and then store the segemented result into 'segmented_question', 'segmented_title', 'segmented_paragraphs' like the downloaded preprocessed data, then run:
``` shell 
cat data/raw/trainset/search.train.json | python utils/preprocess.py > data/preprocessed/trainset/search.train.json
```
### Important Fields 
- documents: answer related documents list 
- segmented_title: title segemented 
- 
- paragraphs: paragraphs of each document 
- segmented_paragraphs: paragraphs of each document after segmented 
- 

### Sample Data 
###### Language-and-Intelligent-Technology-Competition/2019/MRC/models/DuReader/data/preprocessed/testset/zhidao.dev.json

``` json 
{"documents":[
   {
   "paragraphs":["首届禁烟奥运会是25届巴塞罗那奥运会。\n第二十五届巴塞罗那奥运会已被列为历史上的首届禁烟奥运会。除了运动场上禁止吸烟外，室外球场观众席也被列为禁止吸烟区。室内更是不准吸烟。其中包括抵制烟草制造商的任何形式的广告，严禁在奥运会的各赛场点出售烟草制品等。","1992年巴塞罗那","92年巴塞罗那>第25届奥运会","第二十五届巴塞罗那奥运会已被列为历史上的首届禁烟奥运会。除了运动场上禁止吸烟外，室外球场观众席也被列为禁止吸烟区。室内更是不准吸烟。其中包括抵制烟草制造商的任何形式的广告，严禁在奥运会的各赛场点出售烟草制品等。","首届禁烟奥运会是25届巴塞罗那奥运会\n第二十五届巴塞罗那奥运会已被列为历史上的首届禁>烟奥运会。除了运动场上禁止吸烟外，室外球场观众席也被列为禁止吸烟区。室内更是不准吸烟。其中包括抵制烟草制造商的任何形式的广告，严禁在奥运会的各赛场点出售烟草制品等。","第二十五届巴塞罗那奥运会已被列为历史上的首届禁烟奥运会。除了运动场上禁止吸烟外，室外球场观众席也被列为禁止吸烟区。室内更是不准吸烟。其中包括抵制烟草制造商的任何形式的广告，严禁在奥运会的各赛场点出售烟草制品等。"],
   "segmented_title":["首届","禁烟","奥运会","是","哪","届","？"],
   "segmented_paragraphs":[
      ["首届","禁烟","奥运会","是","25","届","巴塞罗那","奥运会","。","\n","第","二","十","五","届","巴塞罗那","奥运会","已","被","列为","历史","上","的","首届","禁烟","奥运会","。","除了","运动场","上","禁止","吸烟","外","，","室外","球场","观众席","也","被","列为","禁止","吸烟","区","。","室内","更","是","不准","吸烟","。","其中包括","抵制","烟草","制造商","的","任何形式","的","广告","，","严禁","在","奥运会","的","各","赛","场","点","出售","烟草制品","等","。"],
      ["1992","年","巴塞罗那"],["92","年","巴塞罗那","第","25","届","奥运会"],
      ["第","二","十","五","届","巴塞罗那","奥运会","已","被","列为","历史","上","的","首届","禁烟","奥运会","。","除了","运动场","上","禁止","吸烟","外","，","室外","球场","观众席","也","被","列为","禁止","吸烟","区","。","室内","更","是","不准","吸烟","。","其中包括","抵制","烟草","制造商","的","任何形式","的","广告","，","严禁","在","奥运会","的","各","赛","场","点","出售","烟草制品","等","。"],
      ["首届","禁烟","奥运会","是","25","届","巴塞罗那","奥运会","\n","第","二","十","五","届","巴塞罗那","奥运会","已","被","列为","历史","上","的","首届","禁烟","奥运会","。","除了","运动场","上","禁止","吸烟","外","，","室外","球场","观众席","也","被","列为","禁止","吸烟","区","。","室内","更","是","不准","吸烟","。","其中包括","抵制","烟草","制造商","的","任何形式","的","广告","，","严禁","在","奥运会","的","各","赛","场","点","出售","烟草制品","等","。"],
      ["第","二","十","五","届","巴塞罗那","奥运会","已","被","列为","历史","上","的","首届","禁烟","奥运会","。","除了","运动场","上","禁止","吸烟","外","，","室外","球场","观众席","也","被","列为","禁止","吸烟","区","。","室内","更","是","不准","吸烟","。","其中包括","抵制","烟草","制造商","的","任何形式","的","广告","，",">严禁","在","奥运会","的","各","赛","场","点","出售","烟草制品","等","。"]
      ],
      "title":"首届禁烟奥运会是哪届？"
    },
  {
    "paragraphs":["第25届巴塞罗那奥运会被列为历史上的首届禁烟奥运会。\n\n中文名：1992年巴塞罗那夏季奥林匹克运动会\n外文名：The1992BarcelonaOlympicGames\n举办时间：1992年7月25日-8月9日\n主办地点：西班牙加泰罗尼亚区首府巴塞罗那\n参赛国家地区：170","第二十五届巴塞罗那奥运会已被列为历史上的首届禁烟奥运会。除了运动场上禁止吸烟外，室外球场观众席也被列为禁止吸烟区。室内更是不准吸烟。其中包括抵制烟草制造商的任何形式的广告，严禁在奥运会的各赛场点出售烟草制品等。"],
    "segmented_title":["首届","禁烟","奥运会","是","哪","届"],
    "segmented_paragraphs":[
       ["第","25","届","巴塞罗那","奥运会","被","列为","历史","上","的","首届","禁烟","奥运会","。","\n","\n","中文名","：","1992","年","巴塞罗那","夏季","奥林匹克运动","会","\n","外文","名","：","The","1992","Barcelona","Olympic","Games","\n","举办","时间","：","1992","年","7","月","25","日","-","8","月","9","日","\n","主办","地点","：","西班牙","加泰","罗尼","亚","区","首府","巴塞罗那","\n","参赛","国家","地区","：","170"],["第","二","十","五","届","巴塞罗那","奥运会","已","被","列为","历史","上","的","首届","禁烟","奥运会","。","除了","运动场","上","禁止","吸烟","外","，","室外","球场","观众席","也","被","列为","禁止","吸烟","区","。","室内","更","是","不准","吸烟","。","其中包括","抵制","烟草","制造商","的","任何形式","的","广告","，","严禁","在","奥运会","的","各","赛","场","点","出售","烟草制品","等","。"]
  ],
  "title":"首届禁烟奥运会是哪届"
  },
  {"paragraphs":["第25届巴塞罗那奥运会被列为历史上的首届禁>烟奥运会。\n\n中文名：1992年巴塞罗那夏季奥林匹克运动会\n外文名：The1992BarcelonaOlympicGames\n举办时间：1992年7月25日-8月9日\n主办地点：西班牙加泰罗尼亚区首府巴塞罗那\n参赛国家地区：170","首届禁烟奥运会是25届巴塞罗那奥运会\n第二十五届巴塞罗那奥运会已被列为历史上的首届禁烟奥运会。除了运动场上禁止吸烟外，室外球>场观众席也被列为禁止吸烟区。室内更是不准吸烟。其中包括抵制烟草制造商的任何形式的广告，严禁在奥运会的各赛场点出售烟草制品等。","第二十五届巴塞罗那奥运会。","第二十五届巴塞罗那奥运会。\n\n\n\n哥们你要提多少问题啊","25届","二十五届巴塞罗那奥运会","第二十五届巴塞罗那奥运会已被列为历史上的首届禁烟奥运会。除了运动场上禁止吸烟外，室外球场观众席也被列为禁止吸烟区。室内更是不准吸烟。其中包括抵制烟草制造商的任何形式的广告，严禁在奥运会的各赛场点出售烟草制品等。","25","第二十五届巴塞罗那奥运会。"],"segmented_title":["21","、","首届","禁烟","奥运会","是","哪","届","？"],
  "segmented_paragraphs":[["第","25","届","巴塞罗那","奥运>会","被","列为","历史","上","的","首届","禁烟","奥运会","。","\n","\n","中文名","：","1992","年","巴塞罗那","夏季","奥林匹克运动","会","\n","外文","名","：","The","1992","Barcelona","Olympic","Games","\n","举办","时间","：","1992","年","7","月","25","日","-","8","月","9","日","\n","主办","地点","：","西班牙","加泰","罗尼","亚","区","首府","巴塞罗那","\n","参赛","国家","地区","：","170"],
  ["首届","禁烟","奥运会","是","25","届","巴塞罗那","奥运会","\n","第","二","十","五","届","巴塞罗那","奥运会","已","被","列为","历史","上","的","首届","禁烟","奥运会","。","除了","运动场","上","禁止","吸烟","外","，","室外","球场",">观众席","也","被","列为","禁止","吸烟","区","。","室内","更","是","不准","吸烟","。","其中包括","抵制","烟草","制造商","的","任何形式","的","广告","，","严禁","在","奥运会","的","各","赛","场","点","出售","烟草制品","等","。"],
  ["第","二","十","五","届","巴塞罗那","奥运会","。"],
  ["第","二","十","五","届","巴塞>罗那","奥运会","。","\n","\n","\n","\n","哥们","你","要","提","多少","问题","啊"],
  ["25","届"],
  ["二","十","五","届","巴塞罗那","奥运会"],
  ["第","二","十","五","届","巴塞罗那","奥运会","已","被","列为","历史","上","的","首届","禁烟","奥运会","。","除了","运动场","上","禁止","吸烟","外","，","室外","球场","观众席","也","被","列为","禁止","吸烟","区","。","室内","更","是","不准","吸烟","。","其中包括","抵制","烟草","制造商","的","任何形式","的","广告","，","严禁","在","奥运会","的","各","赛","场","点","出售","烟草制品","等","。"],
  ["25"],
  ["第","二","十","五","届","巴塞罗那","奥运会","。"]
  ],
  "title":"21、首届禁烟奥运会是哪届？"
  },
  {"paragraphs":["第二十五届巴塞罗那奥运会已被列为历史上的首届禁烟奥运会"],
    "segmented_title":["首届","禁烟","奥运会","是","哪","届","？"],
    "segmented_paragraphs":[
      ["第","二","十","五","届","巴塞罗那","奥运会","已","被","列为","历史","上","的","首届","禁烟","奥运会"]
      ],
      "title":"首届禁烟奥运会是哪届？"
   },
  {"paragraphs":["第25届巴塞罗那奥运会被列为历史上的首届禁烟奥运会。\n\n中文名：1992年巴塞罗那夏季奥林匹克运动会\n外文名：The1992BarcelonaOlympicGames\n举办时间：1992年7月25日-8月9日\n主办地点：西班牙加泰罗尼亚区首府巴塞罗那\n参赛国家地区：170","第二十五届巴塞罗那奥运会已被列为历史上的首届禁烟奥运会。除了运动场上禁止吸烟外，室外球场观众席也被列为禁止吸烟区。室内更是不准吸烟。其中包括抵制烟草制造商的任何形式的广告，严禁在奥运会的各赛场点出售烟草制品等。","第二十五届巴塞罗那奥运会已被列为历史上的首届禁烟奥运会。除了运动场上禁止吸烟外，室外球场观众席也被列为禁止吸烟区。室内更是不准吸烟。其中包括抵制烟草制造商的任何形式的广告，严禁在奥运会的各赛场点出售烟草制品等。"],
   "segmented_title":["首届","禁烟","奥运会","是","哪","届","？"],
   "segmented_paragraphs":[
   ["第","25","届","巴塞罗那","奥运会","被","列为","历史","上","的","首届","禁烟","奥运会","。","\n","\n","中文名","：","1992","年","巴塞罗那","夏季","奥林匹克运动","会","\n","外文",">名","：","The","1992","Barcelona","Olympic","Games","\n","举办","时间","：","1992","年","7","月","25","日","-","8","月","9","日","\n","主办","地点","：","西班牙","加泰","罗尼","亚","区","首府","巴塞罗那","\n","参赛","国家","地区","：","170"],
   ["第","二","十","五","届","巴塞罗那","奥运会","已","被","列为","历史","上","的","首届","禁烟","奥运会","。","除了","运动场","上","禁止","吸烟","外","，","室外","球场","观众席","也","被","列为","禁止","吸烟","区","。","室内","更","是","不准","吸烟","。","其中包括","抵制","烟草","制造商","的","任何形式","的","广告","，","严禁","在","奥运会","的","各","赛","场","点","出售","烟草制品","等","。"],
   ["第","二","十","五","届","巴塞罗那","奥运会","已","被","列为","历史","上","的","首届","禁烟","奥运会","。","除了","运动场","上","禁止","吸烟","外","，","室外","球场","观众席","也","被","列为","禁止","吸烟","区","。","室内","更","是","不准","吸烟","。","其中包括","抵制","烟草","制造商","的","任>何形式","的","广告","，","严禁","在","奥运会","的","各","赛","场","点","出售","烟草制品","等","。"]
   ],
   "title":"首届禁烟奥运会是哪届？"
   }
 ],
   "question":"首届禁烟奥运会是哪届",
   "segmented_question":["首届","禁烟","奥运会","是","哪","届"],
   "question_type":"ENTITY",
   "fact_or_opinion":"FACT",
   "question_id":368334}


```Todo: 方案介绍与使用
