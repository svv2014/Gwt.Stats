Gwt.Stats
=========
[![Build Status](https://travis-ci.org/svv2014/Gwt.Stats.svg?branch=master)](https://travis-ci.org/svv2014/Gwt.Stats)

#### Native Google Web Toolkit port of [stats](https://github.com/mrdoob/stats.js) ####

#### Install
Clon this project and run `mvn install` after add dependency to your project `pom.xml` 
`````
        <dependency>
            <groupId>gwt.stats</groupId>
            <artifactId>gwt-stats</artifactId>
            <version>0.1-SNAPSHOT</version>
            <scope>provided</scope>
        </dependency>
`````

#### Usage ####
Minimum of usage
```
    Stats stats = new Stats();
    RootPanel.get().getElement().appendChild(stats.getDomElement());
    ....
    //add this some where in your animation frame update 
    stats.update();
```

Please refer to [original utility](https://github.com/mrdoob/stats.js) from [mrdoob](https://github.com/mrdoob) for usage. Port uses the same simple API.

#### In Action ####
To see Gwt.Stats in action, please visit [gwt.threejs example “Earth”](http://vatula.github.com/gwt.threejs/examples/canvas_geometry_earth/Globe.html). Original Stats demo can be observed on [original three.js example “Earth”](http://mrdoob.github.com/three.js/examples/canvas_geometry_earth.html).
