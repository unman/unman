I use Split GPG in Qubes, with subkeys.

The key at https://www.qubes-os.org/team is the one I use for email.  
The fingerprint is:  
C6E2 533D 976E 4B29 A82B  79CB 0C6D 15D5 E0A9 816E

*I have used this key to sign this note.*

I use a separate key for signing code,packages and templates: 

```
pub   rsa4096 2016-06-25 [SC]
      4B1F400DF25651B53C4141B38B3F30F9C8C0C2EF
uid           [ unknown] unman (Qubes OS signing key) <unman@thirdeyesecurity.org>
sub   rsa4096 2016-06-25 [E]
sub   rsa4096 2016-06-27 [S] [expires: 2024-06-30]

```

Both are available on keyservers - for example:  
https://keys.gnupg.net/pks/lookup?search=unman+Qubes+OS+signing&fingerprint=on&op=index

The public key I use for Qubes OS signing is unman.pub  
gpg-keys.asc contains a PGP Signed copy of this information.
