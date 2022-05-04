##users テーブル

| Column | Type       | Options                        |
| ------ | ---------- | ------------------------------ |
| email   | references | null: false, foreign_key: true |
| g  | references | null: false, foreign_key: true |



##prototypes テーブル

| Column | Type       | Options                        |
| ------ | ---------- | ------------------------------ |
| user   | references | null: false, foreign_key: true |
| group  | references | null: false, foreign_key: true |





##comments テーブル

| Column | Type       | Options                        |
| ------ | ---------- | ------------------------------ |
| user   | references | null: false, foreign_key: true |
| group  | references | null: false, foreign_key: true |