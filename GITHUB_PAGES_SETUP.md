# Как опубликовать сайт на GitHub Pages (5–10 минут, кликами)

Репозиторий и аккаунт — твои. Claude файлы подготовил, публикуешь ты.

## Что уже готово в папке `website/`
- `index.html` — лендинг
- `privacy-ru.html` — политика конфиденциальности (RU, для листинга RuStore)
- `privacy-bg.html` — заготовка BG/EU (черновик, не для публикации)
- `screenshots/` — сюда положи 3 PNG: `home.png`, `maya.png`, `hive.png`
  (те три скриншота: главный экран, чат с Маей, карточка улья)

## Шаг 0. Добавь скриншоты
Скопируй три PNG в `website/screenshots/` и назови ровно:
`home.png`, `maya.png`, `hive.png` (вёрстка уже на них ссылается).

## Шаг 1. Создай репозиторий
1. Зайди на github.com под своим аккаунтом (или заведи — бесплатно).
2. Справа вверху «+» → **New repository**.
3. Repository name: **beejournal-ru**
4. Public (обязательно для бесплатного Pages).
5. Галочку «Add a README» НЕ ставь. → **Create repository**.

## Шаг 2. Загрузи файлы
1. На странице пустого репозитория → ссылка **uploading an existing file**.
2. Перетащи ВСЁ содержимое папки `website/` (index.html, privacy-ru.html,
   privacy-bg.html, папку screenshots). Важно: заливай сами файлы, не папку
   `website` целиком — index.html должен оказаться в корне репозитория.
3. Внизу → **Commit changes**.

## Шаг 3. Включи Pages
1. В репозитории → вкладка **Settings** → слева **Pages**.
2. Source: **Deploy from a branch**.
3. Branch: **main**, папка **/ (root)** → **Save**.
4. Подожди 1–2 минуты, обнови страницу.

## Готово
Адрес сайта: `https://<твой-логин>.github.io/beejournal-ru/`
Политика для RuStore: `https://<твой-логин>.github.io/beejournal-ru/privacy-ru.html`

Эту вторую ссылку вставляешь в поле «Политика конфиденциальности» при заполнении
листинга в RuStore Console.

## Обновить сайт потом
Любой файл → карандаш (Edit) прямо на github.com → Commit. Изменения появятся
на сайте за минуту. Скриншоты/тексты меняются так же.

## Позже (не сейчас)
- Свой домен (beejournal.ru) прикручивается в Settings → Pages → Custom domain.
- Отдельный репозиторий `beejournal-bg` — когда дойдём до болгарского релиза.
- Блок «Поддержать разработку» с ссылкой ЮKassa — после публикации в RuStore.
