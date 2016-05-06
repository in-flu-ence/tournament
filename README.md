# Swiss Pairing Tournament (P2)

The Swiss Pairing Tournament is a python toolkit to allow user to generate a swiss pairing list for different tournaments.

Features:
1. Muliple tournament entry available
2. Provide player standing & score according to the reported win (3pt)/lose (0pt)/draw(1pt)
3. A skipped round win is assigned to the top player if the number of total registered number is odd.
4. Opponent Match Win assigned in standing position with players of equal score
5. No rematch allowed during the pairing process

## Table of Content

* [Quick start](#quick-start)
* [Bugs reporting](#bugs-reporting)
* [Contributor](#contributor)

## Quick start

* [Install Python](https://www.python.org/downloads/). This code is written and tested in Python 3.5.0. 
However, it should be backward compatible with previous versions of Python.
* Clone github repository "tournament" to local drive 
* Execute 'tournament.sql' in PostgreSQL
* Run 'tournament_test.py' in your Python console.

### What's in this code

Within the extracted folder, you will find the following files

`tournament_test.py` - Default test code for error check on the swiss pairing system

`tournament.py` - Various functions for the swiss pairing system

`tournament.sql` - Postgre SQL script to create the relevant tables

## Bugs reporting

Found a bug or a movie request? Please contact the Contributor.

## Contributor

**Harris Ngan**

**Udacity Team**
