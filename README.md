# g00se_bt_exploit

Samsung devices are vulnerable to a critical Bluetooth security vulnerability that allows an attacker to control the targeted device as if they were attached by a Bluetooth keyboard, performing various functions remotely depending on the endpoint. This vulnerability, tracked as CVE-2023-45866, affects macOS, iOS, Android, and Linux device platforms. It works by tricking the Bluetooth host state-machine into pairing with a fake keyboard without user confirmation.

On Android devices, the vulnerability is exploitable whenever Bluetooth is enabled. However, Samsung has released patches for most affected devices, although some older models may not receive updates.
 To mitigate the risk, users are advised to install the latest available security patches and to only enable Bluetooth when strictly necessary.

Additionally, a zero-day vulnerability, tracked as CVE-2024-44068, was discovered in Samsung’s mobile and wearable processors, including Exynos models 9820, 9825, 980, 990, 850, and W920. This vulnerability allows for arbitrary code execution and has been exploited in the wild as part of an exploit chain enabling attackers to escalate privileges on vulnerable devices.

Samsung has released a patch as part of its October 2024 security updates, and users should apply this update to mitigate the risk
