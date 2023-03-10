# A list of maintained Purescript libraries

## Essential tools
- purs: the compiler
- spago: package manager and build tool
- esbuild: Javascript bundler used by spago

## Essential libraries
- [prelude](https://github.com/purescript/purescript-prelude)
- [effect](https://github.com/purescript/purescript-effect): native side effects (equivalent to IO in Haskell)
- [aff](https://github.com/purescript-contrib/purescript-aff): asynchronous effects
- [maybe](https://github.com/purescript/purescript-maybe): optional values
- [either](https://github.com/purescript/purescript-either): commonly used for error handling
- [arrays](https://github.com/purescript/purescript-arrays): javascript arrays
- [lists](https://github.com/purescript/purescript-lists): linked lists
- [transformers](https://github.com/purescript/purescript-transformers): monad transnformers ReaderT, StateT, MaybeT, etc (equivalent to mtl in Haskell)
- [exists](https://github.com/purescript/purescript-exists): encodes existential types.
- [profunctor-lenses](https://github.com/purescript-contrib/purescript-profunctor-lenses): A mechanism for updating, viewing, and setting values within nested data structures.

## Data structures
- [sequences](https://github.com/hdgarrood/purescript-sequences)
- [tree-rose](https://github.com/JordanMartinez/purescript-tree-rose): Tree zippers

## Maths
- [bigints](https://github.com/purescript-contrib/purescript-bigints): Arbitrary length integers. This is a simple wrapper around biginteger.js
- [js-bigints](https://github.com/rowtype-yoga/purescript-js-bigints): Alternative to bigints. FFI bindings for JavaScript's BigInt. Does not require external js libraries.
- [rationals](https://github.com/purescript-contrib/purescript-rationals): Rational numbers
- vectors: 2d and 3d vectors
- fast-vect: Vectors with size encoded in the type

## Random
- [random](https://github.com/purescript/purescript-random): A basic library to generate random numbers
- [gen](https://github.com/purescript/purescript-gen): A type class for random generator implementations.
- [generate-values](https://github.com/jordanmartinez/purescript-generate-values): An instance for gen and additional functions

## Routing
- [routing-duplex](https://github.com/natefaubion/purescript-routing-duplex): Simple bidirectional parser/printers for your routing data types

## Json
- [argonaut](https://github.com/purescript-contrib/purescript-argonaut): A collection of libraries for working with JSON in PureScript.
- [json-codecs](https://github.com/jordanmartinez/purescript-json-codecs): A bidirectional and unidirectional value-based and runtime-configurable typeclass-based JSON codec library. 

## Web

- [web-storage](https://github.com/purescript-web/purescript-web-storage): A low-level library for local storage
- [web-socket](https://github.com/purescript-web/purescript-web-socket): A low-level library for web sockets
- [web-workers](https://github.com/gbagan/purescript-web-workers): A low-level library for web workers

#### Ajax
- [fetch](https://github.com/rowtype-yoga/purescript-fetch) High-level library for the WHATWG Fetch Living Standard.
- [affjax](https://github.com/purescript-contrib/purescript-affjax): A library taking advantage of aff to enable pain-free asynchronous AJAX requests and response handling.

## UI
#### Halogen
- [halogen](https://github.com/purescript-halogen/purescript-halogen): A declarative, component-based library entirely written in purescript

#### React
- [react-basic](https://github.com/lumihq/purescript-react-basic): A binding to the React library
- [react-basic-hooks](https://github.com/megamaddu/purescript-react-basic-hooks): React hook API for react-basic

#### FRP
- [deku](https://github.com/mikesol/purescript-deku): A FRP web framework for apps that need to be fast
- [hyrule](https://github.com/mikesol/purescript-hyrule): An event library

#### CSS
- [tecton](https://github.com/nsaunders/purescript-tecton): Domain-specific language for authoring CSS

## Testing
- [spec](https://github.com/purescript-spec/purescript-spec): A testing framework, inspired by hspec.
