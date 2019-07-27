<p align="center">AndroCat is a GitHub client for Android phones like how you used to</p>
<p align="center"><a href="https://play.google.com/store/apps/details?id=mustafaozhan.github.com.androcat"><img src="https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png" width="300px"></a></p>
<p align="center"><a href='https://ko-fi.com/B0B2TZMH' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://az743702.vo.msecnd.net/cdn/kofi1.png?v=2' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a></p>
<p align="center">Important! The old version has been removed from the Google Play Store. Download the updated AndroCat from the store icon above to get the lastest updates.</p>

## Screenshots

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/9d1a9f2296d543de941250c5596c3bdf)](https://app.codacy.com/app/mr.mustafa.ozhan/AndroCat?utm_source=github.com&utm_medium=referral&utm_content=mustafaozhan/AndroCat&utm_campaign=Badge_Grade_Dashboard)

<img src="https://i.postimg.cc/WsScMB5v/1.png?dl=1" width="420px"/> <img src="https://i.postimg.cc/Vmq8NrM5/2.png?dl=1" width="420px"/>

<img src="https://i.postimg.cc/dsZMcLws/3.png?dl=1" width="420px"/> <img src="https://i.postimg.cc/pWwwWRLD/4.png?dl=1" width="420px"/>

<img src="https://i.postimg.cc/r8mXgfHt/5.png?dl=1" width="420px"/> <img src="https://i.postimg.cc/RMDrYcrp/6.png?dl=1" width="420px"/>

<img src="https://i.postimg.cc/rqqLRVCj/7.png?dl=1" width="420px"/> <img src="https://i.postimg.cc/RMZGT58c/8.png?dl=1" width="420px"/>

## Dependencies
```
dependencies {
    implementation fileTree(include: ['*.jar'], dir: 'libs')
    implementation "org.jetbrains.kotlin:kotlin-stdlib-jdk8:$kotlin_version"
    implementation 'com.google.android.material:material:1.0.0'
    implementation 'androidx.constraintlayout:constraintlayout:1.1.3'

    testImplementation 'junit:junit:4.12'
    androidTestImplementation 'androidx.test:runner:1.2.0'
    androidTestImplementation 'androidx.test.espresso:espresso-core:3.2.0'

    // Dagger
    kapt "com.google.dagger:dagger-compiler:${rootProject.ext.daggerVersion}"
    implementation "com.google.dagger:dagger:${rootProject.ext.daggerVersion}"

    // Crashlytics
    implementation 'com.crashlytics.sdk.android:crashlytics:2.10.1'

    // Fabric
    implementation('com.crashlytics.sdk.android:crashlytics:2.10.0@aar') {
        transitive = true
    }

    // Anko
    implementation 'org.jetbrains.anko:anko-commons:0.10.8'

    // Retrofit
    implementation "com.google.code.gson:gson:${gsonVersion}"
    implementation "com.squareup.retrofit2:retrofit:${rootProject.ext.retrofitVersion}"
    implementation "com.squareup.retrofit2:converter-gson:${rootProject.ext.retrofitVersion}"
    implementation 'com.squareup.retrofit2:adapter-rxjava2:2.4.0'

    // Rx
    implementation "io.reactivex.rxjava2:rxkotlin:2.2.0"
    implementation "com.jakewharton.rxbinding2:rxbinding-kotlin:${rootProject.ext.rxBindingVersion}"

    // LiveData
    implementation 'androidx.lifecycle:lifecycle-extensions:2.0.0'

    // Ad
    implementation 'com.google.firebase:firebase-ads:18.0.0'

    // Firebase
    implementation 'com.google.firebase:firebase-core:17.0.0'
    implementation 'com.google.firebase:firebase-config:18.0.0'

    // Advanced WebView
    implementation 'com.github.delight-im:Android-AdvancedWebView:v3.0.0'

    // Quick Action
    implementation 'com.github.mustafaozhan:quickaction:3.0.2'

    // Bottom Navigation
    implementation 'com.github.ittianyu:BottomNavigationViewEx:2.0.4'

    // Snacky
    implementation 'com.github.matecode:Snacky:1.0.3'

    // Multidex
    implementation 'androidx.multidex:multidex:2.0.1'

    // Http client
    implementation "com.squareup.okhttp3:okhttp:${rootProject.ext.okHttpVersion}"

    // Android Fillable Loader
    implementation 'com.github.jorgecastilloprz:fillableloaders:1.03@aar'
}
```

### License
Copyright 2018 Mustafa Ozhan

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

<http://www.apache.org/licenses/LICENSE-2.0>

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
