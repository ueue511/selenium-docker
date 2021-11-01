[Python]docker-selenium環境構築

■ selenium ・・・ 3.141.0

■ 立ち上げ
- docker-compose build --no-cache
- docker-compose up -d

■ コンテナ内部に入る
- docker exec -it ['Pythonがあるコンテナ名'] bash 

■ .py実行
- python ['ファイル名'].py
