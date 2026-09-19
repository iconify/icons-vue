<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iqLprqc)"><circle fill="url(#izAc0cd)" class="uggh96bfb"/></g><g filter="url(#ic6OKgb)"><circle fill="url(#ii79p7L)" class="o_drskb5d"/></g><g filter="url(#iYNsLeo)"><circle fill="url(#iZLVUgW)" class="l380b9bcr"/><circle fill="url(#ih93jKg)" class="l380b9bcr"/></g><g filter="url(#iODeYGd)"><circle class="pko800b2f"/><circle fill="url(#igRqz7d)" class="v4djr4bzy"/><circle fill="url(#ijF64Wc)" class="v4djr4bzy"/></g><g filter="url(#ikIXerb)"><path fill="url(#i2w1i1V)" class="bppy92r3u"/><path fill="url(#iqHdIEb)" class="bppy92r3u"/><path fill="url(#i1vQwDb)" class="bppy92r3u"/><path fill="url(#iLBB1hd)" class="bppy92r3u"/><path fill="url(#i0VlwKd)" class="bppy92r3u"/></g><g filter="url(#inzuCXd)"><path fill="url(#isFAhEb)" class="anj76nhkr"/></g><g filter="url(#imiuegc)"><path class="ekazbbcvj"/><path fill="url(#isQMyke)" class="po_nc8bzh"/><path fill="url(#ifLAbsb)" class="po_nc8bzh"/><path fill="url(#i4mDvEb)" class="po_nc8bzh"/><path fill="url(#izikOKd)" class="po_nc8bzh"/></g><g filter="url(#iCQb6jd)"><path class="v8iqyzpqo"/></g><g filter="url(#iuHSTSZ)"><path class="o3mf9zbxg"/><path fill="url(#ixVyvDb)" class="ye0wtbymj"/><path fill="url(#iKMzpBb)" class="ye0wtbymj"/><path fill="url(#ifJgsfY)" class="ye0wtbymj"/><path fill="url(#iqyjuwb)" class="ye0wtbymj"/></g><path fill="url(#irtw8Rd)" class="ye0wtbymj"/><path stroke="url(#iy7aq0b)" class="jfozcpb8o"/><g filter="url(#iKbr7yc)"><path class="xyza8fboq"/></g><g filter="url(#iUqs73d)"><path class="c5fcuybyq"/></g><path class="akoqlejsh"/><path fill="url(#iJDjoQd)" class="ryb9ksbwy"/><path class="rs4yt5byt"/><g filter="url(#iZGPTKd)"><path class="br836wbnd"/><path fill="url(#iF4wo7b)" class="u5mf6ccuk"/></g><g filter="url(#iUYSGLc)"><path fill="url(#i2rqafc)" class="zoxn06blq"/></g><path class="yau6hdc7q"/><path fill="url(#iIQEk0b)" class="q5pd5ob4x"/><path class="ilts2c-ja"/><g filter="url(#ieCQTFe)"><path fill="url(#iuoJadd)" class="j4owdlb_o"/></g><g filter="url(#iMqdiJe)"><ellipse transform="rotate(-27.914 11.367 17.108)" class="vl9ydvbeb"/><ellipse fill="url(#i5cVaRc)" transform="rotate(-27.914 11.367 17.108)" class="boi6jzbkr"/></g><g filter="url(#iwt7Nsb)"><path stroke="url(#iQcHjiG)" class="kg9_cdcna"/></g><g filter="url(#ij7vILd)"><path stroke="url(#iG4hVNd)" class="x8vxh860r"/></g><g filter="url(#iKFDZte)"><path stroke="url(#iaBMVod)" class="k4bv00_-r"/></g><g filter="url(#iMkdMoc)"><path fill="url(#iEq6RCb)" class="ve9quacpk"/></g><path fill="url(#iZiu8Dc)" class="ve9quacpk"/><path fill="url(#iKvbfwc)" class="ve9quacpk"/><defs><filter id="iqLprqc" width="6.427" height="6.227" x="3.979" y="15.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19839"/></filter><filter id="ic6OKgb" width="4.711" height="4.711" x="4.737" y="16.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19839" stdDeviation=".25"/></filter><filter id="iYNsLeo" width="6.477" height="6.477" x="21.72" y="15.195" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19839"/></filter><filter id="iODeYGd" width="4.711" height="4.711" x="22.478" y="16.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19839" stdDeviation=".25"/></filter><filter id="ikIXerb" width="19.345" height="22.68" x="6.327" y="8.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19839"/></filter><filter id="inzuCXd" width="11.918" height="9.719" x="14.263" y="6.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19839" stdDeviation="1"/></filter><filter id="imiuegc" width="23.5" height="15.5" x="4.196" y="2.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19839"/></filter><filter id="iCQb6jd" width="4.782" height="6.5" x="13.11" y="17.054" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19839" stdDeviation=".375"/></filter><filter id="iuHSTSZ" width="4" height="5.5" x="13.946" y="17.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19839" stdDeviation=".125"/></filter><filter id="iKbr7yc" width="5.34" height="3.147" x="18.151" y="12.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19839"/></filter><filter id="iUqs73d" width="5.341" height="3.147" x="8.551" y="12.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19839"/></filter><filter id="iZGPTKd" width="1.294" height="1.125" x="18.727" y="16.553" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19839" stdDeviation=".05"/></filter><filter id="iUYSGLc" width="1.316" height="1.357" x="20.38" y="16.779" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19839" stdDeviation=".1"/></filter><filter id="ieCQTFe" width="1.493" height="1.594" x="12.097" y="16.661" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19839" stdDeviation=".1"/></filter><filter id="iMqdiJe" width="1.529" height="1.141" x="10.603" y="16.538" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19839" stdDeviation=".05"/></filter><filter id="iwt7Nsb" width="4.949" height="2.304" x="18.293" y="12.405" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19839" stdDeviation=".25"/></filter><filter id="ij7vILd" width="5.094" height="2.41" x="8.56" y="12.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19839" stdDeviation=".25"/></filter><filter id="iKFDZte" width="1.231" height="3.583" x="6.637" y="9.211" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19839" stdDeviation=".125"/></filter><filter id="iMkdMoc" width="20.086" height="16.516" x="5.936" y="14.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.235294 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19839"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.290196 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_19839" result="effect2_innerShadow_3987_19839"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".35"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0509804 0 0 0 0 0.0196078 0 0 0 0 0.0235294 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_3987_19839" result="effect3_innerShadow_3987_19839"/></filter><radialGradient id="izAc0cd" cx="0" cy="0" r="1" gradientTransform="matrix(3.27255 0 0 5.72699 3.979 18.559)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="ih93jKg" cx="0" cy="0" r="1" gradientTransform="matrix(1.54168 -1.12256 1.28126 1.75963 25.527 18.064)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="igRqz7d" cx="0" cy="0" r="1" gradientTransform="matrix(1.53153 -2.8169 1.64874 .8964 24.756 20.09)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="ijF64Wc" cx="0" cy="0" r="1" gradientTransform="rotate(44.708 -10.148 39.473)scale(.68036 .87707)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="iqHdIEb" cx="0" cy="0" r="1" gradientTransform="rotate(100.62 2.577 15.227)scale(15.2614 20.7165)" gradientUnits="userSpaceOnUse"><stop offset=".746" class="za_-d8ldm"/><stop offset="1" class="z0cx0-b2p"/></radialGradient><radialGradient id="iLBB1hd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.4375 3 0 20.321 16.188)" gradientUnits="userSpaceOnUse"><stop class="m459pab_j"/><stop offset="1" class="rcuz4uefu"/></radialGradient><radialGradient id="i0VlwKd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.59375 3.22556 0 11.821 16.125)" gradientUnits="userSpaceOnUse"><stop class="hplqxft1w"/><stop offset="1" class="ay1rn8bxh"/></radialGradient><radialGradient id="isQMyke" cx="0" cy="0" r="1" gradientTransform="matrix(1.4878 -5.51363 2.04463 .55172 24.05 10.9)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="ifLAbsb" cx="0" cy="0" r="1" gradientTransform="matrix(7.13272 .65639 -.35293 3.83521 20.986 7.62)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="i4mDvEb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.1314 -4.84965 0 15.946 2.519)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="izikOKd" cx="0" cy="0" r="1" gradientTransform="rotate(-36.235 25.239 1.626)scale(7.1069 11.1342)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="iqyjuwb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36719 -1.17969 0 16.556 21.555)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="iJDjoQd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.40601 0 20.01 17.287)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iF4wo7b" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 14.064 3.926)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iIQEk0b" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51271 -2.40614 0 11.873 17.287)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i5cVaRc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.38 3.266)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iKvbfwc" cx="0" cy="0" r="1" gradientTransform="matrix(10.88217 13.48113 -18.75991 15.14329 12.136 15.997)" gradientUnits="userSpaceOnUse"><stop offset=".901" class="nv4ngd99r"/><stop offset="1" class="iwvz51btf"/></radialGradient><linearGradient id="ii79p7L" x1="7.092" x2="5.898" y1="19.078" y2="19.078" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="iZLVUgW" x1="26.859" x2="25.332" y1="16.523" y2="21.253" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="i2w1i1V" x1="23.473" x2="9.231" y1="19.285" y2="21.407" gradientUnits="userSpaceOnUse"><stop class="ydq0kpc8x"/><stop offset="1" class="e-sxlzbkb"/></linearGradient><linearGradient id="i1vQwDb" x1="5.884" x2="9.392" y1="24.313" y2="24.188" gradientUnits="userSpaceOnUse"><stop class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="isFAhEb" x1="14.955" x2="30.142" y1="13.719" y2="8.281" gradientUnits="userSpaceOnUse"><stop class="sbbw_6vcc"/><stop offset="1" class="b7cutjkii"/></linearGradient><linearGradient id="ixVyvDb" x1="14.335" x2="16.084" y1="20.514" y2="20.514" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="iKMzpBb" x1="17.696" x2="15.784" y1="21.116" y2="21.088" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="ifJgsfY" x1="16.309" x2="16.309" y1="22.5" y2="21.431" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="irtw8Rd" x1="16.181" x2="16.181" y1="22.578" y2="22.266" gradientUnits="userSpaceOnUse"><stop class="l1er17byo"/><stop offset="1" class="abcg0lbyl"/></linearGradient><linearGradient id="iy7aq0b" x1="14.119" x2="14.885" y1="25.782" y2="24.571" gradientUnits="userSpaceOnUse"><stop class="wl-j51biu"/><stop offset=".663" class="i-vkeo5mo"/></linearGradient><linearGradient id="i2rqafc" x1="21.46" x2="20.875" y1="17.387" y2="17.748" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iuoJadd" x1="13.26" x2="12.675" y1="17.387" y2="17.748" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iQcHjiG" x1="21.489" x2="20.706" y1="13.397" y2="11.796" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iG4hVNd" x1="11.597" x2="9.379" y1="13.159" y2="12.229" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iaBMVod" x1="7.253" x2="7.253" y1="9.402" y2="13.425" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><linearGradient id="iEq6RCb" x1="8.628" x2="23.068" y1="28.788" y2="24.701" gradientUnits="userSpaceOnUse"><stop offset=".314" class="zw_dreclm"/><stop offset="1" class="t6ufhqbgd"/></linearGradient><linearGradient id="iZiu8Dc" x1="6.586" x2="9.004" y1="23.676" y2="23.456" gradientUnits="userSpaceOnUse"><stop class="r5hzt4y-e"/><stop offset="1" class="fklwc1-8k"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-beard-light" /></template>
<style>
.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.abcg0lbyl {
  stop-color: var(--svg-color--d6938e, #D6938E);
  stop-opacity: 0;
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.akoqlejsh {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.4 15.89c1.217 0 2.245.84 2.525 1.975a.51.51 0 0 1-.499.635h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.556-2.102");
}

.anj76nhkr {
  d: path("m23.338 8.07l-5.74 1.913a1.953 1.953 0 0 0 .878 3.788l5.706-.764z");
}

.ay1rn8bxh {
  stop-color: var(--svg-color--d0958d, #D0958D);
  stop-opacity: 0;
}

.b7cutjkii {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
  stop-opacity: 0;
}

.boi6jzbkr {
  cx: 11.367px;
  cy: 17.108px;
  rx: 0.726px;
  ry: 0.368px;
}

.bppy92r3u {
  d: path("M6.327 14.734c0-.498.2-1.094.6-1.393l.3-.298c.5-.398.7-.995.7-1.591V9.86c0-.497.301-.895.801-.994c1.2-.299 3.701-.796 7.302-.796s6.102.497 7.302.796c.4.099.8.497.8.994v1.592c0 .596.3 1.193.7 1.59c.937.657.879 1.018.801 1.791c-.1.995-.2 2.685-.2 2.685h.034L24.97 24.9c-.3 3.3-2.894 5.6-5.987 5.6h-5.987c-3.193 0-5.687-2.3-5.987-5.6c-.26-3.387-.373-6.785-.683-10.166");
}

.br836wbnd {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.891 16.75c.119.158-.13.351-.41.562c-.283.21-.492.358-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.252.725-.094");
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

.c5fcuybyq {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m8.91 13.487l.002-.002l.004-.002l.008-.007l.022-.018l.067-.05q.083-.061.222-.15c.186-.117.45-.262.783-.394a5.3 5.3 0 0 1 2.784-.295a.995.995 0 0 1-.31 1.967a3.3 3.3 0 0 0-1.742.18a2.8 2.8 0 0 0-.56.297l-.015.01a.995.995 0 0 1-1.266-1.535");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.e-sxlzbkb {
  stop-color: var(--svg-color--daa594, #DAA594);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.ekazbbcvj {
  fill: var(--svg-color--242324, #242324);
  d: path("m24.933 6.479l.8.397c1.4.697 2.2 2.288 1.9 3.979l-1.1 5.669c-.098.585-.485.98-1.066.994h-.034s.1-1.69.2-2.685c.081-.808-.06-1.054-.8-1.79c-.4-.398-.7-.995-.7-1.592v-1.59c0-.498-.4-.896-.8-.996c-1.201-.298-3.702-.795-7.303-.795s-6.102.497-7.302.795c-.5.1-.8.498-.8.995v1.591c0 .597-.2 1.194-.7 1.592l-.3.298c-.4.299-.6.895-.6 1.393c.1 1.094.2 2.685.2 2.685l-.092-.003a1.18 1.18 0 0 1-1.109-.992l-1.1-5.669c-.2-1.591.6-3.182 2-3.879l.8-.397c.5-.299 1-.697 1.501-1.095l1.8-1.89c1.1-.994 2.701-1.292 4.102-.596c1 .298 2.1.298 3.1 0c1.501-.497 3.202-.1 4.402.995l1.5 1.491c.4.498.9.796 1.5 1.095");
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.fklwc1-8k {
  stop-color: var(--svg-color--4d4341, #4D4341);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.hmo3unbrx {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
}

.hplqxft1w {
  stop-color: var(--svg-color--d0958d, #D0958D);
}

.i-vkeo5mo {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
  stop-opacity: 0;
}

.ilts2c-ja {
  fill: var(--svg-color--000, #000);
  d: path("M12.823 18.061a.95.95 0 0 0-.953-.953a.95.95 0 0 0-.953.953c0 .16.037.31.105.439h1.687a.95.95 0 0 0 .114-.439");
}

.iwvz51btf {
  stop-color: var(--svg-color--4d4a4f, #4D4A4F);
}

.j4owdlb_o {
  d: path("M13.39 17.866c0-.538-.438-.896-.556-1.005l-.537.52l.33.674z");
}

.jfozcpb8o {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.529 24.104a.32.32 0 0 0-.382.066a.29.29 0 0 0-.032.375a3.39 3.39 0 0 0 2.831 1.512a3.39 3.39 0 0 0 2.832-1.512a.295.295 0 0 0-.033-.378a.32.32 0 0 0-.38-.063a5.2 5.2 0 0 1-2.419.573a5.24 5.24 0 0 1-2.417-.573Z");
}

.k4bv00_-r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M7.493 9.586v1.674c-.014.277-.131.897-.481 1.16");
}

.kg9_cdcna {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.043 13.217c.802-.14 2.366-.1 3.449.742");
}

.l1er17byo {
  stop-color: var(--svg-color--d6938e, #D6938E);
}

.l380b9bcr {
  cx: 24.833px;
  cy: 18.559px;
  r: 3.113px;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
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

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.nv4ngd99r {
  stop-color: var(--svg-color--4d4a4f, #4D4A4F);
  stop-opacity: 0;
}

.o_drskb5d {
  cx: 7.092px;
  cy: 18.559px;
  r: 1.855px;
}

.o3mf9zbxg {
  fill: var(--svg-color--fbc4b1, #FBC4B1);
  d: path("m15.234 18.027l-.991 3.17a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.702-1.204-.702-1.427 0");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pko800b2f {
  cx: 24.833px;
  cy: 18.559px;
  r: 1.855px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
}

.po_nc8bzh {
  d: path("m24.933 6.479l.8.397c1.4.697 2.2 2.288 1.9 3.979l-1.1 5.669c-.098.585-.485.98-1.066.994h-.034s.1-1.69.2-2.685c.081-.808-.06-1.054-.8-1.79c-.4-.398-.7-.995-.7-1.592v-1.59c0-.498-.4-.896-.8-.996c-1.201-.298-3.702-.795-7.303-.795s-6.102.497-7.302.795c-.5.1-.8.498-.8.995v1.591c0 .597-.2 1.194-.7 1.592l-.3.298c-.4.299-.6.895-.6 1.393c.1 1.094.2 2.685.2 2.685l-.092-.003a1.18 1.18 0 0 1-1.109-.992l-1.1-5.669c-.2-1.591.6-3.182 2-3.879l.8-.397c.5-.299 1-.697 1.501-1.095l1.8-1.89c1.1-.994 2.701-1.292 4.102-.596c1 .298 2.1.298 3.1 0c1.501-.497 3.202-.1 4.402.995l1.5 1.491c.4.498.9.796 1.5 1.095");
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.q5pd5ob4x {
  d: path("M11.87 16.397a1.664 1.664 0 0 0-1.604 2.103h3.214c.038-.144.061-.288.061-.439a1.675 1.675 0 0 0-1.671-1.664");
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
  stop-opacity: 0;
}

.r5hzt4y-e {
  stop-color: var(--svg-color--4d4341, #4D4341);
}

.rcuz4uefu {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
  stop-opacity: 0;
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
}

.rs4yt5byt {
  fill: var(--svg-color--000, #000);
  d: path("M19.06 18.061c0-.53.424-.953.953-.953c.53 0 .953.424.953.953a.94.94 0 0 1-.106.439h-1.686a.86.86 0 0 1-.113-.439");
}

.ryb9ksbwy {
  d: path("M20.013 16.397a1.664 1.664 0 0 1 1.604 2.103h-3.215a1.7 1.7 0 0 1-.06-.439a1.67 1.67 0 0 1 1.671-1.664");
}

.sbbw_6vcc {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
}

.t6ufhqbgd {
  stop-color: var(--svg-color--373234, #373234);
}

.u5mf6ccuk {
  d: path("M19.891 16.75c.119.158-.13.351-.41.562c-.283.21-.492.358-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.252.725-.094");
}

.uggh96bfb {
  cx: 7.092px;
  cy: 18.559px;
  r: 3.113px;
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.v4djr4bzy {
  cx: 24.833px;
  cy: 18.559px;
  r: 1.855px;
}

.v8iqyzpqo {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m15.433 18.33l-1.53 3.17c-.19.652.266 1.304.91 1.304h1.375c.645 0 1.1-.662.91-1.304l-.929-3.17c-.199-.701-.527-.701-.736 0");
}

.ve9quacpk {
  d: path("m25.672 14.634l-.703 10.2c-.301 3.3-2.51 5.666-6.023 5.666h-6.024C9.41 30.5 7.2 28.134 6.9 24.834l-.663-9.345l3.072 8.045c.1.5.703.6 1.004.3l.803-.7c.703-.6 1.506-.8 2.31-.8h5.019c.903 0 1.706.2 2.309.8l.803.7c.301.3.903.1 1.004-.3zm-12.75 11.7c0 .9.803 1.7 1.807 1.7c.201 0 .301-.2.301-.3v-.1c0-.5.402-.9.904-.9s.903.4.903.9v.1c0 .2.201.3.302.3c.903 0 1.807-.7 1.807-1.7v-1.5c0-.5-.347-.9-1.004-.9h-4.016c-.636 0-1.004.4-1.004.9z");
}

.vl9ydvbeb {
  cx: 11.367px;
  cy: 17.108px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
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

.wl-j51biu {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.x8vxh860r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M9.31 14.184c.61-.54 1.942-1.107 3.593-.844");
}

.xyza8fboq {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m22.883 13.486l-.002-.002l-.004-.002l-.008-.007l-.023-.018l-.067-.05a4 4 0 0 0-.221-.15a5 5 0 0 0-.783-.394a5.3 5.3 0 0 0-2.784-.295a.995.995 0 0 0 .31 1.967a3.3 3.3 0 0 1 1.742.18a2.8 2.8 0 0 1 .56.297q.011.009.015.01a.995.995 0 0 0 1.265-1.536");
}

.yau6hdc7q {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.484 15.89c-1.218 0-2.247.84-2.526 1.975a.51.51 0 0 0 .499.635h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.102");
}

.ydq0kpc8x {
  stop-color: var(--svg-color--ffdac0, #FFDAC0);
}

.ye0wtbymj {
  d: path("m15.234 18.027l-.991 3.17a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.702-1.204-.702-1.427 0");
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.yyvs3obha {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
  stop-opacity: 0;
}

.z0cx0-b2p {
  stop-color: var(--svg-color--b57995, #B57995);
}

.za_-d8ldm {
  stop-color: var(--svg-color--b57995, #B57995);
  stop-opacity: 0;
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
}

.zoxn06blq {
  d: path("M21.496 17.842a1.57 1.57 0 0 0-.432-.862l-.484.531l.218.426z");
}

.zw_dreclm {
  stop-color: var(--svg-color--1d1223, #1D1223);
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

</style>
