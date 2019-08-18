.. _nrf51_bvmcn51:

Braveridge BVMCN510x
#################

Overview
********

.

Hardware
********

BVMCN510x has no external oscillator.

Supported Features
==================

?

+-----------+------------+----------------------+
| Interface | Controller | Driver/Component     |
+===========+============+======================+
| NVIC      | on-chip    | nested vectored      |
|           |            | interrupt controller |
+-----------+------------+----------------------+
| RTC       | on-chip    | system clock         |
+-----------+------------+----------------------+
| UART      | on-chip    | serial port          |
+-----------+------------+----------------------+
| GPIO      | on-chip    | gpio                 |
+-----------+------------+----------------------+
| FLASH     | on-chip    | flash                |
+-----------+------------+----------------------+
| RADIO     | on-chip    | Bluetooth            |
+-----------+------------+----------------------+

Connections and IOs
====================

.

Programming and Debugging
*************************

Applications for the ``nrf51_bvmcn51`` board configuration can be built and
flashed in the usual way (see :ref:`build_an_application` and
:ref:`application_run` for more details).

Flashing
========

Use J-Link LITE.

Now build and flash applications as usual. Here is an example for the
:ref:`hello_world` application.

.. zephyr-app-commands::
   :zephyr-app: samples/hello_world
   :board: nrf51_bvmcn51
   :goals: build flash

Debugging
=========

?

References
**********

?
