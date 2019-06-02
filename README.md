# Help @vkmusic_bot be international!
Help to translate [@vkmusic_bot](https://telegram.me/vkmusic_bot) for Telegram!
Do not hesitate to message me [@vkmowner](https://telegram.me/vkmowner) in Telegram if you have any troubles.

## Translation guidelines
1. Download poedit app from https://poedit.net/ 
2. Open or create a translation file for your language (`%%LANG_CODE%%/LC_MESSAGES/vk-music-bot.po`)
3. Select `Catalogue -> Update from POT file...` menu command and choose `vk-music-bot.pot` from the root of the repository
4. Translate and fill the missing translations, validate the existing ones using the following guidelines:
    * Keep `\n` symbols in their places
    * Try to keep the same line lengths as the original English
    * Do not translate commands (e.g. `/song`, `/artist`, `/my`, etc) — let them be in English
    * Do not translate or remove placeholders (e.g. `%s`, `%(channel)s`)
5. Save, commit and send you changes as a pull request to the repo