# sangiovenale.github.io

Lavori svolti rifacendo la casa

## Development

Setup:
```
bower install bootstrap
```

Run development server:

```
jekyll serve
```

## jQuery and Bootstrap Update

```
cp bower_components/jquery/dist/jquery.min.* js/
cd bower_components/bootstrap
npm install
grunt dist
cd -
cp bower_components/bootstrap/dist/js/bootstrap.min.js js/
cp bower_components/bootstrap/dist/css/*.min.css css/
cp bower_components/bootstrap/dist/css/*.map css/
```
