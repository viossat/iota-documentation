# Outsource proof of work

**By default [proof of work](root://getting-started/0.1/transactions/proof-of-work.md) is done on the computer that is running Trinity. In this guide, you learn how to ask one of the connected nodes to do proof of work instead.**

1. Go to **Settings** > **Node** > **Add custom nodes**,  and enter the URL or IP address of one or more nodes that you want to add

    :::info:
    All nodes in Trinity must communicate over HTTPS.
    :::

2. Enable the **Outsource proof of work** option

3. In the **PROOF OF WORK NODE** dropdown, select your node

    :::warning:Devnet nodes
    If your node is a Devnet node, you must also [connect to a primary Devnet node](../how-to-guides/connect-to-a-custom-node.md).
    :::

4. Click **Save**

:::success:Congratulations! :tada:
Whenever you send a transaction, the proof of work is done by your custom proof-of-work node.
:::

## Next steps

[Send a transaction](../how-to-guides/send-a-transaction.md)