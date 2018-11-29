---
title: JET_LOGTIME.ToDateTime method  (Microsoft.Isam.Esent.Interop)
TOCTitle: 'ToDateTime method '
ms:assetid: M:Microsoft.Isam.Esent.Interop.JET_LOGTIME.ToDateTime
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.isam.esent.interop.jet_logtime.todatetime(v=EXCHG.10)
ms:contentKeyID: 39512964
ms.date: 07/30/2014
ms.topic: article
f1_keywords:
- Microsoft.Isam.Esent.Interop.JET_LOGTIME.ToDateTime
dev_langs:
- CSharp
- JScript
- VB
- other
api_name: 
- Microsoft.Isam.Esent.Interop.JET_LOGTIME.ToDateTime
topic_type: 
- kbSyntax
- apiref
api_type: 
- Managed
api_location: 
- Microsoft.Isam.Esent.Interop.dll
ROBOTS: INDEX,FOLLOW

---

# JET\_LOGTIME.ToDateTime method

Generate a DateTime representation of this JET\_LOGTIME.

**Namespace:**  [Microsoft.Isam.Esent.Interop](hh596136\(v=exchg.10\).md)  
**Assembly:**  Microsoft.Isam.Esent.Interop (in Microsoft.Isam.Esent.Interop.dll)

## Syntax

``` vb
'Declaration
Public Function ToDateTime As Nullable(Of DateTime)
'Usage
Dim instance As JET_LOGTIME
Dim returnValue As Nullable(Of DateTime)

returnValue = instance.ToDateTime()
```

``` csharp
public Nullable<DateTime> ToDateTime()
```

#### Return value

Type: [System.Nullable](http://msdn2.microsoft.com/en-us/library/b3h38hb0)\<[DateTime](http://msdn2.microsoft.com/en-us/library/03ybds8y)\>  
A DateTime representing the JET\_LOGTIME. If the JET\_LOGTIME is null then null is returned.  

#### Implements

[IJET\_LOGTIME.ToDateTime()](hh577639\(v=exchg.10\).md)  

## See also

#### Reference

[JET\_LOGTIME structure](hh557188\(v=exchg.10\).md)

[JET\_LOGTIME members](hh579151\(v=exchg.10\).md)

[Microsoft.Isam.Esent.Interop namespace](hh596136\(v=exchg.10\).md)
