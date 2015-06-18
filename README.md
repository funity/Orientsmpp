# smpp
This class library implements the SMPP 3.4 protocol for use within .Net application. It can be used to build both ESME and SMSC based software.

Key Features
1. Fully tested production code. Can handle millions of transactions a day.
2. ESMEManager support mutiple binds of different types. Will round-robin on Transmitter and Transceiver bind.
3. Will log the Full PDU to stdout.
4. Support for SQL Server to store PDU's.
5. Reconnection support when connection drop. Implements the Enquire link rules.
6. Supports Encoding for ASCII, Latin1 and UTF-16. Handles Default data coding rules.
7. Event driven API so all the details are taken care of.
8. Working console based test application.
