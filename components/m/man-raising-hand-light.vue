<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ildZEpe)" class="l57h88ixc"/><path fill="url(#iF3kRuE)" class="l57h88ixc"/><path fill="url(#iVpv6Ed)" class="l57h88ixc"/><path fill="url(#iYEBDgc)" class="l57h88ixc"/><path fill="url(#id8EuRd)" class="l57h88ixc"/><path fill="url(#iT3oF2h)" class="l57h88ixc"/><path fill="url(#i6Pky5c)" class="l57h88ixc"/><path fill="url(#iqIfVEe)" class="l57h88ixc"/><path fill="url(#iI1RESd)" class="l57h88ixc"/><path fill="url(#i1KyrEz)" class="l57h88ixc"/><path fill="url(#iHSLzHz)" class="l57h88ixc"/><path fill="url(#iUBPSKe)" class="l57h88ixc"/><g filter="url(#iUkuPPc)"><path stroke="url(#iAz03Kb)" class="mjpr7hb-x"/></g><g filter="url(#iCC16Ld)"><path stroke="url(#ixj2Rke)" class="v3f8r-b1a"/></g><g filter="url(#iuLMfib)"><path stroke="url(#i4T7aJb)" class="xe5jqpfgl"/></g><g filter="url(#iVWdHle)"><path stroke="url(#iuzpNIb)" class="jobuis-np"/></g><g filter="url(#ijVMy1d)"><path stroke="url(#iirkH0c)" class="xwvtbubzs"/></g><g filter="url(#iVSrY6c)"><path stroke="url(#imL9C7b)" class="y32wwxp-n"/></g><g filter="url(#iwRwWqc)"><path stroke="url(#iiMbVwb)" class="j2sww20lc"/></g><g filter="url(#i5joINc)"><path stroke="url(#iIwkDfd)" class="gceq2bmkz"/></g><g filter="url(#iTswcIe)"><path stroke="url(#iIZlFRd)" class="xfulnmbvj"/></g><g filter="url(#iUxdEoe)"><path stroke="url(#iPCDxLe)" class="gje8h9e6u"/></g><path fill="url(#ib3HQDb)" class="xbngcbcvy"/><path fill="url(#iTcIzco)" class="xbngcbcvy"/><path fill="url(#i25j8dc)" class="xbngcbcvy"/><path fill="url(#iDtoqPb)" class="cfkued39h"/><path fill="url(#iIADzkb)" class="cfkued39h"/><path fill="url(#iAQK9Le)" class="cfkued39h"/><path fill="url(#iJ43dud)" class="vso5jhb-q"/><path fill="url(#iyrew9I)" class="vso5jhb-q"/><path fill="url(#ihE1Hxc)" class="vso5jhb-q"/><path fill="url(#iGmVVEc)" class="vso5jhb-q"/><path fill="url(#ido6yDu)" class="vso5jhb-q"/><path fill="url(#iaPRLph)" class="vso5jhb-q"/><path fill="url(#iUzbsJd)" class="qipqt3gey"/><path fill="url(#ioSZs5c)" class="qipqt3gey"/><g filter="url(#iDHqZiY)"><path stroke="url(#iFD1Mlc)" class="a8kxg2bbn"/></g><g filter="url(#ipf01Xb)"><circle fill="url(#ir3oOze)" class="aumjr8ztk"/></g><g filter="url(#iWlq4ob)"><circle fill="url(#iW2zZIb)" class="aur9p9-6d"/></g><g filter="url(#iifA4vb)"><circle fill="url(#iiLQytd)" class="hnno5_bly"/><circle fill="url(#iV2YEUb)" class="hnno5_bly"/></g><g filter="url(#iX0krxd)"><circle class="w4whhwbre"/><circle fill="url(#iVazWDd)" class="dvzfukqrr"/><circle fill="url(#ieILkbe)" class="dvzfukqrr"/></g><g filter="url(#iIWnAJd)"><path fill="url(#iKjBgDe)" class="m0fcn9amk"/><path fill="url(#ixwauoc)" class="m0fcn9amk"/><path fill="url(#ihllRjd)" class="m0fcn9amk"/><path fill="url(#iy7wZWc)" class="m0fcn9amk"/><path fill="url(#iLehq4v)" class="m0fcn9amk"/><path fill="url(#itdtguj)" class="m0fcn9amk"/></g><g filter="url(#iPRZInd)"><path fill="url(#iHAodzd)" class="tjmidccjs"/></g><g filter="url(#i30Iq0d)"><path class="tb5rwqbbg"/><path fill="url(#ir8x8lB)" class="p7o9mvj4g"/><path fill="url(#ioaZ5Qd)" class="p7o9mvj4g"/><path fill="url(#ittdvyc)" class="p7o9mvj4g"/><path fill="url(#iJJYHPb)" class="p7o9mvj4g"/></g><g filter="url(#inHvsIc)"><path class="wvonw2bgo"/></g><g filter="url(#i3KBkle)"><path class="jccnc-ngg"/><path fill="url(#iOyFvzb)" class="ywacwkb7e"/><path fill="url(#iOloi0c)" class="ywacwkb7e"/><path fill="url(#ipkpb1W)" class="ywacwkb7e"/><path fill="url(#iwZBTFc)" class="ywacwkb7e"/></g><path fill="url(#iEWzTVd)" class="ywacwkb7e"/><path stroke="url(#imkTzoc)" class="r6qbpybtc"/><g filter="url(#iDqlIxa)"><path class="haseebcrw"/></g><g filter="url(#it8Ksjd)"><path class="bskafxbrl"/></g><path class="x9npxpbhw"/><path fill="url(#iWZ82pe)" class="wc9ix5css"/><path class="bstmbfe2y"/><g filter="url(#iZqyGKc)"><path class="sds3xqcrb"/><path fill="url(#iRPc1Oe)" class="te3_r4d6j"/></g><g filter="url(#i6NcYOJ)"><path fill="url(#iX4k5Ub)" class="q6p5qmbzg"/></g><path class="sb8pumbal"/><path fill="url(#iHKf87d)" class="lcrj95b4s"/><path class="p1hz223sy"/><g filter="url(#i29j0id)"><path fill="url(#ipU9SIg)" class="g0ryhtbyl"/></g><g filter="url(#ipdEiCc)"><ellipse transform="rotate(-27.914 16.4 13.275)" class="fzq0f_b5r"/><ellipse fill="url(#iWbbENd)" transform="rotate(-27.914 16.4 13.275)" class="apwch-eyo"/></g><g filter="url(#iYP8CPd)"><path stroke="url(#iyXPasb)" class="c9l9vh6fs"/></g><g filter="url(#imCxtbK)"><path stroke="url(#idiDMcb)" class="jo-08qboz"/></g><g filter="url(#iwxLZ5y)"><path stroke="url(#iuFmtbc)" class="z3pyqljuk"/></g><defs><linearGradient id="iVpv6Ed" x1="6.665" x2="6.665" y1="12.216" y2="10.513" gradientUnits="userSpaceOnUse"><stop class="d5szmqb9x"/><stop offset="1" class="w7r4_8bab"/></linearGradient><linearGradient id="iUBPSKe" x1="3.449" x2="4.168" y1="9.072" y2="8.978" gradientUnits="userSpaceOnUse"><stop class="h8_gk412t"/><stop offset="1" class="fswarsdde"/></linearGradient><linearGradient id="iAz03Kb" x1="5.155" x2="4.203" y1="4.909" y2="6.695" gradientUnits="userSpaceOnUse"><stop class="qj12c_bfp"/><stop offset="1" class="wjvebfn2s"/></linearGradient><linearGradient id="ixj2Rke" x1="6.575" x2="5.274" y1="4.48" y2="5.46" gradientUnits="userSpaceOnUse"><stop class="qj12c_bfp"/><stop offset="1" class="wjvebfn2s"/></linearGradient><linearGradient id="i4T7aJb" x1="8.334" x2="7.953" y1="5.08" y2="6.645" gradientUnits="userSpaceOnUse"><stop class="qj12c_bfp"/><stop offset="1" class="wjvebfn2s"/></linearGradient><linearGradient id="iuzpNIb" x1="3.921" x2="4.34" y1="5.022" y2="7.629" gradientUnits="userSpaceOnUse"><stop class="n2lghubug"/><stop offset="1" class="o-9gnobjq"/></linearGradient><linearGradient id="iirkH0c" x1="5.065" x2="5.277" y1="4.149" y2="7.272" gradientUnits="userSpaceOnUse"><stop class="n2lghubug"/><stop offset="1" class="o-9gnobjq"/></linearGradient><linearGradient id="imL9C7b" x1="7.215" x2="8.317" y1="3.392" y2="7.069" gradientUnits="userSpaceOnUse"><stop class="n2lghubug"/><stop offset="1" class="o-9gnobjq"/></linearGradient><linearGradient id="iiMbVwb" x1="8.169" x2="8.486" y1="4.342" y2="7.773" gradientUnits="userSpaceOnUse"><stop class="n2lghubug"/><stop offset="1" class="o-9gnobjq"/></linearGradient><linearGradient id="iIwkDfd" x1="5.216" x2="4.123" y1="6.889" y2="6.821" gradientUnits="userSpaceOnUse"><stop class="qnynbebrn"/><stop offset="1" class="ogs4x8_bh"/></linearGradient><linearGradient id="iIZlFRd" x1="6.487" x2="5.923" y1="6.717" y2="6.576" gradientUnits="userSpaceOnUse"><stop class="qnynbebrn"/><stop offset="1" class="ogs4x8_bh"/></linearGradient><linearGradient id="iPCDxLe" x1="7.989" x2="7.185" y1="6.53" y2="6.317" gradientUnits="userSpaceOnUse"><stop class="qnynbebrn"/><stop offset="1" class="ogs4x8_bh"/></linearGradient><linearGradient id="ib3HQDb" x1="4.513" x2="8.888" y1="12.417" y2="12.417" gradientUnits="userSpaceOnUse"><stop class="w8p93gb0x"/><stop offset=".743" class="m--3robwq"/></linearGradient><linearGradient id="i25j8dc" x1="6.782" x2="6.782" y1="11.831" y2="12.089" gradientUnits="userSpaceOnUse"><stop class="qp7m7zbwo"/><stop offset="1" class="va6027bik"/></linearGradient><linearGradient id="iDtoqPb" x1="21.51" x2="5.774" y1="30.696" y2="12.854" gradientUnits="userSpaceOnUse"><stop class="cgidz9b8x"/><stop offset=".401" class="qxg6rvb4w"/></linearGradient><linearGradient id="iJ43dud" x1="9.779" x2="10.51" y1="26.523" y2="21.696" gradientUnits="userSpaceOnUse"><stop offset=".1" class="nrwls_btk"/><stop offset="1" class="tilf7ac3p"/></linearGradient><linearGradient id="ido6yDu" x1="14.048" x2="13.31" y1="24.547" y2="23.151" gradientUnits="userSpaceOnUse"><stop offset=".35" class="lign7ubxp"/><stop offset=".794" class="iu5n-nb1z"/></linearGradient><linearGradient id="iaPRLph" x1="7.309" x2="7.309" y1="12.854" y2="13.895" gradientUnits="userSpaceOnUse"><stop class="nwxnfd6vs"/><stop offset="1" class="uwkg4cb-r"/></linearGradient><linearGradient id="iFD1Mlc" x1="7.325" x2="13.075" y1="14.562" y2="22.843" gradientUnits="userSpaceOnUse"><stop class="rtxxuvbkk"/><stop offset="1" class="cm0qez-we"/></linearGradient><linearGradient id="iW2zZIb" x1="13.678" x2="12.918" y1="14.529" y2="14.529" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="iiLQytd" x1="26.265" x2="25.293" y1="12.902" y2="15.914" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="iKjBgDe" x1="24.109" x2="15.04" y1="14.661" y2="16.012" gradientUnits="userSpaceOnUse"><stop class="ydq0kpc8x"/><stop offset="1" class="e-sxlzbkb"/></linearGradient><linearGradient id="ihllRjd" x1="12.616" x2="16.604" y1="16.475" y2="16.61" gradientUnits="userSpaceOnUse"><stop class="z3n_1mwef"/><stop offset="1" class="rvf3-0bfj"/></linearGradient><linearGradient id="iy7wZWc" x1="12.909" x2="15.143" y1="17.862" y2="17.783" gradientUnits="userSpaceOnUse"><stop class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="iHAodzd" x1="18.685" x2="28.356" y1="11.117" y2="7.654" gradientUnits="userSpaceOnUse"><stop class="sbbw_6vcc"/><stop offset="1" class="b7cutjkii"/></linearGradient><linearGradient id="iOyFvzb" x1="18.29" x2="19.404" y1="15.444" y2="15.444" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="iOloi0c" x1="20.431" x2="19.213" y1="15.827" y2="15.809" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="ipkpb1W" x1="19.547" x2="19.547" y1="16.708" y2="16.028" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="iEWzTVd" x1="19.465" x2="19.465" y1="16.758" y2="16.559" gradientUnits="userSpaceOnUse"><stop class="l1er17byo"/><stop offset="1" class="abcg0lbyl"/></linearGradient><linearGradient id="imkTzoc" x1="18.085" x2="18.601" y1="18.626" y2="17.81" gradientUnits="userSpaceOnUse"><stop class="wl-j51biu"/><stop offset=".663" class="i-vkeo5mo"/></linearGradient><linearGradient id="iX4k5Ub" x1="22.827" x2="22.455" y1="13.453" y2="13.682" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ipU9SIg" x1="17.606" x2="17.233" y1="13.453" y2="13.682" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iyXPasb" x1="22.846" x2="22.347" y1="10.912" y2="9.892" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="idiDMcb" x1="16.547" x2="15.135" y1="10.76" y2="10.168" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iuFmtbc" x1="13.78" x2="13.78" y1="8.368" y2="10.929" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><radialGradient id="ildZEpe" cx="0" cy="0" r="1" gradientTransform="matrix(2.33335 -6.04232 7.22855 2.79144 6.183 11.555)" gradientUnits="userSpaceOnUse"><stop offset=".475" class="i3_w4pbvx"/><stop offset="1" class="p9znm86eq"/></radialGradient><radialGradient id="iF3kRuE" cx="0" cy="0" r="1" gradientTransform="matrix(-6.25005 7.24996 -1.42583 -1.22918 10.446 9.67)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="qkzewyv7e"/><stop offset="1" class="s5-y7slxt"/></radialGradient><radialGradient id="iYEBDgc" cx="0" cy="0" r="1" gradientTransform="rotate(85.056 -.131 5.046)scale(2.26624 .33713)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="enl5oqy9k"/><stop offset="1" class="j8wcapbkq"/></radialGradient><radialGradient id="id8EuRd" cx="0" cy="0" r="1" gradientTransform="matrix(-.04685 3.40625 -.266 -.00366 6.555 3.578)" gradientUnits="userSpaceOnUse"><stop class="enl5oqy9k"/><stop offset="1" class="j8wcapbkq"/></radialGradient><radialGradient id="iT3oF2h" cx="0" cy="0" r="1" gradientTransform="rotate(99.609 3.074 5.007)scale(4.02522 .49917)" gradientUnits="userSpaceOnUse"><stop offset=".202" class="enl5oqy9k"/><stop offset="1" class="j8wcapbkq"/></radialGradient><radialGradient id="i6Pky5c" cx="0" cy="0" r="1" gradientTransform="matrix(-.6629 .73793 -.64825 -.58233 10.023 3.173)" gradientUnits="userSpaceOnUse"><stop class="ofxbley4x"/><stop offset="1" class="da81ldttv"/></radialGradient><radialGradient id="iqIfVEe" cx="0" cy="0" r="1" gradientTransform="matrix(-.6504 1.06501 -.658 -.40183 8.097 2.145)" gradientUnits="userSpaceOnUse"><stop class="ofxbley4x"/><stop offset="1" class="da81ldttv"/></radialGradient><radialGradient id="iI1RESd" cx="0" cy="0" r="1" gradientTransform="rotate(99.841 1.866 3.906)scale(1.24402 .95461)" gradientUnits="userSpaceOnUse"><stop class="ofxbley4x"/><stop offset="1" class="da81ldttv"/></radialGradient><radialGradient id="i1KyrEz" cx="0" cy="0" r="1" gradientTransform="matrix(-.13758 .96306 -.68465 -.0978 4.281 3.96)" gradientUnits="userSpaceOnUse"><stop class="ofxbley4x"/><stop offset="1" class="da81ldttv"/></radialGradient><radialGradient id="iHSLzHz" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09125 1.09125 -.85394 -.85394 12.318 6.442)" gradientUnits="userSpaceOnUse"><stop class="ofxbley4x"/><stop offset="1" class="da81ldttv"/></radialGradient><radialGradient id="iTcIzco" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.10937 -1.15625 0 7.443 12.307)" gradientUnits="userSpaceOnUse"><stop class="zen3jbcth"/><stop offset="1" class="e873ol6-u"/></radialGradient><radialGradient id="iIADzkb" cx="0" cy="0" r="1" gradientTransform="matrix(-8.68288 2.79847 -2.9931 -9.28678 26.414 27.056)" gradientUnits="userSpaceOnUse"><stop class="ul7rmpbso"/><stop offset="1" class="ezu_a_bod"/></radialGradient><radialGradient id="iAQK9Le" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.19204 2.98189 0 11.204 30.422)" gradientUnits="userSpaceOnUse"><stop class="iqmfu1bfz"/><stop offset="1" class="b_ji9tgfr"/></radialGradient><radialGradient id="iyrew9I" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.8125 -5.4375 0 3.294 12.854)" gradientUnits="userSpaceOnUse"><stop class="v74r7idhd"/><stop offset="1" class="hk_d6vbsx"/></radialGradient><radialGradient id="ihE1Hxc" cx="0" cy="0" r="1" gradientTransform="rotate(-167.876 10.084 9.173)scale(10.3399 4.20474)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="dz4ncrwcz"/><stop offset="1" class="ou0802bre"/></radialGradient><radialGradient id="iGmVVEc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.69115 0 0 -5.7286 12.064 15.767)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="pzn0rnkkd"/><stop offset="1" class="zpuae6b8t"/></radialGradient><radialGradient id="iUzbsJd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.3731 -4.14332 0 19.327 20.758)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="fbf66108l"/><stop offset="1" class="m2a4dvbzi"/></radialGradient><radialGradient id="ioSZs5c" cx="0" cy="0" r="1" gradientTransform="matrix(1.90434 4.58794 -4.92328 2.04353 18.377 20.46)" gradientUnits="userSpaceOnUse"><stop offset=".527" class="zhvue1b_t"/><stop offset=".914" class="rq0vvgb8y"/></radialGradient><radialGradient id="ir3oOze" cx="0" cy="0" r="1" gradientTransform="matrix(2.08383 0 0 3.64672 11.696 14.198)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="iV2YEUb" cx="0" cy="0" r="1" gradientTransform="matrix(.98168 -.71481 .81586 1.12045 25.417 13.884)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="iVazWDd" cx="0" cy="0" r="1" gradientTransform="matrix(.97521 -1.7937 1.04985 .5708 24.926 15.174)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="ieILkbe" cx="0" cy="0" r="1" gradientTransform="matrix(.3079 .30477 -.39289 .39692 24.975 14.198)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="ixwauoc" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.4085 -14.1289 0 19.35 11.912)" gradientUnits="userSpaceOnUse"><stop offset=".487" class="xlsr65bou"/><stop offset="1" class="s0nym4b3v"/></radialGradient><radialGradient id="iLehq4v" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.5521 1.91028 0 22.102 12.688)" gradientUnits="userSpaceOnUse"><stop class="m459pab_j"/><stop offset="1" class="rcuz4uefu"/></radialGradient><radialGradient id="itdtguj" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.6516 2.05391 0 16.69 12.649)" gradientUnits="userSpaceOnUse"><stop class="hplqxft1w"/><stop offset="1" class="ay1rn8bxh"/></radialGradient><radialGradient id="ir8x8lB" cx="0" cy="0" r="1" gradientTransform="matrix(.94738 -3.51087 1.30193 .35132 24.476 9.322)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="ioaZ5Qd" cx="0" cy="0" r="1" gradientTransform="matrix(4.54183 .41797 -.22474 2.44211 22.526 7.233)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="ittdvyc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.99395 -3.08806 0 19.316 3.985)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iJJYHPb" cx="0" cy="0" r="1" gradientTransform="matrix(3.65018 -2.67494 4.19076 5.71864 11.658 12.081)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="iwZBTFc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .23381 -.75118 0 19.705 16.106)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="iWZ82pe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .96318 -1.53205 0 21.904 13.389)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iRPc1Oe" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 14.12 1.447)scale(.4491 .61829)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iHKf87d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .96323 -1.53213 0 16.723 13.389)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iWbbENd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00918 -.58657 .70508 -.01104 16.383 13.649)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iUkuPPc" width=".423" height="2.22" x="4.762" y="4.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3876" stdDeviation=".05"/></filter><filter id="iCC16Ld" width=".345" height="2.572" x="6.317" y="4.339" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3876" stdDeviation=".05"/></filter><filter id="iuLMfib" width=".509" height="1.681" x="7.793" y="4.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3876" stdDeviation=".05"/></filter><filter id="iVWdHle" width="1.556" height="3.487" x="3.627" y="4.118" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3876" stdDeviation=".2"/></filter><filter id="ijVMy1d" width="1.2" height="3.889" x="5.313" y="3.19" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3876" stdDeviation=".2"/></filter><filter id="iVSrY6c" width="1.488" height="4.773" x="6.86" y="2.264" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3876" stdDeviation=".2"/></filter><filter id="iwRwWqc" width="2.002" height="4.299" x="8.264" y="3.279" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3876" stdDeviation=".2"/></filter><filter id="i5joINc" width="1.412" height="1.358" x="3.918" y="6.636" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3876" stdDeviation=".1"/></filter><filter id="iTswcIe" width="1.118" height=".999" x="5.566" y="6.428" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3876" stdDeviation=".1"/></filter><filter id="iUxdEoe" width="1.312" height="1.023" x="6.832" y="6.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3876" stdDeviation=".1"/></filter><filter id="iDHqZiY" width="9.217" height="11.911" x="5.669" y="12.283" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3876" stdDeviation=".75"/></filter><filter id="ipf01Xb" width="4.165" height="3.965" x="11.696" y="12.216" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3876"/></filter><filter id="iWlq4ob" width="3.363" height="3.363" x="11.997" y="12.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3876" stdDeviation=".25"/></filter><filter id="iifA4vb" width="4.215" height="4.215" x="22.993" y="11.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3876"/></filter><filter id="iX0krxd" width="3.363" height="3.363" x="23.294" y="12.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3876" stdDeviation=".25"/></filter><filter id="iIWnAJd" width="12.318" height="14.533" x="13.191" y="7.52" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3876"/></filter><filter id="iPRZInd" width="9.042" height="7.642" x="17.518" y="5.52" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3876" stdDeviation="1"/></filter><filter id="i30Iq0d" width="14.964" height="10.051" x="11.834" y="3.485" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3876"/></filter><filter id="inHvsIc" width="3.59" height="4.684" x="17.237" y="12.968" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3876" stdDeviation=".375"/></filter><filter id="i3KBkle" width="2.729" height="3.684" x="17.952" y="13.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3876" stdDeviation=".125"/></filter><filter id="iDqlIxa" width="3.491" height="2.149" x="20.72" y="9.941" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3876"/></filter><filter id="it8Ksjd" width="3.492" height="2.149" x="14.607" y="9.941" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3876"/></filter><filter id="iZqyGKc" width=".897" height=".789" x="21.051" y="12.885" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3876" stdDeviation=".05"/></filter><filter id="i6NcYOJ" width=".983" height="1.01" x="22.067" y="12.993" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3876" stdDeviation=".1"/></filter><filter id="i29j0id" width="1.096" height="1.16" x="16.792" y="12.918" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3876" stdDeviation=".1"/></filter><filter id="ipdEiCc" width="1.047" height=".799" x="15.877" y="12.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3876" stdDeviation=".05"/></filter><filter id="iYP8CPd" width="3.696" height="2.012" x="20.538" y="10.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3876" stdDeviation=".25"/></filter><filter id="imCxtbK" width="3.788" height="2.08" x="14.34" y="10.083" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3876" stdDeviation=".25"/></filter><filter id="iwxLZ5y" width="1.057" height="2.554" x="13.252" y="8.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3876" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-raising-hand-light" /></template>
<style>
.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.a8kxg2bbn {
  d: path("M7.669 13.783v5.171a2 2 0 0 0 1.38 1.902l4.182 1.362");
}

.abcg0lbyl {
  stop-color: var(--svg-color--d6938e, #D6938E);
  stop-opacity: 0;
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.apwch-eyo {
  cx: 16.401px;
  cy: 13.275px;
  rx: 0.463px;
  ry: 0.234px;
}

.aumjr8ztk {
  cx: 13.678px;
  cy: 14.198px;
  r: 1.982px;
}

.aur9p9-6d {
  cx: 13.678px;
  cy: 14.198px;
  r: 1.181px;
}

.ay1rn8bxh {
  stop-color: var(--svg-color--d0958d, #D0958D);
  stop-opacity: 0;
}

.b_ji9tgfr {
  stop-color: var(--svg-color--4496db, #4496DB);
  stop-opacity: 0;
}

.b7cutjkii {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
  stop-opacity: 0;
}

.bskafxbrl {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m14.835 10.969l.001-.002l.002-.001l.006-.005l.014-.011q.016-.014.043-.032q.052-.04.14-.096c.12-.074.287-.166.5-.25a3.36 3.36 0 0 1 1.772-.188a.634.634 0 1 1-.198 1.252a2.1 2.1 0 0 0-1.109.115a1.8 1.8 0 0 0-.356.19l-.01.006a.634.634 0 0 1-.806-.978");
}

.bstmbfe2y {
  fill: var(--svg-color--000, #000);
  d: path("M21.3 13.882c0-.337.269-.607.606-.607a.604.604 0 0 1 .54.886H21.37a.55.55 0 0 1-.072-.28");
}

.btip4dbzo {
  stop-color: var(--svg-color--dfa790, #DFA790);
  stop-opacity: 0;
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bw8j_5egh {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
}

.c9l9vh6fs {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M21.288 10.797c.51-.09 1.507-.064 2.196.472");
}

.cfkued39h {
  d: path("M20.292 20.855h.97c2.49 0 7.471 3.5 7.471 9H10.8v-3.5a.67.67 0 0 0-.414-.626l-3.073-1.374c-2.49-1-3.486-3.5-3.486-5.198v-5.288c0-.564.423-1.014.931-1.014h4.114c.518 0 .932.46.932 1.014v3.986c0 1.302.996 1.5.996 1.5l5.978 1.5z");
}

.cgidz9b8x {
  stop-color: var(--svg-color--38a2f1, #38A2F1);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cm0qez-we {
  stop-color: var(--svg-color--56a6ff, #56A6FF);
  stop-opacity: 0;
}

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.d5szmqb9x {
  stop-color: var(--svg-color--dd9c7f, #DD9C7F);
}

.da81ldttv {
  stop-color: var(--svg-color--ffd2ba, #FFD2BA);
  stop-opacity: 0;
}

.dvzfukqrr {
  cx: 24.975px;
  cy: 14.198px;
  r: 1.181px;
}

.dz4ncrwcz {
  stop-color: var(--svg-color--09538b, #09538B);
}

.e-sxlzbkb {
  stop-color: var(--svg-color--daa594, #DAA594);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e873ol6-u {
  stop-color: var(--svg-color--3983b7, #3983B7);
  stop-opacity: 0;
}

.enl5oqy9k {
  stop-color: var(--svg-color--e1a587, #E1A587);
}

.ezu_a_bod {
  stop-color: var(--svg-color--4ab7ff, #4AB7FF);
  stop-opacity: 0;
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.fbf66108l {
  stop-color: var(--svg-color--b88790, #B88790);
}

.fswarsdde {
  stop-color: var(--svg-color--ffd5b9, #FFD5B9);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.fzq0f_b5r {
  cx: 16.401px;
  cy: 13.275px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.463px;
  ry: 0.234px;
}

.g0ryhtbyl {
  d: path("M17.688 13.757c0-.342-.278-.57-.354-.64l-.342.332l.21.429z");
}

.gceq2bmkz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M4.218 7.694c.109-.063.617-.38.812-.758");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gje8h9e6u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M7.844 6.537c-.13.164-.501.36-.712.422");
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.h8_gk412t {
  stop-color: var(--svg-color--ffd5b9, #FFD5B9);
}

.haseebcrw {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m23.733 10.969l-.001-.002l-.003-.001l-.005-.005l-.014-.011a2 2 0 0 0-.184-.128a3 3 0 0 0-.498-.25a3.36 3.36 0 0 0-1.773-.188a.634.634 0 1 0 .198 1.252a2.1 2.1 0 0 1 1.108.115a1.8 1.8 0 0 1 .366.196a.634.634 0 0 0 .806-.978");
}

.hk_d6vbsx {
  stop-color: var(--svg-color--3394d1, #3394D1);
  stop-opacity: 0;
}

.hmo3unbrx {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
}

.hnno5_bly {
  cx: 24.975px;
  cy: 14.198px;
  r: 1.982px;
}

.hplqxft1w {
  stop-color: var(--svg-color--d0958d, #D0958D);
}

.i-vkeo5mo {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
  stop-opacity: 0;
}

.i3_w4pbvx {
  stop-color: var(--svg-color--f0bba8, #F0BBA8);
}

.iqmfu1bfz {
  stop-color: var(--svg-color--4496db, #4496DB);
}

.iu5n-nb1z {
  stop-color: var(--svg-color--2877cd, #2877CD);
  stop-opacity: 0;
}

.j2sww20lc {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m9.67 3.725l-.812 3.406");
}

.j8wcapbkq {
  stop-color: var(--svg-color--e1a587, #E1A587);
  stop-opacity: 0;
}

.jccnc-ngg {
  fill: var(--svg-color--fbc4b1, #FBC4B1);
  d: path("m18.862 13.86l-.63 2.018a.64.64 0 0 0 .617.83h.934a.642.642 0 0 0 .618-.83l-.63-2.018c-.136-.447-.767-.447-.909 0");
}

.jo-08qboz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M15.09 11.413c.389-.344 1.237-.705 2.289-.538");
}

.jobuis-np {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m4.225 4.545l.36 2.633");
}

.l1er17byo {
  stop-color: var(--svg-color--d6938e, #D6938E);
}

.l57h88ixc {
  d: path("M3.603 8.92c-.125-1.923-.282-2.96-.328-3.641c-.036-.513.023-1.067.71-1.192c.598-.074.883.452.907.66c-.003-.2 0-.68 0-.804c0-.211.008-.977.86-.977c.6 0 .816.587.8.863c.01-.101.023-.413.035-.707c.018-.433.252-.989.945-.976c.598.039.793.613.766.976L8.181 4.99c.023-.187.102-.664.277-1.34c.175-.674.702-.72.957-.683c.326.046.88.361.649 1.273c-.275 1.157-.463 2.645-.528 3.286c.324-.133.643-.413 1.002-.788c.36-.375.887-.383 1.184-.16c.34.293.521.967.119 1.37c-.463.424-2.129 2.404-2.957 3.394c-.23.292-.997.875-2.234.875c-2.204-.094-2.942-1.676-3.047-3.297");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lcrj95b4s {
  d: path("M16.72 12.822a1.06 1.06 0 0 0-1.02 1.34h2.046q.038-.137.039-.28a1.067 1.067 0 0 0-1.065-1.06");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lign7ubxp {
  stop-color: var(--svg-color--2790d8, #2790D8);
}

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m--3robwq {
  stop-color: var(--svg-color--1b6b9f, #1B6B9F);
}

.m0fcn9amk {
  d: path("M13.191 11.763c0-.317.128-.697.382-.887l.191-.19c.319-.253.446-.633.446-1.013V8.66c0-.317.191-.57.51-.634c.764-.19 2.357-.506 4.65-.506s3.885.316 4.65.506c.254.064.509.317.509.634v1.013c0 .38.191.76.446 1.013c.596.418.559.648.51 1.14c-.064.633-.128 1.71-.128 1.71h.021l-.315 4.7c-.19 2.102-1.843 3.566-3.812 3.566h-3.813c-2.033 0-3.621-1.464-3.812-3.566c-.165-2.157-.238-4.32-.435-6.473");
}

.m2a4dvbzi {
  stop-color: var(--svg-color--d7a49a, #D7A49A);
}

.m459pab_j {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mjpr7hb-x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m4.9 4.906l.148 1.945");
}

.n2lghubug {
  stop-color: var(--svg-color--f1bea1, #F1BEA1);
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.nrwls_btk {
  stop-color: var(--svg-color--2a6bc6, #2A6BC6);
}

.nwxnfd6vs {
  stop-color: var(--svg-color--408dc5, #408DC5);
}

.o-9gnobjq {
  stop-color: var(--svg-color--f1bea1, #F1BEA1);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofxbley4x {
  stop-color: var(--svg-color--ffd2ba, #FFD2BA);
}

.ogs4x8_bh {
  stop-color: var(--svg-color--efb99b, #EFB99B);
  stop-opacity: 0;
}

.ou0802bre {
  stop-color: var(--svg-color--1473af, #1473AF);
  stop-opacity: 0;
}

.p1hz223sy {
  fill: var(--svg-color--000, #000);
  d: path("M17.327 13.882a.604.604 0 0 0-.607-.607a.604.604 0 0 0-.54.886h1.075a.6.6 0 0 0 .072-.28");
}

.p7o9mvj4g {
  d: path("m25.038 6.506l.51.254c.892.443 1.401 1.456 1.21 2.533l-.7 3.61c-.063.373-.31.624-.68.633h-.021s.064-1.076.127-1.71c.052-.514-.038-.67-.51-1.14c-.254-.253-.445-.633-.445-1.013V8.66c0-.317-.255-.57-.51-.634c-.764-.19-2.356-.506-4.65-.506c-2.292 0-3.885.316-4.65.506a.62.62 0 0 0-.509.634v1.013c0 .38-.127.76-.446 1.013l-.19.19c-.255.19-.383.57-.383.887c.064.697.128 1.71.128 1.71q-.03 0-.059-.002a.75.75 0 0 1-.706-.631l-.7-3.61c-.128-1.014.382-2.027 1.274-2.47l.51-.254c.318-.19.636-.443.954-.696l1.147-1.204c.7-.633 1.72-.823 2.611-.38c.637.19 1.338.19 1.975 0c.955-.316 2.038-.063 2.803.634l.955.95c.255.316.573.506.955.696");
}

.p9znm86eq {
  stop-color: var(--svg-color--f4bda7, #F4BDA7);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.pzn0rnkkd {
  stop-color: var(--svg-color--3473ab, #3473AB);
}

.q6p5qmbzg {
  d: path("M22.85 13.742a1 1 0 0 0-.275-.55l-.308.34l.139.27z");
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qipqt3gey {
  d: path("M19.327 23.96c-1.268 0-2.297-.985-2.297-2.2v-2.6c0-1.214 1.029-2.2 2.297-2.2c1.267 0 2.296.986 2.296 2.2v2.6c0 1.215-1.029 2.2-2.296 2.2");
}

.qj12c_bfp {
  stop-color: var(--svg-color--d59776, #D59776);
}

.qkzewyv7e {
  stop-color: var(--svg-color--be8479, #BE8479);
}

.qnynbebrn {
  stop-color: var(--svg-color--efb99b, #EFB99B);
}

.qp7m7zbwo {
  stop-color: var(--svg-color--186a98, #186A98);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxg6rvb4w {
  stop-color: var(--svg-color--268fd7, #268FD7);
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
  stop-opacity: 0;
}

.r6qbpybtc {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.695 17.48a.23.23 0 0 0-.277.048a.21.21 0 0 0-.023.273a2.3 2.3 0 0 0 1.921 1.027c.807 0 1.515-.41 1.922-1.027a.215.215 0 0 0-.024-.275a.23.23 0 0 0-.276-.045a3.5 3.5 0 0 1-1.622.384c-.595 0-1.153-.14-1.621-.384Z");
}

.rcuz4uefu {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
  stop-opacity: 0;
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
}

.rq0vvgb8y {
  stop-color: var(--svg-color--d39f86, #D39F86);
}

.rtxxuvbkk {
  stop-color: var(--svg-color--56a6ff, #56A6FF);
}

.rvf3-0bfj {
  stop-color: var(--svg-color--dead9d, #DEAD9D);
  stop-opacity: 0;
}

.s0nym4b3v {
  stop-color: var(--svg-color--a77d91, #A77D91);
}

.s5-y7slxt {
  stop-color: var(--svg-color--c38e7c, #C38E7C);
  stop-opacity: 0;
}

.sb8pumbal {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.475 12.5c-.776 0-1.43.534-1.609 1.257a.325.325 0 0 0 .318.404h2.649a.273.273 0 0 0 .27-.323a1.66 1.66 0 0 0-1.628-1.338");
}

.sbbw_6vcc {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
}

.sds3xqcrb {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M21.828 13.046c.076.101-.082.224-.262.358c-.179.135-.312.229-.388.128c-.075-.101.01-.292.189-.426s.386-.16.461-.06");
}

.tb5rwqbbg {
  fill: var(--svg-color--242324, #242324);
  d: path("m25.038 6.506l.51.254c.892.443 1.401 1.456 1.21 2.533l-.7 3.61c-.063.373-.31.624-.68.633h-.021s.064-1.076.127-1.71c.052-.514-.038-.67-.51-1.14c-.254-.253-.445-.633-.445-1.013V8.66c0-.317-.255-.57-.51-.634c-.764-.19-2.356-.506-4.65-.506c-2.292 0-3.885.316-4.65.506a.62.62 0 0 0-.509.634v1.013c0 .38-.127.76-.446 1.013l-.19.19c-.255.19-.383.57-.383.887c.064.697.128 1.71.128 1.71q-.03 0-.059-.002a.75.75 0 0 1-.706-.631l-.7-3.61c-.128-1.014.382-2.027 1.274-2.47l.51-.254c.318-.19.636-.443.954-.696l1.147-1.204c.7-.633 1.72-.823 2.611-.38c.637.19 1.338.19 1.975 0c.955-.316 2.038-.063 2.803.634l.955.95c.255.316.573.506.955.696");
}

.te3_r4d6j {
  d: path("M21.828 13.046c.076.101-.082.224-.262.358c-.179.135-.312.229-.388.128c-.075-.101.01-.292.189-.426s.386-.16.461-.06");
}

.tilf7ac3p {
  stop-color: var(--svg-color--2a6bc6, #2A6BC6);
  stop-opacity: 0;
}

.tjmidccjs {
  d: path("m24.023 7.52l-3.655 1.218a1.243 1.243 0 0 0 .559 2.412l3.633-.486z");
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.ul7rmpbso {
  stop-color: var(--svg-color--4ab7ff, #4AB7FF);
}

.uwkg4cb-r {
  stop-color: var(--svg-color--408dc5, #408DC5);
  stop-opacity: 0;
}

.v3f8r-b1a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m6.524 4.476l-.07 2.297");
}

.v74r7idhd {
  stop-color: var(--svg-color--3394d1, #3394D1);
}

.va6027bik {
  stop-color: var(--svg-color--186a98, #186A98);
  stop-opacity: 0;
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.vso5jhb-q {
  d: path("m18.685 20.964l-7.874 5.245a.66.66 0 0 0-.4-.48l-3.084-1.374c-2.5-1-3.5-3.5-3.5-5.198v-5.288c0-.564.425-1.014.935-1.014h4.13c.519 0 .935.46.935 1.014v3.986c0 1.302 1 1.5 1 1.5l6 1.5z");
}

.w4whhwbre {
  cx: 24.975px;
  cy: 14.198px;
  r: 1.181px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
}

.w7r4_8bab {
  stop-color: var(--svg-color--dd9c7f, #DD9C7F);
  stop-opacity: 0;
}

.w8p93gb0x {
  stop-color: var(--svg-color--3688bf, #3688BF);
}

.wachewblq {
  stop-color: var(--svg-color--ba7c6b, #BA7C6B);
}

.wc9ix5css {
  d: path("M21.906 12.822a1.06 1.06 0 0 1 1.021 1.34H20.88a1.064 1.064 0 0 1 1.026-1.339");
}

.wdqn7tq-u {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wjvebfn2s {
  stop-color: var(--svg-color--d59776, #D59776);
  stop-opacity: 0;
}

.wl-j51biu {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
}

.wvonw2bgo {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m18.99 14.053l-.975 2.018c-.12.416.17.83.58.83h.875c.41 0 .7-.42.58-.83l-.592-2.018c-.127-.447-.336-.447-.469 0");
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.x9npxpbhw {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.152 12.5c.775 0 1.43.534 1.608 1.257a.325.325 0 0 1-.318.404h-2.649a.273.273 0 0 1-.27-.323a1.66 1.66 0 0 1 1.628-1.338");
}

.xbngcbcvy {
  d: path("M4.677 12.031c0-.11.09-.2.2-.2h3.81a.2.2 0 0 1 .2.2v1.714h-4.21z");
}

.xe5jqpfgl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m8.165 5.078l-.234 1.406");
}

.xfulnmbvj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.385 6.728c-.13.165-.333.3-.519.4");
}

.xlsr65bou {
  stop-color: var(--svg-color--e0ad9b, #E0AD9B);
  stop-opacity: 0;
}

.xwvtbubzs {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M5.913 3.59v3.088");
}

.y32wwxp-n {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m7.749 2.678l-.29 3.944");
}

.ydq0kpc8x {
  stop-color: var(--svg-color--ffdac0, #FFDAC0);
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.ywacwkb7e {
  d: path("m18.862 13.86l-.63 2.018a.64.64 0 0 0 .617.83h.934a.642.642 0 0 0 .618-.83l-.63-2.018c-.136-.447-.767-.447-.909 0");
}

.yyvs3obha {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
  stop-opacity: 0;
}

.z3n_1mwef {
  stop-color: var(--svg-color--a58787, #A58787);
}

.z3pyqljuk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.934 8.485v1.066c-.01.176-.084.571-.307.738");
}

.zen3jbcth {
  stop-color: var(--svg-color--3983b7, #3983B7);
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
}

.zhvue1b_t {
  stop-color: var(--svg-color--d39f86, #D39F86);
  stop-opacity: 0;
}

.zpuae6b8t {
  stop-color: var(--svg-color--127cc2, #127CC2);
  stop-opacity: 0;
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

</style>
