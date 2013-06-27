# adminui Changelog

## 1.0.6 (unreleased)

## 1.0.5

- ``ADMINUI-1417`` Firewall rules are now shown on vm details page
- ``ADMINUI-1415`` When changing views, adminui now scrolls you to top of page automatically
- ``ADMINUI-1310`` Display image name on vms list and allow filtering by image name

## 1.0.4

- ``ADMINUI-1150`` Role based access control (currently supports roles: readers, operators)
- ``ADMINUI-1406`` Fixes Cloud Analytiics rendering issues in Firefox
- ``ADMINUI-1149`` Users now in the "readers" group have access to adminui in read-only mode
- ``ADMINUI-1407`` Can now assign user to the read-only operator group
- ``ADMINUI-1301`` User details page vms can now be filtered by alias, status, and server uuid
- ``ADMINUI-1399`` Fixes issue in alarms dashboard tile where it may says no alarms when are indeed alarms
- ``ADMINUI-1295`` Provision screen now shows basic information about the selected user
- ``ADMINUI-1228`` Provision screen now allows operators to specify the primary network used
- ``ADMINUI-1343`` Job Progress View "raw output" toggle has been replaced with a button that takes you to the job details view
- ``ADMINUI-1309`` VM listings now include VM's IP addresses
- ``ADMINUI-1388`` Hostname searches are now no longer case case sensitive
- ``ADMINUI-1397`` Fixes Cloud Analytics not able to predicate on metrics
- ``ADMINUI-1400`` Fixes filtering servers by hostname
- ``ADMINUI-1398`` Fixes fingerprint typo on users -> ssh keys
- ``ADMINUI-1404`` Server page searches that return no results no longer stay in loading state

## 1.0.3

- ``ADMINUI-1394`` link version number in header to changelog file
- ``ADMINUI-1387`` network pool creation owner assignment now working again
- ``ADMINUI-1386`` network creation owner assignment now working again
- ``ADMINUI-1385`` network details view now shows owners
- ``ADMINUI-1391`` image import now uses workflow job progres
- ``ADMINUI-1389`` adminui no longer allows creating a VM with incorrect image for brand
- ``ADMINUI-1378`` image search suggestions dropdown does not show enough results
- ``ADMINUI-1393`` display adminui package version on header
- ``ADMINUI-1392`` display current utc time on page
- ``ADMINUI-1390`` app-wide display timestmaps in UTC instead of local time
- ``ADMINUI-1378`` image search suggestions dropdown does not show enough results
- ``ADMINUI-1389`` adminui should not allow creating a VM with incorrect dataset for brand
- ``ADMINUI-1391`` image import should consume new importRemoteImage endpoint that uses workflow
- ``ADMINUI-1342`` Provision button greyed out after filling all fields