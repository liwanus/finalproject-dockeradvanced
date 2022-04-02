# finalproject-dockeradvanced
final project docker advanced
1. download file nginx.conf, database  dan web dari github 
2. extract file tsb dilocal direktori pc
3. create dockerfile.web
4. create dockerfile.nginx
5. create file YAML docker-compose.yml
6. before compose run edit dulu file hosts yang ada di C:\Windows\System32\drivers\etc
add baris ini:
xx.xx.xx.x www.domainsaya.local pma.domainsaya.local
7. buka cmd dan masuk ke direktori final project yang dimana terdapat file docker compose dkk
8. jalankan comand: docker-compose up
9. pastikan container sudah berjalan normal semua
10. test http://pma.domainsaya.local dan lakukan config database
11. test web http://www.domainsaya.local/
