*This repository is a mirror of the [component](http://component.io) module [matthewmueller/clock](http://github.com/matthewmueller/clock). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/matthewmueller-clock`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# clock

Create a swiss railway inspired clock.

![swiss clock](http://i.cloudup.com/dpi2yHoUlp.png)

## Installation

    $ component install matthewmueller/clock

## Example

```js
var clock = new Clock;

clock.refresh();
document.body.appendChild(clock.el);

setInterval(function() {
  clock.refresh();
}, 1000);
```

## API

#### `Clock(hour, minute, second)`

  Initialize a `Clock`

#### `Clock.refresh()`

Refresh the clock to the current time

```js
clock.refresh()
```

#### `Clock.hour(hr)`

Get or set the hour.

```js
clock.hour(5)
```

#### `Clock.minute(min)`

Get or set the minute

```js
clock.minute(30)
```

#### `Clock.second(sec)`

Get or set the second

```js
clock.second(45)
```

## License

  MIT
