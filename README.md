# awesome-realm
A curated list of awesome [Realm](https://realm.io/) resources, libraries, tools and applications

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing. Feel free to improve this list by contributing!

## Table of Contents
- [Resources](#resources)
   - [Documentation](#documentation)
   - [Articles](#articles)
   - [Books](#books)
   - [Talks](#talks)
   - [Tutorials](#tutorials)
   - [Community](#community)
   - [More](#more)
- [Tools](#tools)
- SDKs
  - [Swift](#swift)
    - [Sample apps](#swift-samples)
    - [Libraries and components](#swift-libs)
    - [Tools](#swift-tools)
  - [Java/Kotlin](#java)
    - [Sample apps](#java-samples)
    - [Libraries and components](#java-libs)
    - [Tools](#java-tools)
  - [Javascript](#javascript)
    - [Sample apps](#js-samples)
    - [Libraries and components](#js-libs)
    - [Tools](#js-tools)
  - [.Net & Unity](#dotnet)
    - [Unity Sample apps](#unity-samples)
    - [Libraries and components](#dotnet-libs)
  - [Dart](#dart)
    - [Sample apps](#dart-samples) 
  - [C++](#cpp)


## Resources
### Documentation
- [MongoDB Realm Docs](https://docs.mongodb.com/realm/) - Main documentation for MongoDB Realm

### Books
- [Building Modern Swift Apps with Realm Database](https://store.raywenderlich.com/products/realm-building-modern-swift-apps-with-realm-database) - Realm book from Marin Todorov

### Community
- [Realm Forum](https://www.mongodb.com/community/forums/c/realm/9) - The place to discuss Realm
- [Realm on StackOverflow](https://stackoverflow.com/questions/tagged/realm) - Realm Questions and Answers on StackOverflow
- [Realm meetups](https://live.mongodb.com/realm-global-community/) - Meetups about Realm where you can meet other Realm users

## Tools
- [Realm Studio](https://github.com/realm/realm-studio) - Realm Studio is a visual tool to view, edit, and design Realm Database files.

## Swift
- [Swift Mobile Database GitHub repo](https://github.com/realm/realm-swift)
- [Swift SDK Documentation](https://docs.mongodb.com/realm/sdk/swift/)
- [Swift SDK Reference](https://docs.mongodb.com/realm-sdks/swift/latest/)

### <a name="swift-samples"></a>Swift Sample Apps
- [Realm-Draw](https://github.com/realm/Realm-Drawing) - Drawing app that demonstrates the Realm mobile database and MongoDB Realm Sync.
- [RChat](https://github.com/realm/RChat) = Chat app built with SwiftUI and Realm
- [Realm-Sweeper](https://github.com/realm/Realm-Sweeper) - Collaborative version of the Windows Mine Sweeper app.
- [Inventory](https://github.com/realm/realm-sync-demos/tree/main/Inventory-app) - Showcases the Inventory & Delivery operations of a mid/large store chain.

### <a name="swift-libs"></a>Swift Libraries and Components
- [RxRealm](https://github.com/RxSwiftCommunity/RxRealm) - RxSwift extension for RealmSwift's types
- [LoginKit](https://github.com/realm/realm-loginkit) = General purpose account login user interface for apps build on Realm
- [DrawKit](https://github.com/realm/realm-drawkit) - Modular drawing library backed by Realm
- [Realm Converter](https://github.com/realm/realm-cocoa-converter) - Utility framework to make it easier to get data both in and out of Realm (imports from CSV, XLSX and JSON).
- [IceCream](https://github.com/caiyue1993/IceCream) - Sync Realm Database with CloudKit
- [RealmGeoQueries](https://github.com/mhergon/RealmGeoQueries) - Spatial queries. In the absence of official functions, this library provide the possibility to do proximity search.
- [CombineRealm](https://github.com/CombineCommunity/CombineRealm) - Combine extensions for Realm

### <a name="swift-tools"></a>Swift Tools
- [SwiftLint](https://github.com/realm/SwiftLint) - A tool to enforce Swift style and conventions.
- [Jazzy](https://github.com/realm/jazzy) - Create soulful docs for Swift & Objective-C

## <a name="java"> Java/Kotlin
- [Realm Java](https://github.com/realm/realm-java) - Java SDK for the Realm Mobile Database
- [Realm Kotlin](https://github.com/realm/realm-kotlin) - Kotlin Multiplatform and Android SDK for the Realm Mobile Database
   
### <a name="java-samples"></a>Java/Kotlin Sample Apps
- [Inventory](https://github.com/realm/realm-sync-demos/tree/main/Inventory-app) - Showcases the Inventory & Delivery operations of a mid/large store chain.
- [Kotlin Sample Apps](https://github.com/realm/realm-kotlin-samples) - a set of projects to help you learn about using Realm-Kotlin SDK Each sample demonstrates different use cases.
- [Fantasy Premier League](https://github.com/joreilly/FantasyPremierLeague) - Kotlin Multiplatform sample using Jetpack Compose, SwiftUI and Realm for local persistence.
   
### <a name="java-libs"></a>Java/Kotlin Libraries and Components
- [realm-android-adapters](https://github.com/realm/realm-android-adapters) - Adapters for combining Realm Java with Android UI components and framework classes
- [realmfieldnameshelper](https://github.com/cmelchior/realmfieldnameshelper) - Extension library used to create more type-safe queries.
   
### <a name="java-tools"></a>Java/Kotlin Tools
- [Flipper-Realm](https://github.com/kamgurgul/Flipper-Realm) - Android Realm driver for Flipper.
- [Stetho-Realm](https://github.com/uPhyca/stetho-realm) - Displays Realm database content in Stetho instead of SQLite database content.

## <a name="javascript"> Javascript
- [Realm-js](https://github.com/realm/realm-js) - Realm JavaScript SDK for Node, React Native and Electron
- [Realm-js Node Docs](https://docs.mongodb.com/realm/sdk/node/)
- [Realm-js React Native Docs](https://docs.mongodb.com/realm/sdk/react-native/)
- [Realm-js Reference](https://docs.mongodb.com/realm-sdks/js/latest/)
   
### <a name="js-samples"></a>Javascript Sample Apps
   
### <a name="js-libs"></a>Javascript Libraries and Components
- [Realm-React](https://www.npmjs.com/package/@realm/react) - Components that simplifies using Realm with React
- [Babel Realm Type-Safe Queries](https://github.com/tomduncalf/babel-realm-typesafe-plugin) - Creating type-safe queries for Realm using TypeScript and Babel
- [Realm Aggregate](https://github.com/sourabhbagrecha/realm-aggregate) - Simple aggregation pipeline framework for Realm

## <a name="dotnet"> .Net & Unity
- [Realm .Net](https://github.com/realm/realm-dotnet) - Realm SDK for DotNet & Unity
- [Realm .Net Documentation](https://docs.mongodb.com/realm/sdk/dotnet/)
- [Realm .Net Reference](https://docs.mongodb.com/realm-sdks/dotnet/latest/)
   
### <a name="unity-samples"></a>Unity Sample Apps
- [Unity Examples](https://github.com/realm/unity-examples) - Examples of how you can use Realm to enhance your games created in Unity3D.
- [Space Shooter](https://github.com/mongodb-developer/unity-space-shooter) - Space Shooter game build using Unity and realm.
- [Mongo World Game Demos](https://github.com/mongodb-developer/aws-reinvent-game-demo) - Games built with Unity and MongoDB Realm that can be experienced cross-platform on mobile as well as computer.
- [Infinite Runner](https://github.com/mongodb-developer/unity-infinite-runner) - Demo of a game using Realm for local storage
   
### <a name="dotnet-libs"></a>.Net Libraries and Components
- [realm-lfs](https://github.com/nirinchev/realm-lfs) - Interacting with binary files that are transparently uploaded to a 3rd party service (e.g. S3/Azure Blob Storage)
- [GroupedCollections](https://github.com/realm/realm-dotnet-groupedcollection) - Data bindable grouped collections that can be passed directly to a Xamarin.Forms ListView.
   
## <a name="dart"> Dart
- [Realm Dart](https://github.com/realm/realm-dart) - Realm SDK for Dart & Flutter (alpha)
- [Realm Flutter Documentation](https://docs.mongodb.com/realm/sdk/flutter/)
   
### <a name="dart-samples"></a>Dart Sample Apps
- [Dart Sample Apps](https://github.com/realm/realm-dart-samples) -  Realm Flutter and Realm Dart SDK Sample Apps.

## <a name="cpp"> C++
- [Realm C++](https://github.com/realm/realm-cpp) - Realm SDK for C++ (prototype)
 
   

