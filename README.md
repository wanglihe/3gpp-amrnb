3gpp-amrnb
==========

amrnb codec from 3gpp official websit http://www.3gpp.org/DynaReport/26104.htm

These word comes from official document:

This Technical Standard (TS) contains an electronic copy of the ANSI-C code for
a floating-point implementation of the Adaptive Multi-Rate codec. This
floating-point codec speci fication is mainly targeted to be used in multimedia
applications such as the 3G-324M terminal specified in 3GPP TS 26.110,
or in packet-based (e.g., H.323) applications.
The bit-exact fixed-point ANSI-C code in 3GPP TS 26.073 remains the preferred implementation for all applications,
but the floating-point codec may be used instead of the fixed-point codec when the implementation platform is better
suited for a floating-point implementation. It has been verified that the fixed-point and floating-point codecs
interoperate with each other without any artefacts.

The floating-point ANSI-C code in this specification is the only standard conforming non-bit-exact implementation of
the Adaptive Multi Rate speech transcoder (3GPP TS 26.090 [2]), Voice Activity Detection (3GPP TS 26.094 [6]),
comfort noise generation (3GPP TS 26.092 [4]), and source controlled rate operation (3GPP TS 26.093 [5]). The
floating-point code also contains example solutions for substituting and muting of lost frames (3GPP TS 26.091 [3]).

**The fixed-point specification in 26.073 shall remain the only allowed implementati
on for the 3G mandatory
speech service and the use of the floating-point codec is strictly limited to
other services.**

The floating-point encoder in this specification is a non-bit-exact implementation of the fixed-point encoder producing
quality indistinguishable from that of the fixed-point encoder. The decoder in this specification is functionally a
bit-exact implementation of the fixed-point decoder, but the
code has been optimized for speed and the standard fixed-point libraries are not used as such.

license
=======

I don't know what license it is using, all these code can get from official
freely.
