###ssr_admin

SSR調査研究 管理者用サンプルアプリケーション

###設計

* アクター

>1. 管理者(大学)
>1. 修了学生
>1. 在学生
>1. 非学生



* [ユースケース図](https://github.com/takanorioo/SSR_Open_Project/wiki/%E3%83%A6%E3%83%BC%E3%82%B9%E3%82%B1%E3%83%BC%E3%82%B9%E5%9B%B3)
* [DB設計](https://github.com/takanorioo/SSR_Open_Project/wiki/Db%E8%A8%AD%E8%A8%88)


### アプリケーション構成

>#####管理者用アプリケーション (ssr_adming) 
>* 管理者用EmailとPASSで認証
>* 全てのユースケースが可能
>
>#####在学生と修了学生用アプリケーション (ssr_student)
>* 学内EmailとPASSで認証
>
>##### 非学生と在学生用アプリケーション (ssr_public)
>* EmailとPASSで認証 
>* 説明会関連のユースケースを行う。


### 各ルーティングとその説明

* [管理者用アプリケーション](https://github.com/takanorioo/SSR_Open_Project/wiki/%E7%AE%A1%E7%90%86%E8%80%85%E7%94%A8%E3%82%A2%E3%83%97%E3%83%AA%E3%82%B1%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3)
* [在学生と修了学生用アプリケーション](https://github.com/takanorioo/SSR_Open_Project/wiki/%E5%9C%A8%E5%AD%A6%E7%94%9F%E3%81%A8%E4%BF%AE%E4%BA%86%E5%AD%A6%E7%94%9F%E7%94%A8%E3%82%A2%E3%83%97%E3%83%AA%E3%82%B1%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3)
* [非学生用アプリケーション]()
* 

### 開発関連

* [開発環境]()
