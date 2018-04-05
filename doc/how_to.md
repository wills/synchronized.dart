# Synchronized guide

* [Development notes](synchronized_development.md)

## Development guide

### Check list

* run test
* no warning
* string mode / implicit-casts: false

````
# quick run before commiting

dartfmt -w .
flutter analyze lib test
flutter test

flutter run
flutter run --preview-dart-2

# Using preview dart 2
flutter test --preview-dart-2
````
