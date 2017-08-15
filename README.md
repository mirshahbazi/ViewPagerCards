# ViewPagerCards
ViewPager cards inspired by Duolingo

## Using with gradle
- Add the JitPack repository to your root build.gradle:
```gradle
repositories {
    maven { url "https://jitpack.io" }
}
```

- Add the dependency to your sub build.gradle:
```gradle
dependencies {
   compile 'com.github.mirshahbazi:ViewPagerCards:-SNAPSHOT'
}
```

This is just a sample project.

There's support included for Fragments and normal Views. Check the CardPagerAdapter and CardFragmentPagerAdapter classes.

**Left** - Duolingo implementation

**Right** - This sample

<img src="https://rubensousa.github.io/img/duolingo_viewpager.gif" width=300></img> <img src="https://rubensousa.github.io/img/viewpager_result.gif" width=300></img>


**What you could do with this:**

1. Showcasing premium features
2. An app intro
2. A small gallery of images


## License

    Copyright 2016 Rúben Sousa
    
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
    
        http://www.apache.org/licenses/LICENSE-2.0
    
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
