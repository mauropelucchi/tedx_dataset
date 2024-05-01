# TED Talks
TEDx Dataset contains information about 6,300k audio-video recordings of TED Talks uploaded to the official TED.com website (update to 2024/05/01).
The dataset is obtained with a scraper based on Selenium Web Driver\APIs for accademic and teaching purpose.
The data and the scraper has been scraped from the official TED Website and is available under the MIT license.

# Structure
The dataset is composed by 5 CSV files:
- final_list it the TED Talks main table
- related_videos contains the watch next videos for each talk
- tags contains the topics\tags for each talk
- images contains the image url for each talk
- details contains the attribute (speaker, duration, description, ...)

*final_list* contains the main informaion about talks including an unique id, slug, the title, the main speaker and the url.

*details* contains the detailed informaion about talks including an unique id, the description, th speaker, the number of views, the duration, ..

*related_videos* contains the releated talks.

*tags* contains, for each TEDx talk, the list of the assosiate talk.

*images* contains, for each TEDx talk, the image url.


# MIT License

Copyright (c) 2024 Mauro Pelucchi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
