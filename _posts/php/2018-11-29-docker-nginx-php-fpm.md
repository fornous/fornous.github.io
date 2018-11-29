---
layout: post
title:  "Dockerize Php app using Nginx and Php-FPM"
categories: [php, docker]
tags: [hot, summer]
comments: true
---

We had been serving several Php apps from premise - single hardware setup with 

## Original solution

## Why NginX and not Apache

The decision to move to this configuration is not based on measuring, but rather on experiences of other programmers. I just wanted to give a try to new kid on the block and test Php-Fpm.

```bash
# zanecha konfiguracni soubory a zavislosti
sudo apt remove <package>

# smaze konfiguracni soubory i zavislosti
sudo apt purge <package>
```

```javascript
class MyComponent extends Component {
  onClick(e){
    console.log("Toto je komponenta")
  }
  render() {
    return (
      <View>
        {# Toto nebude fungovat a bude vyhazovat hodnotu undefined #}
        <Button onPress={this.onClick} />
      </View>
    )
  }
}
```


```javascript
const ScreenComponent = ({showNext,item}) => (
  <View style={[{flex:1},styles.page]}>
    <TouchableHighlight onPress={showNext(item)}>
      <Image source={{uri:item.url}} style={[{width: 100, height: 100},styles.image]} />
      <Text style={styles.text}>{item.title}</Text>
    </TouchableHighlight>
  </View>
)

// navigation proxy example for NavigatorIOS
const ScreenNavigationProxy = ({navigation, item}) => (
  <ScreenComponent
    showNext={(item) => navigation.push({component:NextNavigationProxy,passParams={item:item}})}
    item={item}
  />
)
```