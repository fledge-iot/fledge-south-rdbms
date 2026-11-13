# fledge-south-rdbms
Fledge south plugin that reads rows from relational databases over ODBC and ingests them as Fledge readings. Watermark-based incremental fetch means each poll picks up only new or changed rows. Built on pyODBC and targeted at SQL Server, but it should work with any ODBC-accessible database.

To be donated by Rob Raesemann, Industrial Intelligence Group.
