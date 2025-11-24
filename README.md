# Jyothi-Krishna-yadav-
Joho app
plugins {
    id 'com.android.application'
    id 'kotlin-android'
    id 'com.google.gms.google-services' // for Firebase
}

android {
    namespace "com.example.joho"
    compileSdk 34
    defaultConfig {
        applicationId "com.example.joho"
        minSdk 21
        targetSdk 34
        versionCode 1
        versionName "1.0"
    }
    ...
}

dependencies {
    implementation "org.jetbrains.kotlin:kotlin-stdlib:1.9.0"
    implementation 'androidx.core:core-ktx:1.10.1'
    implementation 'com.google.android.material:material:1.9.0'
    implementation 'androidx.appcompat:appcompat:1.6.1'
    implementation 'androidx.constraintlayout:constraintlayout:2.1.4'
    implementation 'androidx.recyclerview:recyclerview:1.3.0'
    implementation 'com.google.firebase:firebase-auth-ktx:22.0.0'
    implementation 'com.google.firebase:firebase-firestore-ktx:24.7.0'
    implementation 'com.google.firebase:firebase-storage-ktx:20.1.0'
    implementation 'com.google.firebase:firebase-messaging:23.1.1'
    implementation 'com.google.firebase:firebase-analytics-ktx:21.1.0'
    implementation 'com.squareup.picasso:picasso:2.8' // load images
    // optionally lifecycle & coroutines:
    implementation 'androidx.lifecycle:lifecycle-runtime-ktx:2.6.1'
    implementation 'org.jetbrains.kotlinx:kotlinx-coroutines-android:1.7.3'
}
apply plugin: 'com.google.gms.google-services'
