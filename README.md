# WLAN_planning
Additional files for the paper "Hybrid Multicriteria Algorithms Applied to Structural Design of Wireless Local Area Networks". 
All dataset are stored in 8-digit ASCII format.

RSS_AP_CL (2401x512) Receive Signal Strength estimated from the AP to clients, in dBm.

rows -> APs;
colums -> clients;
AP_cand_positions (2x2401) Coordinates x and y of candidate points to instalation of APs.

rows -> x and y positions;
colums -> candidate points to install APs - grid (49x49 pts);
client_positions (2x512) Coordinates x and y of clients.

rows -> x and y positions;
colums -> clients;
BW_consumption (1X512) Bandwidth consumption of clients, in Mbps.

Barriers (51x4) Coordinates of the barriers (walls) of ambient.

rows -> barriers;
colums -> initial and final points of the walls (coordinates) 1=x1, 2=y1, 3=x2, 4=y2
