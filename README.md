# Awesome SDN [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/sdnds-tw/awesome-sdn.svg?branch=master)](https://travis-ci.org/sdnds-tw/awesome-sdn)

An awesome list about Software Defined Networks (SDN)

- [Awesome SDN](#awesome-sdn)
  - [Introduction](#introduction)
  - [Network Operating System](#network-operating-system)
  - [Install Environment](#install-environment)
  - [Software Switch](#software-switch)
  - [Network Virtualization](#network-virtualization)
  - [Protocol](#protocol)
  - [Controller](#controller)
  - [Simulator/Emulator](#simulatoremulator)
  - [Language](#language)
  - [Library](#library)
  - [Test](#lest)
  - [NFV](#nfv)
  - [Overlay Network](#overlay-network)
  - [Misc](#misc)
- [Resources](#resources)
  - [Books](#books)

# Introduction
  Software-defined networking (SDN) is an approach to computer networking that allows network administrators to manage network services through abstraction of higher-level functionality.
  Wiki : [Software-Defined Networking](https://en.wikipedia.org/wiki/Software-defined_networking)

# Network Operating System
- [PicOS](http://www.pica8.com/products/picos) - A SDN OS for white box switches Layer-2/3 feature set with support for OpenFlow, OVSDB, and other protocols.
- [Open Network Linux, ONL](https://opennetlinux.org) - A Linux distribution for "bare metal" switches, that is, network forwarding devices built from commodity components.
- [OpenSwitch](http://www.openswitch.net) - A linux network oerating system from Hewlett-Packard.
- [Cumulus Linux](https://cumulusnetworks.com) - Cumulus Linux is a powerful open network operating system that allows you to automate, customize and scale using web-scale principles like the world's largest data centers.
- [OcNOS](https://www.ipinfusion.com/) - Extensive switching and routing protocol support with advanced
capabilities such as MPLS and SDN
- [FlexSwitch](https://snaproute.com/) - The first open source network protocol suite offering complete layer2/layer3 functionality for accelerating development and deployment of whitebox networking gear


# Install Environment
- [ONIE](http://onie.org/) - ONIE enables a bare metal network switch ecosystem where end users have a choice among different network operating systems.

# Software Switch

- [OpenvSwtich](http://openvswitch.org/) - Open vSwitch is a production quality, multilayer virtual switch.
- [Indigo](https://github.com/floodlight/indigo) - Indigo is an open source project aimed at enabling support for OpenFlow on physical and hypervisor switches.
- [CPqD](https://github.com/CPqD/ofsoftswitch13)- An OpenFlow 1.3 compatible user-space software switch implementation
- [Lagopus](https://lagopus.github.io) - A high-performance software OpenFlow 1.3 switch.
- [LINC-Switch](https://github.com/FlowForwarding/LINC-Switch) - A pure OpenFlow software switch written in Erlang
- [snabbswitch](https://github.com/SnabbCo/snabbswitch) - An open source virtualized Ethernet networking stack.
- [ZeroTier](https://github.com/zerotier/ZeroTierOne) - ZeroTier is a software-based managed Ethernet switch for planet Earth.

# Network Virtualization

- [FlowVisor](https://github.com/opennetworkinglab/flowvisor) - An OpenFlow controller that acts as a hypervisor/proxy between a switch and multiple controllers. Can slice multiple switches in parallel, effectively slicing a network.
- [OpenVirtex](https://github.com/opennetworkinglab/OpenVirteX) - A network hypervisor that can create multiple virtual and programmable networks on top of a single physical infrastructure.

# Protocol

- [OpenFlow](https://www.opennetworking.org/sdn-resources/openflow) - A communications protocol that gives access to the forwarding plane of a network switch or router over the network.
- [OF-Config](https://www.opennetworking.org/technical-communities/areas/specification/1928-of-config) - OpenFlow Management and Configuration Protocol
- [OVSDB](https://tools.ietf.org/html/rfc7047) - A communication protocol which used to manage the OpenvSwitch database.
- [POF](http://www.poforwarding.org/) - Protocol Oblivious Forwarding

# Controller

- [NOX](http://www.noxrepo.org) - An open source development platform for C++-based software-defined networking (*SDN*) control applications.
- [NodeFlow](https://github.com/gaberger/NodeFLow) - An OpenFlow Controller Node Style.
- [ONOS](http://onosproject.org) - Open Network Operating System.
- [OpenDaylight](https://www.opendaylight.org) - OpenDaylight Platform
- [Ryu](https://osrg.github.io/ryu) - A component-based software defined networking framework.
- [Floodlight](https://github.com/floodlight/floodlight) - A java-based OpenFlow controller.
- [Vyatta](https://github.com/BRCDcomm/BVC/) - The first commercial Controller built directly from OpenDaylight.
- [OpenContrail](http://www.opencontrail.org/) - A SDN project that utilizes SDN & NFV and provides all the necessary components for network virtualization.
- [IRIS](http://openiris.etri.re.kr/) - A Resursive SDN Openflow Controller created by SDN Research Section, ETRI.
- [Open MUL](http://www.openmul.org/openmul-controller.html) - A lightweight SDN/Openflow controller written almost entirely in C from scratch.
- [OESS](https://github.com/globalnoc/oess) - The Open Exchange Software Suite to configure and control OpenFlow Enabled switches.
- [Beehive Network Controller](https://github.com/kandoo/beehive-netctrl) - A distributed SDN controller built on top of Beehive. It supports OpenFlow but can be easily extended for other southbound protocols.
- [Ravel](https://github.com/ravel-net/ravel) - A software-defined networking (SDN) controller that uses a standard SQL database to represent the network.
- [Trema](https://trema.github.io/trema/) - A full-stack, easy-to-use framework for developing OpenFlow controllers in Ruby and C.

# Simulator/Emulator

- [Mininet](http://mininet.org/) - An Instant Virtual Network on your Laptop (or other PC)
- [OpenNet](http://github.com/dlinknctu/opennet) - A simulator for software-defined wireless local area network
- [EstiNet](http://www.estinet.com/products.php?lv1=13&sn=13) - A world-renowned software tool for network planning
- [ns-3](https://www.nsnam.org/) - A discrete-event network simulator that supports OpenFlow environment.

# Language

- [P4](http://p4.org/) - A declarative language for expressing how packets are processed by the pipeline of a network forwarding element such as a switch, NIC, router or network function appliance.
- [Frenetic](https://github.com/frenetic-lang/frenetic) - The Frenetic Programming Language and Runtime System
- [Pyretic](http://www.frenetic-lang.org/pyretic/) - Pyretic is one member of the Frenetic family of SDN programming languages.
- [NEMO](https://wiki.onosproject.org/display/ONOS/NEMO+Language) - A domain specific language (DSL) based on abstraction of network models and conclusion of operation patterns.

# Library

- [loxigen](https://github.com/floodlight/loxigen) - LoxiGen is a tool that generates OpenFlow protocol libraries for a number of languages.
- [openfaucet](https://github.com/rlenglet/openfaucet) - openfaucet is a pure Python implementation of the OpenFlow 1.0.0
protocol, based on Twisted.
- [oflib-node](https://github.com/TrafficLab/oflib-node) - Oflib-node is an OpenFlow protocol library for Node. It converts between OpenFlow wire protocol messages and Javascript objects.
- [OpenFlowJ](https://bitbucket.org/openflowj/openflowj) - A Java implementation of low-level OpenFlow packet marshalling/unmarshalling and IO operations.
- [nettle](http://haskell.cs.yale.edu/other-projects/nettle/) - A Haskell library for working with the OpenFlow protocol.
- [OCaml OpenFlow](https://github.com/frenetic-lang/ocaml-openflow) - A serialization and protocol library for OpenFlow.

# Test

- [oftest](https://github.com/floodlight/oftest) - OpenFlow Testing Framework
- [STS](https://ucb-sts.github.com/sts/) - SDN Troubleshooting System, simulates network devices, allowing programmatically test cases generation.
- [nice-of](https://code.google.com/archive/p/nice-of/) - A tool to test OpenFlow controller application for the NOX controller platform.
- [OpenSDNCore](http://www.opensdncore.org/) - Virtualisation Testbed for NFV/SDN Environment.

# NFV

- [OPNFV](https://www.opnfv.org) - Accelerating NFV's evolution through an integrated, open platform.

# Overlay Network

- [VXLAN](https://docs.ustack.com/unp/src/architecture/vxlan.html) - Virtual Extensible LAN

# Misc

- [Central Office Re-architected as a Datacenter, CORD](http://opencord.org) - Reference Implementation of a Service Delivery Platform that Provides Cloud Economies and Agility.
- [OPEN-Orchestrator Project, Open-O](https://www.open-o.org)
- [Open Source MANO Community, OSM](https://osm.etsi.org/welcome/)
- [Enhanced Controller Orchestration Management Policy, ECOMP](http://att.com/ecomp) - Operations management framework.


# Resources
## Books

- [SDN: Software Defined Networks: An Authoritative Review of Network Programmability Technologies](https://www.amazon.com/SDN-Software-Networks-Thomas-Nadeau/dp/1449342302/&tag=eltale-20)
- [圖解OpenFlow](http://www.books.com.tw/products/CN11301942)
- [重构网络-SDN架构与实现](http://www.sdnlab.com/book/18762.html)
- [深度解析SDN: 利益、战略、技术、实践](http://www.sdnlab.com/book/9470.html)
- [SDN核心技术剖析和实战指南](http://www.sdnlab.com/book/9480.html)
- [软件定义网络:SDN与OpenFlow解析](http://www.sdnlab.com/book/9473.html)

