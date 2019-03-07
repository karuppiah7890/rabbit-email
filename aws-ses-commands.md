Some aws ses commands

To send a simple email :

```
aws ses send-email --from $FROM_ADDRESS \
  --to $TO_ADDRESS --subject hello --text hello
```