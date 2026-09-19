<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iakT1uc)" class="v7gluqbxb"/><g filter="url(#i9wJ78b)"><path fill="url(#iqwTWde)" clip-rule="evenodd" class="xzc44cc_j"/><path fill="url(#i5yYQHc)" clip-rule="evenodd" class="xzc44cc_j"/><path fill="url(#i9klPZd)" clip-rule="evenodd" class="xzc44cc_j"/><path fill="url(#iNw3Bfe)" clip-rule="evenodd" class="xzc44cc_j"/><path fill="url(#iH8BxLb)" clip-rule="evenodd" class="xzc44cc_j"/><path fill="url(#iQ3hYhd)" clip-rule="evenodd" class="xzc44cc_j"/><path fill="url(#i3AWrhD)" clip-rule="evenodd" class="xzc44cc_j"/><path fill="url(#izeyrGd)" clip-rule="evenodd" class="xzc44cc_j"/><path fill="url(#iz34B0M)" clip-rule="evenodd" class="xzc44cc_j"/><path fill="url(#ifbcTne)" clip-rule="evenodd" class="xzc44cc_j"/><path fill="url(#iWuAYpb)" clip-rule="evenodd" class="xzc44cc_j"/></g><path fill="url(#i2aa0Oc)" class="su72xqoac"/><path fill="url(#iDfO3Vb)" class="su72xqoac"/><path fill="url(#iPbok2c)" class="xu2szrbjd"/><path fill="url(#izGmjCe)" class="xu2szrbjd"/><path fill="url(#iqL9usb)" class="xu2szrbjd"/><path fill="url(#inrblnc)" class="xu2szrbjd"/><path fill="url(#iGzNNFc)" class="r3q9_wiir"/><path fill="url(#iw7An0a)" class="r3q9_wiir"/><path fill="url(#iViGBMM)" class="r3q9_wiir"/><path fill="url(#iCFheld)" class="r3q9_wiir"/><g filter="url(#i4AOVad)"><path fill="url(#iaSHNeb)" class="wk8vkxvjb"/></g><g filter="url(#i8CJzDe)"><path fill="url(#iVg82Db)" class="zehc2bc2m"/></g><g filter="url(#iqdjPWc)"><path fill="url(#iNQW5un)" class="r39_kb6dq"/></g><path fill="url(#i4t7TWb)" class="ztn-0pg6n"/><path fill="url(#ivSDZvr)" class="ztn-0pg6n"/><path fill="url(#iD1HD5c)" class="ztn-0pg6n"/><path fill="url(#iDvpDpd)" class="ztn-0pg6n"/><path fill="url(#iHhQ0NL)" class="ztn-0pg6n"/><path fill="url(#iM7SDhd)" class="mx0dy7bzm"/><path fill="url(#iQ7B0Vc)" class="mx0dy7bzm"/><path fill="url(#iw8F5Od)" class="mx0dy7bzm"/><path fill="url(#iItEm1T)" class="mx0dy7bzm"/><path fill="url(#i8MGWHb)" class="zehc2bc2m"/><path fill="url(#iC3KAHn)" class="qctpdhrvn"/><path fill="url(#iupneAV)" class="qctpdhrvn"/><path fill="url(#iakT1uc)" class="v7gluqbxb"/><path fill="url(#iriZyhb)" class="xazl-5b3q"/><path class="kua6vgb0k"/><path fill="url(#ic1k1Nb)" class="tq9nmh6wg"/><path fill="url(#iKkFNtc)" class="briaz_b_b"/><path fill="url(#ijPMi1c)" class="briaz_b_b"/><path fill="url(#icTS2Zb)" class="briaz_b_b"/><g filter="url(#irq8bce)"><rect class="dpvsui56n"/><rect fill="url(#izniTAb)" class="i6tsuwbjp"/><rect fill="url(#iVSfw3d)" class="i6tsuwbjp"/><rect fill="url(#ieqcHub)" class="i6tsuwbjp"/></g><path fill="url(#i3VTKjc)" class="b7ptc5bto"/><path fill="url(#i5TJHOH)" class="b7ptc5bto"/><path fill="url(#iY8Nhve)" class="b7ptc5bto"/><path fill="url(#iy710pt)" class="b7ptc5bto"/><path fill="url(#ikHXSJd)" class="edip7dywy"/><path fill="url(#iMtf6md)" class="l2nok66dj"/><g filter="url(#iCZMpkc)"><path fill="url(#iAQa3Ee)" class="k-hxoxbhg"/><path fill="url(#iI61LIc)" class="k-hxoxbhg"/><path fill="url(#icj0iib)" class="k-hxoxbhg"/><path fill="url(#igLTHZc)" class="k-hxoxbhg"/><path fill="url(#imPVYdl)" class="k-hxoxbhg"/></g><g filter="url(#ir5HQ0b)"><path stroke="url(#iGgfLte)" class="oyvjs-x-y"/></g><g filter="url(#iX3RWHb)"><path stroke="url(#iGP1Yrb)" class="rnmqrkbhw"/></g><g filter="url(#iVfmYTd)"><path stroke="url(#iXOHnge)" class="rmgd8acpv"/></g><g filter="url(#ibDGfqb)"><path fill="url(#io6VOcb)" class="z0b4bspnd"/></g><g filter="url(#i0Tybsb)"><path fill="url(#iQ7aRWb)" class="nl6m8oboo"/></g><g filter="url(#icayaKb)"><path class="is2-rm9rl"/><path fill="url(#iJ1JXQn)" class="n0zx1htzw"/></g><g filter="url(#iHq0uUb)"><path class="j944t7b4y"/><path fill="url(#iOHAJge)" class="r47pfjb1m"/></g><g filter="url(#iUjX2Oc)"><path fill="url(#iqJSnNx)" class="kbf5deyse"/><path fill="url(#iOnCUhi)" class="kbf5deyse"/><path fill="url(#iEJMpOM)" class="kbf5deyse"/><path fill="url(#i5v3w7y)" class="kbf5deyse"/><path fill="url(#iNhPlin)" class="kbf5deyse"/><path fill="url(#iBMhJCd)" class="kbf5deyse"/><path fill="url(#iSXgwlS)" class="kbf5deyse"/></g><path fill="url(#i0G4htb)" class="kbf5deyse"/><g filter="url(#iUuAJXc)"><path class="tocxavgag"/></g><g filter="url(#iQmx9kc)"><path fill="url(#ije2xHe)" class="l0oa60bqe"/><path fill="url(#iw3wzBd)" class="l0oa60bqe"/><path fill="url(#ioRF7Ie)" class="l0oa60bqe"/><path fill="url(#iraNTzc)" class="l0oa60bqe"/></g><path fill="url(#iDDClHd)" class="yd98qowkb"/><path fill="url(#i42Dnnb)" class="yd98qowkb"/><path stroke="url(#iQzvCmc)" class="krlyqhb_p"/><g filter="url(#i9lyxpc)"><path class="a2vzatbix"/></g><g filter="url(#iLztTsc)"><path class="cpmztcvnw"/></g><g filter="url(#iP4eeTb)"><path clip-rule="evenodd" class="jho7fp0ws"/></g><path class="aw-mzjbnt"/><path fill="url(#iDTeaHb)" class="if8d5_btg"/><path class="rpwi1zcyf"/><g filter="url(#iAo3oUb)"><path class="ak72hopku"/></g><path class="o9uhuu5-x"/><path fill="url(#igxXm8L)" class="lhcs9cc6n"/><path class="xyeqa6bqm"/><g filter="url(#iEIcagE)"><path class="rfihmeb7t"/><path fill="url(#i5KHVcc)" class="o7epp0bzj"/></g><g filter="url(#iYkgjCa)"><path fill="url(#iCTAiOb)" class="kri2xabhg"/></g><g filter="url(#ic9rTcc)"><path fill="url(#iHFMwdd)" class="ilkkrkb1w"/></g><g filter="url(#iRdw0wc)"><ellipse transform="rotate(-27.914 13 9.905)" class="i-49h5vxx"/><ellipse fill="url(#iiwzl1d)" transform="rotate(-27.914 13 9.905)" class="hhuggwz1h"/></g><g filter="url(#iyE7Dqb)"><path class="m9udaht4q"/></g><g filter="url(#ixRxjbc)"><path class="ljkt_bcky"/></g><g filter="url(#ihGVuJe)"><path fill="url(#iJw8yrb)" class="gx0v65jmq"/><path fill="url(#iocCdfd)" class="gx0v65jmq"/></g><g filter="url(#i1s3HKb)"><path fill="url(#idX3txc)" class="k4wir2bzl"/><path fill="url(#igEeH6c)" class="k4wir2bzl"/><path fill="url(#iQrNRjd)" class="k4wir2bzl"/></g><g filter="url(#i22R7yw)"><path stroke="url(#iAepbud)" class="zh9_ydbxc"/></g><path fill="url(#iRYRJXe)" class="uc1cxyvnm"/><g filter="url(#iZzDdSb)"><path clip-rule="evenodd" class="be9nqnwdq"/></g><defs><radialGradient id="i5yYQHc" cx="0" cy="0" r="1" gradientTransform="matrix(2.9187 2.33151 -3.30247 4.13418 19.269 13.777)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="vkjpfvbgu"/><stop offset="1" class="i2-0q3b1j"/></radialGradient><radialGradient id="i9klPZd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.45645 -2.68487 0 10.875 12.512)" gradientUnits="userSpaceOnUse"><stop class="lcrdwk1fj"/><stop offset="1" class="denqa3bda"/></radialGradient><radialGradient id="iNw3Bfe" cx="0" cy="0" r="1" gradientTransform="scale(5.8032 5.57099)rotate(90 .2 2.462)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="ag6fa4z4y"/><stop offset="1" class="qir_1cb0f"/></radialGradient><radialGradient id="iH8BxLb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.24075 1.61016 -1.56338 -1.2047 10.535 10.8)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="ha2cq84sa"/><stop offset="1" class="p4wkjrbae"/></radialGradient><radialGradient id="iQ3hYhd" cx="0" cy="0" r="1" gradientTransform="matrix(-.46758 2.51377 -2.61762 -.4869 11.126 8.363)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="tgqxysbgm"/><stop offset="1" class="p1xq25bjq"/></radialGradient><radialGradient id="i3AWrhD" cx="0" cy="0" r="1" gradientTransform="rotate(62.605 3.328 11.615)scale(2.38097 4.53569)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="esx41hbqq"/><stop offset=".921" class="v9rq5jjti"/></radialGradient><radialGradient id="izeyrGd" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 9.43 6.973)scale(1.63713 2.28786)" gradientUnits="userSpaceOnUse"><stop class="duwob45dr"/><stop offset="1" class="v61l3jbat"/></radialGradient><radialGradient id="iz34B0M" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.16706 -4.01156 22.955 9.627)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="hottnizrg"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="ifbcTne" cx="0" cy="0" r="1" gradientTransform="rotate(-133.315 14.294 4.152)scale(4.66215 6.69539)" gradientUnits="userSpaceOnUse"><stop class="yqk-2gbyp"/><stop offset="1" class="oaxszm67z"/></radialGradient><radialGradient id="iWuAYpb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00843 -1.37436 .45061 -.00276 12.741 5.81)" gradientUnits="userSpaceOnUse"><stop offset=".295" class="sufhn4bec"/><stop offset="1" class="kpf8h5ohf"/></radialGradient><radialGradient id="i2aa0Oc" cx="0" cy="0" r="1" gradientTransform="scale(3.29991 5.8125)rotate(90 .76 3.921)" gradientUnits="userSpaceOnUse"><stop class="m3bo30rid"/><stop offset="1" class="nbiohly8w"/></radialGradient><radialGradient id="iDfO3Vb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.65625 6.93357 0 15.446 30.378)" gradientUnits="userSpaceOnUse"><stop class="bfl4-fbqr"/><stop offset="1" class="frstvbc2m"/></radialGradient><radialGradient id="iPbok2c" cx="0" cy="0" r="1" gradientTransform="rotate(161.686 4.488 14.592)scale(4.67425 7.57955)" gradientUnits="userSpaceOnUse"><stop class="d-w3_abhe"/><stop offset="1" class="bqs6izbmd"/></radialGradient><radialGradient id="inrblnc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.375 -2.57376 0 9.302 17.472)" gradientUnits="userSpaceOnUse"><stop class="x3hlfcbwc"/><stop offset="1" class="sfpaimhix"/></radialGradient><radialGradient id="iGzNNFc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.15073 2.71782 0 21.206 30.347)" gradientUnits="userSpaceOnUse"><stop class="rfuz_acet"/><stop offset="1" class="q-fl22tnr"/></radialGradient><radialGradient id="iw7An0a" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.15625 -3.9375 0 22.77 18.597)" gradientUnits="userSpaceOnUse"><stop class="n8vj2kb3y"/><stop offset="1" class="irjqokbks"/></radialGradient><radialGradient id="iVg82Db" cx="0" cy="0" r="1" gradientTransform="matrix(-3.7279 1.31251 -2.69681 -7.65971 14.999 21.972)" gradientUnits="userSpaceOnUse"><stop class="iezv8nbum"/><stop offset="1" class="ry-6rkb7q"/></radialGradient><radialGradient id="i4t7TWb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.74796 3.71877 -3.74799 -3.7774 22.49 17.753)" gradientUnits="userSpaceOnUse"><stop class="y5gxirbqq"/><stop offset="1" class="t0qf5rbqk"/></radialGradient><radialGradient id="ivSDZvr" cx="0" cy="0" r="1" gradientTransform="rotate(-64.11 29.357 -.224)scale(8.30198 11.1931)" gradientUnits="userSpaceOnUse"><stop class="mvrro-b_u"/><stop offset=".93" class="ocku6nzyd"/></radialGradient><radialGradient id="iD1HD5c" cx="0" cy="0" r="1" gradientTransform="matrix(-.73439 2.1875 -3.93465 -1.32095 19.943 16.05)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="lwgxwcc9p"/><stop offset="1" class="brppywbtt"/></radialGradient><radialGradient id="iM7SDhd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.95848 0 0 -8.5991 8.226 26.174)" gradientUnits="userSpaceOnUse"><stop class="xoi7hsb-w"/><stop offset="1" class="hkq9astav"/></radialGradient><radialGradient id="iw8F5Od" cx="0" cy="0" r="1" gradientTransform="matrix(-7.51743 0 0 -10.8202 10.005 29.03)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="c1dciy28n"/><stop offset="1" class="vxd8ts5kx"/></radialGradient><radialGradient id="i8MGWHb" cx="0" cy="0" r="1" gradientTransform="rotate(109.374 .564 12.51)scale(3.01445 6.53104)" gradientUnits="userSpaceOnUse"><stop offset=".058" class="hxg13bqik"/><stop offset="1" class="k10lreb3f"/></radialGradient><radialGradient id="iC3KAHn" cx="0" cy="0" r="1" gradientTransform="matrix(.41584 12.10916 -8.52544 .29277 24.177 17.94)" gradientUnits="userSpaceOnUse"><stop class="v6ge5bcpf"/><stop offset="1" class="z78o0obou"/></radialGradient><radialGradient id="iriZyhb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.59837 5.09841 0 15.426 18.68)" gradientUnits="userSpaceOnUse"><stop class="yzv5f8bpf"/><stop offset=".621" class="p4jiy8bvo"/><stop offset="1" class="vj4_95wuu"/></radialGradient><radialGradient id="ic1k1Nb" cx="0" cy="0" r="1" gradientTransform="rotate(131.186 8.022 17.939)scale(.74743 .79607)" gradientUnits="userSpaceOnUse"><stop class="u7id6gble"/><stop offset="1" class="ydn9dmb6d"/></radialGradient><radialGradient id="icTS2Zb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.54688 -.39416 0 25.571 19.44)" gradientUnits="userSpaceOnUse"><stop class="hkh0bccgk"/><stop offset="1" class="sfa02aclf"/></radialGradient><radialGradient id="izniTAb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.91833 0 0 -.20741 25.177 19.128)" gradientUnits="userSpaceOnUse"><stop offset=".496" class="afeb8bsjy"/><stop offset="1" class="rced3uh7f"/></radialGradient><radialGradient id="iVSfw3d" cx="0" cy="0" r="1" gradientTransform="matrix(-.28516 .14844 -.12607 -.24218 27.004 18.98)" gradientUnits="userSpaceOnUse"><stop class="p4k8mjbje"/><stop offset="1" class="e1oaafz6u"/></radialGradient><radialGradient id="ieqcHub" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .13281 -.08816 -.11928 23.407 19.34)" gradientUnits="userSpaceOnUse"><stop class="bj_z41bxg"/><stop offset="1" class="boi6rx35q"/></radialGradient><radialGradient id="iy710pt" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.34375 -.51563 0 26.227 21.284)" gradientUnits="userSpaceOnUse"><stop class="tsloro5fn"/><stop offset="1" class="p9rinuedy"/></radialGradient><radialGradient id="iI61LIc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.44615 2.39061 -1.97778 -1.19642 27.454 24.644)" gradientUnits="userSpaceOnUse"><stop class="tqgfgwd_y"/><stop offset="1" class="de0rqgbhp"/></radialGradient><radialGradient id="icj0iib" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 0 0 .46609 23.323 26.02)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><radialGradient id="igLTHZc" cx="0" cy="0" r="1" gradientTransform="matrix(2.59241 0 0 .5225 23.137 27.347)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><radialGradient id="imPVYdl" cx="0" cy="0" r="1" gradientTransform="matrix(2.71875 0 0 .32813 23.041 28.613)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><radialGradient id="iQ7aRWb" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 19.485 10.917)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="iJ1JXQn" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 39.952 -50.614)scale(1.30459)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="iOHAJge" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07411 0 0 -1.02745 10.78 10.478)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="iqJSnNx" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.062 6.98)scale(7.16175 9.58588)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset="1" class="m45oyzb-o"/></radialGradient><radialGradient id="iOnCUhi" cx="0" cy="0" r="1" gradientTransform="matrix(-2.10973 1.11592 -.94678 -1.78996 17.346 10.638)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="iEJMpOM" cx="0" cy="0" r="1" gradientTransform="matrix(.8369 -4.04513 5.13253 1.06187 13.266 16.724)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="i5v3w7y" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.44059 -11.8177 0 15.184 9.457)" gradientUnits="userSpaceOnUse"><stop offset=".593" class="ajxs5ri3z"/><stop offset="1" class="x05md6_2b"/></radialGradient><radialGradient id="iNhPlin" cx="0" cy="0" r="1" gradientTransform="matrix(-5.42256 1.49953 -2.58173 -9.33598 16.073 11.597)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></radialGradient><radialGradient id="iBMhJCd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 17.747 9.522)" gradientUnits="userSpaceOnUse"><stop class="e0lgwbeaw"/><stop offset="1" class="y7n0ymbzx"/></radialGradient><radialGradient id="iSXgwlS" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36 1.55865 0 13.528 9.61)" gradientUnits="userSpaceOnUse"><stop class="w2e_edyjl"/><stop offset="1" class="gsggv-b-p"/></radialGradient><radialGradient id="i0G4htb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34695 0 0 -4.43421 20.541 11.01)" gradientUnits="userSpaceOnUse"><stop class="f902gfhfn"/><stop offset="1" class="jh40i5bvl"/></radialGradient><radialGradient id="iw3wzBd" cx="0" cy="0" r="1" gradientTransform="matrix(-.69746 -2.44974 1.40177 -.3991 16.23 11.737)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="i42Dnnb" cx="0" cy="0" r="1" gradientTransform="rotate(144.462 6.02 8.285)scale(1.57489 2.10945)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="e6-lebcyw"/><stop offset="1" class="b8os9sbcy"/></radialGradient><radialGradient id="iDTeaHb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .84135 -1.33826 0 13.282 10.005)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="igxXm8L" cx="0" cy="0" r="1" gradientTransform="matrix(0 .83765 -1.33237 0 17.637 10.001)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i5KHVcc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.17 .783)scale(.39025 .53728)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iiwzl1d" cx="0" cy="0" r="1" gradientTransform="matrix(-.00802 -.51193 .61536 -.00963 12.985 10.232)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iJw8yrb" cx="0" cy="0" r="1" gradientTransform="rotate(129.554 5.535 4.761)scale(5.36951 2.34181)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="esh4v5qtq"/><stop offset=".911" class="nria2ku7r"/></radialGradient><radialGradient id="iocCdfd" cx="0" cy="0" r="1" gradientTransform="rotate(144.458 5.643 4.054)scale(3.81321 1.88454)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="dpv-wxbjb"/><stop offset="1" class="abu2lcc5n"/><stop offset="1" class="sxoxd_kke"/></radialGradient><radialGradient id="idX3txc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.18534 4.55504 -6.4674 -3.10282 17.237 2.353)" gradientUnits="userSpaceOnUse"><stop offset=".627" class="crfaaqblp"/><stop offset="1" class="ehjghj3fe"/></radialGradient><radialGradient id="igEeH6c" cx="0" cy="0" r="1" gradientTransform="rotate(105.909 7.616 8.58)scale(3.44004 7.20923)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="z-gx2rb2w"/><stop offset="1" class="gbpc14bxe"/></radialGradient><radialGradient id="iQrNRjd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.41682 -6.46744 5.78149 -3.05443 16.596 9.238)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="s3t3owbgt"/><stop offset="1" class="yehxt3bls"/></radialGradient><linearGradient id="iakT1uc" x1="8.23" x2="22.659" y1="15.358" y2="15.358" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iqwTWde" x1="20.139" x2="12.898" y1="3.526" y2="16.968" gradientUnits="userSpaceOnUse"><stop class="yr1vjkbzu"/><stop offset="1" class="btu9i2bec"/></linearGradient><linearGradient id="izGmjCe" x1="11.239" x2="11.239" y1="30.472" y2="29.159" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iqL9usb" x1="15.177" x2="14.208" y1="29.159" y2="29.159" gradientUnits="userSpaceOnUse"><stop offset=".129" class="dx1e6jb0z"/><stop offset="1" class="q4mowll4q"/></linearGradient><linearGradient id="iViGBMM" x1="19.74" x2="19.74" y1="30.472" y2="29.159" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iCFheld" x1="15.802" x2="16.505" y1="28.034" y2="28.034" gradientUnits="userSpaceOnUse"><stop class="bx23o8bkx"/><stop offset="1" class="i4kgizoks"/></linearGradient><linearGradient id="iaSHNeb" x1="10.458" x2="12.677" y1="18.091" y2="24.779" gradientUnits="userSpaceOnUse"><stop class="v4-zmrbyl"/><stop offset="1" class="r-0tl8b_g"/></linearGradient><linearGradient id="iNQW5un" x1="20.633" x2="18.282" y1="19.142" y2="23.843" gradientUnits="userSpaceOnUse"><stop class="z4xhuybyb"/><stop offset="1" class="lkjzf4omc"/></linearGradient><linearGradient id="iDvpDpd" x1="18.958" x2="17.552" y1="24.159" y2="22.659" gradientUnits="userSpaceOnUse"><stop class="p2mir8bpk"/><stop offset="1" class="ifg4wbcuq"/></linearGradient><linearGradient id="iHhQ0NL" x1="17.146" x2="17.974" y1="18.941" y2="19.284" gradientUnits="userSpaceOnUse"><stop offset=".081" class="q_2usqome"/><stop offset="1" class="z_a2ribdx"/></linearGradient><linearGradient id="iQ7B0Vc" x1="6.567" x2="6.567" y1="30.414" y2="29.281" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iItEm1T" x1="8.38" x2="7.935" y1="29.448" y2="29.446" gradientUnits="userSpaceOnUse"><stop offset=".175" class="w01lnqx9a"/><stop offset="1" class="xx10debny"/></linearGradient><linearGradient id="iupneAV" x1="22.753" x2="23.162" y1="27.722" y2="27.706" gradientUnits="userSpaceOnUse"><stop class="ckzhu0bvt"/><stop offset="1" class="dtqi4cbss"/></linearGradient><linearGradient id="iKkFNtc" x1="23.825" x2="26.529" y1="20.909" y2="20.909" gradientUnits="userSpaceOnUse"><stop offset=".253" class="cpykpvzxv"/><stop offset=".773" class="ahix7mbin"/></linearGradient><linearGradient id="ijPMi1c" x1="26.529" x2="26.18" y1="20.894" y2="20.894" gradientUnits="userSpaceOnUse"><stop class="g1a66we9o"/><stop offset="1" class="c3eiz-bza"/></linearGradient><linearGradient id="i3VTKjc" x1="26.529" x2="25.177" y1="23.222" y2="23.222" gradientUnits="userSpaceOnUse"><stop offset=".477" class="ubsir5m6c"/><stop offset="1" class="v0fk_zbwr"/></linearGradient><linearGradient id="i5TJHOH" x1="26.529" x2="26.129" y1="23.37" y2="23.37" gradientUnits="userSpaceOnUse"><stop class="bywelvb6j"/><stop offset="1" class="s44sum5km"/></linearGradient><linearGradient id="iY8Nhve" x1="23.696" x2="24.227" y1="23.37" y2="23.37" gradientUnits="userSpaceOnUse"><stop class="jr9zsmblm"/><stop offset="1" class="r1tra0r1f"/></linearGradient><linearGradient id="ikHXSJd" x1="24.782" x2="23.892" y1="21.863" y2="21.863" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="iMtf6md" x1="24.782" x2="23.892" y1="23.644" y2="23.644" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="iAQa3Ee" x1="27.165" x2="23.137" y1="28.112" y2="28.112" gradientUnits="userSpaceOnUse"><stop class="ut7pv-xgw"/><stop offset=".861" class="oltxz8b0t"/></linearGradient><linearGradient id="iGgfLte" x1="25.434" x2="23.599" y1="26.052" y2="26.052" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="iGP1Yrb" x1="25.356" x2="23.52" y1="27.357" y2="27.357" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="iXOHnge" x1="25.434" x2="23.599" y1="28.661" y2="28.661" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="io6VOcb" x1="9.151" x2="12.11" y1="10.565" y2="10.565" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="ije2xHe" x1="15.446" x2="15.446" y1="12.517" y2="9.835" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="ioRF7Ie" x1="14.399" x2="15.254" y1="11.754" y2="11.859" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="iraNTzc" x1="15.446" x2="15.446" y1="12.608" y2="11.998" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="iDDClHd" x1="15.524" x2="15.524" y1="12.731" y2="12.591" gradientUnits="userSpaceOnUse"><stop class="b8os9sbcy"/><stop offset="1" class="e6-lebcyw"/></linearGradient><linearGradient id="iQzvCmc" x1="14.717" x2="15.169" y1="14.085" y2="13.214" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="iCTAiOb" x1="18.439" x2="18.116" y1="10.056" y2="10.256" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iHFMwdd" x1="14.053" x2="13.728" y1="10.06" y2="10.261" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iAepbud" x1="12.555" x2="13.099" y1="4.28" y2="5.554" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient><linearGradient id="iRYRJXe" x1="10.917" x2="22.177" y1="9.789" y2="9.789" gradientUnits="userSpaceOnUse"><stop offset=".436" class="ksjv3r0ar"/><stop offset="1" class="cey6-nbgg"/></linearGradient><filter id="i9wJ78b" width="15.268" height="15.268" x="7.937" y="1.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.537255 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2164"/></filter><filter id="i4AOVad" width="7.023" height="11.703" x="8.372" y="15.865" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2164" stdDeviation=".375"/></filter><filter id="i8CJzDe" width="5.673" height="10.453" x="9.475" y="15.668" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.721569 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2164"/></filter><filter id="iqdjPWc" width="6.388" height="10.529" x="15.682" y="16.452" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2164" stdDeviation=".375"/></filter><filter id="irq8bce" width="4.008" height=".781" x="23.173" y="18.738" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.796078 0 0 0 0 0.94902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2164"/></filter><filter id="iCZMpkc" width="4.618" height="5.556" x="23.137" y="24.494" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.521569 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2164"/></filter><filter id="ir5HQ0b" width="2.047" height=".25" x="23.629" y="25.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2164" stdDeviation=".05"/></filter><filter id="iX3RWHb" width="2.047" height=".25" x="23.551" y="27.232" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2164" stdDeviation=".05"/></filter><filter id="iVfmYTd" width="2.047" height=".25" x="23.629" y="28.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2164" stdDeviation=".05"/></filter><filter id="ibDGfqb" width="3.318" height="3.218" x="9.151" y="8.869" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.501961 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2164"/></filter><filter id="i0Tybsb" width="3.218" height="3.468" x="18.664" y="8.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2164"/></filter><filter id="icayaKb" width="3.148" height="3.148" x="18.699" y="8.904" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2164" stdDeviation=".25"/></filter><filter id="iHq0uUb" width="2.648" height="2.648" x="9.455" y="9.154" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2164" stdDeviation=".125"/></filter><filter id="iUjX2Oc" width="10.191" height="11.277" x="10.351" y="5.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2164"/></filter><filter id="iUuAJXc" width="2.877" height="3.682" x="13.845" y="9.622" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2164" stdDeviation=".25"/></filter><filter id="iQmx9kc" width="2.377" height="3.182" x="14.257" y="9.585" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2164" stdDeviation=".125"/></filter><filter id="i9lyxpc" width="3.105" height="1.333" x="11.456" y="9.167" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2164"/></filter><filter id="iLztTsc" width="2.453" height="1.091" x="11.638" y="7.65" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.499183 0 0 0 0 0.226618 0 0 0 0 0.135763 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2164"/></filter><filter id="iP4eeTb" width="2.453" height="1.091" x="17.055" y="7.65" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.499183 0 0 0 0 0.226618 0 0 0 0 0.135763 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2164"/></filter><filter id="iAo3oUb" width="3.092" height="1.327" x="16.363" y="9.167" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2164"/></filter><filter id="iEIcagE" width=".805" height=".712" x="16.882" y="9.55" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2164" stdDeviation=".05"/></filter><filter id="iYkgjCa" width=".907" height=".93" x="17.752" y="9.631" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2164" stdDeviation=".1"/></filter><filter id="ic9rTcc" width="1.008" height="1.063" x="13.317" y="9.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2164" stdDeviation=".1"/></filter><filter id="iRdw0wc" width=".939" height=".723" x="12.531" y="9.544" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2164" stdDeviation=".05"/></filter><filter id="iyE7Dqb" width="2.661" height="1.378" x="16.885" y="7.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2164" stdDeviation=".2"/></filter><filter id="ixRxjbc" width="2.661" height="1.378" x="11.434" y="7.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2164" stdDeviation=".2"/></filter><filter id="ihGVuJe" width="4.985" height="5.213" x="8.738" y="3.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2164" stdDeviation=".375"/></filter><filter id="i1s3HKb" width="8.914" height="5.78" x="12.129" y="2.404" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2164" stdDeviation=".125"/></filter><filter id="i22R7yw" width="1.145" height="2.31" x="12.255" y="3.636" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2164" stdDeviation=".125"/></filter><filter id="iZzDdSb" width="11.479" height="6.324" x="9.611" y="6.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.529412 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2164"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.788235 0 0 0 0 0.760784 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2164" result="effect2_innerShadow_4002_2164"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-scientist" /></template>
<style>
.a2vzatbix {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.36 10.034c-.275-.484-.693-.867-1.594-.867c-.394 0-.774.11-1.112.383c-.279.225-.242.513-.026.621l.577.33c.676-.22 1.423-.249 2.156-.467");
}

.a9dfe182j {
  stop-color: var(--svg-color--d4993e, #D4993E);
}

.abu2lcc5n {
  stop-color: var(--svg-color--ffe134, #FFE134);
  stop-opacity: 0;
}

.afeb8bsjy {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
}

.ag6fa4z4y {
  stop-color: var(--svg-color--e26b25, #E26B25);
}

.ahix7mbin {
  stop-color: var(--svg-color--bff0ff, #BFF0FF);
}

.ajxs5ri3z {
  stop-color: var(--svg-color--f3943b, #F3943B);
  stop-opacity: 0;
}

.ak72hopku {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M16.563 10.03c.274-.482.69-.863 1.587-.863c.393 0 .771.109 1.108.38c.277.225.24.512.025.62l-.574.327c-.673-.217-1.417-.247-2.146-.464");
}

.aw-mzjbnt {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.065 9.228c-.677 0-1.25.467-1.405 1.098a.284.284 0 0 0 .278.353h2.314a.24.24 0 0 0 .235-.281a1.45 1.45 0 0 0-1.422-1.17");
}

.b7ptc5bto {
  d: path("M26.529 21.284v4.172h-2.704v-4.172z");
}

.b8os9sbcy {
  stop-color: var(--svg-color--e2802f, #E2802F);
}

.be9nqnwdq {
  fill: var(--svg-color--ac9faf, #AC9FAF);
  fill-rule: evenodd;
  d: path("M9.761 9.231c.012-1.676 1.389-3.005 3.047-3.005h5.275a3.01 3.01 0 0 1 3.007 3.04v.001c-.022 1.568-1.339 2.918-2.907 2.973h-.002a3.06 3.06 0 0 1-2.63-1.342c-.045-.065-.09-.076-.112-.076s-.067.01-.112.076a3.08 3.08 0 0 1-2.549 1.352a3.02 3.02 0 0 1-3.017-3.017zm.6.003a2.42 2.42 0 0 0 2.417 2.416c.841 0 1.62-.435 2.05-1.085l.002-.003a.74.74 0 0 1 .609-.34c.243 0 .465.128.609.34v.001a2.46 2.46 0 0 0 2.114 1.077c1.248-.044 2.31-1.133 2.328-2.381a2.41 2.41 0 0 0-2.407-2.433h-5.275c-1.336 0-2.437 1.07-2.447 2.408");
}

.bfl4-fbqr {
  stop-color: var(--svg-color--5f4786, #5F4786);
}

.bj_z41bxg {
  stop-color: var(--svg-color--caedff, #CAEDFF);
}

.boi6rx35q {
  stop-color: var(--svg-color--caedff, #CAEDFF);
  stop-opacity: 0;
}

.bqs6izbmd {
  stop-color: var(--svg-color--cdc1db, #CDC1DB);
}

.briaz_b_b {
  d: path("M23.825 19.519h2.703v5.938h-2.703z");
}

.brppywbtt {
  stop-color: var(--svg-color--f7ddd3, #F7DDD3);
  stop-opacity: 0;
}

.btu9i2bec {
  stop-color: var(--svg-color--e37923, #E37923);
}

.bx23o8bkx {
  stop-color: var(--svg-color--b28598, #B28598);
}

.bywelvb6j {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
}

.bzewrsgmw {
  stop-color: var(--svg-color--df9728, #DF9728);
  stop-opacity: 0;
}

.c1dciy28n {
  stop-color: var(--svg-color--c4c1c3, #C4C1C3);
  stop-opacity: 0;
}

.c3eiz-bza {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
  stop-opacity: 0;
}

.cey6-nbgg {
  stop-color: var(--svg-color--c4c58e, #C4C58E);
  stop-opacity: 0.5;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ckzhu0bvt {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
}

.cpmztcvnw {
  fill: var(--svg-color--bd4f26, #BD4F26);
  d: path("m12.048 8.7l-.004.003a.268.268 0 0 1-.276-.46l.002-.001l.003-.002l.009-.005a2 2 0 0 1 .148-.077a3 3 0 0 1 .41-.162c.34-.108.816-.2 1.329-.109a.268.268 0 1 1-.093.528a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.434.181z");
}

.cpykpvzxv {
  stop-color: var(--svg-color--a3d3ff, #A3D3FF);
}

.crfaaqblp {
  stop-color: var(--svg-color--f49523, #F49523);
  stop-opacity: 0;
}

.cu_6wobdp {
  stop-color: var(--svg-color--c88714, #C88714);
  stop-opacity: 0;
}

.d-w3_abhe {
  stop-color: var(--svg-color--e3d3fa, #E3D3FA);
}

.d7d_80btw {
  stop-color: var(--svg-color--0e7268, #0E7268);
}

.de0rqgbhp {
  stop-color: var(--svg-color--ffe136, #FFE136);
  stop-opacity: 0;
}

.denqa3bda {
  stop-color: var(--svg-color--d77117, #D77117);
  stop-opacity: 0;
}

.dpv-wxbjb {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
}

.dpvsui56n {
  width: 4.008px;
  height: 0.781px;
  x: 23.173px;
  y: 18.738px;
  fill: var(--svg-color--addaff, #ADDAFF);
  rx: 0.391px;
}

.dtqi4cbss {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
  stop-opacity: 0;
}

.duwob45dr {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
}

.dx1e6jb0z {
  stop-color: var(--svg-color--be9bb3, #BE9BB3);
}

.e0lgwbeaw {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
}

.e1oaafz6u {
  stop-color: var(--svg-color--d3faff, #D3FAFF);
  stop-opacity: 0;
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.e6-lebcyw {
  stop-color: var(--svg-color--e2802f, #E2802F);
  stop-opacity: 0;
}

.edip7dywy {
  d: path("M23.825 22.097v-.469h.805a.234.234 0 1 1 0 .469z");
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.ehjghj3fe {
  stop-color: var(--svg-color--f49523, #F49523);
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.esh4v5qtq {
  stop-color: var(--svg-color--ee971b, #EE971B);
  stop-opacity: 0;
}

.esx41hbqq {
  stop-color: var(--svg-color--cba140, #CBA140);
}

.f902gfhfn {
  stop-color: var(--svg-color--ffda39, #FFDA39);
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
}

.fkdj3ejgt {
  stop-color: var(--svg-color--f8c73f, #F8C73F);
}

.frstvbc2m {
  stop-color: var(--svg-color--5f4786, #5F4786);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g1a66we9o {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
}

.gbpc14bxe {
  stop-color: var(--svg-color--ffe337, #FFE337);
  stop-opacity: 0;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.glaz8zb9m {
  stop-color: var(--svg-color--c07200, #C07200);
}

.gsggv-b-p {
  stop-color: var(--svg-color--f09429, #F09429);
  stop-opacity: 0;
}

.gx0v65jmq {
  d: path("M10.552 4.464c.62-.553 1.517-.558 2.02-.469l.402 1.29c-.257-.039-.486.05-.68.235c-.455 1.26-2.022 1.956-2.748 2.146c-.15-1.492-.067-2.246 1.006-3.202");
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h11_utkon {
  stop-color: var(--svg-color--b96201, #B96201);
}

.h97sosa1o {
  stop-color: var(--svg-color--df9728, #DF9728);
}

.ha2cq84sa {
  stop-color: var(--svg-color--c9681c, #C9681C);
}

.hhuggwz1h {
  cx: 13px;
  cy: 9.905px;
  rx: 0.404px;
  ry: 0.204px;
}

.hkh0bccgk {
  stop-color: var(--svg-color--bcebff, #BCEBFF);
}

.hkq9astav {
  stop-color: var(--svg-color--d6cbe2, #D6CBE2);
}

.hottnizrg {
  stop-color: var(--svg-color--ffd336, #FFD336);
  stop-opacity: 0;
}

.hxg13bqik {
  stop-color: var(--svg-color--b7938b, #B7938B);
}

.i-49h5vxx {
  cx: 13px;
  cy: 9.905px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.404px;
  ry: 0.204px;
}

.i2-0q3b1j {
  stop-color: var(--svg-color--f4922d, #F4922D);
  stop-opacity: 0;
}

.i4kgizoks {
  stop-color: var(--svg-color--d1bee7, #D1BEE7);
  stop-opacity: 0;
}

.i6tsuwbjp {
  width: 4.008px;
  height: 0.781px;
  x: 23.173px;
  y: 18.738px;
  rx: 0.391px;
}

.iezv8nbum {
  stop-color: var(--svg-color--fcefff, #FCEFFF);
}

.if8d5_btg {
  d: path("M13.28 9.51a.925.925 0 0 0-.892 1.17h1.788a1 1 0 0 0 .034-.245a.93.93 0 0 0-.93-.925");
}

.ifg4wbcuq {
  stop-color: var(--svg-color--e2d2ee, #E2D2EE);
  stop-opacity: 0;
}

.ilkkrkb1w {
  d: path("M14.125 10.326c0-.299-.243-.498-.309-.558l-.299.289l.184.374z");
}

.irjqokbks {
  stop-color: var(--svg-color--d7ccea, #D7CCEA);
  stop-opacity: 0;
}

.is2-rm9rl {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M20.273 11.553a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.j944t7b4y {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M10.78 11.553a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.jh40i5bvl {
  stop-color: var(--svg-color--ffda39, #FFDA39);
  stop-opacity: 0;
}

.jho7fp0ws {
  fill: var(--svg-color--8c3f23, #8C3F23);
  fill-rule: evenodd;
  d: path("m19.177 8.243l-.137.23za.268.268 0 0 1-.275.46l-.005-.003a1 1 0 0 0-.113-.058a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 1 1-.093-.528c.513-.09.988 0 1.328.11a3.3 3.3 0 0 1 .558.238l.01.005z");
}

.jr9zsmblm {
  stop-color: var(--svg-color--a4c098, #A4C098);
}

.k-hxoxbhg {
  d: path("M23.137 25.375c0-.4.325-.731.726-.731h2.391a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.39a.735.735 0 0 1 0-1.313a.735.735 0 0 1 0-1.315a.74.74 0 0 1-.406-.657");
}

.k10lreb3f {
  stop-color: var(--svg-color--d8c4c9, #D8C4C9);
  stop-opacity: 0;
}

.k4wir2bzl {
  d: path("M14.843 2.688c-1.133-.25-2.347.955-2.464 1.374c1.542 3.62 3.91 3.275 6.537 2.984c1.572-.175 1.743.542 1.877.888c-.436-4.056-3.37-4.676-5.95-5.246");
}

.kbf5deyse {
  d: path("M10.359 9.216h.012l-.01-.266l-.01-.306c.02-.949.574-1.316.81-1.438l.05-.02l.052-.021a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.05a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.087 1.135 1.332l-.118 3.073c-.124 2.803-2.312 4.684-4.984 4.684c-2.671 0-4.86-1.882-4.983-4.684z");
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.kpf8h5ohf {
  stop-color: var(--svg-color--db6009, #DB6009);
  stop-opacity: 0;
}

.kri2xabhg {
  d: path("M18.459 10.308a.87.87 0 0 0-.239-.477l-.268.294l.121.236z");
}

.krlyqhb_p {
  fill: var(--svg-color--8a004f, #8A004F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.048 13.001a.204.204 0 0 0-.248.043a.196.196 0 0 0-.02.248a1.982 1.982 0 0 0 3.333 0a.2.2 0 0 0-.022-.25a.205.205 0 0 0-.247-.041c-.404.216-.88.339-1.398.339a3 3 0 0 1-1.398-.339Z");
}

.ksjv3r0ar {
  stop-color: var(--svg-color--a4a574, #A4A574);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kua6vgb0k {
  fill: var(--svg-color--ffd335, #FFD335);
  d: path("M26.434 23.02c.56 0 1.02.46 1.02 1.02v2.34h-2.04v-2.34c.01-.56.46-1.02 1.02-1.02");
}

.l0oa60bqe {
  d: path("m15.064 10.117l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.646-.376-.766 0");
}

.l2nok66dj {
  d: path("M23.825 23.878v-.469h.805a.234.234 0 0 1 0 .47z");
}

.lcrdwk1fj {
  stop-color: var(--svg-color--c9641b, #C9641B);
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.lhcs9cc6n {
  d: path("M17.639 9.509a.92.92 0 0 1 .887 1.164h-1.78a.925.925 0 0 1 .892-1.164");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljkt_bcky {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.595 8.106c-.323-.079-1.125-.04-1.661.344");
}

.lkjzf4omc {
  stop-color: var(--svg-color--c5b2dd, #C5B2DD);
}

.lwgxwcc9p {
  stop-color: var(--svg-color--ebd4c9, #EBD4C9);
}

.m3bo30rid {
  stop-color: var(--svg-color--7f5f9e, #7F5F9E);
}

.m45oyzb-o {
  stop-color: var(--svg-color--eb9235, #EB9235);
}

.m9udaht4q {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.385 8.106c.323-.079 1.125-.04 1.661.344");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.mvrro-b_u {
  stop-color: var(--svg-color--d8bbf3, #D8BBF3);
}

.mx0dy7bzm {
  d: path("M8.226 30.05V18.26c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07z");
}

.n0zx1htzw {
  d: path("M20.273 11.553a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.n8vj2kb3y {
  stop-color: var(--svg-color--f6f4ff, #F6F4FF);
}

.nbiohly8w {
  stop-color: var(--svg-color--5a306c, #5A306C);
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.nl6m8oboo {
  d: path("M20.273 12.087a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.nria2ku7r {
  stop-color: var(--svg-color--d8772c, #D8772C);
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.o7epp0bzj {
  d: path("M17.57 9.704c.066.087-.071.194-.227.31c-.156.117-.272.2-.337.112c-.066-.088.007-.254.163-.37c.156-.117.336-.14.401-.052");
}

.o9uhuu5-x {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.852 9.228c.674 0 1.244.465 1.399 1.093a.283.283 0 0 1-.276.352H16.67a.238.238 0 0 1-.235-.28a1.44 1.44 0 0 1 1.416-1.165");
}

.oaxszm67z {
  stop-color: var(--svg-color--cb6325, #CB6325);
  stop-opacity: 0;
}

.ocku6nzyd {
  stop-color: var(--svg-color--d8bbf3, #D8BBF3);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oltxz8b0t {
  stop-color: var(--svg-color--df9e26, #DF9E26);
}

.oyvjs-x-y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.754 26.052h1.797");
}

.p1xq25bjq {
  stop-color: var(--svg-color--d76a18, #D76A18);
  stop-opacity: 0;
}

.p2mir8bpk {
  stop-color: var(--svg-color--d2b4ed, #D2B4ED);
}

.p4jiy8bvo {
  stop-color: var(--svg-color--d48028, #D48028);
}

.p4k8mjbje {
  stop-color: var(--svg-color--d3faff, #D3FAFF);
}

.p4wkjrbae {
  stop-color: var(--svg-color--c9681c, #C9681C);
  stop-opacity: 0;
}

.p9rinuedy {
  stop-color: var(--svg-color--e6ff81, #E6FF81);
  stop-opacity: 0;
}

.pb_rvfc5z {
  stop-color: var(--svg-color--ffe842, #FFE842);
}

.pclg_efwa {
  stop-color: var(--svg-color--c7aae2, #C7AAE2);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q_2usqome {
  stop-color: var(--svg-color--bca5a5, #BCA5A5);
}

.q-fl22tnr {
  stop-color: var(--svg-color--cfbce6, #CFBCE6);
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.q4mowll4q {
  stop-color: var(--svg-color--e2d2f8, #E2D2F8);
  stop-opacity: 0;
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qctpdhrvn {
  d: path("M22.753 30.05V18.26c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07z");
}

.qir_1cb0f {
  stop-color: var(--svg-color--e26b25, #E26B25);
  stop-opacity: 0;
}

.qtr_-gj2q {
  stop-color: var(--svg-color--ffc531, #FFC531);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwjswe-rp {
  stop-color: var(--svg-color--e48538, #E48538);
  stop-opacity: 0;
}

.r-0tl8b_g {
  stop-color: var(--svg-color--bfa7d3, #BFA7D3);
}

.r1tra0r1f {
  stop-color: var(--svg-color--a4c098, #A4C098);
  stop-opacity: 0;
}

.r39_kb6dq {
  d: path("m21.202 18.313l.116 1.534a.53.53 0 0 1-.437.563l-.424.075a.133.133 0 0 0-.075.22l.554.61a.44.44 0 0 1-.013.608l-4.188 4.255a.177.177 0 0 1-.303-.124v-2.992c0-.25.053-.497.155-.725l2.306-5.135c.822.264 1.599.64 2.31 1.111");
}

.r3q9_wiir {
  d: path("M19.865 16.343a10.5 10.5 0 0 1 2.878 1.917v.014l.01-.014c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07H15.98v-6.52z");
}

.r47pfjb1m {
  d: path("M10.78 11.553a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.rced3uh7f {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
  stop-opacity: 0;
}

.rfihmeb7t {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.57 9.704c.066.087-.071.194-.227.31c-.156.117-.272.2-.337.112c-.066-.088.007-.254.163-.37c.156-.117.336-.14.401-.052");
}

.rfuz_acet {
  stop-color: var(--svg-color--c3a5dc, #C3A5DC);
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.rmgd8acpv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.754 28.661h1.797");
}

.rnmqrkbhw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.676 27.357h1.797");
}

.rpwi1zcyf {
  fill: var(--svg-color--000, #000);
  d: path("M13.81 10.436a.53.53 0 0 0-.53-.53a.528.528 0 0 0-.471.774h.938a.5.5 0 0 0 .063-.244");
}

.ry-6rkb7q {
  stop-color: var(--svg-color--e6d7e3, #E6D7E3);
}

.s3t3owbgt {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
  stop-opacity: 0;
}

.s44sum5km {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
  stop-opacity: 0;
}

.sfa02aclf {
  stop-color: var(--svg-color--bcebff, #BCEBFF);
  stop-opacity: 0;
}

.sfpaimhix {
  stop-color: var(--svg-color--bdbabb, #BDBABB);
  stop-opacity: 0;
}

.su72xqoac {
  d: path("M15.466 15.41c-2.75 0-5.32 1.06-7.23 2.85v.014l-.01-.014c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h21.79l.01-2.03c.01-1.76-.25-3.51-.77-5.18c-.57-1.81-1.59-3.38-2.91-4.61a10.62 10.62 0 0 0-7.2-2.82");
}

.sufhn4bec {
  stop-color: var(--svg-color--db6009, #DB6009);
}

.sxoxd_kke {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
  stop-opacity: 0;
}

.t0qf5rbqk {
  stop-color: var(--svg-color--e6d2de, #E6D2DE);
}

.tgqxysbgm {
  stop-color: var(--svg-color--d76a18, #D76A18);
}

.tocxavgag {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m15.053 10.404l-.683 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.493-.377-.613 0");
}

.tq9nmh6wg {
  d: path("M26.434 23.02c.56 0 1.02.46 1.02 1.02v2.34h-2.04v-2.34c.01-.56.46-1.02 1.02-1.02");
}

.tqgfgwd_y {
  stop-color: var(--svg-color--ffe136, #FFE136);
}

.tsloro5fn {
  stop-color: var(--svg-color--e6ff81, #E6FF81);
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.u7id6gble {
  stop-color: var(--svg-color--ffe945, #FFE945);
}

.ubsir5m6c {
  stop-color: var(--svg-color--ccff86, #CCFF86);
}

.uc1cxyvnm {
  d: path("M18.083 6.526h-5.275c-1.497 0-2.737 1.2-2.747 2.707a2.72 2.72 0 0 0 2.717 2.717c.942 0 1.814-.486 2.3-1.22c.189-.277.533-.277.721 0a2.76 2.76 0 0 0 2.373 1.21c1.408-.05 2.598-1.269 2.618-2.677a2.71 2.71 0 0 0-2.707-2.737");
  opacity: var(--svg-opacity--0-4, 0.4);
}

.ud-bjxb5c {
  stop-color: var(--svg-color--d4993e, #D4993E);
  stop-opacity: 0;
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.ut7pv-xgw {
  stop-color: var(--svg-color--ffe132, #FFE132);
}

.v0fk_zbwr {
  stop-color: var(--svg-color--83b651, #83B651);
}

.v2k4g1b_w {
  stop-color: var(--svg-color--ffe842, #FFE842);
  stop-opacity: 0;
}

.v4-zmrbyl {
  stop-color: var(--svg-color--b0a6b5, #B0A6B5);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v61l3jbat {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
  stop-opacity: 0;
}

.v6ge5bcpf {
  stop-color: var(--svg-color--faf8fe, #FAF8FE);
}

.v7gluqbxb {
  d: path("M15.466 15.36h-.04c.1 0 .19 0 .3.01c-.09-.01-.18-.01-.26-.01");
}

.v9rq5jjti {
  stop-color: var(--svg-color--cba140, #CBA140);
  stop-opacity: 0;
}

.vj4_95wuu {
  stop-color: var(--svg-color--a15002, #A15002);
}

.vkjpfvbgu {
  stop-color: var(--svg-color--f4922d, #F4922D);
}

.vsluyubzo {
  stop-color: var(--svg-color--f8a322, #F8A322);
  stop-opacity: 0;
}

.vxd8ts5kx {
  stop-color: var(--svg-color--c4c1c3, #C4C1C3);
}

.w01lnqx9a {
  stop-color: var(--svg-color--bfa6da, #BFA6DA);
}

.w2e_edyjl {
  stop-color: var(--svg-color--f09429, #F09429);
}

.wa9cqx9pi {
  stop-color: var(--svg-color--ffe644, #FFE644);
}

.wk8vkxvjb {
  d: path("m9.255 17.87l-.13 1.734a.6.6 0 0 0 .493.636l.48.084a.15.15 0 0 1 .084.249l-.626.69a.5.5 0 0 0 .015.687l4.732 4.808a.2.2 0 0 0 .343-.14v-3.38a2 2 0 0 0-.176-.82l-2.605-5.803a10.6 10.6 0 0 0-2.61 1.256");
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.x05md6_2b {
  stop-color: var(--svg-color--d97c39, #D97C39);
}

.x3hlfcbwc {
  stop-color: var(--svg-color--bdbabb, #BDBABB);
}

.x3pdtmzbl {
  stop-color: var(--svg-color--29615d, #29615D);
}

.xazl-5b3q {
  d: path("M15.426 18.68a2.11 2.11 0 0 1-2.11-2.11v-1.39h4.22v1.39c0 1.17-.95 2.11-2.11 2.11");
}

.xoi7hsb-w {
  stop-color: var(--svg-color--ddcef1, #DDCEF1);
}

.xu2szrbjd {
  d: path("M11.114 16.343a10.5 10.5 0 0 0-2.878 1.917v.014l-.01-.014c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h10.453v-6.52z");
}

.xx10debny {
  stop-color: var(--svg-color--c0a9d9, #C0A9D9);
  stop-opacity: 0;
}

.xyeqa6bqm {
  fill: var(--svg-color--000, #000);
  d: path("M17.11 10.43c0-.293.235-.528.529-.528a.526.526 0 0 1 .469.77h-.934a.5.5 0 0 1-.063-.242");
}

.xzc44cc_j {
  fill-rule: evenodd;
  d: path("M22.631 11.888c.213-.435.324-.92.324-1.427c0-.467-.096-.906-.269-1.305h.006a3 3 0 0 0-.282-.513l-.002-.003a3.24 3.24 0 0 1-.526-1.771v-.01a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.232a3.3 3.3 0 0 0-2.682-1.377a3.3 3.3 0 0 0-2.682 1.377a.56.56 0 0 1-.455.232l-.085.001a3.3 3.3 0 0 0-3.215 3.298v.01a3.24 3.24 0 0 1-.526 1.772l-.002.003a3.3 3.3 0 0 0-.22 3.245c.07.142.07.314 0 .456a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 3.218-3.219c0-.506-.121-.982-.324-1.406a.51.51 0 0 1 0-.456m-12.26-2.672h-.012l1.198 2.355c.124 2.803 1.217 0 3.889 0s3.836 3.12 3.96.317l1.135-3.197c-.053-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.189-1.674a.264.264 0 0 0-.461.051l-.082.194a2.3 2.3 0 0 1-1.292 1.276c-.236.122-.79.49-.81 1.438l.01.306z");
}

.y5gxirbqq {
  stop-color: var(--svg-color--fffbff, #FFFBFF);
}

.y7n0ymbzx {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
  stop-opacity: 0;
}

.yd98qowkb {
  d: path("m15.064 10.266l-.532 1.7a.54.54 0 0 0 .52.699h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.646-.376-.766 0");
}

.ydn9dmb6d {
  stop-color: var(--svg-color--ffe945, #FFE945);
  stop-opacity: 0;
}

.yehxt3bls {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
}

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.yqk-2gbyp {
  stop-color: var(--svg-color--cb6325, #CB6325);
}

.yr1vjkbzu {
  stop-color: var(--svg-color--ffd93c, #FFD93C);
}

.yzv5f8bpf {
  stop-color: var(--svg-color--e69b19, #E69B19);
}

.z_a2ribdx {
  stop-color: var(--svg-color--e7d3df, #E7D3DF);
  stop-opacity: 0;
}

.z-gb6n28y {
  stop-color: var(--svg-color--e4883f, #E4883F);
  stop-opacity: 0;
}

.z-gx2rb2w {
  stop-color: var(--svg-color--ffe337, #FFE337);
}

.z0b4bspnd {
  d: path("M10.76 12.087a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.z4xhuybyb {
  stop-color: var(--svg-color--c8c2cc, #C8C2CC);
}

.z78o0obou {
  stop-color: var(--svg-color--c6a5e0, #C6A5E0);
}

.zehc2bc2m {
  d: path("m9.608 17.174l-.13 1.733a.6.6 0 0 0 .493.636l.48.085a.15.15 0 0 1 .084.248l-.626.691a.5.5 0 0 0 .015.687l4.732 4.807a.2.2 0 0 0 .343-.14v-3.38c0-.282-.06-.562-.176-.82l-2.605-5.803c-.93.299-1.807.723-2.61 1.256");
}

.zh9_ydbxc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.555 3.936c.023.243.234 1.157.544 1.71");
}

.zpmhxsbxd {
  stop-color: var(--svg-color--c7aae2, #C7AAE2);
  stop-opacity: 0;
}

.ztn-0pg6n {
  d: path("m21.37 17.174l.132 1.733a.6.6 0 0 1-.494.636l-.48.085a.15.15 0 0 0-.085.248l.626.691a.5.5 0 0 1-.014.687l-4.732 4.807a.2.2 0 0 1-.343-.14v-3.38c0-.282.06-.562.175-.82l2.606-5.803c.929.299 1.807.723 2.61 1.256");
}

</style>
