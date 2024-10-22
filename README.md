# MAUICrossPlatformTemplate
MAUI Cross Platform アプリ を作成するためのテンプレート

## 使用法

### テンプレートの取得
[MAUIxplat.nupkg](https://github.com/kznagamori/MAUICrossPlatformTemplate/releases/download/v1.0.0/kznagamori.MAUIxplat.1.0.0.nupkg)
をダウンロードします。

### テンプレートのインストール
ダウンロードしたnugetパッケージをインストールします。
```
dotnet new install kznagamori.MAUIxplat.1.0.0.nupkg
```

### MAUI Cross Platform アプリ プロジェクトの作成
```
dotnet new maui-xplat -n <プロジェクト名>
```
**例:** `dotnet new maui-xplat -n MyMauiXPlat `

### テンプレートのアンインストール
```
dotnet new uninstall kznagamori.MAUIxplat
```

### ターゲット

net8.0のみをターゲットとしています。

### ビルド

```
dotnet build
```

### リリースビルド

```
publish_windows.bat
```

### kznagamori.MAUIxplat.X.X.X.nupkgの作成

```
nuget pack .\MAUICrossPlatformTemplate.nuspec
```

