---
id: filecoin.js.jsonrpcprovider
title: JsonRpcProvider class
hide_title: true
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[filecoin.js](./filecoin.js.md) &gt; [JsonRpcProvider](./filecoin.js.jsonrpcprovider.md)

## JsonRpcProvider class

<b>Signature:</b>

```typescript
export declare class JsonRpcProvider 
```

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)(connector)](./filecoin.js.jsonrpcprovider._constructor_.md) |  | Constructs a new instance of the <code>JsonRpcProvider</code> class |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [conn](./filecoin.js.jsonrpcprovider.conn.md) |  | Connector |  |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [accountKey(address, tipSetKey)](./filecoin.js.jsonrpcprovider.accountkey.md) |  | returns the public key address of the given ID address |
|  [allMinerFaults(epoch, tipSetKey)](./filecoin.js.jsonrpcprovider.allminerfaults.md) |  | returns all non-expired Faults that occur within lookback epochs of the given tipset |
|  [chainNotify(cb)](./filecoin.js.jsonrpcprovider.chainnotify.md) |  | call back on chain head updates. |
|  [changedActors(cid1, cid2)](./filecoin.js.jsonrpcprovider.changedactors.md) |  | returns all the actors whose states change between the two given state CIDs |
|  [circulatingSupply(tipSetKey)](./filecoin.js.jsonrpcprovider.circulatingsupply.md) |  | returns the circulating supply of Filecoin at the given tipset |
|  [compute(epoch, messages, tipSetKey)](./filecoin.js.jsonrpcprovider.compute.md) |  | Applies the given messages on the given tipset. |
|  [dealProviderCollateralBounds(size, verified, tipSetKey)](./filecoin.js.jsonrpcprovider.dealprovidercollateralbounds.md) |  | returns the min and max collateral a storage provider can issue |
|  [getActor(address, tipSetKey)](./filecoin.js.jsonrpcprovider.getactor.md) |  | returns the indicated actor's nonce and balance |
|  [getBlock(blockCid)](./filecoin.js.jsonrpcprovider.getblock.md) |  | returns the block specified by the given CID |
|  [getBlockMessages(blockCid)](./filecoin.js.jsonrpcprovider.getblockmessages.md) |  | returns messages stored in the specified block. |
|  [getHead()](./filecoin.js.jsonrpcprovider.gethead.md) |  | returns the current head of the chain |
|  [getMessage(messageCid)](./filecoin.js.jsonrpcprovider.getmessage.md) |  | reads a message referenced by the specified CID from the chain blockstore |
|  [getParentMessages(blockCid)](./filecoin.js.jsonrpcprovider.getparentmessages.md) |  | returns messages stored in parent tipset of the specified block. |
|  [getParentReceipts(blockCid)](./filecoin.js.jsonrpcprovider.getparentreceipts.md) |  | returns receipts for messages in parent tipset of the specified block |
|  [getReceipt(cid, tipSetKey)](./filecoin.js.jsonrpcprovider.getreceipt.md) |  | returns the message receipt for the given message |
|  [getTipSetByHeight(epochNumber)](./filecoin.js.jsonrpcprovider.gettipsetbyheight.md) |  | looks back for a tipset at the specified epoch. |
|  [hasObj(cid)](./filecoin.js.jsonrpcprovider.hasobj.md) |  | checks if a given CID exists in the chain blockstore |
|  [listActors(tipSetKey)](./filecoin.js.jsonrpcprovider.listactors.md) |  | returns the addresses of every actor in the state |
|  [listMessages(filter, tipSetKey, toHeight)](./filecoin.js.jsonrpcprovider.listmessages.md) |  | looks back and returns all messages with a matching to or from address, stopping at the given height. |
|  [listMiners(tipSetKey)](./filecoin.js.jsonrpcprovider.listminers.md) |  | returns the addresses of every miner that has claimed power in the Power Actor |
|  [lookupId(address, tipSetKey)](./filecoin.js.jsonrpcprovider.lookupid.md) |  | retrieves the ID address of the given address |
|  [marketBalance(address, tipSetKey)](./filecoin.js.jsonrpcprovider.marketbalance.md) |  | looks up the Escrow and Locked balances of the given address in the Storage Market |
|  [marketDeals(tipSetKey)](./filecoin.js.jsonrpcprovider.marketdeals.md) |  | returns information about every deal in the Storage Market |
|  [marketParticipants(tipSetKey)](./filecoin.js.jsonrpcprovider.marketparticipants.md) |  | returns the Escrow and Locked balances of every participant in the Storage Market |
|  [marketStorageDeal(dealId, tipSetKey)](./filecoin.js.jsonrpcprovider.marketstoragedeal.md) |  | returns information about the indicated deal |
|  [minerActiveSectors(address, tipSetKey)](./filecoin.js.jsonrpcprovider.mineractivesectors.md) |  | returns info about sectors that a given miner is actively proving. |
|  [minerAvailableBalance(address, tipSetKey)](./filecoin.js.jsonrpcprovider.mineravailablebalance.md) |  | returns the portion of a miner's balance that can be withdrawn or spent |
|  [minerDeadlines(address, tipSetKey)](./filecoin.js.jsonrpcprovider.minerdeadlines.md) |  | returns all the proving deadlines for the given miner |
|  [minerFaults(address, tipSetKey)](./filecoin.js.jsonrpcprovider.minerfaults.md) |  | Returns a bitfield indicating the faulty sectors of the given miner |
|  [minerInfo(address, tipSetKey)](./filecoin.js.jsonrpcprovider.minerinfo.md) |  | returns info about the indicated miner |
|  [minerInitialPledgeCollateral(address, sectorPreCommitInfo, tipSetKey)](./filecoin.js.jsonrpcprovider.minerinitialpledgecollateral.md) |  | returns the initial pledge collateral for the specified miner's sector |
|  [minerPartitions(address, idx, tipSetKey)](./filecoin.js.jsonrpcprovider.minerpartitions.md) |  | Loads miner partitions for the specified miner and deadline |
|  [minerPower(address, tipSetKey)](./filecoin.js.jsonrpcprovider.minerpower.md) |  | returns the power of the indicated miner |
|  [minerPreCommitDepositForPower(address, sectorPreCommitInfo, tipSetKey)](./filecoin.js.jsonrpcprovider.minerprecommitdepositforpower.md) |  | returns the precommit deposit for the specified miner's sector |
|  [minerProvingDeadline(address, tipSetKey)](./filecoin.js.jsonrpcprovider.minerprovingdeadline.md) |  | calculates the deadline at some epoch for a proving period and returns the deadline-related calculations. |
|  [minerRecoveries(address, tipSetKey)](./filecoin.js.jsonrpcprovider.minerrecoveries.md) |  | returns a bitfield indicating the recovering sectors of the given miner |
|  [minerSectorCount(address, tipSetKey)](./filecoin.js.jsonrpcprovider.minersectorcount.md) |  | returns the number of sectors in a miner's sector set and proving set |
|  [minerSectors(address, tipSetKey)](./filecoin.js.jsonrpcprovider.minersectors.md) |  | returns info about the given miner's sectors |
|  [networkName()](./filecoin.js.jsonrpcprovider.networkname.md) |  | returns the name of the network the node is synced to |
|  [readObj(cid)](./filecoin.js.jsonrpcprovider.readobj.md) |  | reads ipld nodes referenced by the specified CID from chain blockstore and returns raw bytes. |
|  [readState(address, tipSetKey)](./filecoin.js.jsonrpcprovider.readstate.md) |  | returns the indicated actor's state |
|  [release()](./filecoin.js.jsonrpcprovider.release.md) |  |  |
|  [searchMsg(cid)](./filecoin.js.jsonrpcprovider.searchmsg.md) |  | searches for a message in the chain and returns its receipt and the tipset where it was executed |
|  [sectorExpiration(address, sector, tipSetKey)](./filecoin.js.jsonrpcprovider.sectorexpiration.md) |  | returns epoch at which given sector will expire |
|  [sectorGetInfo(address, sector, tipSetKey)](./filecoin.js.jsonrpcprovider.sectorgetinfo.md) |  | StateSectorGetInfo returns the on-chain info for the specified miner's sector |
|  [sectorPartition(address, sector, tipSetKey)](./filecoin.js.jsonrpcprovider.sectorpartition.md) |  | finds deadline/partition with the specified sector |
|  [sectorPreCommitInfo(address, sector, tipSetKey)](./filecoin.js.jsonrpcprovider.sectorprecommitinfo.md) |  | returns the PreCommit info for the specified miner's sector |
|  [stateCall(message, tipSetKey)](./filecoin.js.jsonrpcprovider.statecall.md) |  | runs the given message and returns its result without any persisted changes. |
|  [stateReplay(tipSetKey, cid)](./filecoin.js.jsonrpcprovider.statereplay.md) |  | returns the result of executing the indicated message, assuming it was executed in the indicated tipset |
|  [stopChainNotify(intervalId)](./filecoin.js.jsonrpcprovider.stopchainnotify.md) |  |  |
|  [verifiedClientStatus(address, tipSetKey)](./filecoin.js.jsonrpcprovider.verifiedclientstatus.md) |  | returns the data cap for the given address. |
|  [version()](./filecoin.js.jsonrpcprovider.version.md) |  |  |
|  [waitMsg(cid, confidence)](./filecoin.js.jsonrpcprovider.waitmsg.md) |  | looks back in the chain for a message. If not found, it blocks until the message arrives on chain, and gets to the indicated confidence depth. |