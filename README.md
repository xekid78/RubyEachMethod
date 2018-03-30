# RubyEachMethod
eachメソッド

## 処理
配列の内容を`each()`メソッドを使って出力します。

## コード
```
team = ["佐藤", "鈴木", "田中", "岸田", "有森"]
team.each do |i|
    puts "#{i}です。"
end
```

## 出力結果  
```
佐藤です。
鈴木です。
田中です。
岸田です。
有森です。
```
  
## 開発環境
| 開発ツール |  |
|:-|:-|
| OS | Windows10 |
| 仮想化ソフト | Oracle VM VirtualBox 5.2 |
| 構築ソフト | Vagrant 2.0.2 |
| 仮想化上OS | CentOS 6.9 |
| SSHクライアント | PuTTY 0.6.8 |
| FTPクライアント | Cyberduck 6.3.5 |
| エディタ | Atom 1.24.0 |
| 開発言語 | Ruby 2.4.0 |
