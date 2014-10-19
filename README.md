CoverPhotoTwitterExample
========================

Example of blurred expanding cover photo like twitter app

The Problem is every popular examples show how to create this feature manually in code. Check my example, fully compatible with autolayout, created in Xcode 6 using Swift.

Important
========================
1. I use UIImage category for blurring written on objC.
2. Look carefully into views hierarhy. If you put image view inside scroll view there will be some scroll bugs.

*FYI This is not the best implementation, becase every scroll picture should be filtered. For your exercise create two pictures: maximum blurred under original and change original image alpha from 1 to 0 when scroll. It works fine at old models and consump less energy.*
