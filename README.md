# Custom config tmux for vygush
![Изображение][1]

[1]: screenview.png "Screen View"

## Старт
Установка:
```bash
brew install tmux
```

Загружаем менеджер плагинов:
```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

Создаем директорию под конфиг:
```bash
mkdir ~/.config/tmux
```

Загружаем конфиг:
```bash
git clone https://github.com/VYGUSH/vygtmux ~/.config/tmux
```

Чтобы забрать конфиг в свой репозиторий:
```bash
rm -rf ~/.config/tmux/.git
```

Инициализируем конфиг
```bash
tmux source ~/.config/tmux/tmux.conf
```


## hotckey 
`ctrl + b`
>`I` - Для установки плагинов tpm  
`c` - create window  
`n` - swap window up  
`p` - swap window down  
`0` - select 0 window  
`1` - select 1 window  
`2` - select 2 window  
`&` - kill window  
`%` - split window horizontally  
`"` - split window vertically  
`стрелки` - переключение между сплитами  
`q` - отображение номеров окон  
`z` - сделать зум на текущем окне  
`!` - выделить в отдельное окно  
`x` - удалить текущее сплитнутое окно  
`s` - открыть менеджер сессий tmux  
`w` - менеджер окон и сессий  
`tmux new -s name_session`   - создать новую сессию
`tmux attach -t name_session` - открыть запущенную сессию


https://tmuxcheatsheet.com - all hotckey
