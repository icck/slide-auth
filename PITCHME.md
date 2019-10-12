### 認証と認可の違いが度々分からなくなるからまとめ
Komori Issei

---

### 目的
- ユーザー認証を作ろうと思ったときに悩む |
- 認証と認可分からなくてモヤモヤ |
- モヤモヤを解消します。 |

---
### TL;DR
- 認証 |
  - 本人性の確認（Authentication） |
- 認可 |
  - リソースに対する利用権限の付与（Authorization） |
---
### 認証（Authentication）
- 相手が誰（何）であるか確認すること

+++

- 例）証明書の確認
- 純粋な認証：確認だけ

![alt](assets/zei_shopping_mynumber.png)

+++
- WHAT YOU ARE
- （自身を提示）
![alt](assets/face.png)
![alt](assets/simon.png)

+++
- WHAT YOU HAVE
- （その人だけが持っているものを提示）
![alt](assets/reji_kaiinsyou_smartphone.png)

+++
- WHAT YOU KNOW
- （その人だけが知っていることを提示）
![alt](assets/computer_password.png)
![alt](assets/mlitifactor.png)

---
### 認可（Authorization）
---
