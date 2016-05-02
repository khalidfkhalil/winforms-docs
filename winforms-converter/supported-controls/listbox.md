---
title: ListBox
page_title: ListBox | UI for Winforms Documentation
description: This article explains which default .NET controls are automatically converted.
slug: winforms/winforms-converter/supported-controls/listbox
tags: covert, winforms, listbox
published: True
position: 1
---

# ListBox

The ListBox is converted to [RadListControl]({%slug winforms/dropdown-listcontrol-and-checkeddropdownlist/listcontrol%}). The following tables describes which properties, methods and events are removed and which are replaced with similar equivalents.

|Properties|Action|RadControls Equivalent|
|---|---|---|
|DrawMode|Removed|   |
|BorderStyle|Removed|   |
|UseTabStops|Removed|   |
|ColumnWidth|Removed|   |
|Sorted|Replaced|SortStyle = SortStyle.Ascending|
|MultiColumn|Removed|   |
|ScrollAlwaysVisible|Removed|   |
|HorizontalExtent|Removed|   |
|HorizontalScrollbar|Removed|   |
|IntegralHeight|Removed|   |

|Methods|Action|RadControls Equivalent|
|---|---|---|
|GetItemHeight()|Produces Error|   |
|GetItemRectangle()|Produces Error|   |
|GetItemText()|Produces Error|   |
|GetSelected()|Produces Error|   |
|ClearSelected()|Produces Error|   |
|SetSelected()|Produces Error|   |
|IndexFromPoint()|Produces Error|   |

|Events|Action|RadControls Equivalent|
|---|---|---|
|DataSourceChanged|Produces Error|   |
|DisplayMemberChanged|Produces Error|   |
|ValueMemberChanged|Produces Error|   |
|DrawItem|Produces Error|   |
|MeasureItem|Produces Error|   |
|Format|Produces Error|   |
|FormatStringChanged|Produces Error|   |
|FormattingEnabledChanged|Produces Error|   |