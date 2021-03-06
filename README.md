# The Digital Survival Overlay

### app-misc/nixnote ###

An open source Evernote clone for Linux. I will be working on releasing *both* versions in the Portage tree.

### media-video/obs-studio* ###

`USE=pulseaudio` is required to capture audio. PulseAudio is the only available method to capture audio in OBS Studio.

QT5 is required for OBS Studio. QT5 is currently only available on unstable architectures (~arch). To use OBS Studio on stable to add QT5 to `/etc/portage/package.keywords`

If you would prefer to use the live ebuild instead of the release. You will need to add obs-studio to  `/etc/portage/package.keywords`.

A file for symlinking is provided in the Documentation directory:

<pre>
ln -s <path to overlay>/Documentation/package.keywords/obs-studio-live /etc/portage/package.keywords/obs-studio-live
</pre>

<sup><small><small>* This ebuild was based on [saintdev's ebuild](https://github.com/saintdev/obs-studio-overlay).</small></small></sup>

### sys-auth/ppp-pam ###

The Perfect Paper Passwords Pluggable Authentication Module is a PAM module that enables two step verification using one time passwords.

See the [source code repository](https://github.com/DigitalSurvival/ppp-pam#introduction) for additional information.

### Anaconda overlay packages ###

All works in progress.

### A bunch of modern text editors ###

* app-misc/atom
* app-misc/brackets
* app-misc/lighttable
* app-misc/lighttable-bin
* app-misc/vscode

All works in progress. Help appreciated.
