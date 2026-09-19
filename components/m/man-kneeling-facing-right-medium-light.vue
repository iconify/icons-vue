<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i61J34d)"><path class="bjvd-sb3y"/></g><g filter="url(#ixd8kVd)"><path stroke="url(#iVVQcUd)" class="dqeezuryw"/></g><path fill="url(#iskXoee)" class="imnkx9bdk"/><g filter="url(#iQpFiqe)"><path class="a5y-b-r0a"/></g><path fill="url(#iNk50gc)" class="hzh6l3bzz"/><path fill="url(#iZElbee)" class="hzh6l3bzz"/><path fill="url(#iBP8yDd)" class="lz9t8o9wv"/><g filter="url(#iKJabvb)"><path class="m8_3k6boh"/><path fill="url(#iAYuCdd)" class="q2ucym9nt"/><path fill="url(#ihastRb)" class="q2ucym9nt"/></g><g filter="url(#ipKjLjc)"><path class="t63k-8bgz"/><path fill="url(#iKWyxzz)" class="w4enui6bm"/><path fill="url(#iM1lpZc)" class="w4enui6bm"/></g><path fill="url(#iy9wexd)" transform="scale(-1 1)rotate(-14.867 31.211 73.056)" class="ofkpelbcu"/><path fill="url(#imsvv5c)" transform="scale(-1 1)rotate(-14.867 31.211 73.056)" class="ofkpelbcu"/><path fill="url(#iZCT3re)" transform="scale(-1 1)rotate(-14.867 31.211 73.056)" class="ofkpelbcu"/><path fill="url(#iq7N0uW)" class="fb232rble"/><path fill="url(#izSQ2rb)" class="fb232rble"/><path fill="url(#iQLheqc)" class="fb232rble"/><g filter="url(#i7c5JZd)"><path class="mgm6yzblt"/><path fill="url(#iYZCjpd)" class="t236wobrv"/></g><g filter="url(#iS5uFCd)"><path class="dj_7a8bay"/></g><g filter="url(#i8gDSFc)"><path class="dn71q8n7j"/></g><path fill="url(#il80qwb)" class="padpgu-gg"/><path fill="url(#iDZ9Bpd)" class="padpgu-gg"/><g filter="url(#iHsfIvd)"><path fill="url(#iT2Hv5I)" class="v2fgqhxbh"/></g><path fill="url(#iwsFZ0b)" class="x2ysn_bsq"/><path fill="url(#ipu3Urc)" class="x2ysn_bsq"/><g filter="url(#iwyEBmc)"><path fill="url(#iGhThbc)" class="gxym5ub3o"/><path fill="url(#ivu6j2d)" class="gxym5ub3o"/><path fill="url(#iqH1gob)" class="gxym5ub3o"/><path fill="url(#izM0nSd)" class="gxym5ub3o"/></g><g filter="url(#i8GcNkb)"><path fill="url(#iHo2D1c)" class="va13ti-yp"/><path fill="url(#imrXNVd)" class="va13ti-yp"/><path fill="url(#imKdzLe)" class="va13ti-yp"/></g><path fill="url(#iB9yqDe)" class="gsd8uwblb"/><path fill="url(#iygJDYb)" class="gsd8uwblb"/><path fill="url(#iwvS4ie)" class="gsd8uwblb"/><path clip-rule="evenodd" class="qo7gq5kwd"/><path class="hddzoztyz"/><path fill="url(#ioIlVIc)" class="zsjl9nbnj"/><path fill="url(#iV0rX5b)" class="cfa87fbxu"/><ellipse fill="url(#ipECBte)" transform="scale(-1 1)rotate(24.61 -28.596 -39.175)" class="m1l7k9jve"/><g filter="url(#iNR92Rd)"><path clip-rule="evenodd" class="hzekesbau"/></g><defs><radialGradient id="iVVQcUd" cx="0" cy="0" r="1" gradientTransform="rotate(-130.67 14.067 10.256)scale(5.34656 3.97082)" gradientUnits="userSpaceOnUse"><stop class="lt2_2ybqi"/><stop offset="1" class="bils69brp"/></radialGradient><radialGradient id="iskXoee" cx="0" cy="0" r="1" gradientTransform="matrix(.53125 3.29646 -1.78135 .28708 15.362 21.257)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="bmj_fbbea"/><stop offset="1" class="q_g8mnbhc"/></radialGradient><radialGradient id="iZElbee" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03125 -5.37969 0 18.737 18.929)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="nu9hhfe4u"/><stop offset="1" class="t_vl9fbku"/></radialGradient><radialGradient id="iBP8yDd" cx="0" cy="0" r="1" gradientTransform="matrix(.1094 3.14063 -8.2876 .28869 17.143 19.038)" gradientUnits="userSpaceOnUse"><stop offset=".558" class="gwwxm_bpq"/><stop offset=".971" class="xv9roqx4c"/></radialGradient><radialGradient id="iy9wexd" cx="0" cy="0" r="1" gradientTransform="matrix(1.75062 .2869 -.80955 4.93989 .09 1.583)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="cb_1-p-qf"/><stop offset="1" class="zr3rqsbal"/></radialGradient><radialGradient id="imsvv5c" cx="0" cy="0" r="1" gradientTransform="rotate(117.861 .923 .84)scale(.83385 .74963)" gradientUnits="userSpaceOnUse"><stop class="r7mvh1bxd"/><stop offset="1" class="oz-5xeb0l"/></radialGradient><radialGradient id="iq7N0uW" cx="0" cy="0" r="1" gradientTransform="matrix(3.45312 4 -4.99487 4.31198 13.909 14.554)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="b2o3a7r9l"/><stop offset="1" class="g7ee89odc"/></radialGradient><radialGradient id="izSQ2rb" cx="0" cy="0" r="1" gradientTransform="matrix(2.03122 3.14064 -3.13218 2.02576 14.346 12.679)" gradientUnits="userSpaceOnUse"><stop class="oo0a8g8xe"/><stop offset="1" class="hc1x_wbbe"/></radialGradient><radialGradient id="iQLheqc" cx="0" cy="0" r="1" gradientTransform="matrix(3.73437 .23436 -.4261 6.78981 14.423 16.303)" gradientUnits="userSpaceOnUse"><stop offset=".563" class="brpomvbii"/><stop offset="1" class="lmk5_gb2n"/></radialGradient><radialGradient id="iYZCjpd" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 2.34375 -.8049 -.04293 15.237 16.298)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="fs54pab_v"/><stop offset="1" class="zm5b18b9s"/></radialGradient><radialGradient id="iDZ9Bpd" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 1.04686 -.99542 1.2183 14.789 12.678)" gradientUnits="userSpaceOnUse"><stop class="n6csxrxuy"/><stop offset="1" class="obkbkpctx"/></radialGradient><radialGradient id="iwsFZ0b" cx="0" cy="0" r="1" gradientTransform="rotate(151.587 8.85 7.25)scale(.54183 .76481)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="rcpmccbyc"/><stop offset=".684" class="wdglv_bwm"/></radialGradient><radialGradient id="ipu3Urc" cx="0" cy="0" r="1" gradientTransform="matrix(.12006 -.29152 .4375 .18018 19.68 9.733)" gradientUnits="userSpaceOnUse"><stop class="zkj259b3a"/><stop offset="1" class="iv0p50s_n"/></radialGradient><radialGradient id="ivu6j2d" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 -.04687 .05715 1.0287 16.423 8.713)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="pfu46_y1s"/><stop offset="1" class="ccv6f1brb"/></radialGradient><radialGradient id="iqH1gob" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 2.01562 0 19.32 9.9)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="nkfrpdbdq"/><stop offset="1" class="eqwiy2pxg"/></radialGradient><radialGradient id="izM0nSd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39063 -.60919 0 18.491 8.76)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="c-xbvquvy"/><stop offset="1" class="ksl77bchk"/></radialGradient><radialGradient id="iHo2D1c" cx="0" cy="0" r="1" gradientTransform="matrix(3.4375 3.125 -3.54355 3.8979 14.548 6.05)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="n03tmgbfr"/><stop offset="1" class="a7758ab4t"/></radialGradient><radialGradient id="imrXNVd" cx="0" cy="0" r="1" gradientTransform="matrix(-.39452 2.68273 -1.18513 -.17428 14.655 6.8)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="pmcqb6bbe"/><stop offset="1" class="obdoohpwg"/></radialGradient><radialGradient id="imKdzLe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 -.09374 .18396 -2.94358 19.845 6.666)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="ozwza9bad"/><stop offset="1" class="mok6a1b9k"/></radialGradient><radialGradient id="iB9yqDe" cx="0" cy="0" r="1" gradientTransform="rotate(-163.812 8.935 3.114)scale(.75656 .36927)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="gneqelmmi"/><stop offset="1" class="enl5oqy9k"/></radialGradient><radialGradient id="iygJDYb" cx="0" cy="0" r="1" gradientTransform="rotate(100.843 4.88 11.015)scale(1.20119 1.25169)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="rdgulqvms"/><stop offset="1" class="vmk6x9_kg"/></radialGradient><radialGradient id="ioIlVIc" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 0 0 -.53125 18.786 8.787)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iV0rX5b" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 0 0 -.54102 18.954 8.808)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><filter id="i61J34d" width="7.28" height="8.609" x="10.582" y="20.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2241"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.466667 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_2241" result="effect2_innerShadow_2_2241"/></filter><filter id="ixd8kVd" width="5.734" height="7.279" x="10.657" y="21.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2241" stdDeviation=".25"/></filter><filter id="iQpFiqe" width="11.64" height="10.135" x="12.866" y="18.929" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.490196 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2241"/></filter><filter id="iKJabvb" width="4.352" height="2.364" x="19.803" y="26.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.254902 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2241"/></filter><filter id="ipKjLjc" width="3.579" height="3.542" x="7.416" y="25.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.168627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2241"/></filter><filter id="i7c5JZd" width="6.876" height="3.179" x="15.005" y="15.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.607843 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2241"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.501961 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_2241" result="effect2_innerShadow_2_2241"/></filter><filter id="iS5uFCd" width="1.071" height="1.439" x="20.944" y="18.071" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.54902 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2241"/></filter><filter id="i8gDSFc" width="1.196" height="1.065" x="20.464" y="18.669" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.54902 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2241"/></filter><filter id="iHsfIvd" width="8.168" height="8.42" x="13.862" y="19.415" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2241" stdDeviation=".375"/></filter><filter id="iwyEBmc" width="4.443" height="5.249" x="15.155" y="6.514" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.541176 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2241"/></filter><filter id="i8GcNkb" width="6.391" height="5.479" x="13.74" y="4.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.94902 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2241"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.941176 0 0 0 0 0.74902 0 0 0 0 0.596078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_2241" result="effect2_innerShadow_2_2241"/></filter><filter id="iNR92Rd" width="1.117" height=".648" x="17.877" y="7.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.278431 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2241"/></filter><linearGradient id="iNk50gc" x1="14.8" x2="14.8" y1="18.835" y2="19.366" gradientUnits="userSpaceOnUse"><stop class="fy99v1bac"/><stop offset="1" class="l0bg_dlbj"/></linearGradient><linearGradient id="iAYuCdd" x1="19.675" x2="20.659" y1="28.101" y2="28.101" gradientUnits="userSpaceOnUse"><stop class="jje8gccwz"/><stop offset="1" class="ifze1vbqw"/></linearGradient><linearGradient id="ihastRb" x1="21.112" x2="21.112" y1="28.964" y2="28.593" gradientUnits="userSpaceOnUse"><stop class="k1dl65w8i"/><stop offset="1" class="pqpq_lljy"/></linearGradient><linearGradient id="iKWyxzz" x1="10.649" x2="9.964" y1="26.054" y2="26.718" gradientUnits="userSpaceOnUse"><stop class="olt5ljabw"/><stop offset="1" class="xgk77dt3o"/></linearGradient><linearGradient id="iM1lpZc" x1="8.503" x2="8.718" y1="27.257" y2="27.429" gradientUnits="userSpaceOnUse"><stop offset=".098" class="fwheo7gdw"/><stop offset="1" class="oy9f4cbur"/></linearGradient><linearGradient id="iZCT3re" x1="-.003" x2=".233" y1="1.875" y2="1.869" gradientUnits="userSpaceOnUse"><stop class="ayx8pzyyv"/><stop offset="1" class="r1mf-bcbj"/></linearGradient><linearGradient id="il80qwb" x1="14.82" x2="17.311" y1="15.304" y2="15.382" gradientUnits="userSpaceOnUse"><stop class="ofo46gsuq"/><stop offset="1" class="lq0qk0brb"/></linearGradient><linearGradient id="iT2Hv5I" x1="21.28" x2="14.799" y1="25.851" y2="19.913" gradientUnits="userSpaceOnUse"><stop offset=".552" class="cl3ijcbld"/><stop offset="1" class="v224y-b0w"/></linearGradient><linearGradient id="iGhThbc" x1="16.735" x2="19.598" y1="9.455" y2="9.627" gradientUnits="userSpaceOnUse"><stop class="laomgc3gs"/><stop offset="1" class="eur0hut6l"/></linearGradient><linearGradient id="iwvS4ie" x1="16.702" x2="16.554" y1="8.664" y2="8.676" gradientUnits="userSpaceOnUse"><stop class="qdq-erb7u"/><stop offset="1" class="yfv3nqb2s"/></linearGradient><linearGradient id="ipECBte" x1="-.007" x2=".179" y1=".05" y2=".11" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-kneeling-facing-right-medium-light" /></template>
<style>
.a5y-b-r0a {
  fill: var(--svg-color--968ba1, #968BA1);
  d: path("M22.35 22.132c-.137.575-.807 3.427-1.125 4.781c.573.232 1.39.668 2.067 1.008c.324.163.533.495.443.847a.26.26 0 0 1-.252.196h-3.43a.25.25 0 0 1-.25-.253l.076-7.169c-1.787.442-3.937.808-5.747.262c-1.2-.363-1.266-1.817-1.266-2.875l7.61.078a2.726 2.726 0 0 1 1.874 3.125");
}

.a7758ab4t {
  stop-color: var(--svg-color--ffdaa9, #FFDAA9);
}

.ayx8pzyyv {
  stop-color: var(--svg-color--d59984, #D59984);
}

.b2o3a7r9l {
  stop-color: var(--svg-color--45a7f8, #45A7F8);
}

.bils69brp {
  stop-color: var(--svg-color--a49dac, #A49DAC);
  stop-opacity: 0;
}

.bjvd-sb3y {
  fill: var(--svg-color--97919f, #97919F);
  d: path("M16.855 26.64c.05-1.838-.195-4.492-.32-5.57l-3.484-.696c.554 3.344 1.328 5.508 1.687 6.266c-1.062-.266-2.578-.172-3.765-.117l-.391 1.515c1.234.125 3.34.523 3.844.648c.562.141 2.371.086 2.43-2.046");
}

.bmj_fbbea {
  stop-color: var(--svg-color--6a5a7a, #6A5A7A);
}

.brpomvbii {
  stop-color: var(--svg-color--4b77af, #4B77AF);
  stop-opacity: 0;
}

.c-xbvquvy {
  stop-color: var(--svg-color--e6aa86, #E6AA86);
}

.cb_1-p-qf {
  stop-color: var(--svg-color--d08a75, #D08A75);
}

.ccv6f1brb {
  stop-color: var(--svg-color--dd9c79, #DD9C79);
  stop-opacity: 0;
}

.cfa87fbxu {
  d: path("m18.654 8.808l-.005-.072c0-.185.08-.336.176-.336c.097 0 .176.15.176.336l-.004.072z");
}

.cl3ijcbld {
  stop-color: var(--svg-color--a098a8, #A098A8);
}

.dj_7a8bay {
  fill: var(--svg-color--cd9789, #CD9789);
  d: path("m20.987 18.17l-.043.634c.233.181.452.427.603.608a.27.27 0 0 0 .345.059c.118-.073.161-.224.085-.339a3.6 3.6 0 0 0-.99-.961");
}

.dn71q8n7j {
  fill: var(--svg-color--cd9789, #CD9789);
  d: path("M21.034 18.769c-.325-.003-.516.178-.57.27c.271.143.499.375.65.566c.1.124.278.17.413.086a.266.266 0 0 0 .079-.39c-.257-.329-.48-.49-.572-.532");
}

.dqeezuryw {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M14.378 21.616c.138.941.573 3.264 1.239 5.338a.5.5 0 0 1-.152.535a.55.55 0 0 1-.538.086c-.689-.244-2.053-.526-3.737-.302");
}

.enl5oqy9k {
  stop-color: var(--svg-color--e1a587, #E1A587);
}

.eqwiy2pxg {
  stop-color: var(--svg-color--fbbca1, #FBBCA1);
  stop-opacity: 0;
}

.eur0hut6l {
  stop-color: var(--svg-color--e3ab8e, #E3AB8E);
}

.fb232rble {
  d: path("M17.909 14.151c.162 1.15.094 2.637-.016 3.528v1.289h-5.031c.055-2.063.578-4.728 1.367-6.047c.664-1.11 1.422-1.176 2.055-.957c.605.183 1.422.75 1.625 2.187");
}

.fs54pab_v {
  stop-color: var(--svg-color--e4ad98, #E4AD98);
}

.ft5dv1b6b {
  fill: none;
}

.fwheo7gdw {
  stop-color: var(--svg-color--60608e, #60608E);
}

.fy99v1bac {
  stop-color: var(--svg-color--897694, #897694);
}

.g7ee89odc {
  stop-color: var(--svg-color--3370b9, #3370B9);
}

.gneqelmmi {
  stop-color: var(--svg-color--ebb497, #EBB497);
}

.gsd8uwblb {
  d: path("m16.8 9.469l-.2-1.44a.727.727 0 0 0 .2 1.44");
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gwwxm_bpq {
  stop-color: var(--svg-color--857297, #857297);
  stop-opacity: 0;
}

.gxym5ub3o {
  d: path("M19.57 8.015c-.039-.802-.298-1.188-.42-1.3h-3.733l-.062 3.163c.866 2.122 3.511 2.213 3.906 1.445c.395-.767.354-2.38.309-3.308");
}

.hc1x_wbbe {
  stop-color: var(--svg-color--4aa9ee, #4AA9EE);
  stop-opacity: 0;
}

.hddzoztyz {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.064 8.808h-.989c0-.391.221-.709.494-.709s.495.318.495.71");
}

.hzekesbau {
  fill: var(--svg-color--945f3d, #945F3D);
  fill-rule: evenodd;
  d: path("M18.294 7.951c.147-.105.363-.11.5-.11a.2.2 0 0 0 0-.4h-.01c-.128 0-.463-.001-.723.185a.2.2 0 1 0 .233.325");
}

.hzh6l3bzz {
  d: path("M22.35 22.132c-.137.575-.807 3.427-1.125 4.781c.573.232 1.39.668 2.067 1.008c.324.163.533.495.443.847a.26.26 0 0 1-.252.196h-3.43a.25.25 0 0 1-.25-.253l.076-7.169c-1.787.442-3.937.808-5.747.262c-1.2-.363-1.266-1.817-1.266-2.875l7.61.078a2.726 2.726 0 0 1 1.874 3.125");
}

.ifze1vbqw {
  stop-color: var(--svg-color--605f91, #605F91);
  stop-opacity: 0;
}

.imnkx9bdk {
  d: path("M16.855 26.64c.05-1.838-.195-4.492-.32-5.57l-3.484-.696c.554 3.344 1.328 5.508 1.687 6.266c-1.062-.266-2.578-.172-3.765-.117l-.391 1.515c1.234.125 3.34.523 3.844.648c.562.141 2.371.086 2.43-2.046");
}

.iv0p50s_n {
  stop-color: var(--svg-color--f0aa89, #F0AA89);
  stop-opacity: 0;
}

.jje8gccwz {
  stop-color: var(--svg-color--605f91, #605F91);
}

.k1dl65w8i {
  stop-color: var(--svg-color--3f2d7e, #3F2D7E);
}

.ksl77bchk {
  stop-color: var(--svg-color--e6aa86, #E6AA86);
  stop-opacity: 0;
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l0bg_dlbj {
  stop-color: var(--svg-color--897694, #897694);
  stop-opacity: 0;
}

.laomgc3gs {
  stop-color: var(--svg-color--db9f84, #DB9F84);
}

.lmk5_gb2n {
  stop-color: var(--svg-color--4b77af, #4B77AF);
}

.lq0qk0brb {
  stop-color: var(--svg-color--3a78c3, #3A78C3);
}

.lt2_2ybqi {
  stop-color: var(--svg-color--a49dac, #A49DAC);
}

.lz9t8o9wv {
  d: path("M19.879 21.545v-.003c-1.787.442-3.938.808-5.748.262c-1.2-.363-1.265-1.817-1.265-2.875l7.61.078q.4.138.701.336z");
}

.m1l7k9jve {
  cx: 0.064px;
  cy: 0.088px;
  rx: 0.064px;
  ry: 0.088px;
}

.m8_3k6boh {
  fill: var(--svg-color--55538a, #55538A);
  d: path("M19.816 27.542a6.3 6.3 0 0 1 1.413-.643l-.004.014c.433.175 1.005.467 1.55.746l.517.262c.324.163.533.495.443.847a.26.26 0 0 1-.252.196h-3.43a.25.25 0 0 1-.25-.253z");
}

.mgm6yzblt {
  fill: var(--svg-color--d8a490, #D8A490);
  d: path("m16.901 17.1l.04-.78l-1.891-.126c-.047.664-.118 1.594.148 1.985c.266.39.765.858 2.2.945a42 42 0 0 0 3.269.031v-.18h.672l.34-.214c.039-.192-.39-.568-.79-.711c-1.253-.45-2.96-.82-3.988-.95");
}

.mok6a1b9k {
  stop-color: var(--svg-color--ffe8b5, #FFE8B5);
  stop-opacity: 0;
}

.n03tmgbfr {
  stop-color: var(--svg-color--ffe0af, #FFE0AF);
}

.n6csxrxuy {
  stop-color: var(--svg-color--4ba6ed, #4BA6ED);
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.nkfrpdbdq {
  stop-color: var(--svg-color--fbbca1, #FBBCA1);
}

.nu9hhfe4u {
  stop-color: var(--svg-color--774e55, #774E55);
}

.obdoohpwg {
  stop-color: var(--svg-color--fff4bb, #FFF4BB);
  stop-opacity: 0;
}

.obkbkpctx {
  stop-color: var(--svg-color--4ba6ed, #4BA6ED);
  stop-opacity: 0;
}

.ofkpelbcu {
  d: path("M0 0h1.976v2.198H0z");
}

.ofo46gsuq {
  stop-color: var(--svg-color--439ff0, #439FF0);
}

.olt5ljabw {
  stop-color: var(--svg-color--3f3e62, #3F3E62);
}

.oo0a8g8xe {
  stop-color: var(--svg-color--4aa9ee, #4AA9EE);
}

.oy9f4cbur {
  stop-color: var(--svg-color--60608e, #60608E);
  stop-opacity: 0;
}

.oz-5xeb0l {
  stop-color: var(--svg-color--ce9074, #CE9074);
  stop-opacity: 0;
}

.ozwza9bad {
  stop-color: var(--svg-color--ffe8b5, #FFE8B5);
}

.padpgu-gg {
  d: path("M17.31 13.636a1.261 1.261 0 0 0-2.52-.119l-.155 2.775l2.567.152z");
}

.pfu46_y1s {
  stop-color: var(--svg-color--dd9c79, #DD9C79);
}

.pmcqb6bbe {
  stop-color: var(--svg-color--fff4bb, #FFF4BB);
}

.pqpq_lljy {
  stop-color: var(--svg-color--3f2d7e, #3F2D7E);
  stop-opacity: 0;
}

.q_g8mnbhc {
  stop-color: var(--svg-color--766b81, #766B81);
  stop-opacity: 0;
}

.q2ucym9nt {
  d: path("M19.816 27.542a6.3 6.3 0 0 1 1.413-.643l-.004.014c.433.175 1.005.467 1.55.746l.517.262c.324.163.533.495.443.847a.26.26 0 0 1-.252.196h-3.43a.25.25 0 0 1-.25-.253z");
}

.qdq-erb7u {
  stop-color: var(--svg-color--e5a88d, #E5A88D);
}

.qo7gq5kwd {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M18.318 9.922a.125.125 0 0 0 .002.177c.238.233.582.293.692.304a.125.125 0 0 0 .025-.248c-.093-.01-.366-.062-.542-.235a.125.125 0 0 0-.177.002");
}

.r1mf-bcbj {
  stop-color: var(--svg-color--d59984, #D59984);
  stop-opacity: 0;
}

.r7mvh1bxd {
  stop-color: var(--svg-color--ce9074, #CE9074);
}

.rcpmccbyc {
  stop-color: var(--svg-color--fec19d, #FEC19D);
}

.rdgulqvms {
  stop-color: var(--svg-color--e1a38b, #E1A38B);
  stop-opacity: 0;
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t_vl9fbku {
  stop-color: var(--svg-color--8f7c7f, #8F7C7F);
  stop-opacity: 0;
}

.t236wobrv {
  d: path("m16.901 17.1l.04-.78l-1.891-.126c-.047.664-.118 1.594.148 1.985c.266.39.765.858 2.2.945a42 42 0 0 0 3.269.031v-.18h.672l.34-.214c.039-.192-.39-.568-.79-.711c-1.253-.45-2.96-.82-3.988-.95");
}

.t63k-8bgz {
  fill: var(--svg-color--443c7f, #443C7F);
  d: path("m10.11 25.788l.885.75l-.406 1.5c-.391.198-1.35.653-2.063.89c-.547.183-.887.06-1.056-.083c-.078-.065-.066-.178 0-.257l2.285-2.769a.25.25 0 0 1 .355-.031");
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.v224y-b0w {
  stop-color: var(--svg-color--a098a8, #A098A8);
  stop-opacity: 0;
}

.v2fgqhxbh {
  d: path("m21.268 21.468l-.656 5.492l-.313.125l.43-5.73a.487.487 0 0 0-.481-.528c-.926-.006-3.848 0-4.542 0c-.813 0-1.094-.273-1.094-.648c1.193-.01 4.676-.025 5.664 0s1.039.862.992 1.289");
}

.va13ti-yp {
  d: path("M18.93 7.261c.657 0 .97-.37 1-.835c0-.657-.5-.796-.694-.817c-.22-.023-.305-.047-.61-.262a.9.9 0 0 0-.91-.097c-.148.07-.477.105-.71.035c-.392-.117-.696-.113-.997.117c-.209.16-.363.16-.613.16c-.344 0-.636.154-.856.32c-.657.498-.582 2.208-.257 3.169c.31.919.777 1.027 1.167.992c.47-.043.59-.399.66-.696c.057-.237.201-.99.266-1.237c.136-.063.431-.086.531-.474c.1-.387.493-.431.758-.406c.162.016.61.031 1.266.031");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vmk6x9_kg {
  stop-color: var(--svg-color--dd9a7e, #DD9A7E);
}

.w4enui6bm {
  d: path("m10.11 25.788l.885.75l-.406 1.5c-.391.198-1.35.653-2.063.89c-.547.183-.887.06-1.056-.083c-.078-.065-.066-.178 0-.257l2.285-2.769a.25.25 0 0 1 .355-.031");
}

.wdglv_bwm {
  stop-color: var(--svg-color--f2b08a, #F2B08A);
}

.x2ysn_bsq {
  d: path("M19.794 8.978a1 1 0 0 1-.258-.457h-.18v1.125c.215.137.522.115.614-.09c.078-.175.02-.394-.176-.578");
}

.xgk77dt3o {
  stop-color: var(--svg-color--3f3e62, #3F3E62);
  stop-opacity: 0;
}

.xv9roqx4c {
  stop-color: var(--svg-color--7e5e9a, #7E5E9A);
}

.yfv3nqb2s {
  stop-color: var(--svg-color--e4a88b, #E4A88B);
  stop-opacity: 0;
}

.zkj259b3a {
  stop-color: var(--svg-color--f0aa89, #F0AA89);
}

.zm5b18b9s {
  stop-color: var(--svg-color--e4ad98, #E4AD98);
  stop-opacity: 0;
}

.zr3rqsbal {
  stop-color: var(--svg-color--e5ab92, #E5AB92);
}

.zsjl9nbnj {
  d: path("M18.458 8.808v-.004c0-.32.137-.58.307-.58s.306.26.306.58v.004z");
}

</style>
