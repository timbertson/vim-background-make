Using:
------

When you would use `:make`, use `:Make` instead. Simple!

Customising:
------------

currently the only settable option is changing the notification
command, by setting `g:background_make_notify_cmd`

The default value is:

	notify-send "$msg" "Vim background make"

`$msg` will be substitited at run time for either "Success!" or "Failed.".
If you don't want any notifications, you can simply set it to "echo" or
something similarly ineffectual.
