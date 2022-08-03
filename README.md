
MIKROTIK LOGICMODULES - August 2022

This archive contains a collection of LogicMonitor "LogicModules" and other information for MikroTik networking products. These are community-developed, custom LogicModules and are not officially supported by the LogicMonitor support team.


PACKAGE CONTENTS

//ConfigSources

This folder contains the ConfigSource needed to backup MikroTik device configurations via SSH; requires that a valid SSH credential has been configured in LogicMonitor

//DataSources

This folder contains DataSources for collection of metrics from MikroTik devices via SNMP

//DataSources/Legacy DataSources

This sub-folder contains "legacy" custom DataSources for MikroTik devices that are unlikely to work with current MikroTik products, but may work with older products for which the newer DataSources are not compatible

//PropertySources

This folder contains a PropertySource file to identify MikroTik devices and automatically tag them with a device property that is referenced by other LogicModules in this package; required for the DataSources to work properly

//SNMP SysOID Maps

This folder contains a screenshot of the SNMP SysOID map that you must configure in LogicMonitor in order for these LogicModules to work correctly
