# originate-react-component

[loom][1] origin for creating distributable react components. Sets up a distributable (npm, bower) react component, with tests and examples.

Fork of original [react-component](http://github.com/knomedia/originate-react-component) with :

 - zuul instead of karma
 - default .babelrc .eslintrc
 - packages : 
    - node-readme

## Usage

```sh
$ npm install -g loom
# now the originate program is available
$ originate react-component-revolunet my-component

$ cd my-component
$ npm install

#run local specs
$ npm test

$ npm start
#visit localhost:8080
```

## Local Developement

```sh
$ git clone https://github.com/revolunet/originate-react-component.git
$ cd originate-react-component
$ npm install
$ npm link

$ cd ..
$ npm link originate-react-component-revolunet

# now you can use the local repo version with:
$ originate react-component-revolunet my-component
```

## Licences and Copyright

MIT Style licence
(c) 2014 Jason Madsen

[1]:https://github.com/rpflorence/loom
