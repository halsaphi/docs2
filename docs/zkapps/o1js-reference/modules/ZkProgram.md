[o1js](../README.md) / [Modules](../modules.md) / ZkProgram

# Namespace: ZkProgram

## Table of contents

### Functions

- [Proof](ZkProgram.md#proof)

## Functions

### Proof

▸ **Proof**<`PublicInputType`, `PublicOutputType`\>(`program`): typeof `ZkProgramProof`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `PublicInputType` | extends [`FlexibleProvablePure`](../modules.md#flexibleprovablepure)<`any`\> |
| `PublicOutputType` | extends [`FlexibleProvablePure`](../modules.md#flexibleprovablepure)<`any`\> |

#### Parameters

| Name | Type |
| :------ | :------ |
| `program` | `Object` |
| `program.name` | `string` |
| `program.publicInputType` | `PublicInputType` |
| `program.publicOutputType` | `PublicOutputType` |

#### Returns

typeof `ZkProgramProof`

#### Defined in

[lib/proof_system.ts:902](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/proof_system.ts#L902)