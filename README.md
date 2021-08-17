# Telegram to Notion

Pushes posts (that contain links) from telegram to notion block.

```
npm start
```

## Environment variables
To make it work create `.env` file in project folder. 

```
NOTION_ACCESS_TOKEN = <your_notion_access_token>    #https://www.notion.so/my-integrations
BOT_TOKEN = <your_bot_token>    #Get it with botFather
BLOCK_ID = <your_block_id>   #id of desired block. Just google how to get it.
CHAT_ID_1 = <your_chat_id>   #Chat id's is additional white list. You can choose users or groups that can use that bot.
CHAT_ID_2 = <your_chat_id>
```
