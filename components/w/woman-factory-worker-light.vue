<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iB8PmSb)"><path fill="url(#iWH3P4d)" clip-rule="evenodd" class="rknqf7fgs"/><path fill="url(#iSZ0Lcb)" clip-rule="evenodd" class="rknqf7fgs"/><path fill="url(#iotWnzt)" clip-rule="evenodd" class="rknqf7fgs"/></g><g filter="url(#iyHSMPe)"><path fill="url(#i1Pd52d)" class="e5n7-cbky"/><path fill="url(#iM6rPqd)" class="e5n7-cbky"/></g><g filter="url(#ibpfIJe)"><path class="eo9zbabbe"/></g><g filter="url(#i3XVCqe)"><path class="x9-b3hbfy"/></g><g filter="url(#iLGZPSb)"><path class="a424ylq9x"/><path fill="url(#i7bctJc)" class="m3dxw5b4u"/><path fill="url(#izNqDsc)" class="m3dxw5b4u"/><path fill="url(#it3vqkc)" class="m3dxw5b4u"/></g><path class="a1i_j40xh"/><path fill="url(#igSiocc)" class="rq76sybla"/><path fill="url(#iQD9PdN)" class="rq76sybla"/><path fill="url(#ifkmApd)" class="rq76sybla"/><path fill="url(#iUzRGHc)" class="rq76sybla"/><path fill="url(#iFGxoeb)" class="lt_b3wboz"/><path fill="url(#i5m29vW)" class="lt_b3wboz"/><path class="vbc9nqbss"/><path fill="url(#iPRoNnL)" class="pi6c47yng"/><path class="javsik_yi"/><path fill="url(#iOgo57h)" class="u-q3e7b8s"/><path fill="url(#isXfl9d)" class="f311uubal"/><path fill="url(#ii0Cl9c)" class="f311uubal"/><path fill="url(#iWL0fQe)" class="f311uubal"/><path fill="url(#i3MqPDW)" class="fbjx3y-qb"/><path fill="url(#i8fe9wd)" class="fbjx3y-qb"/><g filter="url(#iGifTvd)"><path class="kc9q3mbff"/><path fill="url(#ifFH9Wc)" class="qv8wc6zla"/></g><path fill="url(#iUEJUid)" class="ue1gv6enh"/><path fill="url(#i294t4w)" class="ue1gv6enh"/><g filter="url(#iIlikxe)"><path fill="url(#ipsyrne)" class="na59ribzw"/></g><path class="vczswwwcd"/><g filter="url(#iNya15d)"><path fill="url(#imJjD7b)" class="qtzewq2gr"/><path fill="url(#is7JiJc)" class="qtzewq2gr"/><path fill="url(#ihwje5b)" class="qtzewq2gr"/><path fill="url(#i595Jhe)" class="qtzewq2gr"/><path fill="url(#iFC06Gc)" class="qtzewq2gr"/></g><g filter="url(#ibP3Udb)"><path fill="url(#iOKq7lc)" class="qtzewq2gr"/><path fill="url(#iI8fpid)" class="qtzewq2gr"/><path fill="url(#ivXSXbb)" class="qtzewq2gr"/><path fill="url(#inoTRvd)" class="qtzewq2gr"/><path fill="url(#ifrujYb)" class="qtzewq2gr"/></g><path fill="url(#iElbqJe)" class="qtzewq2gr"/><g filter="url(#iRU8nfd)"><path stroke="url(#ijiAIMd)" class="bzs2-ddka"/></g><g filter="url(#i5cfB7c)"><path stroke="url(#iNT2srd)" class="pjsi77bhr"/></g><g filter="url(#iGkneAZ)"><path stroke="url(#iflwwud)" class="oool1tdti"/></g><g filter="url(#igg8cjq)"><path fill="url(#ih8wQsd)" class="eh59-c2og"/></g><path fill="url(#iW5pAAe)" class="dw3xeubwh"/><path fill="url(#iARIqvb)" class="dw3xeubwh"/><g filter="url(#iZ1Wjyb)"><path fill="url(#izZpByb)" class="wg_w1vbgj"/></g><g filter="url(#itNMl7d)"><path fill="url(#iNhriUd)" class="v9wc5kdsn"/></g><g filter="url(#i836Fob)"><path fill="url(#ilzzYwc)" class="g8y5_ueit"/></g><path fill="url(#iW3PiEb)" class="g8y5_ueit"/><path fill="url(#iCeflMb)" class="g8y5_ueit"/><path fill="url(#iS0QRBb)" class="g8y5_ueit"/><path fill="url(#ismniqb)" class="g8y5_ueit"/><path fill="url(#i3eEY6b)" class="g8y5_ueit"/><path fill="url(#iuXKrfD)" class="g8y5_ueit"/><g filter="url(#iEZWTuc)"><path class="v70cngc9z"/></g><g filter="url(#iUfl7Og)"><path fill="url(#itol2ue)" class="vxca8ab-k"/></g><g filter="url(#icdvHub)"><path stroke="url(#iNxTY6d)" class="jt6x1fb4w"/></g><path fill="url(#iEh528d)" class="l8qslmb5u"/><g filter="url(#i2y2Nlc)"><path class="d8j-r9bsb"/></g><g filter="url(#iZG3irv)"><path class="pmikb6mtj"/></g><g filter="url(#i5QohGc)"><path class="he2vvvbiu"/></g><g filter="url(#ismz8Pe)"><path clip-rule="evenodd" class="iegtj7has"/></g><path class="knosl_37y"/><path fill="url(#ipdtO8d)" class="s3p5lff5x"/><path class="ngwa02-tu"/><g filter="url(#i2r2e6d)"><path class="b9xd2sfxu"/><path fill="url(#illsOim)" class="lkgfrvbcs"/></g><g filter="url(#iQiONXc)"><path fill="url(#iz27EMc)" class="pdra6ipeg"/></g><path class="y9d5neb6h"/><path fill="url(#ia1chte)" class="jv7e0m1bl"/><path class="qjc1qgb0d"/><g filter="url(#iwA6EOd)"><path fill="url(#iMcjOzc)" class="rxmjvacge"/></g><g filter="url(#iHMrykW)"><ellipse transform="rotate(-27.914 12.28 9.93)" class="v6_fcq9so"/><ellipse fill="url(#i7Oj7Cc)" transform="rotate(-27.914 12.28 9.93)" class="v-p3thbyp"/></g><g filter="url(#i4eU4pQ)"><path class="yjsg34f1d"/></g><g filter="url(#iTzcKHd)"><path class="rb6ci4jgt"/></g><path fill="url(#icBL91d)" class="iycy_sbnz"/><path fill="url(#ibvcPeT)" class="g9arp8b8o"/><path fill="url(#ic8iSPb)" class="g9arp8b8o"/><path fill="url(#iLeaTZU)" class="sb1phf9zd"/><path fill="url(#iE9kqQd)" class="sb1phf9zd"/><path fill="url(#ijzTWdd)" class="ltwsa8bld"/><path fill="url(#iT74aTv)" class="ltwsa8bld"/><path fill="url(#ivqY3ab)" class="ltwsa8bld"/><g filter="url(#iQRV9Je)"><path fill="url(#iCmdwmN)" class="o12zmvuzn"/></g><g filter="url(#iaqkCcc)"><path class="ojb-ttbmo"/></g><g filter="url(#iwAiKJe)"><path class="ac3zfwb5z"/></g><g filter="url(#iuT6PEc)"><path fill="url(#igg6KEo)" class="ah-0903bl"/></g><defs><radialGradient id="iSZ0Lcb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52301 0 0 -1.79688 22.36 12.616)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iotWnzt" cx="0" cy="0" r="1" gradientTransform="rotate(102.551 .208 7.835)scale(2.59322)" gradientUnits="userSpaceOnUse"><stop class="s0ihitbab"/><stop offset="1" class="y8uqe7b6k"/></radialGradient><radialGradient id="iM6rPqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.5 5.875 0 20.418 30)" gradientUnits="userSpaceOnUse"><stop class="bbqwceq4e"/><stop offset="1" class="s5pm96b_v"/></radialGradient><radialGradient id="i7bctJc" cx="0" cy="0" r="1" gradientTransform="rotate(137.578 3.33 12.372)scale(3.51039 2.85287)" gradientUnits="userSpaceOnUse"><stop class="ypv_kpaja"/><stop offset="1" class="iv7bj_baj"/></radialGradient><radialGradient id="izNqDsc" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 1.72406 -2.87775 -1.46054 13.106 16.844)" gradientUnits="userSpaceOnUse"><stop offset=".316" class="d7sh3eboe"/><stop offset="1" class="tizux9w7p"/></radialGradient><radialGradient id="ifkmApd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.94352 -1.86047 0 16.66 16.037)" gradientUnits="userSpaceOnUse"><stop offset=".368" class="rtj8_6bqg"/><stop offset="1" class="m8_l30tsr"/></radialGradient><radialGradient id="iUzRGHc" cx="0" cy="0" r="1" gradientTransform="matrix(-.94683 2.47509 -1.65865 -.6345 15.664 17.448)" gradientUnits="userSpaceOnUse"><stop offset=".307" class="s1rw4px-b"/><stop offset="1" class="p3_97vb4n"/></radialGradient><radialGradient id="iFGxoeb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.1875 3.9375 0 6.668 30)" gradientUnits="userSpaceOnUse"><stop class="mx797o4di"/><stop offset="1" class="m1_q07_me"/></radialGradient><radialGradient id="iPRoNnL" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.625 -3.70312 0 24.043 20.063)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="p7prpqhjw"/><stop offset="1" class="m4mhe8bqv"/></radialGradient><radialGradient id="iOgo57h" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.76563 6.85285 0 14.734 21.438)" gradientUnits="userSpaceOnUse"><stop offset=".469" class="ee8yo8bto"/><stop offset="1" class="dn7nvsb1v"/></radialGradient><radialGradient id="isXfl9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.69641 -1.82355 0 14.734 16.448)" gradientUnits="userSpaceOnUse"><stop class="eg1knzbxh"/><stop offset="1" class="hj4mfbctc"/></radialGradient><radialGradient id="i3MqPDW" cx="0" cy="0" r="1" gradientTransform="rotate(154.424 10.772 15.093)scale(2.44794 2.40172)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="tj2vllbvr"/><stop offset=".956" class="fop80r8ws"/></radialGradient><radialGradient id="i8fe9wd" cx="0" cy="0" r="1" gradientTransform="matrix(.78818 -.60013 .4599 .60401 26.205 23.598)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="q7l79-2rh"/><stop offset="1" class="aszpk2bre"/></radialGradient><radialGradient id="ifFH9Wc" cx="0" cy="0" r="1" gradientTransform="rotate(-45 32.088 -22.467)scale(.99437 .32275)" gradientUnits="userSpaceOnUse"><stop offset=".383" class="ky_dg6bhp"/><stop offset="1" class="qwfi8obtf"/></radialGradient><radialGradient id="i294t4w" cx="0" cy="0" r="1" gradientTransform="matrix(-1.45773 0 0 -.25781 25.259 22.922)" gradientUnits="userSpaceOnUse"><stop class="wp6rq3sqk"/><stop offset="1" class="hnxygroex"/></radialGradient><radialGradient id="is7JiJc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 24.568 25.305)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="ihwje5b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 24.568 26.6)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="i595Jhe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 24.568 27.85)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iFC06Gc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 24.568 29.2)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iI8fpid" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 24.568 25.305)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="ivXSXbb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 24.568 26.6)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="inoTRvd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 24.568 27.85)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="ifrujYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 24.568 29.2)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iElbqJe" cx="0" cy="0" r="1" gradientTransform="scale(3.72384 5.01752)rotate(90 1.09 6.07)" gradientUnits="userSpaceOnUse"><stop class="b4rjnnb6m"/><stop offset="1" class="bgp-eqwmb"/></radialGradient><radialGradient id="iW5pAAe" cx="0" cy="0" r="1" gradientTransform="matrix(-.41657 3.3751 -4.1856 -.5166 20.301 8.858)" gradientUnits="userSpaceOnUse"><stop offset=".104" class="xng4o8biy"/><stop offset=".811" class="ugclr1_ae"/></radialGradient><radialGradient id="iARIqvb" cx="0" cy="0" r="1" gradientTransform="matrix(1.27242 -.46819 .30286 .8231 19.9 12.234)" gradientUnits="userSpaceOnUse"><stop class="e_o4pyb1k"/><stop offset="1" class="veu345b3w"/></radialGradient><radialGradient id="iNhriUd" cx="0" cy="0" r="1" gradientTransform="matrix(-.66406 -.0616 .11497 -1.2396 9.736 10.624)" gradientUnits="userSpaceOnUse"><stop class="yd1ogmbpn"/><stop offset="1" class="po8erdb9o"/></radialGradient><radialGradient id="ilzzYwc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.85065 3.01535 -4.036 -7.831 17.594 10.086)" gradientUnits="userSpaceOnUse"><stop class="ce3hsxbpz"/><stop offset=".792" class="d_e12kbzd"/></radialGradient><radialGradient id="iW3PiEb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.5625 -2.23353 0 15.931 7.24)" gradientUnits="userSpaceOnUse"><stop offset=".23" class="d5v4cifyl"/><stop offset="1" class="q0q7pnllq"/></radialGradient><radialGradient id="iS0QRBb" cx="0" cy="0" r="1" gradientTransform="rotate(68.962 4.663 17.851)scale(5.65841 5.23213)" gradientUnits="userSpaceOnUse"><stop offset=".068" class="h_qe7fbbg"/><stop offset="1" class="b1b52y3-n"/></radialGradient><radialGradient id="ismniqb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.05615 -8.39787 0 14.719 9.74)" gradientUnits="userSpaceOnUse"><stop offset=".601" class="h-qkfsbcb"/><stop offset="1" class="ghxd2_qoa"/></radialGradient><radialGradient id="i3eEY6b" cx="0" cy="0" r="1" gradientTransform="rotate(-139.611 8.044 2.515)scale(1.37447 .89292)" gradientUnits="userSpaceOnUse"><stop offset=".379" class="iqc_7zb-q"/><stop offset="1" class="gst7rh7-l"/></radialGradient><radialGradient id="iuXKrfD" cx="0" cy="0" r="1" gradientTransform="matrix(-4.125 2.85938 -1.45866 -2.1043 11.572 6.61)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="pf-t-gb_g"/><stop offset="1" class="lf2lmgb_v"/><stop offset="1" class="q8-xadb4t"/></radialGradient><radialGradient id="iNxTY6d" cx="0" cy="0" r="1" gradientTransform="matrix(.35636 -.6504 1.87012 1.02467 13.577 13.95)" gradientUnits="userSpaceOnUse"><stop class="axbpixbbs"/><stop offset="1" class="jwg_rcc4c"/></radialGradient><radialGradient id="iEh528d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.75673 2.97657 0 14.734 14.212)" gradientUnits="userSpaceOnUse"><stop class="jase_0f7h"/><stop offset="1" class="zn-qjxbde"/></radialGradient><radialGradient id="ipdtO8d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81164 -1.291 0 16.917 10.027)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="illsOim" cx="0" cy="0" r="1" gradientTransform="matrix(-.23182 -.29873 .41128 -.31916 16.688 10.111)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ia1chte" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81164 -1.29101 0 12.55 10.027)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i7Oj7Cc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00773 -.49386 .59363 -.0093 12.264 10.246)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ic8iSPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.3125 -.47665 0 23.309 6.469)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="y66dh_b5l"/><stop offset="1" class="nzjwoybta"/></radialGradient><radialGradient id="iLeaTZU" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.40034 6.13 0 14.849 7.33)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="ixw-oi7aq"/><stop offset="1" class="mguibccfx"/></radialGradient><radialGradient id="ijzTWdd" cx="0" cy="0" r="1" gradientTransform="rotate(129.472 9.359 6.843)scale(6.19389 12.2026)" gradientUnits="userSpaceOnUse"><stop class="qyg3b1b6n"/><stop offset="1" class="p64oiyb7x"/></radialGradient><radialGradient id="iT74aTv" cx="0" cy="0" r="1" gradientTransform="rotate(146.725 7.907 4.576)scale(9.56883 10.9225)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="yytwt1d8s"/><stop offset="1" class="s1a8ycb7r"/></radialGradient><radialGradient id="iCmdwmN" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.71875 -10.576 0 14.791 6.156)" gradientUnits="userSpaceOnUse"><stop class="z2rllvutr"/><stop offset="1" class="t8ye-ilvp"/></radialGradient><filter id="iB8PmSb" width="15.024" height="15.274" x="7.337" y="2.036" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.211765 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2033"/></filter><filter id="iyHSMPe" width="22.99" height="15" x="3.739" y="15.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.431373 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2033"/></filter><filter id="ibpfIJe" width="5.492" height="8.119" x="10.431" y="15.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2033" stdDeviation=".5"/></filter><filter id="i3XVCqe" width="5.492" height="8.113" x="13.872" y="15.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2033" stdDeviation=".5"/></filter><filter id="iLGZPSb" width="3.592" height="6.219" x="10.712" y="15.408" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.337255 0 0 0 0 0.811765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2033"/></filter><filter id="iGifTvd" width="3.02" height="8.58" x="23.729" y="14.21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.501961 0 0 0 0 0.529412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2033"/></filter><filter id="iIlikxe" width="3.675" height="3.685" x="24.636" y="12.621" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.870588 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2033"/></filter><filter id="iNya15d" width="4.468" height="5.556" x="22.131" y="24.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.443137 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2033"/></filter><filter id="ibP3Udb" width="4.468" height="5.556" x="22.131" y="24.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.509804 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2033"/></filter><filter id="iRU8nfd" width="2.097" height=".3" x="22.598" y="25.852" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2033" stdDeviation=".05"/></filter><filter id="i5cfB7c" width="2.097" height=".3" x="22.52" y="27.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2033" stdDeviation=".05"/></filter><filter id="iGkneAZ" width="2.097" height=".3" x="22.598" y="28.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2033" stdDeviation=".05"/></filter><filter id="igg8cjq" width="3.319" height="3.219" x="8.436" y="9.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.635294 0 0 0 0 0.568627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2033"/></filter><filter id="iZ1Wjyb" width="3.149" height="3.149" x="17.988" y="9.049" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2033" stdDeviation=".25"/></filter><filter id="itNMl7d" width="2.649" height="2.649" x="8.741" y="9.299" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2033" stdDeviation=".125"/></filter><filter id="i836Fob" width="10.706" height="10.881" x="9.616" y="5.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.662745 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2033"/></filter><filter id="iEZWTuc" width="2.878" height="3.683" x="13.132" y="9.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2033" stdDeviation=".25"/></filter><filter id="iUfl7Og" width="2.078" height="2.883" x="13.695" y="9.88" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.796078 0 0 0 0 0.560784 0 0 0 0 0.568627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2033"/><feGaussianBlur result="effect2_foregroundBlur_4002_2033" stdDeviation=".05"/></filter><filter id="icdvHub" width="3.704" height="1.526" x="12.882" y="12.973" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2033" stdDeviation=".05"/></filter><filter id="i2y2Nlc" width="3.002" height="1.286" x="15.676" y="9.219" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2033"/></filter><filter id="iZG3irv" width="3.002" height="1.286" x="10.789" y="9.219" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2033"/></filter><filter id="i5QohGc" width="2.354" height="1.091" x="10.924" y="7.795" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.113725 0 0 0 0 0.0784314 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2033"/></filter><filter id="ismz8Pe" width="2.354" height="1.091" x="16.343" y="7.795" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.113725 0 0 0 0 0.0784314 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2033"/></filter><filter id="i2r2e6d" width=".787" height=".696" x="16.182" y="9.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2033" stdDeviation=".05"/></filter><filter id="iQiONXc" width=".891" height=".913" x="17.022" y="9.662" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2033" stdDeviation=".1"/></filter><filter id="iwA6EOd" width=".986" height="1.04" x="12.578" y="9.598" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2033" stdDeviation=".1"/></filter><filter id="iHMrykW" width=".913" height=".704" x="11.823" y="9.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2033" stdDeviation=".05"/></filter><filter id="i4eU4pQ" width="2.061" height=".778" x="16.474" y="8.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2033" stdDeviation=".075"/></filter><filter id="iTzcKHd" width="2.061" height=".778" x="11.02" y="8.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2033" stdDeviation=".075"/></filter><filter id="iQRV9Je" width="15.17" height="4.76" x="7.155" y="5.371" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.47451 0 0 0 0 0.827451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2033"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.329412 0 0 0 0 0.627451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2033" result="effect2_innerShadow_4002_2033"/></filter><filter id="iaqkCcc" width="9.99" height="2.47" x="9.739" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.843137 0 0 0 0 0.835294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2033"/></filter><filter id="iwAiKJe" width="6.31" height="2.47" x="13.419" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.552941 0 0 0 0 0.890196 0 0 0 0 0.92549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2033"/></filter><filter id="iuT6PEc" width="1.556" height="3.181" x="14.141" y="9.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2033" stdDeviation=".15"/></filter><linearGradient id="iWH3P4d" x1="21.65" x2="12.3" y1="12.584" y2="17.31" gradientUnits="userSpaceOnUse"><stop class="bk_sxpbcv"/><stop offset="1" class="w5wbm7itt"/></linearGradient><linearGradient id="i1Pd52d" x1="14.735" x2="14.735" y1="16.438" y2="30.563" gradientUnits="userSpaceOnUse"><stop class="troaenb0e"/><stop offset="1" class="jsbk_hbmd"/></linearGradient><linearGradient id="it3vqkc" x1="10.637" x2="11.379" y1="18.219" y2="18.242" gradientUnits="userSpaceOnUse"><stop offset=".344" class="u9ri-jbkw"/><stop offset="1" class="j0xtzac4y"/></linearGradient><linearGradient id="igSiocc" x1="18.805" x2="18.012" y1="18.937" y2="18.937" gradientUnits="userSpaceOnUse"><stop class="ph46gxbvy"/><stop offset="1" class="s21zh4b3w"/></linearGradient><linearGradient id="iQD9PdN" x1="16.746" x2="17.254" y1="20.766" y2="19.984" gradientUnits="userSpaceOnUse"><stop class="sq-bwm1qa"/><stop offset="1" class="s21zh4b3w"/></linearGradient><linearGradient id="i5m29vW" x1="7.769" x2="5.387" y1="27.844" y2="27.844" gradientUnits="userSpaceOnUse"><stop class="r5fk93cur"/><stop offset="1" class="bl3c3b0wv"/></linearGradient><linearGradient id="ii0Cl9c" x1="12.723" x2="13.744" y1="16.325" y2="16.325" gradientUnits="userSpaceOnUse"><stop class="fdnml8bad"/><stop offset="1" class="w60oimv2y"/></linearGradient><linearGradient id="iWL0fQe" x1="17.009" x2="16.009" y1="16.668" y2="16.668" gradientUnits="userSpaceOnUse"><stop offset=".125" class="fo0fkzbam"/><stop offset="1" class="te5b1ia_g"/></linearGradient><linearGradient id="iUEJUid" x1="25.259" x2="23.652" y1="24.265" y2="24.265" gradientUnits="userSpaceOnUse"><stop class="ec1jnjbjz"/><stop offset="1" class="yd41utmlw"/></linearGradient><linearGradient id="ipsyrne" x1="25.442" x2="26.863" y1="15.852" y2="14.43" gradientUnits="userSpaceOnUse"><stop class="tgqsm4b7j"/><stop offset="1" class="k1-983bet"/></linearGradient><linearGradient id="imJjD7b" x1="26.159" x2="22.131" y1="28.063" y2="28.063" gradientUnits="userSpaceOnUse"><stop offset=".146" class="hqh-1rbea"/><stop offset=".861" class="id19t5fes"/></linearGradient><linearGradient id="iOKq7lc" x1="26.159" x2="22.131" y1="28.063" y2="28.063" gradientUnits="userSpaceOnUse"><stop offset=".146" class="v5rheyc4i"/><stop offset=".861" class="j1qr75obr"/></linearGradient><linearGradient id="ijiAIMd" x1="22.748" x2="24.458" y1="26.08" y2="26.08" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iNT2srd" x1="22.67" x2="24.38" y1="27.385" y2="27.385" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iflwwud" x1="22.748" x2="24.458" y1="28.689" y2="28.689" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="ih8wQsd" x1="9.291" x2="10.046" y1="9.109" y2="12.094" gradientUnits="userSpaceOnUse"><stop class="bf2pvhbua"/><stop offset="1" class="j23wz_bzl"/></linearGradient><linearGradient id="izZpByb" x1="20.236" x2="19.563" y1="10.015" y2="11.698" gradientUnits="userSpaceOnUse"><stop offset=".355" class="hb081ceky"/><stop offset=".873" class="tti66ybyp"/></linearGradient><linearGradient id="iCeflMb" x1="14.719" x2="14.719" y1="6.999" y2="7.656" gradientUnits="userSpaceOnUse"><stop offset=".399" class="kgfm32btz"/><stop offset="1" class="qawbbbcem"/></linearGradient><linearGradient id="itol2ue" x1="15.111" x2="15.111" y1="10.185" y2="12.518" gradientUnits="userSpaceOnUse"><stop offset=".729" class="hzb8dacww"/><stop offset="1" class="vaw3c9xmk"/></linearGradient><linearGradient id="iz27EMc" x1="17.694" x2="17.381" y1="10.08" y2="10.274" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iMcjOzc" x1="13.294" x2="12.981" y1="10.08" y2="10.274" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="icBL91d" x1="6.356" x2="7.059" y1="7.633" y2="6.703" gradientUnits="userSpaceOnUse"><stop class="qo28zhh9b"/><stop offset="1" class="yhrc8s1zu"/></linearGradient><linearGradient id="ibvcPeT" x1="22.462" x2="22.462" y1="6" y2="8.01" gradientUnits="userSpaceOnUse"><stop class="ott3_jqut"/><stop offset="1" class="l8p6brbrs"/></linearGradient><linearGradient id="iE9kqQd" x1="15.051" x2="15.051" y1="7.33" y2="7.174" gradientUnits="userSpaceOnUse"><stop class="j3h4o1d7b"/><stop offset="1" class="lo1ogpbbw"/></linearGradient><linearGradient id="ivqY3ab" x1="6.787" x2="7.841" y1="7.125" y2="7.125" gradientUnits="userSpaceOnUse"><stop class="it1_ig0bc"/><stop offset="1" class="qgmif2bih"/></linearGradient><linearGradient id="igg6KEo" x1="14.919" x2="14.919" y1="9.584" y2="12.165" gradientUnits="userSpaceOnUse"><stop offset=".128" class="g6jrnjb2b"/><stop offset="1" class="i05ykabkr"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-factory-worker-light" /></template>
<style>
.a1i_j40xh {
  fill: var(--svg-color--3c77cf, #3C77CF);
  d: path("M18.804 16.276v4.576c.003.26-.023.578-.25.718c-.233.145-.58-.018-.742-.14l-2.5-1.766v-4.15c1.228.064 2.403.329 3.492.762");
}

.a424ylq9x {
  fill: var(--svg-color--3674c9, #3674C9);
  d: path("M10.812 16.221v4.63c-.002.26.024.579.25.72c.234.144.581-.019.743-.141l2.5-1.766v-4.156a11 11 0 0 0-3.493.713");
}

.ac3zfwb5z {
  fill: var(--svg-color--8cf5ff, #8CF5FF);
  d: path("m16.169 2l-2.45 2.37h5.45c.31 0 .56-.25.56-.56V2.19c-.4-.12-.83-.19-1.27-.19z");
}

.ah-0903bl {
  d: path("m14.748 11.804l.02-2.22l.476 2.297h.01a.142.142 0 0 1 0 .284h-.67a.142.142 0 0 1 0-.284h.088a.077.077 0 0 0 .076-.077");
}

.aszpk2bre {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
  stop-opacity: 0;
}

.axbpixbbs {
  stop-color: var(--svg-color--d7a293, #D7A293);
}

.b1b52y3-n {
  stop-color: var(--svg-color--a9707c, #A9707C);
  stop-opacity: 0;
}

.b4rjnnb6m {
  stop-color: var(--svg-color--ffe0c3, #FFE0C3);
}

.b570nlb5r {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
  stop-opacity: 0;
}

.b9xd2sfxu {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.852 9.738c.064.085-.069.189-.22.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.05");
}

.bbqwceq4e {
  stop-color: var(--svg-color--3878e5, #3878E5);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bf2pvhbua {
  stop-color: var(--svg-color--a0685a, #A0685A);
}

.bgp-eqwmb {
  stop-color: var(--svg-color--ffe0c3, #FFE0C3);
  stop-opacity: 0;
}

.bk_sxpbcv {
  stop-color: var(--svg-color--221d20, #221D20);
}

.bl3c3b0wv {
  stop-color: var(--svg-color--3e6fc6, #3E6FC6);
  stop-opacity: 0;
}

.bzs2-ddka {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M22.748 26.002h1.797");
}

.ce3hsxbpz {
  stop-color: var(--svg-color--f9c5ae, #F9C5AE);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d_e12kbzd {
  stop-color: var(--svg-color--d49e94, #D49E94);
}

.d5v4cifyl {
  stop-color: var(--svg-color--ebb7aa, #EBB7AA);
}

.d7sh3eboe {
  stop-color: var(--svg-color--26386d, #26386D);
}

.d8j-r9bsb {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M15.876 10.055c.266-.467.67-.836 1.538-.836c.38 0 .747.105 1.073.369c.27.217.233.495.025.6l-.556.317c-.652-.211-1.373-.24-2.08-.45");
}

.dn7nvsb1v {
  stop-color: var(--svg-color--806879, #806879);
}

.dw3xeubwh {
  d: path("M19.563 12.234a1.61 1.61 0 1 0 0-3.22a1.61 1.61 0 0 0 0 3.22");
}

.e_o4pyb1k {
  stop-color: var(--svg-color--c69693, #C69693);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e5n7-cbky {
  d: path("M14.739 15.5c-6.07 0-11 4.92-11 11V30h20.99a1 1 0 0 0 1-1v-2.5c0-6.08-4.92-11-10.99-11");
}

.ec1jnjbjz {
  stop-color: var(--svg-color--675479, #675479);
}

.ee8yo8bto {
  stop-color: var(--svg-color--806879, #806879);
  stop-opacity: 0;
}

.eg1knzbxh {
  stop-color: var(--svg-color--db96af, #DB96AF);
}

.eh59-c2og {
  d: path("M10.046 12.234a1.61 1.61 0 1 0 0-3.22a1.61 1.61 0 0 0 0 3.22");
}

.eo9zbabbe {
  fill: var(--svg-color--1e6dc3, #1E6DC3);
  d: path("M11.432 16.72v4.63c-.003.26.023.578.25.718c.233.145.58-.018.742-.14l2.5-1.766v-4.156c-1.226.048-2.4.296-3.492.713");
}

.f311uubal {
  d: path("M14.734 18.144c-.865 0-2.01-.576-2.01-1.729v-3.02c0-1.143.897-2.073 2.01-2.073s2.01.93 2.01 2.083v3.02c-.01 1.143-1.146 1.72-2.01 1.72");
}

.fbjx3y-qb {
  d: path("M25.449 23.1c.55 0 1 .45 1 1v2.29h-2V24.1c0-.55.45-1 1-1");
}

.fdnml8bad {
  stop-color: var(--svg-color--7a4b49, #7A4B49);
}

.fo0fkzbam {
  stop-color: var(--svg-color--7d4e47, #7D4E47);
}

.fop80r8ws {
  stop-color: var(--svg-color--c79175, #C79175);
}

.ft5dv1b6b {
  fill: none;
}

.g6jrnjb2b {
  stop-color: var(--svg-color--fecdbb, #FECDBB);
  stop-opacity: 0;
}

.g8y5_ueit {
  d: path("M9.616 8.631c.02-.949.574-1.316.81-1.439q.024-.008.052-.02l.05-.02c.534-.246.986-.516 1.211-1.078l.082-.194a.264.264 0 0 1 .462-.05c.718 1.05 1.878.147 3.15.147h3.221c.18 0 1.114.102 1.168 1.347l-.11 4.586c-.123 2.804-2.312 4.686-4.985 4.686c-2.672 0-4.862-1.882-4.985-4.686z");
}

.g9arp8b8o {
  d: path("M22.819 8.01h-.713a.49.49 0 0 1-.49-.49V6.49c-.01-.27.21-.49.49-.49h.713c.27 0 .49.22.49.49v1.02c0 .28-.22.5-.49.5");
}

.ghxd2_qoa {
  stop-color: var(--svg-color--be809b, #BE809B);
}

.gst7rh7-l {
  stop-color: var(--svg-color--ce948e, #CE948E);
  stop-opacity: 0;
}

.h_qe7fbbg {
  stop-color: var(--svg-color--744750, #744750);
}

.h-qkfsbcb {
  stop-color: var(--svg-color--cb959c, #CB959C);
  stop-opacity: 0;
}

.hb081ceky {
  stop-color: var(--svg-color--a06f69, #A06F69);
}

.he2vvvbiu {
  fill: var(--svg-color--0d0b10, #0D0B10);
  d: path("m11.335 8.845l-.005.003a.268.268 0 0 1-.275-.46l.001-.001l.003-.002l.01-.006l.032-.018q.041-.023.116-.058a3 3 0 0 1 .41-.162c.34-.109.816-.2 1.329-.11a.268.268 0 0 1-.093.529a2.3 2.3 0 0 0-1.073.092a3 3 0 0 0-.455.193");
}

.hj4mfbctc {
  stop-color: var(--svg-color--e1a7ae, #E1A7AE);
}

.hnxygroex {
  stop-color: var(--svg-color--624b78, #624B78);
  stop-opacity: 0;
}

.hqh-1rbea {
  stop-color: var(--svg-color--f3c29f, #F3C29F);
}

.hzb8dacww {
  stop-color: var(--svg-color--ebb6a1, #EBB6A1);
}

.i05ykabkr {
  stop-color: var(--svg-color--fecdbb, #FECDBB);
}

.id19t5fes {
  stop-color: var(--svg-color--c68b80, #C68B80);
}

.iegtj7has {
  fill: var(--svg-color--0d0b10, #0D0B10);
  fill-rule: evenodd;
  d: path("m18.467 8.388l-.138.23za.268.268 0 0 1-.276.46l-.005-.003a1 1 0 0 0-.113-.058a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.073-.092a.268.268 0 0 1-.093-.528c.513-.091.989 0 1.329.109a3.3 3.3 0 0 1 .559.238l.01.006l.002.002z");
}

.iqc_7zb-q {
  stop-color: var(--svg-color--ce948e, #CE948E);
}

.it1_ig0bc {
  stop-color: var(--svg-color--57525e, #57525E);
}

.iv7bj_baj {
  stop-color: var(--svg-color--4680db, #4680DB);
  stop-opacity: 0;
}

.ixw-oi7aq {
  stop-color: var(--svg-color--3d3248, #3D3248);
}

.iycy_sbnz {
  d: path("M7.366 8.01h-.707a.49.49 0 0 1-.49-.49V6.49c-.01-.27.21-.49.49-.49h.707c.27 0 .49.22.49.49v1.02c0 .28-.22.5-.49.5");
}

.j0xtzac4y {
  stop-color: var(--svg-color--4d79b0, #4D79B0);
  stop-opacity: 0;
}

.j1qr75obr {
  stop-color: var(--svg-color--d8a696, #D8A696);
}

.j23wz_bzl {
  stop-color: var(--svg-color--c68883, #C68883);
}

.j3h4o1d7b {
  stop-color: var(--svg-color--391f48, #391F48);
}

.jase_0f7h {
  stop-color: var(--svg-color--88014e, #88014E);
}

.javsik_yi {
  fill: var(--svg-color--f3d8ed, #F3D8ED);
  d: path("m15.659 19.69l-.65.58c-.16.14-.39.14-.55 0l-.65-.58a3.45 3.45 0 0 1-1.14-2.55v-3.09a2.07 2.07 0 0 1 2.07-2.05c1.14 0 2.06.92 2.06 2.06v3.09c-.01.97-.42 1.89-1.14 2.54");
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jsbk_hbmd {
  stop-color: var(--svg-color--3e80ff, #3E80FF);
}

.jt6x1fb4w {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.335 13.148a.205.205 0 0 0-.248.043a.196.196 0 0 0-.02.248a1.983 1.983 0 0 0 3.334 0a.2.2 0 0 0-.021-.25a.205.205 0 0 0-.247-.041a3 3 0 0 1-1.4.339c-.512 0-.994-.124-1.398-.34Z");
}

.jv7e0m1bl {
  d: path("M12.549 9.55a.893.893 0 0 0-.86 1.127h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.jwg_rcc4c {
  stop-color: var(--svg-color--d7a293, #D7A293);
  stop-opacity: 0;
}

.k1-983bet {
  stop-color: var(--svg-color--8cffff, #8CFFFF);
}

.kc9q3mbff {
  fill: var(--svg-color--c6c6c6, #C6C6C6);
  d: path("m26.449 14.92l-.71-.71l-1.42 1.42c-.38.38-.59.89-.59 1.42v5.54h1v-5.74c0-.14.05-.27.15-.37z");
}

.kgfm32btz {
  stop-color: var(--svg-color--bd7c86, #BD7C86);
}

.knosl_37y {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.126 9.278c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.232a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.372-1.128");
}

.ky_dg6bhp {
  stop-color: var(--svg-color--b0b0b0, #B0B0B0);
}

.l8p6brbrs {
  stop-color: var(--svg-color--38234f, #38234F);
}

.l8qslmb5u {
  d: path("M14.734 13.537a3 3 0 0 1-1.422-.345c-.141-.073-.292.089-.204.22a1.933 1.933 0 0 0 3.251 0c.089-.136-.062-.293-.203-.22c-.412.22-.896.345-1.422.345");
}

.ldqge0b0v {
  stop-color: var(--svg-color--c08666, #C08666);
  stop-opacity: 0;
}

.lf2lmgb_v {
  stop-color: var(--svg-color--9e6261, #9E6261);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkgfrvbcs {
  d: path("M16.852 9.738c.064.085-.069.189-.22.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.05");
}

.lo1ogpbbw {
  stop-color: var(--svg-color--391f48, #391F48);
  stop-opacity: 0;
}

.lt_b3wboz {
  d: path("m3.769 30l4-.02l-.06-11.94a11 11 0 0 0-3.563 5.482c-.262.948-.4 1.947-.397 2.978z");
}

.ltwsa8bld {
  d: path("M7.757 10.031c.21-.47 1.98-4.06 7.03-4.06c5.6 0 7.04 4.06 7.04 4.06h.47c.27 0 .48-.22.48-.48v-3.24c0-2.36-1.91-4.27-4.27-4.27h-7.45a4.253 4.253 0 0 0-4.27 4.26v3.24c0 .27.21.49.48.49z");
}

.m1_q07_me {
  stop-color: var(--svg-color--6899f0, #6899F0);
}

.m3dxw5b4u {
  d: path("M10.812 16.221v4.63c-.002.26.024.579.25.72c.234.144.581-.019.743-.141l2.5-1.766v-4.156a11 11 0 0 0-3.493.713");
}

.m4mhe8bqv {
  stop-color: var(--svg-color--4f94d3, #4F94D3);
  stop-opacity: 0;
}

.m8_l30tsr {
  stop-color: var(--svg-color--2a3765, #2A3765);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mguibccfx {
  stop-color: var(--svg-color--2a193d, #2A193D);
}

.mx797o4di {
  stop-color: var(--svg-color--4086f6, #4086F6);
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.na59ribzw {
  d: path("M28.245 13.16c.081-.326-.151-.554-.478-.472c-.878.18-2.296.406-2.714.954c-.571.613-.55 1.582.03 2.184a1.577 1.577 0 0 0 2.256.01c.503-.512.733-1.836.906-2.676");
}

.ngwa02-tu {
  fill: var(--svg-color--000, #000);
  d: path("M16.407 10.442a.51.51 0 0 1 .512-.511a.51.51 0 0 1 .454.747h-.905a.46.46 0 0 1-.06-.236");
}

.nzjwoybta {
  stop-color: var(--svg-color--675878, #675878);
  stop-opacity: 0;
}

.o12zmvuzn {
  d: path("M20.756 7.641a7.5 7.5 0 0 0-2.31-1.49c-1.09-.45-2.32-.68-3.66-.68c-1.22 0-2.36.2-3.38.6c-.84.33-1.61.79-2.28 1.38c-1.16 1-1.69 2.07-1.83 2.37c-.03.07-.04.14-.04.21h.5c.21-.47 1.98-4.06 7.03-4.06c5.6 0 7.04 4.06 7.04 4.06h.5c0-.06-.01-.11-.03-.17c-.01-.05-.41-1.14-1.54-2.22");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojb-ttbmo {
  fill: var(--svg-color--c4ffff, #C4FFFF);
  d: path("M10.299 4.37h8.87c.31 0 .56-.25.56-.56V2.19c-.4-.12-.83-.19-1.27-.19h-7.45c-.44 0-.87.07-1.27.19v1.62c0 .31.25.56.56.56");
}

.oool1tdti {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M22.748 28.611h1.797");
}

.ott3_jqut {
  stop-color: var(--svg-color--534065, #534065);
}

.p3_97vb4n {
  stop-color: var(--svg-color--465e8a, #465E8A);
  stop-opacity: 0;
}

.p64oiyb7x {
  stop-color: var(--svg-color--55406a, #55406A);
}

.p7prpqhjw {
  stop-color: var(--svg-color--5da7f2, #5DA7F2);
}

.pdra6ipeg {
  d: path("M17.713 10.324a.84.84 0 0 0-.23-.462l-.26.285l.117.228z");
}

.pf-t-gb_g {
  stop-color: var(--svg-color--b87885, #B87885);
}

.ph46gxbvy {
  stop-color: var(--svg-color--4f8dd8, #4F8DD8);
}

.pi6c47yng {
  d: path("M21.729 18.01v11.98h3a1 1 0 0 0 1-1v-2.5c0-3.41-1.55-6.46-4-8.48");
}

.pjsi77bhr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M22.67 27.307h1.797");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmikb6mtj {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M13.591 10.055c-.265-.467-.669-.836-1.538-.836c-.38 0-.747.105-1.073.369c-.269.217-.233.495-.024.6l.556.317c.652-.211 1.373-.24 2.08-.45");
}

.po8erdb9o {
  stop-color: var(--svg-color--c0867c, #C0867C);
}

.q0q7pnllq {
  stop-color: var(--svg-color--ebb7aa, #EBB7AA);
  stop-opacity: 0;
}

.q7l79-2rh {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
}

.q8-xadb4t {
  stop-color: var(--svg-color--b87885, #B87885);
  stop-opacity: 0;
}

.qawbbbcem {
  stop-color: var(--svg-color--bd7c86, #BD7C86);
  stop-opacity: 0;
}

.qgmif2bih {
  stop-color: var(--svg-color--57525e, #57525E);
  stop-opacity: 0;
}

.qjc1qgb0d {
  fill: var(--svg-color--000, #000);
  d: path("M13.06 10.442a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.747H13a.5.5 0 0 0 .061-.236");
}

.qo28zhh9b {
  stop-color: var(--svg-color--3a2252, #3A2252);
}

.qtzewq2gr {
  d: path("M22.13 25.326c0-.402.326-.732.727-.732h2.392a1.2 1.2 0 0 1 1.2 1.2V29a1 1 0 0 1-1 1h-2.592a.731.731 0 0 1-.319-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.qv8wc6zla {
  d: path("m26.449 14.92l-.71-.71l-1.42 1.42c-.38.38-.59.89-.59 1.42v5.54h1v-5.74c0-.14.05-.27.15-.37z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwfi8obtf {
  stop-color: var(--svg-color--b0b0b0, #B0B0B0);
  stop-opacity: 0;
}

.qyg3b1b6n {
  stop-color: var(--svg-color--6f5b84, #6F5B84);
}

.r0p9vfbnw {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
  stop-opacity: 0;
}

.r5fk93cur {
  stop-color: var(--svg-color--2869c1, #2869C1);
}

.rb6ci4jgt {
  stroke: var(--svg-color--252325, #252325);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.882 8.25c-.323-.078-1.125-.039-1.662.345");
}

.rknqf7fgs {
  fill-rule: evenodd;
  d: path("M22.037 12.228a3.25 3.25 0 0 0 .324-1.427a3.3 3.3 0 0 0-.269-1.306h.005a3 3 0 0 0-.28-.514l-.003-.003a3.24 3.24 0 0 1-.526-1.771v-.01a3.3 3.3 0 0 0-3.3-3.3a.54.54 0 0 1-.456-.234a3.3 3.3 0 0 0-2.683-1.377a3.3 3.3 0 0 0-2.683 1.377a.56.56 0 0 1-.456.233l-.085.001a3.3 3.3 0 0 0-3.215 3.3v.01a3.24 3.24 0 0 1-.527 1.771l-.002.004a3.3 3.3 0 0 0-.22 3.246c.07.142.07.314 0 .456a3.215 3.215 0 0 0 2.895 4.627h8.585a3.215 3.215 0 0 0 3.22-3.22c0-.506-.122-.982-.324-1.407a.52.52 0 0 1 0-.456M10.979 9.555h-.012l-.008 2.356c.123 2.804 1.217 0 3.89 0s3.837 3.12 3.96.317l-.481-3.245c-.054-1.245.662-1.286.482-1.286h-3.221a3.86 3.86 0 0 1-3.191-1.674a.264.264 0 0 0-.462.051l-.082.194c-.225.561.551.99.018 1.235l-.052.02q-.028.013-.05.02c-.237.123-.79.49-.811 1.44l.01.306z");
}

.rq76sybla {
  d: path("M18.804 16.276v4.576c.003.26-.023.578-.25.718c-.233.145-.58-.018-.742-.14l-2.5-1.766v-4.15c1.228.064 2.403.329 3.492.762");
}

.rtj8_6bqg {
  stop-color: var(--svg-color--2a3765, #2A3765);
}

.rxmjvacge {
  d: path("M13.364 10.337c0-.288-.235-.48-.298-.539l-.288.28l.177.36z");
}

.s0ihitbab {
  stop-color: var(--svg-color--3f3531, #3F3531);
}

.s1a8ycb7r {
  stop-color: var(--svg-color--362d41, #362D41);
}

.s1rw4px-b {
  stop-color: var(--svg-color--465e8a, #465E8A);
}

.s21zh4b3w {
  stop-color: var(--svg-color--3d78d0, #3D78D0);
  stop-opacity: 0;
}

.s3p5lff5x {
  d: path("M16.919 9.55a.893.893 0 0 1 .86 1.127h-1.725a.896.896 0 0 1 .864-1.128");
}

.s5pm96b_v {
  stop-color: var(--svg-color--3578e5, #3578E5);
  stop-opacity: 0;
}

.sb1phf9zd {
  d: path("M20.979 4.68H8.719v2.65h12.26z");
}

.sbugs4b_s {
  stop-color: var(--svg-color--f2c49e, #F2C49E);
  stop-opacity: 0;
}

.sq-bwm1qa {
  stop-color: var(--svg-color--1f54c5, #1F54C5);
}

.t8ye-ilvp {
  stop-color: var(--svg-color--7b51c6, #7B51C6);
}

.te5b1ia_g {
  stop-color: var(--svg-color--af7e80, #AF7E80);
  stop-opacity: 0;
}

.tgqsm4b7j {
  stop-color: var(--svg-color--5cd3e2, #5CD3E2);
}

.tizux9w7p {
  stop-color: var(--svg-color--3877cc, #3877CC);
  stop-opacity: 0;
}

.tj2vllbvr {
  stop-color: var(--svg-color--f3c6af, #F3C6AF);
}

.troaenb0e {
  stop-color: var(--svg-color--428ef7, #428EF7);
}

.tti66ybyp {
  stop-color: var(--svg-color--cd9a88, #CD9A88);
}

.u-q3e7b8s {
  d: path("m15.659 19.69l-.65.58c-.16.14-.39.14-.55 0l-.65-.58a3.45 3.45 0 0 1-1.14-2.55v-3.09a2.07 2.07 0 0 1 2.07-2.05c1.14 0 2.06.92 2.06 2.06v3.09c-.01.97-.42 1.89-1.14 2.54");
}

.u9ri-jbkw {
  stop-color: var(--svg-color--547eb3, #547EB3);
}

.ue1gv6enh {
  d: path("M25.259 25.94h-2.05v-3c0-.19.16-.35.35-.35h1.35c.19 0 .35.16.35.35z");
}

.ugclr1_ae {
  stop-color: var(--svg-color--d6aaa1, #D6AAA1);
}

.uxfooubcv {
  stop-color: var(--svg-color--ae7759, #AE7759);
}

.uzac_3qef {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
}

.v-p3thbyp {
  cx: 12.279px;
  cy: 9.931px;
  rx: 0.389px;
  ry: 0.197px;
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.v6_fcq9so {
  cx: 12.279px;
  cy: 9.931px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.v70cngc9z {
  fill: var(--svg-color--c28572, #C28572);
  d: path("m14.341 10.401l-.684 1.7a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.494-.377-.613 0");
}

.v9wc5kdsn {
  d: path("M10.066 11.698a1.075 1.075 0 1 0 0-2.149a1.075 1.075 0 0 0 0 2.15");
}

.vaw3c9xmk {
  stop-color: var(--svg-color--cf9393, #CF9393);
}

.vbc9nqbss {
  fill: var(--svg-color--1e64bd, #1E64BD);
  d: path("M21.729 18.01v11.98h3a1 1 0 0 0 1-1v-2.5c0-3.41-1.55-6.46-4-8.48");
}

.vczswwwcd {
  fill: var(--svg-color--fff, #fff);
  d: path("M26.151 15.597a.85.85 0 1 0 0-1.7a.85.85 0 0 0 0 1.7");
}

.veu345b3w {
  stop-color: var(--svg-color--c69693, #C69693);
  stop-opacity: 0;
}

.vx-77wbda {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
}

.vxca8ab-k {
  d: path("m14.351 10.263l-.532 1.7a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.377-.646-.377-.766 0");
}

.w5wbm7itt {
  stop-color: var(--svg-color--170f1e, #170F1E);
}

.w60oimv2y {
  stop-color: var(--svg-color--ac747d, #AC747D);
  stop-opacity: 0;
}

.wg_w1vbgj {
  d: path("M19.563 11.698a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.15");
}

.wp6rq3sqk {
  stop-color: var(--svg-color--6e5981, #6E5981);
}

.x9-b3hbfy {
  fill: var(--svg-color--1e6dc3, #1E6DC3);
  d: path("M18.365 16.768v4.575c.002.26-.024.578-.25.719c-.234.145-.581-.018-.743-.14l-2.5-1.766v-4.15c1.229.064 2.403.328 3.492.762");
}

.xng4o8biy {
  stop-color: var(--svg-color--7e514e, #7E514E);
}

.y66dh_b5l {
  stop-color: var(--svg-color--675878, #675878);
}

.y8uqe7b6k {
  stop-color: var(--svg-color--3f3531, #3F3531);
  stop-opacity: 0;
}

.y9d5neb6h {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.342 9.278c-.654 0-1.206.45-1.356 1.059c-.044.174.09.34.268.34h2.232a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.yd1ogmbpn {
  stop-color: var(--svg-color--b67b6f, #B67B6F);
}

.yd41utmlw {
  stop-color: var(--svg-color--32263f, #32263F);
}

.yhi4l7bah {
  stop-color: var(--svg-color--f8c8ad, #F8C8AD);
}

.yhrc8s1zu {
  stop-color: var(--svg-color--31263f, #31263F);
}

.yjsg34f1d {
  stroke: var(--svg-color--252325, #252325);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.674 8.25c.323-.078 1.125-.039 1.661.345");
}

.ypv_kpaja {
  stop-color: var(--svg-color--4680db, #4680DB);
}

.yytwt1d8s {
  stop-color: var(--svg-color--362d41, #362D41);
  stop-opacity: 0;
}

.z2rllvutr {
  stop-color: var(--svg-color--8c68d5, #8C68D5);
}

.zn-qjxbde {
  stop-color: var(--svg-color--86004d, #86004D);
}

</style>
