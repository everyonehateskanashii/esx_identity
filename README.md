# esx_identity
#### *Reskin of esx_identity*

This is my reskin of esx_identity, you can find original file here : [original esx_identity](https://github.com/ESX-Org/esx_identity) 

![Video](https://i.imgur.com/VPQLopO.png)

## Requirements
* Dependencies For Full Functionality
  * [esx_skin](https://github.com/ESX-Org/esx_skin)
  * [esx_policejob](https://github.com/ESX-Org/esx_policejob)
  * [esx_society](https://github.com/ESX-Org/esx_society)
  
## Installation
- Import `esx_identity.sql` in your database
- Add this to your `server.cfg`:

```
start esx_identity
```

- If you are using esx_policejob or esx_society, you need to enable the following in the scripts' `config.lua`:
```Config.EnableESXIdentity          = true```

### Commands
```
/register
/charlist
/charselect
/chardel
```

## Support

You can ask for help on dm:

* Kanashii#9054

## License
[MIT](https://choosealicense.com/licenses/mit/)
