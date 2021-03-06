---
title: Freedom of Association on the Internet
abbrev: FoA
docname: draft-irtf-hrpc-association-03
category: info

ipr: trust200902
area: IRTF
workgroup: Human Rights Protocol Considerations Research Group
keyword: Internet-Draft
stand_alone: yes
pi:
  rfcedstyle: yes
  toc: yes
  tocindent: yes
  sortrefs: yes
  symrefs: yes
  strict: yes
  comments: yes
  inline: yes
  text-list-symbols: -o*+

author:

-
       ins: N. ten Oever
       name: Niels ten Oever
       organization: University of Amsterdam
       email: mail@nielstenoever.net
-
       ins: G. Perez de Acha
       name: Gisela Perez de Acha
       organization: Derechos Digitales
       email: gisela@derechosdigitales.org
-
       ins: S. Couture
       name: Stéphane Couture
       organization: University de Montreal
       email: stephane.couture@umontreal.ca
-
       ins: J.L. Hall
       name: Joseph Lorenzo Hall
       organization: ISOC
       email: joe@isoc.org



normative:

informative:

  RFC0001:
  RFC0155:
  RFC0791:
  RFC0903:
  RFC1211:
  RFC1287:
  RFC1771:
  RFC1930:
  RFC2810:
  RFC2812:
  RFC3233:
  RFC1958:
  RFC4033:
  RFC4084:
  RFC4271:
  RFC4880:
  RFC5246:
  RFC5694:
  RFC5751:
  RFC6176:
  RFC7118:
  RFC7194:
  RFC7754:
  RFC7858:
  RFC8280:
  RFC8484:

  UDHR:
    title: The Universal Declaration of Human Rights
    date: 1948
    author:
      - org: United Nations General Assembly
    target: http://www.un.org/en/documents/udhr/

  ICCPR:
    title: International Covenant on Civil and Political Rights
    date: 1966
    author:
      - org: United Nations General Assembly
    target: http://www.ohchr.org/EN/ProfessionalInterest/Pages/CCPR.aspx

  Tocqueville:
    title: Democracy in America
    date: 1840
    author:
      - ins: A. de Tocqueville
    target: http://classiques.uqac.ca/classiques/De_tocqueville_alexis/democracy_in_america_historical_critical_ed/democracy_in_america_vol_2.pdf p. 304

  HussainHoward:
    title: "What Best Explains Successful Protest Cascades? ICTs and the Fuzzy Causes of the Arab Spring"
    date: 2013
    author:
      - ins: M.M. Hussain
      - ins: P.N. Howard
    target: https://doi.org/10.1111/misr.12020
    seriesinfo: "Int Stud Rev (2013) 15 (1): 48-66."

  UNHRC:
    title: Report of the Special Rapporteur on the rights to freedom of peaceful assembly and of association
    date: 2012
    author:
      - ins: Maina Kiai
    target: http://freeassembly.net/wp-content/uploads/2013/10/A-HRC-20-27_en-annual-report-May-2012.pdf
    seriesinfo: A/HRC/20/27

  APC:
    title: Freedom of assembly and association online in India, Malaysia and Pakistan. Trends, challenges and recommendations.
    date: 2016
    author:
      - org: Association for Progressive Communications
      - ins: Gayathry Venkiteswaran
    target: https://www.apc.org/es/system/files/FOAA_online_IndiaMalaysiaPakistan.pdf

  Swire:
    title: "Social Networks, Privacy, and Freedom of Association: Data Empowerment vs. Data Protection"
    date: 2012
    author:
      - ins: Peter Swire
    target: https://ssrn.com/abstract=1989516 or http://dx.doi.org/10.2139/ssrn.1989516
    seriesinfo: "North Carolina Law Review (2012) 90 (1): 104."

  UNGA:
    title: Human rights defenders
    date: 2004
    author:
      - ins: Hina Jilani
    target: http://www.un.org/en/ga/search/view_doc.asp?symbol=A/59/401 para. 46
    seriesinfo: A/59/401

  HafnerandLyon:
    title: Where Wizards Stay Up Late. The Origins of the Internet
    date: 1998
    author:
      - ins: K. Hafnerand
      - ins: M. Lyon
    target: https://doi.org/10.1111/misr.12020
    seriesinfo: "First Touchstone Edition (1998): 93."

  Pensado:
    title: Student Activism. Utopian Dreams.
    date: 2012
    author:
      - ins: Jaime Pensado
    target: http://revista.drclas.harvard.edu/book/student-activism
    seriesinfo: "ReVista. Harvard Review of Latin America (2012)."

  Abbate:
    title: Inventing the Internet
    date: 2013
    author:
      - ins: Janet Abbate
    target: https://mitpress.mit.edu/books/inventing-internet
    seriesinfo: "Cambridge: MIT Press (2013): 11."

  Melucci:
    title: The Process of Collective Identity
    date: 1995
    author:
      - ins: A. Melucci
    seriesinfo: Temple University Press, Philadelphia

  AckermannKargerZhang:
    title: "Mailing Lists: Why Are They Still Here, What’s Wrong With Them, and How Can We Fix Them?"
    date: 2017
    author:
      - ins: M. S. Ackerman
      - ins: D. R. Karger
      - ins: A. X. Zhang
    target: https://people.csail.mit.edu/axz/papers/mailinglists.pdf
    seriesinfo: "Mit. edu (2017): 1."

  Benkler:
    title: Peer Production and Cooperation
    date: 2009
    author:
      - ins: Y. Benkler
    target: http://www.benkler.org/Peer%20production%20and%20cooperation%2009.pdf
    #    seriesinfo: "M. Bauer &amp; M. Latzer (eds.), Handbook on the Economics of the Internet, Cheltenham and Northampton, Edward Elgar."

  AndersonGuarnieri:
    title: "Fictitious Profiles and WebRTC's Privacy Leaks Used to Identify Iranian Activists"
    date: 2016
    author:
      - ins: C. Anderson
      - ins: C. Guarnieri
    target: https://iranthreats.github.io/resources/webrtc-deanonymization/

  OSCE:
    title: Guidelines on Freedom of Peaceful Assembly
    date: 2010
    author:
      - org: OSCE Office for Democratic Institutions and Human Rights
    target: https://www.osce.org/odihr/73405?download=true
    seriesinfo: page 24

  NelsonHedlun:
    title: "A Network of Peers: Models Through the History of the Internet"
    date: 2001
    author:
      - ins: N. Minar
      - ins: M. Hedlun
    target: "http://library.uniteddiversity.coop/REconomy_Resource_Pack/More_Inspirational_Videos_and_Useful_Info/Peer_to_Peer-Harnessing_the_Power_of_Disruptive_Technologies.pdf"
    seriesinfo: "Peer to Peer: Harnessing the Power of Disruptive Technologies, ed: Andy Oram"

  Vu:
    title: "Peer-to-Peer Computing: Principles and Applications"
    date: 2010
    author:
      - ins: Vu, Quang Hieu
      - ins: Lupu, Mihai
      - ins: Ooi, Beng Chin
    target: "https://www.springer.com/cn/book/9783642035135"

  Star:
    title: The Ethnography of Infrastructure
    date: 1999
    author:
      - ins: S.L. Star
    target: http://journals.sagepub.com/doi/abs/10.1177/00027649921955326
    seriesinfo: American Behavioral Scientist, Volume 43 (3), 377-391.

  Schleuder:
    title: Schleuder - A gpg-enabled mailinglist with remailing-capabilities.
    date: 2017
    author:
      - org: Nadir
    target: https://schleuder.nadir.org/

  Crawford:
    title: "The WebRTC VPN “Bug” and How to Fix"
    date: 2015
    author:
      - ins: D. Crawford
    target: https://www.bestvpn.com/the-webrtc-vpn-bug-and-how-to-fix-it/

  RPZ:
    title: DNS Response Policy Zones (RPZ)
    date: 2017
    author:
       - ins: P. Vixie
       - ins: V. Schyver
    target: https://tools.ietf.org/html/draft-ietf-dnsop-dns-rpz-00

  Wugh:
    title: Using Third Party Services for IETF Work
    date: 2017
    author:
       - ins: M. Nottingham
    target: https://datatracker.ietf.org/doc/draft-nottingham-wugh-services/

  GithubIETF:
    title: Using GitHub at the IETF
    date: 2017
    author:
       - ins: M. Thomson
       - ins: A. Atlas
    target:

  Troncosoetal:
    title: "Systematizing Decentralization and Privacy: Lessons from 15 Years of Research and Deployments"
    date: 2017
    author:
       - ins: C. Troncoso
       - ins: M. Isaakdis
       - ins: G. Danezis
       - ins: H. Halpin
    seriesinfo: "Proceedings on Privacy Enhancing Technologies ; 2017 (4):307–329"
    target: https://www.petsymposium.org/2017/papers/issue4/paper87-2017-4-source.pdf

  StarRuhleder:
    title: "Steps toward an ecology of infrastructure: Design and access for large information spaces"
    date: 1996
    author:
       - ins: S.L. Star
       - ins: K. Ruhleder
    seriesinfo: "Information Systems Research 7 (1) (1996) 111–134."

  Haas:
    title: "Introduction: epistemic communities and international policy coordination"
    date: 1992
    author:
       - ins: P.M. Haas
    seriesinfo:  "International Organization, special issue: Knowledge, Power, and International Policy Coordination, Cambridge Journals. 46 (1): 1–35."

  Mainwaringetal:
    title: "Infrastructures and Their Discontents: Implications for Ubicomp"
    date: 2004
    author:
       - ins: S.D. Mainwaring
       - ins: M.F. Chang
       - ins: K. Anderson
    seriesinfo: "DBLP Conference: Conference: UbiComp 2004: Ubiquitous Computing: 6th International Conference, Nottingham, UK, September 7-10, 2004. Proceedings"
    target: http://www.dourish.com/classes/readings/Mainwaring-Infrastructure.pdf

  Bowker:
    title: Information mythology and infrastructure
    date: 1994
    author:
       - ins: G. Bowker
    seriesinfo: "In: L. Bud (Ed.), Information Acumen: The Understanding and use of Knowledge in Modern Business,Routledge,London,1994,pp.231–247"

  Bloketal:
    title: Infrastructuring Environments
    date: 2016
    author:
       - ins: A. Blok
       - ins: M. Nakazora
       - ins: B.R. Winthereik
    seriesinfo: "Science as Culture 25:1, 1-22."

  PipekWulf:
    title: "Infrastructuring: Towards an Integrated Perspective on the Design and Use of Information Technology"
    date: 2009
    author:
       - ins: V. Pipek
       - ins: W. Wolf
    seriesinfo: "Journal of the Association for Information Systems (10) 5, pp. 306-332"

  Anderson:
    title: "The political voice of young citizens Educational conditions for political conversation – school and social media"
    date: 2012
    author:
      - ins: E. Andersson
    seriesinfo: "Utbildning &amp; Demokrati: Tidskrift för Didaktik och Utbildningspolitik, Volume 21, Number 1, 2012, pp. 97-119(23)"
    target: http://www.ingentaconnect.com/content/doaj/11026472/2012/00000021/00000001/art00006

  Tufekci:
    title: "Twitter and Tear Gas: The Power and Fragility of Networked Protest"
    date: 2017
    author:
      - ins: Z. Tufekci
    target: https://www.twitterandteargas.org/

  Weiser:
    title: The Computer for the 21st Century
    date: 1991
    author:
      - ins: L M. Weiser
    seriesinfo: Scientific American Ubicomp Paper after Sci Am editing
    target: https://web.archive.org/web/20141022035044/http://www.ubiq.com/hypertext/weiser/SciAmDraft3.html

  Sink:
    title: Version Control by Example
    date: 2011
    author:
      - ins: E. Sink
    target: http://ericsink.com/vcbe/

  Mosco:
     title: "The Digital Sublime: Myth, Power, and Cyberspace"
     date: 2005
     author:
      - ins: V. Mosco
     target: https://mitpress.mit.edu/books/digital-sublime

  FiveEyes:
     title: "Five Eyes"
     date: 2018
     author:
      - ins: Wikipedia
     target: https://en.wikipedia.org/wiki/Five_Eyes

  SchengenRouting:
     title: "Schengen Routing"
     date: 2018
     author:
      - ins: Wikipedia
     target: https://en.wikipedia.org/wiki/Schengen_Routing

  SeawrightGerring:
     title: "Case Selection Techniques in Case Study Research: A Menu of Qualitative and Quantitative Options"
     date: 2008
     author:
      - ins: J. Seawright
      - ins: J. Gerring
     target: https://journals.sagepub.com/doi/pdf/10.1177/1065912907313077
     seriesinfo: "Political Research Quarterly, 61(2), 294–308."


--- abstract

This document discuss the relationships between the Internet
architecture and the ability of people to exercise their right to
freedom of assembly and association online. The Internet increasingly
mediates our lives, our relationships and our ability to exercise our
human rights. As a forum, it provides a global public space despite
being built on predominantly private infrastructure. Since Internet
protocols play a central role in the management, development and use
of the Internet, the relation between protocols and the aforementioned
rights should be analyzed and any adverse impacts should be mitigated.

--- middle


Introduction
============

    We shape our tools and, thereafter, our tools shape us. 
         - John Culkin (1967)

The Internet is constantly shaping modern information societies by
providing a socio-technical ordering. In other words, the Internet
infrastructure and architecture consist of social and technological
arrangements {{StarRuhleder}}. Such ordering is not always apparent
because infrastructure is often taken for granted by those using
it. It tends to hide itself in the societal woodwork {{Mosco}}, or put
otherwise: ‘The most profound technologies are those that disappear'
{{Weiser}}.

Infrastructure therefore is mostly known by an epistemic community of
experts {{Haas}} and only gets recognized by the larger public when it
fails. As the Internet grows, decisions made about its architecture
are become more important. {{RFC8280}} established the relationship
between human rights and Internet protocols. Following the same
methodology, we now seek to uncover the relation between the right to
assembly, association and the Internet infrastructure.

One one hand, the right to freedom of assembly and association
protects collective expression. Likewise, systems and protocols that
enable communal interactions between people and servers enable this
right given that the Internet itself was originally designed as "a
medium of communication for machines that share resources with each
other as equals" {{NelsonHedlun}}.

The current draft continues the work started in {{RFC8280}} by
investigating the exact impact of Internet protocols on specific human
rights, namely the right to freedom of assembly and association, in
order to mitigate potential negative impacts.


Vocabulary used
===============

Architecture
: The design of a structure

Autonomous System (AS)

: Autonomous Systems are the unit of routing policy in the modern
world of exterior routing {{RFC1930}}.
: Within the Internet, an autonomous system (AS) is a collection of
connected Internet Protocol (IP) routing prefixes under the control of
one or more network operators on behalf of a single administrative
entity or domain that presents a common, clearly defined routing
policy to the Internet {{RFC1930}}.
: The classic definition of an Autonomous System is a set of routers
under a single technical administration, using an interior gateway
protocol and common metrics to route packets within the AS, and using
an exterior gateway protocol to route packets to other ASs
{{RFC1771}}.

Border Gateway Protocol (BGP)
: An inter-Autonomous System routing protocol {{RFC4271}}.

Connectivity
: The extent to which a device or network is able to reach other
devices or networks to exchange data. The Internet is the tool for
providing global connectivity {{RFC1958}}. Different types of
connectivity are further specified in {{RFC4084}}. The combination of
the end-to-end principle, interoperability, distributed architecture,
resilience, reliability and robustness are the enabling factors that
result in connectivity to and on the Internet.

Decentralization
: Implementation or deployment of standards, protocols or systems
without one single point of control.

Distributed system
: A system with multiple components that have their behavior
co-ordinated via message passing. These components are usually
spatially separated and communicate using a network, and may be
managed by a single root of trust or authority. {{Troncosoetal}}

Infrastructure
: Underlying basis or structure for a functioning society,
organization or community. Because infrastructure is a precondition
for other activities it has a procedural, rather than static, nature
due to its social and cultural embeddedness {{PipekWulf}}
{{Bloketal}}. This means that infrastructure is always relational:
infrastructure always develops in relation to something or someone
{{Bowker}}.

Internet

: The Network of networks, that consists of Autonomous Systems that
are connected through the Internet Protocol (IP).
: A persistent socio-technical system over which services are
delivered {{Mainwaringetal}},
: A techno-social assemblage of devices, users, sensors, networks,
routers, governance, administrators, operators and protocols
: An emergent-process-driven thing that is born from the collections
of the ASes that happen to be gathered together at any given time. The
fact that they tend to interact at any given time means it is an
emergent property that happens because they use the protocols defined
at IETF.

Research question
=================

How does the architecture of the internet enable and/or inhibit the
right to freedom of assembly and association?

Methodology
============

The point of departure of the present work is {{RFC8280}} - an initial
effort to establish the relationship between human rights and the
Internet architecture, specifically protocols and standards. As such,
{{RFC8280}} was inductive and explorative in nature, and it ultimately
established relationships between
aforementioned concepts through a series of case studies.

The methodology was based on process tracing, semi-structured
interviews and quantitative and qualitative document analysis which
has been further validated through confirmatory research in the form
of Human Rights Protocol Reviews. The relationship, proposed as
a hypothesis in {{RFC8280}} says that there is an inherent
relation between protocols, the Internet architecture, and human
rights. The guidelines in {{RFC8280}} describe a relationship between
the right to freedom of assembly and association and connectivity,
security, censorship resistance, anonymity, pseudonymity,
accessibility, decentralization, adaptability, and outcome
transparency.

Taking into consideration the international human rights framework
regarding freedom of assembly and association, the present document
seeks to deepen the relationship between the Internet architecture,
protocols, and standards without creating new guidelines. In that way,
we continue the work proposed in {{RFC8280}} and follow the primary
aim of the Human Rights Protocol Consideration Research Group, as laid
out in its charter where one of the research aims is 'to expose the
relation between protocols and human rights, with a focus on the
rights to freedom of expression and freedom of assembly'. Even though
the present work does not seek to create new guidelines, the
conclusions could inform the development of new guidelines such as is
done in draft-irtf-hrpc-guidelines.

Given that our current research proposition is that "the Internet
infrastructure significantly impacts the ability of people to exercise
the human rights to freedom of association and assembly', we therefore
aim to discuss the relationship between protocols and association by analyzing
some protocols that we consider to have been built to enable association in groups. 
Subsequently we analyze the cases through the theoretical
framework provided in the literature review and based on that provide
recommendations based on the findings.

Literature Review
=================

Freedom of association and assembly refers both to the individual right
to join or leave a group and to the collective right of a group to engage
in a collective group and to organize itself. Freedom of association and
assembly is garanteed by many national law and international treaty, such 
as article 20 and 23 of the Universal Declaration of Human Rights {{UDHR}}
and article 22 of International Covenant on Civil and Political Rights
{{ICCPR}}. It's purpose is to ensure that everyone in a society has the 
opportunity to express opinions they hold in common with others. As such, 
it is a tool that facilitates dialogue among citizens, as well as with political
leaders or governments {{OSCE}}. In a democracy, causes and opinions are more
widely heard when a group of people come together behind the same
cause or issue {{Tocqueville}}.

In international law, the right to freedom of assembly and association
protects any collective, gathered either permanently or temporarily
for "peaceful" purposes. It is important to underline the property of
"freedom" because the right to freedom of association and assembly is
voluntary and uncoerced: anyone can join or leave a group of choice,
which in turn means one should not be forced to either join, stay or
leave. What constitutes a definition of "peaceful" is outside the
scope of the present document.

The difference between freedom of assembly and freedom of association
is merely a gradual one: the former tends to have an informal and
ephemeral nature, whereas the latter refers to established and
permanent bodies with specific objectives. Nonetheless, both are
protected to the same degree.

Where an assembly is an intentional and temporary gathering of a
collective in a private or public space for a specific purpose:
demonstrations, indoor meetings, strikes, processions, rallies or even
sits-in {{UNHRC}}; association has a more formal and established
nature. It refers to a group of individuals or legal entities brought
together in order to collectively act, express, pursue or defend a
field of common interests {{UNGA}}. Think about civil society
organizations, clubs, cooperatives, NGOs, religious associations,
political parties, trade unions or foundations.

Even if privacy and freedom of expression are the most discussed human
rights when it comes to the online world, the right to freedom of
assembly and association is quintessential for the Internet. Online
association and assembly are the starting point of group to
mobilization in modern democracies, and even more so where physical
gatherings have been impossible or dangerous {{APC}}. Throughout the
world -from the Arab Spring to Latin American student movements and
the #WomensMarch- the Internet has played a crucial role by providing
means for the fast dissemination of information otherwise mediated by
the press, or even forbidden by the government {{Pensado}}. According
to Hussain and Howard the Internet helped to "build solidarity
networks and identification of collective identities and goals, extend
the range of local coverage to international broadcast networks" and
as platform for contestation for "the future of civil society and
information infrastructure" {{HussainHoward}}.

The IETF itself, defined as a 'open global community' of network
designers, operators, vendors, and researchers is also protected by
freedom of assembly and association {{RFC3233}}. Discussions, comments
and consensus around RFCs are possible because of the collective
expression that freedom of association and assembly allow. The very
word “protocol” found its way into the language of computer networking
based on the need for collective agreement among network users
{{HafnerandLyon}}.

We are aware that some of the following examples go beyond the use of
Internet protocols and flow over into the application layer or
examples in the offline world whereas the purpose of the current
document is to break down the relationship between Internet protocols
and the right to freedom of assembly and association. Nonetheless,
given that protocols are a part of the socio-technical ordering of
reality, we do recognize that in some cases the line between them and
applications, implementations, policies and offline realities are
often blurred and hard -if not impossible- to differentiate.


Cases and examples
==================

As the Internet mediates collective action and collaboration, it
impacts on freedom of association and assembly. To answer our research
question regarding how internet architecture enable and/or inhibits
such human right, we researched several independent and typical cases
related to protocols that have been either adopted by the IETF, or are
widely used on the Internet. Our goal is to figure out whether they
facilitate freedom of assembly and association, or whether they
inhibit it through their design or implementation. We also indicate,
per case, the interrelation with issues in {{RFC8280}}.

## Conversing

An interactive conversation between two or more people forms the basis
to organize and associate. According to Anderson "the relationship
between political conversation and engagement in the democratic
process is strong." {{Anderson}}. A conversation is inherently of
social nature. Therefore, by these definitions the core of the
"political" is essentially assembly or association: a basis for the
development of social cohesion in society.

### Mailing Lists

Since the beginning of the Internet mailing lists have been a key site
of assembly and association {{RFC0155}} {{RFC1211}}. In fact, mailing
lists were one of the Internet's first functionalities
{{HafnerandLyon}}.

In 1971, four years after the invention of email, the first mailing
list was created to talk about the idea of using Arpanet for
discussion. What had initially propelled the Arpanet project forward
as a resource sharing platform was gradually replaced by the idea of a
network as a means of bringing people together {{Abbate}}. More than
45 years after, mailing lists are pervasive and help communities to
engage, have discussions, share information, ask questions, and build
ties. Even as social media and discussion forums grow, mailing lists
continue to be widely used {{AckermannKargerZhang}} and are still a
crucial tool to organise groups and individuals around themes and
causes {{APC}}.

Mailing lists' pervasive use are partly explained because they allow
for "free" association: people subscribe (join) and unsubscribe
(leave) as they please. Mailing lists also allow for association of
specific groups on closed lists. Furthermore, the archival function of
mailinglists allows for posterior accountability and analysis. The
downsides of mailinglists are similar to the ones generally associated
with e-mail, except that end-to-end encryption such as OpenPGP
{{RFC4880}} and S/MIME {{RFC5751}} are not possible because the final
recipients are not known. There have been experimental solutions to
address this issue such as Schleuder {{Schleuder}}, but this has not
been standardized or widely deployed.

This case relates to the following considerations in {{RFC8280}}:
	- Security
	- Privacy
	- Decentralization
	- Censorship Resistance
	- Open Standards
	- Confidentiality

### Multi-party video conferencing

Multi-party video conferencing protocols like WebRTC {{RFC6176}}
{{RFC7118}} allow for robust, bandwidth-adaptive, wideband and
super-wideband video and audio discussions in groups. 'The WebRTC
protocol was designed to enable responsive real-time communications
over the Internet, and is instrumental in allowing streaming video and
conferencing applications to run in the browser. In order to easily
facilitate direct connections between computers (bypassing the need
for a central server to act as a gatekeeper), WebRTC provides
functionality to automatically collect the local and public IP
addresses of Internet users (ICE or STUN). These functions do not
require consent from the user, and can be instantiated by sites that a
user visits without their awareness. The potential privacy
implications of this aspect of WebRTC are well documented, and certain
browsers have provided options to limit its behavior.'
{{AndersonGuarnieri}}.

Even though some multi-party video conferencing tools facilitate
freedom of assembly and association, their own configuration might
might pose concrete risks for those who use them. One the one hand
WebRTC is providing resilient channels of communications, but on the
other hand it also exposes information about those who are using the
tool which might lead to increased surveillance, identification and
the consequences that might be derived from that. This is especially
concerning because the usage of a VPN does not protect against the
exposure of IP addresses {{Crawford}}.

The risk of surveillance is also true in an offline space, but this is
generally easy to analyze for the end-user. Security and privacy
expectations of the end-user could be either improved or made
explicit. This in turn would result in a more secure and/or private
exercise of the right to freedom of assembly or association.

This case relates to the following considerations in {{RFC8280}}:
	- Security
	- Privacy
	- Decentralization
	- Censorship Resistance
	- Open Standards
	- Anonymity
	- Confidentiality

### Internet Relay Chat

Internet Relay Chat (IRC) is an application layer protocol that
enables communication in the form of text through a client/server
networking model {{RFC2810}}. In other words, a chat service. IRC
clients are computer programs that a user can install on their
system. These clients communicate with chat servers to transfer
messages to other clients.

For order to be kept within the IRC network, special classes of users
become "operators" and are allowed to perform general maintenance
functions on the network: basic network tasks such as disconnecting
(temporary or permanently) and reconnecting servers as needed
{{RFC2812}}. One of the most controversial power of operators is the
ability to remove a user from the connected network by 'force', i.e.,
operators are able to close the connection between any client and
server {{RFC2812}}.

IRC servers may deploy different policies for the ability of users to
create their own channels or 'rooms', and for the delegation of
'operator'-rights in such spaces. Some IRC servers support SSL/TLS
connections for security purposes {{RFC7194}} which helps stop the use
of packet sniffer programs to obtain the passwords of IRC users, but
has little use beyond this scope due to the public nature of IRC
channels. TLS connections require both client and server support (that
may require the user to install TLS binaries and IRC client specific
patches or modules on their computers). Some networks also use TLS for
server to server connections, and provide a special channel flag (such
as +S) to only allow TLS-connected users on the channel, while
disallowing operator identification in clear text, to better utilize
the advantages that TLS provides.

This case relates to the following considerations in {{RFC8280}}:
	- Security
	- Privacy
	- Censorship Resistance

## Peer-to-peer networks and systems

At the organizational level, peer production is one of the most
relevant innovations from Internet mediated social
practices. According to {{Benkler}} these networks imply 'open
collaborative innovation and creation, performed by diverse,
decentralized groups organized principally by neither price signals
nor organizational hierarchy, harnessing heterogeneous motivations,
and governed and managed based on principles other than the residual
authority of ownership implemented through contract.' {{Benkler}}.

In his book The Wealth of Networks, Benkler significantly expands on
his definition of commons-based peer production. In his view, what
distinguishes commons-based production is that it doesn't rely upon or
propagate proprietary knowledge: "The inputs and outputs of the
process are shared, freely or conditionally, in an institutional form
that leaves them equally available for all to use as they choose at
their individual discretion." {{Benkler}} To ensure that the knowledge
generated is available for free use, commons-based projects are often
shared under an open license.

### Peer-to-peer system architectures

Peer-to-peer (P2P) is essentially a model of how people interact in
real life because "we deal directly with one another whenever we wish
to" {{Vu}}. Usually if we need something we ask our peers, who in turn
refer us to other peers. In this sense, the ideal definition of P2P is
that "nodes are able to directly exchange resources and services
between themselves without the need for centralized servers" where
each participating node typically acts both as a server and as a
client {{Vu}}. RFC 5694 has defined it as peers or nodes that should
be able to communicate directly between themselves without passing
intermediaries, and that the system should be self-organizing and have
decentralized control {{RFC5694}}. With this in mind, the ultimate
model of P2P is a completely decentralized system, which is more
resistant to speech regulation, immune to single points of failure and
has a higher performance and scalability. Nonetheless, in practice
some P2P systems are supported by centralized servers and some others
have hybrid models where nodes are organized into two layers: the
upper tier servers and the lower tier common nodes {{Vu}}.

Since the ARPANET project, the original idea behind the Internet was
conceived as what we would now call a peer-to-peer system
{{RFC0001}}. Over time it has increasingly shifted towards a
client/server model with "millions of consumer clients communicating
with a relatively privileged set of servers" {{NelsonHedlun}}.

Whether for resource sharing or data sharing, P2P systems are enabling
freedom of assembly and association. Not only do they allow for
effective dissemination of information, but they leverage computing
resources by diminishing costs allowing for the formation of open
collectives at the network level. At the same time, in completely
decentralized systems the nodes are autonomous and can join or leave
the network as they want -a characteristic that makes the system
unpredictable: a resource might be only sometimes available, and some
other resources might be missing or incomplete {{Vu}}. Lack of
information might in turn makes association or assembly more
difficult.

Additionally, when architecturally assessing the role of P2P systems
we could say that: "the main advantage of centralized P2P systems is
that they are able to provide a quick and reliable resource
locating. Their limitation, however, is that the scalability of the
systems is affected by the use of servers. While decentralized P2P
systems are better than centralized P2P systems in this aspect, they
require a longer time in resource locating. As a result, hybrid P2P
systems have been introduced to take advantage of both centralized and
decentralized architectures. Basically, to maintain the scalability,
similar to decentralized P2P systems, there are no servers in hybrid
P2P systems. However, peer nodes that are more powerful than others
can be selected to act as servers to serve others. These nodes are
often called super peers. In this way, resource locating can be done
by both decentralized search techniques and centralized search
techniques (asking super peers), and hence the systems benefit from
the search techniques of centralized P2P systems." {{Vu}}

This case relates to the following considerations in {{RFC8280}}:
	- Security
	- Privacy
	- Decentralization
	- Censorship Resistance
	- Open Standards
	- Anonymity
	- Heterogeneity Support
	- Integrity
	- Authenticity
	- Adaptability

### Version control

Ever since developers needed to collaboratively write, maintain and
discuss large code basis for the Internet there have been different
approaches of doing so. The easiest approach has been discussing code
through mailing lists even though this has proven to be hard when
maintaining the most recent versions, which is why versión control
systems ultimately make sense.

A version control system is a piece of software that enables
developers on a software team to work together and also archive a
complete history of their work {{Sink}}. This allows teams to be
working simultaneously on updated versions. According to Sink, broadly
speaking, the history of version control tools can be divided into
three generations. In the first one, concurrent development meant that
only one person could be working on a file at a time. The second
generation tools permit simultaneous modifications as long as users
merge the current revisions into their work before they are allowed to
commit. The third generation tools allow merge and commit to be
separated {{Sink}}.

Interestingly no version control system has ever been standardized in
the IETF whereas the version control systems like Subversion and Git
are widely used within the community and working groups. There has
been a spirited discussion on whether working groups should use
centralized forms of the Git protocol, such as those offered by Gitlab
or Github. Proponents argue that this simplifies the workflow and
allows for more transparency. Opponents argue that the reliance on a
centralized service which is not merely using the Git protocol but
also uses non-standardized options like an Issue-Tracker, makes the
process less transparent and reliant on a third party.

The IETF has not made a decision on the use of centralized instances
of Git, such as Github or Gitlab. There have been two efforts to
standardize the workflow vis a vis these third party services, but
these haven't come to fruition: {{Wugh}} {{GithubIETF}}.

This case relates to the following considerations in {{RFC8280}}:
	- Security
	- Decentralization
	- Open Standards
	- Heterogeneity Support
	- Integrity
	- Authenticity
	- Adaptability

## Grouping together (identities)

Collective identities are also protected by freedom of association and
assembly. According to Melucci these are 'shared definitions produced
by several interacting individuals who are concerned with the
orientation of their action as well as the field of opportunities and
constraints in which their action takes place.' {{Melucci}} In this
sense, assemblies and associations are an important base in the
maintenance and development of culture, as well as preservation of
minority identities {{OSCE}}.

### DNS

Domain names allow hosts to be identified by human parsable
information. Whereas an IP address might not be the expression of an
identity, a domain name can be and often is. The grouping of certain
identities under specific domains or even Top Level Domains are risky:
connecting an identity to a hierarchically structured identifier
systems creates a central attack surface which allows for an easier
surveillance of the services running on the domain, domain based
censorship {{RFC7754}}, or impersonation of the domain through DNS
cache poisoning. The use of a centralized authority always makes
censorship through a registry or registrar possible, as well as by
using a fake resolver or using proposed standards such as DNS Response
Policy Zones {{RPZ}}. Several technologies have been developed in the
IETF to mitigate these risks such as DNS over TLS {{RFC7858}}, DNSSEC
{{RFC4033}}, DNS over HTTPS {{RFC8484}}. When these mitigations are
implemented, censorship will not be made impossible but it will be
made visible.

The structuring of DNS as a hierarchical authority structure also
brings about a specific characteristic, namely the possibility of
centralized policy making vis-á-vis the management and operation of
Top Level Domains, which is what happens partly at ICANN. The impact
of ICANN processes on human rights will not be discussed here.

This case relates to the following considerations in {{RFC8280}}:
	- Security
	- Privacy
	- Decentralization
	- Censorship Resistance
	- Anonymity
	- Heterogeneity Support
	- Integrity
	- Authenticity
	- Adaptability
	- Outcome Transparency

### Autonomous Systems

In order for edge-users to connect to the Internet, they need to be
connected to an Autonomous System (AS) which, in turn, has peering or
transit relations with other AS'es. This means that in the process of
accessing the Internet, edge-users need to accept the policies and
practices of the intermediary that provides them access to the other
networks. In other words, for users to be able to join the 'network of
networks', they always need to connect through an intermediary.

While accessing the Internet through an intermediary, the user is
forced to accept the policies, practices and principles of a
network. This could impede the rights of the edge-user, depending on
the implemented policies and practices on the network and how (if at
all) they are communicated to them. For example: filtering, blocking,
extensive logging, slowing down connection or specific services, or
other invasive practices that are not clearly communicated to the
user.

In practice, the user must accept policies of ASes he has no
relationship with, and didn't choose. For instance, there is no way to
direct the packets to avoid the Five Eyes, not even to know after the
fact where the packet went. {{FiveEyes}} {{SchengenRouting}}
(Traceroutes give you an idea but the path may change before and after
the traceroute.) Given that it is not trivial for an edge-user to
operate an AS and engage in peering relation with other ASes, there
might not be another way for the edge-user to connect to the network
of networks. In this case, users are forced into accepting the
policies of a specific network. Such design, combined with the
increased importance of the Internet to make use of basic services,
forces edge-users to associate with a specific network without
consenting -or even knowing- the policies of the network.

Additionally, it can be noted that there is no standard and deployed
way for the edge-user to choose the routes her packets will go
through. {{RFC0791}} section 3.1 standardized "source routing" and
"record route" but neither were deployed, mainly because of serious
security issues.

This case relates to the following considerations in {{RFC8280}}:
	- Security
	- Privacy
	- Decentralization
	- Censorship Resistance
	- Anonymity
	- Heterogeneity Support
	- Integrity
	- Authenticity
	- Adaptability
	- Outcome Transparency

Discussion: Establishing the relation
=====================================

The case studies show that the Internet infrastructure, the
combination of architecture and protocols, facilitates freedom of
association and assembly, by allowing groups of people to converse,
collaborate, exchange, and build and maintain identities in both
structural and occasional manners. The structural forms of group
activities are more related to freedom of association, whereas freedom
of assembly often has a more incidental nature. The difference between
the two, as mentioned, is a gradual one. This is equally true to the
infrastructural mediations of these rights.

Whereas we established that the Internet infrastructure facilitates
freedom of association and assembly, by its very technical and
material nature, it both creates and limits the spaces for it. This is
an interesting tension because juridically only lawful limitations to
the rights are allowed, and even then only if they are necessary, and
proportionate. This exposes legal implications of the characteristics
of the Internet infrastructure.

These preliminary finding suggest that the properties and
characteristic through which the Internet infrastructure enables and
inhibits freedom of assemblies and association should also be analyzed
from a legal lens. The case studies have pointed out several caveats
in implementations, that might not necessarily be understood by people
while exercising their right to association of assembly, and which
thus should either be mitigated, or at least, be communicated to the
rights holders.

Discussion: Protocols and Platforms
===================================

Whereas the Internet is a network of networks, and can therefore be
understood as an assembly, applications on top of the Internet do not
necessarily inherit the same structure. Quite the opposite, the
Internet increasingly becomes a vehicle for commercial, proprietary
and non-interoperable platforms. This lack of interoperation is
harming the ability of people to set or negotiate their own terms on
which they would like to assemble or associate, or host their own
interoperating services.

Even though the Internet has always allowed for (partially) closed-off
networks, the current trend shows the rise of a small number of very
large non-interoperable platforms. Chat has moved from XMPP and IRC to
Facebook Messenger, Whatsapp and WeChat and there has been a strong
rise of social media networks with large numbers of users, such as
Facebook, Twitter and Instagram. A similar trend can be found among
e-mail providers, with the significant difference that e-mail is
interoperable.

Often these non-interoperable platforms are built on open-protocols
but do not allow for inter-operability or data-portability. In the
case of large private platforms, this in turn leads to strong network
externalities also know as a network effect; because the users are
there, users will be there. Even though social-media platforms have
enabled groups to associate, they have also led to a 'tactical freeze'
because of the inability to change the platforms {{Tufekci}}.

Whereas these networks are a ready-to-hand networked public sphere,
they do not allow their inhabitants to change or fully understand
their workings. In a near future, this could potentially impact
infrastructure itself and the distributed nature of the Internet
{{RFC1287}}.

Conclusions
===========

Communities, collaboration and joint action lie at the heart of the
Internet. Even at at linguistical level, the words "networks” and
“associations” are close synonyms. Both interconnected groups and
assemblies of people depend on “links” and “relationships”
{{Swire}}. Taking legal definitions given in international human
rights law jurisprudence, we could assert that the right to freedom of
assembly and association protect collective expression. These rights
protect any collective, gathered either permanently or temporarily for
"peaceful" purposes. It is voluntary and uncoerced.

Given that the Internet itself was originally designed as a medium of
communication for machines that share resources with each other as
equals {{RFC0903}}, the Internet is now one of the most basic
infrastructures for the right to freedom of assembly and
association. Since Internet protocols and the Internet architecture
play a central role in the management, development and use of the
Internet, we established the relation between some protocols and the
right to freedom of assembly and association.

After reviewing several typical representative cases, we can conclude
that the way in which infrastructure is designed and implemented
impacts people's ability to exercise their freedom of assembly and
association. This is because different technical designs come with
different properties and characteristics. These properties and
characteristics on the one hand enable people to assemble and
associate, but on the other hand also adds limiting, or even
potentially endangering, characteristics. More often than not, this
depends on the context. A clearly identified group for open
communications, where messages are sent in cleartext and where peoples
persistent identities are viisble, can help to faciliate an assembly
and build trust, but in other context the same configuration could
pose a significant danger. Endangering characteristics should be
mitigated, or at least clearly communicated to the users of these
technologies.

Lastly, the increasing shift towards closed and non-interoperable
platforms in chat and social media networks have a significant impact
on the distributed and open nature of the Internet. Often these
non-interoperable platforms are built on open-protocols but do not
allow for inter-operability or data-portability. The use of
social-media platforms has enabled groups to associate, but is has
also rendered users unable to change platforms, therefore leading to a
sort of "forced association" that inhibits people to fully exercise
their freedom of assembly and association.

Acknowledgements
================

- Fred Baker, Jefsey, and Andrew Sullivan for work on Internet
  definitions.

- Stephane Bortzmeyer for several concrete text suggestions that found
  their way in this document (such as the AS filtering example).

- Mark Perkins and Gurshabad for finding a lot of typos.

- Gurshabad Grover and an anonymous reviewer for a full review.

- The hrpc mailinglist at large for a very constructive discussion on
  a hard topic.

Security Considerations
=======================

As this draft concerns a research document, there are no security
considerations.


IANA Considerations
===================

This document has no actions for IANA.

Research Group Information
==========================

The discussion list for the IRTF Human Rights Protocol Considerations
Research Group is located at the e-mail address
<hrpc@ietf.org>. Information on the group and information on how to
subscribe to the list is at
<https://www.irtf.org/mailman/listinfo/hrpc>

Archives of the list can be found at:
<https://www.irtf.org/mail-archive/web/hrpc/current/index.html>
