HumHub Change Log (DEVELOP)
=================


1.4
---

- Enh: GroupPermissionManager - allow to query users by given permission
- Enh: Automatic migrate DB collations from utf8 to utf8mb4
- Enh: Added Icon widget as wrapper class 
- Enh: Moved from bower to npm assets
- Chng: Removed `jquery-placeholder` asset and dependency
- Chng: Removed `atwho` asset and dependency
- Cnng: Removed old IE support
- Fix #2946: Use Yii2 default timezone handling
- Chng #2164: Removed MSN & Google+ social bookmarks during setup
- Enh: Added a user module configuration for setting password strength rules (Baleks)
- Fix #3103 Password recovery links pjax layout issue
- Enh: Added `humhub.ui.widget.Widget.loader()` for default loader functionality
- Enh: Added `humhub.ui.widget.Widget.reload()` in combination with `humhub\widgets\Reloadable` interface
- Enh: Implemented an auto loading mechanism for notification filters (Baleks)
- Enh: Added an option for added additional or override existing OEmbed providers (Baleks)
- Fix: WallEntry::EVENT_AFTER_RUN event not triggered
- Enh: Added `humhub\components\Widget::widgetLayout`
- Enh: Added an option for user to change username (Baleks)
- Enh: Added warning confirmation when module is being deactivated from console (Baleks)
- Enh: Moved 'Default spaces' setting from Basic settings to Space settings (Baleks)
- Enh: Add inviter name to Space Admin Member section (Baleks) 
- Fix #3463 Changed 'Deny Invite' to 'Decline Invite' for space invites (Baleks)
