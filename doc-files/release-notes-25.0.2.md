# Release Notes for JavaFX 25.0.2

## Introduction

The following notes describe important changes and information about this release. In some cases, the descriptions provide links to additional detailed information about an issue or a change.

These notes document the JavaFX 25.0.2 update release. As such, they complement the [JavaFX 25](https://github.com/openjdk/jfx25u/blob/master/doc-files/release-notes-25.md) and [JavaFX 25.0.1](https://github.com/openjdk/jfx25u/blob/master/doc-files/release-notes-25.0.1.md) release notes.

## List of Enhancements

Issue key | Summary | Subcomponent
--------- | ------- | ------------
[JDK-8271024](https://bugs.openjdk.org/browse/JDK-8271024) | Implement macOS Metal Rendering Pipeline | graphics

## List of Fixed Bugs

Issue key | Summary | Subcomponent
--------- | ------- | ------------
[JDK-8367602](https://bugs.openjdk.org/browse/JDK-8367602) | Regression: TabPane with wrapped label calculates wrong initial size | controls
[JDK-8335748](https://bugs.openjdk.org/browse/JDK-8335748) | Rippling of frame on scrolling | graphics
[JDK-8368166](https://bugs.openjdk.org/browse/JDK-8368166) | Media query should accept multiple rules | graphics
[JDK-8368631](https://bugs.openjdk.org/browse/JDK-8368631) | Avoid updating disposed MTLTexture | graphics
[JDK-8368879](https://bugs.openjdk.org/browse/JDK-8368879) | Intermittent crash on exit when disposing MTLRTTextureData | graphics
[JDK-8366217](https://bugs.openjdk.org/browse/JDK-8366217) | Update GStreamer to 1.26.5 | media
[JDK-8371052](https://bugs.openjdk.org/browse/JDK-8371052) | Update libFFI to 3.5.2 | media
[JDK-8361644](https://bugs.openjdk.org/browse/JDK-8361644) | Update ICU4C to 77.1 | web
[JDK-8366744](https://bugs.openjdk.org/browse/JDK-8366744) | Update SQLite to 3.50.4 | web
[JDK-8367578](https://bugs.openjdk.org/browse/JDK-8367578) | Additional WebKit 622.1 fixes from WebKitGTK 2.48.7 | web
[JDK-8368691](https://bugs.openjdk.org/browse/JDK-8368691) | Update libxml2 to 2.14.6 | web
[JDK-8370235](https://bugs.openjdk.org/browse/JDK-8370235) | WebKit build fails on Windows 32-bit and Linux 32-bit after JDK-8367578 | web
[JDK-8370632](https://bugs.openjdk.org/browse/JDK-8370632) | Additional libxslt 1.1.43 fixes | web
[JDK-8252373](https://bugs.openjdk.org/browse/JDK-8252373) | [macOS] Stage with owner disappears when moved to another screen | window-toolkit
[JDK-8350479](https://bugs.openjdk.org/browse/JDK-8350479) | SW pipeline should use default pipeline in Glass | window-toolkit
[JDK-8367370](https://bugs.openjdk.org/browse/JDK-8367370) | Accent color platform preference not updating in macOS 26 (Tahoe) | window-toolkit
[JDK-8368021](https://bugs.openjdk.org/browse/JDK-8368021) | Window buttons of extended RTL stage are on the wrong side | window-toolkit
[JDK-8372453](https://bugs.openjdk.org/browse/JDK-8372453) | [macOS] Iconifying owner may not iconify owned window | window-toolkit


## List of Security fixes

Issue key | Summary | Subcomponent
--------- | ------- | ------------
JDK-nnnnnnn (not public) | TITLE | SUBCOMPONENT
