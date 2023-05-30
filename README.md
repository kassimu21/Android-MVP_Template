README MVP
Android MVP Architecture: Sample App
This repository contains a detailed sample app that implements MVP architecture using Dagger2, GreenDao, RxJava, FastAndroidNetworking, PlaceHolderView and AndroidDebugDatabase

  


   



Architecture Blueprint
Blueprint

Project Structure
Structure

Read the below listed articles. They describe the MVP concepts and the Project structure.
MVP: Part 1
MVP: Part 2
MVP: Part 3
Extension with Interactors and Repositories
The app has following packages:
data: It contains all the data accessing and manipulating components.
di: Dependency providing classes using Dagger2.
ui: View classes along with their corresponding Presenters.
service: Services for the application.
utils: Utility classes.
Classes have been designed in such a way that it could be inherited and maximize the code reuse.
Library reference resources:
Dagger2: https://github.com/kassimu21/android-dagger2-example
PlaceHolderView: https://github.com/kassimu21/PlaceHolderView
Calligraphy: https://github.com/chrisjenx/Calligraphy
GreenDao: http://greenrobot.org/greendao/
ButterKnife: http://jakewharton.github.io/butterknife/
Concept reference resources:
Introduction to Dagger 2: Part 1
Introduction to Dagger 2: Part 2
Android Dagger2: Critical things to know before you implement
Android Tinder Swipe View Example
RxJava Anatomy: What is RxJava, how RxJava is designed, and how RxJava works.
Powerful Android ORM: greenDAO 3 Tutorial
Looking for MVVM Architecture - Check here
Looking for Kotlin MVP Architecture - Check here
How do I use this project?
This is a boilerplate project aimed to help bootstrap new Android MVP Applications. Feel free to fork this application or use AndroidStarters to create new app using this boilerplate.

MVP template
When we follow any architecture pattern like MVP, MVVM, MVP clean, we always come across a small but repetitive task to create basic files like Android Activity, Presenter, View, Api models and then writing boiler plate code. This usually takes 1-2 hours for each single screen. To ease out work and save time We have created an automated template which will do above work in less than 20 seconds.

How to Install
Find the template/MVPActivity folder under root directory of android-mvp-architecture app. Paste the MVPActivity folder at below location.

Windows - C:\Program Files\Android\Android Studio\plugins\android\lib\templates\activities
Mac - /Applications/Android/Studio.app/Contents/plugins/android/lib/templates/activities
Restart the Android Studio.

Blueprint

How to use
Select the folder under which you want to create a new MVP folder. This MVP folder will contain Activity, Presenter, MVpPresenter and View class. For example, to create a new MVP folder under “view” folder, do as shown below.

Blueprint

License
   Copyright (C) 2023 KASIMU SAMAILA

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
Contributing to Android MVP Architecture
All pull requests are welcome, make sure to follow the contribution guidelines when you submit pull request.
