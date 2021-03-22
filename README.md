# MyBB-Plugin-Custommenu

A plugin for MyBB 1.8.x to easily manage the forums toplinks menu

Requires the PluginLibrary plugin* (*included in pkg)


Still todo:

- provide, create further overall localization support
- write more descriptive documentation to explain how to use the the menu items as is on title input or say rather if desired to say opt instead to not apply title input on the menu inserts and instead learn to use just like the provided localized default menu items in css stylesheet to translate such items and explain further how in say future documentation one could then do such for thier custom menu items

ie:

/** English **/
[title="portal"]:lang(en):after {
	content: 'Portal';
	vertical-align: middle;
}

[title="search"]:lang(en):after {
	content: 'Search';
	vertical-align: middle;
}

[title="memberlist"]:lang(en):after {
	content: 'Memberlist';
	vertical-align: middle;
}

[title="calendar"]:lang(en):after {
	content: 'Calendar';
	vertical-align: middle;
}

[title="help"]:lang(en):after {
	content: 'Help';
	vertical-align: middle;
}

/** Espanol **/
[title="portal"]:lang(es):after {
	content: 'Portal';
	vertical-align: middle;
}

[title="search"]:lang(es):after {
	content: 'Búsqueda';
	vertical-align: middle;
}

[title="memberlist"]:lang(es):after {
	content: 'Lista de miembros';
	vertical-align: middle;
}

[title="calendar"]:lang(es):after {
	content: 'Calendario';
	vertical-align: middle;
}

[title="help"]:lang(es):after {
	content: 'Ayuda';
	vertical-align: middle;
}

/** French **/
[title="portal"]:lang(fr):after {
	content: 'Portail';
	vertical-align: middle;
}

[title="search"]:lang(fr):after {
	content: 'Chercher';
	vertical-align: middle;
}

[title="memberlist"]:lang(fr):after {
	content: 'Liste des membres';
	vertical-align: middle;
}

[title="calendar"]:lang(fr):after {
	content: 'Calendrier';
	vertical-align: middle;
}

[title="help"]:lang(fr):after {
	content: 'Aider';
	vertical-align: middle;
}

/** Italian **/
[title="portal"]:lang(it):after {
	content: 'Portale';
	vertical-align: middle;
}

[title="search"]:lang(it):after {
	content: 'Ricerca';
	vertical-align: middle;
}

[title="memberlist"]:lang(it):after {
	content: 'Lista dei membri';
	vertical-align: middle;
}

[title="calendar"]:lang(it):after {
	content: 'Calendario';
	vertical-align: middle;
}

[title="help"]:lang(it):after {
	content: 'Aiuto';
	vertical-align: middle;
}

/** German **/
[title="portal"]:lang(de):after {
	content: 'Portal';
	vertical-align: middle;
}

[title="search"]:lang(de):after {
	content: 'Suche';
	vertical-align: middle;
}

[title="memberlist"]:lang(de):after {
	content: 'Mitgliederliste';
	vertical-align: middle;
}

[title="calendar"]:lang(de):after {
	content: 'Kalender';
	vertical-align: middle;
}

[title="help"]:lang(de):after {
	content: 'Hilfe';
	vertical-align: middle;
}

/** Polish **/
[title="portal"]:lang(pl):after {
	content: 'Portal';
	vertical-align: middle;
}

[title="search"]:lang(pl):after {
	content: 'Szukaj';
	vertical-align: middle;
}

[title="memberlist"]:lang(pl):after {
	content: 'Lista członków';
	vertical-align: middle;
}

[title="calendar"]:lang(pl):after {
	content: 'Kalendarz';
	vertical-align: middle;
}

[title="help"]:lang(pl):after {
	content: 'Wsparcie';
	vertical-align: middle;
}
