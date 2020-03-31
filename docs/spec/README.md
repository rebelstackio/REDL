Request For Comments
Category: Informational/Experimental

Rein Petersen  (rebelstack.io)
Javier Galarza (rebelstack.io)

# REST Endpoint Definition Language ( REDL )

## Status of this memo
This document specifies an experimental machine-able description language which can describe important elements of REST service endpoints.

1. Introduction
  For the purposes of this document, a REST(ful) service endpoint is a web service which generally adheres to "Representational state transfer"
   
      [REST]     Fielding, R., "Architectural Styles and the Design of
              Network-based Software Architectures",
              Doctoral Dissertation, University of California, Irvine,
              September 2000,
              <http://roy.gbiv.com/pubs/dissertation/top.htm>.


2. Motivation
  With the proliferation of RESTful web services, we need an extensible and machine-able method for describing common elements of a
  service. It must permit specificity sufficient to allow the construction of consuming services/software which leaves no ambiguity.
  It may, optionally, provide a common means of fetching a description for any service or group of services over HTTP(S).
