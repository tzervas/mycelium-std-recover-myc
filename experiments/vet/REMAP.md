# Remap Manifest — mycelium-std-recover → std.recover

_DN-109 §5.2 provenance ledger. Guarantee: **Declared** — this records proposed/performed structural and idiom choices; it does not certify them (no guarantee-tag upgrade from the manifest's existence alone, VR-5). Rendered from `remap` in `summary.json` — this file is a pure projection, never a second source of truth._

## Nodules (8)

| Target nodule | Operation | Safety | API surface changed | Identity neutral | Sources | Rationale |
|---|---|---|---|---|---|---|
| `std.recover.action` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-std-recover/src/action.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `std.recover.effect` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-std-recover/src/effect.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `std.recover.guarantee_matrix` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-std-recover/src/guarantee_matrix.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `std.recover.handle` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-std-recover/src/handle.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `std.recover` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-std-recover/src/lib.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `std.recover.outcome` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-std-recover/src/outcome.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `std.recover.policy` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-std-recover/src/policy.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `std.recover.registry` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-std-recover/src/registry.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |

## Idiom choices (0)

_(none in this run — v0 Mechanical-only auto-fire with no located idiom-choice instrumentation yet; see DN-109 §7-e and this module's doc comment)_
