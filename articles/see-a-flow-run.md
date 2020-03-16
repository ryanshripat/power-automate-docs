---
title: Watch a flow run | Microsoft Docs
description: View the inputs and outputs for each step of a flow to verify that it behaves as expected.
services: ''
suite: flow
documentationcenter: na
author: MSFTMAN
manager: KVIVEK
ms.author: Deonhe
editor: ''
tags: ''
ms.service: flow
ms.devlang: na
ms.topic: article
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 02/05/2018
search.app: 
  - Flow
search.audienceType: 
  - flowmaker
  - enduser
---
# Watch your flows in action


>[!VIDEO https://www.youtube.com/embed/3wPoUCGm7Yg]

To ensure that your flows run as you expect, perform the trigger, and then review the inputs and outputs that each step in your flow generates.

1. Create or update a flow, and then leave the designer open after you select **Create flow** or **Update flow**.

     For example, [create a flow](get-started-logic-flow.md) that sends email whenever someone tweets using the **#azure** hashtag.
1. Perform the starting action for your flow.

    For example, send a tweet that contains the **#azure** hashtag.

    The starting action and each subsequent step indicates whether it succeeded and how long it took.

    ![Image of a successful run](./media/see-a-flow-run/successful-flow-run.png)
1. Select the trigger or action to see its inputs and outputs.

    ![Image of a successful run with expanded cards](./media/see-a-flow-run/successful-flow-expanded-cards.png)
1. Select **Edit flow** to make more changes or select **Done** if the flow works as you expect.