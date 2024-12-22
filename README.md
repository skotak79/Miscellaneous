# Miscellaneous

## Tchibo Capsule Tracker Demo (iOS)
UI: SwiftUI<br>
iOS: 18

☕️ Tracks your Tchibo coffee capsules collection<br>
❤️ Logs estimated caffeine amount to HealthKit

## SF Symbol finder (MacOS)
Finds SF symbols related to the query and similar words

## Lotto Skaner (iOS)

- Scans Lotto tickets and tries to extract relevant data
- Keeps collection of scanned coupons
- Checks the winning numbers

Todo
- [ ] improve the UI

## Kiedy wywóz (iOS)

[www.kiedywywoz.pl](https://www.kiedywywoz.pl)

I tried to more or less copy the home screen, the list of waste collections and the side menu.<br> 
Fun fact - collection dates for the given address are generated programmatically and based on the actual dates.<br>
Obviously the original app can be improved in many ways. Just for the heck of it I added two mapview screens - **Bulky waste** and **'Szops'** - problem waste. JSON files were scrapped of the website.

## Overlays 🗺 ~2018 (iOS)

Slightly modified (for educational purposes) raywenderlich.com's "MapKit Tutorial: Overlay Views" (The first part) <br>
You can load custom overlay image and corresponding JSON file generated by Maptiler app. <br>
I added user's position tracking and slider to change opacity of the overlay. <br>
### Screenshots
<div align="center">
<img src="Images/overlays_01.png" height="400" hspace="20" />
<img src="Images/overlays_02.png" height="400" hspace="20"/>
<img src="Images/overlays_03.png" height="400" hspace="20"/>
</div> 

---

## Remove !!! Poznańskie Cmentarze - wyszukiwarka miejsc pochówku DEMO 🕯<br>

[![codebeat badge](https://codebeat.co/badges/48d3a0b4-b396-4c6e-8148-86ff39f844a4)](https://codebeat.co/projects/github-com-skotak79-poznanskie-cmentarze-master)<br>
[![UIKit badge](https://img.shields.io/badge/Made%20with-UIKit-blue)](https://developer.apple.com/documentation/uikit) <br>
iOS: 13.0 <br>
Architecture pattern: MVVM-C <br>

App's name is pretty self explanatory. My first steps into iOS development, silly demo project from 2018, not updated since then. 
Suspended.

### Screenshots
![Demo](Images/cmentarze.gif)

## LottoScanner 🍀

- UI: SwiftUI
- iOS: 14.5
- Persistence: JSON + serialization in internal storage
- OCR: Google ML Kit's TextRecognizer, BarcodeRecognizer

My attempt to create a prototype of the anticipated iOS Lotto coupon scanner / winnings calculator. 
- Fetches latest lottery drawings results from [Mobilotto](http://serwis.mobilotto.pl/mapi_v6/index.php?json=getGames)
- Allows user to fix misrecognized numbers (Accuracy is pretty high though)

Early version. Currently recognizes Lotto coupon (Lotto, Plus and Super Szansa games).

## Screenshots
[Needs photo]

### Status
Needs massive refactoring. Utilize Core Data, Apple's Vision, ... 
