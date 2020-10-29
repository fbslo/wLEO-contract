# Wrapped LEO Token contract

Originally written by @superoo7 as https://github.com/superoo7/BSwap, modified by @fbslo

---

Difference between https://github.com/fbslo/wToken-contract and wLEO contract is that wLEO has fixed supply.

To convert tokens back, they are not burned by instead sent back to central address.

---

[!] Before deployment, don't forget to modify contracts/Burnable.sol and replace deposit address.

After deployment, mint wanted number of tokens, then call `removeMinter()` to disable any further minting.
