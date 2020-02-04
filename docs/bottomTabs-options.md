---
id: bottomTabs-options
title: Bottom Tabs Options
sidebar_label: Bottom Tabs
---

```
const options = {
  bottomTabs: {

  }
}
```

## animate
Controls wether toggling visibility states will be animated.

| Type    | Required | Platform |
| ------- | -------- | -------- |
| boolean | No       | Both     |

## backgroundColor
Change the background color.

| Type  | Required | Platform |
| ----- | -------- | -------- |
| color | No       | Both     |

## barStyle
Controls wether the BottomTabs use dark (black) or light (default) visual style. Requires `translucent: true`.

| Type                    | Required | Platform |
| ----------------------- | -------- | -------- |
| enum('default','black') | No       | Both     |

## currentTabId: number
Select a tab by the id (componentId) of a child contained in it. See [Selecting tabs programmatically](#selectingtabsprogrammatically) for details explanation.

| Type   | Required | Platform |
| ------ | -------- | -------- |
| number | No       | Both     |

## currentTabIndex

| Type   | Required | Platform |
| ------ | -------- | -------- |
| number | No       | Both     |

## drawBehind

| Type    | Required | Platform |
| ------- | -------- | -------- |
| boolean | No       | Both     |

## elevation

| Type   | Required | Platform |
| ------ | -------- | -------- |
| number | No       | Android  |

## hideShadow

| Type    | Required | Platform |
| ------- | -------- | -------- |
| boolean | No       | iOS      |

## preferLargeIcons

| Type    | Required | Platform |
| ------- | -------- | -------- |
| boolean | No       | Android  |

## tabsAttachMode

| Type                                               | Required | Platform |
| -------------------------------------------------- | -------- | -------- |
| enum('together','afterInitialTab','onSwitchToTab') | No       | Both     |

## testID

| Type   | Required | Platform |
| ------ | -------- | -------- |
| string | No       | Both     |

## titleDisplayMode

| Type                                             | Required | Android |
| ------------------------------------------------ | -------- | ------- |
| enum('alwaysShow','showWhenActive','alwaysHide') | No       | Both    |

## translucent

| Type    | Required | Platform |
| ------- | -------- | -------- |
| boolean | No       | iOS      |

## visible

| Type    | Required | Platform |
| ------- | -------- | -------- |
| boolean | No       | Both     |