# 12306
hello guys，This is a gadget for querying train tickets on the Linux.
I use the docopt, requests, prettytable, colorama and other libraries
Implemented this function in Ubuntu.

This project is to learn from the video of the “shiyanlou” train ticket inquiry tool and complete it by myself.

Page api:
https://kyfw.12306.cn/otn/leftTicket/query?leftTicketDTO.train_date=2018-04-19&leftTicketDTO.from_station=BJP&leftTicketDTO.to_station=SHH&purpose_codes=ADULT
Page JS:
https://kyfw.12306.cn/otn/resources/merged/queryLeftTicket_end_UAM_js.js?scriptVersion=1.9033
http://tool.oschina.net/codeformat/js/ （Online formatting tool）

Steps：
python3 setup.py install

tickets 北京 上海 2018-03-22
