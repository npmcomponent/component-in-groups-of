*This repository is a mirror of the [component](http://component.io) module [component/in-groups-of](http://github.com/component/in-groups-of). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-in-groups-of`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# in-groups-of

  Return an array of arrays in groups of N

## Installation

```
$ component install component/in-groups-of
```

## Example

```js
var nums = [1,2,3,4,5,6,7,8,9,10];

inGroupsOf(nums, 5)
// => [[1,2,3,4,5], [6,7,8,9,10]]

inGroupsOf(nums, 4)
// => [[1,2,3,4], [5,6,7,8], [9,10]]

inGroupsOf(nums, 2)
//=> [[1,2], [3,4], [5,6], [7,8], [9,10]]
```

# License

  MIT
