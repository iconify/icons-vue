<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#izwrvUb)" class="nkunvgnhz"/><path fill="url(#i1JcZue)" class="ibh3944it"/><g filter="url(#iD7ZTiv)"><path fill="url(#iIouSEb)" class="brcjs0b9g"/><path fill="url(#iGIYfIe)" class="brcjs0b9g"/></g><path fill="url(#imyZpIJ)" class="brcjs0b9g"/><path fill="url(#i2BxFxe)" class="brcjs0b9g"/><path fill="url(#i4oky5b)" class="brcjs0b9g"/><path fill="url(#iKMBlRd)" class="brcjs0b9g"/><path fill="url(#ib86Yfd)" class="brcjs0b9g"/><path fill="url(#iPC23Ac)" class="brcjs0b9g"/><path fill="url(#iyisKmd)" class="brcjs0b9g"/><g filter="url(#i2WCyZo)"><path class="kzmnfq74k"/></g><g filter="url(#iZ5lrSc)"><path class="g3bvhtblg"/><path fill="url(#ifKTdIc)" class="mep5-xbda"/><path fill="url(#iFLbT0c)" class="mep5-xbda"/><path fill="url(#ieHVO6b)" class="mep5-xbda"/><path fill="url(#ivr7Ule)" class="mep5-xbda"/><path fill="url(#iZTgRZb)" class="mep5-xbda"/></g><path fill="url(#igeYFyc)" class="mep5-xbda"/><path fill="url(#i0wZmJc)" class="mep5-xbda"/><g filter="url(#io4VHuv)"><path stroke="url(#iP2wcjd)" class="br7q4abvp"/></g><path fill="url(#iBhdLpe)" class="sj2-0xb5m"/><g filter="url(#ivH6j7d)"><path fill="url(#iISjWud)" class="j8i-kcehm"/><path fill="url(#iL5Eb9d)" class="j8i-kcehm"/><path fill="url(#iArvIid)" class="j8i-kcehm"/><path fill="url(#i73lHGt)" class="j8i-kcehm"/><path fill="url(#iIREnQc)" class="j8i-kcehm"/></g><g filter="url(#ivMjPke)"><path class="ffrbmwtyr"/></g><g filter="url(#idX0Tjd)"><path class="mqvf3mbmj"/></g><g filter="url(#iHpqDZb)"><path class="x7a6zj28d"/><path fill="url(#itU6i5o)" class="gxy7mlbgt"/><path fill="url(#ieWgsbK)" class="gxy7mlbgt"/></g><g filter="url(#i1g3U9b)"><path class="gfdd_ybox"/><path fill="url(#i0h1rAd)" class="ffnuo2k7t"/><path fill="url(#iTcwehb)" class="ffnuo2k7t"/><path fill="url(#ikW69Ey)" class="ffnuo2k7t"/></g><path class="g1azyqb3t"/><path fill="url(#ijXeqce)" class="x5-jv6b5j"/><path class="lfy8o1f3s"/><g filter="url(#izxkOeO)"><path class="f7aosn70g"/><path fill="url(#izlWgXc)" class="ae03yabng"/></g><g filter="url(#i2pjBJc)"><path fill="url(#iy2qT8M)" class="lkluesb3l"/></g><path class="pqv0w15we"/><path fill="url(#iQkR8Yc)" class="fycqq9bby"/><path class="r-07d-v7y"/><g filter="url(#iJk17Kc)"><path fill="url(#i4SOZHx)" class="w05v7abvv"/></g><g filter="url(#iEZVPxx)"><ellipse transform="rotate(-27.914 11.338 16.474)" class="m9vn0lkvn"/><ellipse fill="url(#i8WnJGt)" transform="rotate(-27.914 11.338 16.474)" class="inuvwbg4d"/></g><path fill="url(#i0Kr8oc)" class="uyeawsbmr"/><path fill="url(#i2LlBub)" class="uyeawsbmr"/><path fill="url(#imlVeoU)" class="uyeawsbmr"/><path fill="url(#icB4Abd)" class="uyeawsbmr"/><path fill="url(#iNiaaib)" class="vyx15snot"/><path fill="url(#io3Jcbe)" class="vyx15snot"/><g filter="url(#itliOqd)"><path fill="url(#irnZDTb)" class="q64xq4lpt"/></g><g filter="url(#iJkKBJb)"><path fill="url(#ijj5RVb)" class="girpf6bgt"/></g><g filter="url(#ifkZzqd)"><path class="da-i9vbqx"/></g><g filter="url(#i21o2ee)"><path class="cjj30yhpp"/></g><defs><radialGradient id="izwrvUb" cx="0" cy="0" r="1" gradientTransform="matrix(1.39603 3.76525 -4.47282 1.65837 24.775 20.116)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="i1JcZue" cx="0" cy="0" r="1" gradientTransform="matrix(2.75273 .86514 -2.66903 8.49237 4.62 21.03)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="iIouSEb" cx="0" cy="0" r="1" gradientTransform="matrix(-9.74687 0 0 -17.2421 21.147 18.361)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="iGIYfIe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.24997 5.37502 -4.43752 -2.68312 20.438 9.078)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="i2BxFxe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.90593 23.16252 -19.18137 -1.57834 18.86 7.336)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="axnqidyuu"/><stop offset="1" class="j7pnfkbxw"/></radialGradient><radialGradient id="i4oky5b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.141 2.64949 0 20.475 15.913)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="iKMBlRd" cx="0" cy="0" r="1" gradientTransform="matrix(.00733 -2.04019 2.2202 .00797 11.624 16)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="ib86Yfd" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 10.838 10.453)scale(15.8715 40.5438)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="iPC23Ac" cx="0" cy="0" r="1" gradientTransform="matrix(6.3125 -5.4375 1.60615 1.8646 3.25 13.266)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="iyisKmd" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 4.65625 -1.8613 -.17489 26.25 12.922)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="iFLbT0c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4551 -1.43034 0 16.782 20.898)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="ivr7Ule" cx="0" cy="0" r="1" gradientTransform="rotate(155.369 6.334 11.773)scale(3.11992 5.01397)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="i0wZmJc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.39062 2.28126 -3.2924 -3.45025 16.719 19.297)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="p1yo_4s7a"/><stop offset="1" class="a1wau6blr"/></radialGradient><radialGradient id="iBhdLpe" cx="0" cy="0" r="1" gradientTransform="matrix(4.06811 -2 8.04654 16.36708 14.997 25.116)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iL5Eb9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.52791 16.5083 0 6.162 12.969)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iArvIid" cx="0" cy="0" r="1" gradientTransform="rotate(-87.401 20.55 -5.361)scale(4.68924 8.30841)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="i73lHGt" cx="0" cy="0" r="1" gradientTransform="rotate(-146.667 12.34 -1.673)scale(5.26377 3.86388)" gradientUnits="userSpaceOnUse"><stop class="jx9hffbwe"/><stop offset="1" class="mzj8iibqz"/></radialGradient><radialGradient id="iIREnQc" cx="0" cy="0" r="1" gradientTransform="matrix(1.68751 2.75 -6.3677 3.90748 14.225 .741)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="itU6i5o" cx="0" cy="0" r="1" gradientTransform="matrix(-4.10381 0 0 -1.52308 16.385 4.953)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="ieWgsbK" cx="0" cy="0" r="1" gradientTransform="matrix(6 -9.5 10.52499 6.64735 5.787 12.303)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="i0h1rAd" cx="0" cy="0" r="1" gradientTransform="matrix(5.70209 0 0 2.22942 22.277 6.401)" gradientUnits="userSpaceOnUse"><stop class="nszf4yi9c"/><stop offset="1" class="a061yvbds"/></radialGradient><radialGradient id="iTcwehb" cx="0" cy="0" r="1" gradientTransform="rotate(-43.614 25.487 -19.989)scale(6.89811 12.6287)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="ikW69Ey" cx="0" cy="0" r="1" gradientTransform="rotate(6.667 -70.35 169.23)scale(6.09724 2.5528)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="ijXeqce" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.40601 0 19.98 16.653)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="izlWgXc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 13.894 3.616)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iQkR8Yc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51271 -2.40614 0 11.844 16.653)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i8WnJGt" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.053 2.963)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i2LlBub" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 1.264 24.508)scale(4.34346 4.144)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="imlVeoU" cx="0" cy="0" r="1" gradientTransform="matrix(1.46875 -2.01563 1.6895 1.2311 25.194 17.694)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="icB4Abd" cx="0" cy="0" r="1" gradientTransform="matrix(1.0944 -2.89062 3.86227 1.46228 25.406 18.016)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="io3Jcbe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.09167 0 0 -3.45229 6.748 17.874)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="irnZDTb" cx="0" cy="0" r="1" gradientTransform="rotate(170.26 2.613 9.227)scale(1.73369 1.77757)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><filter id="iD7ZTiv" width="20.055" height="23.21" x="6.472" y="6.856" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2009"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3930_2009" result="effect2_innerShadow_3930_2009"/></filter><filter id="i2WCyZo" width="5.257" height="7.407" x="13.019" y="15.824" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2009" stdDeviation=".5"/></filter><filter id="iZ5lrSc" width="3.9" height="5.807" x="13.962" y="16.259" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2009" stdDeviation=".1"/></filter><filter id="io4VHuv" width="6.5" height="2.5" x="12.662" y="22.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2009" stdDeviation=".05"/></filter><filter id="ivH6j7d" width="24" height="15.148" x="3.912" y="1.366" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2009"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3930_2009" result="effect2_innerShadow_3930_2009"/></filter><filter id="ivMjPke" width="4.274" height="2.047" x="18.875" y="11.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2009"/></filter><filter id="idX0Tjd" width="4.274" height="2.019" x="9.075" y="11.694" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2009"/></filter><filter id="iHpqDZb" width="12.344" height="11.239" x="4.541" y="2.93" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2009"/><feGaussianBlur result="effect2_foregroundBlur_3930_2009" stdDeviation=".25"/></filter><filter id="i1g3U9b" width="12.094" height="10.965" x="15.417" y="3.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2009" stdDeviation=".25"/></filter><filter id="izxkOeO" width="1.294" height="1.125" x="18.698" y="15.919" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2009" stdDeviation=".05"/></filter><filter id="i2pjBJc" width="1.316" height="1.357" x="20.351" y="16.146" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2009" stdDeviation=".1"/></filter><filter id="iJk17Kc" width="1.493" height="1.594" x="12.068" y="16.027" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2009" stdDeviation=".1"/></filter><filter id="iEZVPxx" width="1.529" height="1.141" x="10.574" y="15.904" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2009" stdDeviation=".05"/></filter><filter id="itliOqd" width="2.045" height="4.004" x="4.791" y="15.877" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2009" stdDeviation=".125"/></filter><filter id="iJkKBJb" width="2.765" height="4.549" x="24.628" y="15.592" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2009" stdDeviation=".25"/></filter><filter id="ifkZzqd" width="3.836" height="1.515" x="9.248" y="11.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2009" stdDeviation=".125"/></filter><filter id="i21o2ee" width="3.836" height="1.515" x="19.091" y="11.898" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2009" stdDeviation=".125"/></filter><linearGradient id="imyZpIJ" x1="25.527" x2="20.813" y1="21.503" y2="21.503" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="ifKTdIc" x1="17.475" x2="15.912" y1="19.619" y2="19.684" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="ieHVO6b" x1="15.912" x2="15.912" y1="21.743" y2="20.876" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="iZTgRZb" x1="15.912" x2="15.912" y1="16.7" y2="17.719" gradientUnits="userSpaceOnUse"><stop class="fok393bvn"/><stop offset="1" class="y4umwkb_f"/></linearGradient><linearGradient id="igeYFyc" x1="16.688" x2="16.688" y1="22" y2="21.641" gradientUnits="userSpaceOnUse"><stop class="a1wau6blr"/><stop offset="1" class="p1yo_4s7a"/></linearGradient><linearGradient id="iP2wcjd" x1="13.672" x2="14.266" y1="24.672" y2="23.116" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="iISjWud" x1="28.687" x2="7.037" y1="7.804" y2="7.804" gradientUnits="userSpaceOnUse"><stop class="s5pji6bqr"/><stop offset="1" class="c7qpv738k"/></linearGradient><linearGradient id="iy2qT8M" x1="21.431" x2="20.846" y1="16.753" y2="17.114" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i4SOZHx" x1="13.231" x2="12.646" y1="16.753" y2="17.114" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i0Kr8oc" x1="27.912" x2="25.662" y1="16.803" y2="20.861" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="iNiaaib" x1="5.006" x2="7.725" y1="18.116" y2="17.879" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="ijj5RVb" x1="26.011" x2="26.011" y1="16.092" y2="19.64" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-medium-dark" /></template>
<style>
.a061yvbds {
  stop-color: var(--svg-color--4e494b, #4E494B);
  stop-opacity: 0;
}

.a1wau6blr {
  stop-color: var(--svg-color--6d3945, #6D3945);
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.ae03yabng {
  d: path("M19.862 16.115c.119.159-.13.352-.41.563c-.283.21-.492.359-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.252.725-.094");
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.axnqidyuu {
  stop-color: var(--svg-color--804776, #804776);
  stop-opacity: 0;
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.br7q4abvp {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.364 23.083a.36.36 0 0 0-.43.074a.33.33 0 0 0-.036.424a3.6 3.6 0 0 0 3.014 1.61a3.6 3.6 0 0 0 3.015-1.61a.334.334 0 0 0-.037-.428a.36.36 0 0 0-.428-.07h-.001a5.5 5.5 0 0 1-2.549.604c-.934 0-1.812-.22-2.548-.604Z");
}

.brcjs0b9g {
  d: path("M6.917 23.516a7.3 7.3 0 0 0 7.244 6.35h3.518a7.3 7.3 0 0 0 7.244-6.35c.22-3.512.441-7.01.605-10.52c-.02-1.43-1.148-2.61-2.572-2.67h-2.61a4.52 4.52 0 0 1-4.123-2.69a1.24 1.24 0 0 0-1.148-.78h-2.373c-3.441 0-6.23 2.82-6.23 6.3c0 3.47.217 6.882.445 10.36");
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c7qpv738k {
  stop-color: var(--svg-color--362c2e, #362C2E);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.cbylncbjf {
  stop-color: var(--svg-color--332f31, #332F31);
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.cjj30yhpp {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.552 13.038c-.48-.344-1.674-.949-3.086-.711");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.da-i9vbqx {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.623 13.124c.48-.344 1.674-.949 3.086-.711");
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.etju2kb3q {
  stop-color: var(--svg-color--87004e, #87004E);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f7aosn70g {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.862 16.115c.119.159-.13.352-.41.563c-.283.21-.492.359-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.252.725-.094");
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.ffnuo2k7t {
  d: path("m25.63 13.982l-.053-1.177c-.02-1.423-1.197-2.598-2.62-2.658h-2.611a4.51 4.51 0 0 1-3.96-2.348s-.382-.885-.466-2.18c-.065-1 .84-1.718 1.835-1.587c2.066.274 4.934.919 6.905 2.205c3.252 2.121 2.683 5.944.97 7.745");
}

.ffrbmwtyr {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M22.872 12.806c-.327-.285-.706-.586-1.282-.767c-.567-.179-1.277-.227-2.26-.107a.517.517 0 0 0 .125 1.027c.897-.11 1.447-.053 1.825.066c.37.116.62.305.913.56a.517.517 0 0 0 .679-.78");
}

.fok393bvn {
  stop-color: var(--svg-color--865c56, #865C56);
}

.ft5dv1b6b {
  fill: none;
}

.fycqq9bby {
  d: path("M11.84 15.763a1.664 1.664 0 0 0-1.603 2.103h3.214c.038-.144.061-.287.061-.439a1.675 1.675 0 0 0-1.671-1.664");
}

.g1azyqb3t {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.37 15.257c1.218 0 2.246.84 2.526 1.974a.51.51 0 0 1-.499.635h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.556-2.102");
}

.g3bvhtblg {
  fill: var(--svg-color--845b55, #845B55);
  d: path("m15.2 17.029l-.991 3.427c-.202.705.283 1.41.97 1.41h1.466c.688 0 1.173-.716.971-1.41l-.99-3.427c-.213-.76-1.204-.76-1.426 0");
}

.gfdd_ybox {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m25.63 13.982l-.053-1.177c-.02-1.423-1.197-2.598-2.62-2.658h-2.611a4.51 4.51 0 0 1-3.96-2.348s-.382-.885-.466-2.18c-.065-1 .84-1.718 1.835-1.587c2.066.274 4.934.919 6.905 2.205c3.252 2.121 2.683 5.944.97 7.745");
}

.girpf6bgt {
  d: path("M25.128 19.64q.109-1.774.206-3.548a1.782 1.782 0 0 1-.206 3.548");
}

.gxy7mlbgt {
  d: path("M16.346 7.891a5 5 0 0 1-.123-.255a1.24 1.24 0 0 0-1.148-.78h-2.373c-3.441 0-6.23 2.82-6.23 6.3v.513c-.633-.482-1.43-1.5-1.43-3.147c0-1.998 1.457-3.008 2.386-3.652c.263-.182.483-.335.617-.473l.186-.195c.652-.691 1.813-1.923 3.84-2.461c1.299-.345 2.62-.348 3.511-.268c.471.042.803.45.803.923v3.47z");
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hj2nkngkt {
  stop-color: var(--svg-color--221925, #221925);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ibh3944it {
  d: path("M6.849 20.691a3.06 3.06 0 0 1-1.687-.575v1.736c0 1.665.992 3.148 2.5 3.764a7.6 7.6 0 0 1-.644-2.2z");
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.inuvwbg4d {
  cx: 11.338px;
  cy: 16.474px;
  rx: 0.726px;
  ry: 0.368px;
}

.j7pnfkbxw {
  stop-color: var(--svg-color--804776, #804776);
}

.j8i-kcehm {
  d: path("M24.964 5.976c.959.33 1.82 1 2.363 1.96a4.42 4.42 0 0 1-.198 4.71a2.9 2.9 0 0 0-.504 1.63v2.215a3.25 3.25 0 0 0-1.244-.5l.146-2.995c-.02-1.43-1.147-2.61-2.57-2.67h-2.611a4.52 4.52 0 0 1-4.123-2.69a1.24 1.24 0 0 0-1.148-.78h-2.373c-3.441 0-6.23 2.82-6.23 6.3l.058 2.866c-.474.07-.969.228-1.343.492v-2.238c0-.58-.178-1.15-.504-1.63a4.46 4.46 0 0 1-.267-4.56a4.37 4.37 0 0 1 2.422-2.1a5 5 0 0 0 2.581-2.07a4.34 4.34 0 0 1 3.679-2.05c.603 0 1.176.13 1.71.35c.712.31 1.513.31 2.225 0a4.4 4.4 0 0 1 1.701-.35c1.572 0 2.947.85 3.708 2.11c.574.95 1.474 1.64 2.522 2");
}

.jx9hffbwe {
  stop-color: var(--svg-color--402c32, #402C32);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.kzmnfq74k {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.164 17.394l-1.101 3.427c-.189.705.263 1.41.903 1.41h1.364c.64 0 1.091-.716.903-1.41l-.922-3.427c-.198-.76-.94-.76-1.147 0");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lfy8o1f3s {
  fill: var(--svg-color--000, #000);
  d: path("M19.032 17.427c0-.53.423-.953.953-.953c.529 0 .952.424.952.953c0 .16-.037.31-.106.439h-1.686a.86.86 0 0 1-.113-.439");
}

.lg98p_5je {
  stop-color: var(--svg-color--70424e, #70424E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkluesb3l {
  d: path("M21.467 17.208a1.57 1.57 0 0 0-.432-.862l-.484.531l.218.426z");
}

.ln8xouyxx {
  stop-color: var(--svg-color--866163, #866163);
  stop-opacity: 0;
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.m9vn0lkvn {
  cx: 11.338px;
  cy: 16.474px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mep5-xbda {
  d: path("m15.2 17.029l-.991 3.427c-.202.705.283 1.41.97 1.41h1.466c.688 0 1.173-.716.971-1.41l-.99-3.427c-.213-.76-1.204-.76-1.426 0");
}

.mqvf3mbmj {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M9.553 12.602a5.17 5.17 0 0 1 3.242-.67a.517.517 0 0 1-.125 1.027a4.14 4.14 0 0 0-2.586.53a3 3 0 0 0-.17.112l-.006.004a.517.517 0 0 1-.633-.818z");
}

.mzj8iibqz {
  stop-color: var(--svg-color--402c32, #402C32);
  stop-opacity: 0;
}

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.nkunvgnhz {
  d: path("M24.976 20.691a3.06 3.06 0 0 0 1.686-.575v1.736c0 1.665-.992 3.148-2.5 3.764a7.6 7.6 0 0 0 .645-2.2z");
}

.nszf4yi9c {
  stop-color: var(--svg-color--4e494b, #4E494B);
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.p1yo_4s7a {
  stop-color: var(--svg-color--6d3945, #6D3945);
  stop-opacity: 0;
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.pqv0w15we {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.455 15.257c-1.218 0-2.247.84-2.526 1.974a.51.51 0 0 0 .499.635h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.102");
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.q64xq4lpt {
  d: path("M6.431 16.127a1.782 1.782 0 0 0 .156 3.504a142 142 0 0 1-.156-3.504");
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
}

.r-07d-v7y {
  fill: var(--svg-color--000, #000);
  d: path("M12.794 17.427a.95.95 0 0 0-.953-.953a.95.95 0 0 0-.953.953c0 .16.037.31.105.439h1.687a.95.95 0 0 0 .114-.439");
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.s5pji6bqr {
  stop-color: var(--svg-color--443237, #443237);
}

.sf65_-b_u {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.sim-rnb6d {
  stop-color: var(--svg-color--815f58, #815F58);
  stop-opacity: 0;
}

.sj2-0xb5m {
  d: path("M15.912 23.762a5.6 5.6 0 0 1-2.583-.613c-.255-.13-.53.158-.369.39a3.53 3.53 0 0 0 2.952 1.577a3.53 3.53 0 0 0 2.952-1.577c.161-.241-.113-.52-.369-.39a5.6 5.6 0 0 1-2.583.613");
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.t_m5csgaz {
  stop-color: var(--svg-color--866163, #866163);
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.uyeawsbmr {
  d: path("M25.089 20.86q.186-2.974.344-5.949a3 3 0 0 1-.344 5.95");
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.vyx15snot {
  d: path("M6.508 14.887a3.025 3.025 0 0 0-2.596 2.979a3 3 0 0 0 2.836 2.996q-.181-2.987-.24-5.975");
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w05v7abvv {
  d: path("M13.36 17.232c0-.538-.437-.896-.555-1.005l-.537.52l.33.674z");
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.x5-jv6b5j {
  d: path("M19.985 15.764a1.664 1.664 0 0 1 1.603 2.102h-3.215a1.7 1.7 0 0 1-.06-.439a1.67 1.67 0 0 1 1.672-1.663");
}

.x7a6zj28d {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("M16.346 7.891a5 5 0 0 1-.123-.255a1.24 1.24 0 0 0-1.148-.78h-2.373c-3.441 0-6.23 2.82-6.23 6.3v.513c-.633-.482-1.43-1.5-1.43-3.147c0-1.998 1.457-3.008 2.386-3.652c.263-.182.483-.335.617-.473l.186-.195c.652-.691 1.813-1.923 3.84-2.461c1.299-.345 2.62-.348 3.511-.268c.471.042.803.45.803.923v3.47z");
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.y4umwkb_f {
  stop-color: var(--svg-color--865c56, #865C56);
  stop-opacity: 0;
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

</style>
