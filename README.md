# search-agentをlanggraphを使用して作ってみた
## フロー
1. 特定のドキュメントをロード
2. プロンプトから持ってる文書で回答できるかを評価
3. 評価が⚪︎なら回答生成
4. ×ならtavilyAPIよりweb検索してその結果を用いて回答を生成

### この仕組み作って自己学習できるAgentを作れるのでは？
