.. _nvc0-macro:

=====================
Fermi macro processor
=====================

.. contents::


Introduction
============

.. todo:: write me


Registers
=========

.. todo:: write me

404400+i*4, i<8: REG[]
404420: OPCODE [at PC]
404424: PC
404428: NEXTPC
40442c: STATE
		b0: ?
		b4: ?
		b8: ACTIVE
		b9: PARM/MADDR?
404430: ??? 117ffff
404434: ??? 17ffff
404438: ??? 13ffff
404460: ??? 7f
404464: ??? 7ff
404468: WATCHDOG_TIMEOUT [30-bit]
40446c: WATCHDOG_TIME [30-bit]
404480: ??? 3
404488: MCACHE_CTRL
40448c: MCACHE_DATA
404490: TRAP
	b0: TOO_FEW_PARAMS
	b1: TOO_MANY_PARAMS
	b2: ILLEGAL_OPCODE
	b3: DOUBLE_BRANCH
	b4: TIMEOUT
	b29: ?
	b30: CLEAR
	b31: ENABLE
404494: TRAP_PC and something?
404498: 1/11/0
40449c: TRAP_OPCODE?
4044a0: STATUS [0000000f - idle]
