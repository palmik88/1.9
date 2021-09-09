### Создаем пользователя, добавляем правило в sudoers.d/228:

* sudo adduser test
* sudo touch /etc/sudoers.d/228
* sudo visudo -f /etc/sudoers.d/228

![66ea3dec36a2937c1dcf949361edde7a](https://user-images.githubusercontent.com/71388963/132773145-b200ae5c-bab2-4bb1-82c2-5b879d1b4eca.png)
### Переключаемся на пользователя test, копируем skukozh, делаем chmod 550, копируем ls.
* su - test
* sudo chmod 550 skukozh
* cp /bin/ls .
 
![f57cde93be9ee8357e4a50129ccb2cfa](https://user-images.githubusercontent.com/71388963/132773192-72f05e38-8e5d-479d-9b5a-f242b8ca55ca.png)
### ДО запуска skukozh - ls работает, ПОСЛЕ - нет
![41bf5ff56616315a8af9a166ab6692d5](https://user-images.githubusercontent.com/71388963/132773240-0484bdb2-992a-4a9f-8478-f76f2b7a4e1f.png)
