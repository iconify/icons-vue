<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i8NcPAS)" class="x23qd5bao"/><path fill="url(#iEusgId)" class="x23qd5bao"/><path fill="url(#i4PA0su)" class="x23qd5bao"/><g filter="url(#iTEPIud)"><path class="aeak0zb5f"/></g><g filter="url(#ik8vyKc)"><path fill="url(#icQgc3d)" class="yr-it8bbt"/><path fill="url(#inlPnid)" class="yr-it8bbt"/><path fill="url(#iV59Yib)" class="yr-it8bbt"/></g><path fill="url(#ir3urIe)" class="yr-it8bbt"/><path fill="url(#ibf7iCc)" class="mxtum0_7s"/><path fill="url(#izyJX4b)" class="mxtum0_7s"/><path fill="url(#iAjXjKc)" class="mxtum0_7s"/><path fill="url(#iNc9FCc)" class="mxtum0_7s"/><path fill="url(#i2CBGoc)" class="mxtum0_7s"/><g filter="url(#iM5mNlc)"><path fill="url(#iO6Vxbd)" class="ms-y_bbed"/><path fill="url(#izyr54c)" class="ms-y_bbed"/><path fill="url(#iOP3ETd)" class="ms-y_bbed"/><path fill="url(#iHWVn3b)" class="ms-y_bbed"/><path fill="url(#iVIBBcN)" class="ms-y_bbed"/><path fill="url(#iqp2I1N)" class="ms-y_bbed"/><path fill="url(#i9emJHe)" class="ms-y_bbed"/></g><path fill="url(#i6ngyDx)" class="ms-y_bbed"/><path fill="url(#i0RA82b)" class="ms-y_bbed"/><g filter="url(#icFw3qd)"><path class="ch8j1n90t"/></g><g filter="url(#i5djMGb)"><path fill="url(#iOqUZgb)" class="q0uuenbnl"/><path fill="url(#iuPCOqc)" class="q0uuenbnl"/><path fill="url(#i38vCgb)" class="q0uuenbnl"/><path fill="url(#iUOR5ke)" class="q0uuenbnl"/></g><g filter="url(#iihAIkd)"><path fill="url(#iwYc0GO)" class="ga5fls61p"/></g><g filter="url(#igQIVqb)"><path stroke="url(#iUmxwCe)" class="lownffbyl"/></g><path class="u9nb5acml"/><g filter="url(#i5Ycabe)"><path class="djkfu9cda"/></g><g filter="url(#irwkMxb)"><path class="mfymzqbit"/></g><g filter="url(#idSL68c)"><path class="xvt6-li_v"/></g><g filter="url(#iMrxXyc)"><path clip-rule="evenodd" class="jqcmqgkbh"/></g><path class="axgu7dufp"/><path fill="url(#iuvCnBQ)" class="pb6wv5bfm"/><path class="el4_syb1y"/><g filter="url(#iLwftGc)"><path class="md91ccbvd"/><path fill="url(#ii4HF0b)" class="d5xx5sbtg"/></g><g filter="url(#ir5tvPe)"><path fill="url(#iNv1zAc)" class="a6kvl-uum"/></g><path class="ofvz6p8lh"/><path fill="url(#iasU5Bf)" class="zgjfljb7z"/><path class="gg6-i0tzp"/><g filter="url(#iUJKEML)"><path fill="url(#im7IQNe)" class="xg-x3u61h"/></g><g filter="url(#iQyF2ne)"><ellipse transform="rotate(-27.914 13.64 10.582)" class="b3ui_v_5e"/><ellipse fill="url(#idA3Vle)" transform="rotate(-27.914 13.64 10.582)" class="ac9cyybse"/></g><g filter="url(#iUqLnUc)"><path stroke="url(#i0ysjQc)" class="zav9a6p_u"/></g><g filter="url(#ilJhoHc)"><path stroke="url(#i9Q42ac)" class="zlifvscts"/></g><g filter="url(#iZsGMDc)"><path fill="url(#iDMe5Td)" clip-rule="evenodd" class="znteny2zw"/></g><path fill="url(#iRuSP0d)" clip-rule="evenodd" class="znteny2zw"/><path fill="url(#iWJ0fGb)" clip-rule="evenodd" class="znteny2zw"/><path fill="url(#iQgPmhb)" clip-rule="evenodd" class="znteny2zw"/><path fill="url(#i8cDj5d)" clip-rule="evenodd" class="znteny2zw"/><path fill="url(#ikXKfBc)" clip-rule="evenodd" class="znteny2zw"/><defs><radialGradient id="i8NcPAS" cx="0" cy="0" r="1" gradientTransform="matrix(-15.56254 13.4375 -17.37186 -20.1191 24.048 18.224)" gradientUnits="userSpaceOnUse"><stop offset=".468" class="c-m2-db1r"/><stop offset="1" class="lpw_68bsr"/></radialGradient><radialGradient id="iEusgId" cx="0" cy="0" r="1" gradientTransform="rotate(136.874 7.155 16.615)scale(6.07995 6.11994)" gradientUnits="userSpaceOnUse"><stop class="wdm8my4jl"/><stop offset="1" class="au_4blbid"/></radialGradient><radialGradient id="icQgc3d" cx="0" cy="0" r="1" gradientTransform="matrix(-8.48286 0 0 -9.81298 19.454 23.506)" gradientUnits="userSpaceOnUse"><stop class="prklqobcj"/><stop offset="1" class="ym6mqqctl"/></radialGradient><radialGradient id="inlPnid" cx="0" cy="0" r="1" gradientTransform="matrix(-12.58516 -5.40493 4.87536 -11.35207 18.546 28.82)" gradientUnits="userSpaceOnUse"><stop offset=".79" class="zl0gbcrkw"/><stop offset="1" class="rqdnlobox"/></radialGradient><radialGradient id="iV59Yib" cx="0" cy="0" r="1" gradientTransform="matrix(-.96657 6.43064 -6.40563 -.96281 15.351 16.688)" gradientUnits="userSpaceOnUse"><stop offset=".633" class="zhscqlbpv"/><stop offset="1" class="hr18vydyp"/></radialGradient><radialGradient id="ir3urIe" cx="0" cy="0" r="1" gradientTransform="matrix(10.03122 6.84374 -7.53953 11.05108 10.048 16.693)" gradientUnits="userSpaceOnUse"><stop offset=".972" class="j3anwzjna"/><stop offset=".991" class="y61txublo"/></radialGradient><radialGradient id="izyJX4b" cx="0" cy="0" r="1" gradientTransform="matrix(-4.99999 3.96877 -1.22204 -1.53957 20.704 16.975)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="n1775ub4r"/><stop offset="1" class="yh-1r4-sb"/></radialGradient><radialGradient id="iAjXjKc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.3178 2.71017 -3.76393 -8.7743 17.397 16.577)" gradientUnits="userSpaceOnUse"><stop offset=".694" class="ln5rrnnhq"/><stop offset=".928" class="zvy0gs06n"/></radialGradient><radialGradient id="iNc9FCc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.81395 -5.55482 0 15.277 17.7)" gradientUnits="userSpaceOnUse"><stop offset=".498" class="g2b227i-s"/><stop offset="1" class="ul9foxw2y"/></radialGradient><radialGradient id="i2CBGoc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.86218 -8.36853 0 16.173 15.786)" gradientUnits="userSpaceOnUse"><stop offset=".789" class="ryrd9sb2y"/><stop offset="1" class="lesk0hb6s"/></radialGradient><radialGradient id="iO6Vxbd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.11576 2.52066 -4.16347 -11.75336 19.392 11.287)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset="1" class="m45oyzb-o"/></radialGradient><radialGradient id="izyr54c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.24201 1.14133 -.94724 -1.86074 18.168 11.454)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="iOP3ETd" cx="0" cy="0" r="1" gradientTransform="matrix(.88939 -4.13735 5.43653 1.16867 13.832 17.678)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="iHWVn3b" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.61021 -12.5585 0 15.87 10.246)" gradientUnits="userSpaceOnUse"><stop offset=".593" class="ajxs5ri3z"/><stop offset="1" class="x05md6_2b"/></radialGradient><radialGradient id="iVIBBcN" cx="0" cy="0" r="1" gradientTransform="matrix(-5.76249 1.53371 -2.55482 -9.59904 16.816 12.435)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></radialGradient><radialGradient id="iqp2I1N" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.177 1.50085 0 18.594 10.312)" gradientUnits="userSpaceOnUse"><stop class="e0lgwbeaw"/><stop offset="1" class="y7n0ymbzx"/></radialGradient><radialGradient id="i9emJHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39101 1.65636 0 14.11 10.402)" gradientUnits="userSpaceOnUse"><stop class="w2e_edyjl"/><stop offset="1" class="gsggv-b-p"/></radialGradient><radialGradient id="i6ngyDx" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.3125 -2.15625 0 21.485 10.63)" gradientUnits="userSpaceOnUse"><stop class="p8j84vbpc"/><stop offset="1" class="fej9_egjo"/></radialGradient><radialGradient id="i0RA82b" cx="0" cy="0" r="1" gradientTransform="matrix(-8.57129 0 0 -19.8464 19.548 11.557)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="abwnix0nz"/><stop offset=".987" class="az-d89_ji"/></radialGradient><radialGradient id="iuPCOqc" cx="0" cy="0" r="1" gradientTransform="rotate(-105.892 13.224 -.11)scale(2.60516 1.49071)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="iuvCnBQ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82981 -1.31991 0 18.38 10.68)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ii4HF0b" cx="0" cy="0" r="1" gradientTransform="matrix(-.23668 -.305 .4199 -.32585 18.146 10.765)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iasU5Bf" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82982 -1.31992 0 13.917 10.68)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="idA3Vle" cx="0" cy="0" r="1" gradientTransform="matrix(-.0079 -.50492 .60693 -.0095 13.624 10.903)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iDMe5Td" cx="0" cy="0" r="1" gradientTransform="rotate(121.679 8.163 8.531)scale(12.0506 10.0996)" gradientUnits="userSpaceOnUse"><stop class="qgb64vbcc"/><stop offset="1" class="qifif4biz"/></radialGradient><radialGradient id="iWJ0fGb" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.7879 -8.79851 0 16.149 8.624)" gradientUnits="userSpaceOnUse"><stop class="al4q6ffpx"/><stop offset=".866" class="thcs-obed"/><stop offset="1" class="x8eb2zbkq"/></radialGradient><radialGradient id="iQgPmhb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.65397 -9.37048 9.62948 -5.81025 17.293 12.436)" gradientUnits="userSpaceOnUse"><stop offset=".758" class="xhimsmknu"/><stop offset=".994" class="fuwrw2b5h"/></radialGradient><radialGradient id="i8cDj5d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.79524 3.2082 -9.93816 -8.65893 21.93 3.256)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="p40y9dbky"/><stop offset="1" class="msi-dpmal"/></radialGradient><filter id="iTEPIud" width="16.584" height="15.121" x="5.412" y="13.596" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3295" stdDeviation=".125"/></filter><filter id="ik8vyKc" width="16.502" height="15.01" x="5.314" y="13.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.317647 0 0 0 0 0.745098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3295"/></filter><filter id="iM5mNlc" width="10.328" height="12.079" x="10.977" y="5.717" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3295"/></filter><filter id="icFw3qd" width="2.92" height="3.743" x="14.523" y="10.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3295" stdDeviation=".25"/></filter><filter id="i5djMGb" width="2.42" height="3.243" x="14.939" y="10.382" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3295" stdDeviation=".125"/></filter><filter id="iihAIkd" width="2.42" height="3.243" x="14.939" y="10.196" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3295" stdDeviation=".125"/></filter><filter id="igQIVqb" width="3.778" height="1.552" x="14.26" y="13.696" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3295" stdDeviation=".05"/></filter><filter id="i5Ycabe" width="3.065" height="1.315" x="17.117" y="9.854" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3295"/></filter><filter id="irwkMxb" width="3.065" height="1.315" x="12.116" y="9.854" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3295"/></filter><filter id="idSL68c" width="2.504" height="1.111" x="12.254" y="8.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 0.211765 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3295"/></filter><filter id="iMrxXyc" width="2.504" height="1.111" x="17.795" y="8.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 0.211765 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3295"/></filter><filter id="iLwftGc" width=".799" height=".707" x="17.632" y="10.232" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3295" stdDeviation=".05"/></filter><filter id="ir5tvPe" width=".901" height=".924" x="18.494" y="10.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3295" stdDeviation=".1"/></filter><filter id="iUJKEML" width=".998" height="1.053" x="13.949" y="10.246" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3295" stdDeviation=".1"/></filter><filter id="iQyF2ne" width=".929" height=".716" x="13.175" y="10.224" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3295" stdDeviation=".05"/></filter><filter id="iUqLnUc" width="2.299" height=".986" x="17.833" y="8.529" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3295" stdDeviation=".1"/></filter><filter id="ilJhoHc" width="2.299" height=".986" x="12.257" y="8.529" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3295" stdDeviation=".1"/></filter><filter id="iZsGMDc" width="15.212" height="17.812" x="8.718" y="1.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.45098 0 0 0 0 0.258824 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3295"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.196078 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3295" result="effect2_innerShadow_4002_3295"/></filter><linearGradient id="i4PA0su" x1="5.73" x2="8.017" y1="29.972" y2="29.972" gradientUnits="userSpaceOnUse"><stop class="fozhrdxgd"/><stop offset="1" class="fnmmfsrpm"/></linearGradient><linearGradient id="ibf7iCc" x1="20.735" x2="12.673" y1="17.506" y2="20.912" gradientUnits="userSpaceOnUse"><stop class="vow0ojb4t"/><stop offset="1" class="lem83lbgo"/></linearGradient><linearGradient id="iOqUZgb" x1="16.149" x2="16.149" y1="13.375" y2="10.632" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="i38vCgb" x1="15.079" x2="15.953" y1="12.595" y2="12.702" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="iUOR5ke" x1="16.149" x2="16.149" y1="13.469" y2="12.845" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="iwYc0GO" x1="16.149" x2="16.149" y1="10.446" y2="11.945" gradientUnits="userSpaceOnUse"><stop class="fkdj3ejgt"/><stop offset="1" class="mvi8_hbzp"/></linearGradient><linearGradient id="iUmxwCe" x1="15.403" x2="15.866" y1="14.979" y2="14.088" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="iNv1zAc" x1="19.175" x2="18.855" y1="10.734" y2="10.931" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="im7IQNe" x1="14.677" x2="14.357" y1="10.734" y2="10.931" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i0ysjQc" x1="18.231" x2="20.329" y1="8.829" y2="9.334" gradientUnits="userSpaceOnUse"><stop class="i736s42mq"/><stop offset="1" class="ajpa2y_nm"/></linearGradient><linearGradient id="i9Q42ac" x1="14.157" x2="12.189" y1="8.829" y2="9.215" gradientUnits="userSpaceOnUse"><stop class="i736s42mq"/><stop offset="1" class="ajpa2y_nm"/></linearGradient><linearGradient id="iRuSP0d" x1="23.43" x2="22.057" y1="12.595" y2="12.595" gradientUnits="userSpaceOnUse"><stop class="g7b7vvs6b"/><stop offset="1" class="tcqkmtb2a"/></linearGradient><linearGradient id="ikXKfBc" x1="8.868" x2="10.463" y1="11.642" y2="11.579" gradientUnits="userSpaceOnUse"><stop class="wqzdbcbqv"/><stop offset="1" class="ikg8w-bhe"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-with-headscarf" /></template>
<style>
.a6kvl-uum {
  d: path("M19.195 10.983a.86.86 0 0 0-.236-.472l-.265.29l.12.234z");
}

.a9dfe182j {
  stop-color: var(--svg-color--d4993e, #D4993E);
}

.abwnix0nz {
  stop-color: var(--svg-color--cf9347, #CF9347);
  stop-opacity: 0;
}

.ac9cyybse {
  cx: 13.639px;
  cy: 10.582px;
  rx: 0.398px;
  ry: 0.202px;
}

.aeak0zb5f {
  fill: var(--svg-color--514575, #514575);
  d: path("M5.663 27.23a.1.1 0 0 0 .053.105c1.522.762 3.168 1.131 4.986 1.131c5.349 0 9.887-3.85 11.04-8.846a.1.1 0 0 0-.045-.108c-.883-.524-1.797-1-2.822-1.25c-.314-.078-.652-.131-.652-.455v-1.941c0-1.118-.902-2.02-2.02-2.02s-2.02.902-2.02 2.02v1.941c0 .324-.205.443-.519.521c-4.197 1.11-7.23 4.068-8.001 8.902");
}

.ajpa2y_nm {
  stop-color: var(--svg-color--c36b56, #C36B56);
  stop-opacity: 0;
}

.ajxs5ri3z {
  stop-color: var(--svg-color--f3943b, #F3943B);
  stop-opacity: 0;
}

.al4q6ffpx {
  stop-color: var(--svg-color--573199, #573199);
  stop-opacity: 0;
}

.au_4blbid {
  stop-color: var(--svg-color--7866a7, #7866A7);
  stop-opacity: 0;
}

.axgu7dufp {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.595 9.914c.668 0 1.232.46 1.385 1.082a.28.28 0 0 1-.274.349h-2.282a.235.235 0 0 1-.232-.278a1.43 1.43 0 0 1 1.402-1.153");
}

.az-d89_ji {
  stop-color: var(--svg-color--cf9347, #CF9347);
}

.b3ui_v_5e {
  cx: 13.639px;
  cy: 10.582px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.398px;
  ry: 0.202px;
}

.c-m2-db1r {
  stop-color: var(--svg-color--6e5d9b, #6E5D9B);
}

.ch8j1n90t {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m15.747 11.062l-.699 1.74a.552.552 0 0 0 .533.714h.804a.553.553 0 0 0 .532-.715l-.543-1.739c-.117-.385-.505-.385-.627 0");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d5xx5sbtg {
  d: path("M18.314 10.385c.065.087-.07.193-.225.308c-.154.115-.269.196-.333.11c-.065-.087.007-.251.161-.366c.154-.116.332-.139.397-.052");
}

.djkfu9cda {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.317 10.708c.271-.477.684-.854 1.572-.854c.39 0 .764.107 1.098.377c.275.222.238.506.025.613l-.569.324c-.667-.215-1.404-.244-2.126-.46");
}

.e0lgwbeaw {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.el4_syb1y {
  fill: var(--svg-color--000, #000);
  d: path("M17.86 11.104a.52.52 0 0 1 .523-.522a.52.52 0 0 1 .465.763h-.926a.5.5 0 0 1-.062-.24");
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.fej9_egjo {
  stop-color: var(--svg-color--ffd530, #FFD530);
  stop-opacity: 0;
}

.fkdj3ejgt {
  stop-color: var(--svg-color--f8c73f, #F8C73F);
}

.fnmmfsrpm {
  stop-color: var(--svg-color--655b83, #655B83);
  stop-opacity: 0;
}

.fozhrdxgd {
  stop-color: var(--svg-color--655b83, #655B83);
}

.ft5dv1b6b {
  fill: none;
}

.fuwrw2b5h {
  stop-color: var(--svg-color--7358a4, #7358A4);
}

.g2b227i-s {
  stop-color: var(--svg-color--452686, #452686);
}

.g7b7vvs6b {
  stop-color: var(--svg-color--906ccf, #906CCF);
}

.ga5fls61p {
  d: path("m15.758 10.735l-.544 1.739a.552.552 0 0 0 .533.715h.804a.553.553 0 0 0 .533-.715l-.544-1.739c-.117-.385-.66-.385-.782 0");
}

.gg6-i0tzp {
  fill: var(--svg-color--000, #000);
  d: path("M14.438 11.104a.52.52 0 0 0-.523-.522a.52.52 0 0 0-.465.763h.926a.5.5 0 0 0 .062-.24");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gsggv-b-p {
  stop-color: var(--svg-color--f09429, #F09429);
  stop-opacity: 0;
}

.hr18vydyp {
  stop-color: var(--svg-color--4f2e93, #4F2E93);
  stop-opacity: 0;
}

.i736s42mq {
  stop-color: var(--svg-color--c36b56, #C36B56);
}

.ikg8w-bhe {
  stop-color: var(--svg-color--755da5, #755DA5);
  stop-opacity: 0;
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.j3anwzjna {
  stop-color: var(--svg-color--9c7ada, #9C7ADA);
  stop-opacity: 0;
}

.jqcmqgkbh {
  fill: var(--svg-color--b64e31, #B64E31);
  fill-rule: evenodd;
  d: path("m19.966 9.004l-.141.235za.274.274 0 0 1-.281.47l-.005-.002a1 1 0 0 0-.115-.06a3 3 0 0 0-.35-.138a2.3 2.3 0 0 0-1.097-.094a.274.274 0 1 1-.096-.54c.525-.093 1.011 0 1.359.111a3.4 3.4 0 0 1 .571.244l.01.006z");
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.lem83lbgo {
  stop-color: var(--svg-color--60429a, #60429A);
}

.lesk0hb6s {
  stop-color: var(--svg-color--5c35a2, #5C35A2);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ln5rrnnhq {
  stop-color: var(--svg-color--755fa4, #755FA4);
  stop-opacity: 0;
}

.lownffbyl {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.15 14.268a3.1 3.1 0 0 1-1.455-.353c-.144-.074-.298.091-.208.225a1.976 1.976 0 0 0 3.324 0c.09-.139-.064-.3-.208-.225a3.1 3.1 0 0 1-1.454.353Z");
}

.lpw_68bsr {
  stop-color: var(--svg-color--534082, #534082);
}

.m45oyzb-o {
  stop-color: var(--svg-color--eb9235, #EB9235);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.md91ccbvd {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.314 10.385c.065.087-.07.193-.225.308c-.154.115-.269.196-.333.11c-.065-.087.007-.251.161-.366c.154-.116.332-.139.397-.052");
}

.mfymzqbit {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.981 10.708c-.271-.477-.684-.854-1.572-.854c-.39 0-.764.107-1.098.377c-.274.222-.238.506-.025.613l.569.324c.667-.215 1.404-.244 2.126-.46");
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.ms-y_bbed {
  d: path("M17.32 6.102a2 2 0 0 0-2.36 0l-3.163 2.312a2 2 0 0 0-.82 1.615v2.235a5.17 5.17 0 0 0 3.693 4.951c.468.119.962.181 1.472.181c.505 0 .994-.06 1.457-.177a5.17 5.17 0 0 0 3.706-4.955v-2.235a2 2 0 0 0-.82-1.615z");
}

.msi-dpmal {
  stop-color: var(--svg-color--a27ce3, #A27CE3);
  stop-opacity: 0;
}

.mvi8_hbzp {
  stop-color: var(--svg-color--f8c73f, #F8C73F);
  stop-opacity: 0;
}

.mxtum0_7s {
  d: path("M16.173 22.427a5.85 5.85 0 1 0 0-11.7a5.85 5.85 0 0 0 0 11.7");
}

.n1775ub4r {
  stop-color: var(--svg-color--9376cc, #9376CC);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofvz6p8lh {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.703 9.914c-.668 0-1.232.46-1.385 1.082a.28.28 0 0 0 .273.349h2.282a.235.235 0 0 0 .233-.278a1.43 1.43 0 0 0-1.403-1.153");
}

.p40y9dbky {
  stop-color: var(--svg-color--a27ce3, #A27CE3);
}

.p8j84vbpc {
  stop-color: var(--svg-color--ffd530, #FFD530);
}

.pb_rvfc5z {
  stop-color: var(--svg-color--ffe842, #FFE842);
}

.pb6wv5bfm {
  d: path("M18.383 10.191a.913.913 0 0 1 .88 1.154h-1.764a.916.916 0 0 1 .884-1.153");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.prklqobcj {
  stop-color: var(--svg-color--8e6bd1, #8E6BD1);
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.q0uuenbnl {
  d: path("m15.758 10.92l-.544 1.74a.552.552 0 0 0 .533.715h.804a.553.553 0 0 0 .533-.716l-.544-1.738c-.117-.385-.66-.385-.782 0");
}

.qgb64vbcc {
  stop-color: var(--svg-color--9670d7, #9670D7);
}

.qifif4biz {
  stop-color: var(--svg-color--7454ac, #7454AC);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwjswe-rp {
  stop-color: var(--svg-color--e48538, #E48538);
  stop-opacity: 0;
}

.rqdnlobox {
  stop-color: var(--svg-color--7a65a5, #7A65A5);
}

.ryrd9sb2y {
  stop-color: var(--svg-color--5c35a2, #5C35A2);
  stop-opacity: 0;
}

.tcqkmtb2a {
  stop-color: var(--svg-color--906ccf, #906CCF);
  stop-opacity: 0;
}

.thcs-obed {
  stop-color: var(--svg-color--573199, #573199);
  stop-opacity: 0.024;
}

.u9nb5acml {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M16.15 14.268a3.1 3.1 0 0 1-1.455-.353c-.144-.074-.298.091-.208.225a1.976 1.976 0 0 0 3.324 0c.09-.139-.064-.3-.208-.225a3.1 3.1 0 0 1-1.454.353");
}

.ud-bjxb5c {
  stop-color: var(--svg-color--d4993e, #D4993E);
  stop-opacity: 0;
}

.ul9foxw2y {
  stop-color: var(--svg-color--452686, #452686);
  stop-opacity: 0;
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.v2k4g1b_w {
  stop-color: var(--svg-color--ffe842, #FFE842);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vow0ojb4t {
  stop-color: var(--svg-color--8966c9, #8966C9);
}

.vsluyubzo {
  stop-color: var(--svg-color--f8a322, #F8A322);
  stop-opacity: 0;
}

.w2e_edyjl {
  stop-color: var(--svg-color--f09429, #F09429);
}

.wa9cqx9pi {
  stop-color: var(--svg-color--ffe644, #FFE644);
}

.wdm8my4jl {
  stop-color: var(--svg-color--8570b8, #8570B8);
}

.wqzdbcbqv {
  stop-color: var(--svg-color--755da5, #755DA5);
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.x05md6_2b {
  stop-color: var(--svg-color--d97c39, #D97C39);
}

.x23qd5bao {
  d: path("M18.72 18.079a.715.715 0 0 1-.53-.703V15.36c0-1.161-.905-2.098-2.026-2.098s-2.026.937-2.026 2.098v2.016a.715.715 0 0 1-.53.703c-4.73 1.19-8.24 5.61-8.24 10.875v1.018H26.97v-1.018c0-5.265-3.51-9.684-8.25-10.875");
}

.x8eb2zbkq {
  stop-color: var(--svg-color--573199, #573199);
}

.xg-x3u61h {
  d: path("M14.748 10.996c0-.294-.24-.49-.304-.55l-.295.285l.181.369z");
}

.xhimsmknu {
  stop-color: var(--svg-color--7358a4, #7358A4);
  stop-opacity: 0;
}

.xvt6-li_v {
  fill: var(--svg-color--b64e31, #B64E31);
  d: path("m12.674 9.472l-.005.002a.274.274 0 0 1-.282-.47l.002-.001l.003-.002l.01-.006a2 2 0 0 1 .152-.078c.1-.048.244-.11.419-.166a2.9 2.9 0 0 1 1.358-.111a.274.274 0 1 1-.095.54c-.408-.072-.8 0-1.096.094a3 3 0 0 0-.444.185z");
}

.y61txublo {
  stop-color: var(--svg-color--9c7ada, #9C7ADA);
}

.y7n0ymbzx {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
  stop-opacity: 0;
}

.yh-1r4-sb {
  stop-color: var(--svg-color--9376cc, #9376CC);
  stop-opacity: 0;
}

.ym6mqqctl {
  stop-color: var(--svg-color--7050ad, #7050AD);
}

.yr-it8bbt {
  d: path("M5.415 27.223a.1.1 0 0 0 .053.105c1.552.777 3.231 1.154 5.086 1.154c5.455 0 10.083-3.927 11.26-9.023a.1.1 0 0 0-.047-.107c-.9-.536-1.833-1.022-2.88-1.276c-.32-.08-.663-.134-.663-.464v-1.98c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v1.98c0 .33-.21.451-.53.531c-4.28 1.132-7.373 4.149-8.16 9.08");
}

.z-gb6n28y {
  stop-color: var(--svg-color--e4883f, #E4883F);
  stop-opacity: 0;
}

.zav9a6p_u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.133 8.863c.33-.08 1.15-.04 1.698.352");
}

.zgjfljb7z {
  d: path("M13.915 10.191a.913.913 0 0 0-.88 1.154H14.8a1 1 0 0 0 .033-.24a.92.92 0 0 0-.917-.914");
}

.zhscqlbpv {
  stop-color: var(--svg-color--4f2e93, #4F2E93);
}

.zl0gbcrkw {
  stop-color: var(--svg-color--7a65a5, #7A65A5);
  stop-opacity: 0;
}

.zlifvscts {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.255 8.863c-.33-.08-1.15-.04-1.698.352");
}

.znteny2zw {
  fill-rule: evenodd;
  d: path("M10.283 4.194c2.911-2.928 8.815-2.925 11.732.007c1.234 1.39 1.415 2.897 1.415 4.125c0 .836-.055 2.784-.086 3.68c-.086 3.713-2.68 7.25-7.195 7.406c-5.391 0-7.138-4.914-7.195-7.414c-.032-.896-.086-2.843-.086-3.68c0-1.227.18-2.734 1.415-4.124m4.678 1.909a2 2 0 0 1 2.36 0l3.164 2.312a2 2 0 0 1 .82 1.615v2.234a5.164 5.164 0 1 1-10.328 0V10.03a2 2 0 0 1 .82-1.615z");
}

.zvy0gs06n {
  stop-color: var(--svg-color--755fa4, #755FA4);
}

</style>
