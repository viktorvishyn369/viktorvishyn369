# StealthLynk

Privacy-first ecosystem for photographers and traders — bit-for-bit media
backup, tamper-evident authenticity certificates, on-device encryption, and
self-hosted infrastructure. Own your bytes, your keys, and your servers.

## Apps

| App | Description |
|---|---|
| **PhotoLynk** | Cross-platform photo & video backup with end-to-end encryption, digital proof-of-authenticity certificates (RFC 3161 timestamps, C2PA provenance manifests, 4-layer EXIF hashing), device pairing/sync, and a Solana cNFT Web3 album minted to *your* wallet |
| **PaceSeeker** | AI-assisted DCA trading bot — on-device strategy learning, multi-regime indicators, crash-safe state |
| **Lane** | Avatar/profile companion app for the ecosystem |
| **PhotoLynk Server / Desktop Tray** | Self-hosted backup server — run it on a Pi, a VPS, or your desktop. Public bundle: [`Server-Public`](https://github.com/viktorvishyn369/Server-Public) |

## Security model

- **Zero-knowledge storage** — media encrypted on-device before upload; the
  server never sees plaintext or keys
- **On-device keys** — certificates, wallets and NFT transfers signed locally;
  private keys never leave the device
- **User-owned NFTs** — cNFTs mint to the user's wallet; the service pays
  minting fees but never holds ownership
- **Local-first** — apps keep working offline and reconcile when connectivity
  returns; designed for restarts, failover and flaky networks
- **Tamper-evident** — SHA-256 fingerprints, RFC 3161 timestamps and C2PA
  manifests detect any modification

## Repositories

| Repo | Visibility | Purpose |
|---|---|---|
| [`Server-Public`](https://github.com/viktorvishyn369/Server-Public) | public | Self-host bundle: desktop tray, public pages, policy documents |
| [`PhotoLynk-iOS-Android`](https://github.com/viktorvishyn369/PhotoLynk-iOS-Android) | public | Early PhotoLynk snapshot (archived demo) |
| [`PhotoLynk-SolanaMobile`](https://github.com/viktorvishyn369/PhotoLynk-SolanaMobile) | public | Early Solana Mobile build (archived) |
| `Server`, `PhotoLynk`, `PaceSeeker`, `Lane`, `nft-service` | private | Production codebase |

## Links

- Website: [stealthlynk.io](https://stealthlynk.io)
- Pages: [viktorvishyn369.github.io](https://viktorvishyn369.github.io)
