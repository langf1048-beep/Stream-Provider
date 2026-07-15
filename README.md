# Media-Stream-Provider

We provide free open source streaming data as complied android support files rather than direct source for media projects, usable as you want and flexible. We don't contain any client UI structures, application views, and tracking engines to keep only the pure data mechanism to connect our backend.

## 📁 Repository Map

The root workspace contains isolated core modules grouped specifically by their underlying system functions:

### 📁 `/AndroidManifest`
Contains the extracted network security policies, manifest definitions, configurations, and application permission levels required to run the core network routines safely.
* `AndroidManifest.xml`
* `provider 2 AndroidManifest.xml`
* `provider 3 AndroidManifest.xml`

### 📁 `/assets`
Houses the active cryptographic handshake tokens, SSL credentials, and server routing definitions used to establish secure connections with streaming targets.
* `hisavana_rsa_public_key.pem` & `rsa_public_key.pem` (Public cryptographic validation keys)
* `license.crt` (Root network authorization certificate)
* `local_mcc.json` & `sdk_country_cc_mcc.json` (Mobile Country Code templates to manage carrier-specific and geo-restricted video feeds)
* `provider 2 idc.json` (Regional data center traffic router schemas)
* `provider 2 pp_hlsProtected.dat` (The protected connection strings needed to authorize secure HTTP Live Streaming media pipelines)

### 📁 `/dex`
Contains the compiled Dalvik Executable binary modules carrying the application's actual data extraction and request parsing routines. Subdirectories isolate them to prevent system conflicts:
* **`provider 1/`**: Base logic arrays mapping out standard data requests (`classes.dex` through `classes8.dex`).
* **`provider 2/`**: Extended execution blocks containing complex operational arrays (`classes.dex` through `classes12.dex`).
* **`provider 3/`**: Light independent streaming framework footprint (`classes.dex`).

### 📁 `/org`
Holds the low-level, headless structural network configurations utilized for media communication over network routers:
* **`fourthline/cling/support/`**: Standard UPnP/DLNA schemas (`avtransport` for transport management, `renderingcontrol` for playback properties).
* **`fourthline/seamless/`**: Direct serialization helper utilities handling structural schema handshakes safely.

## 🛠️ Usage Target
This structural arrangement is optimized for fetching with your own streaming app with your creativity.

## ⬇️ Update
We have decided to public the direct source soon...
Stay tuned.
