# Chakra API

[demo](https://rawgit.com/tbassett44/chakras/1.0/demo.html)

## Initalize
```
var chakrabody=new chakras($('#chakras'),{
    chakras:{
        crown:{
            intensity:7
        },
        thirdeye:{
            intensity:6
        },
        throat:{
            intensity:5
        },
        heart:{
            intensity:4
        },
        solarplexus:{
            intensity:3
        },
        sacral:{
            intensity:2
        },
        root:{
            intensity:1
        }
    }
});
chakrabody.start();
```

## Update
```
chakrabody.set('crown',{intensity:4})
```

## Other Options
```
{
    background:'https://s3.amazonaws.com/wearenectar/static/chakras.jpg', //background image put in (fit) container
    hara:.5,//hara line - where the chakras will line up relative to the container [0-1]
    radius:.06,//size of each chakra
}
```