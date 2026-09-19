<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iOttkVc)"><path fill="url(#iK2Or7d)" class="zk0zz6s7t"/></g><path fill="url(#i2DGTFc)" class="zk0zz6s7t"/><g filter="url(#iSdUKpO)"><path fill="url(#ijXBhVc)" class="t6506rynz"/><path fill="url(#ivbNife)" class="t6506rynz"/></g><g filter="url(#i5BY4Lc)"><path class="a6zm-0bnl"/><path fill="url(#iIhwAPc)" class="n9tnz5ikc"/></g><g filter="url(#iluM93c)"><path class="gwjnpqb1s"/><path fill="url(#ivZISeb)" class="cnl1fccua"/></g><g filter="url(#iNPxY1c)"><path fill="url(#iuXO7Rz)" class="q0pkd7b8s"/><path fill="url(#ia4qARb)" class="q0pkd7b8s"/><path fill="url(#i4vpZmU)" class="q0pkd7b8s"/><path fill="url(#i5szcGw)" class="q0pkd7b8s"/><path fill="url(#iwEj3eb)" class="q0pkd7b8s"/><path fill="url(#iUB5yMo)" class="q0pkd7b8s"/><path fill="url(#iPs06MI)" class="q0pkd7b8s"/><path fill="url(#i4JeVAc)" class="q0pkd7b8s"/><path fill="url(#iMa2o4d)" class="q0pkd7b8s"/></g><path fill="url(#ilqsKTb)" class="q0pkd7b8s"/><g filter="url(#igfuLQc)"><path class="cudan5oie"/></g><g filter="url(#iGEOSxc)"><path class="k1ya_5b2l"/><path fill="url(#iInlUyd)" class="i16q27b0z"/><path fill="url(#ifLg7td)" class="i16q27b0z"/><path fill="url(#iFfDame)" class="i16q27b0z"/><path fill="url(#iLGPhae)" class="i16q27b0z"/></g><g filter="url(#i5WBN5b)"><path stroke="url(#inC5Mnc)" class="bpds6s3ke"/></g><path class="pkudt8e8m"/><g filter="url(#iue9PCd)"><path class="y0k8bfqtb"/></g><g filter="url(#iFIkQnc)"><path class="y3sbsbvfu"/></g><g filter="url(#in8LvLc)"><path class="fifq1nuxy"/></g><g filter="url(#iizS74b)"><path clip-rule="evenodd" class="paaw4qgqj"/></g><path class="gg0p36txc"/><path fill="url(#iAEOppd)" class="er6nvlbzc"/><path class="nzgowqbpe"/><g filter="url(#iAXj5id)"><path class="rdwuebbdx"/><path fill="url(#izootwe)" class="gelt6sv6v"/></g><g filter="url(#i1nidJE)"><path fill="url(#iq9ESve)" class="k2qq48brl"/></g><path class="tm3kujhuf"/><path fill="url(#ikEJsCP)" class="n644_45yf"/><path class="p__cvka-s"/><g filter="url(#iXhGPNb)"><path fill="url(#iGmi1hd)" class="jxp6cl9zo"/></g><g filter="url(#ix0E1Kc)"><ellipse transform="rotate(-27.914 11.2 17.313)" class="s6qc0ccmr"/><ellipse fill="url(#iCev65d)" transform="rotate(-27.914 11.2 17.313)" class="j1honvvth"/></g><g filter="url(#i2Iaiyd)"><path class="svu__lk9m"/></g><g filter="url(#iwUJ6ld)"><path class="byhm9ccsg"/></g><path fill="url(#iAiNHae)" class="nsn47rbed"/><path fill="url(#iBcFe2d)" class="nsn47rbed"/><path fill="url(#iZXhLkE)" class="nsn47rbed"/><g filter="url(#ipip6Jb)"><path fill="url(#i5EYg7b)" class="opjf3kbfq"/><path fill="url(#ixY9nMe)" class="opjf3kbfq"/></g><g filter="url(#i2uGWjF)"><path fill="url(#iLPDbid)" class="etyder0ew"/></g><path fill="url(#i4dwOqd)" class="etyder0ew"/><path fill="url(#iDxKDTb)" class="etyder0ew"/><path fill="url(#iqQdf3d)" class="etyder0ew"/><g filter="url(#iMTWFKc)"><path fill="url(#if2XEiA)" class="ajkq73jxq"/></g><path fill="url(#iUlKGqd)" class="ajkq73jxq"/><path fill="url(#i8KfJqF)" class="ajkq73jxq"/><path fill="url(#iAMx8mb)" class="ajkq73jxq"/><path fill="url(#iRXTsMd)" class="ajkq73jxq"/><path fill="url(#ittfgOd)" class="ajkq73jxq"/><g filter="url(#ifLXyBc)"><path fill="url(#iRtnCtc)" class="empsclb_z"/><path fill="url(#iFLgi9b)" class="empsclb_z"/><path fill="url(#iHoI0yb)" class="empsclb_z"/><path fill="url(#iaumesd)" class="empsclb_z"/><path fill="url(#i3pO2hc)" class="empsclb_z"/></g><g filter="url(#irWfgKc)"><path fill="url(#i2cEdqd)" class="r3imb_bxi"/></g><path fill="url(#iXxQ0Oe)" class="r3imb_bxi"/><path fill="url(#iBQf8Bd)" class="r3imb_bxi"/><defs><radialGradient id="i2DGTFc" cx="0" cy="0" r="1" gradientTransform="rotate(-118.51 9.554 9)scale(2.60459 2.95135)" gradientUnits="userSpaceOnUse"><stop class="wlzou1bho"/><stop offset="1" class="muarw1mje"/></radialGradient><radialGradient id="ijXBhVc" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 56.706 -44.622)scale(5.19975 6.34866)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="ivbNife" cx="0" cy="0" r="1" gradientTransform="matrix(2.29512 0 0 .98818 25.269 15.385)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="iIhwAPc" cx="0" cy="0" r="1" gradientTransform="matrix(2.87152 -.2136 .16697 2.24473 24.217 18.844)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="ivZISeb" cx="0" cy="0" r="1" gradientTransform="rotate(180 3.558 9.315)scale(2.00823)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="iuXO7Rz" cx="0" cy="0" r="1" gradientTransform="matrix(-12.3685 5.70352 -7.63407 -16.55501 21.303 17.608)" gradientUnits="userSpaceOnUse"><stop class="ox3481l0h"/><stop offset="1" class="l65mx1yct"/></radialGradient><radialGradient id="ia4qARb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.14646 1.82457 -1.2706 -2.88753 19.613 19.232)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="i4vpZmU" cx="0" cy="0" r="1" gradientTransform="rotate(-71.832 26.575 6.879)scale(7.86295 9.97663)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="i5szcGw" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.2025 -16.503 0 15.853 17.088)" gradientUnits="userSpaceOnUse"><stop offset=".633" class="huyrf746z"/><stop offset="1" class="lllw09ati"/></radialGradient><radialGradient id="iwEj3eb" cx="0" cy="0" r="1" gradientTransform="rotate(168.15 8.57 11.452)scale(12.9713 22.3327)" gradientUnits="userSpaceOnUse"><stop offset=".819" class="ugdux3jmg"/><stop offset="1" class="p3nv89fme"/></radialGradient><radialGradient id="iUB5yMo" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.18853 2.68593 0 20.242 16.813)" gradientUnits="userSpaceOnUse"><stop class="azt-9rbtm"/><stop offset="1" class="ci16jsbol"/></radialGradient><radialGradient id="iPs06MI" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.49614 2.86074 0 11.916 16.378)" gradientUnits="userSpaceOnUse"><stop class="zemyxxbjg"/><stop offset="1" class="k1zv-ubmt"/></radialGradient><radialGradient id="i4JeVAc" cx="0" cy="0" r="1" gradientTransform="rotate(105.092 4.495 13.288)scale(6.35584 5.08572)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="iMa2o4d" cx="0" cy="0" r="1" gradientTransform="matrix(4.58945 -5.12383 1.16012 1.03913 5.796 12.813)" gradientUnits="userSpaceOnUse"><stop class="gzixuxhsr"/><stop offset="1" class="ajl7zymqy"/></radialGradient><radialGradient id="ilqsKTb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.416 0 0 -11.3076 25.431 20.444)" gradientUnits="userSpaceOnUse"><stop class="fyxppic9g"/><stop offset="1" class="kq5b787yl"/></radialGradient><radialGradient id="iInlUyd" cx="0" cy="0" r="1" gradientTransform="rotate(-102.564 17.106 3.555)scale(3.98267 1.22742)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="iLGPhae" cx="0" cy="0" r="1" gradientTransform="matrix(-1.48226 0 0 -.4144 16.901 21.426)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="iAEOppd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.54296 -2.45425 0 20.015 17.495)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="izootwe" cx="0" cy="0" r="1" gradientTransform="matrix(-.44106 -.56836 .7825 -.60724 19.58 17.656)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ikEJsCP" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.54297 -2.45427 0 11.716 17.495)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iCev65d" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.402 3.457)scale(.93972 1.12958)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iAiNHae" cx="0" cy="0" r="1" gradientTransform="matrix(-.84218 3.75478 -8.78476 -1.97039 25.881 5.042)" gradientUnits="userSpaceOnUse"><stop class="s6vdf8bty"/><stop offset=".789" class="lxkykv_ud"/></radialGradient><radialGradient id="iBcFe2d" cx="0" cy="0" r="1" gradientTransform="matrix(2.09375 .53125 -1.15317 4.54483 20.347 6.676)" gradientUnits="userSpaceOnUse"><stop offset=".152" class="q2rl-9b2o"/><stop offset="1" class="fi285-b6u"/></radialGradient><radialGradient id="iZXhLkE" cx="0" cy="0" r="1" gradientTransform="matrix(1.5 -2.625 6.33197 3.61827 22.284 10.52)" gradientUnits="userSpaceOnUse"><stop class="p6ygghbxv"/><stop offset="1" class="ih_njzbst"/></radialGradient><radialGradient id="i5EYg7b" cx="0" cy="0" r="1" gradientTransform="matrix(.17188 2.91016 -14.53547 .85847 21.253 2.016)" gradientUnits="userSpaceOnUse"><stop class="nsg0945ca"/><stop offset="1" class="mcdrc7blw"/></radialGradient><radialGradient id="ixY9nMe" cx="0" cy="0" r="1" gradientTransform="matrix(1.45313 0 0 5.1925 20.8 3.332)" gradientUnits="userSpaceOnUse"><stop offset=".253" class="w7pk8_-qm"/><stop offset="1" class="wfm74pxcd"/></radialGradient><radialGradient id="i4dwOqd" cx="0" cy="0" r="1" gradientTransform="matrix(2.46875 1.71875 -3.03125 4.35398 17.69 9.05)" gradientUnits="userSpaceOnUse"><stop offset=".391" class="hc5vad6zv"/><stop offset="1" class="m71s56bwv"/></radialGradient><radialGradient id="iDxKDTb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.93844 1.49148 0 24.653 14.5)" gradientUnits="userSpaceOnUse"><stop offset=".306" class="b5m4mk31i"/><stop offset="1" class="o02xvvb7n"/></radialGradient><radialGradient id="iqQdf3d" cx="0" cy="0" r="1" gradientTransform="matrix(3.71875 0 0 .30337 18.753 8.675)" gradientUnits="userSpaceOnUse"><stop class="w98e9_6zv"/><stop offset="1" class="phr-zrige"/></radialGradient><radialGradient id="if2XEiA" cx="0" cy="0" r="1" gradientTransform="matrix(-4.28125 -.09372 .19553 -8.93238 21.565 5.582)" gradientUnits="userSpaceOnUse"><stop class="qnoj66lkr"/><stop offset="1" class="s_fkwccyi"/></radialGradient><radialGradient id="iUlKGqd" cx="0" cy="0" r="1" gradientTransform="matrix(11.55068 3.52232 -4.80864 15.76891 9.13 5.736)" gradientUnits="userSpaceOnUse"><stop offset=".633" class="rjs9uccph"/><stop offset=".952" class="x7ia8vuzd"/></radialGradient><radialGradient id="i8KfJqF" cx="0" cy="0" r="1" gradientTransform="matrix(1.11064 -4.72815 1.61144 .37853 16.84 4.594)" gradientUnits="userSpaceOnUse"><stop offset=".348" class="zz39r5b3o"/><stop offset="1" class="wvn8vtban"/></radialGradient><radialGradient id="iAMx8mb" cx="0" cy="0" r="1" gradientTransform="matrix(-.06346 1.33277 -6.75892 -.32185 9.193 7.386)" gradientUnits="userSpaceOnUse"><stop class="biviy7bfr"/><stop offset="1" class="ednzh9b6g"/></radialGradient><radialGradient id="iRXTsMd" cx="0" cy="0" r="1" gradientTransform="matrix(-13.48639 2.82409 -3.69438 -17.64244 17.539 7.513)" gradientUnits="userSpaceOnUse"><stop offset=".681" class="rq033_icj"/><stop offset="1" class="dbmxbxbzy"/></radialGradient><radialGradient id="ittfgOd" cx="0" cy="0" r="1" gradientTransform="matrix(.88851 -3.93483 2.3195 .52376 6.94 14.494)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="nmcqtrbfm"/><stop offset="1" class="w9crknafl"/></radialGradient><radialGradient id="iRtnCtc" cx="0" cy="0" r="1" gradientTransform="rotate(137.988 8.553 4.64)scale(9.89862 9.45071)" gradientUnits="userSpaceOnUse"><stop class="rnyxtsb4p"/><stop offset="1" class="isvyw7ooh"/></radialGradient><radialGradient id="iFLgi9b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78125 0 0 -4.75 18.44 3.488)" gradientUnits="userSpaceOnUse"><stop class="dqjzd9_8e"/><stop offset="1" class="jcrjf-b8x"/></radialGradient><radialGradient id="iaumesd" cx="0" cy="0" r="1" gradientTransform="matrix(5.90625 .125 -.02777 1.31192 10.128 4.113)" gradientUnits="userSpaceOnUse"><stop class="qw_ssccar"/><stop offset="1" class="mvpyyqb8k"/></radialGradient><radialGradient id="i3pO2hc" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 -.09375 .17757 2.4268 14.128 2.457)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="jdd1i0reo"/><stop offset="1" class="ixxpbv8hf"/></radialGradient><radialGradient id="i2cEdqd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.06249 1.65631 -3.03846 -14.79042 14.534 2.582)" gradientUnits="userSpaceOnUse"><stop class="nsmntj3ul"/><stop offset="1" class="q9wqsddqp"/></radialGradient><radialGradient id="iXxQ0Oe" cx="0" cy="0" r="1" gradientTransform="matrix(8.03125 .96875 -1.11478 9.24187 7.253 3.238)" gradientUnits="userSpaceOnUse"><stop offset=".869" class="atp4gmb-q"/><stop offset="1" class="qfleuzzqm"/></radialGradient><radialGradient id="iBQf8Bd" cx="0" cy="0" r="1" gradientTransform="matrix(2.71875 -2.3259 1.71042 1.99932 4.597 7.752)" gradientUnits="userSpaceOnUse"><stop class="lo97d1z0q"/><stop offset="1" class="qt9c-0dps"/></radialGradient><filter id="iOttkVc" width="6.27" height="6.12" x="3.894" y="15.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3103"/></filter><filter id="iSdUKpO" width="6.12" height="6.37" x="21.985" y="15.32" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3103"/></filter><filter id="i5BY4Lc" width="5.085" height="5.085" x="22.503" y="16.088" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3103" stdDeviation=".25"/></filter><filter id="iluM93c" width="4.785" height="4.785" x="4.598" y="16.238" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3103" stdDeviation=".175"/></filter><filter id="iNPxY1c" width="19.156" height="19.482" x="6.275" y="10.903" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.45098 0 0 0 0 0.278431 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3103"/></filter><filter id="igfuLQc" width="4.57" height="6.1" x="13.271" y="17.17" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3103" stdDeviation=".25"/></filter><filter id="iGEOSxc" width="4.07" height="5.6" x="13.83" y="17.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3103" stdDeviation=".125"/></filter><filter id="i5WBN5b" width="6.68" height="2.541" x="12.525" y="23.277" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3103" stdDeviation=".05"/></filter><filter id="iue9PCd" width="5.528" height="2.445" x="17.837" y="15.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.0705882 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3103"/></filter><filter id="iFIkQnc" width="5.528" height="2.445" x="8.366" y="15.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3103"/></filter><filter id="in8LvLc" width="4.484" height="1.895" x="8.623" y="13.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3103"/></filter><filter id="iizS74b" width="4.484" height="1.895" x="18.926" y="13.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3103"/></filter><filter id="iAXj5id" width="1.316" height="1.144" x="18.709" y="16.749" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3103" stdDeviation=".05"/></filter><filter id="i1nidJE" width="1.334" height="1.376" x="20.397" y="16.982" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3103" stdDeviation=".1"/></filter><filter id="iXhGPNb" width="1.515" height="1.618" x="11.947" y="16.861" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3103" stdDeviation=".1"/></filter><filter id="ix0E1Kc" width="1.556" height="1.159" x="10.422" y="16.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3103" stdDeviation=".05"/></filter><filter id="i2Iaiyd" width="3.758" height="1.318" x="19.254" y="13.755" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3103" stdDeviation=".1"/></filter><filter id="iwUJ6ld" width="3.758" height="1.318" x="8.886" y="13.755" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3103" stdDeviation=".1"/></filter><filter id="ipip6Jb" width="7.307" height="5.168" x="20.417" y="1.916" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.8 0 0 0 0 0.890196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3103"/></filter><filter id="i2uGWjF" width="12.925" height="6.714" x="14.465" y="8.129" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.992157 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3103"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.25"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.560784 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3103" result="effect2_innerShadow_4002_3103"/></filter><filter id="iMTWFKc" width="17.006" height="13.059" x="4.107" y="1.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.45098 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3103"/></filter><filter id="ifLXyBc" width="13.757" height="8.679" x="4.257" y="1.916" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.588235 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3103"/></filter><filter id="irWfgKc" width="10.523" height="5.986" x="4.357" y="1.816" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.686275 0 0 0 0 0.619608 0 0 0 0 0.752941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3103"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.701961 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3103" result="effect2_innerShadow_4002_3103"/></filter><linearGradient id="iK2Or7d" x1="3.894" x2="7.426" y1="18.796" y2="18.796" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="ifLg7td" x1="14.08" x2="15.865" y1="21.163" y2="21.163" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="iFfDame" x1="15.865" x2="15.865" y1="22.507" y2="21.315" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="inC5Mnc" x1="13.841" x2="14.718" y1="25.363" y2="24.009" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="iq9ESve" x1="21.495" x2="20.898" y1="17.598" y2="17.965" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iGmi1hd" x1="13.13" x2="12.533" y1="17.598" y2="17.965" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iLPDbid" x1="26.159" x2="15.409" y1="13.582" y2="13.582" gradientUnits="userSpaceOnUse"><stop class="qxbo6kk2p"/><stop offset="1" class="kkvh--b-a"/></linearGradient><linearGradient id="iHoI0yb" x1="4.357" x2="8.534" y1="9.551" y2="8.582" gradientUnits="userSpaceOnUse"><stop class="d2rffhbfx"/><stop offset="1" class="m1v3gnbun"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-wearing-turban-medium" /></template>
<style>
.a21bmlbcx {
  stop-color: var(--svg-color--945a73, #945A73);
  stop-opacity: 0;
}

.a6zm-0bnl {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M25.046 20.673a2.043 2.043 0 1 0 0-4.085a2.043 2.043 0 0 0 0 4.085");
}

.ab1vgh_ru {
  stop-color: var(--svg-color--cda38b, #CDA38B);
}

.ajkq73jxq {
  d: path("M20.946 2.016c.357 1.961.193 4.54-1.02 6.425c-.921 1.434-2.18 2.462-3.472 2.462H9.39c-.89 0-1.8.09-2.6 1.285c-.499.743-.485 1.88-.478 2.47l.001.166c-.364-.29-1.568-1.374-1.761-4.18c-.183-.857-.195-2.226-.195-2.985c0-.642.08-1.73.673-2.844c.743-1.393 1.71-2.8 5.42-2.8z");
}

.ajl7zymqy {
  stop-color: var(--svg-color--643446, #643446);
  stop-opacity: 0;
}

.ame5l9u0o {
  stop-color: var(--svg-color--906d53, #906D53);
  stop-opacity: 0;
}

.aotu-xwil {
  stop-color: var(--svg-color--ab8179, #AB8179);
}

.atp4gmb-q {
  stop-color: var(--svg-color--a5a0a9, #A5A0A9);
  stop-opacity: 0;
}

.azt-9rbtm {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
}

.b5m4mk31i {
  stop-color: var(--svg-color--b384b3, #B384B3);
}

.biviy7bfr {
  stop-color: var(--svg-color--bdbbbe, #BDBBBE);
}

.bpds6s3ke {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.865 24.168c-.99 0-1.921-.238-2.703-.655c-.268-.14-.555.168-.387.417a3.67 3.67 0 0 0 3.09 1.688a3.67 3.67 0 0 0 3.09-1.688c.168-.259-.119-.557-.386-.418a5.7 5.7 0 0 1-2.704.656Z");
}

.byhm9ccsg {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.344 14.118c-.613-.15-2.138-.075-3.158.655");
}

.cg1k0hirj {
  stop-color: var(--svg-color--8d645f, #8D645F);
}

.ci16jsbol {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnl1fccua {
  d: path("M6.99 20.673a2.043 2.043 0 1 0 0-4.085a2.043 2.043 0 0 0 0 4.085");
}

.cudan5oie {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m15.119 18.207l-1.3 3.233c-.207.665.288 1.33.99 1.33h1.495c.702 0 1.197-.675.99-1.33l-1.01-3.233c-.217-.716-.938-.716-1.165 0");
}

.d2rffhbfx {
  stop-color: var(--svg-color--b6b0bb, #B6B0BB);
}

.dbmxbxbzy {
  stop-color: var(--svg-color--bfb7c6, #BFB7C6);
}

.dqjzd9_8e {
  stop-color: var(--svg-color--ebeaec, #EBEAEC);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.ednzh9b6g {
  stop-color: var(--svg-color--bdbbbe, #BDBBBE);
  stop-opacity: 0;
}

.empsclb_z {
  d: path("M4.542 10.595c.457-.912 1.614-2.206 5.677-2.626c.406-.042 1.003-.06 1.672-.08c1.666-.05 3.775-.113 4.482-.594c.933-.445 1.973-3.245 1.54-5.28h-5.97l-6.989 2.95c-.524 1.062-.598 2.081-.597 2.695c0 .745.012 2.077.185 2.936");
}

.er6nvlbzc {
  d: path("M20.019 16.588a1.697 1.697 0 0 1 1.636 2.145h-3.28a1.7 1.7 0 0 1-.061-.448c0-.933.764-1.697 1.705-1.697");
}

.etyder0ew {
  d: path("M26.99 12.483c.005-1.482-1.085-2.607-1.93-3.105c-1.34-.79-3.268-1.004-4.104-.999H19.47l-4.955.805l.256 1.719h7.579c2.465 0 3.102 1.792 3.043 2.694l-.055 1.146c.217 0 .866-.237 1.115-.728c.203-.4.383-.937.537-1.532");
}

.f80hfjhpj {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
}

.fi285-b6u {
  stop-color: var(--svg-color--ece8f1, #ECE8F1);
  stop-opacity: 0;
}

.fifq1nuxy {
  fill: var(--svg-color--432a28, #432A28);
  d: path("m9.404 15.25l-.008.004h-.001a.51.51 0 0 1-.524-.875h.001l.002-.002l.006-.003l.018-.01q.021-.013.061-.034a6 6 0 0 1 1-.42c.647-.206 1.551-.38 2.527-.207a.51.51 0 0 1-.177 1.004c-.759-.134-1.487-.001-2.039.175a5 5 0 0 0-.866.367");
}

.ft5dv1b6b {
  fill: none;
}

.fyxppic9g {
  stop-color: var(--svg-color--c0967a, #C0967A);
}

.gelt6sv6v {
  d: path("M19.894 16.947c.121.162-.132.359-.42.574c-.287.214-.5.366-.62.204c-.121-.162.013-.467.3-.682c.288-.215.62-.258.74-.096");
}

.gg0p36txc {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.413 16.071c1.242 0 2.29.857 2.576 2.014a.52.52 0 0 1-.509.648h-4.243a.438.438 0 0 1-.432-.517a2.66 2.66 0 0 1 2.608-2.145");
}

.gwjnpqb1s {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M6.99 20.673a2.043 2.043 0 1 0 0-4.085a2.043 2.043 0 0 0 0 4.085");
}

.gzixuxhsr {
  stop-color: var(--svg-color--643446, #643446);
}

.hc5vad6zv {
  stop-color: var(--svg-color--bfb1c9, #BFB1C9);
}

.hjp773b9j {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
}

.hl813wbpa {
  stop-color: var(--svg-color--945a73, #945A73);
}

.hm31m3bmo {
  stop-color: var(--svg-color--875f54, #875F54);
}

.huyrf746z {
  stop-color: var(--svg-color--996173, #996173);
  stop-opacity: 0;
}

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.i16q27b0z {
  d: path("m15.138 17.944l-1.01 3.233c-.207.665.288 1.33.99 1.33h1.495c.701 0 1.197-.675.99-1.33l-1.01-3.233c-.217-.716-1.228-.716-1.455 0");
}

.ih_njzbst {
  stop-color: var(--svg-color--d3cfd9, #D3CFD9);
  stop-opacity: 0;
}

.isvyw7ooh {
  stop-color: var(--svg-color--c0bbc4, #C0BBC4);
}

.ixxpbv8hf {
  stop-color: var(--svg-color--bbb9bd, #BBB9BD);
  stop-opacity: 0;
}

.izc7dk1pl {
  stop-color: var(--svg-color--ab8179, #AB8179);
  stop-opacity: 0;
}

.j_jb06m8v {
  stop-color: var(--svg-color--a26d62, #A26D62);
  stop-opacity: 0;
}

.j1honvvth {
  cx: 11.2px;
  cy: 17.313px;
  rx: 0.741px;
  ry: 0.375px;
}

.jcrjf-b8x {
  stop-color: var(--svg-color--ebeaec, #EBEAEC);
  stop-opacity: 0;
}

.jdd1i0reo {
  stop-color: var(--svg-color--bbb9bd, #BBB9BD);
}

.jxp6cl9zo {
  d: path("M13.262 18.086c0-.549-.446-.914-.566-1.025l-.549.53l.338.688z");
}

.k1ya_5b2l {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m15.138 17.944l-1.01 3.233c-.207.665.288 1.33.99 1.33h1.495c.701 0 1.197-.675.99-1.33l-1.01-3.233c-.217-.716-1.228-.716-1.455 0");
}

.k1zv-ubmt {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
  stop-opacity: 0;
}

.k2qq48brl {
  d: path("M21.53 18.062a1.6 1.6 0 0 0-.44-.88l-.493.542l.223.434z");
}

.kkvh--b-a {
  stop-color: var(--svg-color--ddd6e4, #DDD6E4);
}

.kq5b787yl {
  stop-color: var(--svg-color--c0967a, #C0967A);
  stop-opacity: 0;
}

.l65mx1yct {
  stop-color: var(--svg-color--946568, #946568);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lllw09ati {
  stop-color: var(--svg-color--9e5f91, #9E5F91);
}

.lo97d1z0q {
  stop-color: var(--svg-color--bcb7c1, #BCB7C1);
}

.lxkykv_ud {
  stop-color: var(--svg-color--ebe6f2, #EBE6F2);
}

.m1v3gnbun {
  stop-color: var(--svg-color--b6b0bb, #B6B0BB);
  stop-opacity: 0;
}

.m71s56bwv {
  stop-color: var(--svg-color--e0dae8, #E0DAE8);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mcdrc7blw {
  stop-color: var(--svg-color--fafafa, #FAFAFA);
}

.muarw1mje {
  stop-color: var(--svg-color--814e62, #814E62);
  stop-opacity: 0;
}

.mvpyyqb8k {
  stop-color: var(--svg-color--b8b2be, #B8B2BE);
  stop-opacity: 0;
}

.n644_45yf {
  d: path("M11.712 16.588a1.697 1.697 0 0 0-1.636 2.145h3.279c.038-.147.062-.294.062-.448a1.71 1.71 0 0 0-1.705-1.697");
}

.n9tnz5ikc {
  d: path("M25.046 20.673a2.043 2.043 0 1 0 0-4.085a2.043 2.043 0 0 0 0 4.085");
}

.nmcqtrbfm {
  stop-color: var(--svg-color--a87b9c, #A87B9C);
}

.nsg0945ca {
  stop-color: var(--svg-color--dbdbdc, #DBDBDC);
}

.nsmntj3ul {
  stop-color: var(--svg-color--d2d1d3, #D2D1D3);
}

.nsn47rbed {
  d: path("M4.552 10.644c.193 2.806 1.397 3.89 1.761 4.18c0-.515-.074-1.815.476-2.636c.801-1.196 1.711-1.285 2.601-1.285h12.96c2.465 0 3.081 1.796 3.081 2.694l-.093 1.146c.217 0 .866-.237 1.115-.728c.65-1.285 1.068-3.963 1.161-5.527s.031-2.764-1.192-4.452c-.979-1.35-2.795-2.02-4.42-2.02H10.45c-3.712 0-4.678 1.406-5.42 2.8c-.594 1.114-.675 2.2-.674 2.843c0 .759.012 2.128.195 2.985");
}

.nzgowqbpe {
  fill: var(--svg-color--000, #000);
  d: path("M19.047 18.285c0-.54.432-.972.972-.972s.972.432.972.972a.96.96 0 0 1-.108.448h-1.72a.9.9 0 0 1-.116-.448");
}

.o02xvvb7n {
  stop-color: var(--svg-color--b384b3, #B384B3);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.opjf3kbfq {
  d: path("m20.417 2.016l.055 2.427c1.224-.031 3.562.082 5.578 1.227c.85.482 1.29.992 1.574 1.413c-.073-.969-.366-1.894-1.202-3.047c-.979-1.35-2.795-2.02-4.42-2.02z");
}

.ox3481l0h {
  stop-color: var(--svg-color--c79980, #C79980);
}

.p__cvka-s {
  fill: var(--svg-color--000, #000);
  d: path("M12.684 18.285a.97.97 0 0 0-.972-.972a.97.97 0 0 0-.972.972c0 .162.038.316.108.448h1.72a.96.96 0 0 0 .116-.448");
}

.p3nv89fme {
  stop-color: var(--svg-color--a47a6b, #A47A6B);
}

.p6ygghbxv {
  stop-color: var(--svg-color--d3cfd9, #D3CFD9);
}

.paaw4qgqj {
  fill: var(--svg-color--432a28, #432A28);
  fill-rule: evenodd;
  d: path("m22.962 14.38l-.262.437za.51.51 0 0 1-.524.875l-.009-.005a3 3 0 0 0-.215-.11a5 5 0 0 0-.651-.257c-.552-.176-1.28-.309-2.039-.175a.51.51 0 0 1-.177-1.005c.976-.172 1.88.002 2.526.208a6 6 0 0 1 1 .42q.04.02.062.034l.018.01l.006.003l.002.002z");
}

.phr-zrige {
  stop-color: var(--svg-color--d0ccd3, #D0CCD3);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkudt8e8m {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M15.865 24.168c-.99 0-1.921-.238-2.703-.655c-.268-.14-.555.168-.387.417a3.67 3.67 0 0 0 3.09 1.688a3.67 3.67 0 0 0 3.09-1.688c.168-.259-.119-.557-.386-.418a5.7 5.7 0 0 1-2.704.656");
}

.q0pkd7b8s {
  d: path("m25.358 14.492l-.02.25h.02l-.028 6.334c-.235 5.33-4.397 8.908-9.477 8.908s-9.243-3.579-9.477-8.908l-.095-6.028q.003-.106-.006-.255l.038.031l-.001-.166c-.007-.59-.02-1.727.477-2.47c.801-1.196 1.711-1.285 2.601-1.285h12.96c2.465 0 3.081 1.796 3.081 2.694l-.052.646l-.02.031z");
}

.q2rl-9b2o {
  stop-color: var(--svg-color--cfcad4, #CFCAD4);
}

.q9wqsddqp {
  stop-color: var(--svg-color--b5b4b6, #B5B4B6);
}

.qfleuzzqm {
  stop-color: var(--svg-color--a5a0a9, #A5A0A9);
}

.qnoj66lkr {
  stop-color: var(--svg-color--f5f4f6, #F5F4F6);
}

.qt9c-0dps {
  stop-color: var(--svg-color--bcb7c1, #BCB7C1);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw_ssccar {
  stop-color: var(--svg-color--b8b2be, #B8B2BE);
}

.qxbo6kk2p {
  stop-color: var(--svg-color--eee8f4, #EEE8F4);
}

.r3imb_bxi {
  d: path("M4.357 7.752c.557-.67 1.563-1.613 2.897-1.974c1.879-.509 4.836-.733 6.069-.82c.45.025 1.556-.442 1.556-1.61c0-.434-.016-.89-.053-1.332H10.45c-3.712 0-4.678 1.406-5.42 2.8c-.594 1.114-.675 2.2-.674 2.843z");
}

.rdwuebbdx {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.894 16.947c.121.162-.132.359-.42.574c-.287.214-.5.366-.62.204c-.121-.162.013-.467.3-.682c.288-.215.62-.258.74-.096");
}

.rjs9uccph {
  stop-color: var(--svg-color--d1cad9, #D1CAD9);
  stop-opacity: 0;
}

.rnyxtsb4p {
  stop-color: var(--svg-color--ddddde, #DDDDDE);
}

.rq033_icj {
  stop-color: var(--svg-color--bfb7c6, #BFB7C6);
  stop-opacity: 0;
}

.s_fkwccyi {
  stop-color: var(--svg-color--cfc8d7, #CFC8D7);
}

.s6qc0ccmr {
  cx: 11.2px;
  cy: 17.313px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.741px;
  ry: 0.375px;
}

.s6vdf8bty {
  stop-color: var(--svg-color--f8f6fb, #F8F6FB);
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.svu__lk9m {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M19.554 14.118c.614-.15 2.139-.075 3.159.655");
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t6506rynz {
  d: path("M25.046 21.69a3.06 3.06 0 1 0 0-6.12a3.06 3.06 0 0 0 0 6.12");
}

.t9v208shd {
  stop-color: var(--svg-color--a26d62, #A26D62);
}

.tm3kujhuf {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.318 16.07a2.656 2.656 0 0 0-2.577 2.014a.52.52 0 0 0 .51.648h4.243c.27 0 .486-.247.432-.517a2.665 2.665 0 0 0-2.608-2.144");
}

.u6m78ac0i {
  stop-color: var(--svg-color--604138, #604138);
}

.ugdux3jmg {
  stop-color: var(--svg-color--a47a6b, #A47A6B);
  stop-opacity: 0;
}

.us3ue9b4r {
  stop-color: var(--svg-color--995c76, #995C76);
}

.v4cuahbfk {
  stop-color: var(--svg-color--906d53, #906D53);
}

.v5m4qhb2r {
  stop-color: var(--svg-color--c4967a, #C4967A);
  stop-opacity: 0;
}

.vh12xwf7a {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
}

.vw42v6b3v {
  stop-color: var(--svg-color--c4967a, #C4967A);
}

.w4wkyodwa {
  stop-color: var(--svg-color--6c4640, #6C4640);
}

.w5re42dqy {
  stop-color: var(--svg-color--6c4640, #6C4640);
  stop-opacity: 0;
}

.w7pk8_-qm {
  stop-color: var(--svg-color--e2dce8, #E2DCE8);
}

.w98e9_6zv {
  stop-color: var(--svg-color--d0ccd3, #D0CCD3);
}

.w9crknafl {
  stop-color: var(--svg-color--a87b9c, #A87B9C);
  stop-opacity: 0;
}

.wfm74pxcd {
  stop-color: var(--svg-color--e2dce8, #E2DCE8);
  stop-opacity: 0;
}

.wh0vrhbzi {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
  stop-opacity: 0;
}

.wlzou1bho {
  stop-color: var(--svg-color--814e62, #814E62);
}

.wvn8vtban {
  stop-color: var(--svg-color--c5c2c8, #C5C2C8);
  stop-opacity: 0;
}

.x7ia8vuzd {
  stop-color: var(--svg-color--f1edf4, #F1EDF4);
}

.xqzyuky4n {
  stop-color: var(--svg-color--b28279, #B28279);
}

.y0k8bfqtb {
  fill: var(--svg-color--2f2c32, #2F2C32);
  d: path("M18.037 17.548c.505-.887 1.273-1.588 2.924-1.588c.723 0 1.42.2 2.04.7c.512.414.443.942.047 1.14l-1.057.604c-1.24-.4-2.61-.455-3.954-.856");
}

.y3sbsbvfu {
  fill: var(--svg-color--27232a, #27232A);
  d: path("M13.694 17.548c-.505-.887-1.272-1.588-2.924-1.588c-.723 0-1.42.2-2.04.7c-.512.414-.443.942-.047 1.14l1.057.604c1.24-.4 2.61-.455 3.954-.856");
}

.yiz6fvgdb {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

.zemyxxbjg {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
}

.zk0zz6s7t {
  d: path("M6.954 21.69a3.06 3.06 0 1 0 0-6.12a3.06 3.06 0 0 0 0 6.12");
}

.zz39r5b3o {
  stop-color: var(--svg-color--c5c2c8, #C5C2C8);
}

</style>
