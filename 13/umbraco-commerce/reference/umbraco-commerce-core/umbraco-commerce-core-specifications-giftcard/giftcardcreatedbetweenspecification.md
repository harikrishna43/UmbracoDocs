---
title: GiftCardCreatedBetweenSpecification
description: API reference for GiftCardCreatedBetweenSpecification in Umbraco Commerce
---
## GiftCardCreatedBetweenSpecification

```csharp
public class GiftCardCreatedBetweenSpecification : IQuerySpecification<GiftCardReadOnly>, 
    ISpecification<GiftCardReadOnly>
```

**Inheritance**

* interface [IQuerySpecification&lt;!0&gt;](../../umbraco-commerce-common/umbraco-commerce-common-specifications/iqueryspecification-1.md)
* interface [ISpecification&lt;!0&gt;](../../umbraco-commerce-common/umbraco-commerce-common-specifications/ispecification-1.md)

**Namespace**
* [Umbraco.Commerce.Core.Specifications.GiftCard](README.md)

### Constructors

#### GiftCardCreatedBetweenSpecification

```csharp
public GiftCardCreatedBetweenSpecification(DateTime? fromDate, DateTime? toDate)
```


### Fields

#### FromDate

```csharp
public DateTime? FromDate;
```


---

#### ToDate

```csharp
public DateTime? ToDate;
```


### Methods

#### Accept

```csharp
public void Accept(IVisitor visitor)
```


---

#### IsSatisfiedBy

```csharp
public bool IsSatisfiedBy(GiftCardReadOnly item)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->
