# mahjong-oshihiki

麻雀の押し引き判断アプリ（静的HTML）。

## 公開

- URL: https://oshihiki.smartchat.co.jp
- ホスティング: Netlify（サイト名 `celadon-licorice-50702f`）。`main` へのpushで自動デプロイ
- DNS: Cloudflareの `smartchat.co.jp` ゾーンに `oshihiki` のCNAME（→ `celadon-licorice-50702f.netlify.app`、プロキシなし）

## 旧ドメイン oshihiki.com

- 2026-10-20に oshihiki.smartchat.co.jp へ移行。Netlifyで主ドメインを切り替え、oshihiki.com・www.oshihiki.com は新URLへ301リダイレクトしている
- ドメインはXServerドメインで管理。DNSはNetlify DNS
- 自動更新は停止済み。期限 2027-12-03 で失効させる（それまでリダイレクトが効く）
