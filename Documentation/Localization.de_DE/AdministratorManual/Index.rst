.. ==================================================
.. FOR YOUR INFORMATION
.. --------------------------------------------------
.. -*- coding: utf-8 -*- with BOM.

.. include:: ../../Includes.txt


.. _admin-manualDE:

Administrator Handbuch
======================

Zielgruppe: **Administratoren**

.. only:: html

	.. contents:: Within this page
		:local:
		:depth: 3

Voraussetzungen
---------------

.. caution::
	Auf der Homepage muss jQuery JavaScript Framework global verfügbar sein, weil das Frontend Plugin jQuery benutzt.
	Ebenso wie das jQuery Validation Plugin.

Installation
------------

1) Laden und installieren Sie die Erweiterung über den Erweiterungsmanager (extKey: datec_blog).
2) Fügen Sie eine Seite vom Typ "Systemordner" für die Blog-Inhalte hinzu, oder besser jeweils einen für Blog-Einträge, Kategorien, Schlüsselwörter und Kommentare. Notieren Sie sich die Seiten-Id/s (PID) des/der Ordners.
3) Sehen Sie sich das Kapitel "Konfiguration" dieses Dokuments an und folgen Sie den Schritten zur minimalen Konfiguration.
4) Fügen Sie das Haupt Plugin (DatecBlog - Blog) und optionale Plugins mit folgenden Schritten auf einer beliebigen Seite ein.

Plugin einfügen
---------------

1) Erstellen Sie ein neues Inhaltselement, wählen Sie: "Plugins" -> "General Plugin"

.. figure:: ../../Images/plugin_01.jpg
	:width: 700px
	:alt: insert plugin

	Inhaltslement vom Typ "Plugin" einfügen


2) Wählen Sie eine der Ansichtsformen um ihren Blog einzurichten.

.. figure:: ../../Images/plugin_02.jpg
	:width: 700px
	:alt: modules

	Ansichtsformen auswählen


Blog
^^^^

Zeigt die Listenansicht und Einzelansicht von Blogeinträgen mit Kommentaren. Dieses Plugin ist mindestens benötigt.

Kategorien
^^^^^^^^^^

Zeigt die Kategorien als Baum, anklickbar zum filtern.

Archiv
^^^^^^

Generiert ein Archiv aus Blogeinträgen in der Listenansicht, angezeigt als Baum aus Jahr - Monat - Tag, anklickbar zum filtern.

Schlüsselwörter
^^^^^^^^^^^^^^^

Zeigt Schlüsselwörter als Wolke oder Liste, abhänging von der TypoScript Konfiguration des Plugins, anklickbar zum filtern.