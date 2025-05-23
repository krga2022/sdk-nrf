.. _ug_wifi_mem_req_raw_mode:

Memory requirements for Wi-Fi applications in Raw mode
######################################################

Code and RAM memory footprint requirements differ depending on the selected platform and the application example.

The following table list memory requirement values for selected Wi-Fi® samples supporting Raw mode.

Footprint values are provided in kilobytes (KB).

.. tabs::

   .. tab:: nRF54H20 DK

      The following table lists memory requirements for samples running on the :ref:`nRF54H20 DK <programming_board_names>` (:ref:`nrf54h20dk/nrf54h20/cpuapp <zephyr:nrf54h20dk_nrf54h20>`).

      +---------------------------------------------------------------+-------------+--------------------+----------------------+----------------------+---------------------------------+--------------------+----------------------+
      | Sample                                                        |   Total ROM |   Wi-Fi driver ROM |   nRF70 FW Patch ROM |   WPA supplicant ROM |   Total RAM (incl. static HEAP) |   Wi-Fi driver RAM |   WPA supplicant RAM |
      +===============================================================+=============+====================+======================+======================+=================================+====================+======================+
      | :ref:`Raw TX packet <wifi_raw_tx_packet_sample>`              |         502 |                  3 |                   73 |                  146 |                             222 |                146 |                   15 |
      +---------------------------------------------------------------+-------------+--------------------+----------------------+----------------------+---------------------------------+--------------------+----------------------+
      | :ref:`Monitor <wifi_monitor_sample>`                          |         490 |                  3 |                   73 |                  146 |                             228 |                150 |                   15 |
      +---------------------------------------------------------------+-------------+--------------------+----------------------+----------------------+---------------------------------+--------------------+----------------------+
      | :ref:`Promiscuous <wifi_promiscuous_sample>`                  |         508 |                  3 |                   73 |                  146 |                             231 |                150 |                   15 |
      +---------------------------------------------------------------+-------------+--------------------+----------------------+----------------------+---------------------------------+--------------------+----------------------+

   .. tab:: nRF54L15 DK

      The following table lists memory requirements for samples running on the :ref:`nRF54L15 DK <programming_board_names>` (:ref:`nrf54l15dk/nrf54l15/cpuapp <zephyr:nrf54l15dk_nrf54l15>`).

      +---------------------------------------------------------------+-------------+--------------------+----------------------+----------------------+---------------------------------+--------------------+----------------------+
      | Sample                                                        |   Total ROM |   Wi-Fi driver ROM |   nRF70 FW Patch ROM |   WPA supplicant ROM |   Total RAM (incl. static HEAP) |   Wi-Fi driver RAM |   WPA supplicant RAM |
      +===============================================================+=============+====================+======================+======================+=================================+====================+======================+
      | :ref:`Raw TX packet <wifi_raw_tx_packet_sample>`              |         539 |                  3 |                   73 |                  197 |                             221 |                145 |                   23 |
      +---------------------------------------------------------------+-------------+--------------------+----------------------+----------------------+---------------------------------+--------------------+----------------------+

   .. tab:: nRF7002 DK

      The following table lists memory requirements for samples running on the :ref:`nRF7002 DK <programming_board_names>` (:ref:`nrf7002dk/nrf5340/cpuapp <nrf7002dk_nrf5340>`).

      +----------------------------------------------------+-------------+-------------------------------------------+----------------------------+----------------------+---------------------------------+--------------------+----------------------+
      | Sample                                             |   Total ROM |   Wi-Fi driver ROM                        |         nRF70 FW patch ROM |   WPA supplicant ROM |   Total RAM (incl. static heap) |   Wi-Fi driver RAM |   WPA supplicant RAM |
      +====================================================+=============+===========================================+============================+======================+=================================+====================+======================+
      | :ref:`Raw TX packet <wifi_raw_tx_packet_sample>`   |         539 |                                         3 |                         73 |                  187 |                             290 |                218 |                   15 |
      +----------------------------------------------------+-------------+-------------------------------------------+----------------------------+----------------------+---------------------------------+--------------------+----------------------+
      | :ref:`Monitor <wifi_monitor_sample>`               |         526 |                                         3 |                         73 |                  187 |                             312 |                239 |                   15 |
      +----------------------------------------------------+-------------+-------------------------------------------+----------------------------+----------------------+---------------------------------+--------------------+----------------------+
      | :ref:`Promiscuous <wifi_promiscuous_sample>`       |         545 |                                         3 |                         73 |                  187 |                             316 |                239 |                   15 |
      +----------------------------------------------------+-------------+-------------------------------------------+----------------------------+----------------------+---------------------------------+--------------------+----------------------+
