# Pre-work - *Simple Todo*

**Simple Todo ** is an android app that allows building a todo list and basic todo items management functionality including adding new items, editing and deleting an existing item.

Submitted by: **Oleksandr Bihary**

Time spent: **5** hours spent in total

## User Stories

The following **required** functionality is completed:

* [X] User can **successfully add and remove items** from the todo list
* [ ] User can **tap a todo item in the list and bring up an edit screen for the todo item** and then have any changes to the text reflected in the todo list.
* [X] User can **persist todo items** and retrieve them properly on app restart

The following **optional** features are implemented:

* [ ] Persist the todo items [into SQLite](http://guides.codepath.com/android/Persisting-Data-to-the-Device#sqlite) instead of a text file
* [ ] Improve style of the todo items in the list [using a custom adapter](http://guides.codepath.com/android/Using-an-ArrayAdapter-with-ListView)
* [ ] Add support for completion due dates for todo items (and display within listview item)
* [ ] Use a [DialogFragment](http://guides.codepath.com/android/Using-DialogFragment) instead of new Activity for editing items
* [ ] Add support for selecting the priority of each todo item (and display in listview item)
* [ ] Tweak the style improving the UI / UX, play with colors, images or backgrounds

The following **additional** features are implemented:

* [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

Link 1 = [https://imgur.com/a/WhUumhG]

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Project Analysis

As part of your pre-work submission, please reflect on the app and answer the following questions below:

**Question 1:** "What are your reactions to the Android app development platform so far? Compare and contrast Android's approach to layouts and user interfaces in past platforms you've used."

**Answer:** [The Android app development platform is very different from many other platforms I have used before. I like it since it has predictions and recommendations for what we may want to do in the future. So far the whole user interface works well and looks well and I am very excited to learn more in the future about the application.].

**Question 2:** "Take a moment to reflect on the `ArrayAdapter` used in your pre-work. How would you describe an adapter in this context and what is its function in Android? Why do you think the adapter is important? Explain the purpose of the `convertView` in the `getView` method of the `ArrayAdapter`."

**Answer:** [The ArrayAdapter has two parts, the array itself which helped us store our list of todo items. The second part of the ArrayAdapter is the adapter itself and it helps us with data collection as it is used to manage the items in our list. The ArrayAdapter can handle lists or arrays in Java and it will place the input in a new line everytime. The purpose of the convertView and getView is that they are implemented as the list is being scrolled and any string that isn't visible (as it has been scrolled to far of the screen) gets sent by the Adapter as an old view and it isn't used anymore by the convertView.].

## Notes

Describe any challenges encountered while building the app.

[The emulator took quite a while to load, I will solve this problem by using an old phone. Also, I set a dark theme for the app but it failed to display in the gif capture. ]

## License

    Copyright [2018] [Oleksandr Bihary]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

