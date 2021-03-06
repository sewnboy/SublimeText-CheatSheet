# Sublime Text Plugins


## [ASCII Decorator](https://github.com/viisual/ASCII-Decorator)

**Description** : Permet de créer des blocs de texte ASCII pour plus de lisibilité.

**Shortcut** : `Alt + Shift + K`, après avoir sélectionné le texte à modifier.

**Installation** : 
* Installer la police Univers
* Code à placer dans le fichier de préférences utilisateur : `Preferences > Package Setting > ASCII Decorator > Setting User` :

```json
"ascii_decorator_font": "univers",
```


## [DockBlockr](https://github.com/Warin/Sublime/tree/master/DocBlockr)

**Description** : Crée un block de commentaire au dessus d'une fonction en php, js, ... Exemple :

```php
/**
 * [function description]
 * @return [type] [description]
 */
```

**Shortcut** : `/**` au dessus d'une fonction, puis `entrée` ou `shift`.

**Installation** : Via Package control `Preferences > Package Control`, puis `Package Control: Install Package`.


## [CodeFormatter](https://github.com/akalongman/sublimetext-codeformatter)

**Description** : Nettoie et organise le code aux normes. Fonctionne pour PHP, JS, CSS, HTML, Python. Ne fonctionne pas encore pour Blade.

**Shortcut** :  `Ctrl + Alt + F`.

**Installation** : Via Package control `Preferences > Package Control`, puis `Package Control: Install Package`.



## [SassBeautify](https://github.com/badsyntax/SassBeautify)

**Description** : Nettoie et organise le code SASS. Il faudrait réflechir à une éventuelle inclusion dans `CodeFormatter`.

**Shortcut** : `Ctrl + Alt + P`, puis sélectionner `SassBeautify`.

**Installation** : Via Package control `Preferences > Package Control`, puis `Package Control: Install Package`.


## Trim White Spaces

**Description** : Cette option permet de supprimer tous les espaces en fin de ligne automatiquement à chaque sauvegarde de fichier.

**Shortcut** : Automatique à chaque sauvegarde de fichier (`Ctrl + S`).

**Installation** : 
Code à placer dans le fichier de préférences utilisateur : `Preferences > Settings - User` :

```json
"trim_trailing_white_space_on_save": true,
```
