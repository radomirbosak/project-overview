Project overview
================

This page serves as a gallery of my projects done mostly in python and displayed here on github.

**Python**
*	[My master's thesis](#thesis)
*	[Dorgin fight simulator](#dfs)
*	[Duden down](#duden)
*	[FMFI tests](#fmfi)
*	[Physics-inspired simulations](#fyzsim)
*	[SHMU extract](#shmu)
*	[Piecewise-linear functions](#plf)
*	[Trends in slovak media](#trendy)

**Assembler**
*	[bfc - Brainfuck compiler](#bfc)
*	[print-dec](#printdec)

**Java**
*	[Pripomienkovac](#pripo)

**C**
*	[Memory Capacity](#mcc)
*	[Stolicka](#stolicka)

**PHP (+ HTML + SQL)**
*	[Eidžof](#eidzof)

Python
------
*	<a name="thesis"></a>[My master's thesis](http://diplomovka.rbos.sk) (not a github link)

	My master thesis is called *Computational analysis of memory capacity of an echo-state network*.

	As part of my master's thesis, I conducted simulations on echo-state networks (a type of artificial neural network). These simulations were written as python scripts.

	Partial results produced by this research were published on a dedicated site [diplomovka.rbos.sk](http://diplomovka.rbos.sk). Some of the scripts used are available there. To browse available sourcecode(s), click "all articles" on the bottom of the page (or follow this [link](http://diplomovka.rbos.sk/?a=all)) and search the page for the keyword "sourcecode".

	Or even better, you can find all of these sources in the [optimizing-reservoir-esn](https://github.com/radomirbosak/optimizing-reservoir-esn) repository. They are quite unorganized however.

	Uses: scientific python (numpy, scipy, matplotlib)

	![A random graph used in my thesis](diplo-forget-ortho.png)

*	<a name="dfs"></a>[Dorgin fight simulator](https://github.com/radomirbosak/dorgin-fight-simulator)

	Simulates fights in the game *Dračí Doupě* and displays the winning probability.

	Uses: GUI (tkinter), threading

	![dfs screenshot](https://raw.githubusercontent.com/radomirbosak/dorgin-fight-simulator/master/screenshot-dfs22-ubuntu.png)

*	<a name="duden"></a>[Duden down](https://github.com/radomirbosak/duden-down)

	Displays the meaning (or description) of german words.

	Uses: HTML parser (BeautifulSoup)

	![](https://raw.githubusercontent.com/radomirbosak/duden-down/master/screenshot.png)

*	<a name="fmfi"></a>[FMFI tests](https://github.com/radomirbosak/fmfi-tests)

	Static webpage (python webserver) collecting old tests from matfyz in Bratislava.

	Uses: Web framework (bottle)

	![](https://raw.githubusercontent.com/radomirbosak/fmfi-tests/master/scr.png)

*	<a name="fyzsim"></a>[Physics-inspired simulations](https://github.com/radomirbosak/fyzsim)

	Various simulations based on physical models, done mostly as school projects.

	Uses: scientific python (numpy, scipy, matplotlib)

	![](https://raw.githubusercontent.com/radomirbosak/fyzsim/master/scr1.png)

*	<a name="shmu"></a>[SHMU extract](https://github.com/radomirbosak/shmu-extract)

	Scrapes, stores and displays hourly temperatures (obtained from slovak weather forecast site shmu.sk).

	Uses: HTML parser (BeautifulSoup), PHP, MySQL

	![](https://raw.githubusercontent.com/radomirbosak/shmu-extract/master/scr-mobile.png)

*	<a name="plf"></a>[Piecewise-linear functions](https://github.com/radomirbosak/plf)

	Library which implements piecewise-linear real functions.

	Uses: scientific python (numpy, matplotlib)

	![](https://github.com/radomirbosak/plf/blob/master/scr.png)

*	<a name="trendy"></a>[Trends in slovak media](https://github.com/radomirbosak/trendy)

	Group project (team of 3 people) done for the Summer school at [the Spot](http://www.thespot.sk/en) during summer 2013.

	It crawls most visited slovak news sites (sme.sk, pravda.sk, hnonline.sk), parses their articles for keywords and display keyword statistics and word popularity trends.

	Uses: Web framework ([pyramid](http://www.pylonsproject.org/)), HTML parser (BeautifulSoup), CSS, javascript


Assembler
---------

*	<a name="bfc"></a>[bfc - Brainfuck compiler](https://github.com/radomirbosak/bfc)

	Compiler for the esoteric programming language [Brainfuck](https://en.wikipedia.org/wiki/Brainfuck).

	Uses: Python, Shell script

	![bfc screenshot](https://raw.githubusercontent.com/radomirbosak/bfc/master/screenshot.png)


*	<a name="printdec"></a>[print-dec](https://github.com/radomirbosak/print-dec)
	
	Prints a decimal representation of a number stored in `rax` register. 

	Uses: `nasm` (netwide assembler)

	![print-dec screenshot](https://raw.githubusercontent.com/radomirbosak/print-dec/master/screenshot.png)

Java
----

*	<a name="pripo"></a>[Pripomienkovac](https://github.com/radomirbosak/pripomienkovac)

	An older java project used to store notes, search through them and remind future events. Programmed in [Netbeans IDE](https://netbeans.org/).

	Uses: GUI (swing), MySQL

C
--

*	<a name="mcc"></a>[Memory capacity](https://github.com/radomirbosak/c-memory-capacity)

	A C implementation of the memory capacity function. Calculates the memory capacity of an echo-state network (a type of artificial neural network) as defined by Jeager (2001) in his paper *Short term memory in echo state networks*.

	Uses: GNU Scientific library, used to calculate [matrix pseudoinverse](https://en.wikipedia.org/wiki/Moore%E2%80%93Penrose_pseudoinverse).

*	<a name="stolicka"></a>[Stolička](https://github.com/radomirbosak/stolicka)

	A `C` and `python` implementation of a solution of a simple [inverse kinematics problem](https://en.wikipedia.org/wiki/Inverse_kinematics). 

	Uses: C (math.h), Python (built-in math functions)

PHP (+ HTML + SQL)
------------------

*	<a name="eidzof"></a>[Eidžof](https://github.com/radomirbosak/eidzof)

	Eidžof is an online turn-based strategy game written in `PHP`.

	![eidzof screenshot](https://raw.githubusercontent.com/radomirbosak/eidzof/master/screenshot-hry_2009-10-4.png)

	Uses: PHP, MySQL, HTML