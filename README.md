# Cantabile Bug Reports

This is the place to report **bugs** in [Cantabile](https://www.cantabilesoftware.com).

It's **only for bug reports**: things in Cantabile that don't work the way they should. Please don't use it for
questions, help with your setup, or feature requests (see [Not a bug?](#not-a-bug) below for where those go).

**[Report a bug](https://github.com/toptensoftware/cantabile-issues/issues/new/choose)**

## Not a bug?

| If you have... | Please go to... |
|---|---|
| A question, or need help setting something up | The [Community forum](https://community.cantabilesoftware.com), or email [contact@cantabilesoftware.com](mailto:contact@cantabilesoftware.com) |
| A feature request or suggestion | Email [contact@cantabilesoftware.com](mailto:contact@cantabilesoftware.com) or post on the [forum](https://community.cantabilesoftware.com). You can check and vote on existing requests on [Trello](https://www.cantabilesoftware.com/trello) |
| A licensing, account or purchase question | The [contact page](https://www.cantabilesoftware.com/contact) or [contact@cantabilesoftware.com](mailto:contact@cantabilesoftware.com) |
| A security problem | Please **don't** post it here. Email [contact@cantabilesoftware.com](mailto:contact@cantabilesoftware.com) instead (see [SECURITY.md](SECURITY.md)) |

## You'll need a GitHub account

To report a bug here, and to be notified when there's progress on it, you need a free GitHub account. If you don't
have one, you can [sign up here](https://github.com/signup).

If you'd rather not create an account, you can email your report to
[contact@cantabilesoftware.com](mailto:contact@cantabilesoftware.com) with the same details as below. That's
fine, but we can't track progress on emailed reports for you here.

## Before you report

- **Update to the latest build** and check the [release notes](https://www.cantabilesoftware.com/support/releaseNotes4400):
  it may already be fixed.
- **Search the existing issues**, both [open and closed](https://github.com/toptensoftware/cantabile-issues/issues?q=is%3Aissue).
  If you find your bug, add a comment there rather than opening a new issue.
- **One bug per issue**, please.
- **Not sure it's a bug?** Ask on the [forum](https://community.cantabilesoftware.com) first.

## What to include

The bug report form asks for these. The more of them you can give us, the faster we can find and fix the problem.

| What | Where to find it |
|---|---|
| **Build number** and **edition** (Lite, Solo or Performer) | **Help → About...** shows e.g. *Cantabile Performer* and *Version 4.0 Build 4400*. The build number is the important part. It's also on the first line of `log.txt` |
| **Windows version** | Windows **Settings → System → About** (or type `winver` in the Start menu) |
| **Audio driver and device** | **Tools → Options → Audio Engine**, e.g. *ASIO - Focusrite USB ASIO* or *WASAPI Out - Speakers* |
| **Steps to reproduce** | What you did, step by step, so we can make it happen too |
| **What you expected, and what actually happened** | Error messages, sounds, what you saw on screen |
| **Plugins involved** | Name, maker and version, if the problem involves a plugin |
| **Log files** | `log.txt` and `log-previous.txt`, in the folder opened by **Tools → Open Settings Folder** |
| **Song, rack or set list files** | Use **File → Save Copy As...**, and zip the song together with any racks it uses |
| **Screenshots or a short video** | **Win+Shift+S** for a screenshot; the Snipping Tool or the Xbox Game Bar (**Win+G**) can record video |

You can drag files straight into the form. GitHub's size limits are 25 MB for zip and text files, 10 MB for
images and 100 MB for videos. Please don't attach plugins, sample libraries or copyrighted audio.

### Your files are public

Everything you post here, **including attached files, is public** and can't easily be removed later.

Log files, `settings.json`, `plugins.json` and song files can contain your Windows user name, file paths, the
names of your devices and plugins, and your name. Open files in Notepad and check them before you attach them.
If you'd rather keep a file private, email it to
[contact@cantabilesoftware.com](mailto:contact@cantabilesoftware.com) and mention that in the issue.

**Never post your licence key.**

## Crashes

You usually **don't need to report a crash here**. When Cantabile crashes it shows a crash report window: add a
short description and your email address, then press **Send**. The report reaches us automatically, and we'll
contact you if we need more information and when a fix is available.

If you can make the crash happen again, a bug report is still very welcome: include the steps, and roughly when
the crash happened so we can match it to the crash report.

Crashes while scanning plugins are saved as `ScanServer-*.mdmp` files in the settings folder, but aren't sent
automatically. Please only attach them if we ask.

## Hangs and freezes

If Cantabile stops responding, the [Diagnostics and Troubleshooting](https://www.cantabilesoftware.com/support/debug)
page explains how to capture the information we need.

## What happens next

- We'll look at your report and label it.
- We may ask you for more information. Issues that are still waiting for an answer after **4 weeks** will be
  closed (you can always reopen them or comment later).
- When a bug is fixed, we'll say which build has the fix and close the issue. Fixes are also listed in the
  [release notes](https://www.cantabilesoftware.com/support/releaseNotes4400).

Please be kind and patient: everyone here is trying to make Cantabile better. English is preferred, but machine
translation is fine.

## Useful links

- [Community forum](https://community.cantabilesoftware.com)
- [User guides](https://www.cantabilesoftware.com/guides)
- [Diagnostics and Troubleshooting](https://www.cantabilesoftware.com/support/debug)
- [Release notes](https://www.cantabilesoftware.com/support/releaseNotes4400)
- [Contact Us](https://www.cantabilesoftware.com/contact)
- [Feature requests on Trello](https://www.cantabilesoftware.com/trello)
- [Privacy policy](https://www.cantabilesoftware.com/privacy)
