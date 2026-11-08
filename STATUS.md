# Independent OSDCloud V1 branch

Modified 2026-11-08 from vanilla baseline 1bf395f2b673b2874992716a776c0be4a8c98c6e.

Removed complete features: Start-RecastOSDCloudCLI, Invoke-RecastOSDCloudCLI and Update-RecastOSDCloudUSBCache; also removed Get-OSDCoreLicense, Show-OSDCoreLicenseHelp, their manifest exports and associated command documentation.

Classic V1 source is unchanged. No license check has been bypassed to retain a gated feature. GPL license and original attribution remain intact. Other Recast-named experimental helpers remain where no license gate was found; this is not a complete removal of Recast-related code.

Validation: static reference, manifest, XML and PowerShell syntax checks. Windows/WinPE deployment and external service availability are not verified.

Next action: review and merge the removal PR when ready, then audit external downloads, catalogs and module updates before Windows/WinPE testing. Baseline master remains unchanged until merge. No deployment or package publication performed.
