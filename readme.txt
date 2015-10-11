=== Simple Comment Editing ===
Contributors: ronalfy
Tags: ajax, comments,edit comments, edit, comment, admin
Requires at least: 4.1
Tested up to: 4.3
Stable tag: 1.8.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Simple Comment Editing for your website.

== Description ==

Simple Comment Editing gives anonymous users the ability to edit and/or delete their comments for a period of time.

[youtube https://www.youtube.com/watch?v=KfKTVzEdClw]

YouTube video review from <a href="http://www.wpbeginner.com/plugins/allow-users-edit-comments-wordpress/">WPBeginner</a>.

Simple Comment Editing features:
<ol>
<li>No options. Install the plugin. It just works.
<li>Anonymous users can edit comments for 5 minutes.</li>
<li>No styling is necessary. For advanced customization, see the "Other Notes" section.</li>
<li>Advanced customization can be achieved using filters.</li>
</ol>

<h3>Spread the Word</h3>
If you like this plugin, please help spread the word.  Rate the plugin.  Write about the plugin.  Something :)

<h3>Translations</h3>
<ul>
<li>Arabic - Thanks Soufiane Sabiri.</li>
<li>Czech - Thanks <a href="http://blog.doprofilu.cz/">Petr Baloun</a>.</li>
<li>Dutch (Netherlands) - Thanks <a href="https://github.com/senlin">Senlin</a></li>
<li>French (France) - Thanks <a href="http://wordpress.org/support/profile/colin101">colin101</a>.</li>
<li>German - Thanks Wilfried Kahrs.</li>
<li>Latvian - Thanks Kaspars.</li>
<li>Norwegian Bokmål - Thanks Jan Hagen.</li>
<li>Norwegian Nynorsk - Thanks Jan Hagen.</li>
<li>Persian - Thanks <a href="http://www.wordpress98.com/">Ali HajiMohamadi</a>.</li>
<li>Portuguese (European) - Thanks <a href="https://twitter.com/porreirinha">Marco Pereirinha</a>.</li>
<li>Romanian (with diacritics) - Thanks Vasile Ruscior.</li>
<li>Russian - Thanks Nataliya Zav'yalova (Наталия Завьялова).</li>
<li>Serbian - Thanks <a href="https://twitter.com/lanche86">Milan Ivanovic</a>.</li>
<li>Spanish - Thanks Google Translate :P</li>
<li>Swedish - Thanks Håkan Persson.</li>
</ul>

If you would like to contribute a translation, please leave a support request with a link to your translation  or <a href="http://www.ronalfy.com/contact/">get in touch</a>.  If you would like to update an existing translation, please visit <a href="https://poeditor.com/join/project?hash=b65f6d06a1d423e3d4713a9f4a304d5c">POEditor.com and request access</a>.

You are welcome to help us out and <a href="https://github.com/ronalfy/simple-comment-editing">contribute on GitHub</a>.

== Installation ==

1. Just unzip and upload the "simple-comment-editor" folder to your '/wp-content/plugins/' directory
2. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==
= Why doesn't this plugin come with any styles? =
It's impossible to style an inline comment editor for every theme.  We've included basic HTML markup that is easily stylable to fit your theme.

= Where are the options? =
No options :) - Just simple comment editing.

= How do I customize this plugin? =
For advanced options, please see the <a href="https://github.com/ronalfy/simple-comment-editing#wordpress-filters">SCE Filter/Action reference</a>. 



== Screenshots ==

1. Edit button and timer.
2. Textarea and Save/Cancel buttons.

== Changelog ==

= 1.8.0 =
* Released 2015-10-11
* Logged in users who log out can no longer edit comments
* Added Delete button
* Updated translations for language packs

= 1.7.1 =
* Released 2015-09-26
* Fixed Epoch+SCE user logged in dilemma 

= 1.7.0 =
* Released 2015-09-20
* Fixed timer issue on many sites. New JS hook for allowing customization of output.

= 1.6.7 =
* Released 2015-09-20
* Fixing PHP bug declaring fatal error for multiple class instances. Props volresource.

= 1.6.5 =
* Released 2015-09-17
* Fixing strings that are not replaced in the timer. Sorry I didn't catch this error.

= 1.6.1 =
* Released 2015-09-16
* Fixed undefined JavaScript errors in timer. Sorry about that.

= 1.6.0 =
* Released 2015-09-16
* Added filter for custom timer output
* Added support for logged in users to bypass cookie checks
* Added support for custom post types

= 1.5.5 =
* Released 2015-09-07
* Fixed return call to be better compatible with third-party customizations
* Added Latvian translation
* Revised WP Ajaxify Comments integration

= 1.5.3 =
* Released 2015-08-23
* Fixing PHP 5.2 error

= 1.5.1 =
* Released 2015-08-19
* Forgot to update minified JS

= 1.5.0 =
* Released 2015-08-19
* Adding hooks for the capability to add extra comment fields.
* Added Epoch compatibility.
* Added JS events so third-party plugins can integrate with SCE.

= 1.3.3 =
* Released 2015-07-22
* Fixing JavaScript error that prevented editing if a certain ID wasn't wrapped around a comment.

= 1.3.2 =
* Released 2015-07-13
* Added filter sce_can_edit for more control over who can or cannot edit a comment.
* Updated translations (Arabic, Dutch, French, German, Norwegian, Persian, Portuguese, Romanian, Russian, Serbian, Spanish, and Swedish).

= 1.3.1 =
* Released 2015-06-26
* Fixed debug error that stated there were two few arguments when there was a percentage sign (%) in a comment. Thank you <a href="https://github.com/ronalfy/simple-comment-editing/issues/7">bernie-simon</a>.

= 1.3.0 =
* Released 2015-06-18
* Improved timer internationalization to accept languages with plurality variations (e.g., Russian)
* Added Russian translation
* Improved the timer to be significantly more accurate
* Added filters to the SCE HTML in order to add custom attributes
* Improved inline documentation
* Added smooth scrolling to the comment after a page load

= 1.2.4 =
* Updated 2015-04-19 - Ensuring WordPress 4.2 compatibility
* Released 2015-02-04
* Added status error message area
* Added filter for custom error messages when saving a comment

= 1.2.2 =
* Updated 2014-12-11 - Ensuring WordPress 4.1 compatibility 
* Released 2014-09-02
* Added Romanian language
* Added French language
* Added Dutch language
* Added better support for cached pages
* Fixed a bug where cached pages showed other users they could edit a comment, but in reality, they could not (saving would have failed, so this is not a severe security problem, although upgrading is highly recommended).

= 1.2.1 =
* Released 2014-08-27
* Added Arabic and Czech languages
* Ensuring WordPress 4.0 compatibility

= 1.2.0 =
* Released 2014-05-13
* Added Swedish translation
* Added better support for internationalization
* Removed barrier for admins/editors/authors to edit comments

= 1.1.2 =
* Released 2014-04-14
* Added support for WP-Ajaxify-Comments

= 1.1.1 =
* Released 2014-02-06
* Fixed an error where users were erroneously being told their comment was marked as spam

= 1.1.0 =
* Released 2014-02-05
* Added JavaScript textarea save states when hitting the cancel button
* Allow commenters to delete their comments when they leave an empty comment

= 1.0.7 =
* Released 2013-09-15
* Added Persian translation file

= 1.0.6 =
* Released 2013-09-12
* Added Serbian translation file

= 1.0.5 =
* Released 2013-09-12
* Added Portuguese translation file

= 1.0.4 =
* Released 2013-09-06
* Added German translation file

= 1.0.3 =
* Released 2013-08-23
* Fixed slashes being removed in the plugin

= 1.0.2 =
* Released 2013-08-05
* Fixed an internationalization bug and added Norwegian translations.

= 1.0.1 =
* Released 2013-08-05
* Improved script loading performance

= 1.0 =
* Initial release.

== Upgrade Notice ==

= 1.8.0 =
Added delete button.

== Customization ==

For advanced options, please see the <a href="https://github.com/ronalfy/simple-comment-editing#wordpress-filters">SCE Filter/Action reference</a>. 