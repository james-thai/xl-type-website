XL-TYPE — Launch Instructions
==============================

1. UNBLOCK THE ZIP (recommended)

   Windows marks files downloaded from the internet as untrusted
   ("Mark of the Web"), which can trigger extra security prompts when
   you open the workbook. Before extracting, right-click
   XL-Type-v1.0.zip -> Properties -> check "Unblock" -> OK. Then
   extract as normal; the extracted files won't carry the block.

2. VERIFY BEFORE YOU ENABLE MACROS (recommended)

   XL-Type-v1.0.xlsm is a macro-enabled workbook. Before enabling
   macros, verify the file hasn't been tampered with by checking its
   SHA-256 hash against the value published on the official site:

       https://xl-type.com

   Open PowerShell in the folder containing XL-Type-v1.0.xlsm and run:

       Get-FileHash .\XL-Type-v1.0.xlsm -Algorithm SHA256

   Compare the resulting hash to the SHA-256 value listed on
   https://xl-type.com. If they don't match, do not enable macros —
   delete the file and re-download it from the official site.

3. LAUNCH

   - Open XL-Type-v1.0.xlsm in Microsoft Excel.
   - Excel will show a security warning because the file contains
     macros. Click "Enable Content" (or "Enable Macros") to allow the
     game to run.
   - The game starts automatically once macros are enabled.

4. REQUIREMENTS

   - Windows 10 or 11
   - Microsoft 365 or Excel 2016+ (.xlsm support)
   - Macros enabled (Trust Center -> Macro Settings -> Enable macros)
   - 1920x1080 resolution recommended (120-column board)
   - A relatively powerful CPU (Excel is not an optimized game engine)

XL-TYPE is an independent fan project. Not affiliated with, endorsed
by, or sponsored by Microsoft Corporation.
