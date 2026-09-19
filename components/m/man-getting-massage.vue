<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="ixhZH4c" class="d1ajpf58e"/></defs><g class="ft5dv1b6b"><g filter="url(#iUZ9lbr)"><path fill="url(#iumgDIe)" class="l8jusdr6y"/><path fill="url(#ipmDzYd)" class="l8jusdr6y"/></g><path class="l5jf0nbir"/><path fill="url(#icEd8pd)" class="tx_btybwx"/><path fill="url(#ip6d75n)" class="tx_btybwx"/><circle fill="url(#iqw4THe)" class="ckkaoubhy"/><circle fill="url(#iTXfurb)" class="ckkaoubhy"/><circle fill="url(#iGuMc3c)" class="tr559m5ue"/><g filter="url(#iF7zAcd)"><circle class="rsrx2cx_n"/></g><g filter="url(#iNOFxne)" class="mc2zb0bvp"><circle class="qmo64ubzk"/></g><g filter="url(#irvS9xd)"><path fill="url(#iPU1orl)" class="i5i_8mxsj"/><path fill="url(#iYEgEde)" class="i5i_8mxsj"/></g><path fill="url(#iW4W9yb)" class="i5i_8mxsj"/><g filter="url(#i6sc6qJ)"><path fill="url(#iOi4jJd)" class="d0lldcbqg"/></g><g filter="url(#ig4otub)"><path fill="url(#iXdZXTd)" class="ls65_6i-s"/><path fill="url(#iK6h7hO)" class="ls65_6i-s"/></g><g filter="url(#i2Oe9Rc)"><path class="w3e2onb7r"/><path fill="url(#iuP56yI)" class="m4lo5kbkg"/><path fill="url(#i39Aclc)" class="m4lo5kbkg"/><path fill="url(#irWVGcd)" class="m4lo5kbkg"/><path fill="url(#iRWebmd)" class="m4lo5kbkg"/></g><g filter="url(#iuH04Bo)"><circle fill="url(#iWk2Idb)" class="vh3837gtk"/></g><path stroke="url(#ikuDoYz)" class="wupazrada"/><g filter="url(#iGwWLLe)"><path stroke="url(#iwRU3vc)" class="g-mr_sgso"/></g><path stroke="url(#iCJpwGl)" class="qvye139vd"/><g filter="url(#iS7R6ce)"><path stroke="url(#i6MQnhe)" class="jednjgv3t"/></g><g filter="url(#iwKCcnc)"><path class="zjcgm6bca"/></g><path class="u-rbrjb8j"/><path fill="url(#ipgz66c)" class="a7__jtqji"/><path fill="url(#ijBVjIc)" class="a7__jtqji"/><g filter="url(#iGqIXyd)"><path stroke="url(#ieFOQsb)" class="phcbxnb1c"/></g><path class="yhxndnvrl"/><g filter="url(#iMqNkmc)"><path class="webva-bta"/><path fill="url(#iNOVRNe)" class="t2-7jpk5z"/><path fill="url(#imefpMc)" class="t2-7jpk5z"/></g><g filter="url(#iz2RhAb)"><use href="#ixhZH4c"/><path fill="url(#iEk9ITx)" class="ydwdd-bau"/></g><g filter="url(#iz2RhAb)"><use href="#ixhZH4c"/><path fill="url(#iEk9ITx)" class="ydwdd-bau"/></g><g filter="url(#iB5OQLm)"><path fill="url(#ifzBjqb)" class="bx7cnxbsy"/></g><g filter="url(#it1Sbie)"><path fill="url(#i9hWiUl)" class="fe44mcufk"/></g><g filter="url(#iwXJRPc)"><path class="ksrcf9a3m"/></g><g filter="url(#iId7D7d)"><path clip-rule="evenodd" class="dydvalbfv"/></g><g filter="url(#i7A1TEe)"><path clip-rule="evenodd" class="ousrkb4sf"/></g><g filter="url(#idjbDbd)"><path stroke="url(#iGGIWZd)" class="fx1j--hdc"/></g><g filter="url(#iSvojkc)"><path stroke="url(#iBj6gWd)" class="w-4a-_bjk"/></g><defs><radialGradient id="iumgDIe" cx="0" cy="0" r="1" gradientTransform="matrix(-18.0313 0 0 -9.84375 23.482 28.393)" gradientUnits="userSpaceOnUse"><stop class="mqhcwabvr"/><stop offset=".895" class="n0nsa8bju"/></radialGradient><radialGradient id="ipmDzYd" cx="0" cy="0" r="1" gradientTransform="rotate(-143.857 16.873 9.347)scale(11.1265 12.0118)" gradientUnits="userSpaceOnUse"><stop offset=".079" class="im62pwnwd"/><stop offset="1" class="nwe3t_p9t"/></radialGradient><radialGradient id="icEd8pd" cx="0" cy="0" r="1" gradientTransform="rotate(142.016 5.115 14.8)scale(3.24973 2.31564)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="p6p8s6h_o"/><stop offset="1" class="blutr0uxb"/></radialGradient><radialGradient id="ip6d75n" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 1.9375 -6.30043 2.94698 14.594 21.722)" gradientUnits="userSpaceOnUse"><stop class="uq6p3otof"/><stop offset="1" class="anz2_rbrw"/></radialGradient><radialGradient id="iqw4THe" cx="0" cy="0" r="1" gradientTransform="rotate(120.672 7.428 13.805)scale(2.47552 1.58234)" gradientUnits="userSpaceOnUse"><stop class="pg81w39ph"/><stop offset=".908" class="dmanwfbnw"/></radialGradient><radialGradient id="iTXfurb" cx="0" cy="0" r="1" gradientTransform="rotate(75.315 1.293 21.28)scale(2.2011)" gradientUnits="userSpaceOnUse"><stop offset=".798" class="n3i3hq-br"/><stop offset="1" class="qca9cgb6f"/></radialGradient><radialGradient id="iGuMc3c" cx="0" cy="0" r="1" gradientTransform="rotate(46.621 -12.715 17.502)scale(2.70721)" gradientUnits="userSpaceOnUse"><stop class="g0xv48b6h"/><stop offset="1" class="r6ifw9b5e"/></radialGradient><radialGradient id="iPU1orl" cx="0" cy="0" r="1" gradientTransform="matrix(-6.40084 .5663 -.57862 -6.54 19.71 16.358)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="isb53_mmq"/><stop offset="1" class="b1hif_bph"/></radialGradient><radialGradient id="iYEgEde" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.76172 -3.72696 0 15.992 10.222)" gradientUnits="userSpaceOnUse"><stop class="yck7_dfvw"/><stop offset="1" class="a5byajx2y"/></radialGradient><radialGradient id="iW4W9yb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.10788 11.52075 -14.76509 -1.41987 17.1 12.002)" gradientUnits="userSpaceOnUse"><stop offset=".674" class="h9yvwzbrk"/><stop offset=".933" class="tduaatcyr"/></radialGradient><radialGradient id="iOi4jJd" cx="0" cy="0" r="1" gradientTransform="rotate(89.246 5.575 15.152)scale(4.95122 5.29384)" gradientUnits="userSpaceOnUse"><stop class="p97qg-b4a"/><stop offset="1" class="vukz93b8e"/></radialGradient><radialGradient id="iXdZXTd" cx="0" cy="0" r="1" gradientTransform="matrix(.87207 1.75 -1.15013 .57314 11.04 9.878)" gradientUnits="userSpaceOnUse"><stop class="f7m1yfx-m"/><stop offset="1" class="p3lw01bbh"/></radialGradient><radialGradient id="iK6h7hO" cx="0" cy="0" r="1" gradientTransform="rotate(-91.668 12.423 1.996)scale(3.22012 2.52563)" gradientUnits="userSpaceOnUse"><stop class="km7u9bcta"/><stop offset="1" class="rf_171bfc"/></radialGradient><radialGradient id="iuP56yI" cx="0" cy="0" r="1" gradientTransform="matrix(-2.24908 -1.8848 1.70253 -2.03159 18.78 8.2)" gradientUnits="userSpaceOnUse"><stop offset=".322" class="pbw6czb-j"/><stop offset="1" class="y7xt-dbuk"/></radialGradient><radialGradient id="i39Aclc" cx="0" cy="0" r="1" gradientTransform="rotate(-153.435 9.182 1.887)scale(4.68293 9.81511)" gradientUnits="userSpaceOnUse"><stop offset=".618" class="tsaes21dp"/><stop offset=".971" class="zka0ljdho"/></radialGradient><radialGradient id="irWVGcd" cx="0" cy="0" r="1" gradientTransform="rotate(165.129 8.956 3.522)scale(2.86147 1.10395)" gradientUnits="userSpaceOnUse"><stop offset=".293" class="px216bbgn"/><stop offset="1" class="hux3ebc3y"/></radialGradient><radialGradient id="iRWebmd" cx="0" cy="0" r="1" gradientTransform="rotate(-132.421 11.658 -1.247)scale(4.66658 2.21064)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="q8azbi6jm"/><stop offset="1" class="hstcsgbrz"/></radialGradient><radialGradient id="iWk2Idb" cx="0" cy="0" r="1" gradientTransform="matrix(.92789 -1.80184 1.99143 1.02552 13.347 14.352)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="cibck0b0g"/><stop offset=".902" class="ghvr_e1bi"/></radialGradient><radialGradient id="ikuDoYz" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 13.559 14.988)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="zbl0hn4uu"/><stop offset="1" class="a4w7cpbiw"/></radialGradient><radialGradient id="iCJpwGl" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 18.45 14.988)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="zbl0hn4uu"/><stop offset="1" class="a4w7cpbiw"/></radialGradient><radialGradient id="ijBVjIc" cx="0" cy="0" r="1" gradientTransform="matrix(.19456 -1.08993 4.30796 .769 15.981 17.167)" gradientUnits="userSpaceOnUse"><stop offset=".03" class="lydnq_bqp"/><stop offset="1" class="mw3_h25bb"/></radialGradient><radialGradient id="ieFOQsb" cx="0" cy="0" r="1" gradientTransform="matrix(.20312 -.39062 1.75486 .91253 14.9 18.753)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="ugyr8nbyy"/><stop offset="1" class="xh5cq3bwm"/></radialGradient><radialGradient id="iNOVRNe" cx="0" cy="0" r="1" gradientTransform="rotate(69.766 3.889 10.504)scale(9.1257 4.52893)" gradientUnits="userSpaceOnUse"><stop class="r871ksz2k"/><stop offset="1" class="m5-y-pbea"/></radialGradient><radialGradient id="imefpMc" cx="0" cy="0" r="1" gradientTransform="rotate(-123.921 8.783 2.284)scale(3.21989 1.05742)" gradientUnits="userSpaceOnUse"><stop class="s165-bbuq"/><stop offset="1" class="kyulx_bkd"/></radialGradient><radialGradient id="iEk9ITx" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.14314 -1.29371 0 22.499 2.043)" gradientUnits="userSpaceOnUse"><stop class="pra7rq0gk"/><stop offset="1" class="na9kkhbsz"/></radialGradient><filter id="iUZ9lbr" width="21.451" height="8.965" x="5.65" y="20.845" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.12549 0 0 0 0 0.396078 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24255"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.490196 0 0 0 0 0.666667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24255" result="effect2_innerShadow_3987_24255"/></filter><filter id="iF7zAcd" width="2.689" height="2.689" x="20.081" y="13.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24255" stdDeviation=".1"/></filter><filter id="iNOFxne" width="2.689" height="2.689" x="9.253" y="13.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24255" stdDeviation=".1"/></filter><filter id="irvS9xd" width="12.719" height="14.211" x="9.883" y="7.878" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.607843 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24255"/></filter><filter id="i6sc6qJ" width="7.729" height="10.962" x="16.042" y="4.932" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24255" stdDeviation=".5"/></filter><filter id="ig4otub" width="7.108" height="9.773" x="8.357" y="5.856" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24255" stdDeviation=".5"/></filter><filter id="i2Oe9Rc" width="8.297" height="3.863" x="11.852" y="4.765" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.992157 0 0 0 0 0.541176 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24255"/></filter><filter id="iuH04Bo" width="3.829" height="3.83" x="11.59" y="11.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24255" stdDeviation=".25"/></filter><filter id="iGwWLLe" width="2.618" height=".92" x="12.249" y="14.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24255" stdDeviation=".075"/></filter><filter id="iS7R6ce" width="2.618" height=".92" x="17.14" y="14.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24255" stdDeviation=".075"/></filter><filter id="iwKCcnc" width="3.122" height="4.211" x="14.143" y="13.62" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24255" stdDeviation=".25"/></filter><filter id="iGqIXyd" width="4.199" height="1.729" x="13.887" y="17.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24255" stdDeviation=".05"/></filter><filter id="iMqNkmc" width="6.686" height="12.903" x="8.579" y="1.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.556863 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24255"/></filter><filter id="iz2RhAb" width="6.436" height="12.953" x="17.22" y="1.941" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.541176 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24255"/></filter><filter id="iB5OQLm" width="6.909" height="13.292" x="17.245" y="1.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24255" stdDeviation=".5"/></filter><filter id="it1Sbie" width="2.811" height="6.368" x="8.699" y="8.671" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24255" stdDeviation=".375"/></filter><filter id="iwXJRPc" width="5.64" height="8.855" x="9.403" y="1.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24255" stdDeviation=".375"/></filter><filter id="iId7D7d" width="3.191" height="1.873" x="11.514" y="11.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.25098 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24255"/></filter><filter id="i7A1TEe" width="3.191" height="1.873" x="17.405" y="11.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.25098 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24255"/></filter><filter id="idjbDbd" width="3.085" height="1.469" x="17.433" y="11.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24255" stdDeviation=".15"/></filter><filter id="iSvojkc" width="3.085" height="1.469" x="11.492" y="11.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24255" stdDeviation=".15"/></filter><linearGradient id="iwRU3vc" x1="14.916" x2="12.475" y1="14.394" y2="14.394" gradientUnits="userSpaceOnUse"><stop offset=".045" class="di1p0_b3t"/><stop offset=".32" class="g8-pnsbec"/><stop offset=".794" class="g8-pnsbec"/><stop offset="1" class="di1p0_b3t"/></linearGradient><linearGradient id="i6MQnhe" x1="19.807" x2="17.365" y1="14.394" y2="14.394" gradientUnits="userSpaceOnUse"><stop offset=".045" class="di1p0_b3t"/><stop offset=".32" class="g8-pnsbec"/><stop offset=".794" class="g8-pnsbec"/><stop offset="1" class="di1p0_b3t"/></linearGradient><linearGradient id="ipgz66c" x1="17.042" x2="15.436" y1="15.878" y2="16.042" gradientUnits="userSpaceOnUse"><stop class="p_drcebab"/><stop offset="1" class="tdgu1u54k"/></linearGradient><linearGradient id="ifzBjqb" x1="22.155" x2="22.155" y1="3.157" y2="14.948" gradientUnits="userSpaceOnUse"><stop offset=".786" class="r245klenb"/><stop offset="1" class="qs8hc0yqa"/></linearGradient><linearGradient id="i9hWiUl" x1="10.105" x2="10.105" y1="13.506" y2="8.675" gradientUnits="userSpaceOnUse"><stop class="n6_y6k2_m"/><stop offset="1" class="bd1m8wbbp"/></linearGradient><linearGradient id="iGGIWZd" x1="20.406" x2="17.203" y1="12.519" y2="12.059" gradientUnits="userSpaceOnUse"><stop class="f7g-3qbwt"/><stop offset="1" class="ci_-ps2wb"/></linearGradient><linearGradient id="iBj6gWd" x1="13.969" x2="10.859" y1="12.175" y2="13.394" gradientUnits="userSpaceOnUse"><stop class="f7g-3qbwt"/><stop offset="1" class="ci_-ps2wb"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-getting-massage" /></template>
<style>
.a4w7cpbiw {
  stop-color: var(--svg-color--b54919, #B54919);
}

.a5byajx2y {
  stop-color: var(--svg-color--ffcb32, #FFCB32);
  stop-opacity: 0;
}

.a7__jtqji {
  d: path("M15.98 14.034a.375.375 0 0 0-.357.262l-.678 2.14a.56.56 0 0 0 .535.731h1a.56.56 0 0 0 .536-.73l-.678-2.14a.375.375 0 0 0-.358-.263");
}

.anz2_rbrw {
  stop-color: var(--svg-color--c97a24, #C97A24);
  stop-opacity: 0;
}

.b1hif_bph {
  stop-color: var(--svg-color--fda828, #FDA828);
}

.bd1m8wbbp {
  stop-color: var(--svg-color--ffcb3b, #FFCB3B);
  stop-opacity: 0;
}

.blutr0uxb {
  stop-color: var(--svg-color--f9ca41, #F9CA41);
  stop-opacity: 0;
}

.bx7cnxbsy {
  d: path("M21.214 8.813L19.193 10.3a.595.595 0 0 1-.79-.076a.59.59 0 0 1 .027-.83a52 52 0 0 1 1.99-1.786c.875-.733 1.05-1.838 1.03-2.3V2.732h1.704v10.713a.579.579 0 0 1-1.158 0V9.208a.491.491 0 0 0-.782-.395");
}

.ci_-ps2wb {
  stop-color: var(--svg-color--d2715d, #D2715D);
  stop-opacity: 0;
}

.cibck0b0g {
  stop-color: var(--svg-color--ffb129, #FFB129);
}

.ckkaoubhy {
  cx: 21.426px;
  cy: 14.831px;
  r: 1.859px;
}

.d0lldcbqg {
  d: path("M22.77 7.736h-3.172V5.932c0 .352-.21 1.036-.633 1.43a77 77 0 0 0-1.6 1.692a1.263 1.263 0 0 0 .025 1.715c.42.428 1.009.362 1.439-.055l.906-.74a.464.464 0 0 1 .691.044c.08.096.123.22.123.35v3.327c0 .662.497 1.199 1.11 1.199s1.111-.537 1.111-1.2z");
}

.d1ajpf58e {
  fill: var(--svg-color--ffb62d, #FFB62D);
  d: path("M23.405 2.19H19.98v3.742c0 .352-.227 1.036-.684 1.43a80 80 0 0 0-1.727 1.692a1.196 1.196 0 0 0 .026 1.715c.454.428 1.09.362 1.554-.055l.979-.74a.527.527 0 0 1 .879.393v3.328a1.2 1.2 0 1 0 2.398 0z");
}

.di1p0_b3t {
  stop-color: var(--svg-color--bf6a57, #BF6A57);
}

.dmanwfbnw {
  stop-color: var(--svg-color--fdb530, #FDB530);
}

.dydvalbfv {
  fill: var(--svg-color--bb4447, #BB4447);
  fill-rule: evenodd;
  d: path("M13.932 12.787c-.86-.117-1.389.27-1.521.378a.55.55 0 1 1-.693-.855c.253-.205 1.08-.787 2.361-.614a.55.55 0 1 1-.147 1.09");
}

.f7g-3qbwt {
  stop-color: var(--svg-color--d2715d, #D2715D);
}

.f7m1yfx-m {
  stop-color: var(--svg-color--9b4607, #9B4607);
}

.fe44mcufk {
  d: path("m9.45 9.42l1.31.78v3.433a.656.656 0 0 1-1.31 0z");
}

.ft5dv1b6b {
  fill: none;
}

.fx1j--hdc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M20.068 12.628c-.193-.156-1.044-.632-2.185-.562");
}

.g-mr_sgso {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.475 14.394c.145.164.536.45 1.023.469c.617.023.95-.305 1.145-.47");
}

.g0xv48b6h {
  stop-color: var(--svg-color--d88f27, #D88F27);
}

.g8-pnsbec {
  stop-color: var(--svg-color--93534a, #93534A);
}

.ghvr_e1bi {
  stop-color: var(--svg-color--f39423, #F39423);
}

.h9yvwzbrk {
  stop-color: var(--svg-color--f7a12f, #F7A12F);
  stop-opacity: 0;
}

.hstcsgbrz {
  stop-color: var(--svg-color--eaae29, #EAAE29);
  stop-opacity: 0;
}

.hux3ebc3y {
  stop-color: var(--svg-color--dbab39, #DBAB39);
  stop-opacity: 0;
}

.i5i_8mxsj {
  d: path("M10.375 18.167c.14 1.625.594 3.688 3.594 3.883a64 64 0 0 0 1.984.039h.078c.251 0 1.032-.005 1.985-.039c3-.195 3.453-2.258 3.594-3.883l.492-9.523a31 31 0 0 0-6.07-.765h-.079a31 31 0 0 0-6.07.765z");
}

.im62pwnwd {
  stop-color: var(--svg-color--429efa, #429EFA);
}

.isb53_mmq {
  stop-color: var(--svg-color--ffdd41, #FFDD41);
}

.jednjgv3t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.365 14.394c.146.164.536.45 1.024.469c.617.023.949-.305 1.144-.47");
}

.km7u9bcta {
  stop-color: var(--svg-color--cd8135, #CD8135);
}

.ksrcf9a3m {
  fill: var(--svg-color--ffdf38, #FFDF38);
  d: path("M10.153 5.548v-2.9h1.469v3.535a1 1 0 0 0 .28.694l2.262 2.348a.46.46 0 0 1-.636.663l-2.364-2.094a3 3 0 0 1-1.01-2.246");
}

.kyulx_bkd {
  stop-color: var(--svg-color--ffa92e, #FFA92E);
  stop-opacity: 0;
}

.l5jf0nbir {
  fill: var(--svg-color--ffb735, #FFB735);
  d: path("M13.742 20.41a2.256 2.256 0 0 1 4.512 0v2.102c0 1.245-1.588 1.624-2.256 1.624c-.766 0-2.256-.378-2.256-1.624z");
}

.l8jusdr6y {
  d: path("M5.65 29.81h20.7c-.493-4.932-5.203-8.665-10.39-8.665c-5.189 0-9.713 3.764-10.31 8.664");
}

.ls65_6i-s {
  d: path("M9.357 6.856h2.83v.372c0 .291.187.855.564 1.181c.31.287.905.876 1.426 1.398a.987.987 0 0 1-.021 1.415c-.375.354-.899.3-1.282-.045l-.81-.61a.436.436 0 0 0-.726.324v2.748a.99.99 0 1 1-1.98 0z");
}

.lydnq_bqp {
  stop-color: var(--svg-color--ed8f30, #ED8F30);
}

.m4lo5kbkg {
  d: path("M12.035 6.142c.242-.225.546-.508.707-.635l.04-.03c.27-.218.802-.644 2.007-.376c.297.064.506.114.663.152c.283.067.398.094.548.094s.266-.027.548-.094c.157-.038.367-.088.663-.152c1.205-.268 1.737.158 2.008.375l.039.031c.161.127.465.41.707.635l.184.17l-.493 2.316c-2.351-.28-5.023-.265-7.312 0l-.492-2.316z");
}

.m5-y-pbea {
  stop-color: var(--svg-color--ffdf3b, #FFDF3B);
  stop-opacity: 0;
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mqhcwabvr {
  stop-color: var(--svg-color--469afb, #469AFB);
}

.mw3_h25bb {
  stop-color: var(--svg-color--ffb520, #FFB520);
  stop-opacity: 0;
}

.n0nsa8bju {
  stop-color: var(--svg-color--2376c8, #2376C8);
}

.n3i3hq-br {
  stop-color: var(--svg-color--eb992f, #EB992F);
  stop-opacity: 0;
}

.n6_y6k2_m {
  stop-color: var(--svg-color--ffca3e, #FFCA3E);
}

.na9kkhbsz {
  stop-color: var(--svg-color--ffe041, #FFE041);
  stop-opacity: 0;
}

.nwe3t_p9t {
  stop-color: var(--svg-color--429efa, #429EFA);
  stop-opacity: 0;
}

.ousrkb4sf {
  fill: var(--svg-color--bb4447, #BB4447);
  fill-rule: evenodd;
  d: path("M18.029 12.787c.86-.117 1.389.27 1.521.378a.55.55 0 1 0 .693-.855c-.253-.205-1.08-.787-2.362-.614a.55.55 0 1 0 .148 1.09");
}

.p_drcebab {
  stop-color: var(--svg-color--ffdb40, #FFDB40);
}

.p3lw01bbh {
  stop-color: var(--svg-color--d97513, #D97513);
}

.p6p8s6h_o {
  stop-color: var(--svg-color--f9ca41, #F9CA41);
}

.p97qg-b4a {
  stop-color: var(--svg-color--b95a08, #B95A08);
}

.pbw6czb-j {
  stop-color: var(--svg-color--ffcc30, #FFCC30);
}

.pg81w39ph {
  stop-color: var(--svg-color--ffd742, #FFD742);
}

.phcbxnb1c {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.337 17.742c.345.18.879.384 1.65.384s1.304-.203 1.648-.384c.108-.056.242.014.25.135a.2.2 0 0 1-.015.077c-.76 1.471-3.065 1.456-3.768 0a.15.15 0 0 1-.015-.077c.008-.121.142-.191.25-.135Z");
}

.pra7rq0gk {
  stop-color: var(--svg-color--ffe041, #FFE041);
}

.px216bbgn {
  stop-color: var(--svg-color--dbab39, #DBAB39);
}

.q8azbi6jm {
  stop-color: var(--svg-color--bd7927, #BD7927);
}

.qca9cgb6f {
  stop-color: var(--svg-color--eb992f, #EB992F);
}

.qmo64ubzk {
  cx: 10.598px;
  cy: 14.831px;
  r: 1.145px;
  fill: var(--svg-color--d07d1c, #D07D1C);
}

.qs8hc0yqa {
  stop-color: var(--svg-color--ffdf40, #FFDF40);
  stop-opacity: 0;
}

.qvye139vd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M17.365 14.394c.146.164.536.45 1.024.469c.617.023.949-.305 1.144-.47");
}

.r245klenb {
  stop-color: var(--svg-color--ffdf40, #FFDF40);
}

.r6ifw9b5e {
  stop-color: var(--svg-color--d27f2e, #D27F2E);
}

.r871ksz2k {
  stop-color: var(--svg-color--ffdf3b, #FFDF3B);
}

.rf_171bfc {
  stop-color: var(--svg-color--cd8135, #CD8135);
  stop-opacity: 0;
}

.rsrx2cx_n {
  cx: 21.426px;
  cy: 14.831px;
  r: 1.145px;
  fill: var(--svg-color--f9bb2f, #F9BB2F);
}

.s165-bbuq {
  stop-color: var(--svg-color--c96a05, #C96A05);
}

.t2-7jpk5z {
  d: path("M8.579 2.19h3.426v3.742c0 .352.226 1.036.683 1.43c.376.348 1.096 1.06 1.727 1.692a1.195 1.195 0 0 1-.026 1.715c-.453.428-1.088.362-1.552-.055l-.98-.74a.527.527 0 0 0-.88.393v3.328a1.2 1.2 0 1 1-2.398 0z");
}

.tdgu1u54k {
  stop-color: var(--svg-color--ffdb40, #FFDB40);
  stop-opacity: 0;
}

.tduaatcyr {
  stop-color: var(--svg-color--ad763b, #AD763B);
}

.tr559m5ue {
  cx: 10.598px;
  cy: 14.831px;
  r: 1.859px;
}

.tsaes21dp {
  stop-color: var(--svg-color--f6a10e, #F6A10E);
  stop-opacity: 0;
}

.tx_btybwx {
  d: path("M13.742 20.41a2.256 2.256 0 0 1 4.512 0v2.102c0 1.245-1.588 1.624-2.256 1.624c-.766 0-2.256-.378-2.256-1.624z");
}

.u-rbrjb8j {
  fill: var(--svg-color--ffb31f, #FFB31F);
  d: path("M15.98 14.034a.375.375 0 0 0-.357.262l-.678 2.14a.56.56 0 0 0 .535.731h1a.56.56 0 0 0 .536-.73l-.678-2.14a.375.375 0 0 0-.358-.263");
}

.ugyr8nbyy {
  stop-color: var(--svg-color--ffb333, #FFB333);
}

.uq6p3otof {
  stop-color: var(--svg-color--c97a24, #C97A24);
}

.vh3837gtk {
  cx: 13.505px;
  cy: 13.651px;
  r: 1.415px;
}

.vukz93b8e {
  stop-color: var(--svg-color--fba42d, #FBA42D);
}

.w-4a-_bjk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M11.942 12.628c.193-.156 1.045-.632 2.186-.562");
}

.w3e2onb7r {
  fill: var(--svg-color--ffba15, #FFBA15);
  d: path("M12.035 6.142c.242-.225.546-.508.707-.635l.04-.03c.27-.218.802-.644 2.007-.376c.297.064.506.114.663.152c.283.067.398.094.548.094s.266-.027.548-.094c.157-.038.367-.088.663-.152c1.205-.268 1.737.158 2.008.375l.039.031c.161.127.465.41.707.635l.184.17l-.493 2.316c-2.351-.28-5.023-.265-7.312 0l-.492-2.316z");
}

.webva-bta {
  fill: var(--svg-color--ffb52d, #FFB52D);
  d: path("M8.579 2.19h3.426v3.742c0 .352.226 1.036.683 1.43c.376.348 1.096 1.06 1.727 1.692a1.195 1.195 0 0 1-.026 1.715c-.453.428-1.088.362-1.552-.055l-.98-.74a.527.527 0 0 0-.88.393v3.328a1.2 1.2 0 1 1-2.398 0z");
}

.wupazrada {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M12.475 14.394c.145.164.536.45 1.023.469c.617.023.95-.305 1.145-.47");
}

.xh5cq3bwm {
  stop-color: var(--svg-color--ffb333, #FFB333);
  stop-opacity: 0;
}

.y7xt-dbuk {
  stop-color: var(--svg-color--ffcc30, #FFCC30);
  stop-opacity: 0;
}

.yck7_dfvw {
  stop-color: var(--svg-color--ffcb32, #FFCB32);
}

.ydwdd-bau {
  d: path("M23.405 2.19H19.98v3.742c0 .352-.227 1.036-.684 1.43a80 80 0 0 0-1.727 1.692a1.196 1.196 0 0 0 .026 1.715c.454.428 1.09.362 1.554-.055l.979-.74a.527.527 0 0 1 .879.393v3.328a1.2 1.2 0 1 0 2.398 0z");
}

.yhxndnvrl {
  fill: var(--svg-color--89004e, #89004E);
  d: path("M14.337 17.742c.345.18.879.384 1.65.384s1.304-.203 1.648-.384c.108-.056.242.014.25.135a.2.2 0 0 1-.015.077c-.76 1.471-3.065 1.456-3.768 0a.15.15 0 0 1-.015-.077c.008-.121.142-.191.25-.135");
}

.zbl0hn4uu {
  stop-color: var(--svg-color--8a374b, #8A374B);
}

.zjcgm6bca {
  fill: var(--svg-color--f4982a, #F4982A);
  d: path("M15.852 14.12c-.163 0-.247.093-.296.254l-.887 2.205a.59.59 0 0 0 .112.554c.106.126.26.198.422.198h1a.55.55 0 0 0 .424-.198a.59.59 0 0 0 .112-.554l-.678-2.205c-.049-.16-.045-.254-.209-.254");
}

.zka0ljdho {
  stop-color: var(--svg-color--c49638, #C49638);
}

</style>
