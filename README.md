# サッカー情報管理システム
## プロジェクトの概要
このシステムでは、<br>以下の内容を管理します。
- チームリスト 
  - Jリーグ
  - 欧州リーグ
- 選手
- 試合結果

## ページ構成
| URL | 内容 | サーブレット | HTML |
|:---|:---|:---|:---|
| /home | ホーム | HomeServlet | index.jsp |
| /list | チーム紹介 | TeamServlet | list.jsp |
| /login | ログイン | LoginServlet | login.jsp |

### domainクラスの例
```java
@Date
public class Team{
    private Integer id;
}

