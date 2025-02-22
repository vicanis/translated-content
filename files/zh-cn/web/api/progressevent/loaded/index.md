---
title: ProgressEvent.loaded
slug: Web/API/ProgressEvent/loaded
page-type: web-api-instance-property
tags:
  - API
  - Progress Event
  - ProgressEvent
  - Property
translation_of: Web/api/ProgressEvent/loaded
---
{{APIRef("XMLHttpRequest")}}

**`ProgressEvent.loaded`** 只读属性是一个整数，表示底层的进程已经执行的工作量。可以使用该属性和 `ProgressEvent.total` 计算完成工作的比率。当使用 HTTP 下载一个资源，其值以字节（而不是位）为单位，且仅表示内容（body）部分，不包含标头和其它开销。

## 值

一个数值。

## 规范

{{Specifications}}

## 浏览器兼容性

{{Compat}}

## 参见

- 它属于 {{domxref("ProgressEvent")}} 接口。
