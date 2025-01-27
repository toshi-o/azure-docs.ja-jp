---
author: vimeht
ms.author: vimeht
ms.date: 7/8/2021
ms.topic: include
ms.service: iot-hub-device-update
ms.openlocfilehash: d7970fff815449adf6412c2748e22b2d471e52b0
ms.sourcegitcommit: f6e2ea5571e35b9ed3a79a22485eba4d20ae36cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/24/2021
ms.locfileid: "128645465"
---
 > [!NOTE]
 > 調整可能な制限が特定のリソースまたは操作に存在しない場合、既定の制限と最大制限は同じです。
 > 制限を調整できる場合、表には "既定の制限" および "最大制限" の見出しのさまざまな値が含まれます。 既定の制限を超えて制限を引き上げることはできますが、最大制限を超えることはできません。
 > 制限の引き上げまたは既定の制限を超えるクォータが必要な場合は、[オンライン カスタマー サポート リクエスト](https://azure.microsoft.com/support/options/)を開いてください。


次の表は、Azure Resource Manager の Device Update for IoT Hub リソースの制限を示しています。

| リソース |  既定の制限 | 上限 | 調整可能? |
| --- | --- | --- | --- |
| サブスクリプションあたりのアカウント数 | 2 | 25 | はい |
| アカウントあたりのインスタンス数 | 2 | 25 | はい |
| アカウント名の長さ | 最小: 3 <br/> 最大: 24 | 最小: 3 <br/> 最大: 24 | いいえ |
| インスタンス名の長さ | 最小: 3 <br/> 最大: 36 | 最小: 3 <br/> 最大: 36 | いいえ |



次の表は、Device Update for IoT Hub 内の操作に関連付けられた各種の制限を示しています。

| 操作 |  既定の制限 | 上限 | 調整可能? |
| --- | --- | --- | --- |
| インスタンスあたりのデバイス数 | 10,000 | 10,000 | いいえ |
| インスタンスあたりの更新プロバイダー数 | 25 | 25 | いいえ |
| インスタンスごとのプロバイダーあたりの更新名の数 | 25 | 25 | いいえ |
| インスタンスごとの更新プロバイダーおよび更新名あたりの更新バージョン数 | 100 | 100 | いいえ |
| インスタンスあたりの更新回数の合計 | 100 | 100 | いいえ |
| 1 つの更新ファイルの最大サイズ | 2 GB | 2 GB | いいえ |
| 1 回のインポート操作の全ファイルの最大合計サイズ | 2 GB | 2 GB | いいえ |
| インスタンスあたりのデバイス グループ数 | 75 | 75 | いいえ |
