# Multi Roblox — two Roblox windows on one PC

**[Download MultiRoblox.exe](https://github.com/rbmng/multi-roblox/releases/latest)** · Windows 10 and 11 · free, no install, no key

Normally Windows runs only one Roblox: open a second one and the first closes. MultiRoblox removes that limit, so two Roblox windows run side by side, each under its own account.

## How to use

1. Close every Roblox window.
2. Run `MultiRoblox.exe`. Its window says it is working.
3. Open the first game as usual from the Roblox website.
4. Open the second game under another account (another browser or browser profile).
5. Keep MultiRoblox open while you play.

The same account can't play in two windows: Roblox kicks the first one. Use two different accounts.

## How it works

Every Roblox client checks at startup whether another one is already running, using a Windows object named `ROBLOX_singletonMutex`. MultiRoblox takes that object first, so no window thinks it is the only one and they stop closing each other. The Roblox client itself is not modified: no game files are changed and game memory is never touched.

- Up to two Roblox windows. A third one is closed, with a message explaining why.
- Windows that were open before MultiRoblox started are never touched.
- No accounts, no key, no internet.

## Need more windows?

[Roblox Manager](https://rbmng.lol/en/) is the full version: all your accounts in one list, one-click login without a password, as many windows as you need, auto-rejoin after a disconnect, anti-AFK and macros. It also imports accounts from the old Roblox Account Manager (`AccountData.json`).

## Windows SmartScreen warning

The program is new and not signed with a paid certificate, so SmartScreen may say "Windows protected your PC". Click "More info", then "Run anyway". You can scan the file with any antivirus before running it.

---

# Мульти-Роблокс — два окна Roblox на одном ПК

**[Скачать MultiRoblox.exe](https://github.com/rbmng/multi-roblox/releases/latest)** · Windows 10 и 11 · бесплатно, без установки и ключа

Обычно Roblox на компьютере открывается только один: запустили второй — первый закрылся. MultiRoblox снимает это ограничение — два окна работают рядом, каждое под своим аккаунтом.

## Как пользоваться

1. Закройте все окна Roblox.
2. Запустите `MultiRoblox.exe` — в окне программы будет написано, что она работает.
3. Откройте первую игру как обычно, с сайта Roblox.
4. Откройте вторую игру под другим аккаунтом (в другом браузере или профиле браузера).
5. Не закрывайте MultiRoblox, пока играете.

Один и тот же аккаунт в двух окнах не получится: Roblox выкинет первое окно. Нужны два разных аккаунта.

## Как это работает

Каждый клиент Roblox при запуске проверяет, нет ли уже открытого, по объекту Windows `ROBLOX_singletonMutex`. MultiRoblox занимает его заранее, и окна перестают закрывать друг друга. Сам клиент Roblox не меняется: ни правки файлов игры, ни вмешательства в её память.

- До двух окон Roblox. Третье программа закроет и скажет почему.
- Окна, открытые до запуска MultiRoblox, она не трогает.
- Без аккаунтов, ключа и интернета.

## Нужно больше окон?

[Roblox Manager](https://rbmng.lol/) — полная версия: все аккаунты в одном списке, вход в один клик без пароля, сколько угодно окон, перезаход после вылета, анти-АФК и макросы. Переносит аккаунты из старого Roblox Account Manager (`AccountData.json`).

## Windows предупреждает о программе

Программа новая и не подписана платным сертификатом, поэтому SmartScreen может показать «Windows защитила ваш компьютер». Нажмите «Подробнее» → «Выполнить в любом случае». Файл можно проверить любым антивирусом до запуска.
