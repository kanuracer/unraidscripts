# unraidscripts
scripts for unraid user scripts

boot-backup: script zum backupen des usb sticks. schedule 1h

Nextcloud_LoginAudit: Prüft die Nextcloud.log nach fehlerhaften Anmeldungen (Login failed). Sollte es eine fehlerhafte Anmeldung geben, dann wird die IP, Benutzer und ReqID in ein Logfile geschrieben und über den Unraid-Nachrichtendienst (Telegram, E-Mail,...) eine Nachricht verschickt. Die ReqID wird beim nächsten Durchlauf ignoriert.

