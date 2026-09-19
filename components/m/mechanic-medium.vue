<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#im0wb4T)" class="m1i1rlbvk"/><g filter="url(#iX0q0zd)"><path class="u7j5qywzc"/></g><path class="m3se_ob2r"/><path fill="url(#i4RHwye)" class="zqss5obsp"/><path fill="url(#i86fP2c)" class="zqss5obsp"/><path fill="url(#iGxIi3d)" class="zqss5obsp"/><path class="llp516bpm"/><path fill="url(#ioCT77d)" class="xn6dhjjio"/><path fill="url(#if8dKTc)" class="xn6dhjjio"/><path fill="url(#i77Ytid)" class="xn6dhjjio"/><path fill="url(#i8Zzivd)" class="kvfq7h_0m"/><path fill="url(#iE5Ofte)" class="kvfq7h_0m"/><path fill="url(#iE6iQae)" class="kvfq7h_0m"/><path fill="url(#iTdOGsd)" class="vqc4qgzhu"/><path fill="url(#iJIw8ya)" class="vqc4qgzhu"/><path fill="url(#i1AZebc)" class="dvr2s59yl"/><path fill="url(#iX9JgNb)" class="dvr2s59yl"/><path fill="url(#idlbkMe)" class="rom2yrbwh"/><path fill="url(#iIvEVud)" class="rom2yrbwh"/><path fill="url(#iXRw9pd)" class="rom2yrbwh"/><path fill="url(#iz9xh1o)" class="rom2yrbwh"/><path fill="url(#ixge7fe)" class="rom2yrbwh"/><g filter="url(#iMpmyBt)"><path fill="url(#i1uMIud)" class="lwc2zdrqr"/></g><g filter="url(#ikmUDac)"><path fill="url(#iPXFJHe)" class="momee7bch"/></g><g filter="url(#irxewVh)"><path class="v82ztsbvy"/></g><g filter="url(#iJLDNFd)"><path class="vcv8c754j"/><path fill="url(#iU8Jczd)" class="u1e8ikbzb"/><path fill="url(#ibXRrGc)" class="u1e8ikbzb"/><path fill="url(#i9sxEsb)" class="u1e8ikbzb"/></g><g filter="url(#i4qjdud)"><path class="z5g21op2e"/></g><g filter="url(#icuNE6b)"><path fill="url(#ifKU5mc)" class="pimvl5kot"/><path fill="url(#iSwnSae)" class="pimvl5kot"/><path fill="url(#iWwBHGd)" class="pimvl5kot"/><path fill="url(#iviU92d)" class="pimvl5kot"/><path fill="url(#iJJBG7d)" class="pimvl5kot"/></g><g filter="url(#illG7Tc)"><path stroke="url(#iBO8D2b)" class="cjq4b16bn"/></g><g filter="url(#i4kcvQd)"><path stroke="url(#ijHs0Pe)" class="luyfkt2yj"/></g><g filter="url(#iCLcnqd)"><path stroke="url(#i9Ji0Wc)" class="eqaszhbhb"/></g><path fill="url(#iNMW70c)" class="z1mrz_gsv"/><path fill="url(#iu3QH3j)" class="isnxvrbfh"/><path fill="url(#iwArbHb)" class="yyp9ebbtr"/><path fill="url(#iBFk1zc)" class="w2zd_abhh"/><g filter="url(#iZnNsRM)"><path fill="url(#isDTigc)" class="n1djunb7v"/><path fill="url(#iu0iUHV)" class="n1djunb7v"/></g><path fill="url(#itXsDSb)" class="n1djunb7v"/><path fill="url(#it9UeLe)" class="n1djunb7v"/><path fill="url(#i1zGJxe)" class="n1djunb7v"/><path fill="url(#iVHkgsL)" class="n1djunb7v"/><path fill="url(#i3YY5fc)" class="n1djunb7v"/><path fill="url(#i0Dnpde)" class="n1djunb7v"/><path fill="url(#iMWPZSO)" class="n1djunb7v"/><path fill="url(#ikQh58h)" class="n1djunb7v"/><path fill="url(#i19hGXd)" class="n1djunb7v"/><g filter="url(#iwmQV2d)"><path class="g9kocifrb"/></g><g filter="url(#ikksZPd)"><path class="uh-jw6opt"/><path fill="url(#iLFw5Fd)" class="hdap23b-n"/><path fill="url(#iWGwxYc)" class="hdap23b-n"/><path fill="url(#ik4v7zC)" class="hdap23b-n"/><path fill="url(#iroR3be)" class="hdap23b-n"/><path fill="url(#ism8t3c)" class="hdap23b-n"/></g><g filter="url(#iYDEzrb)"><path stroke="url(#igtIsGc)" class="n6ddjcztw"/></g><path fill="url(#iM8Dy6A)" class="dnlpn5c4m"/><g filter="url(#iMT6tnb)"><path class="hvvawt4nw"/></g><g filter="url(#ioLW4Zd)"><path class="zbbicibto"/></g><path class="n2_xvjdcg"/><path fill="url(#i9addyc)" class="rf9vqhkak"/><path class="viezl_bba"/><g filter="url(#iAGQZjc)"><path class="t87tthbwf"/><path fill="url(#igzEI2O)" class="l7-eynbdn"/></g><g filter="url(#izZaStc)"><path fill="url(#iYCysHd)" class="my1ko-bwx"/></g><path class="r_7zco6vk"/><path fill="url(#iWS2Mbp)" class="qmyvahb1h"/><path class="xkfkdpb1x"/><g filter="url(#iMt565a)"><path fill="url(#im7mDib)" class="rdea4ibyq"/></g><g filter="url(#iW0Qd4K)"><ellipse transform="rotate(-27.914 13.256 9.668)" class="tjuuvfmso"/><ellipse fill="url(#ioIBi5d)" transform="rotate(-27.914 13.256 9.668)" class="mqzcoevnf"/></g><path fill="url(#iim9Mlm)" class="gx30_upqx"/><path fill="url(#iFLETjI)" class="gx30_upqx"/><path fill="url(#iNj5Gle)" class="gx30_upqx"/><path fill="url(#i4C0J3d)" class="gx30_upqx"/><path fill="url(#iJrOasW)" class="b215l7b2u"/><path fill="url(#ioirgHb)" class="b215l7b2u"/><g filter="url(#i3XgZQt)"><path fill="url(#iDOQoOd)" class="elibtcceq"/></g><g filter="url(#iu9Vsbe)"><path fill="url(#itXpQ8w)" class="jtr0qabgf"/></g><g filter="url(#i6ti4Td)"><path class="s0_i_obqx"/></g><g filter="url(#iDSnA0d)"><path class="mj2-v7r_j"/></g><g filter="url(#iLyY5zd)"><path fill="url(#i0vaKQd)" class="s2-xryl0i"/></g><g filter="url(#iZ4mtvb)"><path fill="url(#iIvrIye)" class="psv7auxid"/></g><defs><radialGradient id="iGxIi3d" cx="0" cy="0" r="1" gradientTransform="rotate(131.119 3.397 11.463)scale(2.81867 4.68292)" gradientUnits="userSpaceOnUse"><stop offset=".203" class="qunsngokg"/><stop offset="1" class="zsyglhsdv"/></radialGradient><radialGradient id="i77Ytid" cx="0" cy="0" r="1" gradientTransform="rotate(123.951 4.148 12.705)scale(2.98327 2.1547)" gradientUnits="userSpaceOnUse"><stop class="f7vxzf2re"/><stop offset="1" class="bjz-35bmd"/></radialGradient><radialGradient id="i8Zzivd" cx="0" cy="0" r="1" gradientTransform="matrix(2.70871 0 0 14.0625 6.066 30)" gradientUnits="userSpaceOnUse"><stop class="g21-8bc8z"/><stop offset="1" class="uhp0yeb2h"/></radialGradient><radialGradient id="iE5Ofte" cx="0" cy="0" r="1" gradientTransform="matrix(-2.2813 6.68749 -5.49369 -1.87406 9.223 17.781)" gradientUnits="userSpaceOnUse"><stop class="ghamttb0q"/><stop offset="1" class="z1an05bwi"/></radialGradient><radialGradient id="iE6iQae" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.2187 2.59375 0 9.223 30.438)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="z8optlbcz"/><stop offset="1" class="gmjyv1b7b"/></radialGradient><radialGradient id="iJIw8ya" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.3125 -1.98 0 24.755 21.938)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="cbe6sn2ns"/><stop offset="1" class="gvyr5190s"/></radialGradient><radialGradient id="i1AZebc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.99943 1.36453 -1.33986 -1.96328 27.592 23.749)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="v0ox3l-0u"/><stop offset="1" class="x78tqlban"/></radialGradient><radialGradient id="iX9JgNb" cx="0" cy="0" r="1" gradientTransform="matrix(.78818 -.60013 .4599 .60401 27.001 23.598)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="ruv4dbc7o"/><stop offset="1" class="meeoi68df"/></radialGradient><radialGradient id="idlbkMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -12.1153 44.4939 0 15.79 29.983)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="s8-qpgb5g"/><stop offset="1" class="o5bua8boy"/></radialGradient><radialGradient id="iIvEVud" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.875 5.37793 0 22.464 32.545)" gradientUnits="userSpaceOnUse"><stop class="zwo8xvbzg"/><stop offset="1" class="c-tzwtb6q"/></radialGradient><radialGradient id="ixge7fe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.59908 3.3973 -1.77851 -1.88415 10.554 15.318)" gradientUnits="userSpaceOnUse"><stop class="hfyjss5uq"/><stop offset="1" class="y9jato2vd"/></radialGradient><radialGradient id="ibXRrGc" cx="0" cy="0" r="1" gradientTransform="matrix(1.26563 -2.32812 2.70524 1.47064 23.707 20.906)" gradientUnits="userSpaceOnUse"><stop class="tdvgs2sbs"/><stop offset="1" class="tz6f6rbmx"/></radialGradient><radialGradient id="i9sxEsb" cx="0" cy="0" r="1" gradientTransform="rotate(53.424 -5.116 34.838)scale(2.25697 2.46612)" gradientUnits="userSpaceOnUse"><stop class="sf2388bnl"/><stop offset="1" class="ganm9fbbs"/></radialGradient><radialGradient id="iSwnSae" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.364 25.305)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iWwBHGd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.364 26.6)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iviU92d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.364 27.85)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iJJBG7d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.364 29.2)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iwArbHb" cx="0" cy="0" r="1" gradientTransform="matrix(.76433 2.06149 -2.44889 .90797 20.612 11.662)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="yc6yhhbng"/><stop offset="1" class="acsx37bmr"/></radialGradient><radialGradient id="iBFk1zc" cx="0" cy="0" r="1" gradientTransform="rotate(17.447 -34.843 37.29)scale(1.57981 4.87383)" gradientUnits="userSpaceOnUse"><stop class="a8hir8afg"/><stop offset=".746" class="o43_m0brr"/></radialGradient><radialGradient id="isDTigc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.83861 0 0 -8.49606 18.65 10.7)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="iu0iUHV" cx="0" cy="0" r="1" gradientTransform="rotate(121.348 7.552 7.938)scale(3.44586 2.85461)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="it9UeLe" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.0601 -10.8949 0 16.338 4.402)" gradientUnits="userSpaceOnUse"><stop offset=".742" class="kn12m3thp"/><stop offset="1" class="a7mg-t_7y"/></radialGradient><radialGradient id="i1zGJxe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17221 1.46143 0 18.28 9.36)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="iVHkgsL" cx="0" cy="0" r="1" gradientTransform="rotate(-89.793 11.42 -2.02)scale(1.11702 1.22465)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="i3YY5fc" cx="0" cy="0" r="1" gradientTransform="matrix(-8.73718 .54755 -1.38845 -22.15514 19.294 11.71)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="i0Dnpde" cx="0" cy="0" r="1" gradientTransform="matrix(3.4819 -2.97708 .87839 1.02734 8.78 7.911)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="iMWPZSO" cx="0" cy="0" r="1" gradientTransform="matrix(-.24132 2.54931 -1.02654 -.09717 21.465 7.723)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="ikQh58h" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8897 -1.7207 0 13.485 10.195)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="i19hGXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.78991 -9.53847 0 15.812 6.766)" gradientUnits="userSpaceOnUse"><stop offset=".094" class="u25b8uifi"/><stop offset="1" class="wzclzacav"/></radialGradient><radialGradient id="iWGwxYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .24917 -.78312 0 16.236 12.09)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="iroR3be" cx="0" cy="0" r="1" gradientTransform="matrix(-1.72721 .76568 -1.23051 -2.77577 16.355 11.508)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="iM8Dy6A" cx="0" cy="0" r="1" gradientTransform="matrix(2.2273 -1.095 4.4055 8.96102 15.259 14.4)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="i9addyc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82817 -1.3173 0 17.988 9.766)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="igzEI2O" cx="0" cy="0" r="1" gradientTransform="matrix(-.23674 -.30507 .42 -.32593 17.755 9.852)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iWS2Mbp" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82822 -1.31737 0 13.533 9.766)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ioIBi5d" cx="0" cy="0" r="1" gradientTransform="matrix(-.0079 -.50435 .60625 -.0095 13.24 9.99)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iFLETjI" cx="0" cy="0" r="1" gradientTransform="matrix(.6416 2.28987 -2.18472 .61214 20.474 9.78)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="iNj5Gle" cx="0" cy="0" r="1" gradientTransform="matrix(.80415 -1.10356 .925 .67403 20.841 10.336)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="i4C0J3d" cx="0" cy="0" r="1" gradientTransform="rotate(-69.263 18.089 -9.916)scale(1.69226 2.2611)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="ioirgHb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6927 0 0 -1.88734 10.742 10.437)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="iDOQoOd" cx="0" cy="0" r="1" gradientTransform="matrix(-.93552 .16058 -.16465 -.9592 10.793 10.438)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><radialGradient id="i0vaKQd" cx="0" cy="0" r="1" gradientTransform="rotate(-158.919 10.694 2.553)scale(8.7748 8.41903)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="iodgi0b6i"/><stop offset="1" class="xh-hzrtoi"/></radialGradient><radialGradient id="iIvrIye" cx="0" cy="0" r="1" gradientTransform="rotate(139.529 8.817 5.504)scale(8.95518 9.18704)" gradientUnits="userSpaceOnUse"><stop class="pvjcf1omm"/><stop offset=".682" class="o2y-twbma"/><stop offset="1" class="x2409oaqt"/></radialGradient><linearGradient id="im0wb4T" x1="12.035" x2="21.723" y1="23.156" y2="18.344" gradientUnits="userSpaceOnUse"><stop class="d__di5b1k"/><stop offset="1" class="ldn_ouzqy"/></linearGradient><linearGradient id="i4RHwye" x1="14.633" x2="13.974" y1="19.957" y2="19.239" gradientUnits="userSpaceOnUse"><stop class="ptx8-dg4d"/><stop offset="1" class="m1cydckkt"/></linearGradient><linearGradient id="i86fP2c" x1="11.699" x2="12.504" y1="18.875" y2="18.875" gradientUnits="userSpaceOnUse"><stop class="a969r93lb"/><stop offset="1" class="zsyglhsdv"/></linearGradient><linearGradient id="ioCT77d" x1="19.938" x2="18.313" y1="19.527" y2="19.527" gradientUnits="userSpaceOnUse"><stop class="z9cu3vbra"/><stop offset="1" class="ul2cu2h0c"/></linearGradient><linearGradient id="if8dKTc" x1="17" x2="17.938" y1="20.105" y2="19.027" gradientUnits="userSpaceOnUse"><stop class="h5mxx_cud"/><stop offset="1" class="c5x-f3bwv"/></linearGradient><linearGradient id="iTdOGsd" x1="23.473" x2="23.473" y1="29.781" y2="23.531" gradientUnits="userSpaceOnUse"><stop class="unsdl8pjp"/><stop offset="1" class="r0l64jbzx"/></linearGradient><linearGradient id="iXRw9pd" x1="8.441" x2="9.059" y1="29.973" y2="29.953" gradientUnits="userSpaceOnUse"><stop offset=".203" class="t2xb9pb8a"/><stop offset="1" class="oh9185bnq"/></linearGradient><linearGradient id="iz9xh1o" x1="23.232" x2="22.627" y1="30" y2="30" gradientUnits="userSpaceOnUse"><stop class="hwgxlbc5v"/><stop offset="1" class="z4q6dwvkw"/></linearGradient><linearGradient id="i1uMIud" x1="12.43" x2="12.43" y1="23.95" y2="27.53" gradientUnits="userSpaceOnUse"><stop class="qcmtsylcx"/><stop offset="1" class="o7pw9mb8f"/></linearGradient><linearGradient id="iPXFJHe" x1="12.43" x2="12.43" y1="24.45" y2="27.03" gradientUnits="userSpaceOnUse"><stop class="d337rwvie"/><stop offset=".752" class="n5xzb8_yo"/></linearGradient><linearGradient id="iU8Jczd" x1="25.191" x2="23.16" y1="21.906" y2="21.906" gradientUnits="userSpaceOnUse"><stop class="oj6on8fvq"/><stop offset="1" class="fxowcsv6r"/></linearGradient><linearGradient id="ifKU5mc" x1="26.955" x2="22.927" y1="28.063" y2="28.063" gradientUnits="userSpaceOnUse"><stop offset=".146" class="fd7w0ysog"/><stop offset=".861" class="wtwh9i50b"/></linearGradient><linearGradient id="iBO8D2b" x1="23.503" x2="25.212" y1="26.07" y2="26.07" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="ijHs0Pe" x1="23.425" x2="25.134" y1="27.375" y2="27.375" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="i9Ji0Wc" x1="23.503" x2="25.212" y1="28.68" y2="28.68" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="iNMW70c" x1="10.482" x2="10.482" y1="7.621" y2="9.757" gradientUnits="userSpaceOnUse"><stop class="lfase3b3t"/><stop offset="1" class="r3tk9bbjl"/></linearGradient><linearGradient id="iu3QH3j" x1="21.038" x2="21.038" y1="7.446" y2="9.041" gradientUnits="userSpaceOnUse"><stop class="wvczyl5hy"/><stop offset="1" class="v0x9vt1yz"/></linearGradient><linearGradient id="itXsDSb" x1="21.067" x2="18.466" y1="12.421" y2="12.421" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="iLFw5Fd" x1="16.616" x2="15.76" y1="11.39" y2="11.425" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="ik4v7zC" x1="15.76" x2="15.76" y1="12.553" y2="12.078" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="ism8t3c" x1="15.76" x2="15.76" y1="9.66" y2="10.989" gradientUnits="userSpaceOnUse"><stop class="tucfd5q6h"/><stop offset="1" class="fc26_u1_o"/></linearGradient><linearGradient id="igtIsGc" x1="14.533" x2="14.858" y1="14.156" y2="13.304" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="iYCysHd" x1="18.782" x2="18.461" y1="9.821" y2="10.018" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="im7mDib" x1="14.292" x2="13.972" y1="9.821" y2="10.018" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iim9Mlm" x1="22.33" x2="21.098" y1="9.848" y2="12.07" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="iJrOasW" x1="9.789" x2="11.277" y1="10.569" y2="10.439" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="itXpQ8w" x1="21.308" x2="21.308" y1="9.462" y2="11.405" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient><filter id="iX0q0zd" width="9.938" height="8.021" x="10.364" y="15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1953" stdDeviation=".5"/></filter><filter id="iMpmyBt" width="5.33" height="3.88" x="9.765" y="23.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.384314 0 0 0 0 0.823529 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1953"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_1953" result="shape"/></filter><filter id="ikmUDac" width="4.03" height="2.58" x="10.415" y="24.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.807843 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1953"/></filter><filter id="irxewVh" width="3.922" height="2.04" x="13.799" y="16.636" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.45098 0 0 0 0 0.262745 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1953"/></filter><filter id="iJLDNFd" width="5.15" height="12.15" x="22.255" y="16.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.384314 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1953"/></filter><filter id="i4qjdud" width="2.08" height="4.962" x="24.105" y="21.001" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1953" stdDeviation=".325"/></filter><filter id="icuNE6b" width="4.468" height="5.556" x="22.927" y="24.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.313726 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1953"/></filter><filter id="illG7Tc" width="2.097" height=".3" x="23.353" y="25.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1953" stdDeviation=".05"/></filter><filter id="i4kcvQd" width="2.097" height=".3" x="23.275" y="27.147" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1953" stdDeviation=".05"/></filter><filter id="iCLcnqd" width="2.097" height=".3" x="23.353" y="28.451" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1953" stdDeviation=".05"/></filter><filter id="iZnNsRM" width="11.511" height="12.698" x="10.556" y="4.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1953"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1953" result="effect2_innerShadow_4002_1953"/></filter><filter id="iwmQV2d" width="3.916" height="4.96" x="13.59" y="8.859" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1953" stdDeviation=".5"/></filter><filter id="ikksZPd" width="2.316" height="3.36" x="14.602" y="9.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1953" stdDeviation=".1"/></filter><filter id="iYDEzrb" width="3.685" height="1.495" x="13.917" y="13.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1953" stdDeviation=".05"/></filter><filter id="iMT6tnb" width="2.385" height="1.211" x="17.382" y="7.215" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1953"/></filter><filter id="ioLW4Zd" width="2.385" height="1.196" x="12.017" y="7.222" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1953"/></filter><filter id="iAGQZjc" width=".799" height=".707" x="17.24" y="9.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1953" stdDeviation=".05"/></filter><filter id="izZaStc" width=".901" height=".924" x="18.099" y="9.398" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1953" stdDeviation=".1"/></filter><filter id="iMt565a" width=".999" height="1.054" x="13.565" y="9.333" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1953" stdDeviation=".1"/></filter><filter id="iW0Qd4K" width=".928" height=".715" x="12.792" y="9.31" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1953" stdDeviation=".05"/></filter><filter id="i3XgZQt" width="1.346" height="2.418" x="9.607" y="9.228" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1953" stdDeviation=".125"/></filter><filter id="iu9Vsbe" width="1.966" height="2.943" x="20.325" y="8.962" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1953" stdDeviation=".25"/></filter><filter id="i6ti4Td" width="2.34" height="1.069" x="11.992" y="7.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1953" stdDeviation=".125"/></filter><filter id="iDSnA0d" width="2.34" height="1.078" x="17.38" y="7.304" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1953" stdDeviation=".125"/></filter><filter id="iLyY5zd" width="11.17" height="3.114" x="10.155" y="5.342" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.560784 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1953"/></filter><filter id="iZ4mtvb" width="11.355" height="5.77" x="10.062" y="1.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.12549 0 0 0 0 0.431373 0 0 0 0 0.721569 0 0 0 0.5 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1953"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:mechanic-medium" /></template>
<style>
.a7mg-t_7y {
  stop-color: var(--svg-color--9e5a86, #9E5A86);
}

.a8hir8afg {
  stop-color: var(--svg-color--4c3a38, #4C3A38);
}

.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.a969r93lb {
  stop-color: var(--svg-color--d3c8dc, #D3C8DC);
}

.acsx37bmr {
  stop-color: var(--svg-color--33212e, #33212E);
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b215l7b2u {
  d: path("M10.601 8.804a1.643 1.643 0 0 0 .141 3.266a80 80 0 0 1-.14-3.266");
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bjz-35bmd {
  stop-color: var(--svg-color--d6cbdf, #D6CBDF);
  stop-opacity: 0;
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.c-tzwtb6q {
  stop-color: var(--svg-color--345cbf, #345CBF);
  stop-opacity: 0;
}

.c5x-f3bwv {
  stop-color: var(--svg-color--ffe4f7, #FFE4F7);
  stop-opacity: 0;
}

.cbe6sn2ns {
  stop-color: var(--svg-color--d2c9de, #D2C9DE);
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.cjq4b16bn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.503 25.992H25.3");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d__di5b1k {
  stop-color: var(--svg-color--d2c4ec, #D2C4EC);
}

.d1vocvbes {
  stop-color: var(--svg-color--c99e80, #C99E80);
  stop-opacity: 0;
}

.d337rwvie {
  stop-color: var(--svg-color--e0ccf0, #E0CCF0);
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.dnlpn5c4m {
  d: path("M15.76 13.658a3.1 3.1 0 0 1-1.414-.336c-.14-.07-.29.087-.202.214c.342.518.937.863 1.616.863s1.274-.345 1.616-.863c.088-.132-.062-.285-.202-.214a3.05 3.05 0 0 1-1.414.336");
}

.dvr2s59yl {
  d: path("M26.245 23.1c.55 0 1 .45 1 1v2.29h-2V24.1c0-.55.45-1 1-1");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.elibtcceq {
  d: path("M10.618 9.478a.976.976 0 0 0 .085 1.919a79 79 0 0 1-.085-1.919");
}

.eqaszhbhb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.503 28.602H25.3");
}

.f7vxzf2re {
  stop-color: var(--svg-color--8e7f98, #8E7F98);
}

.fc26_u1_o {
  stop-color: var(--svg-color--8c656e, #8C656E);
  stop-opacity: 0;
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fd7w0ysog {
  stop-color: var(--svg-color--c89a81, #C89A81);
}

.ft5dv1b6b {
  fill: none;
}

.fxowcsv6r {
  stop-color: var(--svg-color--847596, #847596);
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.g21-8bc8z {
  stop-color: var(--svg-color--c7acea, #C7ACEA);
}

.g9kocifrb {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.264 10.171l-.648 1.877c-.111.386.155.772.531.772h.803c.376 0 .642-.392.531-.772l-.542-1.877c-.117-.416-.553-.416-.675 0");
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.ganm9fbbs {
  stop-color: var(--svg-color--bab5c6, #BAB5C6);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.ghamttb0q {
  stop-color: var(--svg-color--99959a, #99959A);
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.gmjyv1b7b {
  stop-color: var(--svg-color--aba1bb, #ABA1BB);
  stop-opacity: 0;
}

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
}

.gvyr5190s {
  stop-color: var(--svg-color--d2c9de, #D2C9DE);
  stop-opacity: 0;
}

.gx30_upqx {
  d: path("M20.784 12.07q.102-1.63.189-3.258a1.643 1.643 0 0 1-.189 3.258");
}

.h5mxx_cud {
  stop-color: var(--svg-color--dbbaf9, #DBBAF9);
}

.hdap23b-n {
  d: path("m15.37 9.971l-.543 1.877c-.11.386.155.772.532.772h.802c.377 0 .643-.392.532-.772l-.543-1.877c-.116-.415-.658-.415-.78 0");
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.hfyjss5uq {
  stop-color: var(--svg-color--3f8aad, #3F8AAD);
}

.hvvawt4nw {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M19.57 7.93a1.85 1.85 0 0 0-.701-.42c-.31-.098-.7-.125-1.238-.059a.283.283 0 1 0 .069.562c.49-.06.792-.029.999.036c.202.064.339.167.5.307a.283.283 0 0 0 .371-.427");
}

.hwgxlbc5v {
  stop-color: var(--svg-color--2b5fb7, #2B5FB7);
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.iodgi0b6i {
  stop-color: var(--svg-color--47c4ff, #47C4FF);
}

.isnxvrbfh {
  d: path("M20.549 7.095h.744l.235 2.662h-.98z");
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.jtr0qabgf {
  d: path("M20.825 11.405q.06-.97.113-1.943a.975.975 0 0 1-.113 1.943");
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.kn12m3thp {
  stop-color: var(--svg-color--996174, #996174);
  stop-opacity: 0;
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.kvfq7h_0m {
  d: path("M8.775 30V17.99a10.98 10.98 0 0 0-4.03 8.51V30z");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l7-eynbdn {
  d: path("M17.923 9.471c.064.087-.071.193-.225.308c-.155.116-.27.197-.334.11c-.065-.087.007-.25.162-.366c.154-.115.332-.138.396-.052");
}

.l731pf7zh {
  stop-color: var(--svg-color--835646, #835646);
}

.ldn_ouzqy {
  stop-color: var(--svg-color--c6c4d3, #C6C4D3);
}

.lfase3b3t {
  stop-color: var(--svg-color--583e3c, #583E3C);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.llp516bpm {
  fill: var(--svg-color--f4e6ff, #F4E6FF);
  d: path("M19.674 16.233v4.908c0 .433-.418.668-.813.379L15.74 18.8a.1.1 0 0 1-.034-.076v-1.322l1.7-1.776c.787.122 1.546.327 2.269.607");
}

.luyfkt2yj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.425 27.297h1.797");
}

.lwc2zdrqr {
  d: path("M13.155 24.45c.71 0 1.29.58 1.29 1.29s-.58 1.29-1.29 1.29h-1.45c-.71 0-1.29-.58-1.29-1.29s.58-1.29 1.29-1.29zm0-.5h-1.45c-.99 0-1.79.8-1.79 1.79s.8 1.79 1.79 1.79h1.45c.99 0 1.79-.8 1.79-1.79s-.8-1.79-1.79-1.79");
}

.m1cydckkt {
  stop-color: var(--svg-color--e0c7fa, #E0C7FA);
  stop-opacity: 0;
}

.m1i1rlbvk {
  d: path("M15.745 15.5c-6.07 0-11 4.92-11 11V30h21.08l.91-3.5c0-6.08-4.92-11-10.99-11");
}

.m3se_ob2r {
  fill: var(--svg-color--eddffd, #EDDFFD);
  d: path("M11.736 16.236v4.905c0 .433.418.668.813.379l3.122-2.72a.1.1 0 0 0 .034-.076v-1.322l-1.699-1.775c-.787.123-1.547.329-2.27.61");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.meeoi68df {
  stop-color: var(--svg-color--cba68e, #CBA68E);
  stop-opacity: 0;
}

.mj2-v7r_j {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.395 8.056c-.288-.303-.916-.519-1.69-.389");
}

.momee7bch {
  d: path("M13.155 27.03h-1.45c-.71 0-1.29-.58-1.29-1.29s.58-1.29 1.29-1.29h1.45c.71 0 1.29.58 1.29 1.29c0 .72-.57 1.29-1.29 1.29");
}

.mqzcoevnf {
  cx: 13.256px;
  cy: 9.668px;
  rx: 0.398px;
  ry: 0.201px;
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.my1ko-bwx {
  d: path("M18.8 10.07a.86.86 0 0 0-.235-.472l-.266.29l.12.234z");
}

.n1djunb7v {
  d: path("M10.835 13.523A4 4 0 0 0 14.8 17h1.926a4 4 0 0 0 3.967-3.477c.12-1.923.284-4.479.373-6.4c-.01-.783-.67-.788-1.45-.821h-1.43a2.47 2.47 0 0 1-2.257-1.473a.68.68 0 0 0-.628-.427h-1.3c-1.884 0-3.446.815-3.446 2.72c0 1.9.154 4.497.279 6.401");
}

.n2_xvjdcg {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.2 9.001c.668 0 1.23.46 1.384 1.081a.28.28 0 0 1-.273.348h-2.278a.235.235 0 0 1-.232-.277A1.43 1.43 0 0 1 18.201 9");
}

.n5xzb8_yo {
  stop-color: var(--svg-color--e0c6f6, #E0C6F6);
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.n6ddjcztw {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.369 13.278c.402.21.88.33 1.391.33c.515 0 .99-.12 1.391-.33a.21.21 0 0 1 .246.04a.19.19 0 0 1 .02.245m-3.048-.285l3.007.258m-3.007-.258a.21.21 0 0 0-.246.042a.19.19 0 0 0-.02.244m.266-.286l-.225.258m3.274.027l-.042-.027m.042.027l-.042-.027m.042.027a1.98 1.98 0 0 1-1.658.886a1.98 1.98 0 0 1-1.658-.885m3.274-.028a1.93 1.93 0 0 1-1.616.863a1.93 1.93 0 0 1-1.616-.863m-.042.028l.042-.028m-.042.028l.042-.028");
}

.njj87ojhb {
  stop-color: var(--svg-color--c2998b, #C2998B);
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.o2y-twbma {
  stop-color: var(--svg-color--2780b8, #2780B8);
}

.o43_m0brr {
  stop-color: var(--svg-color--302028, #302028);
}

.o5bua8boy {
  stop-color: var(--svg-color--45c0ff, #45C0FF);
}

.o7pw9mb8f {
  stop-color: var(--svg-color--f03a62, #F03A62);
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.oh9185bnq {
  stop-color: var(--svg-color--2860c0, #2860C0);
  stop-opacity: 0;
}

.oj6on8fvq {
  stop-color: var(--svg-color--847596, #847596);
  stop-opacity: 0;
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.pimvl5kot {
  d: path("M22.927 25.326a.73.73 0 0 1 .727-.732h2.39a1.2 1.2 0 0 1 1.2 1.2V29a1 1 0 0 1-1 1h-2.59a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.psv7auxid {
  d: path("M16.795 2c1.44 0 2.82.43 3.73 1.51c.7.83 1.08 2.36.8 4.06c-.6-.57-1.21-.99-1.89-1.31a8.76 8.76 0 0 0-7.39 0c-.68.31-1.29.74-1.89 1.31c-.28-1.71.1-3.23.8-4.06c.91-1.08 2.29-1.51 3.73-1.51z");
}

.ptx8-dg4d {
  stop-color: var(--svg-color--e0c7fa, #E0C7FA);
}

.pvjcf1omm {
  stop-color: var(--svg-color--4fbfff, #4FBFFF);
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.qcmtsylcx {
  stop-color: var(--svg-color--e73c75, #E73C75);
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.qmyvahb1h {
  d: path("M13.53 9.279a.91.91 0 0 0-.877 1.151h1.76a1 1 0 0 0 .033-.24a.917.917 0 0 0-.915-.911");
}

.qunsngokg {
  stop-color: var(--svg-color--7c6987, #7C6987);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_7zco6vk {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.32 9.001c-.667 0-1.23.46-1.384 1.081a.28.28 0 0 0 .274.348h2.277a.235.235 0 0 0 .232-.278a1.43 1.43 0 0 0-1.4-1.15");
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.r0l64jbzx {
  stop-color: var(--svg-color--b7a9c2, #B7A9C2);
}

.r3tk9bbjl {
  stop-color: var(--svg-color--422c2c, #422C2C);
}

.rdea4ibyq {
  d: path("M14.363 10.083c0-.295-.24-.491-.304-.55l-.294.284l.18.37z");
}

.rf9vqhkak {
  d: path("M17.99 9.279a.91.91 0 0 1 .877 1.151h-1.76a.915.915 0 0 1 .882-1.151");
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rom2yrbwh {
  d: path("M20.735 16.696v5.877c0 .23-.18.41-.41.41h-9.07c-.23 0-.41-.18-.41-.41v-5.92q-.21.101-.413.213a11 11 0 0 0-1.657 1.127V30h14.03V18.068a11 11 0 0 0-2.07-1.372");
}

.ruv4dbc7o {
  stop-color: var(--svg-color--cba68e, #CBA68E);
}

.s0_i_obqx {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.317 8.096c.262-.188.916-.52 1.69-.39");
}

.s2-xryl0i {
  d: path("M12.045 6.26c-.68.31-1.29.74-1.89 1.31l.41.51c.31.38.85.49 1.28.25c.76-.42 2.11-.99 3.9-.99s3.14.57 3.9.99a1 1 0 0 0 1.27-.25l.41-.51c-.6-.57-1.21-.99-1.89-1.31a8.76 8.76 0 0 0-7.39 0");
}

.s8-qpgb5g {
  stop-color: var(--svg-color--3b71d9, #3B71D9);
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sf2388bnl {
  stop-color: var(--svg-color--bab5c6, #BAB5C6);
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.t2xb9pb8a {
  stop-color: var(--svg-color--2860c0, #2860C0);
}

.t87tthbwf {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.923 9.471c.064.087-.071.193-.225.308c-.155.116-.27.197-.334.11c-.065-.087.007-.25.162-.366c.154-.115.332-.138.396-.052");
}

.tdvgs2sbs {
  stop-color: var(--svg-color--9872bb, #9872BB);
}

.tjuuvfmso {
  cx: 13.256px;
  cy: 9.668px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.398px;
  ry: 0.201px;
}

.tucfd5q6h {
  stop-color: var(--svg-color--8c656e, #8C656E);
}

.tz6f6rbmx {
  stop-color: var(--svg-color--9872bb, #9872BB);
  stop-opacity: 0;
}

.u1e8ikbzb {
  d: path("M25.93 17.043c-.191-.1-.432.03-.432.25v1.551c0 .42-.341.77-.763.76a.746.746 0 0 1-.733-.75v-1.561c0-.22-.24-.36-.432-.26a2.48 2.48 0 0 0-1.315 2.171c-.01.97.552 1.821 1.366 2.241c.09.05.15.15.15.25V28a1.005 1.005 0 0 0 2.008.001v-6.324c0-.1.06-.2.15-.25a2.49 2.49 0 0 0 1.326-2.202a2.52 2.52 0 0 0-1.325-2.181");
}

.u25b8uifi {
  stop-color: var(--svg-color--704c68, #704C68);
}

.u7j5qywzc {
  fill: var(--svg-color--b1a1bf, #B1A1BF);
  d: path("M19.301 21.515v-4.908A11 11 0 0 0 17.033 16l-1.7 1.776l-1.7-1.775c-.787.123-1.546.329-2.27.609v4.905c0 .433.419.668.813.379l3.122-2.72a.1.1 0 0 0 .034-.076a.1.1 0 0 0 .035.076l3.122 2.72c.394.289.812.054.812-.38");
}

.ucdgelbmi {
  stop-color: var(--svg-color--835646, #835646);
  stop-opacity: 0;
}

.uh-jw6opt {
  fill: var(--svg-color--946964, #946964);
  d: path("m15.37 9.971l-.543 1.877c-.11.386.155.772.532.772h.802c.377 0 .643-.392.532-.772l-.543-1.877c-.116-.415-.658-.415-.78 0");
}

.uhp0yeb2h {
  stop-color: var(--svg-color--c6b9db, #C6B9DB);
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.ul2cu2h0c {
  stop-color: var(--svg-color--f0e1ff, #F0E1FF);
  stop-opacity: 0;
}

.unsdl8pjp {
  stop-color: var(--svg-color--9b80b4, #9B80B4);
}

.v0ox3l-0u {
  stop-color: var(--svg-color--a27f66, #A27F66);
}

.v0x9vt1yz {
  stop-color: var(--svg-color--573a38, #573A38);
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.v82ztsbvy {
  fill: var(--svg-color--a77077, #A77077);
  d: path("M15.71 18.676c-1.524-.508-1.825-1.445-1.91-1.84h3.921c-.356 1.237-1.494 1.738-2.012 1.84");
}

.vcv8c754j {
  fill: var(--svg-color--9e88ad, #9E88AD);
  d: path("M25.93 17.043c-.191-.1-.432.03-.432.25v1.551c0 .42-.341.77-.763.76a.746.746 0 0 1-.733-.75v-1.561c0-.22-.24-.36-.432-.26a2.48 2.48 0 0 0-1.315 2.171c-.01.97.552 1.821 1.366 2.241c.09.05.15.15.15.25V28a1.005 1.005 0 0 0 2.008.001v-6.324c0-.1.06-.2.15-.25a2.49 2.49 0 0 0 1.326-2.202a2.52 2.52 0 0 0-1.325-2.181");
}

.viezl_bba {
  fill: var(--svg-color--000, #000);
  d: path("M17.468 10.19a.52.52 0 0 1 .521-.522a.52.52 0 0 1 .464.762h-.923a.5.5 0 0 1-.062-.24");
}

.vqc4qgzhu {
  d: path("M22.775 18.043V30h2.979l.981-3.5c0-3.402-1.54-6.44-3.96-8.457");
}

.w2zd_abhh {
  d: path("M10.798 11.977a1.67 1.67 0 0 1-.924-.315v.95c0 .912.543 1.724 1.37 2.061a4.2 4.2 0 0 1-.354-1.204z");
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
}

.wtwh9i50b {
  stop-color: var(--svg-color--94616d, #94616D);
}

.wvczyl5hy {
  stop-color: var(--svg-color--6b4a49, #6B4A49);
}

.wzclzacav {
  stop-color: var(--svg-color--815963, #815963);
  stop-opacity: 0;
}

.x2409oaqt {
  stop-color: var(--svg-color--3a69a2, #3A69A2);
}

.x78tqlban {
  stop-color: var(--svg-color--6f4745, #6F4745);
}

.xh-hzrtoi {
  stop-color: var(--svg-color--2f83be, #2F83BE);
}

.xkfkdpb1x {
  fill: var(--svg-color--000, #000);
  d: path("M14.052 10.19a.52.52 0 0 0-.521-.522a.52.52 0 0 0-.464.762h.923a.5.5 0 0 0 .062-.24");
}

.xn6dhjjio {
  d: path("M19.674 16.233v4.908c0 .433-.418.668-.813.379L15.74 18.8a.1.1 0 0 1-.034-.076v-1.322l1.7-1.776c.787.122 1.546.327 2.269.607");
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.y9jato2vd {
  stop-color: var(--svg-color--3f8aad, #3F8AAD);
  stop-opacity: 0;
}

.yc6yhhbng {
  stop-color: var(--svg-color--52403f, #52403F);
}

.yyp9ebbtr {
  d: path("M20.722 11.977c.342-.011.663-.127.924-.315v.95c0 .912-.544 1.724-1.37 2.061q.263-.556.354-1.204z");
}

.z1an05bwi {
  stop-color: var(--svg-color--99959a, #99959A);
  stop-opacity: 0;
}

.z1mrz_gsv {
  d: path("M10.184 7.095h.788v2.662h-.98z");
}

.z4q6dwvkw {
  stop-color: var(--svg-color--2b5fb7, #2B5FB7);
  stop-opacity: 0;
}

.z5g21op2e {
  fill: var(--svg-color--b3a4c6, #B3A4C6);
  d: path("M24.755 21.651h.78v3.662h-.78z");
}

.z8optlbcz {
  stop-color: var(--svg-color--9680b0, #9680B0);
}

.z9cu3vbra {
  stop-color: var(--svg-color--fff7ff, #FFF7FF);
}

.zbbicibto {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M12.278 7.81a2.83 2.83 0 0 1 1.775-.367a.283.283 0 1 1-.069.563a2.27 2.27 0 0 0-1.415.29a1 1 0 0 0-.094.061l-.002.002a.283.283 0 0 1-.347-.447z");
}

.zqss5obsp {
  d: path("M11.736 16.236v4.905c0 .433.418.668.813.379l3.122-2.72a.1.1 0 0 0 .034-.076v-1.322l-1.699-1.775c-.787.123-1.547.329-2.27.61");
}

.zsyglhsdv {
  stop-color: var(--svg-color--eee0fe, #EEE0FE);
  stop-opacity: 0;
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

.zwo8xvbzg {
  stop-color: var(--svg-color--345cbf, #345CBF);
}

</style>
