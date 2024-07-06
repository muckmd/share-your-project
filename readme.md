# Привет 
## Это мой первый _публичный_ файл 
### Здесь шпаргалка по первому контакту с Git 

---


1. *_mkdir second-project_* (от англ. *_make directory, «создать директорию»_*) — создай папку с именем second-project в текущей папке.
2. *_git init_* сделать папку репозиторием
3. *_touch index.html (англ. touch, «коснуться»)_* — создай файл index.html в текущей папке
4. *_git add_* Подготовить файлы к сохранению
5. *_git commit -m 'Мой первый коммит!'_* Выполнить коммит
6. *_ls -la .ssh/_* проверить список SSH ключей
7. Если нет - *_ssh-keygen -t ed25519 -C "электронная почта, к которой привязан ваш аккаунт на GitHub"_*
8. > Enter a file in which to save the key (C:\Users\<имя_пользователя>\.ssh\):*_[Press enter]_*
9. *_ls -a ~/.ssh_* проверить список SSH ключей, _можно трогать только с расширением .pub!_
10. *_clip < ~/.ssh/id_ed25519.pub_*  скопировать содержимое ключа в буфер обмена
11. На GitHub во вкладке нужного проекта выбрать настройки => Deploy keys => Add deploy key => *вставить из пункта выше информацию* (РАЗРЕШИТЬ РЕДАКТИРОВАНИЕ! ГАЛОЧКА!)
12. Перейдите на страницу удалённого репозитория, выберите тип SSH и *скопируйте URL*
13. В нужной папке (проверить pwd) прописать *_git remote add origin _git@github.com:%ИМЯ_АККАУНТА%/first-project.git _(вставить с github)_* #вставить на Windows Ctrl+Shift+V или правой кнопкой мыши
14. Убедиться, что репозитории связаны — *_git remote -v_*
15. Вы уже прошли весь «цикл коммита»: 
* подготовили файлы с помощью git add
* закоммитили их с комментарием командой git commit -m. 
* загрузить содержимое локального репозитория на GitHub - команда *_git push_* 
	В первый раз эту команду нужно вызвать с флагом -u и параметрами origin (имя удалённого репозитория) и main или master (название текущей ветки). 
	Флаг -u свяжет локальную ветку с одноимённой удалённой.

---


# Вуаля, вы восхитительны! 


 





