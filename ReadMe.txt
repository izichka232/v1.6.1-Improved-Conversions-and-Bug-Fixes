Collection check is a bit more stable now (and is disabled by default) - If you had it enabled, you will have to re-enable it with this update
Bank module doesn't add the profit for the entire group of items immediately anymore when only part of it was sold
Bank module now doesn't hurt rendering times
Profit is calculated whenever buying OR selling is done, so if someone is "reverse" flipping (selling then buying the item back), it should still work as intended
Profit calculations are more efficient and logical
Crafting profits should actually be accurate now. Before, it would pull from sells when trying to determine if a crafted item had all the resources bought.
Chat notifications for orders should no longer try to show up when you aren't on any server or world (fixing, hopefully, logs being filled with errors from the notification module)
