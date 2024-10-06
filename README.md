latest Manjaro Deepin ISO image download<br>
See: https://github.com/wiwyil2tr/manjarodeepiniso/releases

## Extracting

The isos bigger than certain threshold are provided in multipart zip files because of the filesize restriction of github. To extract the iso, download all the zipped parts, and open the zip file with ``file-roller``, ``engrampa`` or ``7z``.

or run

```
cat manjaro-deepin-24.0.1-241005-linux61.iso.z** > manjaro-deepin.zip
unzip manjaro-deepin.zip

```

This should automatically extract the iso from all the files.

## Latest version(24.1.0): 241005
New Manjaro Deepin iso image released with new DDE Desktop

![Screenshot_20231005_173637](https://github.com/wiwyil2tr/manjarodeepiniso/assets/108447154/2750c336-4575-4b6e-aa5c-c26a074a3fce)
![Screenshot_20231005_173727](https://github.com/wiwyil2tr/manjarodeepiniso/assets/108447154/83af4cf5-e162-4aa9-a051-ed4710600ee0)
![Screenshot_20231005_173811](https://github.com/wiwyil2tr/manjarodeepiniso/assets/108447154/f404426c-fc12-4303-b746-22bedac54639)

* Update Manjaro system to the latest
 * New Deepin Desktop Environment (Deepin 23)
 *  Fixed problem where the launcher sometimes can't display normally.

## Notice
* Due to DDE automatically mounting any new partition, the partitioning tool in the Calamares installer is not usable. Therefore, it is necessary to manually use GParted from the livecd to create partitions before installation, and then select the partitions to mount in the installer for installation.

* The password of the live user "manjaro" is `manjaro`

![Screenshot_2024-10-06_11-05-08](https://github.com/user-attachments/assets/f67acfa0-ff48-4b19-b692-f0d04e5697c3)

![Screenshot_2024-10-06_11-04-06](https://github.com/user-attachments/assets/5c9bd83c-3b68-4707-973d-f2a51f21e084)

