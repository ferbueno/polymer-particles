# \<polymer-particles\>

A polymer integration with particles.js!

Special thanks to Vincent Garreau for his amazing library!

Checkout his [Github](https://github.com/VincentGarreau/particles.js) here!
Also, the configurator for the particles is [here!](http://vincentgarreau.com/particles.js/)

## Description
`polymer-particles` brings you an easy way to use the already easy particles.js library. Just add your URL to your configuration file and you're ready to go.

Example:

```
<polymer-particles></polymer-particles>
```

### Usage

1. Go to the [configurator](http://vincentgarreau.com/particles.js/) and get your configuration JSON. Also, you can create your own JSON with the help of the [documentation](https://github.com/VincentGarreau/particles.js).
2. Save your JSON within your app's directory, reachable by the component.
3. Install with bower
```
bower install --save ferbueno/polymer-particles
```

### Styling

The following properties and mixins are available for custom styling: 

| Custom Property                             | Description                                                          | Default  |
| ------------------------------------------- | -------------------------------------------------------------------- | -------- |
| --polymer-particles-background-display      | The display property to be asigned to the element.                   | block    |
| --polymer-particles-background-color        | The color for the background of the element.                         | red      |
| --polymer-particles-background-position     | The position property to be applied to the element.                  | relative |
| --polymer-particles-background-width        | The width to be applied to the element.                              | 100%     |
| --polymer-particles-background-height       | The height to be applied to the element.                             | 100%     |
| --polymer-particles-background              | Alternatively, the mixin that will be applied to the whole element.  | {}       |

### Properties

**jsonUrl**: string = "/default-config.json"
A relative url to your configuration JSON

**pJSDom**: array = []
An array that's needed to process the DOM for the library.

### Contributing

See something that needs changing? Just Fork It!

Make your feature branch and then send a pull request :D

### License

This element is licensed under the [MIT License](LICENSE.md)