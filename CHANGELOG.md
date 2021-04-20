## In development
### Bugfixes
- `executeFor` functions will no longer fail with an exception if a function scheduled to be called by the local user throws.


## 1.0.2
### New API endpoints
- Added `executeForOthers` and `executeForOtherGMs` that execute for all users/all GMs except the local client.

### Bugfixes
- `executeAsUser` and `executeForUsers` didn't execute locally if the id of the current user was passed in as recipient.
- `executeForEveryone` and `executeForAllGMs` now execute locally as well, as they should


## 1.0.1
### New features
- Added support for game systems

### Compatibility
- Add support for Foundry 0.8.1


## 1.0.0
### Initial release
