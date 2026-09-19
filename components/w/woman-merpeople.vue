<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iIhruVd)"><path fill="url(#iwePCqd)" class="vsknd5b9t"/><path fill="url(#iiiPGmd)" class="vsknd5b9t"/><path fill="url(#i2NxOIc)" class="vsknd5b9t"/><path fill="url(#i62uNfc)" class="vsknd5b9t"/><path fill="url(#iBw3mle)" class="vsknd5b9t"/><path fill="url(#iwTZFQD)" class="vsknd5b9t"/><path fill="url(#iZbMeYb)" class="vsknd5b9t"/><path fill="url(#iqOFWsd)" class="vsknd5b9t"/></g><g filter="url(#ihb91Sb)"><path class="l85u8ibfx"/></g><path fill="url(#imdrOid)" class="d804zky3u"/><g filter="url(#iw6PiJc)"><path fill="url(#iOxYU2b)" class="m4pcayl4x"/></g><path fill="url(#io2a1Fc)" class="lby3v6ati"/><g filter="url(#iB2cGxb)"><path fill="url(#i5Sooac)" class="qdgeq05dx"/></g><g filter="url(#isG3Dkq)"><path fill="url(#i5B8bJd)" class="rvgjtg4fi"/><path fill="url(#i3vfPjc)" class="rvgjtg4fi"/><path fill="url(#iq0rCVW)" class="rvgjtg4fi"/><path fill="url(#iqPEHqb)" class="rvgjtg4fi"/><path fill="url(#iluXJmv)" class="rvgjtg4fi"/><path fill="url(#ijM8VZO)" class="rvgjtg4fi"/><path fill="url(#iPm9VvM)" class="rvgjtg4fi"/><path fill="url(#iZ8nbKb)" class="rvgjtg4fi"/><path fill="url(#i8NO7bd)" class="rvgjtg4fi"/></g><path fill="url(#i7EOSCl)" class="rvgjtg4fi"/><g filter="url(#iACFI7b)"><path stroke="url(#iI9sDUb)" class="yf02b6ygm"/></g><g filter="url(#i5gJBhI)"><path stroke="url(#iUUCLJd)" class="nl2u64eej"/></g><g filter="url(#iABGHyc)"><path stroke="url(#iDbcAtn)" class="ubz5oeoiz"/></g><g filter="url(#iFSd33b)"><path class="pm-mvbcfp"/></g><g filter="url(#icI5jgx)"><path class="lteraocnl"/><path fill="url(#iO96kgc)" class="wliqnbp1k"/><path fill="url(#iAr2xub)" class="wliqnbp1k"/><path fill="url(#iyPwIbP)" class="wliqnbp1k"/></g><g filter="url(#iKqFmwb)"><path class="vp72o-bak"/></g><path fill="url(#iKZ15Bd)" class="o87uryobz"/><g filter="url(#iZWKxDe)"><path class="p_t0wkgjg"/></g><g filter="url(#iLl4m0b)"><path class="jffvhcc9u"/></g><g filter="url(#iSlCBQN)"><path fill="url(#iYOjbre)" class="ml6o-6oro"/></g><path fill="url(#i2Sa9cc)" class="ml6o-6oro"/><path fill="url(#imtbWIb)" class="ml6o-6oro"/><path fill="url(#iUspT1d)" class="ml6o-6oro"/><path fill="url(#iV2fckb)" class="ml6o-6oro"/><g filter="url(#ijpq1rd)"><path class="fa9pnxywj"/></g><path class="a5h3_w6vt"/><path fill="url(#ibgFB7b)" class="vckbn7bgk"/><path fill="url(#ii3CYLW)" class="vckbn7bgk"/><path fill="url(#ipnRe9d)" class="vckbn7bgk"/><g filter="url(#iv6wfcA)"><path stroke="url(#iNsVade)" class="ynjbm96er"/></g><path class="xonyy5bvc"/><g filter="url(#isFBDcy)"><path class="oc32bubbt"/></g><g filter="url(#imNxDOe)"><path class="v3hxs-buk"/></g><g filter="url(#isw04oc)"><path class="m6evu0byd"/></g><g filter="url(#iz0LB4d)"><path clip-rule="evenodd" class="nr9au_--r"/></g><path class="ivaw61bob"/><path fill="url(#iWnBGQb)" class="akquh7bgt"/><path class="ro7svqvjx"/><g filter="url(#iFWv7hN)"><path class="nl_8d1b0i"/><path fill="url(#i2LqhIf)" class="rggh3hbuf"/></g><g filter="url(#ipE3J8d)"><path fill="url(#idDVUGc)" class="yo-rx8c0q"/></g><path class="sdf9tobyx"/><path fill="url(#ik7Aq1M)" class="o0eqsac9n"/><path class="eiflvuzgd"/><g filter="url(#irT68eg)"><path fill="url(#i1cZLfc)" class="x2e_pmc0g"/></g><g filter="url(#iT2qZlp)"><ellipse transform="rotate(-27.914 15.96 6.811)" class="t2ck-pbsh"/><ellipse fill="url(#iNxWnMx)" transform="rotate(-27.914 15.96 6.811)" class="utkhftb9q"/></g><g filter="url(#iFOe5oc)"><path class="kvncffg3l"/></g><g filter="url(#iFfENFc)"><path class="d0_r1omcd"/></g><g filter="url(#iIp7yjb)"><path fill="url(#iMrczGe)" class="q2m7q-bcq"/><path fill="url(#iy30kNd)" class="q2m7q-bcq"/></g><g filter="url(#ivKH6Md)"><path fill="url(#igiRPBb)" class="iwu7gdsah"/></g><g filter="url(#iKb4JMe)"><path fill="url(#igWLRcd)" class="i1dtc041h"/><path fill="url(#i8RH6Id)" class="i1dtc041h"/><path fill="url(#iDNQCdx)" class="i1dtc041h"/><path fill="url(#iCGioVS)" class="i1dtc041h"/></g><g filter="url(#iK50uhb)"><path class="iorvdubip"/><path fill="url(#ibrXHpJ)" class="inz52_phe"/><path fill="url(#iII9RCc)" class="inz52_phe"/><path fill="url(#ihEBcfc)" class="inz52_phe"/></g><g filter="url(#iL4XRNc)"><path class="thj442bmz"/></g><defs><radialGradient id="iwePCqd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.56252 4.21874 -6.12104 -3.718 21.024 3.26)" gradientUnits="userSpaceOnUse"><stop class="dthvnjbka"/><stop offset="1" class="ohwkd8wyz"/></radialGradient><radialGradient id="iiiPGmd" cx="0" cy="0" r="1" gradientTransform="matrix(7.15633 -13.4342 24.24607 12.91576 11.291 16.912)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="r9a_520ft"/><stop offset="1" class="bo441_3xf"/></radialGradient><radialGradient id="i2NxOIc" cx="0" cy="0" r="1" gradientTransform="rotate(144.219 4.695 10.165)scale(4.27577 3.3172)" gradientUnits="userSpaceOnUse"><stop class="zmc2y0hrn"/><stop offset="1" class="gmfdwsbvv"/></radialGradient><radialGradient id="i62uNfc" cx="0" cy="0" r="1" gradientTransform="rotate(-26.896 31.135 -34.786)scale(4.83558 4.72975)" gradientUnits="userSpaceOnUse"><stop class="cbkswf6-m"/><stop offset="1" class="zn6johb1n"/></radialGradient><radialGradient id="iBw3mle" cx="0" cy="0" r="1" gradientTransform="rotate(83.177 2.967 13.177)scale(3.68233 3.00341)" gradientUnits="userSpaceOnUse"><stop offset=".305" class="fu3hkmb1l"/><stop offset="1" class="whiqcnb7o"/></radialGradient><radialGradient id="iwTZFQD" cx="0" cy="0" r="1" gradientTransform="rotate(138.753 4.949 8.646)scale(6.92018 1.68373)" gradientUnits="userSpaceOnUse"><stop offset=".458" class="eoyzs8bag"/><stop offset="1" class="t57u5vsaf"/></radialGradient><radialGradient id="iZbMeYb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.59372 4.50004 -1.36243 -1.69355 14.792 3.134)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="hedy6dh6n"/><stop offset="1" class="msb_mlodm"/></radialGradient><radialGradient id="iqOFWsd" cx="0" cy="0" r="1" gradientTransform="matrix(.98438 1.5625 -1.81496 1.14342 16.073 2.415)" gradientUnits="userSpaceOnUse"><stop class="beae66v4n"/><stop offset="1" class="hg-m2ebmh"/></radialGradient><radialGradient id="imdrOid" cx="0" cy="0" r="1" gradientTransform="rotate(-17.313 87.674 -23.135)scale(13.0953 16.0195)" gradientUnits="userSpaceOnUse"><stop offset=".805" class="g1dp7ccjz"/><stop offset="1" class="s536pit3i"/></radialGradient><radialGradient id="iOxYU2b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.61906 1.93752 -6.36477 -11.88867 22.702 20.572)" gradientUnits="userSpaceOnUse"><stop class="h8_lbz_nz"/><stop offset="1" class="jkj1op9ie"/></radialGradient><radialGradient id="io2a1Fc" cx="0" cy="0" r="1" gradientTransform="matrix(.67968 -.9375 .55678 .40367 6.762 16.9)" gradientUnits="userSpaceOnUse"><stop class="mkkd392fx"/><stop offset="1" class="uukk9e6th"/></radialGradient><radialGradient id="i5Sooac" cx="0" cy="0" r="1" gradientTransform="matrix(-.68567 .5 -.27415 -.37595 25.693 7.447)" gradientUnits="userSpaceOnUse"><stop class="ts5vg6ilu"/><stop offset="1" class="pltv3850l"/></radialGradient><radialGradient id="i5B8bJd" cx="0" cy="0" r="1" gradientTransform="rotate(159 8.58 8.058)scale(4.71973 6.48913)" gradientUnits="userSpaceOnUse"><stop class="zxdg24bmw"/><stop offset="1" class="fg_8_f19k"/></radialGradient><radialGradient id="iq0rCVW" cx="0" cy="0" r="1" gradientTransform="matrix(2.09375 0 0 4.11135 14.48 17.197)" gradientUnits="userSpaceOnUse"><stop offset=".075" class="ox3lchxkt"/><stop offset="1" class="kv1epbcdk"/></radialGradient><radialGradient id="iqPEHqb" cx="0" cy="0" r="1" gradientTransform="rotate(-124.961 15.728 2.092)scale(7.03516 2.62961)" gradientUnits="userSpaceOnUse"><stop offset=".281" class="zbh51bctq"/><stop offset="1" class="jyrqxvbae"/></radialGradient><radialGradient id="iluXJmv" cx="0" cy="0" r="1" gradientTransform="matrix(1.14062 3.15625 -1.12664 .40715 23.76 10.838)" gradientUnits="userSpaceOnUse"><stop class="b8kbmpg3m"/><stop offset="1" class="mmnqgv5yf"/></radialGradient><radialGradient id="ijM8VZO" cx="0" cy="0" r="1" gradientTransform="matrix(-.90625 -1.5 1.25 -.7552 15.612 13.86)" gradientUnits="userSpaceOnUse"><stop class="y1xxtut2l"/><stop offset="1" class="wttyue-hr"/></radialGradient><radialGradient id="iPm9VvM" cx="0" cy="0" r="1" gradientTransform="matrix(-.49998 -1.89063 3.41696 -.90363 24.964 15.493)" gradientUnits="userSpaceOnUse"><stop offset=".117" class="qofl2v1ay"/><stop offset="1" class="gdy5r2p-p"/></radialGradient><radialGradient id="iZ8nbKb" cx="0" cy="0" r="1" gradientTransform="rotate(157.19 7.611 6.63)scale(3.62742 2.32226)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="y-anmyn4x"/><stop offset="1" class="lmbl5xbig"/></radialGradient><radialGradient id="i8NO7bd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.24998 1.9844 -1.20668 -1.36818 13.682 14.9)" gradientUnits="userSpaceOnUse"><stop class="chidanbix"/><stop offset="1" class="lqdtz47lo"/></radialGradient><radialGradient id="iO96kgc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.17187 -1.23438 .5687 -.5399 16.852 14.384)" gradientUnits="userSpaceOnUse"><stop class="rd_1vj1uu"/><stop offset="1" class="w4wjacb9v"/></radialGradient><radialGradient id="iAr2xub" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.26562 -.57617 0 17.413 13.306)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="ookdrzgqt"/><stop offset="1" class="zku_rzyyo"/></radialGradient><radialGradient id="iyPwIbP" cx="0" cy="0" r="1" gradientTransform="matrix(-1.4707 1.41406 -.31529 -.32792 21.136 13.15)" gradientUnits="userSpaceOnUse"><stop class="gwqfskb8v"/><stop offset="1" class="n7-hw2b3h"/></radialGradient><radialGradient id="iKZ15Bd" cx="0" cy="0" r="1" gradientTransform="matrix(-.81766 1.38906 -1.0886 -.6408 21.08 6.783)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="nz73gfbvi"/><stop offset="1" class="tim_a1bwu"/></radialGradient><radialGradient id="iYOjbre" cx="0" cy="0" r="1" gradientTransform="matrix(-3.03126 1.72424 -2.40572 -4.22933 18.573 7.535)" gradientUnits="userSpaceOnUse"><stop class="qn752-99j"/><stop offset="1" class="jf7dy-bqd"/></radialGradient><radialGradient id="i2Sa9cc" cx="0" cy="0" r="1" gradientTransform="matrix(-.44374 4.58332 -6.0454 -.58529 17.854 6.166)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="ofvzbdbov"/><stop offset="1" class="sstkyybun"/></radialGradient><radialGradient id="imtbWIb" cx="0" cy="0" r="1" gradientTransform="rotate(146.659 9.247 5.584)scale(1.42145 2.26202)" gradientUnits="userSpaceOnUse"><stop class="f7fwsckbf"/><stop offset="1" class="u0bnb-zsr"/></radialGradient><radialGradient id="iUspT1d" cx="0" cy="0" r="1" gradientTransform="rotate(74.252 5.23 12.839)scale(3.33917 5.262)" gradientUnits="userSpaceOnUse"><stop class="oqvigc69j"/><stop offset="1" class="iwusohbtz"/></radialGradient><radialGradient id="iV2fckb" cx="0" cy="0" r="1" gradientTransform="matrix(.59375 1.01563 -1.67562 .97958 15.73 4.212)" gradientUnits="userSpaceOnUse"><stop class="d_kww-htp"/><stop offset="1" class="q6rrzt8xr"/></radialGradient><radialGradient id="ii3CYLW" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.39263 1.04529 0 17.41 8.425)" gradientUnits="userSpaceOnUse"><stop offset=".244" class="ysp-lfbbx"/><stop offset="1" class="it3vh_mph"/></radialGradient><radialGradient id="iWnBGQb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .47945 -.76262 0 18.7 6.868)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i2LqhIf" cx="0" cy="0" r="1" gradientTransform="matrix(-.13647 -.17586 .24212 -.18789 18.564 6.918)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ik7Aq1M" cx="0" cy="0" r="1" gradientTransform="matrix(0 .47945 -.76262 0 16.121 6.868)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iNxWnMx" cx="0" cy="0" r="1" gradientTransform="matrix(-.00455 -.29073 .34947 -.00547 15.95 6.997)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iMrczGe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.98437 1.60938 -.62216 -.76713 15.589 4.087)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="bdcn3wmwt"/><stop offset=".77" class="oxhj8dfqw"/></radialGradient><radialGradient id="iy30kNd" cx="0" cy="0" r="1" gradientTransform="matrix(-.57032 -1.67187 3.32715 -1.13499 15.714 4.962)" gradientUnits="userSpaceOnUse"><stop offset=".81" class="vw-gsnb-j"/><stop offset="1" class="wdg5-_bwz"/></radialGradient><radialGradient id="igiRPBb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.46875 .08792 -.04263 -1.68195 19.76 4.138)" gradientUnits="userSpaceOnUse"><stop class="p8wuxeb4t"/><stop offset="1" class="ic9gf7fhi"/></radialGradient><radialGradient id="igWLRcd" cx="0" cy="0" r="1" gradientTransform="matrix(-.88282 -.8203 .46947 -.50525 20.292 4.744)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="nv-3lfz3i"/><stop offset="1" class="y8hb2-0cv"/></radialGradient><radialGradient id="iDNQCdx" cx="0" cy="0" r="1" gradientTransform="matrix(.74219 .69531 -.47672 .50886 20.12 5.369)" gradientUnits="userSpaceOnUse"><stop class="iny0fpg3p"/><stop offset="1" class="wgxxd_b3o"/></radialGradient><radialGradient id="iCGioVS" cx="0" cy="0" r="1" gradientTransform="rotate(-93.956 11.058 -5.312)scale(2.94451 6.47668)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="kqwofjbvr"/><stop offset="1" class="tfu66nomq"/></radialGradient><radialGradient id="ibrXHpJ" cx="0" cy="0" r="1" gradientTransform="matrix(.20313 1.2422 -.5655 .09247 21.027 3.806)" gradientUnits="userSpaceOnUse"><stop class="mk_tesa_t"/><stop offset="1" class="hj78b9cjo"/></radialGradient><radialGradient id="iII9RCc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.11657 .3125 -.09737 -.3479 22.346 4.681)" gradientUnits="userSpaceOnUse"><stop class="o5bua8boy"/><stop offset="1" class="rz_b8bbbi"/></radialGradient><radialGradient id="ihEBcfc" cx="0" cy="0" r="1" gradientTransform="matrix(-.59375 -1.38766 .70345 -.301 21.932 6.494)" gradientUnits="userSpaceOnUse"><stop class="o0h7y_boi"/><stop offset="1" class="s9ajizb_e"/></radialGradient><filter id="iIhruVd" width="14.674" height="15.298" x="7.898" y="1.615" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.396078 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1288"/></filter><filter id="ihb91Sb" width="16.97" height="13.626" x="7.639" y="16.259" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1288"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.576471 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1288" result="effect2_innerShadow_4002_1288"/></filter><filter id="iw6PiJc" width="8.803" height="12.453" x="15.083" y="15.212" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1288" stdDeviation=".5"/></filter><filter id="iB2cGxb" width="1.41" height="1.949" x="24.485" y="7.218" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.607843 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1288"/></filter><filter id="isG3Dkq" width="20.634" height="10.708" x="5.683" y="7.051" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.796078 0 0 0 0 0.513726 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1288"/></filter><filter id="iACFI7b" width="11.112" height="3.615" x="10.829" y="25.798" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1288" stdDeviation=".2"/></filter><filter id="i5gJBhI" width="3.297" height="3.17" x="8.245" y="23.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1288" stdDeviation=".2"/></filter><filter id="iABGHyc" width="3.085" height="3.032" x="11.506" y="23.31" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1288" stdDeviation=".2"/></filter><filter id="iFSd33b" width="6.547" height="2.797" x="14.14" y="13.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1288" stdDeviation=".125"/></filter><filter id="icI5jgx" width="7.845" height="3.428" x="13.691" y="12.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.305882 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1288"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.568627 0 0 0 0 0.388235 0 0 0 0 0.745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1288" result="effect2_innerShadow_4002_1288"/></filter><filter id="iKqFmwb" width="2.002" height="1.902" x="13.691" y="6.27" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.890196 0 0 0 0 0.6 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1288"/></filter><filter id="iZWKxDe" width="1.669" height="1.669" x="19.428" y="6.386" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1288" stdDeviation=".1"/></filter><filter id="iLl4m0b" width="1.569" height="1.569" x="13.868" y="6.436" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1288" stdDeviation=".075"/></filter><filter id="iSlCBQN" width="6.422" height="6.428" x="14.399" y="4.321" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.643137 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1288"/></filter><filter id="ijpq1rd" width="1.609" height="2.085" x="16.51" y="6.672" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1288" stdDeviation=".125"/></filter><filter id="iv6wfcA" width="2.352" height="1.065" x="16.235" y="8.527" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1288" stdDeviation=".05"/></filter><filter id="isFBDcy" width="1.855" height=".76" x="17.885" y="6.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1288"/></filter><filter id="imNxDOe" width="1.855" height=".76" x="15.08" y="6.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1288"/></filter><filter id="isw04oc" width="1.531" height=".727" x="15.16" y="5.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1288"/></filter><filter id="iz0LB4d" width="1.531" height=".727" x="18.361" y="5.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1288"/></filter><filter id="iFWv7hN" width=".545" height=".492" x="18.225" y="6.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1288" stdDeviation=".05"/></filter><filter id="ipE3J8d" width=".689" height=".702" x="18.68" y="6.571" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1288" stdDeviation=".1"/></filter><filter id="irT68eg" width=".745" height=".777" x="16.055" y="6.533" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1288" stdDeviation=".1"/></filter><filter id="iT2qZlp" width=".62" height=".497" x="15.65" y="6.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1288" stdDeviation=".05"/></filter><filter id="iFOe5oc" width="1.231" height=".473" x="18.431" y="5.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1288" stdDeviation=".05"/></filter><filter id="iFfENFc" width="1.231" height=".473" x="15.21" y="5.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1288" stdDeviation=".05"/></filter><filter id="iIp7yjb" width="2.163" height="2.504" x="13.885" y="3.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1288" stdDeviation=".05"/></filter><filter id="ivKH6Md" width="5.15" height="3.645" x="15.32" y="2.328" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.576471 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1288"/><feGaussianBlur result="effect2_foregroundBlur_4002_1288" stdDeviation=".05"/></filter><filter id="iKb4JMe" width="5.15" height="3.495" x="15.32" y="2.478" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1288" stdDeviation=".05"/></filter><filter id="iK50uhb" width="3.17" height="3.061" x="19.276" y="3.525" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.529412 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1288"/></filter><filter id="iL4XRNc" width="3.055" height="7.641" x="23.854" y="7.337" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1288" stdDeviation=".5"/></filter><linearGradient id="i3vfPjc" x1="8.135" x2="14.729" y1="16.572" y2="12.165" gradientUnits="userSpaceOnUse"><stop class="xjs25bcfc"/><stop offset="1" class="xmk1l3i-w"/></linearGradient><linearGradient id="i7EOSCl" x1="17.354" x2="17.354" y1="18.04" y2="16.384" gradientUnits="userSpaceOnUse"><stop offset=".113" class="y-w066bhd"/><stop offset="1" class="j1_qqi8-p"/></linearGradient><linearGradient id="iI9sDUb" x1="11.768" x2="20.875" y1="26.97" y2="28.813" gradientUnits="userSpaceOnUse"><stop class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="iUUCLJd" x1="10.518" x2="8.203" y1="25.763" y2="25.39" gradientUnits="userSpaceOnUse"><stop offset=".302" class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="iDbcAtn" x1="14.012" x2="13.482" y1="24.1" y2="26.21" gradientUnits="userSpaceOnUse"><stop class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="ibgFB7b" x1="17.873" x2="17.002" y1="7.806" y2="7.814" gradientUnits="userSpaceOnUse"><stop offset=".257" class="wjmq6tbsf"/><stop offset="1" class="uuxpnvfdu"/></linearGradient><linearGradient id="ipnRe9d" x1="17.452" x2="17.452" y1="8.455" y2="8.275" gradientUnits="userSpaceOnUse"><stop class="ph5dftb5v"/><stop offset="1" class="y1ow33bnn"/></linearGradient><linearGradient id="iNsVade" x1="16.98" x2="17.247" y1="9.352" y2="8.837" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="idDVUGc" x1="19.158" x2="18.974" y1="6.899" y2="7.013" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i1cZLfc" x1="16.559" x2="16.375" y1="6.899" y2="7.013" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i8RH6Id" x1="19.026" x2="19.026" y1="5.525" y2="5.009" gradientUnits="userSpaceOnUse"><stop class="whwvona8i"/><stop offset="1" class="h-9xzbcps"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-merpeople" /></template>
<style>
.a5h3_w6vt {
  fill: var(--svg-color--feb32a, #FEB32A);
  d: path("m17.184 7.007l-.314 1.005a.32.32 0 0 0 .308.413h.465a.32.32 0 0 0 .307-.413l-.314-1.005c-.067-.222-.381-.222-.452 0");
}

.akquh7bgt {
  d: path("M18.701 6.586a.527.527 0 0 1 .508.666H18.19a.53.53 0 0 1 .51-.666");
}

.b8kbmpg3m {
  stop-color: var(--svg-color--e38c1d, #E38C1D);
}

.bdcn3wmwt {
  stop-color: var(--svg-color--ffbc29, #FFBC29);
}

.beae66v4n {
  stop-color: var(--svg-color--cfa437, #CFA437);
}

.bo441_3xf {
  stop-color: var(--svg-color--fa871d, #FA871D);
  stop-opacity: 0;
}

.cbkswf6-m {
  stop-color: var(--svg-color--f78913, #F78913);
}

.chidanbix {
  stop-color: var(--svg-color--d1791d, #D1791D);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d_kww-htp {
  stop-color: var(--svg-color--d26d02, #D26D02);
}

.d0_r1omcd {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M16.316 5.819c-.19-.047-.664-.024-.981.203");
}

.d804zky3u {
  d: path("M13.356 19.091c0-1.425.76-2.101 1.16-2.242l5.66-.34c1.61.719 2.954 2.781 3.141 5.281c.188 2.5-.203 4.954-2.265 6.563c-1.65 1.287-3.959 1.552-4.938 1.531H13.64c-2.625 0-3.246-1.89-3.355-2.297a11 11 0 0 0-.184-.598a.43.43 0 0 0-.221-.26c-.528-.244-1.521-.486-1.947-1.388a3.1 3.1 0 0 1-.28-1.63c.022-.213.232-.344.44-.296c.52.119.951.252 1.57.567a3.4 3.4 0 0 1 1.238 1.226c.065.11.238.112.304.003c.206-.342.561-.818 1.045-1.12a4.7 4.7 0 0 1 1.846-.678a.347.347 0 0 1 .387.345c.037 1.765-.748 2.275-1.198 2.513c-.288.131-.62.277-.866.388c-.139.063-.208.223-.14.36c.474.956 1.468.87 2.858.87c1.851 0 2.96-1.325 2.843-2.724c-.062-1.812-1.562-2.515-2.57-3.148c-.523-.328-2.055-1.145-2.055-2.926");
}

.dthvnjbka {
  stop-color: var(--svg-color--ffdd36, #FFDD36);
}

.eiflvuzgd {
  fill: var(--svg-color--000, #000);
  d: path("M16.422 7.113a.3.3 0 0 0-.302-.302a.3.3 0 0 0-.269.442h.535a.3.3 0 0 0 .036-.14");
}

.eoyzs8bag {
  stop-color: var(--svg-color--e16e14, #E16E14);
}

.f7fwsckbf {
  stop-color: var(--svg-color--cc972e, #CC972E);
}

.fa9pnxywj {
  fill: var(--svg-color--f09f2f, #F09F2F);
  d: path("m17.179 7.09l-.404 1.004a.32.32 0 0 0 .307.413h.465a.32.32 0 0 0 .308-.413l-.314-1.005c-.068-.222-.292-.222-.363 0");
}

.fg_8_f19k {
  stop-color: var(--svg-color--ffb825, #FFB825);
}

.ft5dv1b6b {
  fill: none;
}

.fu3hkmb1l {
  stop-color: var(--svg-color--dc6c1f, #DC6C1F);
}

.g1dp7ccjz {
  stop-color: var(--svg-color--4dcd7d, #4DCD7D);
  stop-opacity: 0;
}

.gdy5r2p-p {
  stop-color: var(--svg-color--eda433, #EDA433);
  stop-opacity: 0;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gmfdwsbvv {
  stop-color: var(--svg-color--bb5b24, #BB5B24);
  stop-opacity: 0;
}

.gwqfskb8v {
  stop-color: var(--svg-color--9f7ada, #9F7ADA);
}

.h-9xzbcps {
  stop-color: var(--svg-color--ee9d23, #EE9D23);
  stop-opacity: 0;
}

.h8_lbz_nz {
  stop-color: var(--svg-color--4edd83, #4EDD83);
}

.hedy6dh6n {
  stop-color: var(--svg-color--f1b030, #F1B030);
}

.hg-m2ebmh {
  stop-color: var(--svg-color--cfa437, #CFA437);
  stop-opacity: 0;
}

.hj78b9cjo {
  stop-color: var(--svg-color--34affa, #34AFFA);
  stop-opacity: 0;
}

.i1dtc041h {
  d: path("M17.054 2.598c-.67-.148-1.564.586-1.633.833c.91 2.14 2.162 2.022 3.863 1.957c.944-.036.999.28 1.078.485c.156-2.688-1.783-2.938-3.308-3.275");
}

.ic9gf7fhi {
  stop-color: var(--svg-color--feb421, #FEB421);
}

.iny0fpg3p {
  stop-color: var(--svg-color--b06f20, #B06F20);
}

.inz52_phe {
  d: path("m21.018 3.79l.204.628c.03.09.12.16.22.16l.697.01c.21 0 .285.242.105.382l-.532.418c-.08.06-.11.16-.08.26l.198.658c.07.22-.146.36-.336.23l-.542-.398a.225.225 0 0 0-.27 0l-.551.399c-.19.13-.396-.01-.336-.23l.197-.66c.03-.1 0-.2-.08-.26l-.539-.397c-.18-.14-.097-.382.133-.382l.666-.01c.1 0 .19-.07.22-.16l.231-.648c.07-.23.325-.21.395 0");
}

.iorvdubip {
  fill: var(--svg-color--33aef9, #33AEF9);
  d: path("m21.018 3.79l.204.628c.03.09.12.16.22.16l.697.01c.21 0 .285.242.105.382l-.532.418c-.08.06-.11.16-.08.26l.198.658c.07.22-.146.36-.336.23l-.542-.398a.225.225 0 0 0-.27 0l-.551.399c-.19.13-.396-.01-.336-.23l.197-.66c.03-.1 0-.2-.08-.26l-.539-.397c-.18-.14-.097-.382.133-.382l.666-.01c.1 0 .19-.07.22-.16l.231-.648c.07-.23.325-.21.395 0");
}

.it3vh_mph {
  stop-color: var(--svg-color--f6a934, #F6A934);
  stop-opacity: 0;
}

.ivaw61bob {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.824 6.425c.385 0 .711.267.8.626a.162.162 0 0 1-.158.201h-1.319a.136.136 0 0 1-.134-.16a.826.826 0 0 1 .81-.667");
}

.iwu7gdsah {
  d: path("M17.054 2.598c-.67-.148-1.564.586-1.633.833c.91 2.14 2.14 2.001 3.841 1.937c.945-.036 1.02.3 1.1.505c.156-2.688-1.783-2.938-3.308-3.275");
}

.iwusohbtz {
  stop-color: var(--svg-color--f39c22, #F39C22);
  stop-opacity: 0;
}

.j1_qqi8-p {
  stop-color: var(--svg-color--f1b331, #F1B331);
  stop-opacity: 0;
}

.jf7dy-bqd {
  stop-color: var(--svg-color--f4aa35, #F4AA35);
}

.jffvhcc9u {
  fill: var(--svg-color--e38d22, #E38D22);
  d: path("M14.653 7.856a.635.635 0 1 0 0-1.27a.635.635 0 0 0 0 1.27");
}

.jkj1op9ie {
  stop-color: var(--svg-color--4edd83, #4EDD83);
  stop-opacity: 0;
}

.jyrqxvbae {
  stop-color: var(--svg-color--ffc128, #FFC128);
  stop-opacity: 0;
}

.kqwofjbvr {
  stop-color: var(--svg-color--cea639, #CEA639);
  stop-opacity: 0;
}

.kv1epbcdk {
  stop-color: var(--svg-color--efa62d, #EFA62D);
  stop-opacity: 0;
}

.kvncffg3l {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M18.557 5.819c.19-.047.664-.024.981.203");
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

.lmbl5xbig {
  stop-color: var(--svg-color--f4a71e, #F4A71E);
  stop-opacity: 0;
}

.lqdtz47lo {
  stop-color: var(--svg-color--eaa131, #EAA131);
  stop-opacity: 0;
}

.lteraocnl {
  fill: var(--svg-color--8c60d5, #8C60D5);
  d: path("M14.09 13.15a.4.4 0 0 0-.4.4v1.128a1.3 1.3 0 0 0 1.3 1.3h4.846a1.3 1.3 0 0 0 1.3-1.3V13.55a.4.4 0 0 0-.4-.4h-1.842a1.5 1.5 0 0 0-1.377.904c-.027.062-.18.062-.207 0a1.5 1.5 0 0 0-1.377-.904z");
}

.m4pcayl4x {
  d: path("M21.317 26.665c0-5.343-3.922-7.968-5.234-9l3.25-1.453c1.125.521 3.035 2.358 3.453 5.11c.484 3.187-.927 4.927-1.469 5.343");
}

.m6evu0byd {
  fill: var(--svg-color--bd4f26, #BD4F26);
  d: path("m15.402 6.17l-.002.002a.159.159 0 0 1-.163-.272l.002-.002l.006-.003l.02-.01q.024-.015.068-.035c.058-.028.141-.064.242-.096c.201-.064.482-.118.785-.065a.158.158 0 0 1-.055.313c-.236-.042-.462 0-.633.054a1.6 1.6 0 0 0-.257.107z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.mk_tesa_t {
  stop-color: var(--svg-color--49c4fa, #49C4FA);
}

.mkkd392fx {
  stop-color: var(--svg-color--d69b3c, #D69B3C);
}

.ml6o-6oro {
  d: path("M14.404 6.475h.007l-.006-.157l-.006-.181c.012-.56.34-.778.479-.85l.03-.012l.03-.012c.316-.145.57-.398.704-.73l.048-.114a.156.156 0 0 1 .273-.03a2.28 2.28 0 0 0 1.885.988h1.902c.107 0 .64.052.672.788l-.07 1.816c-.073 1.656-1.367 2.768-2.945 2.768c-1.58 0-2.872-1.112-2.945-2.768z");
}

.mmnqgv5yf {
  stop-color: var(--svg-color--ffba27, #FFBA27);
  stop-opacity: 0;
}

.msb_mlodm {
  stop-color: var(--svg-color--f1b030, #F1B030);
  stop-opacity: 0;
}

.n7-hw2b3h {
  stop-color: var(--svg-color--9f7ada, #9F7ADA);
  stop-opacity: 0;
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

.nr9au_--r {
  fill: var(--svg-color--bd4f26, #BD4F26);
  fill-rule: evenodd;
  d: path("m19.615 5.9l-.081.136za.159.159 0 0 1-.162.272l-.003-.002l-.067-.034a2 2 0 0 0-.202-.08a1.34 1.34 0 0 0-.634-.054a.159.159 0 0 1-.055-.313c.303-.053.584 0 .785.065a2 2 0 0 1 .33.14l.006.004z");
}

.nv-3lfz3i {
  stop-color: var(--svg-color--c8a328, #C8A328);
}

.nz73gfbvi {
  stop-color: var(--svg-color--fdc240, #FDC240);
}

.o0eqsac9n {
  d: path("M16.12 6.586a.527.527 0 0 0-.508.667h1.018a.53.53 0 0 0-.51-.666");
}

.o0h7y_boi {
  stop-color: var(--svg-color--45beff, #45BEFF);
}

.o5bua8boy {
  stop-color: var(--svg-color--45c0ff, #45C0FF);
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

.ofvzbdbov {
  stop-color: var(--svg-color--fcae2e, #FCAE2E);
  stop-opacity: 0;
}

.ohwkd8wyz {
  stop-color: var(--svg-color--eea535, #EEA535);
}

.ookdrzgqt {
  stop-color: var(--svg-color--8451b2, #8451B2);
}

.oqvigc69j {
  stop-color: var(--svg-color--f39c22, #F39C22);
}

.ox3lchxkt {
  stop-color: var(--svg-color--efa62d, #EFA62D);
}

.oxhj8dfqw {
  stop-color: var(--svg-color--ffbc29, #FFBC29);
  stop-opacity: 0;
}

.p_t0wkgjg {
  fill: var(--svg-color--efac26, #EFAC26);
  d: path("M20.263 7.856a.635.635 0 1 0 0-1.27a.635.635 0 0 0 0 1.27");
}

.p8wuxeb4t {
  stop-color: var(--svg-color--ffda35, #FFDA35);
}

.ph5dftb5v {
  stop-color: var(--svg-color--e39229, #E39229);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pltv3850l {
  stop-color: var(--svg-color--f3ae26, #F3AE26);
}

.pm-mvbcfp {
  fill: var(--svg-color--e5942b, #E5942B);
  d: path("M14.715 13.837a.325.325 0 0 0-.325.325v.916c0 .584.473 1.056 1.056 1.056h3.935c.583 0 1.055-.473 1.055-1.056v-.916a.325.325 0 0 0-.324-.325h-1.496a1.22 1.22 0 0 0-1.119.735c-.022.05-.146.05-.168 0a1.22 1.22 0 0 0-1.118-.735z");
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.q2m7q-bcq {
  d: path("M15.62 4.556c-.22.565-1.18 1.028-1.61 1.14c-.142-1.143.301-2.523 1.702-2.274l.236.915c-.236-.066-.286.11-.328.219");
}

.q6rrzt8xr {
  stop-color: var(--svg-color--f4a128, #F4A128);
  stop-opacity: 0;
}

.qdgeq05dx {
  d: path("M25.683 7.95h-.003a.53.53 0 0 0-.531.532v.5c0 .14-.14.234-.256.156a1.5 1.5 0 0 1-.238-.2c-.125-.129-.17-.309-.17-.488v-.546l.56-.558a.44.44 0 0 1 .638.605");
}

.qn752-99j {
  stop-color: var(--svg-color--ffcc2e, #FFCC2E);
}

.qofl2v1ay {
  stop-color: var(--svg-color--cc8b40, #CC8B40);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r9a_520ft {
  stop-color: var(--svg-color--fa871d, #FA871D);
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

.sdf9tobyx {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.997 6.425a.825.825 0 0 0-.8.626a.162.162 0 0 0 .158.201h1.318a.136.136 0 0 0 .135-.16a.83.83 0 0 0-.81-.667");
}

.sstkyybun {
  stop-color: var(--svg-color--de8a27, #DE8A27);
}

.t2ck-pbsh {
  cx: 15.959px;
  cy: 6.811px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.229px;
  ry: 0.116px;
}

.t57u5vsaf {
  stop-color: var(--svg-color--fb8a20, #FB8A20);
  stop-opacity: 0;
}

.tfu66nomq {
  stop-color: var(--svg-color--cea639, #CEA639);
}

.thj442bmz {
  fill: var(--svg-color--ffcf3f, #FFCF3F);
  d: path("M25.054 9.557c.399-.066.488-.33.488-.501v-.535a.184.184 0 0 1 .367 0v4.93a.527.527 0 0 1-1.055 0V9.77c0-.11.09-.197.2-.214");
}

.tim_a1bwu {
  stop-color: var(--svg-color--eeaa2e, #EEAA2E);
}

.ts5vg6ilu {
  stop-color: var(--svg-color--fccb44, #FCCB44);
}

.u0bnb-zsr {
  stop-color: var(--svg-color--cc972e, #CC972E);
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

.utkhftb9q {
  cx: 15.959px;
  cy: 6.811px;
  rx: 0.229px;
  ry: 0.116px;
}

.uukk9e6th {
  stop-color: var(--svg-color--cf841f, #CF841F);
}

.uuxpnvfdu {
  stop-color: var(--svg-color--ffb42a, #FFB42A);
  stop-opacity: 0;
}

.v3hxs-buk {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M16.736 6.884c-.157-.275-.396-.493-.909-.493a.98.98 0 0 0-.634.218c-.159.128-.137.292-.014.354l.328.187c.385-.124.811-.141 1.229-.266");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vckbn7bgk {
  d: path("m17.184 7.007l-.314 1.005a.32.32 0 0 0 .308.413h.465a.32.32 0 0 0 .307-.413l-.314-1.005c-.067-.222-.381-.222-.452 0");
}

.vp72o-bak {
  fill: var(--svg-color--eb9c2d, #EB9C2D);
  d: path("M14.641 8.172a.95.95 0 1 0 0-1.902a.95.95 0 0 0 0 1.902");
}

.vsknd5b9t {
  d: path("M9.91 15.744c1.812 1.575 4.202 1.213 5.171.875v-4.626h7.234c.517-1.326.156-2.452-.236-3.066a.28.28 0 0 1-.029-.24c.082-.236.193-.616.207-.916c.031-.66-.172-.707-.192-1.613c-.02-.907-.306-1.241-.78-2.016c-.384-.625-1.372-1.031-1.974-1.27c-.66-.261-.894-.757-1.89-.757c-.77 0-1.277.39-1.626.729a.85.85 0 0 1-.48.23c-1.223.163-2.266.735-2.843 1.802c-.338.626-.369 1.608-.365 2.282a.53.53 0 0 1-.42.513c-1.53.345-2.65 1.23-3.18 2.233c-.578 1.093-.863 3.87 1.402 5.84");
}

.vw-gsnb-j {
  stop-color: var(--svg-color--d1a839, #D1A839);
  stop-opacity: 0;
}

.w4wjacb9v {
  stop-color: var(--svg-color--8c60d5, #8C60D5);
  stop-opacity: 0;
}

.wdg5-_bwz {
  stop-color: var(--svg-color--d1a839, #D1A839);
}

.wgxxd_b3o {
  stop-color: var(--svg-color--eea223, #EEA223);
  stop-opacity: 0;
}

.whiqcnb7o {
  stop-color: var(--svg-color--ec741c, #EC741C);
  stop-opacity: 0;
}

.whwvona8i {
  stop-color: var(--svg-color--ba710f, #BA710F);
}

.wjmq6tbsf {
  stop-color: var(--svg-color--ffcb3a, #FFCB3A);
}

.wliqnbp1k {
  d: path("M14.09 13.15a.4.4 0 0 0-.4.4v1.128a1.3 1.3 0 0 0 1.3 1.3h4.846a1.3 1.3 0 0 0 1.3-1.3V13.55a.4.4 0 0 0-.4-.4h-1.842a1.5 1.5 0 0 0-1.377.904c-.027.062-.18.062-.207 0a1.5 1.5 0 0 0-1.377-.904z");
}

.wttyue-hr {
  stop-color: var(--svg-color--ef9e28, #EF9E28);
  stop-opacity: 0;
}

.x2e_pmc0g {
  d: path("M16.6 7.05c0-.17-.138-.283-.175-.317l-.17.164l.104.213z");
}

.xjs25bcfc {
  stop-color: var(--svg-color--ffb430, #FFB430);
}

.xmk1l3i-w {
  stop-color: var(--svg-color--ffb430, #FFB430);
  stop-opacity: 0;
}

.xonyy5bvc {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M17.41 8.941a1.8 1.8 0 0 1-.84-.203c-.083-.044-.172.052-.12.13a1.142 1.142 0 0 0 1.92 0c.053-.08-.036-.174-.12-.13a1.8 1.8 0 0 1-.84.203");
}

.y_rv32tfd {
  stop-color: var(--svg-color--40b87c, #40B87C);
}

.y-anmyn4x {
  stop-color: var(--svg-color--cf7600, #CF7600);
}

.y-w066bhd {
  stop-color: var(--svg-color--f1b331, #F1B331);
}

.y1ow33bnn {
  stop-color: var(--svg-color--f8ab33, #F8AB33);
  stop-opacity: 0;
}

.y1xxtut2l {
  stop-color: var(--svg-color--ef9e28, #EF9E28);
}

.y8hb2-0cv {
  stop-color: var(--svg-color--ffd833, #FFD833);
  stop-opacity: 0;
}

.yf02b6ygm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M11.429 26.864c-.007.65.436 1.948 2.266 1.948h3.177c1.01-.014 3.316-.516 4.469-2.414");
}

.ynjbm96er {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.41 8.941a1.8 1.8 0 0 1-.84-.203c-.083-.044-.172.052-.12.13a1.142 1.142 0 0 0 1.92 0c.053-.08-.036-.174-.12-.13a1.8 1.8 0 0 1-.84.203Z");
}

.yo-rx8c0q {
  d: path("M19.17 7.043a.5.5 0 0 0-.137-.272l-.152.167l.069.135z");
}

.ysp-lfbbx {
  stop-color: var(--svg-color--f6a934, #F6A934);
}

.zbh51bctq {
  stop-color: var(--svg-color--e4942a, #E4942A);
}

.zku_rzyyo {
  stop-color: var(--svg-color--8d61d6, #8D61D6);
  stop-opacity: 0;
}

.zmc2y0hrn {
  stop-color: var(--svg-color--bb5b24, #BB5B24);
}

.zn6johb1n {
  stop-color: var(--svg-color--f78913, #F78913);
  stop-opacity: 0;
}

.zxdg24bmw {
  stop-color: var(--svg-color--ffd22f, #FFD22F);
}

</style>
