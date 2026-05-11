このフォルダを Web サーバで公開すると iPhone で見られます。
同じ Wi-Fi 内で試すだけなら、このフォルダで `python3 -m http.server 8000` を実行してください。
その後、iPhone の Safari で Mac の IP アドレスに `:8000` を付けて開きます。
レイヤ切替で CS立体図 と 現在の空中写真 を切り替えられます。
GNSSログ開始を押すと継続取得した位置が地図上とログ欄に保存され、再読込後も残ります。
iPhone で現在地を取得するには Geolocation API が必要なので、公開先は HTTPS である必要があります。
LAN 内の http://192.168.x.x では現在地取得が拒否されることがあります。GitHub Pages など HTTPS で公開してください。
