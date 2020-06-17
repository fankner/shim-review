Make sure you have provided the following information:

 - [x] link to your code branch cloned from rhboot/shim-review in the form user/repo@tag
 - [x] completed README.md file with the necessary information
 - [x] shim.efi to be signed
 - [x] public portion of your certificate embedded in shim (the file passed to VENDOR_CERT_FILE)
 - [x] any extra patches to shim via your own git tree or as files
 - [x] any extra patches to grub via your own git tree or as files
 - [x] build logs


###### What organization or people are asking to have this signed:
`Rohde & Schwarz Cybersecurity GmbH`

###### What product or service is this for:
`Trusted Disk Full-disk encryption`

###### What is the origin and full version number of your shim?
`https://github.com/rhboot/shim/releases/tag/15`

###### What's the justification that this really does need to be signed for the whole world to be able to boot it:
`[your text here]`

###### How do you manage and protect the keys used in your SHIM?
`The private key is stored on hardware token with restricted access.`

###### Do you use EV certificates as embedded certificates in the SHIM?
`No`

###### What is the origin and full version number of your bootloader (GRUB or other)?
`[your text here]`

###### If your SHIM launches any other components, please provide further details on what is launched
`[your text here]`

###### How do the launched components prevent execution of unauthenticated code?
`[your text here]`

###### Does your SHIM load any loaders that support loading unsigned kernels (e.g. GRUB)?
`[your text here]`

###### What kernel are you using? Which patches does it includes to enforce Secure Boot?
`[your text here]`

###### What changes were made since your SHIM was last signed?
`[your text here]`

###### What is the hash of your final SHIM binary?
`[your text here]`
