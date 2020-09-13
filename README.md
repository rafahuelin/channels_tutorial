sudo systemctl status redis

Now that we have a channel layer, let’s use it in ChatConsumer. Put the following code in chat/consumers.py, replacing the old code: