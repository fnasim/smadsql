# smadsql
Synchronous Multiply Accessible Database

SMADSQL stands for Synchronized, Multiply Accessible Database. SMADSQL is written in C++, initially for Windows platform. The database engine implements a subset of ANSI SQL-92 functionality and offers robust relational database capabilities over TCP/IP. SMADSQL mainly comprises of three modules: Server (TCP/IP), the SQL parsing engine and the Filing module. Each module is independent of the others, which makes various combinations possible; for example, the filing module may be detached anytime and be replaced with another filing implementation. Likewise, the server may be replaced by a stub routine which could allow the entire engine to be compiled within a library which may be statically or dynamically linked with other software to embed robust database capabilities within the third-party C/C++ application. A Connector API has been designed to account for different filing models.

Full report at:
http://www.nasim.org/faisal/NED/PL%20-%20SMADSQL%20Report.zip
