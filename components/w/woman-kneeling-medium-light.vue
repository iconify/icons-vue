<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i6Livpc)"><path class="y4wyj4zjh"/></g><g filter="url(#i7GOwDe)"><path stroke="url(#iGgBzCc)" class="ysczdsbzf"/></g><path fill="url(#iqkw6tb)" class="vp-i5ufoh"/><g filter="url(#idPHk8c)"><path class="oa71k_21j"/></g><path fill="url(#iXr0Zpc)" class="j7qpbyb-r"/><path fill="url(#i5bTvre)" class="j7qpbyb-r"/><path fill="url(#iuXB9Zb)" class="z30nzhb6f"/><g filter="url(#ipqLemb)"><path class="s1byoub3m"/><path fill="url(#iIB3Sfe)" class="km8o6h6gs"/><path fill="url(#ifZW4Wc)" class="km8o6h6gs"/></g><g filter="url(#iaDrcZA)"><path class="j6p_0hthu"/><path fill="url(#inywIwb)" class="ywfpue-3p"/><path fill="url(#ilwQO3c)" class="ywfpue-3p"/></g><path fill="url(#iPFPtwH)" transform="rotate(-14.867 13.886 10.454)" class="ox_st0bbx"/><path fill="url(#ikIHOQb)" transform="rotate(-14.867 13.886 10.454)" class="ox_st0bbx"/><path fill="url(#ixymiKc)" class="apo7xsboj"/><path fill="url(#i3FNi9c)" class="apo7xsboj"/><path fill="url(#iia4Jid)" class="apo7xsboj"/><path fill="url(#i3KjAPe)" class="apo7xsboj"/><g filter="url(#iw1x3yd)"><path class="sf2q7797h"/><path fill="url(#iTjzyqd)" class="szm_irbgj"/></g><g filter="url(#ir26OQb)"><path class="k8_m3oaqa"/></g><g filter="url(#i9LNKKd)"><path class="o9au8s52j"/></g><path fill="url(#i1fc6sc)" class="cv4locc3a"/><path fill="url(#iFcq2mc)" class="cv4locc3a"/><path fill="url(#iIo4leS)" class="cv4locc3a"/><path fill="url(#iZrw4vb)" class="cv4locc3a"/><g filter="url(#i8dbrme)"><path fill="url(#iupjd7b)" class="awg78lbzn"/></g><path fill="url(#iblBrOc)" class="hwlh1kymk"/><g filter="url(#iLyq0hc)"><path fill="url(#i6nYbOc)" class="vtcy4jgmq"/><path fill="url(#izCKx1b)" class="vtcy4jgmq"/><path fill="url(#is86wUd)" class="vtcy4jgmq"/><path fill="url(#iaJlQ3c)" class="vtcy4jgmq"/></g><g filter="url(#irQd3Ed)"><path class="m_byo2bmz"/><path fill="url(#im1Cslc)" class="i14panb0f"/></g><path fill="url(#iQaDMud)" class="i14panb0f"/><path fill="url(#idBUqQe)" class="y0t-xbb0q"/><path fill="url(#ibcUNEe)" class="y0t-xbb0q"/><path fill="url(#i2JmlOc)" class="y0t-xbb0q"/><path clip-rule="evenodd" class="dtcil2tov"/><g filter="url(#iSx6pSN)"><path clip-rule="evenodd" class="gb0ei9-2m"/></g><path class="luodubbnn"/><path class="dctv-acks"/><path fill="url(#iTQDe0h)" class="hoq7s7bgo"/><path fill="url(#ir9h5Ju)" class="oag-gp42p"/><ellipse fill="url(#iBEtbSg)" transform="rotate(24.61 12.71 8.395)" class="vebuthb8b"/><defs><radialGradient id="iGgBzCc" cx="0" cy="0" r="1" gradientTransform="matrix(3.48437 -4.05522 3.01176 2.5878 16.13 27.609)" gradientUnits="userSpaceOnUse"><stop class="lt2_2ybqi"/><stop offset="1" class="bils69brp"/></radialGradient><radialGradient id="iqkw6tb" cx="0" cy="0" r="1" gradientTransform="matrix(-.53125 3.29646 -1.78135 -.28708 16.225 21.256)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="bmj_fbbea"/><stop offset="1" class="q_g8mnbhc"/></radialGradient><radialGradient id="i5bTvre" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03125 -5.37969 0 12.849 18.929)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="nu9hhfe4u"/><stop offset="1" class="t_vl9fbku"/></radialGradient><radialGradient id="iuXB9Zb" cx="0" cy="0" r="1" gradientTransform="matrix(-.10938 3.14063 -8.2876 -.28863 14.443 19.038)" gradientUnits="userSpaceOnUse"><stop offset=".558" class="gwwxm_bpq"/><stop offset=".971" class="xv9roqx4c"/></radialGradient><radialGradient id="iPFPtwH" cx="0" cy="0" r="1" gradientTransform="matrix(1.77898 -.97701 .89303 1.62605 13.847 12.73)" gradientUnits="userSpaceOnUse"><stop offset=".535" class="yfxz81b1q"/><stop offset="1" class="he8x0vbdp"/></radialGradient><radialGradient id="ixymiKc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.4531 4.00002 -4.9949 -4.31194 17.677 14.554)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="ai9smcbyp"/><stop offset=".849" class="j-pea3b4d"/></radialGradient><radialGradient id="i3FNi9c" cx="0" cy="0" r="1" gradientTransform="rotate(120.981 4.328 11.534)scale(2.40218 1.79199)" gradientUnits="userSpaceOnUse"><stop class="svuvwyb0s"/><stop offset="1" class="dlkt90brn"/></radialGradient><radialGradient id="iia4Jid" cx="0" cy="0" r="1" gradientTransform="matrix(-3.73437 .23436 -.4261 -6.78981 17.161 16.304)" gradientUnits="userSpaceOnUse"><stop offset=".723" class="z_p65vbje"/><stop offset="1" class="ql1m53bju"/></radialGradient><radialGradient id="i3KjAPe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.00267 -6.91786 5.20733 -.75475 16.152 18.463)" gradientUnits="userSpaceOnUse"><stop offset=".86" class="pw_9qjb5p"/><stop offset=".968" class="zieydyb7s"/></radialGradient><radialGradient id="iTjzyqd" cx="0" cy="0" r="1" gradientTransform="rotate(86.947 -.42 16.771)scale(2.34708 .80604)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="fs54pab_v"/><stop offset="1" class="zm5b18b9s"/></radialGradient><radialGradient id="iFcq2mc" cx="0" cy="0" r="1" gradientTransform="matrix(-.83488 1.0625 -1.21448 -.9543 16.448 12.663)" gradientUnits="userSpaceOnUse"><stop class="ove-epbrr"/><stop offset="1" class="h87azyork"/></radialGradient><radialGradient id="iIo4leS" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71876 .54686 -1.0229 -5.08537 16.744 15.898)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="bd3uesbch"/><stop offset=".909" class="f-z_jdbvz"/></radialGradient><radialGradient id="iZrw4vb" cx="0" cy="0" r="1" gradientTransform="matrix(-.18857 -3.34375 2.69988 -.15226 15.613 15.61)" gradientUnits="userSpaceOnUse"><stop offset=".868" class="q1w9isbqn"/><stop offset="1" class="yes5_6oun"/></radialGradient><radialGradient id="iblBrOc" cx="0" cy="0" r="1" gradientTransform="matrix(.48867 .2693 -.38397 .69672 11.496 9.328)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="tpd8yob6x"/><stop offset=".684" class="x-p0yyc_l"/></radialGradient><radialGradient id="izCKx1b" cx="0" cy="0" r="1" gradientTransform="matrix(-.84375 -.04688 .05715 -1.0287 15.176 8.65)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="pfu46_y1s"/><stop offset="1" class="ccv6f1brb"/></radialGradient><radialGradient id="is86wUd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 2.01562 0 12.28 9.838)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="fba3w535x"/><stop offset="1" class="qh_uvdsfh"/></radialGradient><radialGradient id="iaJlQ3c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39063 -.60919 0 13.108 8.698)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="c-xbvquvy"/><stop offset="1" class="ksl77bchk"/></radialGradient><radialGradient id="im1Cslc" cx="0" cy="0" r="1" gradientTransform="matrix(1.53488 -.43168 .9251 3.28923 12.053 6.416)" gradientUnits="userSpaceOnUse"><stop class="k_urnmdao"/><stop offset="1" class="w7r1zi1yh"/></radialGradient><radialGradient id="iQaDMud" cx="0" cy="0" r="1" gradientTransform="rotate(69.974 3.394 13.64)scale(6.69193 5.21956)" gradientUnits="userSpaceOnUse"><stop offset=".715" class="bk38-ufuu"/><stop offset=".967" class="cu7nkxbal"/></radialGradient><radialGradient id="idBUqQe" cx="0" cy="0" r="1" gradientTransform="matrix(.72656 -.21094 .10296 .35463 14.854 8.534)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="gneqelmmi"/><stop offset="1" class="enl5oqy9k"/></radialGradient><radialGradient id="ibcUNEe" cx="0" cy="0" r="1" gradientTransform="matrix(.22596 1.17975 -1.22934 .23546 14.885 8.233)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="rdgulqvms"/><stop offset="1" class="vmk6x9_kg"/></radialGradient><radialGradient id="iTQDe0h" cx="0" cy="0" r="1" gradientTransform="matrix(.27344 0 0 .53125 12.813 8.725)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="ir9h5Ju" cx="0" cy="0" r="1" gradientTransform="matrix(.25 0 0 .54102 12.645 8.747)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><filter id="i6Livpc" width="7.28" height="8.609" x="14.724" y="20.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_253"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.466667 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_253" result="effect2_innerShadow_4002_253"/></filter><filter id="i7GOwDe" width="5.734" height="7.279" x="15.195" y="21.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_253" stdDeviation=".25"/></filter><filter id="idPHk8c" width="11.64" height="10.135" x="7.83" y="18.929" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.490196 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_253"/></filter><filter id="ipqLemb" width="4.352" height="2.364" x="7.83" y="26.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.254902 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_253"/></filter><filter id="iaDrcZA" width="3.579" height="3.542" x="20.591" y="25.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.168627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_253"/></filter><filter id="iw1x3yd" width="6.876" height="3.179" x="9.905" y="15.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.607843 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_253"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.501961 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_253" result="effect2_innerShadow_4002_253"/></filter><filter id="ir26OQb" width="1.171" height="1.439" x="9.571" y="18.071" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.545098 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_253"/></filter><filter id="i9LNKKd" width="1.196" height="1.065" x="9.926" y="18.669" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.54902 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_253"/></filter><filter id="i8dbrme" width="8.168" height="8.42" x="9.556" y="19.415" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_253" stdDeviation=".375"/></filter><filter id="iLyq0hc" width="4.443" height="5.249" x="11.802" y="6.452" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.521569 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_253"/></filter><filter id="irQd3Ed" width="6.813" height="7.403" x="11.44" y="4.791" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.972549 0 0 0 0 0.737255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_253"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.788235 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_253" result="effect2_innerShadow_4002_253"/></filter><filter id="iSx6pSN" width="1.013" height=".568" x="12.563" y="7.396" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_253"/></filter><linearGradient id="iXr0Zpc" x1="16.786" x2="16.786" y1="18.835" y2="19.366" gradientUnits="userSpaceOnUse"><stop class="fy99v1bac"/><stop offset="1" class="l0bg_dlbj"/></linearGradient><linearGradient id="iIB3Sfe" x1="11.911" x2="10.927" y1="28.101" y2="28.101" gradientUnits="userSpaceOnUse"><stop class="jje8gccwz"/><stop offset="1" class="ifze1vbqw"/></linearGradient><linearGradient id="ifZW4Wc" x1="10.474" x2="10.474" y1="28.964" y2="28.593" gradientUnits="userSpaceOnUse"><stop class="k1dl65w8i"/><stop offset="1" class="pqpq_lljy"/></linearGradient><linearGradient id="inywIwb" x1="20.936" x2="21.622" y1="26.054" y2="26.718" gradientUnits="userSpaceOnUse"><stop class="olt5ljabw"/><stop offset="1" class="xgk77dt3o"/></linearGradient><linearGradient id="ilwQO3c" x1="23.083" x2="22.868" y1="27.257" y2="27.429" gradientUnits="userSpaceOnUse"><stop offset=".098" class="fwheo7gdw"/><stop offset="1" class="oy9f4cbur"/></linearGradient><linearGradient id="ikIHOQb" x1="13.874" x2="14.253" y1="12.262" y2="12.233" gradientUnits="userSpaceOnUse"><stop class="tj9-bfwwp"/><stop offset="1" class="h9ba4hxgi"/></linearGradient><linearGradient id="i1fc6sc" x1="16.95" x2="14.885" y1="15.132" y2="15.226" gradientUnits="userSpaceOnUse"><stop class="d30p-0b3w"/><stop offset="1" class="cm74u7bos"/></linearGradient><linearGradient id="iupjd7b" x1="10.306" x2="16.786" y1="25.851" y2="19.913" gradientUnits="userSpaceOnUse"><stop offset=".552" class="cl3ijcbld"/><stop offset="1" class="v224y-b0w"/></linearGradient><linearGradient id="i6nYbOc" x1="14.864" x2="12.002" y1="9.393" y2="9.565" gradientUnits="userSpaceOnUse"><stop class="r-abwq5sm"/><stop offset="1" class="jebkqobzf"/></linearGradient><linearGradient id="i2JmlOc" x1="14.799" x2="14.948" y1="8.602" y2="8.614" gradientUnits="userSpaceOnUse"><stop class="qdq-erb7u"/><stop offset="1" class="yfv3nqb2s"/></linearGradient><linearGradient id="iBEtbSg" x1="12.638" x2="12.825" y1="8.357" y2="8.418" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-kneeling-medium-light" /></template>
<style>
.ai9smcbyp {
  stop-color: var(--svg-color--8672be, #8672BE);
}

.apo7xsboj {
  d: path("M13.677 14.151c-.163 1.15-.094 2.637.016 3.528v1.289h5.03c-.054-2.063-.577-4.728-1.366-6.047c-.665-1.11-1.422-1.176-2.055-.957c-.606.183-1.422.75-1.625 2.187");
}

.awg78lbzn {
  d: path("m10.318 21.468l.656 5.492l.312.125l-.43-5.73a.487.487 0 0 1 .482-.528c.926-.006 3.848 0 4.542 0c.812 0 1.094-.273 1.094-.648c-1.193-.01-4.677-.025-5.664 0s-1.04.862-.992 1.289");
}

.bd3uesbch {
  stop-color: var(--svg-color--79699e, #79699E);
  stop-opacity: 0;
}

.bils69brp {
  stop-color: var(--svg-color--a49dac, #A49DAC);
  stop-opacity: 0;
}

.bk38-ufuu {
  stop-color: var(--svg-color--f0c9a1, #F0C9A1);
  stop-opacity: 0;
}

.bmj_fbbea {
  stop-color: var(--svg-color--6a5a7a, #6A5A7A);
}

.c-xbvquvy {
  stop-color: var(--svg-color--e6aa86, #E6AA86);
}

.ccv6f1brb {
  stop-color: var(--svg-color--dd9c79, #DD9C79);
  stop-opacity: 0;
}

.cl3ijcbld {
  stop-color: var(--svg-color--a098a8, #A098A8);
}

.cm74u7bos {
  stop-color: var(--svg-color--725aaa, #725AAA);
}

.cu7nkxbal {
  stop-color: var(--svg-color--c9a28c, #C9A28C);
}

.cv4locc3a {
  d: path("M14.276 13.636a1.261 1.261 0 0 1 2.519-.119l.155 2.775l-2.566.152z");
}

.d30p-0b3w {
  stop-color: var(--svg-color--8f77c9, #8F77C9);
}

.dctv-acks {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.536 8.747h.988c0-.392-.221-.71-.494-.71s-.494.318-.494.71");
}

.dlkt90brn {
  stop-color: var(--svg-color--9c83d3, #9C83D3);
  stop-opacity: 0;
}

.dtcil2tov {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M13.281 9.86a.125.125 0 0 1-.002.177c-.238.234-.582.293-.691.305a.125.125 0 1 1-.026-.25c.094-.009.366-.06.542-.233a.125.125 0 0 1 .177.001");
}

.enl5oqy9k {
  stop-color: var(--svg-color--e1a587, #E1A587);
}

.f-z_jdbvz {
  stop-color: var(--svg-color--79699e, #79699E);
}

.fba3w535x {
  stop-color: var(--svg-color--ecb294, #ECB294);
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

.gb0ei9-2m {
  fill: var(--svg-color--915d37, #915D37);
  fill-rule: evenodd;
  d: path("M13.049 7.714a.8.8 0 0 0-.217-.016a.15.15 0 1 1-.038-.298c.071-.008.187-.006.313.02c.128.025.278.076.409.173a.15.15 0 1 1-.179.241a.7.7 0 0 0-.288-.12");
}

.gneqelmmi {
  stop-color: var(--svg-color--ebb497, #EBB497);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gwwxm_bpq {
  stop-color: var(--svg-color--857297, #857297);
  stop-opacity: 0;
}

.h87azyork {
  stop-color: var(--svg-color--8366c0, #8366C0);
  stop-opacity: 0;
}

.h9ba4hxgi {
  stop-color: var(--svg-color--dca48d, #DCA48D);
  stop-opacity: 0;
}

.he8x0vbdp {
  stop-color: var(--svg-color--9e6051, #9E6051);
}

.hoq7s7bgo {
  d: path("M13.141 8.747v-.004c0-.32-.137-.58-.306-.58c-.17 0-.307.26-.307.58v.004z");
}

.hwlh1kymk {
  d: path("M11.792 8.89c.156-.147.23-.405.25-.496l.2.065v1.125c-.214.137-.538.081-.63-.124c-.078-.176-.015-.387.18-.57");
}

.i14panb0f {
  d: path("M11.91 6.606c-.172-.41.016-.844.113-.992c.367-.672 1.128-.716 1.566-.524c.516.227.67.347 1.504.11c.837-.239 1.868-.13 2.407.84c.539.968-.047 2.058.086 2.652c.132.594.512.652.652 1.34c.117.953-.473 1.574-.996 1.714c-.524.141-1.602 0-1.953-.875c-.575-1.431-.184-2.109-.31-2.828c-.124-.718-.554-.921-1.335-.765c-.92.184-1.506-.126-1.734-.672");
}

.ifze1vbqw {
  stop-color: var(--svg-color--605f91, #605F91);
  stop-opacity: 0;
}

.j-pea3b4d {
  stop-color: var(--svg-color--7059a7, #7059A7);
}

.j6p_0hthu {
  fill: var(--svg-color--443c7f, #443C7F);
  d: path("m21.476 25.788l-.885.75l.406 1.5c.39.198 1.35.653 2.063.89c.547.183.887.06 1.056-.083c.078-.065.066-.178 0-.257l-2.285-2.769a.25.25 0 0 0-.355-.031");
}

.j7qpbyb-r {
  d: path("M9.236 22.132c.137.575.807 3.427 1.125 4.781c-.573.232-1.39.668-2.067 1.008c-.324.163-.533.495-.443.847a.26.26 0 0 0 .252.196h3.43a.25.25 0 0 0 .25-.253l-.076-7.169c1.787.442 3.937.808 5.747.262c1.2-.363 1.266-1.817 1.266-2.875l-7.61.078a2.726 2.726 0 0 0-1.874 3.125");
}

.jebkqobzf {
  stop-color: var(--svg-color--d39c87, #D39C87);
}

.jje8gccwz {
  stop-color: var(--svg-color--605f91, #605F91);
}

.k_urnmdao {
  stop-color: var(--svg-color--ffecb8, #FFECB8);
}

.k1dl65w8i {
  stop-color: var(--svg-color--3f2d7e, #3F2D7E);
}

.k8_m3oaqa {
  fill: var(--svg-color--ce9982, #CE9982);
  d: path("m10.599 18.17l.043.634a4.3 4.3 0 0 0-.603.608a.27.27 0 0 1-.346.059c-.117-.073-.16-.224-.085-.339c.312-.472.795-.844.99-.961");
}

.km8o6h6gs {
  d: path("M11.77 27.542a6.3 6.3 0 0 0-1.413-.643l.004.014c-.433.175-1.005.467-1.55.746l-.517.262c-.324.163-.533.495-.443.847a.26.26 0 0 0 .252.196h3.43a.25.25 0 0 0 .25-.253z");
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

.lt2_2ybqi {
  stop-color: var(--svg-color--a49dac, #A49DAC);
}

.luodubbnn {
  fill: var(--svg-color--2f2c2d, #2F2C2D);
  d: path("M13.561 8.236c-.131-.132-.349-.162-.441-.16l.302.466c.147-.008.303-.143.14-.306");
}

.m_byo2bmz {
  fill: var(--svg-color--ffe0af, #FFE0AF);
  d: path("M11.91 6.606c-.172-.41.016-.844.113-.992c.367-.672 1.128-.716 1.566-.524c.516.227.67.347 1.504.11c.837-.239 1.868-.13 2.407.84c.539.968-.047 2.058.086 2.652c.132.594.512.652.652 1.34c.117.953-.473 1.574-.996 1.714c-.524.141-1.602 0-1.953-.875c-.575-1.431-.184-2.109-.31-2.828c-.124-.718-.554-.921-1.335-.765c-.92.184-1.506-.126-1.734-.672");
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.nu9hhfe4u {
  stop-color: var(--svg-color--774e55, #774E55);
}

.o9au8s52j {
  fill: var(--svg-color--cd9789, #CD9789);
  d: path("M10.552 18.769c.325-.003.516.178.57.27a2.2 2.2 0 0 0-.65.566c-.1.124-.278.17-.413.086a.266.266 0 0 1-.079-.39c.257-.329.48-.49.572-.532");
}

.oa71k_21j {
  fill: var(--svg-color--968ba1, #968BA1);
  d: path("M9.236 22.132c.137.575.807 3.427 1.125 4.781c-.573.232-1.39.668-2.067 1.008c-.324.163-.533.495-.443.847a.26.26 0 0 0 .252.196h3.43a.25.25 0 0 0 .25-.253l-.076-7.169c1.787.442 3.937.808 5.747.262c1.2-.363 1.266-1.817 1.266-2.875l-7.61.078a2.726 2.726 0 0 0-1.874 3.125");
}

.oag-gp42p {
  d: path("m12.946 8.747l.004-.073c0-.185-.079-.336-.176-.336s-.176.15-.176.336q0 .038.004.073z");
}

.olt5ljabw {
  stop-color: var(--svg-color--3f3e62, #3F3E62);
}

.ove-epbrr {
  stop-color: var(--svg-color--9d84d5, #9D84D5);
}

.ox_st0bbx {
  d: path("M13.886 10.454h1.976v2.198h-1.976z");
}

.oy9f4cbur {
  stop-color: var(--svg-color--60608e, #60608E);
  stop-opacity: 0;
}

.pfu46_y1s {
  stop-color: var(--svg-color--dd9c79, #DD9C79);
}

.pqpq_lljy {
  stop-color: var(--svg-color--3f2d7e, #3F2D7E);
  stop-opacity: 0;
}

.pw_9qjb5p {
  stop-color: var(--svg-color--56427b, #56427B);
  stop-opacity: 0;
}

.q_g8mnbhc {
  stop-color: var(--svg-color--766b81, #766B81);
  stop-opacity: 0;
}

.q1w9isbqn {
  stop-color: var(--svg-color--7a61b3, #7A61B3);
  stop-opacity: 0;
}

.qdq-erb7u {
  stop-color: var(--svg-color--e5a88d, #E5A88D);
}

.qh_uvdsfh {
  stop-color: var(--svg-color--dba486, #DBA486);
  stop-opacity: 0;
}

.ql1m53bju {
  stop-color: var(--svg-color--786c9a, #786C9A);
}

.r-abwq5sm {
  stop-color: var(--svg-color--d9a08f, #D9A08F);
}

.rdgulqvms {
  stop-color: var(--svg-color--e1a38b, #E1A38B);
  stop-opacity: 0;
}

.s1byoub3m {
  fill: var(--svg-color--55538a, #55538A);
  d: path("M11.77 27.542a6.3 6.3 0 0 0-1.413-.643l.004.014c-.433.175-1.005.467-1.55.746l-.517.262c-.324.163-.533.495-.443.847a.26.26 0 0 0 .252.196h3.43a.25.25 0 0 0 .25-.253z");
}

.sf2q7797h {
  fill: var(--svg-color--d8a490, #D8A490);
  d: path("m14.685 17.1l-.04-.78l1.891-.126c.047.664.118 1.594-.148 1.985c-.266.39-.765.858-2.2.945a42 42 0 0 1-3.269.031v-.18h-.672l-.34-.214c-.039-.192.39-.568.79-.711c1.254-.45 2.96-.82 3.988-.95");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.svuvwyb0s {
  stop-color: var(--svg-color--9c83d3, #9C83D3);
}

.szm_irbgj {
  d: path("m14.685 17.1l-.04-.78l1.891-.126c.047.664.118 1.594-.148 1.985c-.266.39-.765.858-2.2.945a42 42 0 0 1-3.269.031v-.18h-.672l-.34-.214c-.039-.192.39-.568.79-.711c1.254-.45 2.96-.82 3.988-.95");
}

.t_vl9fbku {
  stop-color: var(--svg-color--8f7c7f, #8F7C7F);
  stop-opacity: 0;
}

.tj9-bfwwp {
  stop-color: var(--svg-color--dca48d, #DCA48D);
}

.tpd8yob6x {
  stop-color: var(--svg-color--e3aa8c, #E3AA8C);
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.v224y-b0w {
  stop-color: var(--svg-color--a098a8, #A098A8);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vebuthb8b {
  cx: 12.71px;
  cy: 8.395px;
  rx: 0.064px;
  ry: 0.088px;
}

.vmk6x9_kg {
  stop-color: var(--svg-color--dd9a7e, #DD9A7E);
}

.vp-i5ufoh {
  d: path("M14.73 26.64c-.05-1.838.196-4.492.32-5.57l3.485-.696c-.555 3.344-1.328 5.508-1.687 6.266c1.062-.266 2.578-.172 3.765-.117l.39 1.515c-1.233.125-3.339.523-3.843.648c-.562.141-2.371.086-2.43-2.046");
}

.vtcy4jgmq {
  d: path("M12.03 7.953c.038-.802.297-1.188.42-1.3h3.732l.062 3.163c-.866 2.122-3.511 2.213-3.906 1.445c-.395-.767-.353-2.38-.309-3.308");
}

.w7r1zi1yh {
  stop-color: var(--svg-color--ffecb8, #FFECB8);
  stop-opacity: 0;
}

.x-p0yyc_l {
  stop-color: var(--svg-color--d3917d, #D3917D);
}

.xgk77dt3o {
  stop-color: var(--svg-color--3f3e62, #3F3E62);
  stop-opacity: 0;
}

.xv9roqx4c {
  stop-color: var(--svg-color--7e5e9a, #7E5E9A);
}

.y0t-xbb0q {
  d: path("m14.702 9.407l.2-1.44a.727.727 0 0 1-.2 1.44");
}

.y4wyj4zjh {
  fill: var(--svg-color--97919f, #97919F);
  d: path("M14.73 26.64c-.05-1.838.196-4.492.32-5.57l3.485-.696c-.555 3.344-1.328 5.508-1.687 6.266c1.062-.266 2.578-.172 3.765-.117l.39 1.515c-1.233.125-3.339.523-3.843.648c-.562.141-2.371.086-2.43-2.046");
}

.yes5_6oun {
  stop-color: var(--svg-color--624a8d, #624A8D);
}

.yfv3nqb2s {
  stop-color: var(--svg-color--e4a88b, #E4A88B);
  stop-opacity: 0;
}

.yfxz81b1q {
  stop-color: var(--svg-color--bf8a7b, #BF8A7B);
}

.ysczdsbzf {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M17.208 21.616c-.138.941-.573 3.264-1.239 5.338a.5.5 0 0 0 .152.535a.55.55 0 0 0 .538.086c.689-.244 2.053-.526 3.737-.302");
}

.ywfpue-3p {
  d: path("m21.476 25.788l-.885.75l.406 1.5c.39.198 1.35.653 2.063.89c.547.183.887.06 1.056-.083c.078-.065.066-.178 0-.257l-2.285-2.769a.25.25 0 0 0-.355-.031");
}

.z_p65vbje {
  stop-color: var(--svg-color--786c9a, #786C9A);
  stop-opacity: 0;
}

.z30nzhb6f {
  d: path("M11.707 21.545v-.003c1.787.442 3.937.808 5.747.262c1.2-.363 1.266-1.817 1.266-2.875l-7.61.078q-.4.138-.702.336z");
}

.zieydyb7s {
  stop-color: var(--svg-color--342452, #342452);
}

.zm5b18b9s {
  stop-color: var(--svg-color--e4ad98, #E4AD98);
  stop-opacity: 0;
}

</style>
