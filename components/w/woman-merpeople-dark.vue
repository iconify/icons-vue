<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iHv3Qve)"><path fill="url(#irbYSXc)" class="vsknd5b9t"/><path fill="url(#i3fIDlb)" class="vsknd5b9t"/><path fill="url(#iQ3c69b)" class="vsknd5b9t"/><path fill="url(#iQrn8mc)" class="vsknd5b9t"/><path fill="url(#i5rHk7c)" class="vsknd5b9t"/><path fill="url(#i8XzMCd)" class="vsknd5b9t"/><path fill="url(#iJI8Vce)" class="vsknd5b9t"/></g><g filter="url(#iHVrYpg)"><path class="l85u8ibfx"/></g><path fill="url(#imdrOid)" class="d804zky3u"/><g filter="url(#ia574Qd)"><path fill="url(#iOxYU2b)" class="m4pcayl4x"/></g><path fill="url(#i5vssKd)" class="lby3v6ati"/><path fill="url(#imDw7rb)" class="lby3v6ati"/><g filter="url(#iOe2EJb)"><path fill="url(#i9xtkBb)" class="qdgeq05dx"/><path fill="url(#i0RcOOb)" class="qdgeq05dx"/></g><g filter="url(#iPVd7pc)"><path fill="url(#iOU3fve)" class="rvgjtg4fi"/><path fill="url(#iFaJ7wb)" class="rvgjtg4fi"/><path fill="url(#i1BbVjd)" class="rvgjtg4fi"/><path fill="url(#iifXH1b)" class="rvgjtg4fi"/><path fill="url(#izzX8Ob)" class="rvgjtg4fi"/><path fill="url(#i1cj2uc)" class="rvgjtg4fi"/><path fill="url(#imZZWQb)" class="rvgjtg4fi"/><path fill="url(#iy2skpd)" class="rvgjtg4fi"/></g><path fill="url(#iUxxn5b)" class="rvgjtg4fi"/><path fill="url(#iUpU1Nc)" class="rvgjtg4fi"/><path fill="url(#id4Rf4I)" class="rvgjtg4fi"/><g filter="url(#iIar2xc)"><path stroke="url(#iI9sDUb)" class="yf02b6ygm"/></g><g filter="url(#i9kOmcz)"><path stroke="url(#iUUCLJd)" class="nl2u64eej"/></g><g filter="url(#i4snamo)"><path stroke="url(#iDbcAtn)" class="ubz5oeoiz"/></g><g filter="url(#ijQrTAd)"><path class="b_gbvxblg"/></g><g filter="url(#iF7GP0d)"><path class="eywjsqb5l"/><path fill="url(#iO96kgc)" class="wliqnbp1k"/><path fill="url(#iPbL8Xb)" class="wliqnbp1k"/><path fill="url(#iyPwIbP)" class="wliqnbp1k"/></g><g filter="url(#iW1mYdd)"><path class="k_i-sob7k"/></g><path fill="url(#iiBlREE)" class="o87uryobz"/><g filter="url(#ivZMkWc)"><path class="pfckoacfq"/></g><g filter="url(#i9xayzb)"><path class="l2r6gabvx"/></g><g filter="url(#iWRx83P)"><path fill="url(#iPXg6sc)" class="ml6o-6oro"/></g><path fill="url(#iOP2TvL)" class="ml6o-6oro"/><path fill="url(#i0Y2Vrt)" class="ml6o-6oro"/><path fill="url(#ilmeAsb)" class="ml6o-6oro"/><path fill="url(#iOJoN4d)" class="ml6o-6oro"/><g filter="url(#iag9Efd)"><path class="iw5oy2b-m"/></g><path class="i_geetbwl"/><path fill="url(#iz8Udje)" class="vckbn7bgk"/><path fill="url(#i3kGvGe)" class="vckbn7bgk"/><path fill="url(#ituRlFc)" class="vckbn7bgk"/><path fill="url(#ikTYFBd)" class="vckbn7bgk"/><path fill="url(#ivGMJab)" class="vckbn7bgk"/><g filter="url(#ik49Qjc)"><path stroke="url(#imPKjde)" class="kzknyvg9e"/></g><path class="p51s2s65u"/><g filter="url(#iYsQZDc)"><path class="oc32bubbt"/></g><g filter="url(#ilU6qIe)"><path class="v3hxs-buk"/></g><g filter="url(#iLDK84U)"><path class="dx6c81b-y"/></g><g filter="url(#iFTsikc)"><path clip-rule="evenodd" class="c4ttjnc0i"/></g><path class="ivaw61bob"/><path fill="url(#i5YbaKe)" class="akquh7bgt"/><path class="ro7svqvjx"/><g filter="url(#iRe2DQS)"><path class="nl_8d1b0i"/><path fill="url(#i2LqhIf)" class="rggh3hbuf"/></g><g filter="url(#iPPD89b)"><path fill="url(#idDVUGc)" class="yo-rx8c0q"/></g><path class="sdf9tobyx"/><path fill="url(#imJspBd)" class="o0eqsac9n"/><path class="eiflvuzgd"/><g filter="url(#iYavcTz)"><path fill="url(#i1cZLfc)" class="x2e_pmc0g"/></g><g filter="url(#iDS5tue)"><ellipse transform="rotate(-27.914 15.96 6.811)" class="t2ck-pbsh"/><ellipse fill="url(#iNxWnMx)" transform="rotate(-27.914 15.96 6.811)" class="utkhftb9q"/></g><g filter="url(#iT7G5BI)"><path class="w_uqfvbai"/></g><g filter="url(#ikU6rdd)"><path class="qqxfe6pwj"/></g><g filter="url(#iPNxX8N)"><path fill="url(#ixeSyBe)" class="q2m7q-bcq"/></g><g filter="url(#iBv63de)"><path fill="url(#iuFpaVb)" class="iwu7gdsah"/></g><g filter="url(#iGIXOnb)"><path fill="url(#i56h0yb)" class="iwu7gdsah"/><path fill="url(#iSijnkb)" class="iwu7gdsah"/></g><g filter="url(#iwVOXQd)"><path class="iorvdubip"/><path fill="url(#ibrXHpJ)" class="inz52_phe"/><path fill="url(#iII9RCc)" class="inz52_phe"/><path fill="url(#ihEBcfc)" class="inz52_phe"/></g><g filter="url(#i80uUXb)"><path fill="url(#iNVxRmA)" class="p6977lbwx"/></g><g filter="url(#ioW0yQb)"><path fill="url(#iL1qWmb)" class="idot92bag"/></g><g filter="url(#iDi1Pft)"><path stroke="url(#ikrPh5c)" class="vpkiteigl"/></g><defs><radialGradient id="irbYSXc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.56252 4.21874 -6.12104 -3.718 21.024 3.26)" gradientUnits="userSpaceOnUse"><stop class="m6q1utbkt"/><stop offset="1" class="b141qib1b"/></radialGradient><radialGradient id="i3fIDlb" cx="0" cy="0" r="1" gradientTransform="matrix(7.15633 -13.4342 24.24607 12.91576 11.291 16.912)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="jx01c6c2n"/><stop offset="1" class="p_-rkibqb"/></radialGradient><radialGradient id="iQ3c69b" cx="0" cy="0" r="1" gradientTransform="rotate(144.219 4.695 10.165)scale(4.27577 3.3172)" gradientUnits="userSpaceOnUse"><stop class="u_kx35bmm"/><stop offset="1" class="u-uq4ccbs"/></radialGradient><radialGradient id="iQrn8mc" cx="0" cy="0" r="1" gradientTransform="rotate(-26.896 31.135 -34.786)scale(4.83558 4.72975)" gradientUnits="userSpaceOnUse"><stop class="xs_unubla"/><stop offset="1" class="pf7v1soqz"/></radialGradient><radialGradient id="i5rHk7c" cx="0" cy="0" r="1" gradientTransform="rotate(83.177 2.967 13.177)scale(3.68233 3.00341)" gradientUnits="userSpaceOnUse"><stop offset=".305" class="xy7wgkblp"/><stop offset="1" class="xbecpqbnm"/></radialGradient><radialGradient id="i8XzMCd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.59372 4.50004 -1.36243 -1.69355 14.792 3.134)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="tqn-xwbko"/><stop offset="1" class="ftsby3bnh"/></radialGradient><radialGradient id="iJI8Vce" cx="0" cy="0" r="1" gradientTransform="matrix(.98438 1.5625 -1.81496 1.14342 16.073 2.415)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="imdrOid" cx="0" cy="0" r="1" gradientTransform="rotate(-17.313 87.674 -23.135)scale(13.0953 16.0195)" gradientUnits="userSpaceOnUse"><stop offset=".805" class="g1dp7ccjz"/><stop offset="1" class="s536pit3i"/></radialGradient><radialGradient id="iOxYU2b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.61906 1.93752 -6.36477 -11.88867 22.702 20.572)" gradientUnits="userSpaceOnUse"><stop class="h8_lbz_nz"/><stop offset="1" class="jkj1op9ie"/></radialGradient><radialGradient id="i5vssKd" cx="0" cy="0" r="1" gradientTransform="matrix(.67968 -.9375 .55678 .40367 6.762 16.9)" gradientUnits="userSpaceOnUse"><stop class="ps08ktb6i"/><stop offset="1" class="sbjlvwbre"/></radialGradient><radialGradient id="i9xtkBb" cx="0" cy="0" r="1" gradientTransform="matrix(-.68567 .5 -.27415 -.37595 25.693 7.447)" gradientUnits="userSpaceOnUse"><stop class="ht6ac_srn"/><stop offset="1" class="jvte3eb3p"/></radialGradient><radialGradient id="i0RcOOb" cx="0" cy="0" r="1" gradientTransform="matrix(-.239 -.60938 .1217 -.04774 25.14 8.603)" gradientUnits="userSpaceOnUse"><stop class="y543bybjo"/><stop offset="1" class="og8s_xbdj"/></radialGradient><radialGradient id="iOU3fve" cx="0" cy="0" r="1" gradientTransform="rotate(159 8.58 8.058)scale(4.71973 6.48913)" gradientUnits="userSpaceOnUse"><stop class="y6bb5ubdl"/><stop offset="1" class="acwoddqsz"/></radialGradient><radialGradient id="i1BbVjd" cx="0" cy="0" r="1" gradientTransform="matrix(2.09375 0 0 4.11135 14.48 17.197)" gradientUnits="userSpaceOnUse"><stop offset=".075" class="uyl0babqk"/><stop offset="1" class="sui4c2hzy"/></radialGradient><radialGradient id="iifXH1b" cx="0" cy="0" r="1" gradientTransform="rotate(-124.961 15.728 2.092)scale(7.03516 2.62961)" gradientUnits="userSpaceOnUse"><stop offset=".281" class="qal7r2b_k"/><stop offset="1" class="sohh290zz"/></radialGradient><radialGradient id="izzX8Ob" cx="0" cy="0" r="1" gradientTransform="matrix(1.14062 3.15625 -1.12664 .40715 23.76 10.838)" gradientUnits="userSpaceOnUse"><stop class="hyvbooldn"/><stop offset="1" class="g0hd4ubag"/></radialGradient><radialGradient id="i1cj2uc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9412 -1.73466 2.47682 -2.77173 16.647 14.095)" gradientUnits="userSpaceOnUse"><stop class="mlaeyedlj"/><stop offset="1" class="nq4i4cc1a"/></radialGradient><radialGradient id="imZZWQb" cx="0" cy="0" r="1" gradientTransform="matrix(-.49998 -1.89063 3.41696 -.90363 24.964 15.493)" gradientUnits="userSpaceOnUse"><stop offset=".117" class="o5s5w9tej"/><stop offset="1" class="r13l5acqq"/></radialGradient><radialGradient id="iy2skpd" cx="0" cy="0" r="1" gradientTransform="rotate(157.19 7.611 6.63)scale(3.62742 2.32226)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="qxy_enyov"/><stop offset="1" class="hxos-hbkk"/></radialGradient><radialGradient id="iUxxn5b" cx="0" cy="0" r="1" gradientTransform="matrix(.6875 0 0 4.60938 14.12 16.9)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="ndh-ggbqf"/><stop offset="1" class="naoj9jbij"/></radialGradient><radialGradient id="id4Rf4I" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78126 1.58593 -.17358 -.19496 13.002 15.384)" gradientUnits="userSpaceOnUse"><stop offset=".144" class="b03ppibgx"/><stop offset="1" class="yffwppb7t"/></radialGradient><radialGradient id="iO96kgc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.17187 -1.23438 .5687 -.5399 16.852 14.384)" gradientUnits="userSpaceOnUse"><stop class="rd_1vj1uu"/><stop offset="1" class="w4wjacb9v"/></radialGradient><radialGradient id="iPbL8Xb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.26562 -.57617 0 17.413 13.306)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="dsu9eguof"/><stop offset="1" class="dogwq2blg"/></radialGradient><radialGradient id="iyPwIbP" cx="0" cy="0" r="1" gradientTransform="matrix(-1.4707 1.41406 -.31529 -.32792 21.136 13.15)" gradientUnits="userSpaceOnUse"><stop class="gwqfskb8v"/><stop offset="1" class="n7-hw2b3h"/></radialGradient><radialGradient id="iiBlREE" cx="0" cy="0" r="1" gradientTransform="rotate(124.526 8.757 8.934)scale(1.33706 .90463)" gradientUnits="userSpaceOnUse"><stop offset=".292" class="nibdu3-2v"/><stop offset="1" class="se4ekfbko"/></radialGradient><radialGradient id="iPXg6sc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.03126 1.72424 -2.40572 -4.22933 18.573 7.535)" gradientUnits="userSpaceOnUse"><stop class="ox07i09hz"/><stop offset="1" class="e12r3_bhd"/></radialGradient><radialGradient id="iOP2TvL" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.48957 -5.92174 0 17.41 6.26)" gradientUnits="userSpaceOnUse"><stop offset=".658" class="cuy-33n5a"/><stop offset=".929" class="je4t0yh1q"/></radialGradient><radialGradient id="i0Y2Vrt" cx="0" cy="0" r="1" gradientTransform="rotate(146.659 9.247 5.584)scale(1.42145 2.26202)" gradientUnits="userSpaceOnUse"><stop class="yk-s_4bpi"/><stop offset="1" class="pay0dfbkl"/></radialGradient><radialGradient id="ilmeAsb" cx="0" cy="0" r="1" gradientTransform="matrix(.64063 .60156 -1.64542 1.75226 15.542 4.478)" gradientUnits="userSpaceOnUse"><stop offset=".267" class="bx3agpb5g"/><stop offset="1" class="ekzxxeb4n"/></radialGradient><radialGradient id="iOJoN4d" cx="0" cy="0" r="1" gradientTransform="matrix(-1 1.46875 -1.05602 -.719 18.323 5.462)" gradientUnits="userSpaceOnUse"><stop offset=".391" class="mpgqmibea"/><stop offset="1" class="lzwk4mb-k"/></radialGradient><radialGradient id="i3kGvGe" cx="0" cy="0" r="1" gradientTransform="matrix(-.47656 0 0 -.14893 17.659 8.11)" gradientUnits="userSpaceOnUse"><stop class="xg7_958fc"/><stop offset="1" class="tvq_fsbne"/></radialGradient><radialGradient id="ituRlFc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.39263 1.04529 0 17.41 8.425)" gradientUnits="userSpaceOnUse"><stop offset=".244" class="uzwc_ugjd"/><stop offset="1" class="gdl7jobef"/></radialGradient><radialGradient id="i5YbaKe" cx="0" cy="0" r="1" gradientTransform="rotate(124.592 7.723 8.39)scale(.55383 .87854)" gradientUnits="userSpaceOnUse"><stop offset=".622" class="chm_zob8h"/><stop offset="1" class="w_bi9zfnz"/></radialGradient><radialGradient id="i2LqhIf" cx="0" cy="0" r="1" gradientTransform="matrix(-.13647 -.17586 .24212 -.18789 18.564 6.918)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="imJspBd" cx="0" cy="0" r="1" gradientTransform="rotate(124.592 6.433 7.713)scale(.55383 .87855)" gradientUnits="userSpaceOnUse"><stop offset=".622" class="chm_zob8h"/><stop offset="1" class="w_bi9zfnz"/></radialGradient><radialGradient id="iNxWnMx" cx="0" cy="0" r="1" gradientTransform="matrix(-.00455 -.29073 .34947 -.00547 15.95 6.997)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ixeSyBe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.98437 1.60938 -.62216 -.76713 15.589 4.087)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="qo67pbbye"/><stop offset=".77" class="i2-gi5kcc"/></radialGradient><radialGradient id="iuFpaVb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.46875 .08792 -.04263 -1.68195 19.76 4.138)" gradientUnits="userSpaceOnUse"><stop class="ws4l7vbtn"/><stop offset="1" class="wysa1pg4b"/></radialGradient><radialGradient id="i56h0yb" cx="0" cy="0" r="1" gradientTransform="matrix(.42188 -2.92187 6.42687 .92795 16.495 5.337)" gradientUnits="userSpaceOnUse"><stop offset=".683" class="zzrbad3ti"/><stop offset=".945" class="rw2c-304f"/></radialGradient><radialGradient id="iSijnkb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.04688 -.4531 .1291 -.5832 19.682 4.837)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="ibrXHpJ" cx="0" cy="0" r="1" gradientTransform="matrix(.20313 1.2422 -.5655 .09247 21.027 3.806)" gradientUnits="userSpaceOnUse"><stop class="mk_tesa_t"/><stop offset="1" class="hj78b9cjo"/></radialGradient><radialGradient id="iII9RCc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.11657 .3125 -.09737 -.3479 22.346 4.681)" gradientUnits="userSpaceOnUse"><stop class="o5bua8boy"/><stop offset="1" class="rz_b8bbbi"/></radialGradient><radialGradient id="ihEBcfc" cx="0" cy="0" r="1" gradientTransform="matrix(-.59375 -1.38766 .70345 -.301 21.932 6.494)" gradientUnits="userSpaceOnUse"><stop class="o0h7y_boi"/><stop offset="1" class="s9ajizb_e"/></radialGradient><filter id="iHv3Qve" width="14.674" height="15.298" x="7.898" y="1.615" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.231373 0 0 0 0 0.231373 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1291"/></filter><filter id="iHVrYpg" width="16.97" height="13.626" x="7.639" y="16.259" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1291"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.576471 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1291" result="effect2_innerShadow_4002_1291"/></filter><filter id="ia574Qd" width="8.803" height="12.453" x="15.083" y="15.212" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1291" stdDeviation=".5"/></filter><filter id="iOe2EJb" width="1.41" height="1.949" x="24.485" y="7.218" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.0784314 0 0 0 0 0.0705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1291"/></filter><filter id="iPVd7pc" width="20.634" height="10.708" x="5.683" y="7.051" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1291"/></filter><filter id="iIar2xc" width="11.112" height="3.615" x="10.829" y="25.798" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1291" stdDeviation=".2"/></filter><filter id="i9kOmcz" width="3.297" height="3.17" x="8.245" y="23.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1291" stdDeviation=".2"/></filter><filter id="i4snamo" width="3.085" height="3.032" x="11.506" y="23.31" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1291" stdDeviation=".2"/></filter><filter id="ijQrTAd" width="6.547" height="2.797" x="14.14" y="13.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1291" stdDeviation=".125"/></filter><filter id="iF7GP0d" width="7.845" height="3.428" x="13.691" y="12.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.243137 0 0 0 0 0.690196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1291"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.32549 0 0 0 0 0.662745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1291" result="effect2_innerShadow_4002_1291"/></filter><filter id="iW1mYdd" width="2.002" height="1.902" x="13.691" y="6.27" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.254902 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1291"/></filter><filter id="ivZMkWc" width="1.669" height="1.67" x="19.428" y="6.386" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1291" stdDeviation=".1"/></filter><filter id="i9xayzb" width="1.569" height="1.57" x="13.868" y="6.436" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1291" stdDeviation=".075"/></filter><filter id="iWRx83P" width="6.422" height="6.428" x="14.399" y="4.321" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.262745 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1291"/></filter><filter id="iag9Efd" width="1.609" height="2.085" x="16.51" y="6.672" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1291" stdDeviation=".125"/></filter><filter id="ik49Qjc" width="2.152" height=".865" x="16.335" y="8.627" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1291" stdDeviation=".025"/></filter><filter id="iYsQZDc" width="1.855" height=".76" x="17.885" y="6.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1291"/></filter><filter id="ilU6qIe" width="1.855" height=".76" x="15.08" y="6.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1291"/></filter><filter id="iLDK84U" width="1.531" height=".726" x="15.16" y="5.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0431373 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1291"/></filter><filter id="iFTsikc" width="1.531" height=".727" x="18.361" y="5.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0431373 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1291"/></filter><filter id="iRe2DQS" width=".545" height=".492" x="18.225" y="6.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1291" stdDeviation=".05"/></filter><filter id="iPPD89b" width=".689" height=".702" x="18.68" y="6.571" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1291" stdDeviation=".1"/></filter><filter id="iYavcTz" width=".745" height=".777" x="16.055" y="6.533" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1291" stdDeviation=".1"/></filter><filter id="iDS5tue" width=".62" height=".497" x="15.65" y="6.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1291" stdDeviation=".05"/></filter><filter id="iT7G5BI" width="1.231" height=".473" x="18.431" y="5.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1291" stdDeviation=".05"/></filter><filter id="ikU6rdd" width="1.231" height=".473" x="15.21" y="5.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1291" stdDeviation=".05"/></filter><filter id="iPNxX8N" width="2.163" height="2.504" x="13.885" y="3.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1291" stdDeviation=".05"/></filter><filter id="iBv63de" width="5.15" height="3.645" x="15.32" y="2.328" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0745098 0 0 0 0 0.0196078 0 0 0 0 0.054902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1291"/><feGaussianBlur result="effect2_foregroundBlur_4002_1291" stdDeviation=".05"/></filter><filter id="iGIXOnb" width="5.15" height="3.495" x="15.32" y="2.478" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1291" stdDeviation=".05"/></filter><filter id="iwVOXQd" width="3.17" height="3.061" x="19.276" y="3.525" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.529412 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1291"/></filter><filter id="i80uUXb" width="2.055" height="6.641" x="24.354" y="7.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1291" stdDeviation=".25"/></filter><filter id="ioW0yQb" width="4.719" height="3.595" x="19.998" y="10.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1291" stdDeviation=".25"/></filter><filter id="iDi1Pft" width="1.175" height="2.326" x="23.635" y="7.38" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1291" stdDeviation=".125"/></filter><linearGradient id="imDw7rb" x1="6.713" x2="7.026" y1="16.853" y2="16.853" gradientUnits="userSpaceOnUse"><stop class="mo0n2bbuy"/><stop offset="1" class="g53j5bbdl"/></linearGradient><linearGradient id="iFaJ7wb" x1="8.135" x2="14.729" y1="16.572" y2="12.165" gradientUnits="userSpaceOnUse"><stop class="z3skqac1h"/><stop offset="1" class="n88-o7gbs"/></linearGradient><linearGradient id="iUpU1Nc" x1="17.354" x2="17.354" y1="18.04" y2="16.384" gradientUnits="userSpaceOnUse"><stop offset=".113" class="se4ekfbko"/><stop offset="1" class="ls21dtb6x"/></linearGradient><linearGradient id="iI9sDUb" x1="11.768" x2="20.875" y1="26.97" y2="28.813" gradientUnits="userSpaceOnUse"><stop class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="iUUCLJd" x1="10.518" x2="8.203" y1="25.763" y2="25.39" gradientUnits="userSpaceOnUse"><stop offset=".302" class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="iDbcAtn" x1="14.012" x2="13.482" y1="24.1" y2="26.21" gradientUnits="userSpaceOnUse"><stop class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="iz8Udje" x1="17.838" x2="17.37" y1="7.767" y2="7.79" gradientUnits="userSpaceOnUse"><stop class="ugp4i7b_e"/><stop offset="1" class="jcfc22o9u"/></linearGradient><linearGradient id="ikTYFBd" x1="17.452" x2="17.452" y1="8.455" y2="8.275" gradientUnits="userSpaceOnUse"><stop class="e665i0y4p"/><stop offset="1" class="jwxs8nbrt"/></linearGradient><linearGradient id="ivGMJab" x1="17.41" x2="17.41" y1="6.84" y2="7.775" gradientUnits="userSpaceOnUse"><stop class="tla-kpu2g"/><stop offset=".824" class="zyxzx5bbz"/></linearGradient><linearGradient id="imPKjde" x1="16.98" x2="17.247" y1="9.352" y2="8.837" gradientUnits="userSpaceOnUse"><stop class="wv0cm2xvj"/><stop offset="1" class="ke45y-bqc"/></linearGradient><linearGradient id="idDVUGc" x1="19.158" x2="18.974" y1="6.899" y2="7.013" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i1cZLfc" x1="16.559" x2="16.375" y1="6.899" y2="7.013" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iNVxRmA" x1="24.421" x2="26.951" y1="10.087" y2="11.158" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="a2itfaced"/></linearGradient><linearGradient id="iL1qWmb" x1="23.06" x2="23.438" y1="13.196" y2="11.192" gradientUnits="userSpaceOnUse"><stop class="p8v9kob2h"/><stop offset="1" class="a2itfaced"/></linearGradient><linearGradient id="ikrPh5c" x1="24.213" x2="24.213" y1="9.29" y2="6.665" gradientUnits="userSpaceOnUse"><stop class="r4mhscsqa"/><stop offset="1" class="ej8gxzbcw"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-merpeople-dark" /></template>
<style>
.a2itfaced {
  stop-color: var(--svg-color--5b4645, #5B4645);
  stop-opacity: 0;
}

.acwoddqsz {
  stop-color: var(--svg-color--432e2f, #432E2F);
}

.akquh7bgt {
  d: path("M18.701 6.586a.527.527 0 0 1 .508.666H18.19a.53.53 0 0 1 .51-.666");
}

.b_gbvxblg {
  fill: var(--svg-color--372028, #372028);
  d: path("M14.715 13.837a.325.325 0 0 0-.325.325v.916c0 .584.473 1.056 1.056 1.056h3.935c.583 0 1.055-.473 1.055-1.056v-.916a.325.325 0 0 0-.324-.325h-1.496a1.22 1.22 0 0 0-1.119.735c-.022.05-.146.05-.168 0a1.22 1.22 0 0 0-1.118-.735z");
}

.b03ppibgx {
  stop-color: var(--svg-color--463847, #463847);
}

.b141qib1b {
  stop-color: var(--svg-color--1b1120, #1B1120);
}

.bx3agpb5g {
  stop-color: var(--svg-color--1e0a0c, #1E0A0C);
}

.c4ttjnc0i {
  fill: var(--svg-color--120c18, #120C18);
  fill-rule: evenodd;
  d: path("m19.615 5.9l-.081.136za.159.159 0 0 1-.162.272l-.003-.002l-.067-.034a2 2 0 0 0-.202-.08a1.34 1.34 0 0 0-.634-.054a.159.159 0 0 1-.055-.313c.303-.053.584 0 .785.065a2 2 0 0 1 .33.14l.006.004z");
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.chm_zob8h {
  stop-color: var(--svg-color--7a5449, #7A5449);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cuy-33n5a {
  stop-color: var(--svg-color--3d222f, #3D222F);
  stop-opacity: 0;
}

.d804zky3u {
  d: path("M13.356 19.091c0-1.425.76-2.101 1.16-2.242l5.66-.34c1.61.719 2.954 2.781 3.141 5.281c.188 2.5-.203 4.954-2.265 6.563c-1.65 1.287-3.959 1.552-4.938 1.531H13.64c-2.625 0-3.246-1.89-3.355-2.297a11 11 0 0 0-.184-.598a.43.43 0 0 0-.221-.26c-.528-.244-1.521-.486-1.947-1.388a3.1 3.1 0 0 1-.28-1.63c.022-.213.232-.344.44-.296c.52.119.951.252 1.57.567a3.4 3.4 0 0 1 1.238 1.226c.065.11.238.112.304.003c.206-.342.561-.818 1.045-1.12a4.7 4.7 0 0 1 1.846-.678a.347.347 0 0 1 .387.345c.037 1.765-.748 2.275-1.198 2.513c-.288.131-.62.277-.866.388c-.139.063-.208.223-.14.36c.474.956 1.468.87 2.858.87c1.851 0 2.96-1.325 2.843-2.724c-.062-1.812-1.562-2.515-2.57-3.148c-.523-.328-2.055-1.145-2.055-2.926");
}

.dogwq2blg {
  stop-color: var(--svg-color--8b61d1, #8B61D1);
  stop-opacity: 0;
}

.dsu9eguof {
  stop-color: var(--svg-color--7550b8, #7550B8);
}

.dx6c81b-y {
  fill: var(--svg-color--120c18, #120C18);
  d: path("m15.402 6.17l-.002.002a.159.159 0 0 1-.163-.272l.002-.002l.006-.003l.02-.01q.024-.015.068-.035c.058-.028.141-.064.242-.096c.201-.064.482-.118.785-.065a.158.158 0 0 1-.055.313c-.236-.042-.462 0-.633.054a1.6 1.6 0 0 0-.257.107z");
}

.e12r3_bhd {
  stop-color: var(--svg-color--3c212f, #3C212F);
}

.e665i0y4p {
  stop-color: var(--svg-color--341923, #341923);
}

.eiflvuzgd {
  fill: var(--svg-color--000, #000);
  d: path("M16.422 7.113a.3.3 0 0 0-.302-.302a.3.3 0 0 0-.269.442h.535a.3.3 0 0 0 .036-.14");
}

.ej8gxzbcw {
  stop-color: var(--svg-color--5f504f, #5F504F);
  stop-opacity: 0;
}

.ekzxxeb4n {
  stop-color: var(--svg-color--1e0a0c, #1E0A0C);
  stop-opacity: 0;
}

.eywjsqb5l {
  fill: var(--svg-color--8d62d5, #8D62D5);
  d: path("M14.09 13.15a.4.4 0 0 0-.4.4v1.128a1.3 1.3 0 0 0 1.3 1.3h4.846a1.3 1.3 0 0 0 1.3-1.3V13.55a.4.4 0 0 0-.4-.4h-1.842a1.5 1.5 0 0 0-1.377.904c-.027.062-.18.062-.207 0a1.5 1.5 0 0 0-1.377-.904z");
}

.ft5dv1b6b {
  fill: none;
}

.ftsby3bnh {
  stop-color: var(--svg-color--3f3838, #3F3838);
  stop-opacity: 0;
}

.g0hd4ubag {
  stop-color: var(--svg-color--251415, #251415);
  stop-opacity: 0;
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g1dp7ccjz {
  stop-color: var(--svg-color--4dcd7d, #4DCD7D);
  stop-opacity: 0;
}

.g53j5bbdl {
  stop-color: var(--svg-color--544440, #544440);
  stop-opacity: 0;
}

.gdl7jobef {
  stop-color: var(--svg-color--3d222e, #3D222E);
  stop-opacity: 0;
}

.gwqfskb8v {
  stop-color: var(--svg-color--9f7ada, #9F7ADA);
}

.h8_lbz_nz {
  stop-color: var(--svg-color--4edd83, #4EDD83);
}

.hj78b9cjo {
  stop-color: var(--svg-color--34affa, #34AFFA);
  stop-opacity: 0;
}

.ht6ac_srn {
  stop-color: var(--svg-color--615250, #615250);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.hxos-hbkk {
  stop-color: var(--svg-color--291715, #291715);
  stop-opacity: 0;
}

.hyvbooldn {
  stop-color: var(--svg-color--251415, #251415);
}

.i_geetbwl {
  fill: var(--svg-color--452e2c, #452E2C);
  d: path("m17.184 7.007l-.314 1.005a.32.32 0 0 0 .308.413h.465a.32.32 0 0 0 .307-.413l-.314-1.005c-.067-.222-.381-.222-.452 0");
}

.i2-gi5kcc {
  stop-color: var(--svg-color--2e242a, #2E242A);
  stop-opacity: 0;
}

.idot92bag {
  d: path("M24.218 13.296v.793l-3.72-2.397l.083-.198z");
}

.inz52_phe {
  d: path("m21.018 3.79l.204.628c.03.09.12.16.22.16l.697.01c.21 0 .285.242.105.382l-.532.418c-.08.06-.11.16-.08.26l.198.658c.07.22-.146.36-.336.23l-.542-.398a.225.225 0 0 0-.27 0l-.551.399c-.19.13-.396-.01-.336-.23l.197-.66c.03-.1 0-.2-.08-.26l-.539-.397c-.18-.14-.097-.382.133-.382l.666-.01c.1 0 .19-.07.22-.16l.231-.648c.07-.23.325-.21.395 0");
}

.iorvdubip {
  fill: var(--svg-color--33aef9, #33AEF9);
  d: path("m21.018 3.79l.204.628c.03.09.12.16.22.16l.697.01c.21 0 .285.242.105.382l-.532.418c-.08.06-.11.16-.08.26l.198.658c.07.22-.146.36-.336.23l-.542-.398a.225.225 0 0 0-.27 0l-.551.399c-.19.13-.396-.01-.336-.23l.197-.66c.03-.1 0-.2-.08-.26l-.539-.397c-.18-.14-.097-.382.133-.382l.666-.01c.1 0 .19-.07.22-.16l.231-.648c.07-.23.325-.21.395 0");
}

.ivaw61bob {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.824 6.425c.385 0 .711.267.8.626a.162.162 0 0 1-.158.201h-1.319a.136.136 0 0 1-.134-.16a.826.826 0 0 1 .81-.667");
}

.iw5oy2b-m {
  fill: var(--svg-color--3a202b, #3A202B);
  d: path("m17.179 7.09l-.404 1.004a.32.32 0 0 0 .307.413h.465a.32.32 0 0 0 .308-.413l-.314-1.005c-.068-.222-.292-.222-.363 0");
}

.iwu7gdsah {
  d: path("M17.054 2.598c-.67-.148-1.564.586-1.633.833c.91 2.14 2.14 2.001 3.841 1.937c.945-.036 1.02.3 1.1.505c.156-2.688-1.783-2.938-3.308-3.275");
}

.jcfc22o9u {
  stop-color: var(--svg-color--5d4c4b, #5D4C4B);
  stop-opacity: 0;
}

.je4t0yh1q {
  stop-color: var(--svg-color--2c151b, #2C151B);
}

.jkj1op9ie {
  stop-color: var(--svg-color--4edd83, #4EDD83);
  stop-opacity: 0;
}

.jvte3eb3p {
  stop-color: var(--svg-color--432e31, #432E31);
}

.jwxs8nbrt {
  stop-color: var(--svg-color--3d232d, #3D232D);
  stop-opacity: 0;
}

.jx01c6c2n {
  stop-color: var(--svg-color--08070d, #08070D);
}

.k_i-sob7k {
  fill: var(--svg-color--3b2a2a, #3B2A2A);
  d: path("M14.641 8.172a.95.95 0 1 0 0-1.902a.95.95 0 0 0 0 1.902");
}

.ke45y-bqc {
  stop-color: var(--svg-color--4c3b3d, #4C3B3D);
  stop-opacity: 0;
}

.kzknyvg9e {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.41 8.941a1.8 1.8 0 0 1-.84-.203c-.083-.044-.172.052-.12.13a1.142 1.142 0 0 0 1.92 0c.053-.08-.036-.174-.12-.13a1.8 1.8 0 0 1-.84.203Z");
}

.l2r6gabvx {
  fill: var(--svg-color--322026, #322026);
  d: path("M14.653 7.856a.635.635 0 1 0 0-1.27a.635.635 0 0 0 0 1.27");
}

.l85u8ibfx {
  fill: var(--svg-color--35bb78, #35BB78);
  d: path("M13.356 19.091c0-1.425.76-2.101 1.16-2.242l5.66-.34c1.61.719 2.954 2.781 3.141 5.281c.188 2.5-.203 4.954-2.265 6.563c-1.65 1.287-3.959 1.552-4.938 1.531H13.64c-2.625 0-3.246-1.89-3.355-2.297a11 11 0 0 0-.184-.598a.43.43 0 0 0-.221-.26c-.528-.244-1.521-.486-1.947-1.388a3.1 3.1 0 0 1-.28-1.63c.022-.213.232-.344.44-.296c.52.119.951.252 1.57.567a3.4 3.4 0 0 1 1.238 1.226c.065.11.238.112.304.003c.206-.342.561-.818 1.045-1.12a4.7 4.7 0 0 1 1.846-.678a.347.347 0 0 1 .387.345c.037 1.765-.748 2.275-1.198 2.513c-.288.131-.62.277-.866.388c-.139.063-.208.223-.14.36c.474.956 1.468.87 2.858.87c1.851 0 2.96-1.325 2.843-2.724c-.062-1.812-1.562-2.515-2.57-3.148c-.523-.328-2.055-1.145-2.055-2.926");
}

.lby3v6ati {
  d: path("M6.762 16.042a.486.486 0 1 1 .973 0v.775a.486.486 0 0 1-.973 0z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ls21dtb6x {
  stop-color: var(--svg-color--422c2e, #422C2E);
  stop-opacity: 0;
}

.lzwk4mb-k {
  stop-color: var(--svg-color--4b3a3b, #4B3A3B);
  stop-opacity: 0;
}

.m4pcayl4x {
  d: path("M21.317 26.665c0-5.343-3.922-7.968-5.234-9l3.25-1.453c1.125.521 3.035 2.358 3.453 5.11c.484 3.187-.927 4.927-1.469 5.343");
}

.m6q1utbkt {
  stop-color: var(--svg-color--41393c, #41393C);
}

.mk_tesa_t {
  stop-color: var(--svg-color--49c4fa, #49C4FA);
}

.ml6o-6oro {
  d: path("M14.404 6.475h.007l-.006-.157l-.006-.181c.012-.56.34-.778.479-.85l.03-.012l.03-.012c.316-.145.57-.398.704-.73l.048-.114a.156.156 0 0 1 .273-.03a2.28 2.28 0 0 0 1.885.988h1.902c.107 0 .64.052.672.788l-.07 1.816c-.073 1.656-1.367 2.768-2.945 2.768c-1.58 0-2.872-1.112-2.945-2.768z");
}

.mlaeyedlj {
  stop-color: var(--svg-color--3b292b, #3B292B);
}

.mo0n2bbuy {
  stop-color: var(--svg-color--544440, #544440);
}

.mpgqmibea {
  stop-color: var(--svg-color--4b3a3b, #4B3A3B);
}

.n7-hw2b3h {
  stop-color: var(--svg-color--9f7ada, #9F7ADA);
  stop-opacity: 0;
}

.n88-o7gbs {
  stop-color: var(--svg-color--462c31, #462C31);
  stop-opacity: 0;
}

.naoj9jbij {
  stop-color: var(--svg-color--544340, #544340);
  stop-opacity: 0;
}

.ndh-ggbqf {
  stop-color: var(--svg-color--544340, #544340);
}

.nibdu3-2v {
  stop-color: var(--svg-color--5d504f, #5D504F);
}

.nl_8d1b0i {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.66 6.698c.038.05-.04.111-.13.178c-.088.066-.154.113-.191.063s.004-.145.093-.211c.089-.067.191-.08.229-.03");
}

.nl2u64eej {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M8.845 24.429c.41.162 1.402.783 2.097 1.97");
}

.nq4i4cc1a {
  stop-color: var(--svg-color--3b292b, #3B292B);
  stop-opacity: 0;
}

.o0eqsac9n {
  d: path("M16.12 6.586a.527.527 0 0 0-.508.667h1.018a.53.53 0 0 0-.51-.666");
}

.o0h7y_boi {
  stop-color: var(--svg-color--45beff, #45BEFF);
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o5bua8boy {
  stop-color: var(--svg-color--45c0ff, #45C0FF);
}

.o5s5w9tej {
  stop-color: var(--svg-color--3f242e, #3F242E);
}

.o87uryobz {
  d: path("M20.263 8.172a.95.95 0 1 0 0-1.902a.95.95 0 0 0 0 1.902");
}

.oc32bubbt {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M18.085 6.884c.157-.275.396-.493.909-.493a.98.98 0 0 1 .634.218c.159.128.137.292.014.354l-.328.187c-.385-.124-.811-.141-1.229-.266");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.og8s_xbdj {
  stop-color: var(--svg-color--4c4141, #4C4141);
  stop-opacity: 0;
}

.ox07i09hz {
  stop-color: var(--svg-color--472c29, #472C29);
}

.p_-rkibqb {
  stop-color: var(--svg-color--08070d, #08070D);
  stop-opacity: 0;
}

.p51s2s65u {
  fill: var(--svg-color--2a0219, #2A0219);
  d: path("M17.41 8.941a1.8 1.8 0 0 1-.84-.203c-.083-.044-.172.052-.12.13a1.142 1.142 0 0 0 1.92 0c.053-.08-.036-.174-.12-.13a1.8 1.8 0 0 1-.84.203");
}

.p6977lbwx {
  d: path("M25.054 9.557c.399-.066.488-.33.488-.501v-.535a.184.184 0 0 1 .367 0v4.93a.527.527 0 0 1-1.055 0V9.77c0-.11.09-.197.2-.214");
}

.p8v9kob2h {
  stop-color: var(--svg-color--554241, #554241);
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pay0dfbkl {
  stop-color: var(--svg-color--413131, #413131);
  stop-opacity: 0;
}

.pf7v1soqz {
  stop-color: var(--svg-color--080608, #080608);
  stop-opacity: 0;
}

.pfckoacfq {
  fill: var(--svg-color--3f2c2f, #3F2C2F);
  d: path("M20.263 7.856a.635.635 0 1 0 0-1.27a.635.635 0 0 0 0 1.27");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ps08ktb6i {
  stop-color: var(--svg-color--342325, #342325);
}

.q2m7q-bcq {
  d: path("M15.62 4.556c-.22.565-1.18 1.028-1.61 1.14c-.142-1.143.301-2.523 1.702-2.274l.236.915c-.236-.066-.286.11-.328.219");
}

.qal7r2b_k {
  stop-color: var(--svg-color--2d1a26, #2D1A26);
}

.qdgeq05dx {
  d: path("M25.683 7.95h-.003a.53.53 0 0 0-.531.532v.5c0 .14-.14.234-.256.156a1.5 1.5 0 0 1-.238-.2c-.125-.129-.17-.309-.17-.488v-.546l.56-.558a.44.44 0 0 1 .638.605");
}

.qo67pbbye {
  stop-color: var(--svg-color--2e242a, #2E242A);
}

.qqxfe6pwj {
  stroke: var(--svg-color--262628, #262628);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M16.316 5.819c-.19-.047-.664-.024-.981.203");
}

.qxy_enyov {
  stop-color: var(--svg-color--1a0b0a, #1A0B0A);
}

.r13l5acqq {
  stop-color: var(--svg-color--3f242e, #3F242E);
  stop-opacity: 0;
}

.r4mhscsqa {
  stop-color: var(--svg-color--5f504f, #5F504F);
}

.rd_1vj1uu {
  stop-color: var(--svg-color--9971db, #9971DB);
}

.rggh3hbuf {
  d: path("M18.66 6.698c.038.05-.04.111-.13.178c-.088.066-.154.113-.191.063s.004-.145.093-.211c.089-.067.191-.08.229-.03");
}

.ro7svqvjx {
  fill: var(--svg-color--000, #000);
  d: path("M18.399 7.113a.3.3 0 0 1 .302-.302a.3.3 0 0 1 .269.441h-.535a.3.3 0 0 1-.036-.139");
}

.rvgjtg4fi {
  d: path("M20.726 13.688v3.421a.65.65 0 0 1-.65.65H14.75a.65.65 0 0 1-.65-.65v-2.75l-1.953 1.697a2.5 2.5 0 0 1-1.64.613h-1.84l-.612.527a.527.527 0 0 1-.716-.774l.317-.316a.1.1 0 0 0-.019-.154l-.018-.011a.384.384 0 0 0-.476.065l-.554.583a.526.526 0 0 1-.776-.71l.755-.857a.98.98 0 0 1 .621-.326l3.069-.355a.5.5 0 0 0 .284-.132l3.247-3.04c.889-.89 2.57-.98 3.735-.98c1.495 0 2.532.234 3.2.574l2.862 1.473a.202.202 0 0 0 .293-.16c.049-.5.132-1.271.197-1.853a.2.2 0 0 0-.046-.15l-.373-.445a1 1 0 0 1-.235-.644V7.783a.531.531 0 0 1 1.062 0v.667c0 .18.045.36.17.488c.065.067.145.137.239.2c.116.078.255-.016.255-.156v-.5a.531.531 0 1 1 1.063 0v1.39l.015.703c.019.846.042 1.907.088 2.883c.03.64-.263 1.255-.79 1.618a1.8 1.8 0 0 1-1.84.121z");
}

.rw2c-304f {
  stop-color: var(--svg-color--4d494b, #4D494B);
}

.rz_b8bbbi {
  stop-color: var(--svg-color--45c0ff, #45C0FF);
  stop-opacity: 0;
}

.s536pit3i {
  stop-color: var(--svg-color--4dcd7d, #4DCD7D);
}

.s9ajizb_e {
  stop-color: var(--svg-color--45beff, #45BEFF);
  stop-opacity: 0;
}

.sbjlvwbre {
  stop-color: var(--svg-color--211014, #211014);
}

.sdf9tobyx {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.997 6.425a.825.825 0 0 0-.8.626a.162.162 0 0 0 .158.201h1.318a.136.136 0 0 0 .135-.16a.83.83 0 0 0-.81-.667");
}

.se4ekfbko {
  stop-color: var(--svg-color--422c2e, #422C2E);
}

.sohh290zz {
  stop-color: var(--svg-color--2d1a26, #2D1A26);
  stop-opacity: 0;
}

.sui4c2hzy {
  stop-color: var(--svg-color--422f2f, #422F2F);
  stop-opacity: 0;
}

.t2ck-pbsh {
  cx: 15.959px;
  cy: 6.811px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.229px;
  ry: 0.116px;
}

.tla-kpu2g {
  stop-color: var(--svg-color--452d30, #452D30);
}

.tqn-xwbko {
  stop-color: var(--svg-color--3f3838, #3F3838);
}

.tvq_fsbne {
  stop-color: var(--svg-color--5c4b4a, #5C4B4A);
  stop-opacity: 0;
}

.u_kx35bmm {
  stop-color: var(--svg-color--20122b, #20122B);
}

.u-uq4ccbs {
  stop-color: var(--svg-color--20122b, #20122B);
  stop-opacity: 0;
}

.ubz5oeoiz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.991 23.91c-.307.352-1.133 1.1-1.885 1.832");
}

.uc2wxkyln {
  stop-color: var(--svg-color--40b87c, #40B87C);
  stop-opacity: 0;
}

.ugp4i7b_e {
  stop-color: var(--svg-color--5d4c4b, #5D4C4B);
}

.utkhftb9q {
  cx: 15.959px;
  cy: 6.811px;
  rx: 0.229px;
  ry: 0.116px;
}

.uyl0babqk {
  stop-color: var(--svg-color--422f2f, #422F2F);
}

.uzwc_ugjd {
  stop-color: var(--svg-color--3d222e, #3D222E);
}

.v3hxs-buk {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M16.736 6.884c-.157-.275-.396-.493-.909-.493a.98.98 0 0 0-.634.218c-.159.128-.137.292-.014.354l.328.187c.385-.124.811-.141 1.229-.266");
}

.vckbn7bgk {
  d: path("m17.184 7.007l-.314 1.005a.32.32 0 0 0 .308.413h.465a.32.32 0 0 0 .307-.413l-.314-1.005c-.067-.222-.381-.222-.452 0");
}

.vpkiteigl {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M24.085 7.63v1.248c0 .066.026.13.073.177l.26.26");
}

.vsknd5b9t {
  d: path("M9.91 15.744c1.812 1.575 4.202 1.213 5.171.875v-4.626h7.234c.517-1.326.156-2.452-.236-3.066a.28.28 0 0 1-.029-.24c.082-.236.193-.616.207-.916c.031-.66-.172-.707-.192-1.613c-.02-.907-.306-1.241-.78-2.016c-.384-.625-1.372-1.031-1.974-1.27c-.66-.261-.894-.757-1.89-.757c-.77 0-1.277.39-1.626.729a.85.85 0 0 1-.48.23c-1.223.163-2.266.735-2.843 1.802c-.338.626-.369 1.608-.365 2.282a.53.53 0 0 1-.42.513c-1.53.345-2.65 1.23-3.18 2.233c-.578 1.093-.863 3.87 1.402 5.84");
}

.w_bi9zfnz {
  stop-color: var(--svg-color--724c46, #724C46);
}

.w_uqfvbai {
  stroke: var(--svg-color--262628, #262628);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M18.557 5.819c.19-.047.664-.024.981.203");
}

.w4wjacb9v {
  stop-color: var(--svg-color--8c60d5, #8C60D5);
  stop-opacity: 0;
}

.wliqnbp1k {
  d: path("M14.09 13.15a.4.4 0 0 0-.4.4v1.128a1.3 1.3 0 0 0 1.3 1.3h4.846a1.3 1.3 0 0 0 1.3-1.3V13.55a.4.4 0 0 0-.4-.4h-1.842a1.5 1.5 0 0 0-1.377.904c-.027.062-.18.062-.207 0a1.5 1.5 0 0 0-1.377-.904z");
}

.ws4l7vbtn {
  stop-color: var(--svg-color--3c3437, #3C3437);
}

.wv0cm2xvj {
  stop-color: var(--svg-color--4c3b3d, #4C3B3D);
}

.wysa1pg4b {
  stop-color: var(--svg-color--261c20, #261C20);
}

.x2e_pmc0g {
  d: path("M16.6 7.05c0-.17-.138-.283-.175-.317l-.17.164l.104.213z");
}

.xbecpqbnm {
  stop-color: var(--svg-color--110b17, #110B17);
  stop-opacity: 0;
}

.xg7_958fc {
  stop-color: var(--svg-color--5c4b4a, #5C4B4A);
}

.xs_unubla {
  stop-color: var(--svg-color--080608, #080608);
}

.xy7wgkblp {
  stop-color: var(--svg-color--110b17, #110B17);
}

.y_rv32tfd {
  stop-color: var(--svg-color--40b87c, #40B87C);
}

.y543bybjo {
  stop-color: var(--svg-color--4c4141, #4C4141);
}

.y6bb5ubdl {
  stop-color: var(--svg-color--4c322f, #4C322F);
}

.yf02b6ygm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M11.429 26.864c-.007.65.436 1.948 2.266 1.948h3.177c1.01-.014 3.316-.516 4.469-2.414");
}

.yffwppb7t {
  stop-color: var(--svg-color--463847, #463847);
  stop-opacity: 0;
}

.yk-s_4bpi {
  stop-color: var(--svg-color--413131, #413131);
}

.yo-rx8c0q {
  d: path("M19.17 7.043a.5.5 0 0 0-.137-.272l-.152.167l.069.135z");
}

.z3skqac1h {
  stop-color: var(--svg-color--462c31, #462C31);
}

.zyxzx5bbz {
  stop-color: var(--svg-color--452d30, #452D30);
  stop-opacity: 0;
}

.zzrbad3ti {
  stop-color: var(--svg-color--4d494b, #4D494B);
  stop-opacity: 0;
}

</style>
