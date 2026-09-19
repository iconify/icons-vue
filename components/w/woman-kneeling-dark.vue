<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iLEfhDd)"><path class="y4wyj4zjh"/></g><g filter="url(#i1jfITc)"><path stroke="url(#iGgBzCc)" class="ysczdsbzf"/></g><path fill="url(#iqkw6tb)" class="vp-i5ufoh"/><g filter="url(#iAMsGJy)"><path class="oa71k_21j"/></g><path fill="url(#iXr0Zpc)" class="j7qpbyb-r"/><path fill="url(#i5bTvre)" class="j7qpbyb-r"/><path fill="url(#iuXB9Zb)" class="z30nzhb6f"/><g filter="url(#ivn7Wdb)"><path class="s1byoub3m"/><path fill="url(#iIB3Sfe)" class="km8o6h6gs"/><path fill="url(#ifZW4Wc)" class="km8o6h6gs"/></g><g filter="url(#iLej0ye)"><path class="j6p_0hthu"/><path fill="url(#inywIwb)" class="ywfpue-3p"/><path fill="url(#ilwQO3c)" class="ywfpue-3p"/></g><path fill="url(#i7zieoS)" transform="rotate(-14.867 13.886 10.454)" class="ox_st0bbx"/><path fill="url(#iSHyNRb)" transform="rotate(-14.867 13.886 10.454)" class="ox_st0bbx"/><path fill="url(#ixymiKc)" class="apo7xsboj"/><path fill="url(#i3FNi9c)" class="apo7xsboj"/><path fill="url(#iia4Jid)" class="apo7xsboj"/><path fill="url(#i3KjAPe)" class="apo7xsboj"/><g filter="url(#iCOSv8b)"><path class="pr2-7376p"/><path fill="url(#iQuyAKI)" class="szm_irbgj"/></g><g filter="url(#iKOPtIc)"><path class="lw8tx464j"/></g><g filter="url(#iXEvLcb)"><path class="f0fvz7b6w"/></g><path fill="url(#i1fc6sc)" class="cv4locc3a"/><path fill="url(#iFcq2mc)" class="cv4locc3a"/><path fill="url(#iIo4leS)" class="cv4locc3a"/><path fill="url(#iZrw4vb)" class="cv4locc3a"/><g filter="url(#iZ2cWBe)"><path fill="url(#iupjd7b)" class="awg78lbzn"/></g><path fill="url(#iyWDdvb)" class="hwlh1kymk"/><g filter="url(#ifoWkHc)"><path fill="url(#iWslroc)" class="vtcy4jgmq"/><path fill="url(#i6YqdXc)" class="vtcy4jgmq"/><path fill="url(#ifnDT9d)" class="vtcy4jgmq"/><path fill="url(#iGM0kGd)" class="vtcy4jgmq"/></g><g filter="url(#iqF0ule)"><path class="g0u9jubrn"/></g><g filter="url(#i4EXfBe)"><path class="yyep01hgc"/><path fill="url(#iixZ4Bb)" class="i14panb0f"/></g><path fill="url(#imXzC8X)" class="p-fxrtbns"/><path fill="url(#idZcTJb)" class="p-fxrtbns"/><path clip-rule="evenodd" class="m9ioqwb9w"/><g filter="url(#iOFnrXd)"><path clip-rule="evenodd" class="cvpbi-d_r"/></g><path class="luodubbnn"/><path class="dctv-acks"/><path fill="url(#iTQDe0h)" class="hoq7s7bgo"/><path fill="url(#ir9h5Ju)" class="oag-gp42p"/><ellipse fill="url(#iBEtbSg)" transform="rotate(24.61 12.71 8.395)" class="vebuthb8b"/><defs><radialGradient id="iGgBzCc" cx="0" cy="0" r="1" gradientTransform="matrix(3.48437 -4.05522 3.01176 2.5878 16.13 27.609)" gradientUnits="userSpaceOnUse"><stop class="lt2_2ybqi"/><stop offset="1" class="bils69brp"/></radialGradient><radialGradient id="iqkw6tb" cx="0" cy="0" r="1" gradientTransform="matrix(-.53125 3.29646 -1.78135 -.28708 16.225 21.256)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="bmj_fbbea"/><stop offset="1" class="q_g8mnbhc"/></radialGradient><radialGradient id="i5bTvre" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03125 -5.37969 0 12.849 18.929)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="nu9hhfe4u"/><stop offset="1" class="t_vl9fbku"/></radialGradient><radialGradient id="iuXB9Zb" cx="0" cy="0" r="1" gradientTransform="matrix(-.10938 3.14063 -8.2876 -.28863 14.443 19.038)" gradientUnits="userSpaceOnUse"><stop offset=".558" class="gwwxm_bpq"/><stop offset=".971" class="xv9roqx4c"/></radialGradient><radialGradient id="i7zieoS" cx="0" cy="0" r="1" gradientTransform="matrix(1.77898 -.97701 .89303 1.62605 13.847 12.73)" gradientUnits="userSpaceOnUse"><stop offset=".397" class="xjmwsybmx"/><stop offset="1" class="vbd7v4bfq"/></radialGradient><radialGradient id="ixymiKc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.4531 4.00002 -4.9949 -4.31194 17.677 14.554)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="ai9smcbyp"/><stop offset=".849" class="j-pea3b4d"/></radialGradient><radialGradient id="i3FNi9c" cx="0" cy="0" r="1" gradientTransform="rotate(120.981 4.328 11.534)scale(2.40218 1.79199)" gradientUnits="userSpaceOnUse"><stop class="svuvwyb0s"/><stop offset="1" class="dlkt90brn"/></radialGradient><radialGradient id="iia4Jid" cx="0" cy="0" r="1" gradientTransform="matrix(-3.73437 .23436 -.4261 -6.78981 17.161 16.304)" gradientUnits="userSpaceOnUse"><stop offset=".723" class="z_p65vbje"/><stop offset="1" class="ql1m53bju"/></radialGradient><radialGradient id="i3KjAPe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.00267 -6.91786 5.20733 -.75475 16.152 18.463)" gradientUnits="userSpaceOnUse"><stop offset=".86" class="pw_9qjb5p"/><stop offset=".968" class="zieydyb7s"/></radialGradient><radialGradient id="iQuyAKI" cx="0" cy="0" r="1" gradientTransform="rotate(86.947 -.42 16.771)scale(2.34708 .80604)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="bm70d-gaq"/><stop offset="1" class="xojzxxboq"/></radialGradient><radialGradient id="iFcq2mc" cx="0" cy="0" r="1" gradientTransform="matrix(-.83488 1.0625 -1.21448 -.9543 16.448 12.663)" gradientUnits="userSpaceOnUse"><stop class="ove-epbrr"/><stop offset="1" class="h87azyork"/></radialGradient><radialGradient id="iIo4leS" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71876 .54686 -1.0229 -5.08537 16.744 15.898)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="bd3uesbch"/><stop offset=".909" class="f-z_jdbvz"/></radialGradient><radialGradient id="iZrw4vb" cx="0" cy="0" r="1" gradientTransform="matrix(-.18857 -3.34375 2.69988 -.15226 15.613 15.61)" gradientUnits="userSpaceOnUse"><stop offset=".868" class="q1w9isbqn"/><stop offset="1" class="yes5_6oun"/></radialGradient><radialGradient id="iyWDdvb" cx="0" cy="0" r="1" gradientTransform="matrix(.48867 .2693 -.38397 .69672 11.496 9.328)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="ss7zei8xw"/><stop offset=".684" class="d4kn2qv1f"/></radialGradient><radialGradient id="i6YqdXc" cx="0" cy="0" r="1" gradientTransform="matrix(-.84375 -.04688 .05715 -1.0287 15.176 8.65)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="cm3jz64eh"/><stop offset="1" class="lu7jcxbxj"/></radialGradient><radialGradient id="ifnDT9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 1.40625 0 12.28 9.838)" gradientUnits="userSpaceOnUse"><stop offset=".163" class="hrqvsac6m"/><stop offset="1" class="fblnbo7cb"/></radialGradient><radialGradient id="iGM0kGd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39063 -.60919 0 13.108 8.698)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="o5l8xobeq"/><stop offset="1" class="plhowgx4z"/></radialGradient><radialGradient id="iixZ4Bb" cx="0" cy="0" r="1" gradientTransform="matrix(1.53488 -.43168 .9251 3.28923 12.053 6.416)" gradientUnits="userSpaceOnUse"><stop class="tzf255bgc"/><stop offset="1" class="ctuud_14h"/></radialGradient><radialGradient id="imXzC8X" cx="0" cy="0" r="1" gradientTransform="matrix(.72656 -.21094 .10296 .35463 14.854 8.534)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="o1rzobcjq"/><stop offset="1" class="v23x_cgsr"/></radialGradient><radialGradient id="iTQDe0h" cx="0" cy="0" r="1" gradientTransform="matrix(.27344 0 0 .53125 12.813 8.725)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="ir9h5Ju" cx="0" cy="0" r="1" gradientTransform="matrix(.25 0 0 .54102 12.645 8.747)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><filter id="iLEfhDd" width="7.28" height="8.609" x="14.724" y="20.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_244"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.466667 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_244" result="effect2_innerShadow_4002_244"/></filter><filter id="i1jfITc" width="5.734" height="7.279" x="15.195" y="21.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_244" stdDeviation=".25"/></filter><filter id="iAMsGJy" width="11.64" height="10.135" x="7.83" y="18.929" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.490196 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_244"/></filter><filter id="ivn7Wdb" width="4.352" height="2.364" x="7.83" y="26.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.254902 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_244"/></filter><filter id="iLej0ye" width="3.579" height="3.542" x="20.591" y="25.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.168627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_244"/></filter><filter id="iCOSv8b" width="6.876" height="3.179" x="9.905" y="15.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.145098 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_244"/></filter><filter id="iKOPtIc" width="1.071" height="1.439" x="9.571" y="18.071" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.168627 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_244"/></filter><filter id="iXEvLcb" width="1.196" height="1.065" x="9.926" y="18.669" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.168627 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_244"/></filter><filter id="iZ2cWBe" width="8.168" height="8.42" x="9.556" y="19.415" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_244" stdDeviation=".375"/></filter><filter id="ifoWkHc" width="4.443" height="5.249" x="11.802" y="6.452" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.239216 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_244"/></filter><filter id="iqF0ule" width="7.013" height="7.503" x="11.44" y="4.691" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.843137 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_244"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.607843 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_244" result="effect2_innerShadow_4002_244"/></filter><filter id="i4EXfBe" width="6.813" height="7.403" x="11.44" y="4.791" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.266667 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_244"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0901961 0 0 0 0 0.0392157 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_244" result="effect2_innerShadow_4002_244"/></filter><filter id="iOFnrXd" width="1.013" height=".568" x="12.563" y="7.396" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0627451 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_244"/></filter><linearGradient id="iXr0Zpc" x1="16.786" x2="16.786" y1="18.835" y2="19.366" gradientUnits="userSpaceOnUse"><stop class="fy99v1bac"/><stop offset="1" class="l0bg_dlbj"/></linearGradient><linearGradient id="iIB3Sfe" x1="11.911" x2="10.927" y1="28.101" y2="28.101" gradientUnits="userSpaceOnUse"><stop class="jje8gccwz"/><stop offset="1" class="ifze1vbqw"/></linearGradient><linearGradient id="ifZW4Wc" x1="10.474" x2="10.474" y1="28.964" y2="28.593" gradientUnits="userSpaceOnUse"><stop class="k1dl65w8i"/><stop offset="1" class="pqpq_lljy"/></linearGradient><linearGradient id="inywIwb" x1="20.936" x2="21.622" y1="26.054" y2="26.718" gradientUnits="userSpaceOnUse"><stop class="olt5ljabw"/><stop offset="1" class="xgk77dt3o"/></linearGradient><linearGradient id="ilwQO3c" x1="23.083" x2="22.868" y1="27.257" y2="27.429" gradientUnits="userSpaceOnUse"><stop offset=".098" class="fwheo7gdw"/><stop offset="1" class="oy9f4cbur"/></linearGradient><linearGradient id="iSHyNRb" x1="13.874" x2="14.253" y1="12.262" y2="12.233" gradientUnits="userSpaceOnUse"><stop class="ln8qc12st"/><stop offset="1" class="o-5paobui"/></linearGradient><linearGradient id="i1fc6sc" x1="16.95" x2="14.885" y1="15.132" y2="15.226" gradientUnits="userSpaceOnUse"><stop class="d30p-0b3w"/><stop offset="1" class="cm74u7bos"/></linearGradient><linearGradient id="iupjd7b" x1="10.306" x2="16.786" y1="25.851" y2="19.913" gradientUnits="userSpaceOnUse"><stop offset=".552" class="cl3ijcbld"/><stop offset="1" class="v224y-b0w"/></linearGradient><linearGradient id="iWslroc" x1="14.864" x2="12.002" y1="9.393" y2="9.565" gradientUnits="userSpaceOnUse"><stop class="zpg97tbto"/><stop offset="1" class="l-3q2ti-u"/></linearGradient><linearGradient id="idZcTJb" x1="14.819" x2="14.932" y1="8.6" y2="8.616" gradientUnits="userSpaceOnUse"><stop class="uysgu56cq"/><stop offset="1" class="ve-3ak5rg"/></linearGradient><linearGradient id="iBEtbSg" x1="12.638" x2="12.825" y1="8.357" y2="8.418" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-kneeling-dark" /></template>
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

.bm70d-gaq {
  stop-color: var(--svg-color--574241, #574241);
}

.bmj_fbbea {
  stop-color: var(--svg-color--6a5a7a, #6A5A7A);
}

.cl3ijcbld {
  stop-color: var(--svg-color--a098a8, #A098A8);
}

.cm3jz64eh {
  stop-color: var(--svg-color--34191a, #34191A);
}

.cm74u7bos {
  stop-color: var(--svg-color--725aaa, #725AAA);
}

.ctuud_14h {
  stop-color: var(--svg-color--534b49, #534B49);
  stop-opacity: 0;
}

.cv4locc3a {
  d: path("M14.276 13.636a1.261 1.261 0 0 1 2.519-.119l.155 2.775l-2.566.152z");
}

.cvpbi-d_r {
  fill: var(--svg-color--2c2929, #2C2929);
  fill-rule: evenodd;
  d: path("M13.049 7.714a.8.8 0 0 0-.217-.016a.15.15 0 1 1-.038-.298c.071-.008.187-.006.313.02c.128.025.278.076.409.173a.15.15 0 1 1-.179.241a.7.7 0 0 0-.288-.12");
}

.d30p-0b3w {
  stop-color: var(--svg-color--8f77c9, #8F77C9);
}

.d4kn2qv1f {
  stop-color: var(--svg-color--41212e, #41212E);
}

.dctv-acks {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.536 8.747h.988c0-.392-.221-.71-.494-.71s-.494.318-.494.71");
}

.dlkt90brn {
  stop-color: var(--svg-color--9c83d3, #9C83D3);
  stop-opacity: 0;
}

.f-z_jdbvz {
  stop-color: var(--svg-color--79699e, #79699E);
}

.f0fvz7b6w {
  fill: var(--svg-color--442f2e, #442F2E);
  d: path("M10.552 18.769c.325-.003.516.178.57.27a2.2 2.2 0 0 0-.65.566c-.1.124-.278.17-.413.086a.266.266 0 0 1-.079-.39c.257-.329.48-.49.572-.532");
}

.fblnbo7cb {
  stop-color: var(--svg-color--614c49, #614C49);
  stop-opacity: 0;
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

.g0u9jubrn {
  fill: var(--svg-color--ffb629, #FFB629);
  d: path("M11.91 6.606c-.172-.41.016-.844.113-.992c.367-.672 1.128-.716 1.566-.524c.516.227.67.347 1.504.11c.837-.239 1.868-.13 2.407.84c.539.968-.047 2.058.086 2.652c.132.594.512.652.652 1.34c.117.953-.473 1.574-.996 1.714c-.524.141-1.602 0-1.953-.875c-.575-1.431-.184-2.109-.31-2.828c-.124-.718-.554-.921-1.335-.765c-.92.184-1.506-.126-1.734-.672");
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

.hoq7s7bgo {
  d: path("M13.141 8.747v-.004c0-.32-.137-.58-.306-.58c-.17 0-.307.26-.307.58v.004z");
}

.hrqvsac6m {
  stop-color: var(--svg-color--614c49, #614C49);
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

.jje8gccwz {
  stop-color: var(--svg-color--605f91, #605F91);
}

.k1dl65w8i {
  stop-color: var(--svg-color--3f2d7e, #3F2D7E);
}

.km8o6h6gs {
  d: path("M11.77 27.542a6.3 6.3 0 0 0-1.413-.643l.004.014c-.433.175-1.005.467-1.55.746l-.517.262c-.324.163-.533.495-.443.847a.26.26 0 0 0 .252.196h3.43a.25.25 0 0 0 .25-.253z");
}

.l-3q2ti-u {
  stop-color: var(--svg-color--48302f, #48302F);
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l0bg_dlbj {
  stop-color: var(--svg-color--897694, #897694);
  stop-opacity: 0;
}

.ln8qc12st {
  stop-color: var(--svg-color--544341, #544341);
}

.lt2_2ybqi {
  stop-color: var(--svg-color--a49dac, #A49DAC);
}

.lu7jcxbxj {
  stop-color: var(--svg-color--34191a, #34191A);
  stop-opacity: 0;
}

.luodubbnn {
  fill: var(--svg-color--2f2c2d, #2F2C2D);
  d: path("M13.561 8.236c-.131-.132-.349-.162-.441-.16l.302.466c.147-.008.303-.143.14-.306");
}

.lw8tx464j {
  fill: var(--svg-color--442f2e, #442F2E);
  d: path("m10.599 18.17l.043.634a4.3 4.3 0 0 0-.603.608a.27.27 0 0 1-.346.059c-.117-.073-.16-.224-.085-.339c.312-.472.795-.844.99-.961");
}

.m9ioqwb9w {
  fill: var(--svg-color--280017, #280017);
  fill-rule: evenodd;
  d: path("M13.281 9.86a.125.125 0 0 1-.002.177c-.238.234-.582.293-.691.305a.125.125 0 1 1-.026-.25c.094-.009.366-.06.542-.233a.125.125 0 0 1 .177.001");
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.nu9hhfe4u {
  stop-color: var(--svg-color--774e55, #774E55);
}

.o-5paobui {
  stop-color: var(--svg-color--544341, #544341);
  stop-opacity: 0;
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o5l8xobeq {
  stop-color: var(--svg-color--472f2c, #472F2C);
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

.p-fxrtbns {
  d: path("M14.794 9.413c-.05 0-.086-.047-.08-.096l.174-1.25c.008-.054.06-.093.113-.078a.727.727 0 0 1-.207 1.424");
}

.plhowgx4z {
  stop-color: var(--svg-color--472f2c, #472F2C);
  stop-opacity: 0;
}

.pqpq_lljy {
  stop-color: var(--svg-color--3f2d7e, #3F2D7E);
  stop-opacity: 0;
}

.pr2-7376p {
  fill: var(--svg-color--493033, #493033);
  d: path("m14.685 17.1l-.04-.78l1.891-.126c.047.664.118 1.594-.148 1.985c-.266.39-.765.858-2.2.945a42 42 0 0 1-3.269.031v-.18h-.672l-.34-.214c-.039-.192.39-.568.79-.711c1.254-.45 2.96-.82 3.988-.95");
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

.ql1m53bju {
  stop-color: var(--svg-color--786c9a, #786C9A);
}

.s1byoub3m {
  fill: var(--svg-color--55538a, #55538A);
  d: path("M11.77 27.542a6.3 6.3 0 0 0-1.413-.643l.004.014c-.433.175-1.005.467-1.55.746l-.517.262c-.324.163-.533.495-.443.847a.26.26 0 0 0 .252.196h3.43a.25.25 0 0 0 .25-.253z");
}

.ss7zei8xw {
  stop-color: var(--svg-color--68534f, #68534F);
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

.tzf255bgc {
  stop-color: var(--svg-color--534b49, #534B49);
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.uysgu56cq {
  stop-color: var(--svg-color--48302c, #48302C);
}

.v224y-b0w {
  stop-color: var(--svg-color--a098a8, #A098A8);
  stop-opacity: 0;
}

.v23x_cgsr {
  stop-color: var(--svg-color--482c2e, #482C2E);
}

.vbd7v4bfq {
  stop-color: var(--svg-color--26172f, #26172F);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.ve-3ak5rg {
  stop-color: var(--svg-color--48302c, #48302C);
  stop-opacity: 0;
}

.vebuthb8b {
  cx: 12.71px;
  cy: 8.395px;
  rx: 0.064px;
  ry: 0.088px;
}

.vp-i5ufoh {
  d: path("M14.73 26.64c-.05-1.838.196-4.492.32-5.57l3.485-.696c-.555 3.344-1.328 5.508-1.687 6.266c1.062-.266 2.578-.172 3.765-.117l.39 1.515c-1.233.125-3.339.523-3.843.648c-.562.141-2.371.086-2.43-2.046");
}

.vtcy4jgmq {
  d: path("M12.03 7.953c.038-.802.297-1.188.42-1.3h3.732l.062 3.163c-.866 2.122-3.511 2.213-3.906 1.445c-.395-.767-.353-2.38-.309-3.308");
}

.xgk77dt3o {
  stop-color: var(--svg-color--3f3e62, #3F3E62);
  stop-opacity: 0;
}

.xjmwsybmx {
  stop-color: var(--svg-color--3b2a2c, #3B2A2C);
}

.xojzxxboq {
  stop-color: var(--svg-color--574241, #574241);
  stop-opacity: 0;
}

.xv9roqx4c {
  stop-color: var(--svg-color--7e5e9a, #7E5E9A);
}

.y4wyj4zjh {
  fill: var(--svg-color--97919f, #97919F);
  d: path("M14.73 26.64c-.05-1.838.196-4.492.32-5.57l3.485-.696c-.555 3.344-1.328 5.508-1.687 6.266c1.062-.266 2.578-.172 3.765-.117l.39 1.515c-1.233.125-3.339.523-3.843.648c-.562.141-2.371.086-2.43-2.046");
}

.yes5_6oun {
  stop-color: var(--svg-color--624a8d, #624A8D);
}

.ysczdsbzf {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M17.208 21.616c-.138.941-.573 3.264-1.239 5.338a.5.5 0 0 0 .152.535a.55.55 0 0 0 .538.086c.689-.244 2.053-.526 3.737-.302");
}

.ywfpue-3p {
  d: path("m21.476 25.788l-.885.75l.406 1.5c.39.198 1.35.653 2.063.89c.547.183.887.06 1.056-.083c.078-.065.066-.178 0-.257l-2.285-2.769a.25.25 0 0 0-.355-.031");
}

.yyep01hgc {
  fill: var(--svg-color--241823, #241823);
  d: path("M11.91 6.606c-.172-.41.016-.844.113-.992c.367-.672 1.128-.716 1.566-.524c.516.227.67.347 1.504.11c.837-.239 1.868-.13 2.407.84c.539.968-.047 2.058.086 2.652c.132.594.512.652.652 1.34c.117.953-.473 1.574-.996 1.714c-.524.141-1.602 0-1.953-.875c-.575-1.431-.184-2.109-.31-2.828c-.124-.718-.554-.921-1.335-.765c-.92.184-1.506-.126-1.734-.672");
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

.zpg97tbto {
  stop-color: var(--svg-color--432b2f, #432B2F);
}

</style>
