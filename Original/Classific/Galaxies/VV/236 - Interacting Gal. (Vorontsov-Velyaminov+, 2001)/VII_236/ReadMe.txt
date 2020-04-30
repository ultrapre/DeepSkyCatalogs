Byte-by-byte Description of file: catalog.dat
--------------------------------------------------------------------------------
   Bytes Format Units   Label     Explanations
--------------------------------------------------------------------------------
   1-  4  I4        ---       VV      ? VV-designation of the galaxy (1)
       5  A1        ---     m_VV      [Aab] Multiplicity index on VV
       6  A1        ---     n_VV      [=] = when the galaxy has two VV numbers,
                                              the second VV number being in OName
       7  A1        ---       Seq     Letter that identifies connected lines
                                       with no VV number
       8  A1        ---       Con     [+] Connected lines (2)
       9  A1        ---       Rem1    [{] Bracket connects two positions of
                                          interacting galaxies, whose following
                                          other parameters are given as mean ones
  10- 11  I2        h         RAh     ? Right ascension of the galaxy (J2000)
  13- 14  I2        min       RAm     ? Right ascension of the galaxy (J2000)
  16- 19  F4.1      s         RAs     ? Right ascension of the galaxy (J2000)
      21  A1        ---       DE-     Declination sign of the galaxy (J2000)
  22- 23  I2        deg       DEd     ? Declination of the galaxy (J2000)
  25- 26  I2        arcmin    DEm     ? Declination of the galaxy (J2000)
  28- 29  I2        arcsec    DEs     ? Declination of the galaxy (J2000)
      30  A1        ---       Note    [*] Remarks on separate sources (3)
      31  A1        ---       Rem2    [{] Bracket connects following values of two
                                        interacting galaxies for giving mean values
  32- 36  F5.2      mag       m       ? Magnitude of galaxy  (4)
      37  A1        ---     u_m       Uncertainty flag on m
  39- 46  A8 0.1    arcmin    D       ? Angular dimensions of galaxy in 0.1arcmin
                                        from NED or MCG
      47  A1        ---       Rem3    [{] Bracket connects following values of two
                                       interacting galaxies for giving mean values
  48- 52  I5        km/s      RVopt   ? Radial velocity of the galaxy from
                                        optical observations according to
                                        de Vaucouleurs RC3 catalogue (VII/155)
      53  A1        ---     n_RVopt   [NS] North (N) or South (S) part of galaxy
      54  A1        ---     u_RVopt   [?] Uncertainty flag on RVopt
      55  A1        ---     o_RVopt   [*] '*' data from NED but not in RC3
  57- 62  F6.4      ---       z       ? Redshift
      63  A1        ---     o_z       [*] '*' data from NED but not in RC3
  65- 69  I5        km/s      RVrad   ? Radial velocity of the galaxy from radio
                                        observations according to de Vaucouleurs
                                        RC3 catalogue (VII/155)
      70  A1        ---     u_RVrad   [? ] Uncertainty flag on RVrad
      71  A1        ---     o_RVrad   [*] '*' data from NED but not in RC3
      72  A1        ---       IR      [+-] Information on IRAS sources:
                                            +: existence of IRAS source,
                                            -: lack of IRAS data
      75  A1        ---       R       [+-] Information on radio data:
                                            + : existence of radio source,
                                            - : lack of radio data
  77- 80  A4        ---       TType   Morphological type of the galaxy:
                                        S: spiral, E: elliptical, I: irregular
  81- 85  A5        ---       ITType  Type of the interaction (5)
      86  A1        ---     u_ITType  [: ] Uncertainty flag on ITypt
  87- 96  A10       ---       MCG     Identification with MCG
      97  A1        ---     m_MCG     [abc] Multiplicity index on MCG
      98  A1        ---     u_MCG     [):] ")" uncertain,
                                           ":" wrong MCG name for VV160 (+09-19-00A)
     100  A1        ---       Rem4    [{] Bracket connects following values of two
                                        interacting galaxies for giving mean values
 101-104  I4        ---       NGC     ? NGC or IC identification
     105  A1        ---     m_NGC     [AB] Multiplicity index on NGC
     106  A1        ---     n_NGC     [*] '*': IC instead NGC,
     107  A1        ---     u_NGC     [?] Uncertainty flag on NGC identification
 109-114  A6        ---       Zw      ? Identification with Zw
 116-119  I4        ---       Mrk     ? Identification with Mrk
 121-124  I4        ---       Arp     ? Identification with Arp
     125  A1        ---       ---     [,] '=': galaxy has both number
 127-131  I5        ---       UGC     ? Identification with UGC
     132  A1        ---     u_UGC     [?] '?': marks uncertainty on UGC
 133-145  A13       ---       OName   Other name
--------------------------------------------------------------------------------