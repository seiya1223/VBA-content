---
title: OlkTimeControl.MouseUp Event (Outlook)
keywords: vbaol11.chm1000405
f1_keywords:
- vbaol11.chm1000405
ms.prod: outlook
api_name:
- Outlook.OlkTimeControl.MouseUp
ms.assetid: fa4c6576-30af-5b91-aa60-b554c324997d
ms.date: 06/08/2017
---


# OlkTimeControl.MouseUp Event (Outlook)

Occurs after the user releases a mouse button that has been pressed on the control.


## Syntax

 _expression_ . **MouseUp**( **_Button_** , **_Shift_** , **_X_** , **_Y_** )

 _expression_ A variable that represents an **OlkTimeControl** object.


### Parameters



|**Name**|**Required/Optional**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|
| _Button_|Required| **Integer**|An  **[OlMouseButton](olmousebutton-enumeration-outlook.md)** constant that specifies which button on the mouse has been pressed.|
| _Shift_|Required| **Integer**|A bitwise-OR mask of constants in the  **[OlShiftState](olshiftstate-enumeration-outlook.md)** enumeration that specifies whether the **SHIFT**,  **CTRL**, or  **ALT** keys have been pressed.|
| _X_|Required| **[OLE_XPOS_CONTAINER]**|Identifies the location of the mouse cursor on the X-axis relative to the form.|
| _Y_|Required| **[OLE_YPOS_CONTAINER]**|Identifies the location of the mouse cursor on the Y-axis relative to the form.|

## See also


#### Concepts


[OlkTimeControl Object](olktimecontrol-object-outlook.md)

