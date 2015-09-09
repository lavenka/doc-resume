#Resume: Boris Podchezertsev

**Year of birth**: 1972

**Programming languages**: main: java (since 2000), c++ (since 1996), javascript (since 2008), pascal (since 1988)

**OS**: main: linux (since 2008 (ubuntu), openSUSE since 2011), windows (since 1993), DOS (since 1988)

**Specialisation**: software architect & development, frameworks creation, global code review/cleanup/optimizations/refactoring, migrations, multithreading

**Sport**: mountain bike, longboard, snowboard.

**Mail**: speakingfish@gmail.com, lantalia@mail.ru

**City**: Moscow, Russia.

**Networks**: <https://github.com/speaking-fish>, <http://habrahabr.ru/users/speakingfish/>, <https://twitter.com/bpodchezertsev>, <https://plus.google.com/112013112860760105731/posts/p/pub>

**Some freelance jobs**:

1998 - my first program sent to all Russia regions

sometimes - bugfixes, updates for some gyro test-beds software 

#Jobs

##2012-2015 RusTeleSys

**Links**: <http://rustelesys.com> <http://rustelesys.ru> <http://распознавание-номеров.рф>
 
**Specialization**: License plate recognition.

**Position**: Invited to this startup as chief architect and software developer

**Programming languages**: java, c++, object pascal(delphi, lazarus)

**OS**: linux, windows, android

**CPU**: x86, ARM

**Key features**: multithreading, interprocess communications, networking, opencv, postgresql, sqlite.

**Migrations**:

delphi -> lazarus, java

windows -> linux, android

dll -> separate processes

x86 -> ARM

Total refactoring all systems from bottom to up for stability and upscale:

Global code cleanup.
 
Tight coupling -> modules, facade extraction.

Threads -> managed workers and queues.

Data protocols unification XML, binary (see <https://github.com/speaking-fish/doc-sf-ssp>).

Create multiply software variants and external API's based on unified facades.

Unite network nodes with rabbitmq.

**Large clients**:

* ASKT <http://ackt.ru>:
** AFIMALL underground parking (2700 parking places) in "Moscow-city" (Moscow International Business Center) <http://afimall.ru/en/page/about/>
** Kievsky & Paveletsky railway terminal's parkings in Moscow
** Kazan Ice Palace "Tatneft-Arena" parking (800 parking place) <http://tatneftarena.ru/arena/o-ledovom-dvortse.html>

* Russia state structures of some regions

##2005-2011 Tops Business Integrator

**Links**: <http://www.topsbi.ru/>

**Specialization**: Software development

**Position**: Chief software developer and architect.

**Programming languages**: java, javascript

**OS**: windows, linux

**Large projects**:

###RosGosStrakh <http://www.rgs.ru/>: RGS-AUTO: Car insurance system, desktop GUI

java, oracle(+lite), sybase, swing, replication

**Some tasks totally implemented by me**:

Client software migration from oracle-lite to sybase

New GUI subsystems using functional-reactive programming

Renovation of insurance reserves calculation subsystem

**Refactoring**:

GUI hell -> MVC, functional-reactive

Fixes and speedup for multithreading jobs

Fixes all database transaction/locking

Total memory leaks fixes

Lazy calculations

Migration to generics

###MosEnergo <http://www.mosenergo.ru/>: WEB-GIS.

java, javascript, web, RIA, GIS, oracle, COM, using renderer (no tiled interface was supported in that time) from <http://www.resident.ru/> (Yandex.Maps provider)

The project is mainly made by me

###Alfa-Insurance <http://www.alfastrah.ru/>: WEB-client for Unicus insurance system <http://www.systematic.ru/unicus.html>

java, web, oracle

Fully made by me part: DB-layer

##2003-2005 BSS/BFT <http://www.bssys.com/>, <http://www.bftcom.com/>

**Specialization**: Budget and financial software.

**Position**: Chief software developer.

Invited to develop a new report generator to replace the old.

The project is fully implemented and introduced me:

Report generator for MS Excel: java, delphi 5-7, VBA, firebird.

Logical data structure representation based on existing or new data sources, data source union, data operations: application server (java) + GUI client (delphi)

Micro-sripting language for data operations on server (data sources operations) and client (data source operations and functional-reactive forms)

Markup language for templates in Excel.

Tables/trees/matrices with grouping.
 
User extensions via Excel VBA.

Description sample <https://github.com/speaking-fish/archive/blob/master/reporter/reporter.ru.txt>

##2000-2003 Quorum

**Links**: <http://www.quorum.ru/>

**Specialization**: Banking software.

**Position**: Chief core developer.

**Programming languages**: java, delphi 1-5, borland pascal 7, assembler, c++

**Key features**: heavy WinAPI, DLL, COM, 16/32bit, oracle, multithreading, communications, reverse engineering

**Large projects**:

###Automated banking system "Quorum"

**Large refactoring (70% mine)**:

Renovation of unstable terminal version of ABS Quorum. (multithreading, locks, networking)

**Fully made by me**:

Renovation of unstable DLL-links of ABS Quorum.

Link with control cash machine & service tools.

Total code cleanup for ABS Quorum. (mem cleanup, mem check, null pointers, access violations, multithreading, locks, total static initialization/finalization fixes, 16-bit issues fixes, compatibility fixes, code simplification, assembler removal/fixes, etc.)

Experimental GUI-Wrapper for ABS Quorum text mode interface.

###Experimental project "Stealth"

**Links**: <http://bankir.ru/dom/threads/31222-%D0%9A%D0%B2%D0%BE%D1%80%D1%83%D0%BC-Next-%28%D0%BE%D0%BD-%D0%B6%D0%B5-Stelth-%D0%BE%D0%BD-%D0%B6%D0%B5-%29?s=96b5c3058568130d00e68c576e431c81>, <http://bankir.ru/dom/threads/66278-Next>

Application server + GUI-client: delphi GUI client (GUI without business logic) <-> non-GUI java client (business logic) <-> java server (business logic).

##1999 Altey Laboratories

**Links**: <http://www.altey.ru/>

**Specialization**: Clinical Laboratory Automation.

**Programming languages**: Delphi 3-5

**Key features**: WinAPI, COM, DCOM, SQL, BDE, interbase, firebird, DBF, communications, multithreading

**OS:** Windows 95-98, NT 3-4.

**Position**: software developer and system administrator

Support and setup of harware and sofware;

Integrations with customer's hardware and software;

User support.

**Participation in projects**:

* Development of interchange software modules for Moscow polyclinic #129. Setup hardware. User support.

* Software and hardware works in some medical organizations: Moscow Medicina Clinic <http://en.medicina.ru/>, Moscow polyclinic #220, etc.

##1998-1999 Commercial bank «FINROS» Financial Initiative

**Links**: <http://www.banki.ru/banks/memory/bank/?id=174589>

**Specialization**: Commercial bank.

**Position**: Chief software developer.

**Programming languages**: Delphi 1-3, Clipper 6, shell.

**Key features**: RxLib, Quick Report, dbf, paradox.

**OS:** Windows 95-98, DOS.

**Projects**:

* Internal storage support system. Delphi.

* Utilities for financial document covertations, parsing, union, generation, printing etc.


##1996-1998 Prais Telecom

**Links**: <http://web.archive.org/web/20011221163510/http://www.aha.ru/~kat/> <http://www.aboutphone.info/lib/WireLesson2.html>

**Specialization**: Telecommunication systems development.

**Position**: Chief PC developer.
 
**Programmin languages**: Delphi 1-2, assembler, Watcom C/C++, Watcom Optima.

**Key features**: communications, multithreading, embedded, WinAPI, RxLib, paradox.

**OS**: Windows 3-95, DOS

**Projects**:

* TSC-1. Tech service system for telephone exchange system "LOB". Further development.

* Tarification server and client for telephone exchange system "LOB". Development.

* TSC-1-32bit. Migration to Win32.

* TSC-2. Renovation of TSC-1-32bit for unify protocols, configurations, routing.

* Further development of embedded software for new experimental telephone exchange system (Watcom C).

##1992-1995 MSMU (Moscow State Mining University), Department of Surveying and Geology

**Links**: <http://msmu.misis.ru/index.php/ru/>

**Specialization**: Automation geological and surveying works.

**Position**: Chief developer.

**Programming languages**: pascal (TP6, BP7), assembler (TASM2), clipper('87, 5).
	
**Key features**: frameworks, hardware programming (videoadapters, printers, plotters), Turbo Vision, Fast Vision, assembler, vector graphic, Clipper 5, DBF.

**Projects**:

* GeoDB-1. Clipper. Team development.

Fully implemented by me:

* GeoDB-1 – Modules for build and display/plot profiles and plans for mining. Pascal, Turbo Vision, plotters, printers.

* Fast Vision - fastest graphic framework based on Turbo Vision. Pascal, assembler.

* GeoDB-2. Pascal, Fast Vision, assembler.

* GeoDB-2 – Module subsidence monitoring of the Earth's surface. Pascal, Fast Vision.

##1987-1991 Moscow Instrument-building 	Technical College

**Links**: <http://mpt.ru/>

**Profession**: technician-mathematician-programmer

**Programming languages**: pascal (Turbo Pascal 2-6, Borland Pascal 7), assembler (Turbo assembler 1-2), Clipper’87, DBF, C, gwbasic, DOS batch files.

**Key features**: OOP, interrupt handling, TSR, background tasks, low-level hardware access, drivers, graphics, expression parsing, symbolic math, shell scripts, Turbo Vision 
 
**OS**: DOS 2-5, desqview
