# CAN_msg
can_messages.py is the file where CAN_bus data are collected.

can_data_table.py contains the TKsheet, where the can messages are displayed in a widget.

terminal.py runs the code to display the can messages in terminal dynamically.

To connect with the CAN change the :
      self.bus=can.interface.Bus(bustype="socketcan",channel="vcan0",bitrate=250000)   to 
      self.bus=can.interface.Bus(bustype="socketcan",channel="can0",bitrate=250000)
      
      
