<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iuyRCtc)" class="ad6zenl5p"/><path fill="url(#iwPHmHc)" class="ad6zenl5p"/><path fill="url(#iEv1z7b)" class="ad6zenl5p"/><path fill="url(#ig2uhxd)" class="ad6zenl5p"/><path fill="url(#iAFkfSb)" class="ad6zenl5p"/><path fill="url(#iY1nHNe)" class="tfpd72bmj"/><path fill="url(#iWl9v6E)" class="tfpd72bmj"/><path class="kp7cfduip"/><path fill="url(#ihJj5Db)" class="d0i-qonjb"/><path fill="url(#iQPaFqb)" class="d0i-qonjb"/><path class="nlvudybvu"/><path fill="url(#iS8TEvc)" class="ai325kb6x"/><path fill="url(#iqfZUwc)" class="ai325kb6x"/><g filter="url(#ipJ1Ouc)"><circle fill="url(#ignnOge)" class="l2qwdelqw"/></g><g filter="url(#i5OKdBd)"><circle fill="url(#isCO4yL)" class="hn3s_cbup"/></g><g filter="url(#i9hEAoc)"><circle fill="url(#iJSF4uc)" class="qeqnj6bwc"/><circle fill="url(#ijs6CPe)" class="qeqnj6bwc"/></g><g filter="url(#iE5RBRb)"><circle class="wg0cg_b2u"/><circle fill="url(#ieIJqcb)" class="njc_4fbku"/><circle fill="url(#imILOqc)" class="njc_4fbku"/></g><g filter="url(#iWAyYae)"><path fill="url(#izcM2Vj)" class="fekgso86r"/><path fill="url(#iqyDnlc)" class="fekgso86r"/><path fill="url(#ikq3Xmc)" class="fekgso86r"/><path fill="url(#iCkXvxe)" class="fekgso86r"/><path fill="url(#iVsJ7rc)" class="fekgso86r"/><path fill="url(#iSuxwre)" class="fekgso86r"/></g><g filter="url(#iHHSiDc)"><path fill="url(#ictHAJh)" class="k9b2ju7jq"/></g><g filter="url(#iOb9Tzy)"><path class="w2l8s8blm"/><path fill="url(#iaGbxRd)" class="wasrcuy2g"/><path fill="url(#iv4smqb)" class="wasrcuy2g"/><path fill="url(#iIUBysn)" class="wasrcuy2g"/><path fill="url(#i2CrfCc)" class="wasrcuy2g"/></g><g filter="url(#ietGYGB)"><path class="kh03m-bzn"/></g><g filter="url(#i2QijZd)"><path class="dq3p_ts5z"/><path fill="url(#iNeKtgc)" class="qiokirb2u"/><path fill="url(#iFQpAQe)" class="qiokirb2u"/><path fill="url(#iQAVgCe)" class="qiokirb2u"/><path fill="url(#i2KXN9b)" class="qiokirb2u"/></g><path stroke="url(#iF9RHxe)" class="pvprdd62k"/><g filter="url(#iRfL21d)"><path class="h2siqb4or"/></g><g filter="url(#iHlx9Ac)"><path class="ufud3ab4g"/></g><path class="fyrpvcz8c"/><path fill="url(#i5zH5bd)" class="yqvz3__yv"/><path class="e6x563bnc"/><g filter="url(#iVwbTyd)"><path class="tfpj9dbbx"/><path fill="url(#iPJlird)" class="zt5hmhbop"/></g><g filter="url(#iserYJc)"><path fill="url(#iPcCnPb)" class="w457ubb8p"/></g><path class="vo905zb4s"/><path fill="url(#iTdLnCd)" class="x8o19ibsb"/><path class="mpzg2gsjf"/><g filter="url(#iO8dmzc)"><path fill="url(#iRY1qee)" class="gqkb4ibjo"/></g><g filter="url(#iNDgWcd)"><ellipse transform="rotate(-27.914 12.159 12.393)" class="f2r5v8bfp"/><ellipse fill="url(#iwiypTg)" transform="rotate(-27.914 12.159 12.393)" class="v6-g8enxe"/></g><g filter="url(#i20dgHc)"><path stroke="url(#ikTVptb)" class="uxzxrkbxu"/></g><g filter="url(#iK9noXb)"><path stroke="url(#iCxamXO)" class="iiykljbae"/></g><g filter="url(#i7WRyZb)"><path stroke="url(#ien8eTd)" class="em0r0lbnk"/></g><path fill="url(#ie8R11c)" class="trz5t_bmm"/><path fill="url(#itJSQTc)" class="trz5t_bmm"/><path fill="url(#ixn7Nrd)" class="j9_tcit_c"/><path fill="url(#iqFOvTT)" class="j9_tcit_c"/><path fill="url(#iAyumpb)" class="yx0ye_ufd"/><path fill="url(#i0dpVqq)" class="yx0ye_ufd"/><g filter="url(#itCay4W)"><circle fill="url(#iuDFgAe)" class="sm84e7bem"/><circle fill="url(#ipce8Sd)" class="sm84e7bem"/><circle fill="url(#imM1H1b)" class="sm84e7bem"/></g><g filter="url(#inZtRec)"><path fill="url(#i5lhlOb)" clip-rule="evenodd" class="h83b67bow"/></g><path fill="url(#ivqPuuj)" clip-rule="evenodd" class="h83b67bow"/><g filter="url(#ijFQ0md)"><path fill="url(#ie1h4be)" clip-rule="evenodd" class="v99r5cc_a"/></g><g filter="url(#i14arUc)"><circle stroke="url(#ijcJdMb)" class="dusbyk69d"/></g><g filter="url(#iKfimLb)"><circle stroke="url(#ibfKRzb)" class="yd_7jebvl"/></g><g filter="url(#iYAk4Gp)"><circle stroke="url(#iu1pSmd)" class="i1-v3abff"/></g><g filter="url(#iW9IEyc)"><circle stroke="url(#iCqanBe)" class="h9vakccdw"/></g><defs><radialGradient id="iuyRCtc" cx="0" cy="0" r="1" gradientTransform="rotate(154.071 8.313 13.901)scale(15.0662 17.3462)" gradientUnits="userSpaceOnUse"><stop class="tet72waca"/><stop offset="1" class="bmx48tuma"/></radialGradient><radialGradient id="iwPHmHc" cx="0" cy="0" r="1" gradientTransform="rotate(-115.528 17.238 10.578)scale(12.9022 18.5657)" gradientUnits="userSpaceOnUse"><stop offset=".879" class="rxprtfb0z"/><stop offset="1" class="m-fo0lvbc"/></radialGradient><radialGradient id="iEv1z7b" cx="0" cy="0" r="1" gradientTransform="rotate(166.984 5.946 10.215)scale(6.38273 2.1839)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="zdar40bkv"/><stop offset="1" class="cybfe7yaw"/></radialGradient><radialGradient id="ig2uhxd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6713 0 0 -14.1675 21.546 29.356)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="puczgzv3j"/><stop offset="1" class="mq0bii3nt"/></radialGradient><radialGradient id="iAFkfSb" cx="0" cy="0" r="1" gradientTransform="matrix(1.24045 0 0 9.50024 7.166 29.356)" gradientUnits="userSpaceOnUse"><stop class="wke-8-xfb"/><stop offset="1" class="h-56b9bpz"/></radialGradient><radialGradient id="iY1nHNe" cx="0" cy="0" r="1" gradientTransform="matrix(3.25185 0 0 9.13279 21.576 28.577)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="kin3dabop"/><stop offset="1" class="jlkbatyzp"/></radialGradient><radialGradient id="iWl9v6E" cx="0" cy="0" r="1" gradientTransform="matrix(.87006 0 0 11.9715 21.576 29.356)" gradientUnits="userSpaceOnUse"><stop class="hos3q5hgu"/><stop offset="1" class="txm2ysbkn"/></radialGradient><radialGradient id="ihJj5Db" cx="0" cy="0" r="1" gradientTransform="matrix(-3.70862 0 0 -8.85437 7.31 29.356)" gradientUnits="userSpaceOnUse"><stop offset=".614" class="vp_-q7ldm"/><stop offset=".956" class="k-z4zg2os"/></radialGradient><radialGradient id="iQPaFqb" cx="0" cy="0" r="1" gradientTransform="matrix(-.8463 0 0 -10.457 7.31 29.356)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="oxun88gow"/><stop offset="1" class="zi0iv1bfj"/></radialGradient><radialGradient id="iS8TEvc" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 1.75 -3.03541 .97567 13.7 18.991)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="b6nri9f6u"/><stop offset="1" class="u077olbpu"/></radialGradient><radialGradient id="iqfZUwc" cx="0" cy="0" r="1" gradientTransform="rotate(139.583 4.476 13.308)scale(2.48229 1.07513)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="yiypfcbal"/><stop offset="1" class="lhk0x03lq"/></radialGradient><radialGradient id="ignnOge" cx="0" cy="0" r="1" gradientTransform="matrix(1.75471 0 0 3.07077 8.197 13.17)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="ijs6CPe" cx="0" cy="0" r="1" gradientTransform="matrix(.82664 -.60191 .687 .9435 19.751 12.906)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="ieIJqcb" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 19.338 13.992)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="imILOqc" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 -6.325 30.148)scale(.3648 .47028)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="iqyDnlc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.3278 -15.3216 0 14.643 11.246)" gradientUnits="userSpaceOnUse"><stop offset=".73" class="rhrxdzb3e"/><stop offset="1" class="c8tar2btd"/></radialGradient><radialGradient id="iVsJ7rc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60858 0 16.96 11.9)" gradientUnits="userSpaceOnUse"><stop class="m459pab_j"/><stop offset="1" class="rcuz4uefu"/></radialGradient><radialGradient id="iSuxwre" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39075 1.72952 0 12.402 11.866)" gradientUnits="userSpaceOnUse"><stop class="hplqxft1w"/><stop offset="1" class="ay1rn8bxh"/></radialGradient><radialGradient id="iaGbxRd" cx="0" cy="0" r="1" gradientTransform="rotate(-74.899 15.397 -7.844)scale(3.06211 1.13553)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="iv4smqb" cx="0" cy="0" r="1" gradientTransform="rotate(5.258 -70.89 192.223)scale(3.84067 2.0651)" gradientUnits="userSpaceOnUse"><stop offset=".335" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="iIUBysn" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.67903 -2.60035 0 14.614 4.57)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="i2CrfCc" cx="0" cy="0" r="1" gradientTransform="matrix(3.07368 -2.25248 3.5289 4.81545 8.166 11.388)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="i2KXN9b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19688 -.63254 0 14.941 14.777)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="i5zH5bd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81106 -1.29009 0 16.793 12.489)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iPJlird" cx="0" cy="0" r="1" gradientTransform="matrix(-.23184 -.29876 .41132 -.3192 16.565 12.573)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iTdLnCd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8111 -1.29015 0 12.43 12.489)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iwiypTg" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.327 .376)scale(.49399 .59379)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ie8R11c" cx="0" cy="0" r="1" gradientTransform="rotate(153.368 11.027 5.157)scale(5.13895 3.99651)" gradientUnits="userSpaceOnUse"><stop class="vauv6-kqu"/><stop offset=".871" class="d7nlg-wae"/></radialGradient><radialGradient id="itJSQTc" cx="0" cy="0" r="1" gradientTransform="matrix(2.98438 .42715 -.07614 .53198 17.743 6.689)" gradientUnits="userSpaceOnUse"><stop offset=".037" class="yidkw-brm"/><stop offset="1" class="hv9dr3b3w"/></radialGradient><radialGradient id="iuDFgAe" cx="0" cy="0" r="1" gradientTransform="rotate(141.18 10.74 7.666)scale(.43619)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="cz-qsgbfy"/><stop offset="1" class="j80tr6o9y"/></radialGradient><radialGradient id="ipce8Sd" cx="0" cy="0" r="1" gradientTransform="matrix(.19922 -.48438 1.17186 .48198 23.594 7.347)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="m8bo-jb-t"/><stop offset="1" class="wy7e69bbh"/></radialGradient><radialGradient id="imM1H1b" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 .04684 -.05916 .55254 23.369 6.91)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="zk512ndyg"/><stop offset="1" class="hy0z0nf6k"/></radialGradient><radialGradient id="i5lhlOb" cx="0" cy="0" r="1" gradientTransform="matrix(2.20247 -1.61719 2.56784 3.49718 21.396 10.096)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="cnux6p8xn"/><stop offset="1" class="jaxt-o31p"/></radialGradient><radialGradient id="ie1h4be" cx="0" cy="0" r="1" gradientTransform="matrix(2.53124 -1.40627 1.98705 3.57664 24.543 8.273)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="cnux6p8xn"/><stop offset="1" class="jaxt-o31p"/></radialGradient><filter id="ipJ1Ouc" width="3.539" height="3.339" x="8.197" y="11.501" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_38"/></filter><filter id="i5OKdBd" width="2.99" height="2.99" x="8.372" y="11.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_38" stdDeviation=".25"/></filter><filter id="i9hEAoc" width="3.589" height="3.589" x="17.71" y="11.251" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_38"/></filter><filter id="iE5RBRb" width="2.99" height="2.99" x="17.884" y="11.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_38" stdDeviation=".25"/></filter><filter id="iWAyYae" width="10.373" height="12.277" x="9.456" y="7.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_38"/></filter><filter id="iHHSiDc" width="8.246" height="7.066" x="12.784" y="5.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_38" stdDeviation="1"/></filter><filter id="iOb9Tzy" width="12.601" height="8.543" x="8.314" y="4.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_38"/></filter><filter id="ietGYGB" width="3.26" height="4.181" x="12.745" y="12.016" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_38" stdDeviation=".375"/></filter><filter id="i2QijZd" width="2.077" height="2.881" x="13.576" y="12.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_38" stdDeviation=".05"/></filter><filter id="iRfL21d" width="2.979" height="1.873" x="15.796" y="9.522" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_38"/></filter><filter id="iHlx9Ac" width="2.98" height="1.873" x="10.649" y="9.522" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_38"/></filter><filter id="iVwbTyd" width=".787" height=".696" x="16.059" y="12.049" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_38" stdDeviation=".05"/></filter><filter id="iserYJc" width=".891" height=".913" x="16.898" y="12.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_38" stdDeviation=".1"/></filter><filter id="iO8dmzc" width=".986" height="1.04" x="12.457" y="12.06" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_38" stdDeviation=".1"/></filter><filter id="iNDgWcd" width=".913" height=".704" x="11.702" y="12.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_38" stdDeviation=".05"/></filter><filter id="i20dgHc" width="3.099" height="1.681" x="15.649" y="9.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_38" stdDeviation=".25"/></filter><filter id="iK9noXb" width="3.177" height="1.738" x="10.43" y="9.712" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_38" stdDeviation=".25"/></filter><filter id="i7WRyZb" width="1.008" height="2.269" x="9.448" y="7.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_38" stdDeviation=".125"/></filter><filter id="itCay4W" width=".726" height=".726" x="23.426" y="6.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.52549 0 0 0 0 0.388235 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_38"/></filter><filter id="inZtRec" width="3.834" height="4.387" x="20.968" y="7.388" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.45098 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_38"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.282353 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_38" result="effect2_innerShadow_4002_38"/></filter><filter id="ijFQ0md" width="4.283" height="3.734" x="24.166" y="5.911" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.203922 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_38"/></filter><filter id="i14arUc" width="3.843" height="3.843" x="24.637" y="5.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_38" stdDeviation=".1"/></filter><filter id="iKfimLb" width="2.734" height="2.734" x="25.191" y="6.436" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_38" stdDeviation=".1"/></filter><filter id="iYAk4Gp" width="2.734" height="2.734" x="21.543" y="8.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_38" stdDeviation=".1"/></filter><filter id="iW9IEyc" width="3.805" height="3.805" x="21.008" y="7.915" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_38" stdDeviation=".1"/></filter><linearGradient id="isCO4yL" x1="9.867" x2="9.226" y1="13.449" y2="13.449" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="iJSF4uc" x1="20.465" x2="19.647" y1="12.079" y2="14.615" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="izcM2Vj" x1="18.65" x2="11.013" y1="13.56" y2="14.698" gradientUnits="userSpaceOnUse"><stop class="z8y6fgvmn"/><stop offset="1" class="tqgh1edwg"/></linearGradient><linearGradient id="ikq3Xmc" x1="8.972" x2="12.33" y1="15.087" y2="15.201" gradientUnits="userSpaceOnUse"><stop class="z3n_1mwef"/><stop offset="1" class="rvf3-0bfj"/></linearGradient><linearGradient id="iCkXvxe" x1="9.219" x2="11.1" y1="16.256" y2="16.189" gradientUnits="userSpaceOnUse"><stop class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="ictHAJh" x1="14.083" x2="22.226" y1="10.575" y2="7.66" gradientUnits="userSpaceOnUse"><stop class="sbbw_6vcc"/><stop offset="1" class="b7cutjkii"/></linearGradient><linearGradient id="iNeKtgc" x1="13.75" x2="14.688" y1="14.219" y2="14.219" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="iFQpAQe" x1="15.552" x2="14.527" y1="14.542" y2="14.527" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="iQAVgCe" x1="14.809" x2="14.809" y1="15.284" y2="14.711" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="iF9RHxe" x1="13.577" x2="14.012" y1="16.899" y2="16.211" gradientUnits="userSpaceOnUse"><stop class="wl-j51biu"/><stop offset=".663" class="i-vkeo5mo"/></linearGradient><linearGradient id="iPcCnPb" x1="17.571" x2="17.257" y1="12.543" y2="12.736" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iRY1qee" x1="13.174" x2="12.86" y1="12.543" y2="12.736" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ikTVptb" x1="17.586" x2="17.166" y1="10.403" y2="9.545" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iCxamXO" x1="12.282" x2="11.093" y1="10.275" y2="9.777" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="ien8eTd" x1="9.952" x2="9.952" y1="8.261" y2="10.418" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><linearGradient id="ixn7Nrd" x1="24.949" x2="23.758" y1="5.049" y2="4.704" gradientUnits="userSpaceOnUse"><stop class="p9lsnsm5t"/><stop offset="1" class="lapvr59ed"/></linearGradient><linearGradient id="iqFOvTT" x1="23.801" x2="23.875" y1="6.542" y2="6.253" gradientUnits="userSpaceOnUse"><stop offset=".16" class="zl0fwhbas"/><stop offset="1" class="lxc0fmbqt"/></linearGradient><linearGradient id="iAyumpb" x1="22.887" x2="23.152" y1="7.398" y2="6.101" gradientUnits="userSpaceOnUse"><stop class="p9lsnsm5t"/><stop offset="1" class="lapvr59ed"/></linearGradient><linearGradient id="i0dpVqq" x1="24.298" x2="24.1" y1="7.48" y2="7.424" gradientUnits="userSpaceOnUse"><stop class="jd-vaq0no"/><stop offset="1" class="gof7ehbkx"/></linearGradient><linearGradient id="ivqPuuj" x1="23.637" x2="23.578" y1="7.57" y2="7.796" gradientUnits="userSpaceOnUse"><stop offset=".209" class="ni_6htbzm"/><stop offset="1" class="ajm38_jxm"/></linearGradient><linearGradient id="ijcJdMb" x1="24.887" x2="28.077" y1="8.172" y2="6.7" gradientUnits="userSpaceOnUse"><stop offset=".616" class="w5_7ycb6b"/><stop offset=".9" class="srm_r_guo"/></linearGradient><linearGradient id="ibfKRzb" x1="25.441" x2="27.573" y1="8.05" y2="7.066" gradientUnits="userSpaceOnUse"><stop offset=".247" class="jzjqx7qlk"/><stop offset=".669" class="gl3wl_9gz"/></linearGradient><linearGradient id="iu1pSmd" x1="21.793" x2="23.925" y1="10.064" y2="9.079" gradientUnits="userSpaceOnUse"><stop offset=".247" class="rraw6sbsp"/><stop offset=".669" class="r8ibvzbki"/></linearGradient><linearGradient id="iCqanBe" x1="24.563" x2="22.91" y1="9.276" y2="9.817" gradientUnits="userSpaceOnUse"><stop class="znwvjy5yx"/><stop offset="1" class="zi0lb2bns"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-getting-haircut-light" /></template>
<style>
.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.ad6zenl5p {
  d: path("M3.601 28.893c0-5.916 4.854-10.711 10.842-10.711s10.842 4.795 10.842 10.71v.464H3.601z");
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.ai325kb6x {
  d: path("M12.63 17.976h3.985v1.383c0 1.1-.892 1.812-1.992 1.812s-1.992-.712-1.992-1.812z");
}

.ajm38_jxm {
  stop-color: var(--svg-color--ff3178, #FF3178);
  stop-opacity: 0;
}

.ay1rn8bxh {
  stop-color: var(--svg-color--d0958d, #D0958D);
  stop-opacity: 0;
}

.b6nri9f6u {
  stop-color: var(--svg-color--b4818e, #B4818E);
}

.b7cutjkii {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
  stop-opacity: 0;
}

.bmx48tuma {
  stop-color: var(--svg-color--2477dd, #2477DD);
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

.c8tar2btd {
  stop-color: var(--svg-color--a87c91, #A87C91);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnux6p8xn {
  stop-color: var(--svg-color--ff7046, #FF7046);
}

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.cybfe7yaw {
  stop-color: var(--svg-color--27719e, #27719E);
  stop-opacity: 0;
}

.cz-qsgbfy {
  stop-color: var(--svg-color--ebdbe4, #EBDBE4);
}

.d0i-qonjb {
  d: path("M7.31 20.827C5.037 22.79 3.6 25.676 3.6 28.893v.463h3.71z");
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.d7nlg-wae {
  stop-color: var(--svg-color--322a2d, #322A2D);
}

.dq3p_ts5z {
  fill: var(--svg-color--fbc4b1, #FBC4B1);
  d: path("m14.232 12.885l-.531 1.7a.538.538 0 0 0 .52.699h.786a.54.54 0 0 0 .52-.7l-.53-1.699c-.115-.376-.646-.376-.765 0");
}

.dusbyk69d {
  cx: 26.558px;
  cy: 7.804px;
  r: 1.671px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e6x563bnc {
  fill: var(--svg-color--000, #000);
  d: path("M16.284 12.904c0-.284.227-.51.51-.51a.51.51 0 0 1 .455.745h-.904a.46.46 0 0 1-.061-.235");
}

.em0r0lbnk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.082 8.36v.897c-.008.149-.07.481-.259.622");
}

.f2r5v8bfp {
  cx: 12.159px;
  cy: 12.393px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.fekgso86r {
  d: path("M9.456 11.12c0-.267.108-.587.322-.747l.161-.16c.268-.213.376-.533.376-.853v-.853c0-.267.16-.48.429-.534c.643-.16 1.984-.426 3.915-.426c1.93 0 3.272.266 3.915.426c.215.054.43.267.43.534v.853c0 .32.16.64.375.853c.502.352.47.545.429.96c-.054.533-.107 1.44-.107 1.44h.018l-.266 3.958c-.16 1.77-1.552 3.002-3.21 3.002h-3.21c-1.712 0-3.05-1.233-3.21-3.002c-.14-1.817-.2-3.638-.367-5.451");
}

.ft5dv1b6b {
  fill: none;
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.fyrpvcz8c {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.002 11.74c.653 0 1.204.45 1.354 1.059a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gl3wl_9gz {
  stop-color: var(--svg-color--ff7e7a, #FF7E7A);
  stop-opacity: 0;
}

.gof7ehbkx {
  stop-color: var(--svg-color--a2889f, #A2889F);
  stop-opacity: 0;
}

.gqkb4ibjo {
  d: path("M13.243 12.8c0-.29-.234-.481-.298-.54l-.288.28l.178.36z");
}

.h-56b9bpz {
  stop-color: var(--svg-color--1f6ce0, #1F6CE0);
  stop-opacity: 0;
}

.h2siqb4or {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m18.333 10.45l-.002-.002l-.004-.003l-.012-.01a1.4 1.4 0 0 0-.155-.107a2.6 2.6 0 0 0-.42-.211a2.83 2.83 0 0 0-1.492-.158a.534.534 0 0 0 .166 1.054c.398-.063.716.01.934.096a1.5 1.5 0 0 1 .308.166a.534.534 0 0 0 .678-.824");
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.h83b67bow {
  fill-rule: evenodd;
  d: path("M23.013 7.442a.1.1 0 0 0-.124.068l-.104.357a.22.22 0 0 1-.174.149a1.842 1.842 0 1 0 1.514.433a.21.21 0 0 1-.068-.22l.101-.349a.1.1 0 0 0-.068-.124zm.74 2.391a.844.844 0 1 1-1.687 0a.844.844 0 0 1 1.688 0");
}

.h9vakccdw {
  cx: 22.91px;
  cy: 9.817px;
  r: 1.652px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.hmo3unbrx {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
}

.hn3s_cbup {
  cx: 9.867px;
  cy: 13.171px;
  r: 0.995px;
}

.hos3q5hgu {
  stop-color: var(--svg-color--367bf1, #367BF1);
}

.hplqxft1w {
  stop-color: var(--svg-color--d0958d, #D0958D);
}

.hv9dr3b3w {
  stop-color: var(--svg-color--484344, #484344);
  stop-opacity: 0;
}

.hy0z0nf6k {
  stop-color: var(--svg-color--a4888c, #A4888C);
  stop-opacity: 0;
}

.i-vkeo5mo {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
  stop-opacity: 0;
}

.i1-v3abff {
  cx: 22.91px;
  cy: 9.817px;
  r: 1.117px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.iiykljbae {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.055 10.825c.328-.29 1.042-.594 1.927-.453");
}

.j80tr6o9y {
  stop-color: var(--svg-color--c7b1b5, #C7B1B5);
}

.j9_tcit_c {
  d: path("m24.342 2.644l-1.388 4.83l1.186.346l1.072-3.73a1.15 1.15 0 0 0-.784-1.421z");
}

.jaxt-o31p {
  stop-color: var(--svg-color--ff2d78, #FF2D78);
}

.jd-vaq0no {
  stop-color: var(--svg-color--93768e, #93768E);
}

.jlkbatyzp {
  stop-color: var(--svg-color--43a0f3, #43A0F3);
}

.jzjqx7qlk {
  stop-color: var(--svg-color--ff7e7a, #FF7E7A);
}

.k-z4zg2os {
  stop-color: var(--svg-color--517cc3, #517CC3);
}

.k9b2ju7jq {
  d: path("M18.577 7.547L15.5 8.573a1.047 1.047 0 0 0 .47 2.03l3.06-.409z");
}

.kh03m-bzn {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m14.339 13.049l-.82 1.699c-.102.35.142.7.488.7h.737c.345 0 .59-.356.488-.7l-.498-1.7c-.107-.376-.283-.376-.395 0");
}

.kin3dabop {
  stop-color: var(--svg-color--43a2ff, #43A2FF);
}

.kp7cfduip {
  fill: var(--svg-color--2b7fde, #2B7FDE);
  d: path("M7.31 20.827C5.037 22.79 3.6 25.676 3.6 28.893v.463h3.71z");
}

.l2qwdelqw {
  cx: 9.866px;
  cy: 13.171px;
  r: 1.669px;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lapvr59ed {
  stop-color: var(--svg-color--d9b4c8, #D9B4C8);
}

.lhk0x03lq {
  stop-color: var(--svg-color--edb9b3, #EDB9B3);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.lxc0fmbqt {
  stop-color: var(--svg-color--c0a0b5, #C0A0B5);
  stop-opacity: 0;
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m-fo0lvbc {
  stop-color: var(--svg-color--407da5, #407DA5);
}

.m459pab_j {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
}

.m8bo-jb-t {
  stop-color: var(--svg-color--996e9f, #996E9F);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mpzg2gsjf {
  fill: var(--svg-color--000, #000);
  d: path("M12.94 12.904a.51.51 0 0 0-.512-.511a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.235");
}

.mq0bii3nt {
  stop-color: var(--svg-color--459bfc, #459BFC);
  stop-opacity: 0;
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.ni_6htbzm {
  stop-color: var(--svg-color--b71143, #B71143);
}

.njc_4fbku {
  cx: 19.379px;
  cy: 13.171px;
  r: 0.995px;
}

.nlvudybvu {
  fill: var(--svg-color--e4a9a6, #E4A9A6);
  d: path("M12.63 17.976h3.985v1.383c0 1.1-.892 1.812-1.992 1.812s-1.992-.712-1.992-1.812z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oxun88gow {
  stop-color: var(--svg-color--438dec, #438DEC);
}

.p9lsnsm5t {
  stop-color: var(--svg-color--9b8299, #9B8299);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.puczgzv3j {
  stop-color: var(--svg-color--459bfc, #459BFC);
}

.pvprdd62k {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.252 15.928c.394.205.862.322 1.362.322a2.94 2.94 0 0 0 1.362-.322a.2.2 0 0 1 .242.04a.19.19 0 0 1 .02.24m-2.986-.28l2.945.253m-2.945-.253a.2.2 0 0 0-.242.041a.19.19 0 0 0-.02.24m.262-.281l-.22.253m3.207.027l-.042-.027m.042.027l-.042-.027m.042.027a1.94 1.94 0 0 1-1.625.869c-.682 0-1.28-.347-1.624-.868m3.207-.028a1.9 1.9 0 0 1-1.583.846a1.9 1.9 0 0 1-1.583-.846m-.041.028l.041-.028m-.041.028l.041-.028");
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qeqnj6bwc {
  cx: 19.379px;
  cy: 13.171px;
  r: 1.669px;
}

.qiokirb2u {
  d: path("m14.232 12.885l-.531 1.7a.538.538 0 0 0 .52.699h.786a.54.54 0 0 0 .52-.7l-.53-1.699c-.115-.376-.646-.376-.765 0");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
  stop-opacity: 0;
}

.r8ibvzbki {
  stop-color: var(--svg-color--ff9266, #FF9266);
  stop-opacity: 0;
}

.rcuz4uefu {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
  stop-opacity: 0;
}

.rhrxdzb3e {
  stop-color: var(--svg-color--cc9699, #CC9699);
  stop-opacity: 0;
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
}

.rraw6sbsp {
  stop-color: var(--svg-color--ff9266, #FF9266);
}

.rvf3-0bfj {
  stop-color: var(--svg-color--dead9d, #DEAD9D);
  stop-opacity: 0;
}

.rxprtfb0z {
  stop-color: var(--svg-color--407da5, #407DA5);
  stop-opacity: 0;
}

.sbbw_6vcc {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
}

.sm84e7bem {
  cx: 23.739px;
  cy: 7px;
  r: 0.313px;
}

.srm_r_guo {
  stop-color: var(--svg-color--ff6792, #FF6792);
}

.tet72waca {
  stop-color: var(--svg-color--339ff3, #339FF3);
}

.tfpd72bmj {
  d: path("M21.577 29.356h3.708v-.463c0-3.217-1.436-6.103-3.709-8.067z");
}

.tfpj9dbbx {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.73 12.2c.063.086-.07.19-.221.302c-.151.113-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.135.388-.05");
}

.tqgh1edwg {
  stop-color: var(--svg-color--eaab97, #EAAB97);
}

.trz5t_bmm {
  d: path("M20.283 5.867c-1.215-.028-1.642-.098-2.18-.285l1.27 1.728l.158.165c.2.208.481.324.767.278c.754-.122 1.862-.454 2.47-1c.843-.757.785-1.492.715-1.757c-.07-.266-.211-.446-.352-.454c-.14-.007-.26.062-.39.375c-.212.508-.883.985-2.458.95");
}

.txm2ysbkn {
  stop-color: var(--svg-color--367bf1, #367BF1);
  stop-opacity: 0;
}

.u077olbpu {
  stop-color: var(--svg-color--b4818e, #B4818E);
  stop-opacity: 0;
}

.ufud3ab4g {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M10.84 10.451h.002v-.001l.002-.002l.005-.003l.012-.01a1.4 1.4 0 0 1 .155-.107c.1-.063.24-.14.42-.211a2.83 2.83 0 0 1 1.492-.158a.534.534 0 0 1-.167 1.054a1.77 1.77 0 0 0-.933.096a1.5 1.5 0 0 0-.308.166a.534.534 0 0 1-.68-.824");
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.uxzxrkbxu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.275 10.306c.43-.075 1.268-.053 1.849.398");
}

.v6-g8enxe {
  cx: 12.159px;
  cy: 12.393px;
  rx: 0.389px;
  ry: 0.197px;
}

.v99r5cc_a {
  fill-rule: evenodd;
  d: path("M24.457 6.655a.1.1 0 0 1 .123-.07l.36.095a.22.22 0 0 0 .216-.072a1.842 1.842 0 1 1-.412 1.52a.22.22 0 0 0-.153-.172l-.351-.094a.1.1 0 0 1-.071-.122zm1.664 1.87a.844.844 0 1 0 .872-1.444a.844.844 0 0 0-.872 1.445");
}

.vauv6-kqu {
  stop-color: var(--svg-color--0f050b, #0F050B);
}

.vo905zb4s {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.221 11.74c-.653 0-1.204.45-1.354 1.059a.273.273 0 0 0 .267.34h2.23a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.37-1.127");
}

.vp_-q7ldm {
  stop-color: var(--svg-color--517cc3, #517CC3);
  stop-opacity: 0;
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.w2l8s8blm {
  fill: var(--svg-color--242324, #242324);
  d: path("m19.433 6.693l.429.214c.75.373 1.18 1.226 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533H19.7s.053-.907.107-1.44c.044-.433-.032-.565-.429-.96c-.215-.213-.376-.533-.376-.853v-.853c0-.267-.214-.48-.429-.534c-.643-.16-1.984-.426-3.915-.426c-1.93 0-3.272.266-3.915.426a.52.52 0 0 0-.43.534v.853c0 .32-.107.64-.375.853l-.16.16c-.215.16-.323.48-.323.747c.054.586.108 1.44.108 1.44l-.05-.002a.63.63 0 0 1-.594-.532l-.59-3.04c-.107-.853.322-1.706 1.073-2.08l.429-.213c.268-.16.536-.373.804-.586l.966-1.014c.59-.533 1.448-.693 2.199-.32a2.94 2.94 0 0 0 1.663 0c.804-.266 1.716-.053 2.36.534l.804.8c.215.266.483.426.805.586");
}

.w457ubb8p {
  d: path("M17.59 12.787a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.w5_7ycb6b {
  stop-color: var(--svg-color--ff4f4f, #FF4F4F);
}

.wachewblq {
  stop-color: var(--svg-color--ba7c6b, #BA7C6B);
}

.wasrcuy2g {
  d: path("m19.433 6.693l.429.214c.75.373 1.18 1.226 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533H19.7s.053-.907.107-1.44c.044-.433-.032-.565-.429-.96c-.215-.213-.376-.533-.376-.853v-.853c0-.267-.214-.48-.429-.534c-.643-.16-1.984-.426-3.915-.426c-1.93 0-3.272.266-3.915.426a.52.52 0 0 0-.43.534v.853c0 .32-.107.64-.375.853l-.16.16c-.215.16-.323.48-.323.747c.054.586.108 1.44.108 1.44l-.05-.002a.63.63 0 0 1-.594-.532l-.59-3.04c-.107-.853.322-1.706 1.073-2.08l.429-.213c.268-.16.536-.373.804-.586l.966-1.014c.59-.533 1.448-.693 2.199-.32a2.94 2.94 0 0 0 1.663 0c.804-.266 1.716-.053 2.36.534l.804.8c.215.266.483.426.805.586");
}

.wdqn7tq-u {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
}

.wg0cg_b2u {
  cx: 19.379px;
  cy: 13.171px;
  r: 0.995px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wke-8-xfb {
  stop-color: var(--svg-color--1f6ce0, #1F6CE0);
}

.wl-j51biu {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
}

.wy7e69bbh {
  stop-color: var(--svg-color--c8b3b7, #C8B3B7);
  stop-opacity: 0;
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.x8o19ibsb {
  d: path("M12.428 12.012a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.yd_7jebvl {
  cx: 26.558px;
  cy: 7.804px;
  r: 1.117px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.yidkw-brm {
  stop-color: var(--svg-color--403a3d, #403A3D);
}

.yiypfcbal {
  stop-color: var(--svg-color--edb9b3, #EDB9B3);
}

.yqvz3__yv {
  d: path("M16.795 12.012a.892.892 0 0 1 .86 1.127H15.93a.896.896 0 0 1 .864-1.127");
}

.yx0ye_ufd {
  d: path("m19.694 5.22l5.42 1.537l-.338 1.189l-4.313-1.223a1.15 1.15 0 0 1-.793-1.42z");
}

.yyvs3obha {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
  stop-opacity: 0;
}

.z3n_1mwef {
  stop-color: var(--svg-color--a58787, #A58787);
}

.z8y6fgvmn {
  stop-color: var(--svg-color--ffdabf, #FFDABF);
}

.zdar40bkv {
  stop-color: var(--svg-color--145491, #145491);
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
}

.zi0iv1bfj {
  stop-color: var(--svg-color--438dec, #438DEC);
  stop-opacity: 0;
}

.zi0lb2bns {
  stop-color: var(--svg-color--ff5185, #FF5185);
  stop-opacity: 0;
}

.zk512ndyg {
  stop-color: var(--svg-color--a4888c, #A4888C);
}

.zl0fwhbas {
  stop-color: var(--svg-color--a28b95, #A28B95);
}

.znwvjy5yx {
  stop-color: var(--svg-color--ff5c88, #FF5C88);
}

.zt5hmhbop {
  d: path("M16.73 12.2c.063.086-.07.19-.221.302c-.151.113-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.135.388-.05");
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

</style>
