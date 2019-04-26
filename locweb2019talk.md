% **WebLoc Through Mobile Phone Datasets**
% **Leo Ferres**\
  UDD & Telefónica R+D, Chile\
  `lferres@udd.cl`\
  FB, IG, Tw: leoferres
% LocWeb Workshop, WWW'19\
	San Francisco, May 13, 2019\
	\tiny s2019-01-19 09:47:32 -0300 - e:2019-04-23 11:23:33 -0400\normalsize

# Introduction

# Prelims: Geo

All this work has been done in Santiago de Chile.

# Prelims: Telephony

- CDR (**C**all **D**etail **R**ecord) a tuple $\langle n_a, n_b, t_a,
  t_b, d, r\rangle$ (used mainly for billing minutes...)

- XDR (e**X**tended **D**etail **R**ecord) a tuple $\langle n_a, t_a,
  d, k\rangle$ (used mainly for billing data usage)

- DPI (**D**eep **P**acket **I**nspection) a tuple $\langle n_a, t_a,
  d, k, p\rangle$ (used mainly for data bandwidth allocation, but seldom)

- !(CP (**C**ontrol **P**lane), not used let alone persisted, network
  events: handovers, shakes, etc.)

\scriptsize where $n$ is a phone number (hashed), $t$ is the lat/lon of a tower,
$d$ is a timestamp, $r$ is duration, $k$ is bytes downloaded and $p$
is the ``protocol'' (the app's code... hand-labeled (!)) \normalsize

# Prelims: Towers of antennas

![Active SCL towers in May-July, 2016](towers.jpg){ width=70% }

# CDR

- Sparse in time and coarse in space
- Gender

# XDR

- dense in time, coarse in space
- Mallmob, Pokemon GO

# DPI

- Apps, Twitter?, News

# Privacy considerations
