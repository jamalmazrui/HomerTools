---
title: "Homer Tools"
subtitle: "Free, Open Source Windows Apps for Keyboard and Screen Reader Users"
author: "Jamal Mazrui"
version: "v1.0.0"
lang: en
---

# Homer Tools

## Introduction

Homer Tools is a family of free, open source apps for Windows, written by a
blind developer for people who work by keyboard and screen reader. The Homer
name has run through this author's software for years, from the Homer editor
interface and HomerKit to the tools below.

The apps do different jobs but are built the same way. What they share:

- **64-bit Windows programs**, written in C# or Python, with full source code
  public on GitHub.
- **Two ways to work.** Most run either as a dialog with labeled fields or
  from the command line. Every dialog control has a matching command-line
  option with the same name and access letter, and shared options are named
  the same way across apps, so a task done by hand can be repeated in a
  script or scheduled task.
- **One simple installer each**, the same short wizard every time, with a
  direct download link on this page. Each adds a Start menu entry and a
  desktop shortcut with a hotkey.
- **Speech you can count on.** They speak through JAWS and NVDA directly, and
  raise a standard Windows notification for Narrator and others, so you hear
  the result of a command instead of going looking for it.
- **Local work.** Each app does its job on your own computer, not on someone
  else's server.
- **Free to use and change.** Most are MIT-licensed; EdSharp and FileDir, the
  two oldest, use GNU licenses.

Each app also ships the same set of documents, in HTML as well as Markdown:

- **ReadMe** — a short introduction and quick start.
- **Announce** — what is new in the current release.
- **The app's own guide**, named after the app — the full user guide.
- **Developer** — how the program is built, for anyone changing the code.
- **History** — the record of changes across versions.
- **Hotkeys** — every keystroke in one list.

The apps are listed below in alphabetical order, each with a short summary
and links to its project page and installer.

## 2htm

2htm converts Word, Excel, and PowerPoint files to clean HTML, using
Microsoft's own APIs, with options for plain text and for stripping images.
Most free converters copy how a document looks on paper, while 2htm keeps
what matters to a screen reader: headings, lists, tables, and reading order.
The result opens in any browser or editor, so you can move through a long
document by heading.

- Project page: <https://github.com/JamalMazrui/2htm>
- Executable installer: <https://github.com/JamalMazrui/2htm/releases/latest/download/2htm_setup.exe>

## bookFido

bookFido builds one catalog of the books you own or have borrowed across five
libraries: Audible, Bookshare, Goodreads, Kindle, and NLS BARD. No free
website does this, because each library knows only its own books, so bookFido
reads all five the way you would, through your own signed-in copy of
Microsoft Edge. You get a searchable catalog, a spreadsheet, and a database,
with a book counted once even when three libraries have it, and nothing about
your accounts leaves your computer.

- Project page: <https://github.com/JamalMazrui/bookFido>
- Executable installer: <https://github.com/JamalMazrui/bookFido/releases/latest/download/bookFido_setup.exe>

## DbDo

DbDo manages databases from the keyboard, opening SQLite, Access, Excel,
dBASE, and delimited text in their native formats. It offers two ways to work
on the same open database at once: ordinary Windows lists you move through
cell by cell, and a dot prompt for typing commands and SQL. Other database
programs assume you can take in a grid at a glance, while DbDo announces
where you are, so you can query, edit, relate, and report without a mouse.

- Project page: <https://github.com/JamalMazrui/DbDo>
- Executable installer: <https://github.com/JamalMazrui/DbDo/releases/latest/download/DbDo_setup.exe>

## EdSharp

EdSharp is a full featured editor for text and program code, in use since
2007. Ordinary editors can be made to work with a screen reader, but EdSharp
speaks the result of a command on its own, so you get confirmation without
stopping to inspect the screen. It also handles snippets, structured text,
word processing, math, programming, and its own scripting add-ins.

- Project page: <https://github.com/JamalMazrui/EdSharp>
- Executable installer: <https://github.com/JamalMazrui/EdSharp/releases/latest/download/EdSharp_setup.exe>

## extCheck

extCheck checks Word, Excel, PowerPoint, and Markdown files for accessibility
problems, choosing rules from the file extension and writing a report of what
it found. Its rules come from the Microsoft Office Accessibility Checker and
the Web Content Accessibility Guidelines, and the set can be extended. Free
checkers are usually built into Office, one file at a time, while extCheck
can take a whole folder, so you find missing headings, missing picture
descriptions, and unlabeled tables before you send a document out.

- Project page: <https://github.com/JamalMazrui/extCheck>
- Executable installer: <https://github.com/JamalMazrui/extCheck/releases/latest/download/extCheck_setup.exe>

## FileDir

FileDir manages files and folders by typed command rather than by mouse, and
has done so since 2006. Its commands are grouped by what they do: finding,
going to, navigating, querying, tagging, and transferring. Routine file work
takes fewer keystrokes, and the program tells you what happened rather than
leaving you to check.

- Project page: <https://github.com/JamalMazrui/FileDir>
- Executable installer: <https://github.com/JamalMazrui/FileDir/releases/latest/download/FileDir_setup.exe>

## HomerScribe

HomerScribe describes what happens on screen in a video and writes out what
is said in it, returning a new copy of the film with description mixed into
its sound, a timed script of every description, and a transcript. Companies
that do this charge by the minute and want your video uploaded, while
HomerScribe runs the AI models on your own machine and makes no network
request at all once installed. Professional description is still better, but
most recordings have none, and those are the ones this is for.

- Project page: <https://github.com/JamalMazrui/HomerScribe>
- Executable installer: <https://github.com/JamalMazrui/HomerScribe/releases/latest/download/HomerScribe_setup.exe>

## HomerView

Blind people read the web through a flat copy of the page that the screen
reader builds, and the browser has always known more than that copy shows.
HomerView is an add-on for NVDA that steers its own copy of Microsoft Edge
and asks the browser directly, so you can count the headings, links, and form
fields, check the page for accessibility problems, see where a link really
goes before following it, and pull the main article out of the menus and
advertisements around it. No artificial intelligence is involved, and no page
you read leaves your computer.

- Project page: <https://github.com/JamalMazrui/HomerView>
- Executable installer: <https://github.com/JamalMazrui/HomerView/releases/latest/download/HomerView_setup.exe>

## urlCheck

urlCheck opens web pages in Microsoft Edge and runs the axe-core testing
engine on each one, producing a report per page plus a draft Accessibility
Conformance Report covering all 86 WCAG 2.2 success criteria, with a
companion sheet of manual tests. Free checkers on the web test one page at a
time through a form and keep the results on their servers, while urlCheck
works through a whole list on its own and leaves every file on your disk.
Because the reports are ordinary files, you can send them to a developer and
compare them later to see whether a site is improving.

- Project page: <https://github.com/JamalMazrui/urlCheck>
- Executable installer: <https://github.com/JamalMazrui/urlCheck/releases/latest/download/urlCheck_setup.exe>

## urlFido

urlFido downloads files of the kinds you choose from a web page, so a page
offering forty PDF files becomes one command instead of forty trips through a
link list. Ordinary downloaders visit a page as a stranger, while urlFido
drives your own copy of Microsoft Edge, so scripts run, sign-ins apply, and
files a server will release only to a real click still arrive. A Test fetch
button reports what a run would bring back before it brings anything.

- Project page: <https://github.com/JamalMazrui/urlFido>
- Executable installer: <https://github.com/JamalMazrui/urlFido/releases/latest/download/urlFido_setup.exe>
