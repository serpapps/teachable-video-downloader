# Teachable Video Downloader (Browser Extension) | How to Download Teachable Videos

> Browser extension that downloads Teachable lesson videos as MP4 files, one lesson at a time or several lessons from the course panel, for courses your account can already watch.

Teachable Video Downloader is a browser extension for saving the course videos you are enrolled in on Teachable schools. Open a lesson, click the extension and save the lesson as an MP4 file named after the lesson, so you can study offline, on a plane or anywhere with a weak connection.

- Download Teachable lesson videos as MP4 from the lesson page you have open
- Pick from the qualities Teachable's player offers for that lesson
- Use the course panel to select several lessons and save them in course order
- Save PDFs and other files attached to the open lesson
- Works on `*.teachable.com` schools; schools on their own domain can be allowed with one click

## Links

- :rocket: Get it here: [Teachable Video Downloader](https://serp.ly/teachable-video-downloader?via=github)
- :new: Latest release: [GitHub Releases](https://github.com/serpapps/teachable-video-downloader/releases/latest)
- :question: Help center: [SERP Help](https://help.serp.co/en/)
- :beetle: Report bugs: [GitHub Issues](https://github.com/serpapps/teachable-video-downloader/issues)
- :bulb: Request features: [Feature Requests](https://github.com/serpapps/teachable-video-downloader/issues)

## Why Teachable Video Downloader

Teachable lessons play through a streaming player, so there is no right-click "Save video" and
pasting the lesson link into a download website usually fails: Teachable's video host refuses requests
that do not come from its own player. Most people also do not want to use command-line tools such as
yt-dlp just to keep a copy of a course they paid for.

Teachable Video Downloader works inside your open Teachable tab with your own signed-in session. It
requests the video the way the player does, joins the streamed pieces into one MP4 and saves it to
your computer. No desktop software, no terminal.

## Features

- **Lesson video download**: finds the lesson video in Teachable's player (Hotmart player and legacy Wistia embeds) and saves it as MP4
- **Quality selection**: shows the qualities the player offers for that lesson
- **Course panel**: reads the course lesson list grouped by section, marks video, text and quiz lessons, and lets you select several lessons (or every lesson you can open) and save them in one run
- **Course-order filenames**: course-panel files are numbered by section and lesson so they sort in order
- **Locked lessons skipped**: lessons your account cannot open yet are marked and skipped instead of producing broken files
- **Lesson attachments**: lists PDFs and other files attached to the open lesson so you can save them too
- **Free-preview lessons**: preview lessons can be saved without signing in to Teachable
- **Custom-domain schools**: on a school with its own web address, click *Allow on this site* once
- **Private by design**: downloads run in your browser; your course files never pass through our servers

## Supported Browsers

| Browser | Supported |
|---|---|
| Google Chrome | ✅ |
| Microsoft Edge | ✅ |
| Brave | ✅ |
| Opera | ✅ |
| Naver Whale | ✅ |
| Yandex Browser | ✅ |
| Firefox, Safari, mobile browsers | ❌ Not supported |

Works on Windows, macOS and Linux desktops. Every release ships one ZIP per browser
(for example `teachable-video-downloader-chrome.zip`).

## How to Download Teachable Videos (Step-by-Step)

1. Install the extension (see [Installation Instructions](#installation-instructions)) and sign in with your email.
2. Sign in to the Teachable school and open a lesson from a course you are enrolled in.
3. Click the extension icon. It shows the lesson title and the qualities the player offers.
4. Choose a quality and click **Download Video**. Keep the tab open until the file is saved.
5. To save several lessons, right-click the toolbar icon, choose **Open course downloader**, select lessons (or **Select all**) and click **Download selected**.

**Tip:** files are saved in a `Teachable` folder inside your browser's Downloads folder.

## Supported Formats

- **Output:** MP4 (plays on any device or media player)
- **Sources:** Teachable's lesson player (Hotmart player) and legacy Wistia embeds
- **Attachments:** files attached to a lesson (for example PDFs) are saved in their original format
- **Not saved:** text lessons, quizzes and captions

## Who It's For

- **Students** who want offline copies of the Teachable courses they are enrolled in
- **Commuters and travellers** who study without a reliable connection
- **Course creators** who want a local backup of lessons on their own school

## Troubleshooting

**The extension does not find the video**  
Let the lesson page load fully and press play once, then click the extension again. Refresh the page if needed.

**A lesson is marked locked or skipped**  
The lesson is not open to your account yet: you are not enrolled, it is a paid lesson, or the school releases it on a later date.

**The school uses its own domain**  
Open the course panel and click **Allow on this site**, then reload the page.

## Free Trial & Pricing

You get **3 free downloads a week** with no credit card. A **subscription** gives unlimited downloads, with updates included.

- Sign in with your email and a one-time code; no password to create.
- Your free downloads reset every week. In current versions only finished downloads count; a failed or cancelled download does not use one.
- See current plans on the [product page](https://serp.ly/teachable-video-downloader?via=github).

## Installation Instructions

1. Download the ZIP for your browser from the [latest release](https://github.com/serpapps/teachable-video-downloader/releases/latest) (for example `teachable-video-downloader-chrome.zip`).
2. Unzip it. You get a folder that contains `manifest.json`.
3. Open your browser's extensions page: `chrome://extensions` (Chrome), `edge://extensions` (Edge), `brave://extensions` (Brave), `opera://extensions` (Opera), `whale://extensions` (Whale) or `browser://extensions` (Yandex).
4. Turn on **Developer mode**.
5. Click **Load unpacked** and select the unzipped folder.
6. Pin the extension, click its icon, and sign in with your email and the one-time code we send you.

Prefer a guided setup? The [product page](https://serp.ly/teachable-video-downloader?via=github) walks you through the same steps.
When a newer version is published, the extension shows an update notice; download the new ZIP from
[GitHub Releases](https://github.com/serpapps/teachable-video-downloader/releases/latest) and load it the same way.

## FAQ

### How do I download a Teachable video?

Install the extension and open the lesson on Teachable. Click the extension icon; it shows the lesson title and the quality the player offers. Click **Download Video** and keep the tab open until the file is saved.

### Is there a Teachable video downloader that works in Chrome?

Yes. This extension runs in Chrome, Edge, Brave, Opera, Whale and Yandex on Windows, macOS and Linux. Firefox, Safari and mobile browsers are not supported.

### Can I download a whole Teachable course?

The extension includes a course panel for this: right-click the toolbar icon, choose **Open course downloader**, click **Select all**, then **Download selected**. It saves the lessons you can open, one after another. On a large course, check the first few files before leaving it to run.

### Do I need to be signed in or enrolled?

Not for free-preview lessons. For other lessons, sign in to Teachable and enroll first. The extension only saves lessons your account can already watch.

### Why won't a generic video downloader work on Teachable?

Teachable's video host refuses requests that do not come from its own player, so a link pasted into a download website usually fails. The extension works inside your open Teachable tab and requests the video the way the player does.

### What video quality do I get?

The qualities Teachable's player offers for that lesson. The extension does not create higher quality than the player serves.

### Does it work on Teachable schools with their own domain?

On a school that uses its own web address, open the course panel and click **Allow on this site**, then reload the page.

### Can it save PDFs and other lesson files?

The course panel lists files attached to the lesson you have open, such as PDFs, and saves the ones you click.

### What about DRM?

Most Teachable lessons use ordinary streaming that the extension can save. If a creator turns on DRM for a video, the extension tells you and skips it.

### Where are my files saved?

In a `Teachable` folder inside your browser's Downloads folder. A single lesson is named after the lesson title; course-panel files are numbered by section and lesson.

### Is there a free trial?

Yes. You get **3 free downloads a week** with no credit card. A **subscription** gives unlimited downloads, with updates included.

## Notes

- Only download content you own or have permission to save.
- The extension saves lessons your account can already watch. It does not unlock paid or locked lessons.
- Do not share or resell downloaded lessons without the creator's permission.
- Teachable updates can affect detection. If something stops working, [open an issue](https://github.com/serpapps/teachable-video-downloader/issues).

## License

This repository is distributed under the proprietary SERP Apps license in the [LICENSE](LICENSE) file. Review that file before copying, modifying, or redistributing any part of this project.

## Related

- [Kajabi Video Downloader](https://github.com/serpapps/kajabi-video-downloader)
- [Thinkific Video Downloader](https://github.com/serpapps/thinkific-downloader)
- [Skool Video Downloader](https://github.com/serpapps/skool-downloader)
- [Circle Downloader](https://github.com/serpapps/circle-downloader)
- [Vimeo Video Downloader](https://github.com/serpapps/vimeo-video-downloader)

## About Teachable

Teachable is an online course platform that lets creators run their own school, with courses,
coaching and digital downloads, either on a `teachable.com` address or on their own domain. Students
watch lessons in the browser or the Teachable app, but the web player does not offer a download
button. Teachable Video Downloader adds that for lessons you have access to.
