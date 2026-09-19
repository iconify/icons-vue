<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ivx7Icf)" class="rmv5f6ekt"/><path fill="url(#iw70gsb)" class="rmv5f6ekt"/><path fill="url(#iHLn7qb)" class="rmv5f6ekt"/><path fill="url(#iIgCXNe)" class="rmv5f6ekt"/><path fill="url(#iT2cmYb)" class="rmv5f6ekt"/><rect fill="url(#iU2WmFc)" class="qm8bcbjeu"/><g filter="url(#idEa4WK)"><circle fill="url(#iY3Egmd)" class="jharhj-ni"/></g><g filter="url(#idvMzPe)"><circle fill="url(#izte09b)" class="ccm87hbyo"/></g><g filter="url(#ifdif9c)"><circle fill="url(#icbd3wd)" class="krj1s2r6y"/><circle fill="url(#i4Hk5kO)" class="krj1s2r6y"/></g><g filter="url(#iP2o4id)"><circle class="ybxkyhlla"/><circle fill="url(#inLZ0xc)" class="nylmffbzf"/><circle fill="url(#ixI6cPc)" class="nylmffbzf"/></g><g filter="url(#i3K9E9c)"><path fill="url(#in6uxEd)" class="glysebnzk"/><path fill="url(#ihg6HDd)" class="glysebnzk"/><path fill="url(#iDnFRBc)" class="glysebnzk"/><path fill="url(#iQSx9Dc)" class="glysebnzk"/><path fill="url(#iGo673r)" class="glysebnzk"/></g><g filter="url(#ibKduPP)"><path class="t8ce_ac-b"/><path fill="url(#iLJXR7b)" class="u92u_5bxb"/><path fill="url(#iS1Aftb)" class="u92u_5bxb"/><path fill="url(#iq9mf3c)" class="u92u_5bxb"/><path fill="url(#i8eDvEc)" class="u92u_5bxb"/><path fill="url(#inqkkPd)" class="u92u_5bxb"/></g><path fill="url(#iixWpqc)" class="u92u_5bxb"/><path fill="url(#iTBRItb)" class="u92u_5bxb"/><g filter="url(#iLxPzYc)"><path class="cbzwtq_ut"/></g><g filter="url(#i2vG7bb)"><path class="qyie81bpb"/><path fill="url(#ima4TKY)" class="y19dso42s"/><path fill="url(#iWKrkrb)" class="y19dso42s"/><path fill="url(#i7lM8lu)" class="y19dso42s"/></g><path fill="url(#it4v2Be)" class="y19dso42s"/><path class="pjldzot5y"/><path fill="url(#i9CDnrb)" class="fek_kybrv"/><path class="kdw68kvvi"/><g filter="url(#i9RaXcc)"><path class="aeqha4b6g"/><path fill="url(#iB6NCMe)" class="joe29ub8h"/></g><g filter="url(#isVyPcu)"><path fill="url(#iGjcx6r)" class="a4g5pgffh"/></g><path class="az568jbmj"/><path fill="url(#iOvs42c)" class="n4b_03b5p"/><path class="zil-t4d5t"/><g filter="url(#iYFkKWd)"><path fill="url(#iSVdERd)" class="lgt5l_bso"/></g><g filter="url(#iml6hae)"><ellipse transform="rotate(-27.914 12.863 12.299)" class="dlhcaxb1i"/><ellipse fill="url(#ibMI67F)" transform="rotate(-27.914 12.863 12.299)" class="bh__h4bcu"/></g><g filter="url(#iYbKAum)"><path clip-rule="evenodd" class="qt738z6up"/></g><g filter="url(#i1lkA1b)"><path clip-rule="evenodd" class="v9jmb1b6x"/></g><g filter="url(#iNYBxrb)"><path stroke="url(#iuTCcEb)" class="nny4dempw"/></g><g filter="url(#iJgX4be)"><path stroke="url(#iyo8s7b)" class="klkmm6j5l"/></g><g filter="url(#inQQyJc)"><path stroke="url(#iN0HZGM)" clip-rule="evenodd" class="eis6e-ilx"/><path stroke="url(#iY7FUTd)" clip-rule="evenodd" class="eis6e-ilx"/></g><path clip-rule="evenodd" class="jx2nv7b5t"/><defs><radialGradient id="ivx7Icf" cx="0" cy="0" r="1" gradientTransform="rotate(160.481 9.331 14.06)scale(12.5328 12.8728)" gradientUnits="userSpaceOnUse"><stop class="v-2sss5_q"/><stop offset=".578" class="rl_l27czx"/></radialGradient><radialGradient id="iw70gsb" cx="0" cy="0" r="1" gradientTransform="matrix(-20.8125 0 0 -13.0625 25.199 29.069)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="zx529yrpf"/><stop offset="1" class="vith88blc"/></radialGradient><radialGradient id="iIgCXNe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.25498 0 0 -2.00346 15.703 21.083)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="kwfxid2mc"/><stop offset="1" class="axqjsnbkb"/></radialGradient><radialGradient id="iT2cmYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.77741 5.6184 0 12.446 30.118)" gradientUnits="userSpaceOnUse"><stop class="ylk4vpbqv"/><stop offset="1" class="cac2is6pz"/></radialGradient><radialGradient id="iU2WmFc" cx="0" cy="0" r="1" gradientTransform="rotate(45 -17.432 28.787)scale(4.26636 6.72801)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="pkb_n7lvs"/><stop offset=".963" class="t91gw6b7m"/></radialGradient><radialGradient id="iY3Egmd" cx="0" cy="0" r="1" gradientTransform="matrix(2.26599 0 0 3.9655 7.747 13.303)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="i4Hk5kO" cx="0" cy="0" r="1" gradientTransform="matrix(1.0675 -.77729 .88717 1.2184 22.667 12.961)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="inLZ0xc" cx="0" cy="0" r="1" gradientTransform="matrix(1.06047 -1.9505 1.14163 .6207 22.133 14.364)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="ixI6cPc" cx="0" cy="0" r="1" gradientTransform="matrix(.33481 .33141 -.42723 .43162 22.187 13.303)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="ihg6HDd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.38672 10.95548 -14.87154 -1.8824 17.066 11.394)" gradientUnits="userSpaceOnUse"><stop offset=".701" class="daw21qbgk"/><stop offset="1" class="k64o5hods"/></radialGradient><radialGradient id="iQSx9Dc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.68778 2.07727 0 19.063 11.661)" gradientUnits="userSpaceOnUse"><stop class="op2kwubyv"/><stop offset="1" class="wvivicznw"/></radialGradient><radialGradient id="iGo673r" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.79597 2.23345 0 13.177 11.618)" gradientUnits="userSpaceOnUse"><stop class="y7nn5tbfc"/><stop offset="1" class="uylyaxbnq"/></radialGradient><radialGradient id="iLJXR7b" cx="0" cy="0" r="1" gradientTransform="matrix(-4.43756 5.71942 -9.72636 -7.54644 20.801 3.344)" gradientUnits="userSpaceOnUse"><stop class="qyobb4hvj"/><stop offset="1" class="szm1jtb2t"/></radialGradient><radialGradient id="iq9mf3c" cx="0" cy="0" r="1" gradientTransform="matrix(-.08629 -2.40365 1.18049 -.04238 10.62 8.841)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="u7v6tactn"/><stop offset="1" class="hpjuubccm"/></radialGradient><radialGradient id="i8eDvEc" cx="0" cy="0" r="1" gradientTransform="rotate(-66.4 19.196 -10.891)scale(2.77101 2.25997)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ls62f1bvq"/><stop offset="1" class="gx0o3oiqw"/></radialGradient><radialGradient id="inqkkPd" cx="0" cy="0" r="1" gradientTransform="matrix(1.28195 1.59066 -1.40444 1.13187 15.032 2.197)" gradientUnits="userSpaceOnUse"><stop class="kxzxrmw_u"/><stop offset="1" class="vs8934bpj"/></radialGradient><radialGradient id="iixWpqc" cx="0" cy="0" r="1" gradientTransform="matrix(.2342 1.01132 -1.66261 .38503 16.93 2.197)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="dohbdcxhl"/><stop offset="1" class="bb6ud4ewj"/></radialGradient><radialGradient id="iTBRItb" cx="0" cy="0" r="1" gradientTransform="matrix(.9368 1.15868 -2.59618 2.09904 10.422 4.428)" gradientUnits="userSpaceOnUse"><stop class="w-a4mnbis"/><stop offset="1" class="ab4_rnbjl"/></radialGradient><radialGradient id="i9CDnrb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.16621 -1.37993 0 18.847 12.853)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iB6NCMe" cx="0" cy="0" r="1" gradientTransform="matrix(-.2994 -.38581 .53117 -.4122 18.552 12.531)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iOvs42c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.16627 -1.38 0 13.213 12.853)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ibMI67F" cx="0" cy="0" r="1" gradientTransform="matrix(-.00999 -.63784 .76671 -.012 12.843 12.706)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iN0HZGM" cx="0" cy="0" r="1" gradientTransform="matrix(-.08594 .28125 -1.54727 -.47278 16.31 17.371)" gradientUnits="userSpaceOnUse"><stop class="spg62za8n"/><stop offset="1" class="d_j_iqbmo"/></radialGradient><radialGradient id="iY7FUTd" cx="0" cy="0" r="1" gradientTransform="matrix(.191 -.14453 .57285 .75707 14.377 17.688)" gradientUnits="userSpaceOnUse"><stop class="spg62za8n"/><stop offset="1" class="d_j_iqbmo"/></radialGradient><filter id="idEa4WK" width="4.511" height="4.311" x="7.747" y="11.148" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21944"/></filter><filter id="idvMzPe" width="3.57" height="3.57" x="8.118" y="11.518" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21944" stdDeviation=".25"/></filter><filter id="ifdif9c" width="4.561" height="4.561" x="20.031" y="10.898" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21944"/></filter><filter id="iP2o4id" width="3.57" height="3.57" x="20.402" y="11.518" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21944" stdDeviation=".25"/></filter><filter id="i3K9E9c" width="13.395" height="15.781" x="9.373" y="6.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.501961 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21944"/></filter><filter id="ibKduPP" width="16.272" height="10.886" x="7.897" y="1.697" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.690196 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21944"/></filter><filter id="iLxPzYc" width="3.773" height="4.962" x="13.838" y="12.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21944" stdDeviation=".375"/></filter><filter id="i2vG7bb" width="2.923" height="3.962" x="14.572" y="12.32" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21944" stdDeviation=".125"/></filter><filter id="i9RaXcc" width=".958" height=".841" x="17.928" y="11.884" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21944" stdDeviation=".05"/></filter><filter id="isVyPcu" width="1.034" height="1.063" x="19.042" y="12.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21944" stdDeviation=".1"/></filter><filter id="iYFkKWd" width="1.157" height="1.227" x="13.306" y="11.928" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21944" stdDeviation=".1"/></filter><filter id="iml6hae" width="1.121" height=".851" x="12.303" y="11.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21944" stdDeviation=".05"/></filter><filter id="iYbKAum" width="3.582" height="2.502" x="10.973" y="8.778" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21944"/></filter><filter id="i1lkA1b" width="3.582" height="2.502" x="17.762" y="8.778" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21944"/></filter><filter id="iNYBxrb" width="3.582" height="2.352" x="10.848" y="8.897" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21944" stdDeviation=".25"/></filter><filter id="iJgX4be" width="3.582" height="2.352" x="17.718" y="8.811" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21944" stdDeviation=".25"/></filter><filter id="inQQyJc" width="3.695" height="1.445" x="14.127" y="16.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21944" stdDeviation=".05"/></filter><linearGradient id="iHLn7qb" x1="16" x2="16" y1="29.889" y2="29.303" gradientUnits="userSpaceOnUse"><stop class="mbdrodj7c"/><stop offset="1" class="twkbxyfkj"/></linearGradient><linearGradient id="izte09b" x1="9.903" x2="9.075" y1="13.663" y2="13.663" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="icbd3wd" x1="23.59" x2="22.532" y1="11.894" y2="15.169" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="in6uxEd" x1="21.245" x2="11.384" y1="13.806" y2="15.276" gradientUnits="userSpaceOnUse"><stop class="b941pszbd"/><stop offset="1" class="jtnk9gb3a"/></linearGradient><linearGradient id="iDnFRBc" x1="9.066" x2="12.052" y1="17.287" y2="16.898" gradientUnits="userSpaceOnUse"><stop class="ls27mhbfe"/><stop offset="1" class="ys1ri2qqc"/></linearGradient><linearGradient id="iS1Aftb" x1="9.757" x2="13.504" y1="12.958" y2="6.302" gradientUnits="userSpaceOnUse"><stop class="ts8ii3fly"/><stop offset="1" class="zlpmx2b9v"/></linearGradient><linearGradient id="ima4TKY" x1="14.918" x2="16.129" y1="14.657" y2="14.657" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="iWKrkrb" x1="17.245" x2="15.921" y1="15.074" y2="15.055" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="i7lM8lu" x1="16.285" x2="16.285" y1="16.032" y2="15.292" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="it4v2Be" x1="16.196" x2="16.196" y1="16.086" y2="15.87" gradientUnits="userSpaceOnUse"><stop class="e14d05bbo"/><stop offset="1" class="jt8p4rb1c"/></linearGradient><linearGradient id="iGjcx6r" x1="19.851" x2="19.446" y1="12.492" y2="12.742" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iSVdERd" x1="14.173" x2="13.768" y1="12.492" y2="12.742" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iuTCcEb" x1="13.075" x2="12.036" y1="9.904" y2="8.694" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="iyo8s7b" x1="19.073" x2="20.113" y1="9.818" y2="8.608" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-frowning-medium-light" /></template>
<style>
.a4g5pgffh {
  d: path("M19.876 12.807a1.1 1.1 0 0 0-.299-.597l-.335.368l.151.295z");
}

.ab4_rnbjl {
  stop-color: var(--svg-color--dcc291, #DCC291);
  stop-opacity: 0;
}

.aeqha4b6g {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.765 12.05c.082.11-.09.244-.285.39s-.34.248-.422.139c-.082-.11.01-.318.205-.463s.42-.175.502-.066");
}

.aik_z9b6i {
  stop-color: var(--svg-color--c28775, #C28775);
}

.axqjsnbkb {
  stop-color: var(--svg-color--176bb1, #176BB1);
  stop-opacity: 0;
}

.az568jbmj {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.943 11.456c-.843 0-1.555.581-1.749 1.367a.354.354 0 0 0 .346.44h2.88c.184 0 .33-.168.293-.351a1.81 1.81 0 0 0-1.77-1.456");
}

.b941pszbd {
  stop-color: var(--svg-color--fac39e, #FAC39E);
}

.bb6ud4ewj {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
  stop-opacity: 0;
}

.bh__h4bcu {
  cx: 12.863px;
  cy: 12.299px;
  rx: 0.503px;
  ry: 0.255px;
}

.cac2is6pz {
  stop-color: var(--svg-color--2888f9, #2888F9);
  stop-opacity: 0;
}

.cbzwtq_ut {
  fill: var(--svg-color--c68378, #C68378);
  d: path("m15.678 13.145l-1.06 2.195c-.13.451.184.903.63.903h.953c.446 0 .761-.458.63-.903l-.643-2.195c-.138-.486-.366-.486-.51 0");
}

.ccm87hbyo {
  cx: 9.903px;
  cy: 13.303px;
  r: 1.285px;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d_j_iqbmo {
  stop-color: var(--svg-color--e9b19b, #E9B19B);
  stop-opacity: 0;
}

.daw21qbgk {
  stop-color: var(--svg-color--b57195, #B57195);
  stop-opacity: 0;
}

.dlhcaxb1i {
  cx: 12.863px;
  cy: 12.299px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.503px;
  ry: 0.255px;
}

.dohbdcxhl {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
}

.e14d05bbo {
  stop-color: var(--svg-color--c27b77, #C27B77);
}

.eis6e-ilx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M17.141 17.67c-.918-.627-1.93-.26-2.34.005a.275.275 0 0 1-.298-.462c.495-.319 1.765-.806 2.949.004a.275.275 0 0 1-.31.454Z");
}

.ezktjkbgg {
  stop-color: var(--svg-color--d79a76, #D79A76);
  stop-opacity: 0;
}

.fek_kybrv {
  d: path("M18.85 11.807a1.152 1.152 0 0 1 1.11 1.456h-2.226a1.157 1.157 0 0 1 1.115-1.456");
}

.ft5dv1b6b {
  fill: none;
}

.g7lt91bhf {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.glysebnzk {
  d: path("m9.448 12.512l.063.002s-.069-1.102-.138-1.86c0-.344.138-.757.416-.963l.207-.207c.347-.276.485-.689.485-1.102V7.28c0-.344.208-.62.554-.689c.831-.206 2.563-.55 5.056-.55c2.494 0 4.225.344 5.057.55c.277.07.554.345.554.69v1.101c0 .413.207.826.484 1.102c.649.454.608.704.555 1.24c-.07.688-.139 1.859-.139 1.859h.023l-.343 5.111c-.207 2.285-2.003 3.878-4.145 3.878H13.99c-2.21 0-3.938-1.593-4.145-3.878z");
}

.gs643vbjw {
  stop-color: var(--svg-color--cb9173, #CB9173);
}

.gx0o3oiqw {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
  stop-opacity: 0;
}

.gx0xrfbie {
  stop-color: var(--svg-color--dca189, #DCA189);
}

.hpjuubccm {
  stop-color: var(--svg-color--eec19c, #EEC19C);
  stop-opacity: 0;
}

.i4pfhbczn {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
}

.j3anadbkm {
  stop-color: var(--svg-color--d79a76, #D79A76);
}

.jharhj-ni {
  cx: 9.903px;
  cy: 13.303px;
  r: 2.156px;
}

.joe29ub8h {
  d: path("M18.765 12.05c.082.11-.09.244-.285.39s-.34.248-.422.139c-.082-.11.01-.318.205-.463s.42-.175.502-.066");
}

.jt8p4rb1c {
  stop-color: var(--svg-color--c27b77, #C27B77);
  stop-opacity: 0;
}

.jtnk9gb3a {
  stop-color: var(--svg-color--c9917c, #C9917C);
}

.jx2nv7b5t {
  fill: var(--svg-color--88024e, #88024E);
  fill-rule: evenodd;
  d: path("M17.141 17.67c-.918-.627-1.93-.26-2.34.005a.275.275 0 0 1-.298-.462c.495-.319 1.765-.806 2.949.004a.275.275 0 0 1-.31.454");
}

.k1mq2zvhc {
  stop-color: var(--svg-color--ba7867, #BA7867);
}

.k64o5hods {
  stop-color: var(--svg-color--b57195, #B57195);
}

.kdw68kvvi {
  fill: var(--svg-color--000, #000);
  d: path("M18.19 12.959c0-.367.293-.66.66-.66a.657.657 0 0 1 .586.964h-1.168a.6.6 0 0 1-.078-.304");
}

.klkmm6j5l {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M20.55 10.413a3.03 3.03 0 0 1-2.082-.852");
}

.krj1s2r6y {
  cx: 22.187px;
  cy: 13.303px;
  r: 2.156px;
}

.kwfxid2mc {
  stop-color: var(--svg-color--176bb1, #176BB1);
}

.kwz3apblc {
  stop-color: var(--svg-color--f5c8a5, #F5C8A5);
}

.kxzxrmw_u {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
}

.lemuo5beu {
  stop-color: var(--svg-color--c98583, #C98583);
  stop-opacity: 0;
}

.lgt5l_bso {
  d: path("M14.263 12.824c0-.373-.303-.621-.385-.696l-.372.36l.23.466z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ls27mhbfe {
  stop-color: var(--svg-color--d99e84, #D99E84);
}

.ls62f1bvq {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
}

.mbdrodj7c {
  stop-color: var(--svg-color--2771fc, #2771FC);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.n4b_03b5p {
  d: path("M13.21 11.807a1.152 1.152 0 0 0-1.11 1.456h2.226q.04-.149.042-.304a1.16 1.16 0 0 0-1.158-1.152");
}

.nny4dempw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M11.598 10.499c.656 0 1.441-.239 2.082-.852");
}

.nylmffbzf {
  cx: 22.187px;
  cy: 13.303px;
  r: 1.285px;
}

.o6sle6pni {
  stop-color: var(--svg-color--b87862, #B87862);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.op2kwubyv {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
}

.pjldzot5y {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.117 11.456c.843 0 1.555.581 1.749 1.367a.354.354 0 0 1-.346.44h-2.88a.297.297 0 0 1-.294-.351a1.804 1.804 0 0 1 1.77-1.456");
}

.pkb_n7lvs {
  stop-color: var(--svg-color--ad726e, #AD726E);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pqf0u3bgb {
  stop-color: var(--svg-color--a57146, #A57146);
}

.qm8bcbjeu {
  width: 5.188px;
  height: 6.789px;
  x: 13.451px;
  y: 17.141px;
  rx: 2.594px;
}

.qt738z6up {
  fill: var(--svg-color--9a6634, #9A6634);
  fill-rule: evenodd;
  d: path("M14.131 9.371c.239.25.23.645-.019.884a3.66 3.66 0 0 1-2.514 1.025a.625.625 0 1 1 0-1.25a2.4 2.4 0 0 0 1.65-.678a.625.625 0 0 1 .883.02");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qyie81bpb {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m15.54 12.935l-.686 2.194a.696.696 0 0 0 .672.903h1.015a.698.698 0 0 0 .672-.903l-.686-2.194c-.147-.486-.833-.486-.987 0");
}

.qyobb4hvj {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
}

.rl_l27czx {
  stop-color: var(--svg-color--2e96ff, #2E96FF);
}

.rmv5f6ekt {
  d: path("M16 19.631c-5.502 0-9.963 4.461-9.963 9.963v.21h19.926v-.21c0-5.502-4.46-9.963-9.963-9.963");
}

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.s236rjbsc {
  stop-color: var(--svg-color--af6f5d, #AF6F5D);
}

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
}

.spg62za8n {
  stop-color: var(--svg-color--e9b19b, #E9B19B);
}

.szm1jtb2t {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
  stop-opacity: 0;
}

.t8ce_ac-b {
  fill: var(--svg-color--ebcc94, #EBCC94);
  d: path("m22.256 4.939l.554.275c.97.482 1.524 1.584 1.316 2.755l-.762 3.925c-.068.406-.336.679-.738.689h-.024s.07-1.17.139-1.86c.056-.559-.042-.73-.554-1.24c-.277-.275-.485-.688-.485-1.101V7.28c0-.344-.277-.62-.554-.689c-.831-.206-2.563-.55-5.056-.55c-2.494 0-4.225.344-5.057.55c-.346.07-.554.345-.554.69v1.101c0 .413-.138.826-.485 1.102l-.207.207c-.277.206-.416.62-.416.964c.07.757.139 1.86.139 1.86q-.033 0-.064-.003a.82.82 0 0 1-.768-.687L7.92 7.9c-.139-1.102.415-2.204 1.385-2.686l.554-.275c.346-.207.692-.482 1.039-.758l1.246-1.308c.762-.69 1.87-.896 2.84-.414a3.8 3.8 0 0 0 2.148 0c1.038-.344 2.216-.068 3.047.69l1.039 1.032c.277.344.623.551 1.039.758");
}

.t91gw6b7m {
  stop-color: var(--svg-color--e5b39b, #E5B39B);
}

.ts8ii3fly {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
}

.twkbxyfkj {
  stop-color: var(--svg-color--2771fc, #2771FC);
  stop-opacity: 0;
}

.u7v6tactn {
  stop-color: var(--svg-color--eec19c, #EEC19C);
}

.u92u_5bxb {
  d: path("m22.256 4.939l.554.275c.97.482 1.524 1.584 1.316 2.755l-.762 3.925c-.068.406-.336.679-.738.689h-.024s.07-1.17.139-1.86c.056-.559-.042-.73-.554-1.24c-.277-.275-.485-.688-.485-1.101V7.28c0-.344-.277-.62-.554-.689c-.831-.206-2.563-.55-5.056-.55c-2.494 0-4.225.344-5.057.55c-.346.07-.554.345-.554.69v1.101c0 .413-.138.826-.485 1.102l-.207.207c-.277.206-.416.62-.416.964c.07.757.139 1.86.139 1.86q-.033 0-.064-.003a.82.82 0 0 1-.768-.687L7.92 7.9c-.139-1.102.415-2.204 1.385-2.686l.554-.275c.346-.207.692-.482 1.039-.758l1.246-1.308c.762-.69 1.87-.896 2.84-.414a3.8 3.8 0 0 0 2.148 0c1.038-.344 2.216-.068 3.047.69l1.039 1.032c.277.344.623.551 1.039.758");
}

.uylyaxbnq {
  stop-color: var(--svg-color--c2837a, #C2837A);
  stop-opacity: 0;
}

.v-2sss5_q {
  stop-color: var(--svg-color--4ab3ff, #4AB3FF);
}

.v4v-qb7kx {
  stop-color: var(--svg-color--cb9173, #CB9173);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v9jmb1b6x {
  fill: var(--svg-color--9a6634, #9A6634);
  fill-rule: evenodd;
  d: path("M17.935 9.371a.625.625 0 0 0 .02.884a3.66 3.66 0 0 0 2.514 1.025a.625.625 0 1 0 0-1.25a2.4 2.4 0 0 1-1.65-.678a.625.625 0 0 0-.884.02");
}

.vith88blc {
  stop-color: var(--svg-color--3a8fc0, #3A8FC0);
}

.vs8934bpj {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
  stop-opacity: 0;
}

.w-a4mnbis {
  stop-color: var(--svg-color--dcc291, #DCC291);
}

.wvivicznw {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
  stop-opacity: 0;
}

.xjk10obil {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
  stop-opacity: 0;
}

.xogpiobqs {
  stop-color: var(--svg-color--a57146, #A57146);
  stop-opacity: 0;
}

.xrkexibub {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
  stop-opacity: 0;
}

.y19dso42s {
  d: path("m15.54 12.935l-.686 2.194a.696.696 0 0 0 .672.903h1.015a.698.698 0 0 0 .672-.903l-.686-2.194c-.147-.486-.833-.486-.987 0");
}

.y7nn5tbfc {
  stop-color: var(--svg-color--c2837a, #C2837A);
}

.ybxkyhlla {
  cx: 22.187px;
  cy: 13.303px;
  r: 1.285px;
  fill: var(--svg-color--d79e81, #D79E81);
}

.ylk4vpbqv {
  stop-color: var(--svg-color--2888f9, #2888F9);
}

.ys1ri2qqc {
  stop-color: var(--svg-color--d99e84, #D99E84);
  stop-opacity: 0;
}

.ze1cb0iau {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
  stop-opacity: 0;
}

.zil-t4d5t {
  fill: var(--svg-color--000, #000);
  d: path("M13.87 12.959a.657.657 0 0 0-.66-.66a.657.657 0 0 0-.586.964h1.168a.65.65 0 0 0 .078-.304");
}

.zlpmx2b9v {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
  stop-opacity: 0;
}

.zx529yrpf {
  stop-color: var(--svg-color--3a8fc0, #3A8FC0);
  stop-opacity: 0;
}

</style>
