<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iLWTGCe)" class="jgymjdb_q"/><path fill="url(#iUfdCHd)" class="jgymjdb_q"/><path fill="url(#ij3aKmc)" class="jgymjdb_q"/><path fill="url(#iXHhnac)" class="jgymjdb_q"/><path fill="url(#iVtHjvb)" class="jgymjdb_q"/><path fill="url(#iR5keqd)" class="jgymjdb_q"/><path fill="url(#iKOBIzb)" class="jgymjdb_q"/><path fill="url(#iHq650c)" class="jgymjdb_q"/><path fill="url(#iyCqU7d)" class="jgymjdb_q"/><path fill="url(#iPfFn8b)" class="jgymjdb_q"/><path fill="url(#i7SkiMb)" class="jgymjdb_q"/><g filter="url(#i3AhY3R)"><path stroke="url(#i3eZwlx)" class="njr1qzbcy"/></g><g filter="url(#iWYaKTN)"><path stroke="url(#iAgsKPe)" class="ria1jibpr"/></g><g filter="url(#il7Crje)"><path stroke="url(#iqr1iPt)" class="zaioo08lx"/></g><g filter="url(#i2xBeId)"><path stroke="url(#ixBRfSb)" class="m2h86lb3n"/></g><g filter="url(#ixbIvId)"><path stroke="url(#isP6phb)" class="fybh9obit"/></g><g filter="url(#iOXkoyK)"><path stroke="url(#iK1rnBd)" class="cq0mikryq"/></g><g filter="url(#iwST8ib)"><path stroke="url(#izoWe2c)" class="p7vxhi0fa"/></g><g filter="url(#iGvi9cd)"><path stroke="url(#i3kAzVd)" class="qh6j1bbdz"/></g><g filter="url(#iFK3Atd)"><path stroke="url(#iyiicMg)" class="cuep4p7fp"/></g><g filter="url(#isEIBDb)"><path stroke="url(#iNSzuOc)" class="zzipvmdcm"/></g><path fill="url(#iqMZJFe)" class="xbnxtbcba"/><path fill="url(#iI3F8mG)" class="xbnxtbcba"/><path fill="url(#iA1SUfb)" class="xbnxtbcba"/><path fill="url(#ivQEaQe)" class="ftgjbwy1h"/><path fill="url(#iTqhFqb)" class="ftgjbwy1h"/><path fill="url(#ihnWPbe)" class="ftgjbwy1h"/><path fill="url(#iPqwYBd)" class="dy6shwbgc"/><path fill="url(#i0eobCe)" class="dy6shwbgc"/><path fill="url(#iqpwGWd)" class="dy6shwbgc"/><path fill="url(#i3zoDgq)" class="dy6shwbgc"/><path fill="url(#iSSvAce)" class="dy6shwbgc"/><path fill="url(#ibbUckd)" class="dy6shwbgc"/><path fill="url(#iGV60Si)" class="n4tmycgor"/><path fill="url(#ihZjHjb)" class="n4tmycgor"/><g filter="url(#iFlbYxc)"><path stroke="url(#izYMMge)" class="ads-kyhuz"/></g><g filter="url(#iYRSMWb)"><circle fill="url(#iw0a8cx)" class="lrznj57_h"/></g><circle fill="url(#i47Phkc)" class="lrznj57_h"/><g filter="url(#iCJGj3b)"><circle fill="url(#iFgaFod)" class="kz-1anqws"/></g><g filter="url(#ipWfItb)"><circle fill="url(#ix5KDsp)" class="jnnef_lwj"/><circle fill="url(#izAOxPb)" class="jnnef_lwj"/></g><g filter="url(#iOISRge)"><circle class="do50vzs5x"/><circle fill="url(#i4GBkrd)" class="kqiinhbwf"/><circle fill="url(#imf5NXc)" class="kqiinhbwf"/></g><g filter="url(#ibMknvc)"><path fill="url(#icf3dhb)" class="vw_o3ubex"/><path fill="url(#ijfqZHe)" class="vw_o3ubex"/><path fill="url(#iDzWQoJ)" class="vw_o3ubex"/></g><path fill="url(#ioM7Uob)" class="d3adwzboi"/><path fill="url(#ixfU1qU)" class="d3adwzboi"/><path fill="url(#iH28uxb)" class="d3adwzboi"/><g filter="url(#iOSpGle)"><path fill="url(#iyEXdjd)" class="l9mhobcik"/></g><g filter="url(#i8XLQCe)"><path class="c-9nnh-wl"/><path fill="url(#iZft65c)" class="ea9kflbmr"/><path fill="url(#ikOCQHd)" class="ea9kflbmr"/><path fill="url(#iGkJUrb)" class="ea9kflbmr"/><path fill="url(#isUNrkg)" class="ea9kflbmr"/></g><g filter="url(#i7Nb9Ec)"><path class="aiiux3bkj"/></g><g filter="url(#iacxRQV)"><path class="oscp2xoht"/><path fill="url(#iVSRcTc)" class="bxz0_yb6v"/><path fill="url(#ioGVW4b)" class="bxz0_yb6v"/><path fill="url(#iIp0Oib)" class="bxz0_yb6v"/><path fill="url(#i5yw0Ad)" class="bxz0_yb6v"/></g><path fill="url(#iR0NXie)" class="bxz0_yb6v"/><path stroke="url(#iWe7E0c)" class="ity3_rbtf"/><g filter="url(#i5Haroc)"><path class="oixb-3bxy"/><path fill="url(#ikFWaPe)" class="z_rannrme"/></g><g filter="url(#iSZZAVd)"><path class="jcvtzfbuy"/><path fill="url(#i2DbRUc)" class="z4kh_va1f"/></g><path class="h3zwb1bvv"/><path fill="url(#iNfq8Ge)" class="i2gq6_bzt"/><path class="lkyvxhyoh"/><g filter="url(#iuw4pnH)"><path class="gxiobr4sb"/><path fill="url(#iHtuy3b)" class="msoqh-bjb"/></g><g filter="url(#iof4VCd)"><path fill="url(#ic5m5Uc)" class="afx2mm9yw"/></g><path class="d_0vt8b5r"/><path fill="url(#iLocxNc)" class="hhjr4dufw"/><path class="iwzv9ac4a"/><g filter="url(#iO2dhjb)"><path fill="url(#i3gTvJd)" class="f3fovsmxj"/></g><g filter="url(#iVghhQd)"><ellipse transform="rotate(-27.914 16.39 13.27)" class="q-hwntrrd"/><ellipse fill="url(#i4cccsc)" transform="rotate(-27.914 16.39 13.27)" class="r31gy52yf"/></g><g filter="url(#iBoaaCe)"><path stroke="url(#iai7JAe)" class="n6zd1v0yu"/></g><g filter="url(#inLjWjc)"><path stroke="url(#i2BMAJe)" class="to6jezl8q"/></g><g filter="url(#iO8D18d)"><path stroke="url(#iO5EvYE)" class="t-cwjacqu"/></g><defs><radialGradient id="iLWTGCe" cx="0" cy="0" r="1" gradientTransform="matrix(2.33335 -6.04232 7.22855 2.79144 6.186 11.54)" gradientUnits="userSpaceOnUse"><stop offset=".475" class="pr1c_plua"/><stop offset="1" class="qdtuxcc3i"/></radialGradient><radialGradient id="iUfdCHd" cx="0" cy="0" r="1" gradientTransform="rotate(130.764 3.013 7.22)scale(9.5721 2.30417)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="h0kcnqbkf"/><stop offset="1" class="kybxapb2q"/></radialGradient><radialGradient id="iXHhnac" cx="0" cy="0" r="1" gradientTransform="matrix(.19531 2.2578 -.27074 .02342 4.91 4.726)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="t6ahfk42q"/><stop offset="1" class="lnx1w7b3f"/></radialGradient><radialGradient id="iVtHjvb" cx="0" cy="0" r="1" gradientTransform="matrix(-.04685 3.40625 -.266 -.00366 6.56 3.562)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="t6ahfk42q"/><stop offset="1" class="lnx1w7b3f"/></radialGradient><radialGradient id="iR5keqd" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 3.96875 -.56716 -.09602 8.528 2.797)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="t6ahfk42q"/><stop offset="1" class="lnx1w7b3f"/></radialGradient><radialGradient id="iKOBIzb" cx="0" cy="0" r="1" gradientTransform="matrix(-.6629 .73793 -.64825 -.58233 10.028 3.157)" gradientUnits="userSpaceOnUse"><stop class="ww76qh22b"/><stop offset="1" class="lejfwxzry"/></radialGradient><radialGradient id="iHq650c" cx="0" cy="0" r="1" gradientTransform="matrix(-.6504 1.06501 -.658 -.40183 8.1 2.13)" gradientUnits="userSpaceOnUse"><stop class="ww76qh22b"/><stop offset="1" class="lejfwxzry"/></radialGradient><radialGradient id="iyCqU7d" cx="0" cy="0" r="1" gradientTransform="rotate(99.841 1.874 3.9)scale(1.24402 .95461)" gradientUnits="userSpaceOnUse"><stop class="ww76qh22b"/><stop offset="1" class="lejfwxzry"/></radialGradient><radialGradient id="iPfFn8b" cx="0" cy="0" r="1" gradientTransform="matrix(-.13758 .96306 -.68465 -.0978 4.285 3.944)" gradientUnits="userSpaceOnUse"><stop class="ww76qh22b"/><stop offset="1" class="lejfwxzry"/></radialGradient><radialGradient id="i7SkiMb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09125 1.09125 -.85394 -.85394 12.322 6.426)" gradientUnits="userSpaceOnUse"><stop class="ww76qh22b"/><stop offset="1" class="lejfwxzry"/></radialGradient><radialGradient id="iI3F8mG" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.10937 -1.15625 0 7.44 12.323)" gradientUnits="userSpaceOnUse"><stop class="zen3jbcth"/><stop offset="1" class="e873ol6-u"/></radialGradient><radialGradient id="iTqhFqb" cx="0" cy="0" r="1" gradientTransform="matrix(-8.68288 2.79847 -2.9931 -9.28678 26.41 27.072)" gradientUnits="userSpaceOnUse"><stop class="ul7rmpbso"/><stop offset="1" class="ezu_a_bod"/></radialGradient><radialGradient id="ihnWPbe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.19204 2.98189 0 11.2 30.437)" gradientUnits="userSpaceOnUse"><stop class="iqmfu1bfz"/><stop offset="1" class="b_ji9tgfr"/></radialGradient><radialGradient id="i0eobCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.8125 -5.4375 0 3.29 12.87)" gradientUnits="userSpaceOnUse"><stop class="v74r7idhd"/><stop offset="1" class="hk_d6vbsx"/></radialGradient><radialGradient id="iqpwGWd" cx="0" cy="0" r="1" gradientTransform="rotate(-167.876 10.083 9.181)scale(10.3399 4.20474)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="dz4ncrwcz"/><stop offset="1" class="ou0802bre"/></radialGradient><radialGradient id="i3zoDgq" cx="0" cy="0" r="1" gradientTransform="matrix(-5.69115 0 0 -5.7286 12.06 15.783)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="pzn0rnkkd"/><stop offset="1" class="zpuae6b8t"/></radialGradient><radialGradient id="iGV60Si" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.3731 -4.14332 0 19.323 20.774)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="awc29pfeb"/><stop offset="1" class="rs939fpht"/></radialGradient><radialGradient id="ihZjHjb" cx="0" cy="0" r="1" gradientTransform="matrix(1.90434 4.58794 -4.92328 2.04353 18.373 20.476)" gradientUnits="userSpaceOnUse"><stop offset=".527" class="bo3c15bma"/><stop offset=".914" class="czlx86s7a"/></radialGradient><radialGradient id="iw0a8cx" cx="0" cy="0" r="1" gradientTransform="matrix(2.08888 0 0 3.65556 11.674 14.196)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="i47Phkc" cx="0" cy="0" r="1" gradientTransform="rotate(-124.98 11.045 4.534)scale(1.97208)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="ev4-2pfvs"/><stop offset="1" class="w_j-6pbpp"/></radialGradient><radialGradient id="izAOxPb" cx="0" cy="0" r="1" gradientTransform="matrix(.98405 -.71654 .81784 1.12317 25.428 13.88)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="cu-ecjbbc"/><stop offset="1" class="a1ftncccj"/></radialGradient><radialGradient id="i4GBkrd" cx="0" cy="0" r="1" gradientTransform="matrix(.97758 -1.79804 1.0524 .57218 24.936 15.173)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="d66ufbbtl"/><stop offset=".916" class="f7hwkw-sq"/></radialGradient><radialGradient id="imf5NXc" cx="0" cy="0" r="1" gradientTransform="matrix(.30864 .3055 -.39384 .39788 24.985 14.196)" gradientUnits="userSpaceOnUse"><stop class="suj-pjbhk"/><stop offset="1" class="dg9o8ubcl"/></radialGradient><radialGradient id="ijfqZHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.55587 1.91491 0 22.105 12.682)" gradientUnits="userSpaceOnUse"><stop class="e6v6vrbif"/><stop offset="1" class="qmnjff_ag"/></radialGradient><radialGradient id="iDzWQoJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.63565 2.03408 0 16.68 12.842)" gradientUnits="userSpaceOnUse"><stop class="c02-eqbxv"/><stop offset="1" class="mmmkqcbgq"/></radialGradient><radialGradient id="iH28uxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.91366 -12.2874 0 19.16 12.37)" gradientUnits="userSpaceOnUse"><stop offset=".608" class="dcym8repk"/><stop offset=".884" class="fkee40m0y"/><stop offset="1" class="an_-aznlj"/></radialGradient><radialGradient id="iZft65c" cx="0" cy="0" r="1" gradientTransform="matrix(.94967 -3.51937 1.30509 .35217 24.485 9.308)" gradientUnits="userSpaceOnUse"><stop class="ki2rd4v4k"/><stop offset="1" class="tp9jx5j2y"/></radialGradient><radialGradient id="ikOCQHd" cx="0" cy="0" r="1" gradientTransform="matrix(4.55284 .41897 -.22528 2.44804 22.53 7.213)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="je_aabb8l"/><stop offset="1" class="ivhsfvmdg"/></radialGradient><radialGradient id="iGkJUrb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.99878 -3.09555 0 19.313 3.957)" gradientUnits="userSpaceOnUse"><stop class="n7o-m0b5s"/><stop offset="1" class="xp-9f0bqu"/></radialGradient><radialGradient id="isUNrkg" cx="0" cy="0" r="1" gradientTransform="matrix(3.65903 -2.68144 4.20093 5.7325 11.636 12.073)" gradientUnits="userSpaceOnUse"><stop class="ux7-g74jy"/><stop offset="1" class="dd8hfetks"/></radialGradient><radialGradient id="i5yw0Ad" cx="0" cy="0" r="1" gradientTransform="matrix(0 .23438 -.753 0 19.702 16.108)" gradientUnits="userSpaceOnUse"><stop class="mifq-tdon"/><stop offset="1" class="n-ko-_w7d"/></radialGradient><radialGradient id="ikFWaPe" cx="0" cy="0" r="1" gradientTransform="matrix(.12403 -.7181 2.12442 .36692 22.22 11.715)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="i2DbRUc" cx="0" cy="0" r="1" gradientTransform="matrix(.12403 -.7181 2.12453 .36696 16.093 11.715)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="iNfq8Ge" cx="0" cy="0" r="1" gradientTransform="matrix(0 .96552 -1.53577 0 21.905 13.385)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iHtuy3b" cx="0" cy="0" r="1" gradientTransform="matrix(-.276 -.35566 .48965 -.37998 21.636 13.484)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iLocxNc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .96557 -1.53585 0 16.713 13.384)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i4cccsc" cx="0" cy="0" r="1" gradientTransform="matrix(-.0092 -.58799 .7068 -.01107 16.372 13.644)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="ij3aKmc" x1="6.668" x2="6.668" y1="12.2" y2="10.497" gradientUnits="userSpaceOnUse"><stop class="sy2nhlbqj"/><stop offset="1" class="o6qx6mc1p"/></linearGradient><linearGradient id="i3eZwlx" x1="5.158" x2="4.207" y1="4.894" y2="6.68" gradientUnits="userSpaceOnUse"><stop class="a53shnb1b"/><stop offset="1" class="hsqf8hwha"/></linearGradient><linearGradient id="iAgsKPe" x1="6.578" x2="5.278" y1="4.465" y2="5.444" gradientUnits="userSpaceOnUse"><stop class="a53shnb1b"/><stop offset="1" class="hsqf8hwha"/></linearGradient><linearGradient id="iqr1iPt" x1="8.338" x2="7.956" y1="5.065" y2="6.629" gradientUnits="userSpaceOnUse"><stop class="a53shnb1b"/><stop offset="1" class="hsqf8hwha"/></linearGradient><linearGradient id="ixBRfSb" x1="3.924" x2="4.344" y1="5.006" y2="7.614" gradientUnits="userSpaceOnUse"><stop class="px0vdqe0d"/><stop offset="1" class="ik287t08j"/></linearGradient><linearGradient id="isP6phb" x1="5.069" x2="5.281" y1="4.133" y2="7.256" gradientUnits="userSpaceOnUse"><stop class="px0vdqe0d"/><stop offset="1" class="ik287t08j"/></linearGradient><linearGradient id="iK1rnBd" x1="7.218" x2="8.32" y1="3.376" y2="7.053" gradientUnits="userSpaceOnUse"><stop class="px0vdqe0d"/><stop offset="1" class="ik287t08j"/></linearGradient><linearGradient id="izoWe2c" x1="8.173" x2="8.489" y1="4.326" y2="7.757" gradientUnits="userSpaceOnUse"><stop class="px0vdqe0d"/><stop offset="1" class="ik287t08j"/></linearGradient><linearGradient id="i3kAzVd" x1="5.219" x2="4.127" y1="6.873" y2="6.805" gradientUnits="userSpaceOnUse"><stop class="xgo-prp7n"/><stop offset="1" class="krd2fabda"/></linearGradient><linearGradient id="iyiicMg" x1="6.491" x2="5.927" y1="6.702" y2="6.56" gradientUnits="userSpaceOnUse"><stop class="xgo-prp7n"/><stop offset="1" class="krd2fabda"/></linearGradient><linearGradient id="iNSzuOc" x1="7.992" x2="7.189" y1="6.515" y2="6.302" gradientUnits="userSpaceOnUse"><stop class="xgo-prp7n"/><stop offset="1" class="krd2fabda"/></linearGradient><linearGradient id="iqMZJFe" x1="4.509" x2="8.884" y1="12.433" y2="12.433" gradientUnits="userSpaceOnUse"><stop class="w8p93gb0x"/><stop offset=".743" class="m--3robwq"/></linearGradient><linearGradient id="iA1SUfb" x1="6.779" x2="6.779" y1="11.847" y2="12.105" gradientUnits="userSpaceOnUse"><stop class="qp7m7zbwo"/><stop offset="1" class="va6027bik"/></linearGradient><linearGradient id="ivQEaQe" x1="21.507" x2="5.77" y1="30.712" y2="12.87" gradientUnits="userSpaceOnUse"><stop class="cgidz9b8x"/><stop offset=".401" class="qxg6rvb4w"/></linearGradient><linearGradient id="iPqwYBd" x1="9.776" x2="10.507" y1="26.538" y2="21.712" gradientUnits="userSpaceOnUse"><stop offset=".1" class="nrwls_btk"/><stop offset="1" class="tilf7ac3p"/></linearGradient><linearGradient id="iSSvAce" x1="14.045" x2="13.306" y1="24.563" y2="23.167" gradientUnits="userSpaceOnUse"><stop offset=".35" class="lign7ubxp"/><stop offset=".794" class="iu5n-nb1z"/></linearGradient><linearGradient id="ibbUckd" x1="7.305" x2="7.305" y1="12.87" y2="13.91" gradientUnits="userSpaceOnUse"><stop class="nwxnfd6vs"/><stop offset="1" class="uwkg4cb-r"/></linearGradient><linearGradient id="izYMMge" x1="7.322" x2="13.072" y1="14.578" y2="22.859" gradientUnits="userSpaceOnUse"><stop class="rtxxuvbkk"/><stop offset="1" class="cm0qez-we"/></linearGradient><linearGradient id="iFgaFod" x1="13.661" x2="12.899" y1="14.527" y2="14.527" gradientUnits="userSpaceOnUse"><stop class="vo9agqbnp"/><stop offset="1" class="fwwugibmc"/></linearGradient><linearGradient id="ix5KDsp" x1="26.278" x2="25.304" y1="12.896" y2="15.915" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="sla6kib8v"/></linearGradient><linearGradient id="icf3dhb" x1="24.117" x2="15.027" y1="14.659" y2="16.014" gradientUnits="userSpaceOnUse"><stop class="f43nfdclv"/><stop offset="1" class="ixdockwro"/></linearGradient><linearGradient id="ioM7Uob" x1="12.89" x2="15.129" y1="17.868" y2="17.789" gradientUnits="userSpaceOnUse"><stop class="xaj4s_mqh"/><stop offset="1" class="nzdq87b8k"/></linearGradient><linearGradient id="ixfU1qU" x1="25.17" x2="23.846" y1="16.867" y2="16.751" gradientUnits="userSpaceOnUse"><stop class="mxfqo-b2y"/><stop offset="1" class="z8_150olp"/></linearGradient><linearGradient id="iyEXdjd" x1="18.68" x2="28.374" y1="11.106" y2="7.636" gradientUnits="userSpaceOnUse"><stop class="m26ledckw"/><stop offset="1" class="yudgedput"/></linearGradient><linearGradient id="iVSRcTc" x1="18.284" x2="19.401" y1="15.444" y2="15.444" gradientUnits="userSpaceOnUse"><stop class="brzpz-p3w"/><stop offset="1" class="qxphtrj0e"/></linearGradient><linearGradient id="ioGVW4b" x1="20.43" x2="19.209" y1="15.828" y2="15.81" gradientUnits="userSpaceOnUse"><stop class="hcuo1obkg"/><stop offset="1" class="soj01hbui"/></linearGradient><linearGradient id="iIp0Oib" x1="19.544" x2="19.544" y1="16.712" y2="16.029" gradientUnits="userSpaceOnUse"><stop class="xk94moblk"/><stop offset="1" class="v1vf9kb3x"/></linearGradient><linearGradient id="iR0NXie" x1="19.462" x2="19.462" y1="16.761" y2="16.562" gradientUnits="userSpaceOnUse"><stop class="kpt7nxbeg"/><stop offset="1" class="c70lx944e"/></linearGradient><linearGradient id="iWe7E0c" x1="18.078" x2="18.596" y1="18.634" y2="17.816" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="ic5m5Uc" x1="22.832" x2="22.459" y1="13.448" y2="13.678" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i3gTvJd" x1="17.598" x2="17.225" y1="13.448" y2="13.678" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iai7JAe" x1="22.851" x2="22.351" y1="10.901" y2="9.879" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="i2BMAJe" x1="16.537" x2="15.121" y1="10.749" y2="10.155" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="iO5EvYE" x1="13.764" x2="13.764" y1="8.351" y2="10.919" gradientUnits="userSpaceOnUse"><stop offset=".228" class="zw2ljvb-t"/><stop offset="1" class="ohs50t_5m"/></linearGradient><filter id="i3AhY3R" width=".423" height="2.22" x="4.765" y="4.753" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3870" stdDeviation=".05"/></filter><filter id="iWYaKTN" width=".345" height="2.572" x="6.32" y="4.323" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3870" stdDeviation=".05"/></filter><filter id="il7Crje" width=".509" height="1.681" x="7.796" y="4.925" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3870" stdDeviation=".05"/></filter><filter id="i2xBeId" width="1.556" height="3.487" x="3.631" y="4.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3870" stdDeviation=".2"/></filter><filter id="ixbIvId" width="1.2" height="3.889" x="5.316" y="3.174" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3870" stdDeviation=".2"/></filter><filter id="iOXkoyK" width="1.488" height="4.773" x="6.864" y="2.248" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3870" stdDeviation=".2"/></filter><filter id="iwST8ib" width="2.002" height="4.299" x="8.267" y="3.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3870" stdDeviation=".2"/></filter><filter id="iGvi9cd" width="1.412" height="1.358" x="3.921" y="6.62" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3870" stdDeviation=".1"/></filter><filter id="iFK3Atd" width="1.118" height=".999" x="5.57" y="6.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3870" stdDeviation=".1"/></filter><filter id="isEIBDb" width="1.312" height="1.023" x="6.835" y="6.221" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3870" stdDeviation=".1"/></filter><filter id="iFlbYxc" width="9.217" height="11.911" x="5.665" y="12.298" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3870" stdDeviation=".75"/></filter><filter id="iYRSMWb" width="4.174" height="3.974" x="11.674" y="12.208" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3870"/></filter><filter id="iCJGj3b" width="3.369" height="3.369" x="11.977" y="12.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3870" stdDeviation=".25"/></filter><filter id="ipWfItb" width="4.224" height="4.224" x="22.998" y="11.958" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.368627 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3870"/></filter><filter id="iOISRge" width="3.369" height="3.369" x="23.301" y="12.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3870" stdDeviation=".25"/></filter><filter id="ibMknvc" width="12.348" height="14.567" x="13.173" y="7.501" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.2 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3870"/></filter><filter id="iOSpGle" width="9.054" height="7.65" x="17.515" y="5.501" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3870" stdDeviation="1"/></filter><filter id="i8XLQCe" width="15" height="10.075" x="11.813" y="3.457" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.109804 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3870"/></filter><filter id="i7Nb9Ec" width="3.595" height="4.692" x="17.231" y="12.964" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3870" stdDeviation=".375"/></filter><filter id="iacxRQV" width="2.734" height="3.692" x="17.946" y="13.27" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3870" stdDeviation=".125"/></filter><filter id="i5Haroc" width="3.499" height="2.153" x="20.72" y="9.928" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3870"/></filter><filter id="iSZZAVd" width="3.499" height="2.153" x="14.592" y="9.928" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3870"/></filter><filter id="iuw4pnH" width=".898" height=".791" x="21.052" y="12.879" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3870" stdDeviation=".05"/></filter><filter id="iof4VCd" width=".985" height="1.011" x="22.07" y="12.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3870" stdDeviation=".1"/></filter><filter id="iO2dhjb" width="1.098" height="1.162" x="16.783" y="12.912" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3870" stdDeviation=".1"/></filter><filter id="iVghhQd" width="1.049" height=".8" x="15.866" y="12.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3870" stdDeviation=".05"/></filter><filter id="iBoaaCe" width="3.701" height="2.013" x="20.54" y="9.996" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3870" stdDeviation=".25"/></filter><filter id="inLjWjc" width="3.794" height="2.081" x="14.326" y="10.072" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3870" stdDeviation=".25"/></filter><filter id="iO8D18d" width="1.057" height="2.559" x="13.235" y="8.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3870" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-raising-hand-medium" /></template>
<style>
.a1ftncccj {
  stop-color: var(--svg-color--8f6459, #8F6459);
  stop-opacity: 0;
}

.a53shnb1b {
  stop-color: var(--svg-color--724736, #724736);
}

.ads-kyhuz {
  d: path("M7.666 13.798v5.172a2 2 0 0 0 1.38 1.901l4.182 1.363");
}

.afx2mm9yw {
  d: path("M22.855 13.738a1 1 0 0 0-.275-.55l-.31.34l.14.27z");
}

.aiiux3bkj {
  fill: var(--svg-color--87565c, #87565C);
  d: path("m18.985 14.05l-.976 2.023c-.122.416.169.833.58.833h.878c.412 0 .702-.423.581-.833l-.593-2.023c-.127-.448-.337-.448-.47 0");
}

.an_-aznlj {
  stop-color: var(--svg-color--7c5267, #7C5267);
}

.awc29pfeb {
  stop-color: var(--svg-color--855169, #855169);
}

.b_ji9tgfr {
  stop-color: var(--svg-color--4496db, #4496DB);
  stop-opacity: 0;
}

.bac636b7w {
  stop-color: var(--svg-color--5b4545, #5B4545);
}

.bo3c15bma {
  stop-color: var(--svg-color--907374, #907374);
  stop-opacity: 0;
}

.brzpz-p3w {
  stop-color: var(--svg-color--8b6455, #8B6455);
}

.bxz0_yb6v {
  d: path("m18.858 13.856l-.633 2.023a.642.642 0 0 0 .62.833h.936a.644.644 0 0 0 .62-.833l-.633-2.023c-.136-.448-.768-.448-.91 0");
}

.c-9nnh-wl {
  fill: var(--svg-color--4f3332, #4F3332);
  d: path("m25.049 6.485l.51.254c.894.444 1.405 1.46 1.214 2.54l-.703 3.618c-.062.374-.31.625-.68.635h-.022s.064-1.08.128-1.714c.052-.516-.038-.673-.511-1.143c-.255-.254-.447-.635-.447-1.016V8.643c0-.317-.255-.57-.51-.634c-.767-.19-2.363-.508-4.662-.508s-3.895.317-4.66.508a.62.62 0 0 0-.511.634V9.66c0 .381-.128.762-.447 1.016l-.192.19c-.255.19-.383.572-.383.89c.064.697.128 1.713.128 1.713q-.03 0-.059-.002a.754.754 0 0 1-.708-.632l-.702-3.62c-.128-1.015.383-2.03 1.277-2.475l.51-.254c.32-.19.64-.444.959-.698l1.149-1.207c.702-.634 1.724-.825 2.618-.38a3.5 3.5 0 0 0 1.979 0c.958-.318 2.043-.064 2.81.634l.957.953c.255.317.575.507.958.698");
}

.c02-eqbxv {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
}

.c70lx944e {
  stop-color: var(--svg-color--8e5263, #8E5263);
  stop-opacity: 0;
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

.cq0mikryq {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m7.752 2.663l-.289 3.944");
}

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.cuep4p7fp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.388 6.713c-.13.164-.333.3-.518.399");
}

.czlx86s7a {
  stop-color: var(--svg-color--907374, #907374);
}

.d_0vt8b5r {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.464 12.493c-.777 0-1.433.536-1.612 1.26a.326.326 0 0 0 .319.405h2.655a.274.274 0 0 0 .27-.323a1.67 1.67 0 0 0-1.632-1.342");
}

.d3adwzboi {
  d: path("M13.173 11.754c0-.317.128-.698.383-.889l.192-.19c.319-.254.447-.635.447-1.016V8.643c0-.317.191-.571.51-.634c.767-.19 2.363-.508 4.661-.508c2.299 0 3.895.317 4.661.508c.256.063.511.317.511.634V9.66c0 .381.192.762.447 1.016c.598.419.56.65.51 1.143a55 55 0 0 0-.127 1.714h.022l-.317 4.711c-.19 2.107-1.847 3.575-3.821 3.575H17.43c-2.038 0-3.63-1.468-3.821-3.575c-.166-2.162-.239-4.33-.436-6.489");
}

.d66ufbbtl {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
  stop-opacity: 0;
}

.dcym8repk {
  stop-color: var(--svg-color--9b7168, #9B7168);
  stop-opacity: 0;
}

.dd8hfetks {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
  stop-opacity: 0;
}

.dg9o8ubcl {
  stop-color: var(--svg-color--895f52, #895F52);
  stop-opacity: 0;
}

.do50vzs5x {
  cx: 24.985px;
  cy: 14.196px;
  r: 1.184px;
  fill: var(--svg-color--a57c70, #A57C70);
}

.dy6shwbgc {
  d: path("m18.681 20.98l-7.874 5.245a.66.66 0 0 0-.4-.48L7.323 24.37c-2.5-1-3.5-3.5-3.5-5.198v-5.287c0-.564.425-1.015.935-1.015h4.13c.52 0 .935.461.935 1.015v3.985c0 1.302 1 1.5 1 1.5l6 1.5z");
}

.dz4ncrwcz {
  stop-color: var(--svg-color--09538b, #09538B);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e6v6vrbif {
  stop-color: var(--svg-color--ab7773, #AB7773);
}

.e873ol6-u {
  stop-color: var(--svg-color--3983b7, #3983B7);
  stop-opacity: 0;
}

.ea9kflbmr {
  d: path("m25.049 6.485l.51.254c.894.444 1.405 1.46 1.214 2.54l-.703 3.618c-.062.374-.31.625-.68.635h-.022s.064-1.08.128-1.714c.052-.516-.038-.673-.511-1.143c-.255-.254-.447-.635-.447-1.016V8.643c0-.317-.255-.57-.51-.634c-.767-.19-2.363-.508-4.662-.508s-3.895.317-4.66.508a.62.62 0 0 0-.511.634V9.66c0 .381-.128.762-.447 1.016l-.192.19c-.255.19-.383.572-.383.89c.064.697.128 1.713.128 1.713q-.03 0-.059-.002a.754.754 0 0 1-.708-.632l-.702-3.62c-.128-1.015.383-2.03 1.277-2.475l.51-.254c.32-.19.64-.444.959-.698l1.149-1.207c.702-.634 1.724-.825 2.618-.38a3.5 3.5 0 0 0 1.979 0c.958-.318 2.043-.064 2.81.634l.957.953c.255.317.575.507.958.698");
}

.eqzjb1bwj {
  stop-color: var(--svg-color--5b4545, #5B4545);
  stop-opacity: 0;
}

.ev4-2pfvs {
  stop-color: var(--svg-color--834e63, #834E63);
}

.ezu_a_bod {
  stop-color: var(--svg-color--4ab7ff, #4AB7FF);
  stop-opacity: 0;
}

.f3fovsmxj {
  d: path("M17.68 13.753c0-.343-.278-.572-.354-.64l-.343.331l.211.43z");
}

.f43nfdclv {
  stop-color: var(--svg-color--c69980, #C69980);
}

.f7hwkw-sq {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
}

.fkee40m0y {
  stop-color: var(--svg-color--8f5d78, #8F5D78);
}

.fr4wpbo2m {
  stop-color: var(--svg-color--422235, #422235);
}

.ft5dv1b6b {
  fill: none;
}

.ftgjbwy1h {
  d: path("M20.288 20.87h.97c2.49 0 7.472 3.5 7.472 9H10.797v-3.5a.67.67 0 0 0-.414-.625L7.31 24.37c-2.49-1-3.487-3.5-3.487-5.198v-5.287c0-.564.424-1.015.932-1.015h4.114c.518 0 .932.461.932 1.015v3.985c0 1.302.996 1.5.996 1.5l5.978 1.5z");
}

.fwwugibmc {
  stop-color: var(--svg-color--6e464d, #6E464D);
}

.fybh9obit {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M5.916 3.574v3.089");
}

.gxiobr4sb {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M21.83 13.04c.076.102-.082.225-.262.36s-.313.229-.389.128c-.075-.102.01-.293.19-.427c.179-.135.386-.162.462-.06");
}

.h0kcnqbkf {
  stop-color: var(--svg-color--814f57, #814F57);
}

.h3zwb1bvv {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.155 12.493c.777 0 1.434.536 1.613 1.26a.326.326 0 0 1-.32.405h-2.654a.274.274 0 0 1-.27-.323c.15-.763.82-1.342 1.631-1.342");
}

.hcuo1obkg {
  stop-color: var(--svg-color--cda186, #CDA186);
}

.hhjr4dufw {
  d: path("M16.71 12.816a1.062 1.062 0 0 0-1.023 1.342h2.052a1 1 0 0 0 .038-.28a1.07 1.07 0 0 0-1.067-1.062");
}

.hk_d6vbsx {
  stop-color: var(--svg-color--3394d1, #3394D1);
  stop-opacity: 0;
}

.hsqf8hwha {
  stop-color: var(--svg-color--724736, #724736);
  stop-opacity: 0;
}

.i2gq6_bzt {
  d: path("M21.909 12.816a1.062 1.062 0 0 1 1.023 1.342h-2.051a1.066 1.066 0 0 1 1.028-1.342");
}

.ik287t08j {
  stop-color: var(--svg-color--c09a87, #C09A87);
  stop-opacity: 0;
}

.iqmfu1bfz {
  stop-color: var(--svg-color--4496db, #4496DB);
}

.ity3_rbtf {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.687 17.486a.23.23 0 0 0-.277.048a.21.21 0 0 0-.023.273a2.3 2.3 0 0 0 1.926 1.029c.808 0 1.518-.412 1.926-1.03a.215.215 0 0 0-.024-.275a.23.23 0 0 0-.276-.045a3.5 3.5 0 0 1-1.626.385c-.596 0-1.156-.14-1.626-.385Z");
}

.iu5n-nb1z {
  stop-color: var(--svg-color--2877cd, #2877CD);
  stop-opacity: 0;
}

.ivhsfvmdg {
  stop-color: var(--svg-color--644949, #644949);
  stop-opacity: 0;
}

.iwzv9ac4a {
  fill: var(--svg-color--000, #000);
  d: path("M17.319 13.878a.606.606 0 0 0-.608-.608a.606.606 0 0 0-.541.888h1.076a.6.6 0 0 0 .073-.28");
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.ixdockwro {
  stop-color: var(--svg-color--916762, #916762);
}

.jcvtzfbuy {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("M14.82 10.958h.002v-.001l.003-.002l.005-.004l.015-.012l.042-.032a3 3 0 0 1 .641-.347a3.37 3.37 0 0 1 1.777-.188a.635.635 0 1 1-.198 1.255a2.1 2.1 0 0 0-1.111.115a1.8 1.8 0 0 0-.367.197a.635.635 0 0 1-.808-.98");
}

.je_aabb8l {
  stop-color: var(--svg-color--644949, #644949);
}

.jgymjdb_q {
  d: path("M3.606 8.903c-.125-1.922-.281-2.958-.328-3.64c-.035-.513.023-1.067.71-1.192c.599-.074.884.452.907.66c-.002-.2 0-.68 0-.804c0-.211.008-.977.86-.977c.6 0 .816.587.8.863c.01-.101.023-.413.035-.707c.019-.433.252-.989.946-.976c.597.039.793.613.765.976l-.117 1.868c.024-.188.103-.665.278-1.34s.701-.72.957-.684c.326.046.88.361.648 1.274c-.275 1.156-.462 2.644-.527 3.285c.324-.133.642-.413 1.001-.788c.36-.375.887-.383 1.184-.16c.34.293.522.967.12 1.37c-.463.425-2.13 2.405-2.958 3.394c-.229.292-.997.875-2.234.875c-2.203-.094-2.942-1.676-3.047-3.297");
}

.jnnef_lwj {
  cx: 24.985px;
  cy: 14.196px;
  r: 1.987px;
}

.ki2rd4v4k {
  stop-color: var(--svg-color--554042, #554042);
}

.kpt7nxbeg {
  stop-color: var(--svg-color--8e5263, #8E5263);
}

.kqiinhbwf {
  cx: 24.985px;
  cy: 14.196px;
  r: 1.184px;
}

.krd2fabda {
  stop-color: var(--svg-color--b7927f, #B7927F);
  stop-opacity: 0;
}

.kybxapb2q {
  stop-color: var(--svg-color--8e675e, #8E675E);
  stop-opacity: 0;
}

.kz-1anqws {
  cx: 13.661px;
  cy: 14.196px;
  r: 1.184px;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l9mhobcik {
  d: path("m24.03 7.5l-3.663 1.222a1.246 1.246 0 0 0 .56 2.418l3.642-.488z");
}

.lejfwxzry {
  stop-color: var(--svg-color--c8a48a, #C8A48A);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lign7ubxp {
  stop-color: var(--svg-color--2790d8, #2790D8);
}

.lkyvxhyoh {
  fill: var(--svg-color--000, #000);
  d: path("M21.3 13.878c0-.338.271-.608.609-.608a.606.606 0 0 1 .54.888h-1.076a.55.55 0 0 1-.072-.28");
}

.lnx1w7b3f {
  stop-color: var(--svg-color--9c745d, #9C745D);
  stop-opacity: 0;
}

.lrznj57_h {
  cx: 13.661px;
  cy: 14.196px;
  r: 1.987px;
}

.m--3robwq {
  stop-color: var(--svg-color--1b6b9f, #1B6B9F);
}

.m26ledckw {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
}

.m2h86lb3n {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m4.229 4.53l.36 2.633");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mifq-tdon {
  stop-color: var(--svg-color--c39787, #C39787);
}

.mmmkqcbgq {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
  stop-opacity: 0;
}

.msoqh-bjb {
  d: path("M21.83 13.04c.076.102-.082.225-.262.36s-.313.229-.389.128c-.075-.102.01-.293.19-.427c.179-.135.386-.162.462-.06");
}

.mxfqo-b2y {
  stop-color: var(--svg-color--c1987f, #C1987F);
}

.n-ko-_w7d {
  stop-color: var(--svg-color--c39787, #C39787);
  stop-opacity: 0;
}

.n4tmycgor {
  d: path("M19.323 23.976c-1.268 0-2.296-.985-2.296-2.2v-2.6c0-1.215 1.028-2.2 2.296-2.2s2.296.985 2.296 2.2v2.6c0 1.215-1.028 2.2-2.296 2.2");
}

.n6zd1v0yu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M21.29 10.786c.512-.09 1.51-.064 2.201.473");
}

.n7o-m0b5s {
  stop-color: var(--svg-color--624c49, #624C49);
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.njr1qzbcy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m4.903 4.89l.148 1.946");
}

.nrwls_btk {
  stop-color: var(--svg-color--2a6bc6, #2A6BC6);
}

.nwxnfd6vs {
  stop-color: var(--svg-color--408dc5, #408DC5);
}

.nzdq87b8k {
  stop-color: var(--svg-color--9b7569, #9B7569);
  stop-opacity: 0;
}

.o6qx6mc1p {
  stop-color: var(--svg-color--7f4a33, #7F4A33);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ohs50t_5m {
  stop-color: var(--svg-color--4a3236, #4A3236);
  stop-opacity: 0;
}

.oixb-3bxy {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m23.74 10.958l-.001-.001l-.002-.002l-.006-.004l-.014-.012l-.043-.032a3 3 0 0 0-.641-.347a3.37 3.37 0 0 0-1.777-.188a.635.635 0 1 0 .198 1.255c.474-.075.853.013 1.112.115a1.8 1.8 0 0 1 .367.197a.635.635 0 0 0 .807-.981");
}

.oscp2xoht {
  fill: var(--svg-color--b7877d, #B7877D);
  d: path("m18.858 13.856l-.633 2.023a.642.642 0 0 0 .62.833h.936a.644.644 0 0 0 .62-.833l-.633-2.023c-.136-.448-.768-.448-.91 0");
}

.ou0802bre {
  stop-color: var(--svg-color--1473af, #1473AF);
  stop-opacity: 0;
}

.p7vxhi0fa {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m9.674 3.71l-.812 3.406");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pr1c_plua {
  stop-color: var(--svg-color--a97f72, #A97F72);
}

.px0vdqe0d {
  stop-color: var(--svg-color--c09a87, #C09A87);
}

.pzn0rnkkd {
  stop-color: var(--svg-color--3473ab, #3473AB);
}

.q-hwntrrd {
  cx: 16.39px;
  cy: 13.27px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.464px;
  ry: 0.235px;
}

.qdtuxcc3i {
  stop-color: var(--svg-color--9e7963, #9E7963);
}

.qh6j1bbdz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M4.221 7.678c.11-.062.617-.379.813-.758");
}

.qmnjff_ag {
  stop-color: var(--svg-color--ab7773, #AB7773);
  stop-opacity: 0;
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
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

.qxphtrj0e {
  stop-color: var(--svg-color--8b6455, #8B6455);
  stop-opacity: 0;
}

.r31gy52yf {
  cx: 16.39px;
  cy: 13.27px;
  rx: 0.464px;
  ry: 0.235px;
}

.ria1jibpr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m6.528 4.46l-.07 2.298");
}

.rs939fpht {
  stop-color: var(--svg-color--7b585c, #7B585C);
}

.rtxxuvbkk {
  stop-color: var(--svg-color--56a6ff, #56A6FF);
}

.sla6kib8v {
  stop-color: var(--svg-color--ae7f75, #AE7F75);
}

.soj01hbui {
  stop-color: var(--svg-color--cda186, #CDA186);
  stop-opacity: 0;
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.suj-pjbhk {
  stop-color: var(--svg-color--895f52, #895F52);
}

.sy2nhlbqj {
  stop-color: var(--svg-color--7f4a33, #7F4A33);
}

.t-cwjacqu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.917 8.469v1.068c-.01.177-.084.572-.307.74");
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t6ahfk42q {
  stop-color: var(--svg-color--9c745d, #9C745D);
}

.tilf7ac3p {
  stop-color: var(--svg-color--2a6bc6, #2A6BC6);
  stop-opacity: 0;
}

.to6jezl8q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M15.076 11.403c.39-.344 1.24-.707 2.294-.539");
}

.tp9jx5j2y {
  stop-color: var(--svg-color--554042, #554042);
  stop-opacity: 0;
}

.ul7rmpbso {
  stop-color: var(--svg-color--4ab7ff, #4AB7FF);
}

.uwkg4cb-r {
  stop-color: var(--svg-color--408dc5, #408DC5);
  stop-opacity: 0;
}

.ux7-g74jy {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
}

.v1vf9kb3x {
  stop-color: var(--svg-color--9c6073, #9C6073);
  stop-opacity: 0;
}

.v74r7idhd {
  stop-color: var(--svg-color--3394d1, #3394D1);
}

.va6027bik {
  stop-color: var(--svg-color--186a98, #186A98);
  stop-opacity: 0;
}

.vo9agqbnp {
  stop-color: var(--svg-color--694448, #694448);
}

.vw_o3ubex {
  d: path("M13.242 13.466q.03.003.059.002s-.064-1.015-.128-1.714c0-.317.128-.698.383-.889l.192-.19c.319-.254.447-.635.447-1.016V8.643c0-.317.191-.571.51-.634c.767-.19 2.363-.508 4.661-.508c2.299 0 3.895.317 4.661.508c.256.063.511.317.511.634V9.66c0 .381.192.762.447 1.016c.598.419.56.65.51 1.143a55 55 0 0 0-.127 1.714h.022l-.317 4.711c-.19 2.107-1.847 3.575-3.821 3.575H17.43c-2.038 0-3.63-1.468-3.821-3.575z");
}

.w_j-6pbpp {
  stop-color: var(--svg-color--834e63, #834E63);
  stop-opacity: 0;
}

.w8p93gb0x {
  stop-color: var(--svg-color--3688bf, #3688BF);
}

.ww76qh22b {
  stop-color: var(--svg-color--c8a48a, #C8A48A);
}

.xaj4s_mqh {
  stop-color: var(--svg-color--9b7569, #9B7569);
}

.xbnxtbcba {
  d: path("M4.673 12.047c0-.11.09-.2.2-.2h3.811c.11 0 .2.09.2.2v1.714h-4.21z");
}

.xgo-prp7n {
  stop-color: var(--svg-color--b7927f, #B7927F);
}

.xk94moblk {
  stop-color: var(--svg-color--9c6073, #9C6073);
}

.xo-sv8bhm {
  stop-color: var(--svg-color--422235, #422235);
  stop-opacity: 0;
}

.xp-9f0bqu {
  stop-color: var(--svg-color--624c49, #624C49);
  stop-opacity: 0;
}

.yudgedput {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
  stop-opacity: 0;
}

.z_rannrme {
  d: path("m23.74 10.958l-.001-.001l-.002-.002l-.006-.004l-.014-.012l-.043-.032a3 3 0 0 0-.641-.347a3.37 3.37 0 0 0-1.777-.188a.635.635 0 1 0 .198 1.255c.474-.075.853.013 1.112.115a1.8 1.8 0 0 1 .367.197a.635.635 0 0 0 .807-.981");
}

.z4kh_va1f {
  d: path("M14.82 10.958h.002v-.001l.003-.002l.005-.004l.015-.012l.042-.032a3 3 0 0 1 .641-.347a3.37 3.37 0 0 1 1.777-.188a.635.635 0 1 1-.198 1.255a2.1 2.1 0 0 0-1.111.115a1.8 1.8 0 0 0-.367.197a.635.635 0 0 1-.808-.98");
}

.z8_150olp {
  stop-color: var(--svg-color--c1987f, #C1987F);
  stop-opacity: 0;
}

.zaioo08lx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("M8.168 5.062L7.934 6.47");
}

.zen3jbcth {
  stop-color: var(--svg-color--3983b7, #3983B7);
}

.zpuae6b8t {
  stop-color: var(--svg-color--127cc2, #127CC2);
  stop-opacity: 0;
}

.zw2ljvb-t {
  stop-color: var(--svg-color--4a3236, #4A3236);
}

.zzipvmdcm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M7.847 6.521c-.13.165-.501.36-.712.423");
}

</style>
