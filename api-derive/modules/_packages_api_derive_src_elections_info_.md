**Polkadot JS API**

> [README](../README.md) / [Globals](../globals.md) / "packages/api-derive/src/elections/info"

# Module: "packages/api-derive/src/elections/info"

## Index

### Functions

* [info](_packages_api_derive_src_elections_info_.md#info)

## Functions

### info

▸ **info**(`instanceId`: string, `api`: ApiInterfaceRx): function

*Defined in [packages/api-derive/src/elections/info.ts:57](https://github.com/polkadot-js/api/blob/05c0379f4/packages/api-derive/src/elections/info.ts#L57)*

**`name`** info

**`example`** 
<BR>

```javascript
api.derive.elections.info(({ members, candidates }) => {
  console.log(`There are currently ${members.length} council members and ${candidates.length} prospective council candidates.`);
});
```

#### Parameters:

Name | Type |
------ | ------ |
`instanceId` | string |
`api` | ApiInterfaceRx |

**Returns:** function