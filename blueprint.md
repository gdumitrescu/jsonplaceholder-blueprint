FORMAT: X-1A
HOST: https://www.google.com

# JSONPlaceholder Blueprint

### Available resources:
- **Posts:** http://jsonplaceholder.apiary.io/v1/posts/1
- **TODO** - Albums: http://jsonplaceholder.apiary.io/v1/albums/1
- **TODO** - Comments: http://jsonplaceholder.apiary.io/v1/comments/1
- **TODO** - Photos: http://jsonplaceholder.apiary.io/v1/photos/1
- **TODO** - Todos: http://jsonplaceholder.apiary.io/v1/todos/1
- **TODO** - Users: http://jsonplaceholder.apiary.io/v1/users/1

### Credits
Inspired by [JSONPlaceholder](https://github.com/typicode/jsonplaceholder)

# Group Posts

## /v1/posts

### Creating Post [POST]
Creating a resource

Returns
    ```
    {
      "id": 134985902, // Random id
      "title": "foo",
      "body": "bar",
      "userId: 1
    }
    ```

    POST http://jsonplaceholder.apiary.io/v1/posts

+ Request JSON Message
    + Headers

            Accept: application/json

    + Body

            { "title": "foo", "body": "bar", "userId": 1 }


+ Response 201 (application/json)
    ```json
        {
          "id": 134985902,
          "title": "foo",
          "body": "bar",
          "userId": 1
        }
    ```

### Listing Posts [GET]
Listing resources

    GET http://jsonplaceholder.apiary.io/v1/posts

+ Request JSON Message
    + Headers

            Accept: application/json

+ Response 200 (application/json)
    ```json
        [{"id":1,"title":"quas laboriosam ea","body":"earum inventore sapiente\nerror nesciunt ut perferendis soluta suscipit\ndicta nemo at dolorem eveniet maxime ab labore est\neligendi molestias aliquam sapiente","userId":1},{"id":2,"title":"natus omnis voluptas cumque et aliquam","body":"sint delectus sed excepturi fuga exercitationem maiores dolor\niusto autem minus in officiis eaque laborum\naut ut a\nest ipsa soluta","userId":1},{"id":3,"title":"distinctio ut ipsa voluptas ea voluptatem sequi","body":"voluptatem esse illum\nnobis nisi sed numquam incidunt neque nulla sint\noptio quia rerum voluptas doloribus eligendi sit ea similique\nquo sed quod minus sit quo et dolor nesciunt","userId":1},{"id":4,"title":"officia consequatur id","body":"commodi recusandae mollitia et et rerum dolorem dolor iure\ntempore voluptas odio aut sint perferendis molestiae est quae\nsit voluptas ipsa facilis in non\nomnis ut qui cupiditate molestiae","userId":1},{"id":5,"title":"ut et unde quaerat inventore doloribus autem vel provident","body":"sunt quod ea et fuga quasi et odio ab\noccaecati vel autem est natus quas est asperiores libero\naut nihil et consectetur placeat sed\neveniet totam omnis est rerum possimus ea architecto deserunt","userId":1},{"id":6,"title":"saepe reiciendis rerum unde soluta quo repellat sed","body":"eum labore iusto ipsam esse ab dolorem\net eligendi sint et voluptas doloremque dolorem fuga repellat\nnon exercitationem consequatur et minus amet blanditiis\nmodi neque ipsam hic","userId":1},{"id":7,"title":"rem iure facilis","body":"architecto sit et quis exercitationem quia fuga\ndolor deleniti laboriosam magni eos quas\nest eum quam\nipsum asperiores qui pariatur","userId":1},{"id":8,"title":"expedita ducimus sed sapiente","body":"exercitationem ea beatae est aut\npraesentium dolorem est aliquid ad aut\nhic optio aperiam eos voluptas et omnis sit aut\nexcepturi repellat aut mollitia nihil nesciunt deserunt et aperiam","userId":1},{"id":9,"title":"ipsam incidunt quia doloremque eius libero","body":"aut quis ea nihil consequatur aliquam at et nihil\narchitecto eligendi sed\net minima est labore\nqui consequatur eum minus maxime id accusamus est molestiae","userId":1},{"id":10,"title":"quas et voluptas","body":"voluptatum aut voluptas et voluptates qui officiis voluptas unde\nodio molestiae reiciendis nulla iusto et qui error dolor\net numquam placeat aut maiores quia pariatur natus saepe\nvelit a natus culpa odit voluptatem praesentium doloribus vitae","userId":1},{"id":11,"title":"exercitationem numquam voluptatum","body":"aut dolor harum est culpa\nquia ad numquam quia earum molestiae alias id provident\niure consequatur enim\nerror minus et reprehenderit","userId":2},{"id":12,"title":"exercitationem deserunt alias","body":"numquam deserunt aut perspiciatis ea\nrerum vitae libero amet iste illo debitis mollitia\nvelit sed commodi\nrerum reprehenderit eos sit","userId":2},{"id":13,"title":"ea iusto perspiciatis ut aperiam aliquam omnis dignissimos aut","body":"magnam exercitationem nesciunt vitae\nminus voluptatem quia voluptates asperiores\nasperiores tempora minus numquam omnis voluptatum\nincidunt nulla labore blanditiis nihil sequi dicta quia","userId":2},{"id":14,"title":"dolor assumenda fuga non quas quibusdam et impedit est","body":"deleniti voluptatem non nemo tempore ducimus\nofficiis in reiciendis beatae tenetur aspernatur\nminus facilis quis iste voluptatem aut nam nihil\nvoluptas ullam deleniti quibusdam nam et et vero","userId":2},{"id":15,"title":"praesentium et sint dignissimos similique rerum alias","body":"dolore labore eum\nconsectetur autem quis vero occaecati\nlibero occaecati sit commodi aliquid debitis unde\nest qui odit","userId":2},{"id":16,"title":"distinctio soluta qui","body":"autem culpa architecto\nporro quia aliquam\nomnis ullam fugiat\nitaque excepturi sequi beatae nulla ipsam et necessitatibus laudantium","userId":2},{"id":17,"title":"ad quidem eos alias aut","body":"odit facere aliquid rerum similique consequatur neque\ndolorem molestiae perspiciatis blanditiis animi saepe id\nmaxime dolorem et aut dolorum aspernatur vel voluptate\nest et sed praesentium","userId":2},{"id":18,"title":"aut qui assumenda et debitis deserunt placeat consequatur perspiciatis","body":"omnis illum earum\nnobis velit qui dolores quasi totam sit occaecati optio\nillum aliquam autem iure\nvoluptatum velit similique","userId":2},{"id":19,"title":"et qui beatae accusamus","body":"necessitatibus eos nihil praesentium est in enim\nvoluptas dolorum molestiae a animi dolor similique\nab nihil illo et numquam esse consequatur magni non\nquia aut mollitia atque perferendis corrupti quae architecto ut","userId":2},{"id":20,"title":"ratione voluptas tempora accusamus vitae optio asperiores suscipit voluptatem","body":"id voluptate sequi fugiat\nconsequatur aut nobis distinctio excepturi natus eius praesentium\nminus dolor minima\nadipisci non quis qui occaecati officiis temporibus","userId":2},{"id":21,"title":"omnis iusto beatae laudantium","body":"at illo dolores molestiae quia recusandae ea\neaque quia cum voluptatum blanditiis et\net a quam aut ut ipsam excepturi iure est\net aspernatur assumenda occaecati est ut magni","userId":3},{"id":22,"title":"in consequatur et architecto odit et eaque","body":"consequatur distinctio omnis omnis molestiae adipisci\nfacere quaerat sunt quidem voluptatem vitae\ndoloribus sed architecto atque laudantium dolores aliquid quis ut\nexcepturi rem exercitationem dolore voluptas nesciunt odit","userId":3},{"id":23,"title":"illo officiis et quaerat amet aspernatur","body":"molestiae rerum quis odit nemo\nveritatis id neque voluptate\net iusto et similique\nut quia nihil rerum","userId":3},{"id":24,"title":"assumenda quo laboriosam porro exercitationem hic et voluptas mollitia","body":"voluptas vel expedita qui omnis magnam ab perferendis numquam\npraesentium ipsam aut amet\nharum reprehenderit expedita hic magnam\ndoloremque veniam consequatur nulla iusto","userId":3},{"id":25,"title":"quibusdam harum ipsam excepturi non est quod error","body":"omnis unde ea quia totam quia non dolore magnam\naut illo molestiae quisquam aut nisi qui\naspernatur enim iure excepturi velit\neum cumque et qui quo odio aut","userId":3},{"id":26,"title":"dolorem error atque","body":"molestiae veritatis corporis est est\nfuga necessitatibus molestiae\nsuscipit tenetur excepturi quia alias non sit illo illum\nautem et suscipit nostrum pariatur magnam laudantium","userId":3},{"id":27,"title":"velit impedit quisquam et explicabo","body":"eos adipisci et deserunt dolorem qui quaerat sed soluta\nquia ut illo enim enim odit beatae corporis\npraesentium quo minima neque totam qui consequatur\nrepellendus repudiandae neque eum officia dolores","userId":3},{"id":28,"title":"laudantium ut minus optio ducimus laboriosam sed et","body":"nihil praesentium fuga modi id\nquas ipsum incidunt sit\net enim ut quas\nblanditiis cupiditate nemo doloremque illo","userId":3},{"id":29,"title":"laborum impedit tempore optio qui","body":"accusantium impedit totam quaerat animi aperiam dolor illo\nquas ullam ex ut\naut voluptas non voluptatum fugit harum\ntenetur et illo laudantium qui tempore tempora suscipit vero","userId":3},{"id":30,"title":"eveniet placeat adipisci dolorem qui et","body":"repellendus suscipit et\nanimi placeat tempore facilis\neum vitae quam tempora sed amet natus voluptatem\nnon ut dolor modi mollitia culpa quasi reprehenderit","userId":3},{"id":31,"title":"itaque fugiat maiores eum quia recusandae quidem","body":"eum rem fuga voluptatem animi et saepe\nexercitationem vel accusamus et excepturi\nnulla libero assumenda tenetur omnis quo\nquia itaque dolorem assumenda veniam ratione totam laboriosam","userId":4},{"id":32,"title":"molestiae voluptas sit velit aut dolorem a quos et","body":"aut nulla voluptatibus qui mollitia quasi\nodit eaque est non ut id similique maxime sint\neveniet natus commodi vel fuga ea non voluptas\naperiam optio voluptatem blanditiis beatae","userId":4},{"id":33,"title":"suscipit omnis excepturi ipsam consequatur iure reprehenderit repellat eos","body":"aliquam sit fugit\nnihil quidem vel dolorum repudiandae est ducimus laborum ab\nsint dolores nisi id expedita similique suscipit\nmagni ex labore nihil eaque laborum quibusdam eveniet","userId":4},{"id":34,"title":"autem sit incidunt eveniet","body":"cupiditate deserunt occaecati et voluptatem rerum suscipit\nhic et in velit perspiciatis enim error est quaerat\nad corporis consequatur illum consequuntur nulla numquam nihil ullam\npossimus eaque suscipit exercitationem","userId":4},{"id":35,"title":"distinctio qui et","body":"a veniam dolorem qui voluptates est consequuntur ut\nnecessitatibus ipsum et officiis voluptatem\nculpa porro vel soluta officiis illum est\nalias quisquam error veritatis nihil exercitationem iure ducimus","userId":4},{"id":36,"title":"dicta dolorum tempora omnis aut","body":"nulla et est incidunt tempora\na eligendi autem eum\nofficia voluptatum alias beatae totam omnis est\nrem ea cumque ullam qui sapiente","userId":4},{"id":37,"title":"quibusdam non sunt ducimus","body":"sit commodi non exercitationem excepturi aut\nmolestias aut voluptatem aut pariatur\neveniet possimus voluptatibus illum dolores rerum ut corporis reprehenderit\naccusamus sed tempora nam vel deleniti quia id aut","userId":4},{"id":38,"title":"sit atque quo ad","body":"minus et officiis\nesse fugit facilis laudantium magnam\nlaboriosam necessitatibus qui repellendus sit deleniti sunt dolores eaque\nea accusantium ut consectetur perferendis et veritatis id et","userId":4},{"id":39,"title":"temporibus eaque ipsam ex quia quia eos","body":"mollitia ea veniam\net sapiente harum quas\neveniet praesentium excepturi molestias quae ut\nducimus assumenda qui temporibus illum ab voluptates","userId":4},{"id":40,"title":"et tempora quae dolores ipsum culpa deserunt","body":"ut rerum quisquam et laudantium impedit beatae tempore\nvoluptas sapiente commodi sint qui qui\nquo ea explicabo provident debitis ut\nerror numquam non ipsum iure ab et dolores voluptas","userId":4},{"id":41,"title":"quis impedit porro et aut","body":"rerum ipsa qui\ndebitis id veniam\nnisi reprehenderit est laudantium aut tenetur qui facilis\nquo eos animi et optio dolorum nihil","userId":5},{"id":42,"title":"ex est velit","body":"quia distinctio omnis dolorem nisi\nrerum quam id\nvoluptate voluptatibus ullam nemo optio rerum cum dicta\nquasi tempore veritatis laboriosam impedit omnis aliquid","userId":5},{"id":43,"title":"molestiae dolores pariatur architecto sit","body":"est et sit voluptas quas harum quod consectetur quisquam\ndicta quo nesciunt eveniet\nvelit iste quia aperiam error sunt voluptate dolore repudiandae\naperiam dolor similique fugiat non","userId":5},{"id":44,"title":"consectetur non temporibus distinctio at omnis","body":"ea et inventore eos\nnemo dolor est aut consectetur ea cumque error\nprovident consectetur et nulla voluptas similique dicta deleniti et\nquibusdam voluptatem voluptas iure eum aliquid sed","userId":5},{"id":45,"title":"inventore modi officia et","body":"accusantium nobis quis doloremque voluptas numquam aperiam facilis consequatur\nid minus qui cupiditate\nvoluptatem nemo dolorum et\naut nulla consectetur id qui","userId":5},{"id":46,"title":"quae vel assumenda maiores enim ea in praesentium","body":"veniam veritatis officia qui neque est qui natus\nneque excepturi libero\net cumque id temporibus qui libero\naliquid in eveniet fugit","userId":5},{"id":47,"title":"molestiae quidem sed animi vitae maiores reprehenderit","body":"sit aliquid veniam et iusto inventore autem ea\ndignissimos aut dolorum nemo necessitatibus\nfuga facilis esse ipsam praesentium velit dolores\ncum suscipit incidunt","userId":5},{"id":48,"title":"et sunt laboriosam","body":"quod excepturi delectus unde accusamus aut ipsum et et\nquo nihil nesciunt porro numquam labore aut qui illo\naccusantium autem dolorem enim rerum\nassumenda est et","userId":5},{"id":49,"title":"soluta molestiae non","body":"amet dolorem eos et est ut ex iusto\nnon qui voluptates et libero et aut dignissimos molestias\nassumenda et libero cumque est commodi iusto ut dicta\nconsequuntur nam expedita magnam illum iste nisi voluptatem","userId":5},{"id":50,"title":"sint architecto est ipsam earum accusamus illum","body":"esse a qui ut sunt velit nam vel tempore\nvoluptates veniam ullam dolorem ab quibusdam harum molestias\nomnis veritatis in perferendis\nadipisci quae voluptas blanditiis similique voluptatem expedita","userId":5},{"id":51,"title":"repellat omnis est reprehenderit doloribus distinctio","body":"doloremque corporis et vero recusandae excepturi soluta est aut\nquia eum hic perferendis perspiciatis\nvel voluptatum veniam molestias officia\nhic architecto vitae iste non qui id","userId":6},{"id":52,"title":"et et aut ipsa","body":"voluptas qui eos qui et aut officia porro corrupti\nvoluptas perferendis corrupti ut facere nihil ut\nconsequatur dolorem at\nodit qui quod quis laudantium assumenda libero quo","userId":6},{"id":53,"title":"voluptatem inventore qui dolorum consequatur neque cumque aut","body":"dolores quia suscipit cum culpa nihil\npraesentium occaecati quia dolorum sunt ut architecto\net nam magnam excepturi nostrum eum dolores quis\nomnis aut adipisci in","userId":6},{"id":54,"title":"id autem et molestiae minima perspiciatis","body":"excepturi voluptatem rem et aspernatur et amet et\nfugit rerum sunt\nconsequatur atque at aspernatur itaque porro fugiat necessitatibus placeat\nnostrum praesentium quis ut","userId":6},{"id":55,"title":"recusandae natus non molestias magnam rerum","body":"voluptatem commodi et pariatur eos\noccaecati in ratione\nnon quod qui\nquia voluptate delectus ratione eos non consequuntur officia commodi","userId":6},{"id":56,"title":"corporis quaerat deleniti eum quae asperiores error","body":"ex iure sapiente consequatur autem\nquae consequatur ut quaerat quidem unde omnis alias quo\nconsequuntur modi voluptates\neos placeat quo ut et","userId":6},{"id":57,"title":"excepturi tenetur exercitationem inventore alias","body":"iure eos et quaerat\npraesentium reprehenderit aliquam et enim modi magni labore\naut officia corrupti et animi et autem maxime\nut quas vero","userId":6},{"id":58,"title":"voluptatibus blanditiis quo corrupti","body":"qui pariatur illum aut inventore perspiciatis adipisci magni non\ntempore explicabo earum et\ndolorem repudiandae consequuntur consequatur aliquid id dolorem qui mollitia\ntotam harum consequuntur repellat dicta quis","userId":6},{"id":59,"title":"deserunt voluptas doloremque ullam perspiciatis saepe","body":"blanditiis qui ad non\nnon voluptatibus non suscipit\nsed sunt nam rem dolore aut enim\niste nobis et mollitia distinctio sit cum","userId":6},{"id":60,"title":"optio sint vero voluptatibus sapiente occaecati doloremque","body":"voluptatem sequi odio velit\nprovident labore nisi quisquam dolores fugiat est\nautem laudantium animi et\nvoluptatibus nisi mollitia quia a eaque","userId":6},{"id":61,"title":"atque eveniet asperiores possimus est voluptates","body":"cum rerum aut minus vel\naut animi ratione rem aperiam praesentium\nveritatis molestiae ut\nminus accusamus quos saepe ducimus","userId":7},{"id":62,"title":"quasi delectus nostrum ea quis error","body":"voluptas magnam voluptas esse\naliquam eum repellat illo\ndolor est quae distinctio incidunt officiis architecto ut\nsimilique autem enim alias nobis aut quia","userId":7},{"id":63,"title":"aliquam voluptatem occaecati omnis ut enim nihil soluta sed","body":"libero voluptatem officia\neligendi quos omnis\nratione voluptatum iure nihil\nrepellendus voluptas sunt rerum","userId":7},{"id":64,"title":"vitae harum sequi ratione maiores ut et quae quasi","body":"sunt libero praesentium totam ut quod enim\ndistinctio praesentium aut ex\ninventore et modi et enim id quia\nfuga animi in quam qui eos quis temporibus","userId":7},{"id":65,"title":"libero esse amet ut excepturi voluptate provident ea","body":"adipisci eveniet ratione nam maiores laudantium mollitia dolor\nmaxime veniam fugit\nnihil atque numquam rerum adipisci\nfugiat incidunt totam excepturi quia","userId":7},{"id":66,"title":"corrupti et beatae eos voluptas sit voluptas quibusdam nam","body":"vel voluptatem libero consequatur qui cupiditate\nquis veniam debitis qui nesciunt\nmaiores repellendus quo nemo corrupti et illum eius natus\nquis fugit et porro sed","userId":7},{"id":67,"title":"officia est suscipit autem atque et eos corrupti omnis","body":"molestiae repellendus ipsum fugit\nlibero neque qui hic ipsum est\nullam est voluptatibus incidunt mollitia\nquia eos tempore","userId":7},{"id":68,"title":"accusamus voluptas cum iste dignissimos rerum voluptatem","body":"qui ipsa dolorum\niusto expedita nam fugit porro quo et asperiores itaque\nvoluptate quia dolores repudiandae\net voluptas sint sapiente","userId":7},{"id":69,"title":"similique labore magnam sequi sed","body":"quis voluptatibus consequatur amet aspernatur veniam\nnumquam commodi amet quam\nnisi culpa et animi doloribus at officia\nconsequatur vero qui est sit et","userId":7},{"id":70,"title":"qui ut consequuntur debitis itaque soluta qui","body":"aspernatur qui sed ab dolorem\nvero necessitatibus ea quo\natque sequi optio distinctio minima\ndolorem cupiditate et","userId":7},{"id":71,"title":"doloremque non unde","body":"est atque consequatur et aliquam vitae cum\nillum sed eius\nvoluptatem dolores dicta et et ex neque vero\nquasi ducimus cumque dolor","userId":8},{"id":72,"title":"voluptates voluptatem magnam impedit","body":"cumque sunt consequatur deleniti at dolores debitis sed\naut reprehenderit sed nostrum at\nsoluta cum aliquid aut\nexplicabo officia ut maxime quas omnis","userId":8},{"id":73,"title":"quo illo facilis","body":"delectus sed ab totam sint rerum ducimus\noptio nihil consequatur occaecati molestiae\nat quia porro adipisci qui qui\nrerum nemo temporibus doloremque","userId":8},{"id":74,"title":"et dolores voluptate dolore ab possimus voluptas et sint","body":"in quo veritatis velit in\nincidunt occaecati natus rem eum\nerror ratione quae ipsum amet\nlaboriosam perferendis aspernatur aut doloremque sequi","userId":8},{"id":75,"title":"porro deserunt tempore eligendi eos","body":"excepturi consequatur aut et laboriosam\nnatus assumenda occaecati architecto dolores voluptas cumque\nvoluptatibus laudantium qui harum dicta\nporro provident reiciendis","userId":8},{"id":76,"title":"officiis autem delectus expedita aut","body":"suscipit perspiciatis porro\nad nam illo sit non id sit architecto impedit\ncorporis ratione qui reiciendis qui inventore commodi accusamus cupiditate\net quisquam aut est saepe","userId":8},{"id":77,"title":"odio voluptas natus rem","body":"eaque possimus est\nin facilis iste incidunt voluptatibus optio iure ea\nsaepe eos odit et est occaecati quia ipsa rem\ninventore atque saepe corrupti","userId":8},{"id":78,"title":"excepturi quo laborum","body":"eveniet soluta odit ratione harum ducimus\nquis eum voluptatem\nvoluptatibus aut aliquam ut et suscipit\nvelit beatae qui quis voluptas enim error omnis consequatur","userId":8},{"id":79,"title":"ducimus itaque dolorum","body":"totam odio aperiam harum qui omnis non\nnihil ipsam voluptatem illum velit debitis rem\nqui eveniet temporibus magni et corporis\nsuscipit esse qui eligendi fuga ab numquam","userId":8},{"id":80,"title":"autem qui exercitationem qui ut dolorum","body":"veritatis dolore doloremque qui at repellendus\nqui eligendi cumque corporis et\net quia dolor doloribus recusandae eum\nminima nihil quisquam non deleniti laboriosam eum voluptates","userId":8},{"id":81,"title":"ut sed delectus cumque qui adipisci","body":"quas sit accusamus non rerum\nvoluptas error amet\neos sed numquam voluptas omnis excepturi\nvoluptatum minus similique repudiandae omnis provident ratione iure assumenda","userId":9},{"id":82,"title":"hic porro qui aut","body":"totam beatae veritatis blanditiis molestiae modi enim\nquisquam eum dolore voluptatem quis eaque\nnemo nihil beatae\naliquam similique maxime minima","userId":9},{"id":83,"title":"et voluptas qui repudiandae corrupti sint laborum dolorum","body":"et ea et aliquam optio quia\ntempore distinctio quod dolore et tenetur ut aspernatur\nassumenda aperiam odit animi\nquis voluptatum beatae expedita nisi illo velit consequatur","userId":9},{"id":84,"title":"sunt aut sit exercitationem illo id nemo","body":"necessitatibus libero itaque\npraesentium ipsam debitis ab quod\nveniam in eligendi non voluptatum aut molestiae\ndolorem eveniet neque vel architecto id distinctio","userId":9},{"id":85,"title":"error nemo et nostrum culpa sint","body":"facere ea hic dolor ab molestiae aliquam rerum tenetur\nminima beatae qui facilis at officiis earum necessitatibus in\nvero qui sed aut recusandae id ipsum dolore facilis\nexplicabo temporibus dolorem esse laudantium","userId":9},{"id":86,"title":"est est incidunt animi","body":"ea id facere doloremque magni non\ncommodi officiis dolorem numquam\nrerum qui incidunt dolores consequatur omnis dignissimos\nratione maxime in natus et temporibus dicta ut voluptatum","userId":9},{"id":87,"title":"qui officiis qui consequatur vitae optio consequuntur","body":"ex pariatur aut\ndeleniti non placeat totam labore\nvero et voluptatibus qui placeat cupiditate praesentium itaque repudiandae\net ratione autem ea deserunt non eveniet optio","userId":9},{"id":88,"title":"iure maxime est inventore sunt perspiciatis qui et repudiandae","body":"nam quibusdam amet\nfacilis eius laudantium suscipit at quasi velit\nlaboriosam in inventore voluptatem placeat\nnihil rem omnis et vero dolor hic voluptas sed","userId":9},{"id":89,"title":"voluptate expedita cum nobis","body":"pariatur quod non\nad excepturi ut consectetur saepe odit\nea non voluptatibus ut neque facere et necessitatibus ipsa\nexplicabo repellat vel voluptas ducimus quos et iste","userId":9},{"id":90,"title":"iure corporis asperiores accusamus sit dolores nam maiores","body":"sunt eveniet quam odit sed voluptatibus temporibus\nmolestiae sunt et occaecati vel qui sit\nculpa nostrum aut quia odio eligendi minus aliquid\nblanditiis velit est dignissimos","userId":9},{"id":91,"title":"cupiditate accusantium et","body":"laudantium est voluptatem\nrerum ipsa ut et est omnis in consequatur dolores\nsint rem accusamus illum dolores veritatis\net et rerum sunt quia et ut","userId":10},{"id":92,"title":"non tenetur voluptatem","body":"ut ut nam nisi facilis aut quidem\nullam sit harum numquam est\nsoluta animi cupiditate esse occaecati adipisci aliquid ut reiciendis\nitaque aut reiciendis voluptatem autem","userId":10},{"id":93,"title":"vitae suscipit est et accusantium","body":"qui est et mollitia inventore\nquia est ipsam esse et omnis atque est ut\nmagnam recusandae error sit autem facilis dolore aliquam quod\nconsequuntur ab nam magnam tempore libero sint","userId":10},{"id":94,"title":"suscipit aliquam animi doloremque","body":"sapiente et veritatis rerum aut qui in\nquia id ipsa consequatur sapiente voluptate repellendus\nquasi sed porro eos tempore ipsam optio error\nsed quaerat beatae non iure","userId":10},{"id":95,"title":"voluptates deserunt asperiores repellat soluta maxime aut","body":"quidem non enim explicabo\nmagni reprehenderit commodi laudantium et\ntemporibus ut quia sit autem nostrum distinctio occaecati qui\nvoluptatem id in rerum corrupti","userId":10},{"id":96,"title":"distinctio necessitatibus minus","body":"omnis nemo expedita doloribus saepe est dicta sunt\nconsequuntur quibusdam tempora eius quo earum velit\ncorrupti eos vel quo et sed cupiditate in\nadipisci facilis ut","userId":10},{"id":97,"title":"atque inventore aut ducimus et quia molestiae","body":"nemo enim minima ad cumque quo\nomnis et molestiae omnis et eveniet maiores eum\nqui dignissimos excepturi praesentium nam temporibus consequuntur ut\nfugit itaque qui voluptas id esse","userId":10},{"id":98,"title":"facere qui quae","body":"qui ea quas perspiciatis dicta est iusto accusantium\nconsequatur vero sed numquam sint aut consequatur\nvelit non distinctio laboriosam dicta\ncommodi fuga tempora consequatur sed facere odit","userId":10},{"id":99,"title":"alias tempora sit qui","body":"sed labore voluptatum error ut ut\nut aut sed saepe et ducimus totam\nconsequatur qui est earum\nasperiores vel esse hic ducimus aliquam fuga debitis totam","userId":10},{"id":100,"title":"commodi consequatur fugit ullam","body":"nulla voluptas enim error autem quia\nrerum fugit laudantium omnis nulla\net enim debitis sit placeat voluptatibus harum\nfugiat modi at libero","userId":10}]
    ```

## /v1/posts/{id}

### Retrieve a Post [GET]
Showing a resource

    GET http://jsonplaceholder.apiary.io/v1/posts/1

+ Request JSON Message
    + Headers

            Accept: application/json

+ Parameters
    + id (required, integer) ... Post ID

+ Response 200 (application/json)
    ```json
    {
        "id": 1,
        "title": "quas laboriosam ea",
        "body": "earum inventore sapiente error nesciunt ut perferendis soluta suscipit dicta nemo at dolorem eveniet maxime ab labore est eligendi molestias aliquam sapiente",
        "userId": 1
    }
    ```

### Update a Post [PUT]
Updating a resource

    PUT http://jsonplaceholder.apiary.io/v1/posts/1

+ Request JSON Message
    + Headers

            Accept: application/json
    + Body

            { "id": 1, "title": "foo", "body": "bar', "userId": 1 }

+ Parameters
    + id (required, integer) ... Post ID

+ Response 200 (application/json)
    ```json
    {
        "id": 1,
        "title": "foo",
        "body": "bar",
        "userId": 1
    }
    ```

### Delete a Post [DELETE]
Deleting a resource

    DELETE http://jsonplaceholder.apiary.io/v1/posts/1

+ Request JSON Message
    + Headers

            Accept: application/json

+ Parameters
    + id (required, integer) ... Post ID

+ Response 200 (application/json)
    ```json
        { "message" : "deleted" }
    ```

# Group Comments
TODO: Comments Resource
    http://jsonplaceholder.apiary.io/v1/comments/1

# Group Albums
TODO: Albums Resource
    http://jsonplaceholder.apiary.io/v1/albums/1


# Group Photos
TODO: Photos Resource
    http://jsonplaceholder.apiary.io/photos/1

# Group Users
TODO: User Resource
    http://jsonplaceholder.apiary.io/v1/users/1

# Group Todos
TODO: Todos Resource
    http://jsonplaceholder.apiary.io/v1/todos/1



