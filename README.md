# zimbra-summertime-2019
TimeZones for correct the schedules after date 20-10-2019 in google chrome.

# fix created schedules
$ su - zimbra

$ wget https://raw.githubusercontent.com/inova-tecnologias/zimbra-summertime-2019/master/fix_created_mailings.xml

$ zmtzupdate --rulefile fix_created_mailing.xml -a all -after "2019/10/21 00:00:00"
