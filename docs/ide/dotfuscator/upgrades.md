---
title: "Upgrade Dotfuscator Community Edition (CE) | Microsoft Docs"
ms.date: "2017-02-08"
ms.prod: "visual-studio-dev15"
ms.devlang: "dotnet"
ms.technology: 
  - "dotfuscator"
ms.topic: "article"
keywords: Dotfuscator, Dotfuscator CE, PreEmptive, PreEmptive Solutions, PreEmptive Protection, protection, community edition, obfuscation, .NET, free, Visual Studio 2017, upgrade, command line
helpviewer_keywords: 
  - "PreEmptive Protection - Dotfuscator" 
  - "Dotfuscator Community Edition"
  - "Dotfuscator CE"
  - "Dotfuscator"
  - "obfuscation"
  - "protection"
  - "Dotfuscator upgrade"
  - "upgrade Dotfuscator"
  - "upgrading Dotfuscator"
  - "register Dotfuscator"
  - "registering Dotfuscator"
  - "Dotfuscator command line"
  - "Dotfuscator Professional"
description: "Learn how to upgrade the free Dotfuscator Community Edition included in Visual Studio 2017."
ms.assetid: c7c60904-27f9-4f1f-b79b-ddf65041b810
author: "Joe-Sewell-PreEmptive"
manager: "ghogen"
translation.priority.ht: 
  - "cs-cz"
  - "de-de"
  - "es-es"
  - "fr-fr"
  - "it-it"
  - "ja-jp"
  - "ko-kr"
  - "pl-pl"
  - "pt-br"
  - "ru-ru"
  - "tr-tr"
  - "zh-cn"
  - "zh-tw"
---

# Upgrade Dotfuscator Community Edition (CE)

Dotfuscator Community Edition (Dotfuscator CE) offers many application protection and hardening features immediately to all developers using Microsoft Visual Studio.
However, there are more features available to users who upgrade their version of Dotfuscator.

## Registering Dotfuscator CE

Registered users of Dotfuscator CE get access to additional features, such as [command line support][cli], which makes it easy to integrate Dotfuscator CE into your automated build process.

Registration is quick, simple, and free of charge.
To register Dotfuscator CE, see [the Registering Dotfuscator CE section on the Getting Started page of the full Dotfuscator CE User Guide][register-ce].

## Dotfuscator Professional

While Dotfuscator Community Edition provides a basic level of protection, 
***PreEmptive Protection - Dotfuscator* Professional Edition** includes enhanced obfuscation transforms and protection capabilities.
These include:

* *Intellectual Property Protection*
  * Additional renaming options, including Enhanced Overload Induction™ and randomized identifier selection.
  * Tooling for decoding obfuscated stack traces.
  * Access to enterprise-level obfuscation transforms, including [transforms targeted at defeating automated code decompilation][control-flow].
  * The ability to [obscure sensitive strings][string-encryption], making a simple search of the decompiled code impossible.
  * The ability to [discreetly embed ownership and distribution strings into your assemblies][watermarking] (software watermarking), allowing you to determine the source of unauthorized software leaks.
  * The ability to [combine multiple assemblies into one][linking], making it even more difficult for attackers to determine the roles of code elements, as separation of concerns has been eliminated.
  * The ability to [automatically remove unused code from your application][pruning], reducing the amount of sensitive code that is shipped.
* *Application Integrity Protection*
  * Additional [application defense behaviors][check-actions].
  * The ability to inject anti-tamper and anti-debug code into `.dll` assemblies.
  * The ability to provide a warning period before an application's end-of-life deadline.
  * The ability to notify application code during an end-of-life warning period or after the deadline.
  * Telemetry encryption.
* *Application Monitoring*
  * The ability to collect and save collected information during temporary network outages.
  * The ability to collect personally-identifiable information.
  * Unlimited use of [feature tracking][features].
  * The ability to track exceptions caught and thrown by your code, in addition to unhandled exceptions.
  * The ability to track exceptions in `.dll` assemblies.
  * Telemetry encryption.

Dotfuscator Professional is the industry standard [.NET Obfuscator][net-obfuscator] and is suitable for enterprise developers requiring ongoing support, maintenance, and product updates.
Additionally, Dotfuscator Professional offers tighter integration with Visual Studio and is licensed for commercial use.

For more information on the advanced application protection features of Dotfuscator Professional, please visit PreEmptive Solutions' [Dotfuscator Overview page][product-about] and [compare it to Community Edition][product-compare].
[Fully-supported trials are available on request at preemptive.com][eval].

## See Also

[This topic in the full Dotfuscator CE User Guide][full]

<!-- Copyright © 2017 PreEmptive Solutions, LLC -->

[control-flow]: https://www.preemptive.com/products/dotfuscator/features#controlflow
[string-encryption]: https://www.preemptive.com/products/dotfuscator/features#string
[watermarking]: https://www.preemptive.com/products/dotfuscator/features#watermarking
[linking]: https://www.preemptive.com/products/dotfuscator/features#linking
[pruning]: https://www.preemptive.com/products/dotfuscator/features#pruning

[check-actions]: https://www.preemptive.com/images/stories/Dotfuscator/webframe.html#Check%20Actions.html
[features]: https://www.preemptive.com/images/stories/Dotfuscator/webframe.html#Feature_Usage_Tracking_and_the_Feature_Attribute.html

[net-obfuscator]: https://www.preemptive.com/products/dotfuscator/overview
[eval]: https://www.preemptive.com/eval-request

[product-about]: https://www.preemptive.com/products/dotfuscator/overview
[product-compare]: https://www.preemptive.com/products/dotfuscator/compare-editions

[cli]: https://www.preemptive.com/dotfuscator/ce/docs/help/5.27/intro_cli.html
[register-ce]: https://www.preemptive.com/dotfuscator/ce/docs/help/5.27/gui_getstarted.html#register

[full]: https://www.preemptive.com/dotfuscator/ce/docs/help/5.27/intro_upgrades.html