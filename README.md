cmocka-1.2.x-srpm
=================

SRPM building tools for cmocka-1.2.x for runing Samba 4 on RHEL 6.

This tool taken from the EPEL 7 release.
The set of tools need to be built and installed in the following order.

	cmake-2.8.x-srpm

The "make" command will do these steps.

	make build	# Build the package on the local OS
	make all	# Use "mock" to build the packages with the local
			# samba4repo configuration, which needs.
	make install	# Actually install the RPM's in the designated
			# location for samba4repo


		Nico Kadel-Garcia <nkadel@gmail.com>
