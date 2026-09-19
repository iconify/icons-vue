<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iK0N1Ub)" class="yrheztpeb"/><path fill="url(#iPtlIfc)" class="yrheztpeb"/><path fill="url(#igIOdBb)" class="yrheztpeb"/><path fill="url(#i7CRo2d)" class="yrheztpeb"/><path fill="url(#iXjonqb)" class="yrheztpeb"/><path fill="url(#ipvGGZd)" class="sj496hbeg"/><path fill="url(#iwf7gKb)" class="sj496hbeg"/><g filter="url(#iTV7scd)"><path fill="url(#idKwAsM)" class="aktim7bzc"/><path fill="url(#iw5xaKd)" class="aktim7bzc"/></g><path fill="url(#iAUO7De)" class="n4sjjrd5b"/><g filter="url(#iGV3S8C)"><path fill="url(#iaPBeIc)" class="nz1k2j0va"/><path fill="url(#iEj8stc)" class="nz1k2j0va"/></g><g filter="url(#i18Umwd)"><path clip-rule="evenodd" class="qqr07gk3o"/></g><path fill="url(#iYqxBof)" class="x9c83rbtu"/><path fill="url(#ig0Xh7b)" class="x9c83rbtu"/><path fill="url(#iNWFHPd)" class="x9c83rbtu"/><path fill="url(#iScStQb)" class="x9c83rbtu"/><path fill="url(#iqiqfjb)" class="cmnkd-u4q"/><path fill="url(#iWXbFle)" class="cmnkd-u4q"/><path fill="url(#ioVHjMb)" class="cmnkd-u4q"/><path fill="url(#iN1ACtc)" class="cmnkd-u4q"/><g filter="url(#iG5nHZm)"><path fill="url(#i7spMHe)" class="rcq40k3oj"/></g><g filter="url(#ioA5VEe)"><path fill="url(#iObt8Gc)" class="u8204ccps"/></g><path fill="url(#inrUbuc)" class="u8204ccps"/><path fill="url(#iPcQn6J)" class="u8204ccps"/><path fill="url(#ibfV5bb)" class="u8204ccps"/><g filter="url(#iP6PZnU)"><path class="cib_mgb2a"/></g><g filter="url(#icaNAEc)"><circle class="fy-f35ojw"/></g><g filter="url(#iggp3kd)"><circle class="rf-z3i_lt"/></g><g filter="url(#if62Ird)"><circle fill="url(#idvGSzc)" class="slnti_bde"/></g><g filter="url(#i0oBE2c)"><circle fill="url(#iKhgvsc)" class="c063rrbqb"/></g><rect fill="url(#i4ZvwCc)" class="lerr-nbox"/><rect fill="url(#isegrMb)" class="lerr-nbox"/><rect fill="url(#ieojLbc)" class="lerr-nbox"/><rect fill="url(#iY64nGh)" class="lerr-nbox"/><g filter="url(#ijDkvAd)"><path fill="url(#i7lfzIe)" class="aaydc9imt"/></g><path fill="url(#iJlbAGe)" class="aaydc9imt"/><g filter="url(#iNImNCc)"><path class="f_6c2ebcs"/><path fill="url(#iHT8cte)" class="pk74vjldd"/><path fill="url(#iCh2NGd)" class="pk74vjldd"/><path fill="url(#iOZTY0b)" class="pk74vjldd"/></g><g filter="url(#ioAYJkc)"><circle fill="url(#i4Acd0c)" class="rruryhx1n"/><circle fill="url(#iAsT4et)" class="rruryhx1n"/></g><g filter="url(#idf7BIb)"><circle fill="url(#iwCW2zc)" class="sjjnmvbyf"/></g><g filter="url(#iTWgZrc)"><circle fill="url(#iOPhbqS)" class="mw2n2tb6u"/></g><g filter="url(#i1THPme)"><circle fill="url(#iqJCv9c)" class="mblwe85jo"/><circle fill="url(#i31yAhd)" class="mblwe85jo"/></g><g filter="url(#iTbW7Ce)"><circle class="xm2fj02xh"/><circle fill="url(#i77G0db)" class="xtmoiyb-u"/><circle fill="url(#ivpSc1O)" class="xtmoiyb-u"/></g><g filter="url(#ibF2mid)"><path fill="url(#iNPKf4d)" class="xcscp1tzt"/><path fill="url(#i1j0ipR)" class="xcscp1tzt"/><path fill="url(#iW09jgK)" class="xcscp1tzt"/><path fill="url(#idpTZRb)" class="xcscp1tzt"/><path fill="url(#iUX1Eqe)" class="xcscp1tzt"/><path fill="url(#iQiIfvU)" class="xcscp1tzt"/><path fill="url(#iSDM68I)" class="xcscp1tzt"/></g><g filter="url(#ivv3Feb)"><path fill="url(#iu4tMAb)" class="wwvh45cwh"/></g><g filter="url(#iZdkNIb)"><path class="o1-cy92hg"/><path fill="url(#isjFUdc)" class="fmbkj2bpw"/><path fill="url(#iNUivuc)" class="fmbkj2bpw"/><path fill="url(#i3bO3Mc)" class="fmbkj2bpw"/><path fill="url(#iWOZ7hc)" class="fmbkj2bpw"/></g><g filter="url(#iqU4iKa)"><path class="kqi736dpe"/></g><g filter="url(#iHrokAe)"><path class="zky6sqbmn"/><path fill="url(#iWZPDVb)" class="k857wacxl"/><path fill="url(#ixJZBTd)" class="k857wacxl"/><path fill="url(#iRU57QB)" class="k857wacxl"/><path fill="url(#im54CEe)" class="k857wacxl"/></g><g filter="url(#iWZCaOQ)"><path fill="url(#iNYVinc)" class="piwka_buo"/></g><g filter="url(#izy02ue)"><path stroke="url(#iIstlQd)" class="ny8l490vt"/></g><path class="on2ulqbxu"/><g filter="url(#idXZzUc)"><path class="ac15mvbzg"/></g><g filter="url(#iePKTYb)"><path class="v5rdj9bnx"/></g><path class="lerx3rbyx"/><path fill="url(#ikFV7fc)" class="jaluor4-o"/><path class="zj8enfb0n"/><g filter="url(#itVkVQd)"><path class="omxrzvbxf"/><path fill="url(#iE5Lhcc)" class="zf-wx0bhd"/></g><g filter="url(#ifopmAe)"><path fill="url(#iCl2ifd)" class="pmbgiihyf"/></g><path class="vdevotgbu"/><path fill="url(#i43fTQb)" class="y-8wpsx8z"/><path class="dx7wurgst"/><g filter="url(#icK2yWd)"><path fill="url(#ig6H4Kj)" class="te0w8o76f"/></g><g filter="url(#i6rTqDd)"><ellipse transform="rotate(-27.914 13.54 9.851)" class="abggz0bru"/><ellipse fill="url(#ijCbDFb)" transform="rotate(-27.914 13.54 9.851)" class="exsd84beq"/></g><g filter="url(#iE0oKCd)"><path stroke="url(#iJowtkd)" class="yd68gzbbi"/></g><g filter="url(#iRlicxd)"><path stroke="url(#iiIDvMd)" class="zvesnxp2v"/></g><g filter="url(#i2IKBBe)"><path stroke="url(#imcS9He)" class="c1zjcqb7j"/></g><defs><radialGradient id="iK0N1Ub" cx="0" cy="0" r="1" gradientTransform="matrix(-10.875 0 0 -9.21464 22.408 25.375)" gradientUnits="userSpaceOnUse"><stop class="rp3tqelhu"/><stop offset="1" class="nwb1x8bnq"/></radialGradient><radialGradient id="iPtlIfc" cx="0" cy="0" r="1" gradientTransform="rotate(133.011 2.756 10.842)scale(6.32206 7.4475)" gradientUnits="userSpaceOnUse"><stop class="cosmi4y3y"/><stop offset="1" class="fs5qncc9z"/></radialGradient><radialGradient id="igIOdBb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.5 0 0 -14.0625 23.19 23.285)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="b_mjjkbmw"/><stop offset="1" class="tg6m8fb0a"/></radialGradient><radialGradient id="ipvGGZd" cx="0" cy="0" r="1" gradientTransform="rotate(-91.369 27.27 2.64)scale(11.2456 1.27919)" gradientUnits="userSpaceOnUse"><stop offset=".008" class="uc5leibtb"/><stop offset="1" class="j8ireobfm"/><stop offset="1" class="hj096sb7e"/></radialGradient><radialGradient id="iwf7gKb" cx="0" cy="0" r="1" gradientTransform="matrix(.5755 0 0 15.6193 23.099 28.186)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="n_pmxxxsa"/><stop offset="1" class="a_orf89wt"/></radialGradient><radialGradient id="idKwAsM" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.9375 4 0 6.69 30.441)" gradientUnits="userSpaceOnUse"><stop class="cm2l5-bra"/><stop offset="1" class="z_d2yzmmm"/></radialGradient><radialGradient id="iAUO7De" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55519 1.9364 -1.64284 -1.31942 8.901 18.598)" gradientUnits="userSpaceOnUse"><stop class="aba3uxblf"/><stop offset="1" class="bbv_pqbfl"/></radialGradient><radialGradient id="iaPBeIc" cx="0" cy="0" r="1" gradientTransform="matrix(-.03127 9.1875 -4.7805 -.01627 17.096 22.566)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="geqh5zowk"/><stop offset="1" class="u21vfmbcf"/></radialGradient><radialGradient id="iEj8stc" cx="0" cy="0" r="1" gradientTransform="rotate(116.36 1.33 13.054)scale(5.4245 1.91221)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="lf_z1-eut"/><stop offset="1" class="safapbcnd"/></radialGradient><radialGradient id="ig0Xh7b" cx="0" cy="0" r="1" gradientTransform="rotate(-152.488 10.111 8.386)scale(1.16274 3.57827)" gradientUnits="userSpaceOnUse"><stop class="ff2asxc8d"/><stop offset="1" class="c5vb29odw"/></radialGradient><radialGradient id="iNWFHPd" cx="0" cy="0" r="1" gradientTransform="matrix(.79687 -.22754 .55824 1.95507 13.236 18.707)" gradientUnits="userSpaceOnUse"><stop class="vdt_t3f2x"/><stop offset="1" class="v0ftcskkn"/></radialGradient><radialGradient id="iWXbFle" cx="0" cy="0" r="1" gradientTransform="matrix(1.39062 .34376 -1.28105 5.18228 17.174 18.801)" gradientUnits="userSpaceOnUse"><stop offset=".616" class="fojlwlb9t"/><stop offset="1" class="cyzx27bkq"/></radialGradient><radialGradient id="ioVHjMb" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 .35156 -1.56152 -1.21452 17.276 19.442)" gradientUnits="userSpaceOnUse"><stop class="ojp787kql"/><stop offset="1" class="zhh5xs6ht"/></radialGradient><radialGradient id="iObt8Gc" cx="0" cy="0" r="1" gradientTransform="rotate(172.755 6.073 11.885)scale(1.9846 6.9682)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="z58nq_enb"/><stop offset="1" class="v5ndbpbdn"/></radialGradient><radialGradient id="inrUbuc" cx="0" cy="0" r="1" gradientTransform="matrix(-.91838 1.78314 -4.30906 -2.21931 13.135 16.323)" gradientUnits="userSpaceOnUse"><stop class="ubq14mb-s"/><stop offset="1" class="q0kampb0a"/></radialGradient><radialGradient id="iPcQn6J" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.94239 -.4885 0 11.747 16.38)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="ihl9krbbc"/><stop offset="1" class="vjj8ifxqk"/></radialGradient><radialGradient id="ibfV5bb" cx="0" cy="0" r="1" gradientTransform="matrix(.0919 1.7035 -.36222 .01954 10.658 20.675)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="jfikb2f0k"/><stop offset="1" class="k5y7j_bmf"/></radialGradient><radialGradient id="idvGSzc" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 2.862 16.073)scale(.5552)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="iKhgvsc" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 3.481 14.57)scale(.5552)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="isegrMb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.26562 -2.59161 0 16.012 16.884)" gradientUnits="userSpaceOnUse"><stop offset=".209" class="zj5z5alkp"/><stop offset="1" class="ygunkzbtc"/></radialGradient><radialGradient id="ieojLbc" cx="0" cy="0" r="1" gradientTransform="matrix(1.375 -1.22153 .56328 .63405 16.697 18.84)" gradientUnits="userSpaceOnUse"><stop class="h_57ad8xy"/><stop offset="1" class="j8f_3yy_n"/></radialGradient><radialGradient id="iY64nGh" cx="0" cy="0" r="1" gradientTransform="matrix(-1.4375 -1.32812 .29393 -.31814 15.353 18.603)" gradientUnits="userSpaceOnUse"><stop class="iowat_b5w"/><stop offset="1" class="gd8vhtnni"/></radialGradient><radialGradient id="i7lfzIe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.39331 0 0 -1.18711 18.294 18.79)" gradientUnits="userSpaceOnUse"><stop class="udzp2zp0e"/><stop offset="1" class="mgsb3vbjk"/></radialGradient><radialGradient id="iJlbAGe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.92504 -.35938 0 18.143 18.164)" gradientUnits="userSpaceOnUse"><stop class="tayze7bgq"/><stop offset="1" class="s41karbfc"/></radialGradient><radialGradient id="iCh2NGd" cx="0" cy="0" r="1" gradientTransform="rotate(-144.958 10.448 6.884)scale(1.79393 .6786)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="i8gd1zbwo"/><stop offset="1" class="fj3b0ib3x"/></radialGradient><radialGradient id="iOZTY0b" cx="0" cy="0" r="1" gradientTransform="matrix(-.73438 0 0 -1.53003 15.424 19.02)" gradientUnits="userSpaceOnUse"><stop class="p5lz4ubjd"/><stop offset="1" class="tyszy7o8n"/></radialGradient><radialGradient id="i4Acd0c" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 4.363 12.613)scale(.89786)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="iAsT4et" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 -1.4336 1.50732 -.5257 16.174 19.38)" gradientUnits="userSpaceOnUse"><stop offset=".741" class="yl8zw5b_j"/><stop offset="1" class="dh4f0mlhm"/></radialGradient><radialGradient id="iwCW2zc" cx="0" cy="0" r="1" gradientTransform="matrix(1.75471 0 0 3.07077 9.579 10.629)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="i31yAhd" cx="0" cy="0" r="1" gradientTransform="matrix(.82663 -.60192 .68701 .9435 21.133 10.364)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="i77G0db" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 20.72 11.45)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="ivpSc1O" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 -2.544 30.557)scale(.3648 .47028)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="i1j0ipR" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.74023 -11.8644 0 16.024 8.704)" gradientUnits="userSpaceOnUse"><stop offset=".635" class="zz6iedcfy"/><stop offset="1" class="h0sio1r1e"/></radialGradient><radialGradient id="iUX1Eqe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60858 0 18.342 9.358)" gradientUnits="userSpaceOnUse"><stop class="m459pab_j"/><stop offset="1" class="rcuz4uefu"/></radialGradient><radialGradient id="iQiIfvU" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39075 1.72952 0 13.784 9.324)" gradientUnits="userSpaceOnUse"><stop class="hplqxft1w"/><stop offset="1" class="ay1rn8bxh"/></radialGradient><radialGradient id="isjFUdc" cx="0" cy="0" r="1" gradientTransform="matrix(.79775 -2.95637 1.09632 .29583 20.34 6.523)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="iNUivuc" cx="0" cy="0" r="1" gradientTransform="rotate(5.258 -42.523 205.995)scale(3.84067 2.0651)" gradientUnits="userSpaceOnUse"><stop offset=".335" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="i3bO3Mc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.67903 -2.60035 0 15.996 2.029)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iWOZ7hc" cx="0" cy="0" r="1" gradientTransform="matrix(3.07368 -2.25248 3.5289 4.81545 9.547 8.846)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="im54CEe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19688 -.63254 0 16.323 12.236)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="ikFV7fc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81106 -1.29009 0 18.174 9.947)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iE5Lhcc" cx="0" cy="0" r="1" gradientTransform="matrix(-.23184 -.29876 .41132 -.3192 17.946 10.032)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i43fTQb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8111 -1.29015 0 13.812 9.947)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ijCbDFb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.767 -1.574)scale(.49399 .59379)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iTV7scd" width="4.081" height="11.683" x="5.07" y="18.288" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.345098 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3337"/></filter><filter id="iGV3S8C" width="5.909" height="14.117" x="12.858" y="15.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.431373 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3337"/></filter><filter id="i18Umwd" width="7.13" height="5.229" x="12.285" y="16.14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3337" stdDeviation=".3"/></filter><filter id="iG5nHZm" width="7.239" height="14.645" x="9.195" y="15.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3337" stdDeviation=".5"/></filter><filter id="ioA5VEe" width="5.917" height="14.31" x="10.326" y="15.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.113725 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3337"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.113725 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3337" result="effect2_innerShadow_4002_3337"/></filter><filter id="iP6PZnU" width="6.504" height="14.261" x="15.345" y="15.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.372549 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3337"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0901961 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3337" result="effect2_innerShadow_4002_3337"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0901961 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_3337" result="effect3_innerShadow_4002_3337"/></filter><filter id="icaNAEc" width="2" height="2" x="14.731" y="24.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3337" stdDeviation=".25"/></filter><filter id="iggp3kd" width="2" height="2" x="14.731" y="21.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3337" stdDeviation=".25"/></filter><filter id="if62Ird" width="1.05" height="1.05" x="15.504" y="25.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3337"/></filter><filter id="i0oBE2c" width="1.05" height="1.05" x="15.504" y="22.076" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3337"/></filter><filter id="ijDkvAd" width="2.465" height="2.95" x="16.029" y="17.39" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.164706 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3337"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.145098 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3337" result="effect2_innerShadow_4002_3337"/></filter><filter id="iNImNCc" width="2.365" height="2.9" x="13.731" y="17.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3337"/></filter><filter id="ioAYJkc" width="1.717" height="1.717" x="15.204" y="17.846" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3337"/></filter><filter id="idf7BIb" width="3.539" height="3.339" x="9.579" y="8.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3337"/></filter><filter id="iTWgZrc" width="2.99" height="2.99" x="9.753" y="9.135" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3337" stdDeviation=".25"/></filter><filter id="i1THPme" width="3.589" height="3.589" x="19.091" y="8.71" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3337"/></filter><filter id="iTbW7Ce" width="2.99" height="2.99" x="19.266" y="9.135" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3337" stdDeviation=".25"/></filter><filter id="ibF2mid" width="10.373" height="12.277" x="10.838" y="5.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3337"/></filter><filter id="ivv3Feb" width="8.246" height="7.066" x="14.165" y="3.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3337" stdDeviation="1"/></filter><filter id="iZdkNIb" width="12.601" height="8.543" x="9.695" y="1.529" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3337"/></filter><filter id="iqU4iKa" width="3.26" height="4.181" x="14.127" y="9.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3337" stdDeviation=".375"/></filter><filter id="iHrokAe" width="2.377" height="3.181" x="14.807" y="9.812" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3337" stdDeviation=".125"/></filter><filter id="iWZCaOQ" width="2.377" height="3.181" x="14.807" y="9.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3337" stdDeviation=".125"/></filter><filter id="izy02ue" width="3.617" height="1.472" x="14.187" y="13.213" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3337" stdDeviation=".05"/></filter><filter id="idXZzUc" width="2.979" height="1.873" x="17.178" y="6.981" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3337"/></filter><filter id="iePKTYb" width="2.98" height="1.873" x="12.03" y="6.981" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3337"/></filter><filter id="itVkVQd" width=".787" height=".696" x="17.44" y="9.508" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3337" stdDeviation=".05"/></filter><filter id="ifopmAe" width=".891" height=".913" x="18.28" y="9.582" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3337" stdDeviation=".1"/></filter><filter id="icK2yWd" width=".986" height="1.04" x="13.839" y="9.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3337" stdDeviation=".1"/></filter><filter id="i6rTqDd" width=".913" height=".704" x="13.084" y="9.499" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3337" stdDeviation=".05"/></filter><filter id="iE0oKCd" width="3.099" height="1.681" x="17.031" y="7.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3337" stdDeviation=".25"/></filter><filter id="iRlicxd" width="3.177" height="1.738" x="11.812" y="7.17" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3337" stdDeviation=".25"/></filter><filter id="i2IKBBe" width="1.008" height="2.269" x="10.83" y="5.443" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3337" stdDeviation=".125"/></filter><linearGradient id="i7CRo2d" x1="23.131" x2="22.971" y1="29.965" y2="29.965" gradientUnits="userSpaceOnUse"><stop class="xg711ab6m"/><stop offset="1" class="eets9_b_s"/></linearGradient><linearGradient id="iXjonqb" x1="8.858" x2="9.061" y1="29.965" y2="29.965" gradientUnits="userSpaceOnUse"><stop class="az-h38bei"/><stop offset="1" class="fajspub8c"/></linearGradient><linearGradient id="iw5xaKd" x1="9.19" x2="7.596" y1="29.971" y2="29.971" gradientUnits="userSpaceOnUse"><stop class="t1dt_ab6m"/><stop offset="1" class="a519fg_-g"/></linearGradient><linearGradient id="iYqxBof" x1="14.705" x2="13.268" y1="20.035" y2="16.91" gradientUnits="userSpaceOnUse"><stop class="z7qr8pb7n"/><stop offset="1" class="zynu2nm7a"/></linearGradient><linearGradient id="iScStQb" x1="15.518" x2="15.209" y1="20.113" y2="19.996" gradientUnits="userSpaceOnUse"><stop class="x1yfsqmdm"/><stop offset="1" class="kqc3y0bzc"/></linearGradient><linearGradient id="iqiqfjb" x1="16.799" x2="18.471" y1="20.051" y2="17.176" gradientUnits="userSpaceOnUse"><stop class="d4kfw7asd"/><stop offset="1" class="ig120dbzq"/></linearGradient><linearGradient id="iN1ACtc" x1="16.486" x2="16.713" y1="19.852" y2="19.762" gradientUnits="userSpaceOnUse"><stop class="cof-_sb7w"/><stop offset="1" class="vo3um_bur"/></linearGradient><linearGradient id="i7spMHe" x1="12.815" x2="12.815" y1="16.832" y2="29.477" gradientUnits="userSpaceOnUse"><stop class="wm85g1cnx"/><stop offset="1" class="b0z0paczy"/></linearGradient><linearGradient id="i4ZvwCc" x1="17.033" x2="14.384" y1="18.442" y2="18.572" gradientUnits="userSpaceOnUse"><stop class="razk2i29v"/><stop offset="1" class="xu6qifbqx"/></linearGradient><linearGradient id="iHT8cte" x1="15.205" x2="14.838" y1="19.488" y2="19.035" gradientUnits="userSpaceOnUse"><stop class="p5lz4ubjd"/><stop offset="1" class="tyszy7o8n"/></linearGradient><linearGradient id="iOPhbqS" x1="11.248" x2="10.607" y1="10.908" y2="10.908" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="iqJCv9c" x1="21.847" x2="21.028" y1="9.538" y2="12.074" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="iNPKf4d" x1="20.031" x2="12.395" y1="11.019" y2="12.156" gradientUnits="userSpaceOnUse"><stop class="z8y6fgvmn"/><stop offset="1" class="tqgh1edwg"/></linearGradient><linearGradient id="iW09jgK" x1="10.354" x2="13.712" y1="12.546" y2="12.66" gradientUnits="userSpaceOnUse"><stop class="z3n_1mwef"/><stop offset="1" class="rvf3-0bfj"/></linearGradient><linearGradient id="idpTZRb" x1="10.6" x2="12.482" y1="13.714" y2="13.647" gradientUnits="userSpaceOnUse"><stop class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="iSDM68I" x1="16.024" x2="16.024" y1="17.444" y2="16.757" gradientUnits="userSpaceOnUse"><stop class="lvr4qibrk"/><stop offset="1" class="gon8nac-i"/></linearGradient><linearGradient id="iu4tMAb" x1="15.464" x2="23.607" y1="8.034" y2="5.118" gradientUnits="userSpaceOnUse"><stop class="sbbw_6vcc"/><stop offset="1" class="b7cutjkii"/></linearGradient><linearGradient id="iWZPDVb" x1="15.132" x2="16.07" y1="11.678" y2="11.678" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="ixJZBTd" x1="16.934" x2="15.909" y1="12.001" y2="11.986" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="iRU57QB" x1="16.19" x2="16.19" y1="12.743" y2="12.17" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="iNYVinc" x1="15.996" x2="15.996" y1="9.852" y2="10.946" gradientUnits="userSpaceOnUse"><stop class="zgwb37bzk"/><stop offset="1" class="vr98_ac0a"/></linearGradient><linearGradient id="iIstlQd" x1="14.959" x2="15.393" y1="14.357" y2="13.67" gradientUnits="userSpaceOnUse"><stop class="k8t65cc0e"/><stop offset=".663" class="kt86gzb_v"/></linearGradient><linearGradient id="iCl2ifd" x1="18.952" x2="18.638" y1="10.001" y2="10.194" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ig6H4Kj" x1="14.555" x2="14.242" y1="10.001" y2="10.194" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iJowtkd" x1="18.968" x2="18.547" y1="7.862" y2="7.003" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iiIDvMd" x1="13.664" x2="12.475" y1="7.734" y2="7.235" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="imcS9He" x1="11.334" x2="11.334" y1="5.719" y2="7.876" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-in-tuxedo-light" /></template>
<style>
.a_orf89wt {
  stop-color: var(--svg-color--4f3b7b, #4F3B7B);
  stop-opacity: 0;
}

.a519fg_-g {
  stop-color: var(--svg-color--463766, #463766);
  stop-opacity: 0;
}

.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.aaydc9imt {
  d: path("m17.892 17.534l-1.813 1.251l1.795 1.259a.246.246 0 0 0 .388-.188c.041-.79.041-1.569.008-2.143a.239.239 0 0 0-.378-.179");
}

.aba3uxblf {
  stop-color: var(--svg-color--4e475c, #4E475C);
}

.abggz0bru {
  cx: 13.54px;
  cy: 9.851px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.ac15mvbzg {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m19.715 7.91l-.001-.002l-.002-.001l-.005-.004l-.012-.01a1.4 1.4 0 0 0-.154-.107c-.1-.062-.241-.14-.42-.21a2.83 2.83 0 0 0-1.493-.159a.534.534 0 0 0 .167 1.055c.397-.063.716.01.933.096a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .679-.824");
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.aktim7bzc {
  d: path("M8.901 18.288a10.69 10.69 0 0 0-3.831 8.186v3.497H8.9z");
}

.ay1rn8bxh {
  stop-color: var(--svg-color--d0958d, #D0958D);
  stop-opacity: 0;
}

.az-h38bei {
  stop-color: var(--svg-color--4b3973, #4B3973);
}

.b_mjjkbmw {
  stop-color: var(--svg-color--8179b0, #8179B0);
}

.b0z0paczy {
  stop-color: var(--svg-color--4f3a77, #4F3A77);
}

.b7cutjkii {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
  stop-opacity: 0;
}

.bbv_pqbfl {
  stop-color: var(--svg-color--4e475c, #4E475C);
  stop-opacity: 0;
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

.c063rrbqb {
  cx: 16.004px;
  cy: 22.626px;
  r: 0.5px;
}

.c1zjcqb7j {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.463 5.818v.898c-.008.148-.07.48-.258.621");
}

.c5vb29odw {
  stop-color: var(--svg-color--e0c6f9, #E0C6F9);
  stop-opacity: 0;
}

.cib_mgb2a {
  fill: var(--svg-color--443452, #443452);
  d: path("M20.316 17.602c.031-1.094-.595-1.537-.887-1.626l-.668-.07v5.815c0 3.874-1.388 6.264-2.648 8.09c-.062.09.047.2.139.138c2.976-2.036 4.851-4.005 5.196-9.228a.203.203 0 0 0-.188-.215c-.321-.02-.607-.047-.809-.066a.204.204 0 0 1-.185-.206c.011-.575.022-1.659.05-2.632");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cm2l5-bra {
  stop-color: var(--svg-color--554181, #554181);
}

.cmnkd-u4q {
  d: path("M17.598 20.336c1.186-1.235 1.404-3.046 1.367-3.87h-2.968l-.036 2.222l.774 1.52c.148.308.608.394.863.128");
}

.cof-_sb7w {
  stop-color: var(--svg-color--a487bb, #A487BB);
}

.cosmi4y3y {
  stop-color: var(--svg-color--4d3b5d, #4D3B5D);
}

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.cyzx27bkq {
  stop-color: var(--svg-color--978394, #978394);
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.d4kfw7asd {
  stop-color: var(--svg-color--dabff4, #DABFF4);
}

.dh4f0mlhm {
  stop-color: var(--svg-color--592f4f, #592F4F);
}

.dx7wurgst {
  fill: var(--svg-color--000, #000);
  d: path("M14.32 10.363a.51.51 0 0 0-.51-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.eets9_b_s {
  stop-color: var(--svg-color--4e377f, #4E377F);
  stop-opacity: 0;
}

.exsd84beq {
  cx: 13.54px;
  cy: 9.851px;
  rx: 0.389px;
  ry: 0.197px;
}

.f_6c2ebcs {
  fill: var(--svg-color--543b70, #543B70);
  d: path("m14.133 17.534l1.813 1.251l-1.795 1.259a.246.246 0 0 1-.389-.188c-.04-.79-.04-1.569-.007-2.143a.239.239 0 0 1 .378-.179");
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.fajspub8c {
  stop-color: var(--svg-color--4b3973, #4B3973);
  stop-opacity: 0;
}

.ff2asxc8d {
  stop-color: var(--svg-color--e0c6f9, #E0C6F9);
}

.fj3b0ib3x {
  stop-color: var(--svg-color--564561, #564561);
  stop-opacity: 0;
}

.fmbkj2bpw {
  d: path("m20.814 4.152l.43.213c.75.373 1.18 1.227 1.018 2.133l-.59 3.04c-.052.314-.26.525-.572.533h-.018s.054-.906.107-1.44c.044-.433-.032-.565-.429-.96c-.214-.213-.375-.533-.375-.853v-.853c0-.267-.215-.48-.43-.533c-.643-.16-1.984-.427-3.914-.427s-3.272.267-3.916.427a.52.52 0 0 0-.429.533v.853c0 .32-.107.64-.375.854l-.161.16c-.215.16-.322.48-.322.746c.054.587.107 1.44.107 1.44l-.049-.002a.63.63 0 0 1-.594-.531l-.59-3.04c-.108-.853.321-1.707 1.072-2.08l.43-.213c.268-.16.536-.373.804-.587l.965-1.013c.59-.533 1.448-.693 2.2-.32a2.94 2.94 0 0 0 1.662 0c.805-.267 1.716-.053 2.36.533l.805.8c.214.267.482.427.804.587");
}

.fojlwlb9t {
  stop-color: var(--svg-color--dfc6d4, #DFC6D4);
  stop-opacity: 0;
}

.fs5qncc9z {
  stop-color: var(--svg-color--4d3b5d, #4D3B5D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.fy-f35ojw {
  cx: 15.731px;
  cy: 25.907px;
  r: 0.5px;
  fill: var(--svg-color--c5a9df, #C5A9DF);
}

.gd8vhtnni {
  stop-color: var(--svg-color--a16d62, #A16D62);
  stop-opacity: 0;
}

.geqh5zowk {
  stop-color: var(--svg-color--e8d4fa, #E8D4FA);
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gon8nac-i {
  stop-color: var(--svg-color--a77178, #A77178);
  stop-opacity: 0;
}

.h_57ad8xy {
  stop-color: var(--svg-color--af7b6e, #AF7B6E);
}

.h0sio1r1e {
  stop-color: var(--svg-color--b27b82, #B27B82);
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.hj096sb7e {
  stop-color: var(--svg-color--6b628b, #6B628B);
}

.hmo3unbrx {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
}

.hplqxft1w {
  stop-color: var(--svg-color--d0958d, #D0958D);
}

.i8gd1zbwo {
  stop-color: var(--svg-color--564561, #564561);
}

.ig120dbzq {
  stop-color: var(--svg-color--aea5b6, #AEA5B6);
}

.ihl9krbbc {
  stop-color: var(--svg-color--5e5962, #5E5962);
}

.iowat_b5w {
  stop-color: var(--svg-color--a16d62, #A16D62);
}

.j8f_3yy_n {
  stop-color: var(--svg-color--af7b6e, #AF7B6E);
  stop-opacity: 0;
}

.j8ireobfm {
  stop-color: var(--svg-color--72659b, #72659B);
}

.jaluor4-o {
  d: path("M18.176 9.47a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.127");
}

.jfikb2f0k {
  stop-color: var(--svg-color--48414f, #48414F);
}

.k5y7j_bmf {
  stop-color: var(--svg-color--48414f, #48414F);
  stop-opacity: 0;
}

.k857wacxl {
  d: path("m15.614 10.344l-.532 1.7a.54.54 0 0 0 .52.699h.787a.54.54 0 0 0 .52-.7l-.531-1.699c-.114-.376-.645-.376-.764 0");
}

.k8t65cc0e {
  stop-color: var(--svg-color--f6c0b0, #F6C0B0);
}

.kqc3y0bzc {
  stop-color: var(--svg-color--ccb1e3, #CCB1E3);
  stop-opacity: 0;
}

.kqi736dpe {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m15.72 10.507l-.82 1.7c-.102.35.142.699.488.699h.737c.346 0 .59-.355.488-.7l-.498-1.699c-.107-.376-.283-.376-.395 0");
}

.kt86gzb_v {
  stop-color: var(--svg-color--f6c0b0, #F6C0B0);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lerr-nbox {
  width: 3.875px;
  height: 4.5px;
  x: 14.075px;
  y: 14.34px;
  rx: 1.938px;
}

.lerx3rbyx {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.383 9.199c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.341h-2.23a.23.23 0 0 1-.228-.272c.126-.64.69-1.127 1.371-1.127");
}

.lf_z1-eut {
  stop-color: var(--svg-color--705775, #705775);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.lvr4qibrk {
  stop-color: var(--svg-color--a77178, #A77178);
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m459pab_j {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mblwe85jo {
  cx: 20.761px;
  cy: 10.629px;
  r: 1.669px;
}

.mgsb3vbjk {
  stop-color: var(--svg-color--462c5b, #462C5B);
}

.mw2n2tb6u {
  cx: 11.248px;
  cy: 10.629px;
  r: 0.995px;
}

.n_pmxxxsa {
  stop-color: var(--svg-color--4f3b7b, #4F3B7B);
}

.n4sjjrd5b {
  d: path("M8.901 18.288a10.68 10.68 0 0 0-3.831 8.18v3.497H8.9z");
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.nwb1x8bnq {
  stop-color: var(--svg-color--594687, #594687);
}

.ny8l490vt {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.996 13.759c-.508 0-.985-.12-1.386-.328c-.136-.07-.284.084-.197.209c.335.507.918.845 1.582.845c.665 0 1.249-.338 1.583-.845c.087-.13-.06-.28-.197-.21c-.401.21-.873.329-1.386.329Z");
}

.nz1k2j0va {
  d: path("M18.767 16.116a10.3 10.3 0 0 0-2.337-.268h-.86q-1.194.002-2.312.262v5.422c0 4.175 1.065 5.972 2.654 8.433h.285c1.59-2.461 2.57-4.258 2.57-8.433z");
}

.o1-cy92hg {
  fill: var(--svg-color--242324, #242324);
  d: path("m20.814 4.152l.43.213c.75.373 1.18 1.227 1.018 2.133l-.59 3.04c-.052.314-.26.525-.572.533h-.018s.054-.906.107-1.44c.044-.433-.032-.565-.429-.96c-.214-.213-.375-.533-.375-.853v-.853c0-.267-.215-.48-.43-.533c-.643-.16-1.984-.427-3.914-.427s-3.272.267-3.916.427a.52.52 0 0 0-.429.533v.853c0 .32-.107.64-.375.854l-.161.16c-.215.16-.322.48-.322.746c.054.587.107 1.44.107 1.44l-.049-.002a.63.63 0 0 1-.594-.531l-.59-3.04c-.108-.853.321-1.707 1.072-2.08l.43-.213c.268-.16.536-.373.804-.587l.965-1.013c.59-.533 1.448-.693 2.2-.32a2.94 2.94 0 0 0 1.662 0c.805-.267 1.716-.053 2.36.533l.805.8c.214.267.482.427.804.587");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojp787kql {
  stop-color: var(--svg-color--bb9dd6, #BB9DD6);
}

.omxrzvbxf {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.11 9.66c.064.084-.069.188-.22.3c-.15.114-.263.193-.326.108c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.on2ulqbxu {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M15.996 13.759c-.508 0-.985-.12-1.386-.328c-.136-.07-.284.084-.197.209c.335.507.918.845 1.582.845c.665 0 1.249-.338 1.583-.845c.087-.13-.06-.28-.197-.21c-.401.21-.873.329-1.386.329");
}

.p5lz4ubjd {
  stop-color: var(--svg-color--391f50, #391F50);
}

.piwka_buo {
  d: path("m15.614 10.134l-.532 1.7a.54.54 0 0 0 .52.699h.787a.54.54 0 0 0 .52-.7l-.531-1.699c-.114-.376-.645-.376-.764 0");
}

.pk74vjldd {
  d: path("m14.133 17.534l1.813 1.251l-1.795 1.259a.246.246 0 0 1-.389-.188c-.04-.79-.04-1.569-.007-2.143a.239.239 0 0 1 .378-.179");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmbgiihyf {
  d: path("M18.971 10.245a.84.84 0 0 0-.231-.463l-.26.286l.117.228z");
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.q0kampb0a {
  stop-color: var(--svg-color--422131, #422131);
  stop-opacity: 0;
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qqr07gk3o {
  fill: var(--svg-color--9c80b1, #9C80B1);
  fill-rule: evenodd;
  d: path("M12.889 16.74c-.037.824.18 2.636 1.367 3.87c.255.266.715.18.863-.128l.73-1.435l.731 1.435c.149.308.608.394.863.129c1.186-1.235 1.404-3.047 1.368-3.872z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
  stop-opacity: 0;
}

.razk2i29v {
  stop-color: var(--svg-color--b68679, #B68679);
}

.rcq40k3oj {
  d: path("M11.242 18.4c-.03-1.012.55-1.42.819-1.503l.617-.065v5.373c0 3.575.239 4.662 2.733 7.12l.011.015c.047.083-.05.176-.132.12c-2.75-1.88-4.776-3.354-5.094-8.18a.187.187 0 0 1 .174-.198c.297-.019.56-.044.747-.06a.19.19 0 0 0 .171-.192c-.01-.53-.02-1.532-.046-2.43");
}

.rcuz4uefu {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
  stop-opacity: 0;
}

.rf-z3i_lt {
  cx: 15.731px;
  cy: 22.759px;
  r: 0.5px;
  fill: var(--svg-color--bfa7d5, #BFA7D5);
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
}

.rp3tqelhu {
  stop-color: var(--svg-color--63519f, #63519F);
}

.rruryhx1n {
  cx: 16.012px;
  cy: 18.754px;
  r: 0.809px;
}

.rvf3-0bfj {
  stop-color: var(--svg-color--dead9d, #DEAD9D);
  stop-opacity: 0;
}

.s41karbfc {
  stop-color: var(--svg-color--5a4772, #5A4772);
  stop-opacity: 0;
}

.safapbcnd {
  stop-color: var(--svg-color--937da2, #937DA2);
  stop-opacity: 0;
}

.sbbw_6vcc {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
}

.sj496hbeg {
  d: path("M23.099 18.288a10.68 10.68 0 0 1 3.831 8.18v3.497H23.1z");
}

.sjjnmvbyf {
  cx: 11.248px;
  cy: 10.629px;
  r: 1.669px;
}

.slnti_bde {
  cx: 16.004px;
  cy: 25.634px;
  r: 0.5px;
}

.t1dt_ab6m {
  stop-color: var(--svg-color--463766, #463766);
}

.t1trakjku {
  stop-color: var(--svg-color--635275, #635275);
}

.tayze7bgq {
  stop-color: var(--svg-color--60556d, #60556D);
}

.te0w8o76f {
  d: path("M14.625 10.258c0-.289-.235-.48-.298-.539l-.288.279l.177.361z");
}

.tg6m8fb0a {
  stop-color: var(--svg-color--8179b0, #8179B0);
  stop-opacity: 0;
}

.tqgh1edwg {
  stop-color: var(--svg-color--eaab97, #EAAB97);
}

.tyszy7o8n {
  stop-color: var(--svg-color--391f50, #391F50);
  stop-opacity: 0;
}

.u21vfmbcf {
  stop-color: var(--svg-color--c6b5d5, #C6B5D5);
}

.u8204ccps {
  d: path("M11.709 17.602c-.032-1.094.595-1.537.886-1.626l.668-.07v5.815c0 3.874 1.453 6.262 2.712 8.088c.063.09-.047.2-.138.138c-2.977-2.036-4.916-4.003-5.26-9.226a.203.203 0 0 1 .188-.215c.321-.02.606-.047.808-.066c.107-.01.188-.1.186-.206c-.011-.575-.023-1.659-.05-2.632");
}

.ubq14mb-s {
  stop-color: var(--svg-color--422131, #422131);
}

.uc5leibtb {
  stop-color: var(--svg-color--796ba6, #796BA6);
}

.udzp2zp0e {
  stop-color: var(--svg-color--4e3566, #4E3566);
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.v0ftcskkn {
  stop-color: var(--svg-color--866c89, #866C89);
  stop-opacity: 0;
}

.v5ndbpbdn {
  stop-color: var(--svg-color--463856, #463856);
}

.v5rdj9bnx {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M12.222 7.91v-.002l.003-.001l.004-.004l.012-.01a2 2 0 0 1 .155-.107c.1-.062.241-.14.42-.21a2.83 2.83 0 0 1 1.492-.159a.534.534 0 1 1-.166 1.055a1.77 1.77 0 0 0-.934.096a1.5 1.5 0 0 0-.3.16l-.008.005a.534.534 0 0 1-.679-.823");
}

.vdevotgbu {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.603 9.198c-.653 0-1.205.45-1.355 1.059c-.044.174.09.34.268.34h2.23a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.37-1.128");
}

.vdt_t3f2x {
  stop-color: var(--svg-color--866c89, #866C89);
}

.vjj8ifxqk {
  stop-color: var(--svg-color--5e5962, #5E5962);
  stop-opacity: 0;
}

.vo3um_bur {
  stop-color: var(--svg-color--dcc1f4, #DCC1F4);
  stop-opacity: 0;
}

.voa0z2bgu {
  stop-color: var(--svg-color--47305d, #47305D);
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.vr98_ac0a {
  stop-color: var(--svg-color--f4c1aa, #F4C1AA);
  stop-opacity: 0;
}

.wachewblq {
  stop-color: var(--svg-color--ba7c6b, #BA7C6B);
}

.wdqn7tq-u {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wm85g1cnx {
  stop-color: var(--svg-color--4b385d, #4B385D);
}

.wwvh45cwh {
  d: path("m19.959 5.005l-3.077 1.026a1.047 1.047 0 0 0 .47 2.031l3.06-.41z");
}

.x1yfsqmdm {
  stop-color: var(--svg-color--ab90c0, #AB90C0);
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.x9c83rbtu {
  d: path("M14.41 20.336c-1.185-1.235-1.403-3.046-1.367-3.87h2.969l.035 2.222l-.773 1.52c-.148.308-.608.394-.863.128");
}

.xcscp1tzt {
  d: path("M10.838 8.578c0-.266.107-.586.322-.746l.16-.16c.269-.214.376-.534.376-.854v-.853a.52.52 0 0 1 .43-.533c.643-.16 1.984-.427 3.915-.427c1.93 0 3.271.267 3.915.427c.215.053.43.266.43.533v.853c0 .32.16.64.375.854c.502.351.47.545.429.96a46 46 0 0 0-.108 1.44h.018l-.265 3.957c-.16 1.77-1.552 3.003-3.21 3.003h-3.21c-1.713 0-3.05-1.233-3.21-3.003c-.14-1.816-.201-3.638-.367-5.45");
}

.xg711ab6m {
  stop-color: var(--svg-color--4e377f, #4E377F);
}

.xm2fj02xh {
  cx: 20.761px;
  cy: 10.629px;
  r: 0.995px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
}

.xtmoiyb-u {
  cx: 20.761px;
  cy: 10.629px;
  r: 0.995px;
}

.xu6qifbqx {
  stop-color: var(--svg-color--a5716b, #A5716B);
}

.y-8wpsx8z {
  d: path("M13.81 9.47a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.yd68gzbbi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.656 7.765c.43-.075 1.269-.054 1.85.398");
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.ygunkzbtc {
  stop-color: var(--svg-color--ae7878, #AE7878);
  stop-opacity: 0;
}

.yl8zw5b_j {
  stop-color: var(--svg-color--592f4f, #592F4F);
  stop-opacity: 0;
}

.yrheztpeb {
  d: path("M5.07 26.469c0-5.797 4.7-10.62 10.5-10.62h.86c5.8 0 10.5 4.823 10.5 10.62v3.496H5.07z");
}

.yyvs3obha {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
  stop-opacity: 0;
}

.z_d2yzmmm {
  stop-color: var(--svg-color--4b435b, #4B435B);
}

.z3n_1mwef {
  stop-color: var(--svg-color--a58787, #A58787);
}

.z58nq_enb {
  stop-color: var(--svg-color--5e536c, #5E536C);
}

.z7qr8pb7n {
  stop-color: var(--svg-color--ba9fd3, #BA9FD3);
}

.z8y6fgvmn {
  stop-color: var(--svg-color--ffdabf, #FFDABF);
}

.zf-wx0bhd {
  d: path("M18.11 9.66c.064.084-.069.188-.22.3c-.15.114-.263.193-.326.108c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
}

.zgwb37bzk {
  stop-color: var(--svg-color--f4c1aa, #F4C1AA);
}

.zhh5xs6ht {
  stop-color: var(--svg-color--bb9dd6, #BB9DD6);
  stop-opacity: 0;
}

.zj5z5alkp {
  stop-color: var(--svg-color--ae7878, #AE7878);
}

.zj8enfb0n {
  fill: var(--svg-color--000, #000);
  d: path("M17.665 10.363c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.06-.235");
}

.zky6sqbmn {
  fill: var(--svg-color--fbc4b1, #FBC4B1);
  d: path("m15.614 10.344l-.532 1.7a.54.54 0 0 0 .52.699h.787a.54.54 0 0 0 .52-.7l-.531-1.699c-.114-.376-.645-.376-.764 0");
}

.zvesnxp2v {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.437 8.283c.327-.289 1.042-.593 1.927-.452");
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

.zynu2nm7a {
  stop-color: var(--svg-color--6b5977, #6B5977);
}

.zz6iedcfy {
  stop-color: var(--svg-color--d8a09f, #D8A09F);
  stop-opacity: 0;
}

</style>
