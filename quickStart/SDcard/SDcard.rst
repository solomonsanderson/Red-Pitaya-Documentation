.. _prepareSD:

###############
Prepare SD card
###############


***********
OS Versions
***********

==============
Nightly Builds
==============

You can now download Nightly Builds for your Red Pitaya!

The nightly builds are snapshots of the development activity for upcoming Red Pitaya OS releases and include the newest features and bug fixes scheduled for the official releases. These builds are made available to make it easier for users to test their setup for potential issues with an upcoming release or to test new features and provide feedback on ways to improve them before they are released as a Beta OS or Stable version.

We have decided to release the nightly builds to ensure that our codebase stays healthy and to shorten the time that it takes to fix some of the reported issues or implement some new features that were reported as suggestions for improvement.

As these builds are snapshots of the latest code, it is more likely you will encounter an issue compared to the stable releases. If you have encountered an issue, please report it to support@redpitaya.com so that our developers can review the issue and make any needed fixes.

**Nightly Builds ecosystem**: 

   - |nightly builds|  -  `NIGHTLY CHANGELOG <https://downloads.redpitaya.com/downloads/Unify/nightly_builds/CHANGELOG.txt>`_

Ecosystem builds run every Saturday night.

.. note::

   These versions may be unstable and could result in misconfigurations or measurement data loss.
   We recommend you use them only for testing or in cases where you have reported a bug or requested a feature and our technical staff is instructing you to do so.


.. |nightly builds| raw:: html

   <a href="https://downloads.redpitaya.com/downloads/Unify/nightly_builds/" target="_blank">Red Pitaya downloads</a>

==========
Unified OS
==========

This version of the ecosystem includes a build for all boards.

Boards currently supported:

   - STEMlab 125-10
   - STEMlab 125-14
   - STEMlab 125-14-Z7020
   - STEMlab 125-14 4-Input
   - SDRlab 122-16
   - SIGNALlab 250-12

Unify ecosystem now includes primary (master)/secondary (slave) functionality for streaming.

New C libraries were added with the Unified (2.00) OS ecosystem, which causes the C program compilation to fail on older OS.
To run the C applications please use one of the following combinations of OS and ecosystem:

   - UNIFIED OS and 2023.1 or newer release (branch) of the GitHub ecosystem
   - Any other OS version and the 2022.2 or older release (branch) of the GitHub ecosystem


**RedPitaya OS 2.0**:

   - `Latest Beta 2.0 <https://downloads.redpitaya.com/downloads/Unify/RedPitaya_OS_2.00-15_beta.img.zip>`_  - |CHANGELOG| (MD5 (zipped): 18cb8bdc3c623f0e8de31b30316cbf10)

.. note::

   If you have problems running the new version of the ecosystem on the boards listed above, please contact the |SUPPORT_LINK| team.


.. |SUPPORT_LINK| raw:: html

   <a href="https://redpitaya.com/contact-us/" target="_blank">support</a>

================================
Latest and Beta versions 1.04 OS
================================

.. warning::

   New C libraries were added with the Unified (2.00) OS ecosystem, which causes the C program compilation to fail on older OS.
   To run the C applications please use one of the following combinations of OS and ecosystem:

      - UNIFIED OS and 2023.1 or newer release (branch) of the GitHub ecosystem
      - Any other OS version and the 2022.2 or older release (branch) of the GitHub ecosystem


**STEMlab 125-14 & STEMlab 125-10**:

   - `Latest Stable 125-14/10 <https://downloads.redpitaya.com/downloads/STEMlab-125-1x/STEMlab_125-xx_OS_1.04-18_stable.img.zip>`_  - |CHANGELOG| (MD5 (zipped): f6cde9b3264a12372873d039535e58d5)
   - `Latest Beta 125-14/10 <https://downloads.redpitaya.com/downloads/STEMlab-125-1x/STEMlab_125-xx_OS_1.04-28_beta.img.zip>`_  - |CHANGELOG| (MD5 (zipped): 92e14e68d27e63568fb87954239e9fb0)


**STEMlab 125-14 (SECONDARY/SLAVE board)**:

   - `Latest Beta Secondary <https://downloads.redpitaya.com/downloads/Streaming_slave_boards/STEMlab-125-1x/STEMlab_125-xx_OS_1.04-6_slave_beta.img.zip>`_  - |CHANGELOG| (MD5 (zipped): ef928d3014d806539e4360e59b7f6a99)

**STEMlab 125-14-Z7020**:

   - `Latest Stable Z7020 <https://downloads.redpitaya.com/downloads/STEMlab-125-14-Z7020/STEMlab_125-14-Z7020_OS_1.04-10_stable.img.zip>`_  - |CHANGELOG| (MD5 (zipped): 3770f34e954674b0423db33ed8a3471d)
   - `Latest Beta Z7020 <https://downloads.redpitaya.com/downloads/STEMlab-125-14-Z7020/STEMlab_125-14-Z7020_OS_1.04-14_beta.img.zip>`_  - |CHANGELOG| (MD5 (zipped): c740aab5d7b374924f19171e1edd3161)

**STEMlab 125-14 4-Input**:

   - `Latest Beta 4-Input <https://downloads.redpitaya.com/downloads/STEMlab-125-14-Z7020-4CH/STEMlab_125-14-4CH_OS_1.04-3_beta.img.zip>`_  - |CHANGELOG_Z20_4CH| (MD5 (zipped): 414c1e7572ec116657a356f3ee2000ac)

**SDRlab 122-16**:

   - `Latest Stable 122-16 <https://downloads.redpitaya.com/downloads/SDRlab-122-16/SDRlab_122-16_OS_1.04-11_stable.img.zip>`_  - |CHANGELOG_Z20| (MD5 (zipped): 634cf27555d4ae8900c92833afc1ddb9)
   - `Latest Beta 122-16 <https://downloads.redpitaya.com/downloads/SDRlab-122-16/SDRlab_122-16_OS_1.04-15_beta.img.zip>`_  - |CHANGELOG_Z20| (MD5 (zipped): ba9f8be2f19630b42ee7b56bdd1d4392)

**SIGNALlab 250-12**:

   - `Latest Stable 250-12 <https://downloads.redpitaya.com/downloads/SIGNALlab-250-12/SIGNALlab_250-12_OS_1.04-27_stable.img.zip>`_  - |CHANGELOG_Z20_250_12| (MD5 (zipped): 40601a42fb06cf23f43aefe15d042a01)
   - `Latest Beta 250-12 <https://downloads.redpitaya.com/downloads/SIGNALlab-250-12/SIGNALlab_250-12_OS_1.04-30_beta.img.zip>`_  - |CHANGELOG_Z20_250_12| (MD5 (zipped): 2acb0579dbf67a40828a9b60a59be9e8)


.. |CHANGELOG| raw:: html

   <a href="https://github.com/RedPitaya/RedPitaya/blob/master/CHANGELOG.md" target="_blank">CHANGELOG</a>

.. |CHANGELOG_Z20| raw:: html

   <a href="https://github.com/RedPitaya/RedPitaya/blob/master/CHANGELOG_Z20.md" target="_blank">CHANGELOG</a>

.. |CHANGELOG_Z20_250_12| raw:: html

   <a href="https://github.com/RedPitaya/RedPitaya/blob/master/CHANGELOG_Z20_250_12.md" target="_blank">CHANGELOG</a>

.. |CHANGELOG_Z20_4CH| raw:: html

   <a href="https://github.com/RedPitaya/RedPitaya/blob/master/CHANGELOG_Z20_4CH.md" target="_blank">CHANGELOG</a>

=================
Older OS versions
=================

All older OS versions that are in our database are available in our archive:

   - |Red Pitaya archive|

For manual ecosystem upgrades please refer to `Manual upgrade`_.

.. |Red Pitaya archive| raw:: html

   <a href="https://downloads.redpitaya.com/downloads/" target="_blank">Red Pitaya archive link</a>


**************************************
Download and install the SD card image
**************************************

The next procedure will create a clean SD card image.

1. Select an appropriate OS version from above and download it.

   .. figure:: microSDcard-RP.png
       :width: 10%

#. Unzip the SD card image.

#. Write the image onto an SD card. Instructions are available for various operating systems:

.. contents::
   :local:
   :backlinks: none
   :depth: 1

4. Insert the SD card into the Red Pitaya.

   .. figure:: pitaya-quick-start-insert-sd-card.png
      :align: center

.. note::

   This video shows how to identify your Red Pitaya model and write a memory card.

   .. raw:: html

    <div style="position: relative; padding-bottom: 30.25%; overflow: hidden; max-width: 50%; margin-left:auto; margin-right:auto;">
        <iframe src="https://www.youtube.com/embed/Qq_YRv2nk3c" frameborder="0" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe>
    </div>

=======
Windows
=======

.. _windows_gui:

#. Insert the SD card into your PC or SD card reader.

   .. figure:: SDcard_insert.jpg
      :align: center

#. Download |balenaEtcher| and install it.

   .. |balenaEtcher| raw:: html

      <a href="https://www.balena.io/etcher/" target="_blank">Balena Ethcer</a>

#. Open the newly installed Balena Etcher application.

   .. figure:: SDcard_Win_BalenaEtcher.png
      :align: center

#. Under **Flash from file** select an unzipped Red Pitaya image file.

   .. figure:: SDcard_Win_BalEtc_FlashFromFile.png
      :align: center

#. Under **Select target** choose the drive letter of the SD card. Balena Etcher will only show you external drives.

   .. figure:: SDcard_Win_BalEtc_SelectTarget.png
      :align: center

   .. note::

      Balena Etcher will only show you external drives, but please be careful to select the correct drive if you have multiple cards or USBs plugged into your computer. If you choose the wrong one, you risk erasing data from the selected drive. You can easily see the drive letter (for example, E:) by looking in the left column of Windows Explorer.

   .. figure:: SDcard_Win_BalEtc_SelectTarget2.png
      :align: center

#. When you click **Flash** the computer will prompt you to allow the operation. Click **yes** and wait for the flashing and validation to be completed.

   .. figure:: SDcard_Win_BalEtc_Flash.png
      :align: center

#. Close Balena Etcher.

   .. figure:: SDcard_Win_BalEtc_FlashComplete.png
      :align: center

=====
Linux
=====

.. _linux_gui:

.. note::

   You can also use |balenaEtcher| on Linux and macOS. Instructions are under :ref:`Windows section <windows_gui>`.

-------------------------
Ubuntu using Image Writer
-------------------------

#. Right-click on the extracted SD card image and select **Open With > Disk Image Writer**.

   .. figure:: DIW_1.png
      :align: center
      :width: 50%

      Context menu

   .. figure:: DIW_2.png
      :align: center
      :width: 50%

      Select tool dialog

2. In the **Restore Disk Image** window, select your SD card in the **Destination** pull-down menu.
   Be careful to select the correct device; use the size for orientation (for example, a 16 GB SD card).

   .. figure:: DIW_3.png
      :align: center
      :width: 50%

      Select drive dialog

3. You will be asked to confirm your choice and enter a password.
   Additional dialog windows will again show the selected destination drive.
   Take the opportunity to reconsider whether you chose the right device.


.. _linux_cli:

------------
Command line
------------

.. note::

   Please note that the use of the ``dd`` tool can overwrite any partition of your machine.
   If you specify the wrong device in the instructions below, you could delete your primary Linux partition.
   Please be careful.

#. Insert the SD card into your PC or SD card reader.

   .. figure:: SDcard_insert.jpg
      :align: center

#. Open the terminal and check the available disks with ``df -h``.
   Our SD card is 16 GB. It is named ``/dev/sdx`` and divided into two partitions, ``/dev/sdx1`` and ``/dev/sdx2``.
   The drive mounted at ``/`` is your main drive.
   Be careful not to use it.

   .. code-block:: shell-session

      $ df -h
      Filesystem       Size  Used   Avail  Use%  Mounted on
      /dev/sdx1        118M   27M     92M   23%  /media/somebody/CAD5-1E3D
      /dev/sdx2       15.9G 1013M   15.8G   33%  /media/somebody/7b2d3ba8-95ed-4bf4-bd67-eb52fe65df55

#. Unmount all SD card partitions with ``umount /dev/sdxN``
   (make sure you replace N with the right numbers).

   .. code-block:: shell-session

      $ sudo umount /dev/sdx1 /dev/sdx2

#. Write the image onto the SD card with the following command.
   Replace the ``red_pitaya_image_file.img`` with
   the name of the unzipped Red Pitaya SD Card Image
   and replace ``/dev/device_name`` with the path to the SD card.

   .. code-block:: shell-session

      $ sudo dd bs=1M if=red_pitaya_image_file.img of=/dev/device_name

#. Wait until the process has finished.


=====
macOS
=====

.. _macos_gui:

.. note::

   You can also use |balenaEtcher| on Linux and macOS. Instructions are under :ref:`Windows section <windows_gui>`.

-------------------
Using ApplePi-Baker
-------------------

#. Insert the SD card into your PC or SD card reader.

   .. figure:: SDcard_insert.jpg
      :align: center

#. Download |ApplePi|. Direct link:

   - `ApplePi-Baker-v2.2.3.dmg <https://www.tweaking4all.com/downloads/raspberrypi/ApplePi-Baker-v2.2.3.dmg>`_
   - `ApplePi-Baker-1.9.9.dmg <https://www.tweaking4all.com/downloads/raspberrypi/ApplePi-Baker-1.9.9.dmg>`_

   .. |ApplePi| raw:: html

      <a href="https://www.tweaking4all.com/hardware/raspberry-pi/applepi-baker-v2" target="_blank">ApplePi-Baker</a>

#. Click on *ApplePi-Baker* icon, then click *Open* in order to run it.

   .. figure:: SDcard_macOS_open.png
      :align: center

#. Drag and drop *ApplePi-Baker* for installation.

   .. figure:: SDcard_macOS_install.png
      :align: center

#. Enter your admin password and click OK.

   .. figure:: SDcard_macOS_password.png
      :align: center

#. Select the SD card drive. This can be recognised by the size of the card, which is 16 GB.

   .. figure:: SDcard_macOS_ApplePi-Baker_drive.png
      :align: center

#. Select the Red Pitaya OS image file.

   .. figure:: SDcard_macOS_ApplePi-Baker_image.png
      :align: center

#. It's coffee time. The application will show you the estimated time for accomplishment.

   .. figure:: SDcard_macOS_ApplePi-Baker_wait.png
      :align: center

#. When the operation is finished, the status will change to idle.

   .. figure:: SDcard_macOS_ApplePi-Baker_quit.png
      :align: center


.. _macos_cli:

------------
Command line
------------

#. Insert the SD card into your PC or SD card reader.

   .. figure:: SDcard_insert.jpg
      :align: center

#. Click **cmd + space**, type **Disk Utility** into the search box and press enter.
   From the menu, select your SD card and click on the **Erase** button (be careful not to delete your disk!).

   .. figure:: SDcard_macOS_DiskUtility.png
      :align: center

#. Click **cmd + space**, then enter ``cd`` into the **Terminal**.
   Then type ``cd Desktop`` and press enter once more.

#. Unmount the partition so that you will be able to overwrite the disk.
   Type ``diskutil list`` into the Terminal and press enter.
   This will show you the list of all memory devices.

   .. figure:: Screen-Shot-2015-08-07-at-16.59.50.png
      :align: center

   Unmount with: ``diskutil UnmountDisk /dev/diskn``
   (insert the number ``n`` of your disk correctly!)

   .. figure:: Screen-Shot-2015-08-07-at-17.14.34.png
      :align: center

#. Type: ``sudo dd bs=1m if=path_of_your_image.img of=/dev/rdiskn``
   (Remember to replace ``n`` with the number that you noted before!)
   (notice that there is a letter ``r`` in front of the disk name, use that as well!)

   .. figure:: Screen-Shot-2015-08-07-at-17.14.45.png
      :align: center

#. Type in your password and wait a few minutes for the image to be written.

#. When the image is written, type: ``diskutil eject /dev/diskn`` and press enter.

#. Safely eject the SD card.


**********
Background
**********

A Red Pitaya SD card contains two partitions:

1. 128 MB FAT contains the **ecosystem**:

   * boot files: FSBL, FPGA images, U-Boot, Linux kernel
   * Red Pitaya API libraries and header files
   * Red Pitaya web applications, scripts, tools
   * customized Nginx web server


2. ~4 GB Ext4 contains the **OS**:

   * Ubuntu/Debian OS
   * various libraries
   * network setup customization
   * systemd services customization

Most of Red Pitaya's source code translates into the ecosystem.
Therefore, it is updated more often.
The OS is changed less frequently.

.. note::

   You can find older and developed Red Pitaya OS images and Ecosystem zip files
   on our |download server|.

.. |download server| raw:: html

   <a href="https://downloads.redpitaya.com/downloads/" target="_blank">download server</a>


.. note::

   A list of new features, bug fixes, and known bugs for each Red Pitaya release
   can be found in our |CHANGELOG|.


**************
Manual upgrade
**************

Instead of writing the whole SD card image,
it is possible to upgrade only the ecosystem.

A manual upgrade allows you to fix a corrupted SD card image
(if only the FAT partition is corrupted) or to install
older, newer, or custom ecosystem zip files.

#. Download a zip file from our |download server|.

#. Insert the SD card into the card reader.

#. Delete all files from the FAT partition.
   Use ``Shift + Delete`` to avoid placing files
   into the trash bin on the same partition.

#. Extract the ecosystem zip file contents onto the now empty partition.

If you wish to keep wireless settings, skip deleting the next files:

* ``wpa_supplicant.conf``
* ``hostapd.conf``


******************
Resize file system
******************

When recording an image to a flash card of any size, we get sections of the file system of 4 GB in size.
In order to increase the available free space, you need to execute the following script:

      .. code-block:: shell-session

          root@rp-f03dee:~# /opt/redpitaya/sbin/resize.sh

After the script is completed, the system will ask you to restart your Red Pitaya.
If everything is done correctly, the system will start with an increased space size. This can be checked with the following command:

      .. code-block:: shell-session

          root@rp-f03dee:~# df -h


.. note::

   If the file system size has not changed, you can try to manually run the command:

      .. code-block:: shell-session

         root@rp-f03dee:~# sudo resize2fs /dev/mmcblk0p2
