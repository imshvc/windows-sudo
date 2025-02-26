# Sudo executable for Windows 10

Official sudo from [Microsoft](https://github.com/microsoft/sudo).

Executable extracted from a Windows 11 install.

**Verify hash:**

```text
> C:\Windows\System32\certutil.exe -hashfile sudo.exe sha256
SHA256 hash of sudo.exe:
95e852738853949c34a803c39b264d53c86f80de56b654c05489ce7325c66ff4
```

# Installation

1. Download **sudo.exe** from the [Releases page](https://github.com/imshvc/windows-sudo/releases).
2. Copy **sudo.exe** to **C:\\Windows\\System32**.
3. Run Terminal as admin and run the command **sudo config --enable normal**.

Now use the sudo command and run apps "inline".
