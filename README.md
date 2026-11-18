# skills

Моя коллекция навыков. Каждый навык лежит в своей папке и описан в `SKILL.md`.

## Ясный и живой текст

`human-prose` помогает писать рабочие статьи, письма, записки для руководителей, презентации и рассказы. Он выстраивает главный тезис, связывает разделы и абзацы и помогает сохранить авторский голос. В основе пять книг по письму и редактуре, в том числе «Принцип пирамиды Минто».

[Инструкция навыка](skills/human-prose/SKILL.md) · [Примеры работы со структурой](skills/human-prose/references/structure-examples.md) · [Книги и главы](skills/human-prose/references/sources.md)

### Установка в Codex

<a href="https://chatgpt.com/codex/open-app?mode=codex&amp;q=%24skill-installer%20%D0%A3%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%B8%20%D0%BD%D0%B0%D0%B2%D1%8B%D0%BA%20human-prose%20%D0%B8%D0%B7%20https%3A%2F%2Fgithub.com%2Fikratkiy%2Fskills%2Ftree%2Fmain%2Fskills%2Fhuman-prose%20%D1%87%D0%B5%D1%80%D0%B5%D0%B7%20Git%20%28--method%20git%29."><img alt="Открыть установку в Codex" src="assets/open-in-codex.png" width="179" height="35"></a>

Кнопка откроет настольный Codex с готовым запросом на установку. Отправьте его в чате. Если приложение не открылось, вставьте запрос вручную.

```text
$skill-installer Установи навык human-prose из https://github.com/ikratkiy/skills/tree/main/skills/human-prose через Git (--method git).
```

После установки попробуйте в новом чате.

```text
Используй $human-prose, чтобы выстроить мысль, связать абзацы и сохранить мой голос.
```

<details>
<summary>Установка как плагина через Codex CLI</summary>

```sh
codex plugin marketplace add ikratkiy/skills
codex plugin add human-prose@ikratkiy-skills
```

[Документация Codex по каталогам плагинов](https://developers.openai.com/plugins/build/plugins#add-a-marketplace-from-the-cli)

</details>
