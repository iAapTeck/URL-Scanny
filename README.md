# URL-Scanny-Technolgy-Master

URL Scanny is a recognition technology that enables us to recognize any type of URL String, Link text and Massive literal URL from various types of documents such as printed paper, any other printed images booklet manual, newspaper, any specific link from product wrapper, etc. and makes it as linkify URL which is auto searchable result [browsers] or automatic redirect from app[May correspond/specific app].

An experimental app for Android that performs optical character recognition (OCR) on images captured using the device camera.

Runs the Two Tesseract OCR engine using [twoTesseactOCR]. a fork of Tesseract Tools for Android.

Most of the code making up the core structure of this project has been adapted from the ZXing Barcode Scanner. Along with Tesseract-OCR and Tesseract Tools for Android (tesseract-android-tools), several open source projects have been used in this project, including leptonica, google-api-translate-java, microsoft-translator-java-api, and jtar.


## Requires

* A Windows Azure Marketplace Client ID and Client Secret (for translation) - [Documentation](http://msdn.microsoft.com/en-us/library/hh454950.aspx)
* A Google Translate API key (for translation) - [Documentation](https://code.google.com/apis/console/?api=translate)
* A RegexUri Algorithm for url recognition

## Training data for OCR
## Training url [Regular Expression Format]

A data file is required for english language you want to recognize url. For English, this data file is included in the application assets and is automatically installed when the app is first run.


## Installation

To build and run the app, clone this project, open it as an existing project in Android Studio, and click Run.

## License

This project is licensed under the [MIT License, Version 2.0]

    /*
     * Copyright 2018 iAapTeck Sotfware Labs
	 * Author: Sanjay Patel
     *
     * Licensed under the MIT License, Version 2.0 (the "License");
     * you may not use this file except in compliance with the License.
     * You may obtain a copy of the License at
     *
     *      https://rem.mit-license.org/%20licensc
     *
     * Unless required by applicable law or agreed to in writing, software
     * distributed under the License is distributed on an "AS IS" BASIS,
     * WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
     * See the License for the specific language governing permissions and
     * limitations under the License.
     */

One of the jar files in the android/libs directory (google-api-translate-java-0.98-mod2.jar) is licensed under the [GNU Lesser GPL](http://www.gnu.org/licenses/lgpl.html).
