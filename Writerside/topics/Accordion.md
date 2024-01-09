# Accordion

## Overview

## Fields

### Primary Settings

![accordion-tab-primary-settings](accordion-tab-primary-settings.png)

#### Intro Headline

{type="wide"}
Widget
:   Text field

Required
:  No

#### Expand/Collapse All

{type="wide"}
Widget
:   Dropdown

Options
:  Hide, Show

Default
:  Hide

### Accordion Items

![](accordion-tab-accordion-items.png)

#### Accordion Items {id="accordion-items_1"}

{type="wide"}
Widget
:   Flexible Content

Minimum
:  1

Maximum
:  none

Layouts
: Simple Accordion Item

### Intro Heading Settings

![](accordion-tab-intro-heading-settings.png)

#### Heading Level

If an intro heading level is provided, this setting determines the HTML heading level to
use for the headline's tag.

{type="wide"}
Widget
:   Dropdown

Options
:  h1, h2, h3, h4, h5, h6

Default
:  h2

#### Include in Document Outline

This setting determines that HTML tag that is used if an intro heading is provided. If set
to "No", a `<div>` tag will be used along with a class of `h1` through `h6` depending on
the heading level selected above. If set to "Yes", the appropriate heading tag will be
used. See [Headings](Headings.md) for more details.

{type="wide"}
Widget
:   Dropdown

Options
:  Yes, No

Default
:  Yes

### Component Settings

![shared-tab-component-settings.png](shared-tab-component-settings.png)

#### Row ID

This is the common Row ID that is shared across all components and some sub-components.
It is intended to be used by content authors to link to a specific component on a page.

{type="wide"}
Widget
:   Text field

Required
:  No

## Component Notes

* Clicking the “collapse all” button will have no effect on accordion items marked as
  “always open”.

## Accessibility

The accordion component uses the HTML5 `<details>` and `<summary>` elements to provide the
accordion functionality. As these are browser-native elements, they should be fairly
accessible by default.