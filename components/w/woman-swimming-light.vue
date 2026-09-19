<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i8MVuoc)"><path fill="url(#iksZC4d)" class="g121rudws"/></g><g filter="url(#iWBYyCb)"><path fill="url(#iRfmjRd)" class="b0vtgtb4v"/></g><path fill="url(#imOIb6c)" class="y809_hbqk"/><path fill="url(#iG2Hcrb)" class="y809_hbqk"/><g filter="url(#i95DLEe)"><path class="huwvstbme"/></g><path fill="url(#iFMzsQe)" class="rkd9j7b8u"/><path fill="url(#ixqQKNe)" class="rkd9j7b8u"/><path fill="url(#ioDNDwd)" class="rkd9j7b8u"/><path fill="url(#iK1Avvd)" class="ax1ze8btb"/><path fill="url(#iz5PUHO)" class="ax1ze8btb"/><circle fill="url(#iVzV10d)" class="vsjbsubjv"/><g filter="url(#iaOgkoe)"><circle fill="url(#iNM3y4d)" class="dd60xs37z"/></g><circle class="duvau7uac"/><g filter="url(#itHRKDd)"><circle class="yzk_758ko"/></g><g filter="url(#ieHqz0d)"><path fill="url(#iReF14d)" class="u61niccwd"/><path fill="url(#iFhq2jb)" class="u61niccwd"/><path fill="url(#i3g40He)" class="u61niccwd"/><path fill="url(#iQSjNJQ)" class="u61niccwd"/></g><g filter="url(#iXd28rj)"><path fill="url(#ikpBezb)" class="v030gha5h"/><path fill="url(#i0j0bke)" class="v030gha5h"/></g><g filter="url(#i901qYd)"><path fill="url(#ioc54Nb)" class="recys05fn"/></g><g filter="url(#ioi0s8c)"><circle stroke="url(#ic3dFgb)" class="w87zqcbta"/></g><circle class="ttmasdbok"/><g filter="url(#idcsXIc)"><path class="iks90vxqr"/></g><g filter="url(#iT4qJDg)"><path class="k1xdllb9h"/><path fill="url(#iSOq1ud)" class="sw-t_s-eb"/></g><path fill="url(#iTqkBob)" transform="rotate(45.489 14.576 14.486)" class="d57-lacwd"/><path fill="url(#i2K8tId)" transform="rotate(45.489 14.576 14.486)" class="d57-lacwd"/><path fill="url(#iaLWCqb)" class="gme-ibcld"/><path fill="url(#isALree)" class="gme-ibcld"/><path fill="url(#ikR9YGd)" class="gme-ibcld"/><path class="woe82mb8o"/><path fill="url(#iwTbJke)" class="kmyvxe3ny"/><path fill="url(#iDOybHe)" class="kmyvxe3ny"/><path fill="url(#iuDFfyb)" class="kmyvxe3ny"/><g filter="url(#ioPWkHl)"><path fill="url(#isBRU0c)" class="p3j6lfbll"/></g><path clip-rule="evenodd" class="zsnt86kqa"/><g filter="url(#izu6LYX)"><path fill="url(#i59zkDd)" class="w-f9npb5r"/></g><path clip-rule="evenodd" class="yz_8n8zbp"/><path fill="url(#iXLlwfb)" clip-rule="evenodd" class="jy85699ai"/><path clip-rule="evenodd" class="ewmpt0b-e"/><path fill="url(#iSRuCsd)" clip-rule="evenodd" class="rv20wmh1k"/><path clip-rule="evenodd" class="gus4kyb4w"/><path fill="url(#itLYgLd)" clip-rule="evenodd" class="r83i5-b7z"/><path clip-rule="evenodd" class="cic4wrbon"/><path fill="url(#iz0tKAd)" clip-rule="evenodd" class="zrg62uq2q"/><g filter="url(#iTcs5uY)"><path clip-rule="evenodd" class="vbuulebwn"/></g><g filter="url(#iBlRO1d)"><path clip-rule="evenodd" class="x4ydame9e"/></g><g filter="url(#icgD0Gd)"><path stroke="url(#iZU4Hsd)" clip-rule="evenodd" class="ckjm2zbvq"/></g><path fill="url(#ikzvlUd)" class="hhgarhotr"/><g filter="url(#iJDUgjz)"><path class="pa_gnkbmp"/></g><defs><radialGradient id="iRfmjRd" cx="0" cy="0" r="1" gradientTransform="matrix(2.09229 4.61475 -4.78418 2.1691 17.27 11.998)" gradientUnits="userSpaceOnUse"><stop offset=".255" class="m3tpc0gzd"/><stop offset=".769" class="iencerbek"/><stop offset="1" class="ts6tj1b9q"/></radialGradient><radialGradient id="imOIb6c" cx="0" cy="0" r="1" gradientTransform="matrix(4.25 -.4375 .72193 7.01299 9.738 18.707)" gradientUnits="userSpaceOnUse"><stop class="syp23gb-m"/><stop offset="1" class="t2fru8brh"/></radialGradient><radialGradient id="iG2Hcrb" cx="0" cy="0" r="1" gradientTransform="rotate(120.141 .519 11.733)scale(1.12022 1.22424)" gradientUnits="userSpaceOnUse"><stop class="dbcaftyrm"/><stop offset="1" class="kpz18eb7m"/></radialGradient><radialGradient id="iFMzsQe" cx="0" cy="0" r="1" gradientTransform="rotate(-127.867 18.828 4.88)scale(6.23941 9.66032)" gradientUnits="userSpaceOnUse"><stop class="qkza4tkjj"/><stop offset="1" class="p-g29ytws"/></radialGradient><radialGradient id="ixqQKNe" cx="0" cy="0" r="1" gradientTransform="matrix(5.40624 1.93806 -3.92034 10.93584 16.64 18.682)" gradientUnits="userSpaceOnUse"><stop class="qgmdss-1z"/><stop offset="1" class="vh8h0wvlv"/></radialGradient><radialGradient id="ioDNDwd" cx="0" cy="0" r="1" gradientTransform="rotate(108.881 5.333 15.825)scale(.62769 5.10178)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="ddam2y24q"/><stop offset="1" class="e2coowbrg"/></radialGradient><radialGradient id="iK1Avvd" cx="0" cy="0" r="1" gradientTransform="rotate(-177.859 13.426 10.356)scale(6.69217 10.4863)" gradientUnits="userSpaceOnUse"><stop offset=".359" class="olribsbgf"/><stop offset="1" class="gw01gubth"/></radialGradient><radialGradient id="iz5PUHO" cx="0" cy="0" r="1" gradientTransform="rotate(-163.471 15.406 9.664)scale(13.9857 10.6342)" gradientUnits="userSpaceOnUse"><stop offset=".636" class="ez6ahacpu"/><stop offset="1" class="sz75067ko"/></radialGradient><radialGradient id="iVzV10d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.01562 .92188 -.5107 -.56264 18.656 12.264)" gradientUnits="userSpaceOnUse"><stop offset=".011" class="igx665z_i"/><stop offset="1" class="zfpdrebcu"/></radialGradient><radialGradient id="iNM3y4d" cx="0" cy="0" r="1" gradientTransform="matrix(.32031 -.30469 .39566 .41595 17.912 12.853)" gradientUnits="userSpaceOnUse"><stop class="skl6euwzp"/><stop offset="1" class="dh7n4ztfg"/></radialGradient><radialGradient id="iFhq2jb" cx="0" cy="0" r="1" gradientTransform="rotate(72.52 -2.767 18.353)scale(5.02015 5.81107)" gradientUnits="userSpaceOnUse"><stop offset=".545" class="d9x_-fb5p"/><stop offset="1" class="g5wr4t9sk"/></radialGradient><radialGradient id="i3g40He" cx="0" cy="0" r="1" gradientTransform="matrix(1.75 1.50397 -1.54062 1.79264 15.677 14.195)" gradientUnits="userSpaceOnUse"><stop offset=".228" class="yhjfntb6m"/><stop offset="1" class="z78k_ob0g"/></radialGradient><radialGradient id="iQSjNJQ" cx="0" cy="0" r="1" gradientTransform="matrix(1.5 1.59375 -1.31546 1.23808 13.114 16.445)" gradientUnits="userSpaceOnUse"><stop offset=".422" class="p4jbl87fs"/><stop offset="1" class="iz7_01bqj"/></radialGradient><radialGradient id="ikpBezb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.31254 4.18747 -3.07382 -3.16563 15.082 12.144)" gradientUnits="userSpaceOnUse"><stop class="qi5e80-zg"/><stop offset="1" class="nvrmd7xyq"/></radialGradient><radialGradient id="i0j0bke" cx="0" cy="0" r="1" gradientTransform="rotate(136.15 5.33 8.62)scale(9.35994 5.84176)" gradientUnits="userSpaceOnUse"><stop offset=".489" class="uxkewoidr"/><stop offset="1" class="ox604rbri"/></radialGradient><radialGradient id="iSOq1ud" cx="0" cy="0" r="1" gradientTransform="rotate(135.14 4.826 11.475)scale(.85969 .22297)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="qpkqxibzk"/><stop offset="1" class="pdslbmrwt"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="i2K8tId" cx="0" cy="0" r="1" gradientTransform="rotate(90.613 .324 14.606)scale(.28732 .60402)" gradientUnits="userSpaceOnUse"><stop offset=".649" class="wjyjhxryd"/><stop offset="1" class="y01zyrbyt"/></radialGradient><radialGradient id="iwTbJke" cx="0" cy="0" r="1" gradientTransform="matrix(-.46094 .29687 -.34413 -.53431 11.95 17.24)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="y84i3jbqp"/><stop offset="1" class="mn36x_bue"/></radialGradient><radialGradient id="iSRuCsd" cx="0" cy="0" r="1" gradientTransform="rotate(146.787 3.392 4.77)scale(3.43755 1.60167)" gradientUnits="userSpaceOnUse"><stop offset=".402" class="morzxly6g"/><stop offset="1" class="hi8t0xwzs"/></radialGradient><radialGradient id="itLYgLd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.76027 2.13307 -1.04932 -1.35786 8.58 8.024)" gradientUnits="userSpaceOnUse"><stop offset=".402" class="morzxly6g"/><stop offset="1" class="hi8t0xwzs"/></radialGradient><radialGradient id="iz0tKAd" cx="0" cy="0" r="1" gradientTransform="rotate(144.615 3.203 5.685)scale(3.29193 1.58011)" gradientUnits="userSpaceOnUse"><stop offset=".402" class="morzxly6g"/><stop offset="1" class="hi8t0xwzs"/></radialGradient><radialGradient id="ikzvlUd" cx="0" cy="0" r="1" gradientTransform="matrix(5.70676 .41357 -.20538 2.834 10.61 4.87)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="hg6bed3ov"/><stop offset="1" class="h-knxwkhr"/></radialGradient><filter id="i8MVuoc" width="28.306" height="9.762" x="1.847" y="13.136" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.729412 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23163"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.584314 0 0 0 0 0.854902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23163" result="effect2_innerShadow_3987_23163"/></filter><filter id="iWBYyCb" width="7.381" height="7.123" x="14.483" y="10.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.105882 0 0 0 0 0.0666667 0 0 0 0 0.0823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23163"/></filter><filter id="i95DLEe" width="19.128" height="17.805" x="10.609" y="2.808" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25" dy="-1.25"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.607843 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23163"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.509804 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23163" result="effect2_innerShadow_3987_23163"/></filter><filter id="iaOgkoe" width="2.053" height="2.053" x="16.759" y="11.896" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23163" stdDeviation=".075"/></filter><filter id="itHRKDd" width="2.044" height="2.044" x="11.179" y="17.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23163" stdDeviation=".1"/></filter><filter id="ieHqz0d" width="9.291" height="9.288" x="10.356" y="10.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.505882 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23163"/></filter><filter id="iXd28rj" width="9.223" height="9.224" x="7.632" y="8.478" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.662745 0 0 0 0 0.466667 0 0 0 0 0.666667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23163"/></filter><filter id="i901qYd" width="28.306" height="9.762" x="1.847" y="20.199" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.301961 0 0 0 0 0.580392 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23163"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.482353 0 0 0 0 0.772549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23163" result="effect2_innerShadow_3987_23163"/></filter><filter id="ioi0s8c" width="2.217" height="2.217" x="15.887" y="16.582" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23163" stdDeviation=".1"/></filter><filter id="idcsXIc" width="3.003" height="3.058" x="13.846" y="14.925" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23163" stdDeviation=".25"/></filter><filter id="iT4qJDg" width="2.203" height="2.458" x="14.338" y="14.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.545098 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23163"/><feGaussianBlur result="effect2_foregroundBlur_3987_23163" stdDeviation=".05"/></filter><filter id="ioPWkHl" width="2.23" height="2.219" x="14.698" y="12.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0745098 0 0 0 0 0.407843 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23163"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.631373 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23163" result="effect2_innerShadow_3987_23163"/></filter><filter id="izu6LYX" width="2.23" height="2.219" x="11.909" y="15.48" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0745098 0 0 0 0 0.407843 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23163"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.564706 0 0 0 0 0.854902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23163" result="effect2_innerShadow_3987_23163"/></filter><filter id="iTcs5uY" width="4.333" height="3.319" x="7.677" y="6.285" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.529412 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23163"/></filter><filter id="iBlRO1d" width="2.872" height="2.874" x="14.454" y="12.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23163" stdDeviation=".075"/></filter><filter id="icgD0Gd" width="2.872" height="2.874" x="11.674" y="15.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23163" stdDeviation=".075"/></filter><filter id="iJDUgjz" width="10.971" height="13.923" x="16.785" y="5.419" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23163" stdDeviation=".5"/></filter><linearGradient id="iksZC4d" x1="26.833" x2="2.047" y1="17.552" y2="17.552" gradientUnits="userSpaceOnUse"><stop class="q8sgc5k5k"/><stop offset="1" class="o5v952b3t"/></linearGradient><linearGradient id="iReF14d" x1="18.56" x2="14.8" y1="15.277" y2="19.771" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset=".886" class="mua_crbaw"/></linearGradient><linearGradient id="ioc54Nb" x1="26.833" x2="2.047" y1="24.615" y2="24.615" gradientUnits="userSpaceOnUse"><stop class="t8k4gwbbc"/><stop offset="1" class="kpw0uhrkg"/></linearGradient><linearGradient id="ic3dFgb" x1="17.219" x2="17.188" y1="18.621" y2="16.715" gradientUnits="userSpaceOnUse"><stop class="rzorcbc7r"/><stop offset="1" class="lt8zy5hkm"/></linearGradient><linearGradient id="iTqkBob" x1="14.945" x2="14.954" y1="14.659" y2="15.609" gradientUnits="userSpaceOnUse"><stop class="uhfoyqb3x"/><stop offset="1" class="eb0haibji"/></linearGradient><linearGradient id="iaLWCqb" x1="16.334" x2="17.49" y1="12.381" y2="12.17" gradientUnits="userSpaceOnUse"><stop class="nd7thpbgb"/><stop offset="1" class="fs5c4ebko"/></linearGradient><linearGradient id="isALree" x1="16.734" x2="16.847" y1="11.683" y2="11.761" gradientUnits="userSpaceOnUse"><stop offset=".354" class="r7rn_bcmx"/><stop offset="1" class="ht-1xqb8g"/></linearGradient><linearGradient id="ikR9YGd" x1="17.383" x2="17.3" y1="12.101" y2="12.046" gradientUnits="userSpaceOnUse"><stop class="hb9tx9b6i"/><stop offset="1" class="ppgh7wbyg"/></linearGradient><linearGradient id="iDOybHe" x1="11.422" x2="11.304" y1="18.027" y2="17.843" gradientUnits="userSpaceOnUse"><stop offset=".145" class="u8ol5ho1k"/><stop offset="1" class="bbcrpz64i"/></linearGradient><linearGradient id="iuDFfyb" x1="10.984" x2="11.027" y1="17.398" y2="17.468" gradientUnits="userSpaceOnUse"><stop class="bwf4x3cld"/><stop offset="1" class="a5orf1efs"/></linearGradient><linearGradient id="isBRU0c" x1="16.765" x2="15.219" y1="13.152" y2="14.668" gradientUnits="userSpaceOnUse"><stop class="t40s1ccrt"/><stop offset="1" class="vjkwz1bxm"/></linearGradient><linearGradient id="i59zkDd" x1="13.976" x2="12.429" y1="15.91" y2="17.425" gradientUnits="userSpaceOnUse"><stop class="ol7r9kndd"/><stop offset="1" class="xs-q3bbyy"/></linearGradient><linearGradient id="iXLlwfb" x1="8.205" x2="11.23" y1="4.842" y2="4.525" gradientUnits="userSpaceOnUse"><stop class="cljygbcta"/><stop offset="1" class="o9z30xbsa"/></linearGradient><linearGradient id="iZU4Hsd" x1="14.263" x2="12.12" y1="15.613" y2="17.658" gradientUnits="userSpaceOnUse"><stop offset=".096" class="qi1y9bzby"/><stop offset=".322" class="f-nlkoezi"/><stop offset=".768" class="qi1y9bzby"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-swimming-light" /></template>
<style>
.a5orf1efs {
  stop-color: var(--svg-color--504b5b, #504B5B);
  stop-opacity: 0;
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.ax1ze8btb {
  d: path("M15.164 19.953c.36.594 1.149 1.82 2.274 1.996c1.406.219 3.742-.79 3.789-2.531c.078-1.557-.845-2.406-1.794-3.086c.817-.36 1.574-.376 2.326-.36c.899.802 2.705 2.341 3.858 3.07c.85.538 1.741.287 2.375-.093c.594.605 1.388 1.483 1.93 2.406l-6.531 2.266c-1.933.265-6.61.256-9.86-1.906a17 17 0 0 1 1.384-1.89q.124.058.25.128");
}

.b0vtgtb4v {
  d: path("M17.427 10.457a1.45 1.45 0 0 1-.656-.344l-2.187 1.547c1.307 1.828 3.935 5.482 3.992 5.476c.077-.008 2.399-.266 2.851-.883c.453-.617.54-1.593.328-2.32c-.21-.726-.656-.976-1.226-1.133a1.34 1.34 0 0 1-.867-.695c-.07-.14-.188-.437-.68-.914s-1.156-.649-1.555-.734");
}

.bbcrpz64i {
  stop-color: var(--svg-color--443873, #443873);
  stop-opacity: 0;
}

.bwf4x3cld {
  stop-color: var(--svg-color--504b5b, #504B5B);
}

.cic4wrbon {
  fill: var(--svg-color--d5a28e, #D5A28E);
  fill-rule: evenodd;
  d: path("M11.369 6.5a.66.66 0 0 1-.634.689c-1.184.05-2.098.941-2.666 1.87a.662.662 0 1 1-1.13-.69c.65-1.066 1.893-2.426 3.74-2.504a.66.66 0 0 1 .69.634");
}

.ckjm2zbvq {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.07 15.601c-.364-.372-1-.409-1.373-.045l-.559.546c-.372.364-.34.99.024 1.362c.363.373.976.432 1.349.068l.559-.546c.372-.364.364-1.012 0-1.385Z");
}

.cljygbcta {
  stop-color: var(--svg-color--e7ad91, #E7AD91);
}

.d57-lacwd {
  d: path("M14.576 14.486h.758v1.123h-.758z");
}

.d9x_-fb5p {
  stop-color: var(--svg-color--deaaa8, #DEAAA8);
  stop-opacity: 0;
}

.dbcaftyrm {
  stop-color: var(--svg-color--020102, #020102);
}

.dd60xs37z {
  cx: 17.785px;
  cy: 12.923px;
  r: 0.877px;
}

.ddam2y24q {
  stop-color: var(--svg-color--cb8d71, #CB8D71);
}

.dh7n4ztfg {
  stop-color: var(--svg-color--f4b798, #F4B798);
}

.duvau7uac {
  cx: 12.201px;
  cy: 18.511px;
  r: 1.296px;
  fill: var(--svg-color--b8808d, #B8808D);
}

.e2coowbrg {
  stop-color: var(--svg-color--cb8d71, #CB8D71);
  stop-opacity: 0;
}

.eb0haibji {
  stop-color: var(--svg-color--413251, #413251);
}

.ewmpt0b-e {
  fill: var(--svg-color--d5a28e, #D5A28E);
  fill-rule: evenodd;
  d: path("M11.266 4.943a.66.66 0 0 1-.608.713C9.263 5.767 8.17 6.733 7.621 7.52a.662.662 0 1 1-1.086-.758c.677-.971 2.085-2.271 4.018-2.426a.663.663 0 0 1 .713.608");
}

.ez6ahacpu {
  stop-color: var(--svg-color--553c7c, #553C7C);
  stop-opacity: 0;
}

.f-nlkoezi {
  stop-color: var(--svg-color--5f5669, #5F5669);
  stop-opacity: 0;
}

.fs5c4ebko {
  stop-color: var(--svg-color--4c4055, #4C4055);
}

.ft5dv1b6b {
  fill: none;
}

.g121rudws {
  d: path("M3.922 13.136c-.975 0-1.656.49-1.875.735v9.027h27.906v-8.871l-.003-.003c-.623-.545-1.015-.888-2.2-.888c-.906 0-1.67.67-2.05 1.004c-.261.224-.94.637-1.864.637s-1.469-.406-2.07-.906c-.27-.224-.952-.735-1.914-.735c-.963 0-1.857.667-2.165 1c-.244.224-.718.641-1.87.641c-.794 0-1.396-.35-1.614-.562c-.37-.36-1.133-1.079-2.312-1.079c-.975 0-1.54.47-1.907.782s-1.006.89-2.093.89c-.985 0-1.585-.5-1.915-.775l-.007-.006c-.276-.297-1.072-.89-2.047-.89");
}

.g5wr4t9sk {
  stop-color: var(--svg-color--ab7188, #AB7188);
}

.gme-ibcld {
  d: path("M17.065 11.243a.1.1 0 0 1 .138-.026l.44.298a.1.1 0 0 1 .026.138l-.84 1.24l-.604-.41z");
}

.gus4kyb4w {
  fill: var(--svg-color--d5a28e, #D5A28E);
  fill-rule: evenodd;
  d: path("M10.907 5.724a.663.663 0 0 1-.608.713c-.639.051-1.186.36-1.663.804c-.482.447-.862 1.004-1.157 1.487a.662.662 0 1 1-1.13-.69c.314-.516.769-1.196 1.385-1.768c.62-.576 1.434-1.072 2.46-1.153a.663.663 0 0 1 .712.607");
}

.gw01gubth {
  stop-color: var(--svg-color--8f69d4, #8F69D4);
}

.h-knxwkhr {
  stop-color: var(--svg-color--e1ac8c, #E1AC8C);
  stop-opacity: 0;
}

.hb9tx9b6i {
  stop-color: var(--svg-color--574e60, #574E60);
}

.hg6bed3ov {
  stop-color: var(--svg-color--d4a18c, #D4A18C);
}

.hhgarhotr {
  d: path("M10.61 8.058h4.828a4 4 0 0 1 3.602 2.26l2.734 5.664l5.601 2.389l-4.733-9.792a8 8 0 0 0-7.204-4.52h-4.829z");
}

.hi8t0xwzs {
  stop-color: var(--svg-color--cf997e, #CF997E);
  stop-opacity: 0;
}

.ht-1xqb8g {
  stop-color: var(--svg-color--403044, #403044);
  stop-opacity: 0;
}

.huwvstbme {
  fill: var(--svg-color--f7c5aa, #F7C5AA);
  d: path("M10.61 8.058h4.828a4 4 0 0 1 3.602 2.26l4.385 9.608l5.063.687l-5.846-12.034a8 8 0 0 0-7.204-4.52h-4.829z");
}

.iencerbek {
  stop-color: var(--svg-color--100b13, #100B13);
}

.igx665z_i {
  stop-color: var(--svg-color--ffd3bb, #FFD3BB);
}

.iks90vxqr {
  fill: var(--svg-color--ca9297, #CA9297);
  d: path("m15.127 17.263l-.781-1.556l.289-.282l1.51.853a.4.4 0 0 1 .084.633l-.464.457a.4.4 0 0 1-.638-.105");
}

.iz7_01bqj {
  stop-color: var(--svg-color--be8888, #BE8888);
  stop-opacity: 0;
}

.jy85699ai {
  fill-rule: evenodd;
  d: path("M9.936 5.448c-.558.043-1.037.1-1.263.157a.662.662 0 1 1-.323-1.284c.964-.243 2.04-.263 3.029-.263a.662.662 0 1 1 0 1.325c-.345 0-.901.024-1.443.065");
}

.k1xdllb9h {
  fill: var(--svg-color--eebfab, #EEBFAB);
  d: path("m15.22 17.013l-.782-1.556l.29-.282l1.51.853a.4.4 0 0 1 .084.633l-.465.457a.4.4 0 0 1-.638-.105");
}

.kmyvxe3ny {
  d: path("M10.925 18.316a.1.1 0 0 1-.138-.029l-.29-.444a.1.1 0 0 1 .029-.139l1.254-.817l.399.612z");
}

.kpw0uhrkg {
  stop-color: var(--svg-color--4184e7, #4184E7);
}

.kpz18eb7m {
  stop-color: var(--svg-color--020102, #020102);
  stop-opacity: 0;
}

.lt8zy5hkm {
  stop-color: var(--svg-color--e3a695, #E3A695);
}

.m3tpc0gzd {
  stop-color: var(--svg-color--3e393b, #3E393B);
}

.mn36x_bue {
  stop-color: var(--svg-color--483e5b, #483E5B);
  stop-opacity: 0;
}

.morzxly6g {
  stop-color: var(--svg-color--cf997e, #CF997E);
}

.mua_crbaw {
  stop-color: var(--svg-color--af828a, #AF828A);
}

.nd7thpbgb {
  stop-color: var(--svg-color--574c62, #574C62);
}

.nvrmd7xyq {
  stop-color: var(--svg-color--8258c3, #8258C3);
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.o5v952b3t {
  stop-color: var(--svg-color--3ea5fe, #3EA5FE);
}

.o9z30xbsa {
  stop-color: var(--svg-color--d8ac90, #D8AC90);
}

.ol7r9kndd {
  stop-color: var(--svg-color--3387e0, #3387E0);
}

.olribsbgf {
  stop-color: var(--svg-color--a882f8, #A882F8);
}

.ox604rbri {
  stop-color: var(--svg-color--7047b3, #7047B3);
}

.p-g29ytws {
  stop-color: var(--svg-color--f2bcac, #F2BCAC);
}

.p3j6lfbll {
  d: path("M15.533 12.956a.821.821 0 1 1 1.148 1.175l-.487.476a.821.821 0 0 1-1.148-1.175z");
}

.p4jbl87fs {
  stop-color: var(--svg-color--be8888, #BE8888);
}

.pa_gnkbmp {
  fill: var(--svg-color--fad1b0, #FAD1B0);
  d: path("M20.223 8.467c-.675-1.475-1.907-1.969-2.438-2.031c1.469-.157 2.672.789 3.156 1.656l5.815 10.25l-2.533-1.281c-1.052-2.25-3.325-7.119-4-8.594");
}

.pdslbmrwt {
  stop-color: var(--svg-color--f3c4a7, #F3C4A7);
  stop-opacity: 0;
}

.ppgh7wbyg {
  stop-color: var(--svg-color--574e60, #574E60);
  stop-opacity: 0;
}

.q8sgc5k5k {
  stop-color: var(--svg-color--40aafe, #40AAFE);
}

.qgmdss-1z {
  stop-color: var(--svg-color--bb7c7d, #BB7C7D);
}

.qi1y9bzby {
  stop-color: var(--svg-color--5f5669, #5F5669);
}

.qi5e80-zg {
  stop-color: var(--svg-color--a783e1, #A783E1);
}

.qkza4tkjj {
  stop-color: var(--svg-color--ffdcc2, #FFDCC2);
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
}

.r7rn_bcmx {
  stop-color: var(--svg-color--403044, #403044);
}

.r83i5-b7z {
  fill-rule: evenodd;
  d: path("M10.907 5.724a.663.663 0 0 1-.608.713c-.639.051-1.186.36-1.663.804c-.482.447-.862 1.004-1.157 1.487a.662.662 0 1 1-1.13-.69c.314-.516.769-1.196 1.385-1.768c.62-.576 1.434-1.072 2.46-1.153a.663.663 0 0 1 .712.607");
}

.recys05fn {
  d: path("M3.922 20.199c-.975 0-1.656.49-1.875.734v9.028h27.906V21.09l-.003-.003c-.623-.546-1.015-.888-2.2-.888c-.906 0-1.67.67-2.05 1.003c-.261.225-.94.637-1.864.637s-1.469-.406-2.07-.906c-.27-.223-.952-.734-1.914-.734c-.963 0-1.857.667-2.165 1c-.244.224-.718.64-1.87.64c-.794 0-1.396-.35-1.614-.562c-.37-.36-1.133-1.078-2.312-1.078c-.975 0-1.54.469-1.907.781s-1.006.89-2.093.89c-.985 0-1.585-.5-1.915-.774l-.007-.006c-.276-.297-1.072-.891-2.047-.891");
}

.rkd9j7b8u {
  d: path("M17.313 17.558c-1.688 1.15-3.224 3.25-3.782 4.157c3.25 2.162 7.927 2.171 9.86 1.906l6.53-2.266c-.765-1.305-2.036-2.52-2.53-3l-5.638-2.367c-1.468-.062-2.331.133-4.44 1.57");
}

.rv20wmh1k {
  fill-rule: evenodd;
  d: path("M11.266 4.943a.66.66 0 0 1-.608.713C9.263 5.767 8.17 6.733 7.621 7.52a.662.662 0 1 1-1.086-.758c.677-.971 2.085-2.271 4.018-2.426a.663.663 0 0 1 .713.608");
}

.rzorcbc7r {
  stop-color: var(--svg-color--dbab9f, #DBAB9F);
}

.skl6euwzp {
  stop-color: var(--svg-color--fcc5a9, #FCC5A9);
}

.sw-t_s-eb {
  d: path("m15.22 17.013l-.782-1.556l.29-.282l1.51.853a.4.4 0 0 1 .084.633l-.465.457a.4.4 0 0 1-.638-.105");
}

.syp23gb-m {
  stop-color: var(--svg-color--313a5a, #313A5A);
}

.sz75067ko {
  stop-color: var(--svg-color--3c2369, #3C2369);
}

.t2fru8brh {
  stop-color: var(--svg-color--060311, #060311);
}

.t40s1ccrt {
  stop-color: var(--svg-color--489be1, #489BE1);
}

.t8k4gwbbc {
  stop-color: var(--svg-color--3f90f0, #3F90F0);
}

.ts6tj1b9q {
  stop-color: var(--svg-color--010000, #010000);
}

.ttmasdbok {
  cx: 16.996px;
  cy: 17.691px;
  r: 0.809px;
  fill: var(--svg-color--87014e, #87014E);
}

.u61niccwd {
  d: path("M10.575 17.254c-.312-.326-.224-.75-.14-.922l5.281-5.172c.438-.113.66.125.79.265l1.815 1.854a4.12 4.12 0 0 1 .157 5.594c-1.49 1.703-4.067 1.876-5.747.36c-1.072-.967-2-1.819-2.156-1.98");
}

.u8ol5ho1k {
  stop-color: var(--svg-color--443873, #443873);
}

.uhfoyqb3x {
  stop-color: var(--svg-color--52475d, #52475D);
}

.uxkewoidr {
  stop-color: var(--svg-color--7047b3, #7047B3);
  stop-opacity: 0;
}

.v030gha5h {
  d: path("M16.827 10.167L9.45 17.573a.096.096 0 0 1-.121.014c-.578-.38-1.499-1.374-1.583-2.662c-.11-1.671.368-2.712 2.078-4.515c1.868-1.969 3.516-2.094 4.97-1.828c1.05.192 1.78 1.038 2.047 1.466a.096.096 0 0 1-.015.119");
}

.vbuulebwn {
  fill: var(--svg-color--dfac99, #DFAC99);
  fill-rule: evenodd;
  d: path("M11.348 8.01c-.585 0-1.22.227-1.66.526c-.308.21-.667.602-.82.805a.662.662 0 1 1-1.057-.8c.202-.266.66-.78 1.133-1.1c.629-.429 1.52-.756 2.404-.756a.662.662 0 1 1 0 1.325");
}

.vh8h0wvlv {
  stop-color: var(--svg-color--f1ae9a, #F1AE9A);
  stop-opacity: 0;
}

.vjkwz1bxm {
  stop-color: var(--svg-color--4799ea, #4799EA);
}

.vsjbsubjv {
  cx: 17.785px;
  cy: 12.923px;
  r: 1.296px;
}

.w-f9npb5r {
  d: path("M12.744 15.713a.821.821 0 1 1 1.148 1.176l-.487.476a.821.821 0 0 1-1.148-1.176z");
}

.w87zqcbta {
  cx: 16.996px;
  cy: 17.691px;
  r: 0.809px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.wjyjhxryd {
  stop-color: var(--svg-color--453b50, #453B50);
}

.woe82mb8o {
  fill: var(--svg-color--4e496a, #4E496A);
  d: path("M10.925 18.316a.1.1 0 0 1-.138-.029l-.29-.444a.1.1 0 0 1 .029-.139l1.254-.817l.399.612z");
}

.x4ydame9e {
  stroke: var(--svg-color--5c4c6d, #5C4C6D);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.85 12.807c-.363-.373-1-.41-1.372-.046l-.56.547c-.372.363-.34.99.024 1.362s.976.43 1.349.067l.56-.546c.372-.364.363-1.012 0-1.384Z");
}

.xs-q3bbyy {
  stop-color: var(--svg-color--2f81cb, #2F81CB);
}

.y01zyrbyt {
  stop-color: var(--svg-color--453b50, #453B50);
  stop-opacity: 0;
}

.y809_hbqk {
  d: path("M9.654 18.16c-.133-.403-.31-.636-.406-.735l1.093-1.133l4.883 3.727l-1.39 1.742c-.157-.242-.68-.515-2.336-1.21c-1.657-.696-1.702-1.961-1.844-2.391");
}

.y84i3jbqp {
  stop-color: var(--svg-color--483e5b, #483E5B);
}

.yhjfntb6m {
  stop-color: var(--svg-color--deaa9f, #DEAA9F);
}

.yz_8n8zbp {
  fill: var(--svg-color--412e4c, #412E4C);
  fill-rule: evenodd;
  d: path("m14.144 17.146l-.488.476a1.181 1.181 0 0 1-1.65-1.69l.487-.476a1.181 1.181 0 0 1 1.65 1.69m-.238-1.419a.82.82 0 0 0-1.162-.014l-.487.476a.821.821 0 1 0 1.148 1.176l.487-.476a.82.82 0 0 0 .014-1.162");
}

.yzk_758ko {
  cx: 12.201px;
  cy: 18.512px;
  r: 0.822px;
  fill: var(--svg-color--b2757c, #B2757C);
}

.z78k_ob0g {
  stop-color: var(--svg-color--deaa9f, #DEAA9F);
  stop-opacity: 0;
}

.zfpdrebcu {
  stop-color: var(--svg-color--fbc2a4, #FBC2A4);
}

.zrg62uq2q {
  fill-rule: evenodd;
  d: path("M11.369 6.5a.66.66 0 0 1-.634.689c-1.184.05-2.098.941-2.666 1.87a.662.662 0 1 1-1.13-.69c.65-1.066 1.893-2.426 3.74-2.504a.66.66 0 0 1 .69.634");
}

.zsnt86kqa {
  fill: var(--svg-color--412e4c, #412E4C);
  fill-rule: evenodd;
  d: path("m16.933 14.389l-.488.476a1.181 1.181 0 1 1-1.65-1.691l.487-.476a1.182 1.182 0 0 1 1.65 1.69m-.238-1.42a.82.82 0 0 0-1.162-.013l-.487.476a.821.821 0 0 0 1.148 1.175l.487-.476a.82.82 0 0 0 .014-1.162");
}

</style>
