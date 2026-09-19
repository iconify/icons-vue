<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iF1adAb)"><circle fill="url(#iMSoM3Y)" class="pih07rvsm"/></g><g filter="url(#irqCsIZ)"><circle fill="url(#i1Ypjne)" class="r_3u_vbfs"/></g><g filter="url(#iqLxbYd)"><circle fill="url(#iUGwEIX)" class="og18zf_2p"/><circle fill="url(#ixFZ9cc)" class="og18zf_2p"/></g><g filter="url(#iBWX7qe)"><circle class="gcvaa1bfa"/><circle fill="url(#isVm8sb)" class="h4jx91gxb"/><circle fill="url(#i2hDehe)" class="h4jx91gxb"/></g><g filter="url(#i7a3PTb)"><path fill="url(#iBwpx6b)" class="qr00he01g"/><path fill="url(#iHipp4d)" class="qr00he01g"/><path fill="url(#iLaj7Cb)" class="qr00he01g"/><path fill="url(#icORR1C)" class="qr00he01g"/><path fill="url(#iGQIXUc)" class="qr00he01g"/></g><path fill="url(#i1s8Czb)" class="qr00he01g"/><path fill="url(#i25DUnA)" class="qr00he01g"/><path fill="url(#i1pNEZv)" class="qr00he01g"/><path fill="url(#i3C6Aqd)" class="qr00he01g"/><g filter="url(#iuHdZFd)"><path class="kmrvcqblp"/></g><g filter="url(#il1OUzd)"><path class="akpcf_1aq"/><path fill="url(#ieI5sXc)" class="yk38wibgb"/><path fill="url(#iCVV7Ae)" class="yk38wibgb"/><path fill="url(#itPgIdb)" class="yk38wibgb"/><path fill="url(#i3IsO9c)" class="yk38wibgb"/></g><g filter="url(#iXru5jd)"><path fill="url(#iUOyHtc)" class="nmi7nhbkg"/></g><g filter="url(#iHcg6dd)"><path stroke="url(#it4Imqc)" class="up3xx-bty"/></g><path class="jr4syfbsj"/><g filter="url(#iKO8UZd)"><path class="y75qcccyl"/></g><g filter="url(#iOgreqe)"><path class="vp13rcbvk"/></g><path class="ox0pvvbuu"/><path fill="url(#i7fcD5c)" class="h24wpj6ga"/><path class="thnicubcj"/><g filter="url(#iw3fmPz)"><path class="mv2l0x_hp"/><path fill="url(#izPJWpb)" class="l69kqznog"/></g><g filter="url(#izCbuLd)"><path fill="url(#iITljkd)" class="v6-gl02mj"/></g><path class="u4es0m23n"/><path fill="url(#iMVqk5c)" class="uhibk-oxd"/><path class="l3rq1q25q"/><g filter="url(#i9GEZmd)"><path fill="url(#ixv6qic)" class="ia_pnn16t"/></g><g filter="url(#iqJpxeV)"><ellipse transform="rotate(-27.914 11.394 16.54)" class="dbz5x-bgq"/><ellipse fill="url(#iaP7Qne)" transform="rotate(-27.914 11.394 16.54)" class="try973jmd"/></g><g filter="url(#iZWiHrf)"><path stroke="url(#ielT5qd)" class="wf-a-tclc"/></g><g filter="url(#i5xdwLd)"><path stroke="url(#itakbSb)" class="vzlyfrf0q"/></g><path fill="url(#ibj1roc)" class="wy1fk_yef"/><path fill="url(#iBQ20ub)" class="wy1fk_yef"/><path fill="url(#ihki6sd)" class="wy1fk_yef"/><g filter="url(#iAgZpSc)"><path fill="url(#iEByZhb)" class="en_msabfh"/><path fill="url(#iMYQkre)" class="en_msabfh"/></g><g filter="url(#iR1lgzb)"><path fill="url(#ige8EPV)" class="im-saguzd"/></g><path fill="url(#idgCtfe)" class="im-saguzd"/><path fill="url(#inpLpsc)" class="im-saguzd"/><path fill="url(#iDHl7rb)" class="im-saguzd"/><g filter="url(#iXBLYpb)"><path fill="url(#iZDxEcf)" class="jjdj44b8t"/></g><path fill="url(#iGKjxDs)" class="jjdj44b8t"/><path fill="url(#iLGjvBb)" class="jjdj44b8t"/><path fill="url(#iYIbNWc)" class="jjdj44b8t"/><path fill="url(#ivVlysd)" class="jjdj44b8t"/><path fill="url(#iP8qzcd)" class="jjdj44b8t"/><g filter="url(#iWuvlAb)"><path fill="url(#iC9jG5b)" class="w_gy_4baw"/><path fill="url(#inqoqme)" class="w_gy_4baw"/><path fill="url(#iPrnqyb)" class="w_gy_4baw"/><path fill="url(#iwhzqme)" class="w_gy_4baw"/><path fill="url(#iORYy2d)" class="w_gy_4baw"/></g><g filter="url(#ihwpxky)"><path fill="url(#iQy9mYb)" class="w3hticb3q"/></g><path fill="url(#ifS5Cfc)" class="w3hticb3q"/><path fill="url(#i6j4BGc)" class="w3hticb3q"/><defs><radialGradient id="iMSoM3Y" cx="0" cy="0" r="1" gradientTransform="matrix(3.28027 0 0 5.74049 3.988 17.994)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="ixFZ9cc" cx="0" cy="0" r="1" gradientTransform="matrix(1.5453 -1.12522 1.2843 1.76377 25.587 17.499)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="isVm8sb" cx="0" cy="0" r="1" gradientTransform="matrix(1.53514 -2.82355 1.65263 .89852 24.814 19.53)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="i2hDehe" cx="0" cy="0" r="1" gradientTransform="rotate(44.708 -9.433 39.262)scale(.68196 .87914)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="icORR1C" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.44325 3.00707 0 20.37 15.617)" gradientUnits="userSpaceOnUse"><stop class="m459pab_j"/><stop offset="1" class="rcuz4uefu"/></radialGradient><radialGradient id="iGQIXUc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.59987 3.23317 0 11.85 15.555)" gradientUnits="userSpaceOnUse"><stop class="hplqxft1w"/><stop offset="1" class="ay1rn8bxh"/></radialGradient><radialGradient id="i1pNEZv" cx="0" cy="0" r="1" gradientTransform="matrix(0 15.9057 -21.5911 0 16.038 14.396)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="sd37djb7x"/><stop offset="1" class="xohlojkms"/></radialGradient><radialGradient id="i3C6Aqd" cx="0" cy="0" r="1" gradientTransform="matrix(4.9834 -5.04983 1.30925 1.29203 6.086 12.992)" gradientUnits="userSpaceOnUse"><stop class="xyw2spbat"/><stop offset="1" class="qdssebgqk"/></radialGradient><radialGradient id="i3IsO9c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36805 -1.18247 0 16.596 20.997)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="i7fcD5c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.5162 -2.41169 0 20.057 16.72)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="izPJWpb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 13.948 3.631)scale(.70695 .97329)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iMVqk5c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51628 -2.41181 0 11.9 16.72)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iaP7Qne" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.114 2.97)scale(.92346 1.11004)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ibj1roc" cx="0" cy="0" r="1" gradientTransform="matrix(-.84218 3.75478 -8.78476 -1.97039 26.108 5.063)" gradientUnits="userSpaceOnUse"><stop class="s6vdf8bty"/><stop offset=".789" class="lxkykv_ud"/></radialGradient><radialGradient id="iBQ20ub" cx="0" cy="0" r="1" gradientTransform="matrix(2.09375 .53125 -1.15317 4.54483 20.574 6.697)" gradientUnits="userSpaceOnUse"><stop offset=".152" class="q2rl-9b2o"/><stop offset="1" class="fi285-b6u"/></radialGradient><radialGradient id="ihki6sd" cx="0" cy="0" r="1" gradientTransform="matrix(1.5 -2.625 6.33197 3.61827 22.512 10.54)" gradientUnits="userSpaceOnUse"><stop class="p6ygghbxv"/><stop offset="1" class="ih_njzbst"/></radialGradient><radialGradient id="iEByZhb" cx="0" cy="0" r="1" gradientTransform="matrix(.17188 2.91016 -14.53547 .85847 21.48 2.036)" gradientUnits="userSpaceOnUse"><stop class="nsg0945ca"/><stop offset="1" class="mcdrc7blw"/></radialGradient><radialGradient id="iMYQkre" cx="0" cy="0" r="1" gradientTransform="matrix(1.45313 0 0 5.1925 21.027 3.353)" gradientUnits="userSpaceOnUse"><stop offset=".253" class="w7pk8_-qm"/><stop offset="1" class="wfm74pxcd"/></radialGradient><radialGradient id="idgCtfe" cx="0" cy="0" r="1" gradientTransform="matrix(2.46875 1.71875 -3.03125 4.35398 17.918 9.071)" gradientUnits="userSpaceOnUse"><stop offset=".391" class="hc5vad6zv"/><stop offset="1" class="m71s56bwv"/></radialGradient><radialGradient id="inpLpsc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.93844 1.49148 0 24.88 14.52)" gradientUnits="userSpaceOnUse"><stop offset=".306" class="b5m4mk31i"/><stop offset="1" class="o02xvvb7n"/></radialGradient><radialGradient id="iDHl7rb" cx="0" cy="0" r="1" gradientTransform="matrix(3.71875 0 0 .30337 18.98 8.696)" gradientUnits="userSpaceOnUse"><stop class="w98e9_6zv"/><stop offset="1" class="phr-zrige"/></radialGradient><radialGradient id="iZDxEcf" cx="0" cy="0" r="1" gradientTransform="matrix(-4.28125 -.09372 .19553 -8.93238 21.793 5.603)" gradientUnits="userSpaceOnUse"><stop class="qnoj66lkr"/><stop offset="1" class="s_fkwccyi"/></radialGradient><radialGradient id="iGKjxDs" cx="0" cy="0" r="1" gradientTransform="matrix(11.55068 3.52232 -4.80864 15.76891 9.357 5.757)" gradientUnits="userSpaceOnUse"><stop offset=".633" class="rjs9uccph"/><stop offset=".952" class="x7ia8vuzd"/></radialGradient><radialGradient id="iLGjvBb" cx="0" cy="0" r="1" gradientTransform="matrix(1.11064 -4.72815 1.61144 .37853 17.068 4.614)" gradientUnits="userSpaceOnUse"><stop offset=".348" class="zz39r5b3o"/><stop offset="1" class="wvn8vtban"/></radialGradient><radialGradient id="iYIbNWc" cx="0" cy="0" r="1" gradientTransform="matrix(-.06346 1.33277 -6.75892 -.32185 9.42 7.407)" gradientUnits="userSpaceOnUse"><stop class="biviy7bfr"/><stop offset="1" class="ednzh9b6g"/></radialGradient><radialGradient id="ivVlysd" cx="0" cy="0" r="1" gradientTransform="matrix(-13.48639 2.82409 -3.69438 -17.64244 17.766 7.534)" gradientUnits="userSpaceOnUse"><stop offset=".681" class="rq033_icj"/><stop offset="1" class="dbmxbxbzy"/></radialGradient><radialGradient id="iP8qzcd" cx="0" cy="0" r="1" gradientTransform="matrix(.88851 -3.93483 2.3195 .52376 7.168 14.515)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="nmcqtrbfm"/><stop offset="1" class="w9crknafl"/></radialGradient><radialGradient id="iC9jG5b" cx="0" cy="0" r="1" gradientTransform="rotate(137.988 8.663 4.694)scale(9.89862 9.45071)" gradientUnits="userSpaceOnUse"><stop class="rnyxtsb4p"/><stop offset="1" class="isvyw7ooh"/></radialGradient><radialGradient id="inqoqme" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78125 0 0 -4.75 18.668 3.509)" gradientUnits="userSpaceOnUse"><stop class="dqjzd9_8e"/><stop offset="1" class="jcrjf-b8x"/></radialGradient><radialGradient id="iwhzqme" cx="0" cy="0" r="1" gradientTransform="matrix(5.90625 .125 -.02777 1.31192 10.355 4.134)" gradientUnits="userSpaceOnUse"><stop class="qw_ssccar"/><stop offset="1" class="mvpyyqb8k"/></radialGradient><radialGradient id="iORYy2d" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 -.09375 .17757 2.4268 14.355 2.478)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="jdd1i0reo"/><stop offset="1" class="ixxpbv8hf"/></radialGradient><radialGradient id="iQy9mYb" cx="0" cy="0" r="1" gradientTransform="matrix(-8.06249 1.65631 -3.03846 -14.79042 14.761 2.603)" gradientUnits="userSpaceOnUse"><stop class="nsmntj3ul"/><stop offset="1" class="q9wqsddqp"/></radialGradient><radialGradient id="ifS5Cfc" cx="0" cy="0" r="1" gradientTransform="matrix(8.03125 .96875 -1.11478 9.24187 7.48 3.259)" gradientUnits="userSpaceOnUse"><stop offset=".869" class="atp4gmb-q"/><stop offset="1" class="qfleuzzqm"/></radialGradient><radialGradient id="i6j4BGc" cx="0" cy="0" r="1" gradientTransform="matrix(2.71875 -2.3259 1.71042 1.99932 4.824 7.773)" gradientUnits="userSpaceOnUse"><stop class="lo97d1z0q"/><stop offset="1" class="qt9c-0dps"/></radialGradient><filter id="iF1adAb" width="6.441" height="6.241" x="3.988" y="14.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3110"/></filter><filter id="irqCsIZ" width="4.72" height="4.72" x="4.749" y="15.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3110" stdDeviation=".25"/></filter><filter id="iqLxbYd" width="6.491" height="6.491" x="21.771" y="14.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3110"/></filter><filter id="iBWX7qe" width="4.72" height="4.72" x="22.532" y="15.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3110" stdDeviation=".25"/></filter><filter id="i7a3PTb" width="19.116" height="19.29" x="6.537" y="10.924" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.462745 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3110"/></filter><filter id="iuHdZFd" width="4.79" height="6.512" x="13.142" y="16.488" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3110" stdDeviation=".375"/></filter><filter id="il1OUzd" width="4.008" height="5.512" x="13.98" y="16.683" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3110" stdDeviation=".125"/></filter><filter id="iXru5jd" width="4.008" height="5.512" x="13.98" y="16.378" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3110" stdDeviation=".125"/></filter><filter id="iHcg6dd" width="6.414" height="2.405" x="12.777" y="22.998" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3110" stdDeviation=".05"/></filter><filter id="iKO8UZd" width="5.352" height="3.153" x="18.193" y="11.521" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3110"/></filter><filter id="iOgreqe" width="5.353" height="3.153" x="8.571" y="11.521" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3110"/></filter><filter id="iw3fmPz" width="1.297" height="1.127" x="18.771" y="15.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3110" stdDeviation=".05"/></filter><filter id="izCbuLd" width="1.318" height="1.359" x="20.428" y="16.211" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3110" stdDeviation=".1"/></filter><filter id="i9GEZmd" width="1.496" height="1.597" x="12.125" y="16.093" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3110" stdDeviation=".1"/></filter><filter id="iqJpxeV" width="1.533" height="1.143" x="10.628" y="15.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3110" stdDeviation=".05"/></filter><filter id="iZWiHrf" width="4.707" height="2.056" x="18.463" y="11.952" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3110" stdDeviation=".25"/></filter><filter id="i5xdwLd" width="4.852" height="2.162" x="8.706" y="12.071" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3110" stdDeviation=".25"/></filter><filter id="iAgZpSc" width="7.307" height="5.168" x="20.645" y="1.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.8 0 0 0 0 0.890196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3110"/></filter><filter id="iR1lgzb" width="12.925" height="6.714" x="14.693" y="8.15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.992157 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3110"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.25"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.560784 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3110" result="effect2_innerShadow_4002_3110"/></filter><filter id="iXBLYpb" width="17.006" height="13.059" x="4.334" y="1.786" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.45098 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3110"/></filter><filter id="iWuvlAb" width="13.757" height="8.679" x="4.484" y="1.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.588235 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3110"/></filter><filter id="ihwpxky" width="10.523" height="5.986" x="4.584" y="1.836" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.686275 0 0 0 0 0.619608 0 0 0 0 0.752941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3110"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.701961 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3110" result="effect2_innerShadow_4002_3110"/></filter><linearGradient id="i1Ypjne" x1="7.109" x2="5.911" y1="18.515" y2="18.515" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="iUGwEIX" x1="26.922" x2="25.392" y1="15.954" y2="20.695" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="iBwpx6b" x1="23.528" x2="9.253" y1="18.722" y2="20.849" gradientUnits="userSpaceOnUse"><stop class="z8y6fgvmn"/><stop offset="1" class="tqgh1edwg"/></linearGradient><linearGradient id="iHipp4d" x1="5.437" x2="11.714" y1="21.577" y2="21.79" gradientUnits="userSpaceOnUse"><stop class="z3n_1mwef"/><stop offset="1" class="rvf3-0bfj"/></linearGradient><linearGradient id="iLaj7Cb" x1="5.898" x2="9.415" y1="23.762" y2="23.636" gradientUnits="userSpaceOnUse"><stop class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="i1s8Czb" x1="6.537" x2="8.777" y1="21.531" y2="21.464" gradientUnits="userSpaceOnUse"><stop class="hon1eivbz"/><stop offset="1" class="zbbitdbrp"/></linearGradient><linearGradient id="i25DUnA" x1="25.654" x2="22.93" y1="23.125" y2="23.125" gradientUnits="userSpaceOnUse"><stop class="sqxrh1b6n"/><stop offset="1" class="eodwsybla"/></linearGradient><linearGradient id="ieI5sXc" x1="14.368" x2="16.122" y1="19.954" y2="19.954" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="iCVV7Ae" x1="17.738" x2="15.821" y1="20.557" y2="20.53" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="itPgIdb" x1="16.348" x2="16.348" y1="21.945" y2="20.873" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="iUOyHtc" x1="15.984" x2="15.984" y1="16.628" y2="19.019" gradientUnits="userSpaceOnUse"><stop class="h39opibto"/><stop offset="1" class="l8wmcc2hr"/></linearGradient><linearGradient id="it4Imqc" x1="14.045" x2="14.858" y1="24.964" y2="23.679" gradientUnits="userSpaceOnUse"><stop class="qny5yebdb"/><stop offset=".663" class="a1paejb_z"/></linearGradient><linearGradient id="iITljkd" x1="21.51" x2="20.924" y1="16.82" y2="17.181" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ixv6qic" x1="13.291" x2="12.705" y1="16.82" y2="17.181" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ielT5qd" x1="21.54" x2="20.754" y1="12.82" y2="11.215" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="itakbSb" x1="11.624" x2="9.401" y1="12.582" y2="11.649" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="ige8EPV" x1="26.387" x2="15.636" y1="13.602" y2="13.602" gradientUnits="userSpaceOnUse"><stop class="qxbo6kk2p"/><stop offset="1" class="kkvh--b-a"/></linearGradient><linearGradient id="iPrnqyb" x1="4.584" x2="8.761" y1="9.572" y2="8.603" gradientUnits="userSpaceOnUse"><stop class="d2rffhbfx"/><stop offset="1" class="m1v3gnbun"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-wearing-turban-light" /></template>
<style>
.a1paejb_z {
  stop-color: var(--svg-color--f6bdb0, #F6BDB0);
  stop-opacity: 0;
}

.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.akpcf_1aq {
  fill: var(--svg-color--fbc4b1, #FBC4B1);
  d: path("m15.27 17.46l-.994 3.178a1.008 1.008 0 0 0 .973 1.307h1.47c.689 0 1.175-.664.973-1.307l-.994-3.177c-.213-.704-1.206-.704-1.429 0");
}

.atp4gmb-q {
  stop-color: var(--svg-color--a5a0a9, #A5A0A9);
  stop-opacity: 0;
}

.ay1rn8bxh {
  stop-color: var(--svg-color--d0958d, #D0958D);
  stop-opacity: 0;
}

.b5m4mk31i {
  stop-color: var(--svg-color--b384b3, #B384B3);
}

.biviy7bfr {
  stop-color: var(--svg-color--bdbbbe, #BDBBBE);
}

.btip4dbzo {
  stop-color: var(--svg-color--dfa790, #DFA790);
  stop-opacity: 0;
}

.bw8j_5egh {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.d2rffhbfx {
  stop-color: var(--svg-color--b6b0bb, #B6B0BB);
}

.dbmxbxbzy {
  stop-color: var(--svg-color--bfb7c6, #BFB7C6);
}

.dbz5x-bgq {
  cx: 11.394px;
  cy: 16.541px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.728px;
  ry: 0.369px;
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

.en_msabfh {
  d: path("m20.645 2.036l.055 2.427c1.223-.03 3.562.083 5.578 1.227c.849.482 1.289.993 1.573 1.414c-.072-.969-.366-1.894-1.202-3.047c-.978-1.35-2.794-2.02-4.42-2.02z");
}

.eodwsybla {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
  stop-opacity: 0;
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.fi285-b6u {
  stop-color: var(--svg-color--ece8f1, #ECE8F1);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.gcvaa1bfa {
  cx: 24.892px;
  cy: 17.994px;
  r: 1.86px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
}

.h24wpj6ga {
  d: path("M20.06 15.828a1.668 1.668 0 0 1 1.608 2.107h-3.222a1.7 1.7 0 0 1-.061-.44c0-.917.75-1.667 1.675-1.667");
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h39opibto {
  stop-color: var(--svg-color--f5c3ac, #F5C3AC);
}

.h4jx91gxb {
  cx: 24.892px;
  cy: 17.994px;
  r: 1.86px;
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.hc5vad6zv {
  stop-color: var(--svg-color--bfb1c9, #BFB1C9);
}

.hmo3unbrx {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
}

.hon1eivbz {
  stop-color: var(--svg-color--e8ad96, #E8AD96);
}

.hplqxft1w {
  stop-color: var(--svg-color--d0958d, #D0958D);
}

.ia_pnn16t {
  d: path("M13.421 17.3c0-.54-.438-.899-.557-1.007l-.539.52l.332.676z");
}

.ih_njzbst {
  stop-color: var(--svg-color--d3cfd9, #D3CFD9);
  stop-opacity: 0;
}

.im-saguzd {
  d: path("M27.218 12.504c.005-1.483-1.086-2.607-1.931-3.106c-1.34-.79-3.267-1.003-4.103-.998h-1.487l-4.954.805l.255 1.719h7.58c2.464 0 3.101 1.792 3.043 2.694l-.056 1.145c.217 0 .867-.236 1.115-.727c.203-.4.383-.937.538-1.532");
}

.isvyw7ooh {
  stop-color: var(--svg-color--c0bbc4, #C0BBC4);
}

.ixxpbv8hf {
  stop-color: var(--svg-color--bbb9bd, #BBB9BD);
  stop-opacity: 0;
}

.jcrjf-b8x {
  stop-color: var(--svg-color--ebeaec, #EBEAEC);
  stop-opacity: 0;
}

.jdd1i0reo {
  stop-color: var(--svg-color--bbb9bd, #BBB9BD);
}

.jjdj44b8t {
  d: path("M21.173 2.036c.357 1.962.193 4.541-1.019 6.426c-.922 1.433-2.181 2.462-3.473 2.462H9.618c-.89 0-1.8.089-2.602 1.285c-.497.743-.484 1.88-.477 2.47l.001.166c-.364-.29-1.567-1.374-1.76-4.18c-.183-.857-.196-2.226-.196-2.985c0-.643.08-1.73.674-2.844c.742-1.393 1.709-2.8 5.42-2.8z");
}

.jr4syfbsj {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M15.984 23.845c-.949 0-1.84-.223-2.59-.614c-.255-.13-.53.158-.37.39a3.54 3.54 0 0 0 2.96 1.582a3.54 3.54 0 0 0 2.959-1.581c.16-.242-.114-.521-.37-.39c-.75.39-1.631.613-2.59.613");
}

.kkvh--b-a {
  stop-color: var(--svg-color--ddd6e4, #DDD6E4);
}

.kmrvcqblp {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m15.469 17.766l-1.533 3.177c-.19.653.266 1.307.912 1.307h1.378c.646 0 1.102-.664.912-1.307l-.931-3.177c-.2-.704-.529-.704-.738 0");
}

.l3rq1q25q {
  fill: var(--svg-color--000, #000);
  d: path("M12.852 17.496a.95.95 0 0 0-.955-.956a.95.95 0 0 0-.955.956c0 .159.038.31.106.44h1.69a.95.95 0 0 0 .114-.44");
}

.l69kqznog {
  d: path("M19.938 16.18c.119.16-.13.353-.412.564c-.283.212-.492.36-.61.201c-.12-.159.013-.459.295-.67c.283-.211.608-.253.727-.094");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l8wmcc2hr {
  stop-color: var(--svg-color--f5c3ac, #F5C3AC);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lo97d1z0q {
  stop-color: var(--svg-color--bcb7c1, #BCB7C1);
}

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.lxkykv_ud {
  stop-color: var(--svg-color--ebe6f2, #EBE6F2);
}

.m1v3gnbun {
  stop-color: var(--svg-color--b6b0bb, #B6B0BB);
  stop-opacity: 0;
}

.m459pab_j {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
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

.mv2l0x_hp {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.938 16.18c.119.16-.13.353-.412.564c-.283.212-.492.36-.61.201c-.12-.159.013-.459.295-.67c.283-.211.608-.253.727-.094");
}

.mvpyyqb8k {
  stop-color: var(--svg-color--b8b2be, #B8B2BE);
  stop-opacity: 0;
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.nmcqtrbfm {
  stop-color: var(--svg-color--a87b9c, #A87B9C);
}

.nmi7nhbkg {
  d: path("m15.27 17.156l-.994 3.177a1.008 1.008 0 0 0 .973 1.307h1.47c.689 0 1.175-.664.973-1.308l-.994-3.177c-.213-.703-1.206-.703-1.429 0");
}

.nsg0945ca {
  stop-color: var(--svg-color--dbdbdc, #DBDBDC);
}

.nsmntj3ul {
  stop-color: var(--svg-color--d2d1d3, #D2D1D3);
}

.o02xvvb7n {
  stop-color: var(--svg-color--b384b3, #B384B3);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.og18zf_2p {
  cx: 24.891px;
  cy: 17.994px;
  r: 3.121px;
}

.ox0pvvbuu {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.447 15.32a2.61 2.61 0 0 1 2.532 1.979a.512.512 0 0 1-.5.637h-4.17a.43.43 0 0 1-.424-.508a2.61 2.61 0 0 1 2.562-2.108");
}

.p6ygghbxv {
  stop-color: var(--svg-color--d3cfd9, #D3CFD9);
}

.phr-zrige {
  stop-color: var(--svg-color--d0ccd3, #D0CCD3);
  stop-opacity: 0;
}

.pih07rvsm {
  cx: 7.109px;
  cy: 17.994px;
  r: 3.121px;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.q2rl-9b2o {
  stop-color: var(--svg-color--cfcad4, #CFCAD4);
}

.q9wqsddqp {
  stop-color: var(--svg-color--b5b4b6, #B5B4B6);
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qdssebgqk {
  stop-color: var(--svg-color--d09c8f, #D09C8F);
  stop-opacity: 0;
}

.qfleuzzqm {
  stop-color: var(--svg-color--a5a0a9, #A5A0A9);
}

.qnoj66lkr {
  stop-color: var(--svg-color--f5f4f6, #F5F4F6);
}

.qny5yebdb {
  stop-color: var(--svg-color--f6bdb0, #F6BDB0);
}

.qr00he01g {
  d: path("m25.584 14.532l-.019.232h.005c-.12 2.027-.264 4.63-.373 6.626c-.082 1.485-.145 2.634-.167 2.96c-.3 3.308-2.9 5.614-6.001 5.614h-6.001c-3.2 0-5.701-2.306-6.001-5.613c-.12-1.566-.18-3.17-.239-4.775c-.06-1.653-.121-3.309-.25-4.929c-.006-.598-.01-1.708.478-2.438c.802-1.196 1.711-1.285 2.602-1.285h12.96c2.341 0 3.014 1.621 3.076 2.553a5 5 0 0 0-.046.66z");
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

.r_3u_vbfs {
  cx: 7.109px;
  cy: 17.994px;
  r: 1.86px;
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
  stop-opacity: 0;
}

.rcuz4uefu {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
  stop-opacity: 0;
}

.rjs9uccph {
  stop-color: var(--svg-color--d1cad9, #D1CAD9);
  stop-opacity: 0;
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
}

.rnyxtsb4p {
  stop-color: var(--svg-color--ddddde, #DDDDDE);
}

.rq033_icj {
  stop-color: var(--svg-color--bfb7c6, #BFB7C6);
  stop-opacity: 0;
}

.rvf3-0bfj {
  stop-color: var(--svg-color--dead9d, #DEAD9D);
  stop-opacity: 0;
}

.s_fkwccyi {
  stop-color: var(--svg-color--cfc8d7, #CFC8D7);
}

.s6vdf8bty {
  stop-color: var(--svg-color--f8f6fb, #F8F6FB);
}

.sd37djb7x {
  stop-color: var(--svg-color--dfa8a4, #DFA8A4);
  stop-opacity: 0;
}

.sqxrh1b6n {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
}

.thnicubcj {
  fill: var(--svg-color--000, #000);
  d: path("M19.105 17.496c0-.531.425-.956.955-.956c.531 0 .956.425.956.956a.95.95 0 0 1-.106.44h-1.691a.86.86 0 0 1-.114-.44");
}

.tqgh1edwg {
  stop-color: var(--svg-color--eaab97, #EAAB97);
}

.try973jmd {
  cx: 11.394px;
  cy: 16.541px;
  rx: 0.728px;
  ry: 0.369px;
}

.u4es0m23n {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.51 15.32a2.61 2.61 0 0 0-2.53 1.98a.512.512 0 0 0 .5.637h4.17a.43.43 0 0 0 .424-.508a2.62 2.62 0 0 0-2.562-2.108");
}

.uhibk-oxd {
  d: path("M11.897 15.828a1.668 1.668 0 0 0-1.607 2.108h3.222a1.7 1.7 0 0 0 .06-.44a1.68 1.68 0 0 0-1.675-1.668");
}

.up3xx-bty {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.984 23.845c-.949 0-1.84-.223-2.59-.614c-.255-.13-.53.158-.37.39a3.54 3.54 0 0 0 2.96 1.582a3.54 3.54 0 0 0 2.959-1.581c.16-.242-.114-.521-.37-.39c-.75.39-1.631.613-2.59.613Z");
}

.v6-gl02mj {
  d: path("M21.546 17.276a1.57 1.57 0 0 0-.432-.865l-.486.533l.22.427z");
}

.vp13rcbvk {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m8.93 12.91l.002-.002l.004-.003l.008-.007l.022-.018l.067-.05q.083-.061.223-.15c.186-.117.45-.262.784-.395a5.3 5.3 0 0 1 2.79-.295a.998.998 0 1 1-.31 1.97a3.3 3.3 0 0 0-1.746.18a3 3 0 0 0-.561.299l-.015.011a.998.998 0 0 1-1.269-1.54");
}

.vzlyfrf0q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.331 13.609c.612-.54 1.947-1.11 3.603-.846");
}

.w_gy_4baw {
  d: path("M4.769 10.615c.457-.912 1.614-2.205 5.677-2.625c.406-.042 1.004-.06 1.673-.08c1.665-.05 3.775-.113 4.482-.594c.933-.445 1.972-3.245 1.539-5.28h-5.97L5.182 4.985c-.524 1.062-.597 2.081-.597 2.695c0 .744.012 2.076.185 2.935");
}

.w3hticb3q {
  d: path("M4.584 7.772C5.142 7.102 6.148 6.16 7.48 5.8c1.88-.509 4.836-.733 6.07-.82c.448.025 1.556-.442 1.556-1.611c0-.433-.017-.889-.054-1.332h-4.375c-3.711 0-4.678 1.407-5.42 2.8c-.594 1.115-.674 2.201-.674 2.844z");
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

.wachewblq {
  stop-color: var(--svg-color--ba7c6b, #BA7C6B);
}

.wdqn7tq-u {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
}

.wf-a-tclc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.088 12.64c.804-.141 2.371-.101 3.457.743");
}

.wfm74pxcd {
  stop-color: var(--svg-color--e2dce8, #E2DCE8);
  stop-opacity: 0;
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wvn8vtban {
  stop-color: var(--svg-color--c5c2c8, #C5C2C8);
  stop-opacity: 0;
}

.wy1fk_yef {
  d: path("M4.78 10.665c.193 2.806 1.396 3.89 1.76 4.18c0-.515-.073-1.815.476-2.636c.802-1.196 1.711-1.285 2.602-1.285h12.96c2.464 0 3.08 1.796 3.08 2.694l-.093 1.146c.217 0 .867-.237 1.115-.728c.65-1.285 1.069-3.964 1.162-5.528s.03-2.763-1.193-4.451c-.978-1.35-2.794-2.02-4.42-2.02H10.678c-3.711 0-4.678 1.406-5.42 2.8c-.594 1.114-.674 2.2-.674 2.843c0 .759.013 2.128.195 2.985");
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x7ia8vuzd {
  stop-color: var(--svg-color--f1edf4, #F1EDF4);
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.xohlojkms {
  stop-color: var(--svg-color--b67d9d, #B67D9D);
}

.xyw2spbat {
  stop-color: var(--svg-color--ad7277, #AD7277);
}

.y75qcccyl {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m22.936 12.91l-.002-.002l-.003-.003l-.009-.007l-.022-.018l-.067-.05a4 4 0 0 0-.223-.15a5 5 0 0 0-.784-.395a5.3 5.3 0 0 0-2.79-.295a.998.998 0 1 0 .31 1.97a3.3 3.3 0 0 1 1.746.18a3 3 0 0 1 .561.299l.015.011a.998.998 0 0 0 1.268-1.54");
}

.yk38wibgb {
  d: path("m15.27 17.46l-.994 3.178a1.008 1.008 0 0 0 .973 1.307h1.47c.689 0 1.175-.664.973-1.307l-.994-3.177c-.213-.704-1.206-.704-1.429 0");
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

.zbbitdbrp {
  stop-color: var(--svg-color--e8ad96, #E8AD96);
  stop-opacity: 0;
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

.zz39r5b3o {
  stop-color: var(--svg-color--c5c2c8, #C5C2C8);
}

</style>
