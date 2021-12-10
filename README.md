# libnl3
libnl-3.2.25 https://www.infradead.org/~tgr/libnl/doc

Netlink Protocol Library Suite (libnl)
Summary
The libnl suite is a collection of libraries providing APIs to netlink protocol based Linux kernel interfaces.

Netlink is a IPC mechanism primarly between the kernel and user space processes. It was designed to be a more flexible successor to ioctl to provide mainly networking related kernel configuration and monitoring interfaces.


Libraries
The interfaces are split into several small libraries to not force applications to link against a single, bloated library.

libnl
Core library implementing the fundamentals required to use the netlink protocol such as socket handling, message construction and parsing, and sending and receiving of data. This library is kept small and minimalistic. Other libraries of the suite depend on this library.
libnl-route
API to the configuration interfaces of the NETLINK_ROUTE family including network interfaces, routes, addresses, neighbours, and traffic control.
libnl-genl
API to the generic netlink protocol, an extended version of the netlink protocol.
libnl-nf
API to netlink based netfilter configuration and monitoring interfaces (conntrack, log, queue)
