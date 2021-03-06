---
Description: The get\_Hue method retrieves the hue value on which to key. This property applies only when the key type is DXTKEY\_HUE.
ms.assetid: d37fedd6-f29f-4f16-821b-c5f8520c4e12
title: IDxtKey::get_Hue method (Qedit.h)
ms.topic: reference
ms.date: 05/31/2018
topic_type: 
- APIRef
- kbSyntax
api_name: 
- IDxtKey.get_Hue
api_type: 
- COM
api_location: 
- strmiids.lib
- strmiids.dll
---

# IDxtKey::get\_Hue method

> [!Note]  
> \[Deprecated. This API may be removed from future releases of Windows.\]

 

The `get_Hue` method retrieves the hue value on which to key. This property applies only when the key type is DXTKEY\_HUE.

## Syntax


```C++
HRESULT get_Hue(
  [out, retval] int *pVal
);
```



## Parameters

<dl> <dt>

*pVal* \[out, retval\]
</dt> <dd>

Receives the hue value on which to key.

</dd> </dl>

## Return value

If this method succeeds, it returns **S\_OK**. Otherwise, it returns an **HRESULT** error code.

## Remarks

> [!Note]  
> The header file Qedit.h is not compatible with Direct3D headers later than version 7.

 

> [!Note]  
> To obtain Qedit.h, download the [Microsoft Windows SDK Update for Windows Vista and .NET Framework 3.0](https://msdn.microsoft.com/windowsvista/bb980924.aspx). Qedit.h is not available in the Microsoft Windows SDK for Windows 7 and .NET Framework 3.5 Service Pack 1.

 

## Requirements



|                    |                                                                                         |
|--------------------|-----------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>Qedit.h</dt> </dl>      |
| Library<br/> | <dl> <dt>Strmiids.lib</dt> </dl> |



## See also

<dl> <dt>

[**IDxtKey Interface**](idxtkey.md)
</dt> <dt>

[**IDxtKey::get\_KeyType**](idxtkey-get-keytype.md)
</dt> </dl>

 

 




