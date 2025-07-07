# **Andrei Aheyenka**
# **My contact info:**
* **Address:** Belarus, Minsk
* **Phone:** +375 33 3520000
* **E-mail:** andryoha749@gmail.com
* **GitHub:** legolass21
* **Discord to rs_school:** Andrei Agehenka (@legolass21)
* **Telegram:** @Lego_Lass
# **About Me**
# **Skills**
* Python backand
* OOP
* FastAPI
* asyncio
* PostgreSQL, Mysql
* Git/GitHub
# **Code Examples**
```
n, m = [int(i) for i in input().split()]
matrix = [[None for _ in range(m)]for _ in range(n)]
num = 1
for j in range(m + n - 1):
    for i in range(n):
        if j - i in range(m):
            matrix[i][j - i] = num
            num += 1

for row in matrix:
    print(*[str(col).ljust(3) for col in row])
```     
# **Education**

# **Languages**
* **Russian** - native speaker.
* **English** - A2 (B1 in process…)
