.. _arducam:

ArduCam Cameras
===============

.. image:: /_static/images/arducam/cameras.jpg

Overview
********

`ArduCam <https://www.arducam.com/product-category/opencv-ai-kit/>`__ has built a series of M12-capable and C/CS-capable camera boards that work with OAK cameras.
A variety of M12-mount options allow to match lenses in many projects.

.. _arducam-compatible-cameras:

Arducam compatible cameras
**************************

These cameras are compatible with :ref:`OAK-FFC-3P <dm1090ffc>`, :ref:`OAK-FFC-4P`, and :ref:`DepthAI RPi HAT <DepthAI RPi HAT Baseboard>`:

- `M12-Mount Global Shutter Grayscale OV9282 <https://shop.luxonis.com/collections/modular-cameras/products/oak-ffc-ov9282-22-pin>`__
- `M12-Mount Global Shutter Color OV9782 <https://shop.luxonis.com/collections/modular-cameras/products/oak-ffc-ov9782-22-pin>`__
- `M12-Mount 12.3MP Color IMX477 <https://shop.luxonis.com/collections/modular-cameras/products/oak-ffc-imx477>`__
- `M12-Mount 20MP Color IMX283 <https://www.arducam.com/product/arducam-20mp-imx283-camera-module-with-m12-mount-lens-and-adapter-board-for-depthai/>`__
- `Arducam High Quality Camera for RPi, 12.3MP IMX477 <https://www.arducam.com/product/b0240-arducam-imx477-hq-quality-camera/>`__

Some of these have **M12 mount**, so you can use a variety of **different lenses** (for **custom FoV**), for example:

- Kit of `10 different M12 lenses <https://www.arducam.com/product/m12-mount-camera-lens-kit-arduino-raspberry-pi/>`__ (for testing purposes),
- `M25156H14 (HFoV: 141°C) <https://www.arducam.com/product/M25156H14/>`__,
- `M40180H10 (HFoV: 100°C) <https://www.arducam.com/product/M40180H10/>`__,
- `M2506ZH04 (HFoV: 33°C) <https://www.arducam.com/product/M2506ZH04/>`__,
- and `others <https://www.arducam.com/product-category/lenses/m12-lens-arducam/>`__

M12 selectable FOV
******************

Tests were done using 2x `OAK-FFC-IMX477-M12 <https://shop.luxonis.com/collections/modular-cameras/products/oak-ffc-imx477>`__ and two
different M12 lenses: `20° FOV <https://www.arducam.com/product/arducam-telephoto-20-degree-1-2-3-m12-mount-with-lens-adapter-for-raspberry-pi-high-quality-camera/>`__
and `190° FOV <https://www.arducam.com/product/arducam-190-degrees-lens-for-hq-camera-ln074/>`__ one.

.. figure:: /_static/images/arducam/m12-lens-compare.jpeg

    Side-by-side comparison of narrow and wide FOV M12 lenses on OAK-FFC-IMX477-M12

.. figure:: /_static/images/arducam/lens-test-setup.jpeg

    Test setup from birds view

Replacement stereo cameras for OAK-D-PCBA
*****************************************

The cameras below are compatible with the OAK-D-PCBA.  Due to the use of adhesives to affix the cameras in the assembled OAK-D, it is difficult to replace them.  Attempting to remove the cameras can cause damage to both the cameras and the PCB.

The best and easiest way to remove the old Compact Camera Modules (CCM) from the PCBA is to apply a small amount of acetone or IPA (isopropyl alcohol) around the CCM to soften the permanent glue. After that, a scalpel or any other similar tool should be used slicing the camera off of the PCB, by cutting the glue in between the CCM and PCB. 

- Compact Camera Module (CCM) Fish-Eye OV9282 (for better SLAM) `here <https://www.arducam.com/product/arducam-1mp-ov9282-fisheye-mono-global-shutter-drop-in-replacement-for-depthai-oak-dnoir/>`__
- Mechanical, Optical, and Electrical equivalent OV9282 module with visible and IR capability `here <https://www.arducam.com/product/arducam-1mp-ov9282-ccm-drop-in-replacement-for-oak-d/>`__
- Global-Shutter Color Camera (OV9782) with same intrinsics as OV9282 grayscale `here <https://www.arducam.com/product/arducam-1mp-ov9782-color-global-shutter-drop-in-replacement-for-depthai-oak-dnoir-b0352/>`__
- C/CS-Mount IMX283 (1" diagonal sensor, which is huge) `here <https://github.com/luxonis/depthai-hardware/issues/30>`__ is in progress.


.. include::  /pages/includes/footer-short.rst
