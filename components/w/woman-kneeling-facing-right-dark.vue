<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ipIIJPb)"><path class="otxv6821g"/></g><g filter="url(#i7rkmmc)"><path stroke="url(#ifN8ZKd)" class="c5982svzr"/></g><path fill="url(#iViSrFc)" class="p6fapxbfv"/><g filter="url(#ib64t9G)"><path class="r93umccdm"/></g><path fill="url(#i4Gw1sF)" class="b-omp9owd"/><path fill="url(#i8ge7tc)" class="b-omp9owd"/><path fill="url(#iMgTzvJ)" class="w1fwp1zju"/><g filter="url(#iBaRZhc)"><path class="qea32vbxe"/><path fill="url(#ivpJf3c)" class="orgvu4r3v"/><path fill="url(#iFFGjGd)" class="orgvu4r3v"/></g><g filter="url(#igN0tbd)"><path class="tybjqibrw"/><path fill="url(#iZ3KLnd)" class="wnbeks_yi"/><path fill="url(#i6c7nCc)" class="wnbeks_yi"/></g><path fill="url(#iBrICke)" transform="scale(-1 1)rotate(-14.867 31.004 74.643)" class="ofkpelbcu"/><path fill="url(#iMQdqMc)" transform="scale(-1 1)rotate(-14.867 31.004 74.643)" class="ofkpelbcu"/><path fill="url(#i4ORh4c)" class="mks244bdx"/><path fill="url(#i4Cz7Mb)" class="mks244bdx"/><path fill="url(#icwBioH)" class="mks244bdx"/><path fill="url(#iTdOzFc)" class="mks244bdx"/><g filter="url(#iuw7Btc)"><path class="ifphcpbhp"/><path fill="url(#iZnR5Ad)" class="ahftk3bwp"/></g><g filter="url(#idxoAHu)"><path class="s7ur0vm0c"/></g><g filter="url(#iFYWTwI)"><path class="yjf31pb0v"/></g><path fill="url(#itaDDyb)" class="s6pqjobwz"/><path fill="url(#iPDLW1d)" class="s6pqjobwz"/><path fill="url(#ig2zGnb)" class="s6pqjobwz"/><path fill="url(#iYP2aOD)" class="s6pqjobwz"/><g filter="url(#i7PRGZv)"><path fill="url(#iFGa2jS)" class="znd6q-m0a"/></g><path fill="url(#iZ1ibTd)" class="wymlfbc7t"/><g filter="url(#i9aNH9d)"><path fill="url(#iEMCV0c)" class="h96t81ifb"/><path fill="url(#iaiHbPJ)" class="h96t81ifb"/><path fill="url(#iOGEqce)" class="h96t81ifb"/><path fill="url(#ipVrEec)" class="h96t81ifb"/></g><g filter="url(#ikDLdlc)"><path class="mq_4lybxk"/></g><g filter="url(#iwxnWQb)"><path class="zfsxwub6d"/><path fill="url(#itUsHhe)" class="qv_ycbc2s"/></g><path fill="url(#iLOIV7s)" class="ycbjwxwiv"/><path fill="url(#iPKmYtX)" class="ycbjwxwiv"/><path clip-rule="evenodd" class="yhn3uhbth"/><g filter="url(#iZH0ZSb)"><path clip-rule="evenodd" class="tu8aoybid"/></g><path class="lcapjibuy"/><path class="nawft5tmm"/><path fill="url(#iVorgzg)" class="x5bf05rts"/><path fill="url(#i650qtd)" class="jg0g_1g1d"/><ellipse fill="url(#ipECBte)" transform="scale(-1 1)rotate(24.61 -28.655 -40.125)" class="m1l7k9jve"/><defs><radialGradient id="ifN8ZKd" cx="0" cy="0" r="1" gradientTransform="rotate(-130.67 14.274 10.16)scale(5.34656 3.97082)" gradientUnits="userSpaceOnUse"><stop class="lt2_2ybqi"/><stop offset="1" class="bils69brp"/></radialGradient><radialGradient id="iViSrFc" cx="0" cy="0" r="1" gradientTransform="matrix(.53125 3.29646 -1.78135 .28708 15.776 21.257)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="bmj_fbbea"/><stop offset="1" class="q_g8mnbhc"/></radialGradient><radialGradient id="i8ge7tc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03125 -5.37969 0 19.151 18.929)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="nu9hhfe4u"/><stop offset="1" class="t_vl9fbku"/></radialGradient><radialGradient id="iMgTzvJ" cx="0" cy="0" r="1" gradientTransform="matrix(.1094 3.14063 -8.2876 .28869 17.557 19.039)" gradientUnits="userSpaceOnUse"><stop offset=".558" class="gwwxm_bpq"/><stop offset=".971" class="xv9roqx4c"/></radialGradient><radialGradient id="iBrICke" cx="0" cy="0" r="1" gradientTransform="rotate(-28.776 4.415 1.215)scale(2.02961 1.85514)" gradientUnits="userSpaceOnUse"><stop offset=".397" class="xjmwsybmx"/><stop offset="1" class="vbd7v4bfq"/></radialGradient><radialGradient id="i4ORh4c" cx="0" cy="0" r="1" gradientTransform="matrix(3.45312 4 -4.99487 4.31198 14.323 14.554)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="ai9smcbyp"/><stop offset=".849" class="j-pea3b4d"/></radialGradient><radialGradient id="i4Cz7Mb" cx="0" cy="0" r="1" gradientTransform="matrix(1.23653 2.05948 -1.53634 .92244 15.555 13.76)" gradientUnits="userSpaceOnUse"><stop class="svuvwyb0s"/><stop offset="1" class="dlkt90brn"/></radialGradient><radialGradient id="icwBioH" cx="0" cy="0" r="1" gradientTransform="matrix(3.73437 .23436 -.4261 6.78981 14.838 16.302)" gradientUnits="userSpaceOnUse"><stop offset=".723" class="z_p65vbje"/><stop offset="1" class="ql1m53bju"/></radialGradient><radialGradient id="iTdOzFc" cx="0" cy="0" r="1" gradientTransform="rotate(-81.753 18.59 .076)scale(6.99015 5.26174)" gradientUnits="userSpaceOnUse"><stop offset=".86" class="pw_9qjb5p"/><stop offset=".968" class="zieydyb7s"/></radialGradient><radialGradient id="iZnR5Ad" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 2.34375 -.8049 -.04293 15.651 16.298)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="bm70d-gaq"/><stop offset="1" class="xojzxxboq"/></radialGradient><radialGradient id="iPDLW1d" cx="0" cy="0" r="1" gradientTransform="rotate(51.841 -5.251 22.332)scale(1.35127 1.54455)" gradientUnits="userSpaceOnUse"><stop class="ove-epbrr"/><stop offset="1" class="h87azyork"/></radialGradient><radialGradient id="ig2zGnb" cx="0" cy="0" r="1" gradientTransform="rotate(11.373 -72.197 84.55)scale(2.77321 5.18723)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="bd3uesbch"/><stop offset=".909" class="f-z_jdbvz"/></radialGradient><radialGradient id="iYP2aOD" cx="0" cy="0" r="1" gradientTransform="rotate(-86.772 16.452 -.863)scale(3.34906 2.70417)" gradientUnits="userSpaceOnUse"><stop offset=".868" class="q1w9isbqn"/><stop offset="1" class="yes5_6oun"/></radialGradient><radialGradient id="iZ1ibTd" cx="0" cy="0" r="1" gradientTransform="rotate(151.14 9.052 7.302)scale(.55796 .79552)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="ss7zei8xw"/><stop offset=".684" class="d4kn2qv1f"/></radialGradient><radialGradient id="iaiHbPJ" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 -.04687 .05715 1.0287 16.824 8.65)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="cm3jz64eh"/><stop offset="1" class="lu7jcxbxj"/></radialGradient><radialGradient id="iOGEqce" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 1.40625 0 19.72 9.838)" gradientUnits="userSpaceOnUse"><stop offset=".163" class="hrqvsac6m"/><stop offset="1" class="fblnbo7cb"/></radialGradient><radialGradient id="ipVrEec" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39063 -.60919 0 18.892 8.698)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="o5l8xobeq"/><stop offset="1" class="plhowgx4z"/></radialGradient><radialGradient id="itUsHhe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53488 -.4317 .92512 -3.28923 19.947 6.416)" gradientUnits="userSpaceOnUse"><stop class="tzf255bgc"/><stop offset="1" class="ctuud_14h"/></radialGradient><radialGradient id="iLOIV7s" cx="0" cy="0" r="1" gradientTransform="rotate(-163.812 9.18 3.048)scale(.75656 .36927)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="o1rzobcjq"/><stop offset="1" class="v23x_cgsr"/></radialGradient><radialGradient id="iVorgzg" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 0 0 -.53125 19.187 8.725)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="i650qtd" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 0 0 -.54102 19.355 8.747)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><filter id="ipIIJPb" width="7.28" height="8.609" x="10.996" y="20.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1960"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.466667 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_1960" result="effect2_innerShadow_2_1960"/></filter><filter id="i7rkmmc" width="5.734" height="7.279" x="11.071" y="21.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_1960" stdDeviation=".25"/></filter><filter id="ib64t9G" width="11.64" height="10.135" x="13.28" y="18.929" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.490196 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1960"/></filter><filter id="iBaRZhc" width="4.352" height="2.364" x="20.218" y="26.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.254902 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1960"/></filter><filter id="igN0tbd" width="3.579" height="3.542" x="7.83" y="25.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.168627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1960"/></filter><filter id="iuw7Btc" width="6.876" height="3.179" x="15.419" y="15.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.145098 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1960"/></filter><filter id="idxoAHu" width="1.071" height="1.439" x="21.358" y="18.071" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.168627 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1960"/></filter><filter id="iFYWTwI" width="1.196" height="1.065" x="20.878" y="18.669" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.168627 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1960"/></filter><filter id="i7PRGZv" width="8.168" height="8.42" x="14.276" y="19.415" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_1960" stdDeviation=".375"/></filter><filter id="i9aNH9d" width="4.443" height="5.249" x="15.556" y="6.452" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.239216 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1960"/></filter><filter id="ikDLdlc" width="7.013" height="7.503" x="13.347" y="4.691" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.843137 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1960"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.607843 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_1960" result="effect2_innerShadow_2_1960"/></filter><filter id="iwxnWQb" width="6.813" height="7.403" x="13.347" y="4.791" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.266667 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1960"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0901961 0 0 0 0 0.0392157 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_1960" result="effect2_innerShadow_2_1960"/></filter><filter id="iZH0ZSb" width="1.013" height=".568" x="18.324" y="7.396" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0627451 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1960"/></filter><linearGradient id="i4Gw1sF" x1="15.214" x2="15.214" y1="18.835" y2="19.366" gradientUnits="userSpaceOnUse"><stop class="fy99v1bac"/><stop offset="1" class="l0bg_dlbj"/></linearGradient><linearGradient id="ivpJf3c" x1="20.089" x2="21.073" y1="28.101" y2="28.101" gradientUnits="userSpaceOnUse"><stop class="jje8gccwz"/><stop offset="1" class="ifze1vbqw"/></linearGradient><linearGradient id="iFFGjGd" x1="21.526" x2="21.526" y1="28.964" y2="28.593" gradientUnits="userSpaceOnUse"><stop class="k1dl65w8i"/><stop offset="1" class="pqpq_lljy"/></linearGradient><linearGradient id="iZ3KLnd" x1="11.064" x2="10.378" y1="26.054" y2="26.718" gradientUnits="userSpaceOnUse"><stop class="olt5ljabw"/><stop offset="1" class="xgk77dt3o"/></linearGradient><linearGradient id="i6c7nCc" x1="8.917" x2="9.132" y1="27.257" y2="27.429" gradientUnits="userSpaceOnUse"><stop offset=".098" class="fwheo7gdw"/><stop offset="1" class="oy9f4cbur"/></linearGradient><linearGradient id="iMQdqMc" x1="-.013" x2=".367" y1="1.808" y2="1.78" gradientUnits="userSpaceOnUse"><stop class="ln8qc12st"/><stop offset="1" class="o-5paobui"/></linearGradient><linearGradient id="itaDDyb" x1="15.05" x2="17.115" y1="15.132" y2="15.226" gradientUnits="userSpaceOnUse"><stop class="d30p-0b3w"/><stop offset="1" class="cm74u7bos"/></linearGradient><linearGradient id="iFGa2jS" x1="21.694" x2="15.214" y1="25.851" y2="19.913" gradientUnits="userSpaceOnUse"><stop offset=".552" class="cl3ijcbld"/><stop offset="1" class="v224y-b0w"/></linearGradient><linearGradient id="iEMCV0c" x1="17.136" x2="19.998" y1="9.393" y2="9.565" gradientUnits="userSpaceOnUse"><stop class="zpg97tbto"/><stop offset="1" class="l-3q2ti-u"/></linearGradient><linearGradient id="iPKmYtX" x1="17.181" x2="17.068" y1="8.6" y2="8.616" gradientUnits="userSpaceOnUse"><stop class="uysgu56cq"/><stop offset="1" class="ve-3ak5rg"/></linearGradient><linearGradient id="ipECBte" x1="-.007" x2=".179" y1=".05" y2=".11" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-kneeling-facing-right-dark" /></template>
<style>
.ahftk3bwp {
  d: path("m17.315 17.1l.04-.78l-1.891-.126c-.047.664-.118 1.594.148 1.985c.266.39.765.858 2.2.945c1.03.063 2.618.057 3.269.031v-.18h.672l.34-.214c.038-.192-.39-.568-.79-.711c-1.254-.45-2.96-.82-3.988-.95");
}

.ai9smcbyp {
  stop-color: var(--svg-color--8672be, #8672BE);
}

.b-omp9owd {
  d: path("M22.764 22.132c-.137.575-.807 3.427-1.125 4.781c.573.232 1.39.668 2.067 1.008c.325.163.533.495.443.847a.26.26 0 0 1-.252.196h-3.43a.25.25 0 0 1-.25-.253l.076-7.169c-1.787.442-3.937.808-5.747.262c-1.2-.363-1.266-1.817-1.266-2.875l7.61.078a2.726 2.726 0 0 1 1.874 3.125");
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

.c5982svzr {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M14.792 21.616c.138.941.573 3.264 1.239 5.338a.5.5 0 0 1-.152.535a.55.55 0 0 1-.538.086c-.689-.244-2.053-.526-3.737-.302");
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

.d30p-0b3w {
  stop-color: var(--svg-color--8f77c9, #8F77C9);
}

.d4kn2qv1f {
  stop-color: var(--svg-color--41212e, #41212E);
}

.dlkt90brn {
  stop-color: var(--svg-color--9c83d3, #9C83D3);
  stop-opacity: 0;
}

.f-z_jdbvz {
  stop-color: var(--svg-color--79699e, #79699E);
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

.h96t81ifb {
  d: path("M19.97 7.953c-.038-.802-.297-1.188-.42-1.3h-3.732l-.062 3.163c.866 2.122 3.511 2.213 3.906 1.445c.395-.767.353-2.38.309-3.308");
}

.hrqvsac6m {
  stop-color: var(--svg-color--614c49, #614C49);
}

.ifphcpbhp {
  fill: var(--svg-color--493033, #493033);
  d: path("m17.315 17.1l.04-.78l-1.891-.126c-.047.664-.118 1.594.148 1.985c.266.39.765.858 2.2.945c1.03.063 2.618.057 3.269.031v-.18h.672l.34-.214c.038-.192-.39-.568-.79-.711c-1.254-.45-2.96-.82-3.988-.95");
}

.ifze1vbqw {
  stop-color: var(--svg-color--605f91, #605F91);
  stop-opacity: 0;
}

.j-pea3b4d {
  stop-color: var(--svg-color--7059a7, #7059A7);
}

.jg0g_1g1d {
  d: path("m19.054 8.747l-.004-.073c0-.185.079-.336.176-.336s.176.15.176.336l-.004.073z");
}

.jje8gccwz {
  stop-color: var(--svg-color--605f91, #605F91);
}

.k1dl65w8i {
  stop-color: var(--svg-color--3f2d7e, #3F2D7E);
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

.lcapjibuy {
  fill: var(--svg-color--2f2c2d, #2F2C2D);
  d: path("M18.439 8.236c.131-.132.349-.162.441-.16l-.302.466c-.148-.008-.303-.143-.14-.306");
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

.m1l7k9jve {
  cx: 0.064px;
  cy: 0.088px;
  rx: 0.064px;
  ry: 0.088px;
}

.mks244bdx {
  d: path("M18.323 14.151c.163 1.15.094 2.637-.015 3.528v1.289h-5.032c.055-2.063.578-4.728 1.367-6.047c.664-1.11 1.422-1.176 2.055-.957c.606.183 1.422.75 1.625 2.187");
}

.mq_4lybxk {
  fill: var(--svg-color--ffb629, #FFB629);
  d: path("M20.09 6.606c.172-.41-.016-.844-.113-.992c-.367-.672-1.128-.716-1.567-.524c-.515.227-.669.347-1.503.11c-.837-.239-1.868-.13-2.407.84c-.539.968.047 2.058-.086 2.652c-.132.594-.512.652-.652 1.34c-.117.953.473 1.574.996 1.714c.524.141 1.602 0 1.953-.875c.576-1.431.184-2.109.31-2.828c.124-.718.554-.921 1.335-.765c.92.184 1.506-.126 1.734-.672");
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.nawft5tmm {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.464 8.747h-.988c0-.392.221-.71.494-.71s.494.318.494.71");
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

.ofkpelbcu {
  d: path("M0 0h1.976v2.198H0z");
}

.olt5ljabw {
  stop-color: var(--svg-color--3f3e62, #3F3E62);
}

.orgvu4r3v {
  d: path("M20.23 27.542a6.3 6.3 0 0 1 1.413-.643l-.004.014c.433.175 1.005.467 1.55.746l.517.262c.325.163.533.495.443.847a.26.26 0 0 1-.252.196h-3.43a.25.25 0 0 1-.25-.253z");
}

.otxv6821g {
  fill: var(--svg-color--97919f, #97919F);
  d: path("M17.27 26.64c.05-1.838-.196-4.492-.32-5.57l-3.485-.696c.555 3.344 1.328 5.508 1.687 6.266c-1.062-.266-2.578-.172-3.765-.117l-.39 1.515c1.233.125 3.339.523 3.843.648c.562.141 2.372.086 2.43-2.046");
}

.ove-epbrr {
  stop-color: var(--svg-color--9d84d5, #9D84D5);
}

.oy9f4cbur {
  stop-color: var(--svg-color--60608e, #60608E);
  stop-opacity: 0;
}

.p6fapxbfv {
  d: path("M17.27 26.64c.05-1.838-.196-4.492-.32-5.57l-3.485-.696c.555 3.344 1.328 5.508 1.687 6.266c-1.062-.266-2.578-.172-3.765-.117l-.39 1.515c1.233.125 3.339.523 3.843.648c.562.141 2.372.086 2.43-2.046");
}

.plhowgx4z {
  stop-color: var(--svg-color--472f2c, #472F2C);
  stop-opacity: 0;
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

.qea32vbxe {
  fill: var(--svg-color--55538a, #55538A);
  d: path("M20.23 27.542a6.3 6.3 0 0 1 1.413-.643l-.004.014c.433.175 1.005.467 1.55.746l.517.262c.325.163.533.495.443.847a.26.26 0 0 1-.252.196h-3.43a.25.25 0 0 1-.25-.253z");
}

.ql1m53bju {
  stop-color: var(--svg-color--786c9a, #786C9A);
}

.qv_ycbc2s {
  d: path("M20.09 6.606c.172-.41-.016-.844-.113-.992c-.367-.672-1.128-.716-1.567-.524c-.515.227-.669.347-1.503.11c-.837-.239-1.868-.13-2.407.84c-.539.968.047 2.058-.086 2.652c-.132.594-.512.652-.652 1.34c-.117.953.473 1.574.996 1.714c.524.141 1.602 0 1.953-.875c.576-1.431.184-2.109.31-2.828c.124-.718.554-.921 1.335-.765c.92.184 1.506-.126 1.734-.672");
}

.r93umccdm {
  fill: var(--svg-color--968ba1, #968BA1);
  d: path("M22.764 22.132c-.137.575-.807 3.427-1.125 4.781c.573.232 1.39.668 2.067 1.008c.325.163.533.495.443.847a.26.26 0 0 1-.252.196h-3.43a.25.25 0 0 1-.25-.253l.076-7.169c-1.787.442-3.937.808-5.747.262c-1.2-.363-1.266-1.817-1.266-2.875l7.61.078a2.726 2.726 0 0 1 1.874 3.125");
}

.s6pqjobwz {
  d: path("M17.724 13.636a1.261 1.261 0 0 0-2.519-.119l-.155 2.775l2.566.152z");
}

.s7ur0vm0c {
  fill: var(--svg-color--442f2e, #442F2E);
  d: path("m21.401 18.17l-.043.634c.233.181.452.427.603.608a.27.27 0 0 0 .346.059c.117-.073.16-.224.085-.339a3.6 3.6 0 0 0-.99-.961");
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

.t_vl9fbku {
  stop-color: var(--svg-color--8f7c7f, #8F7C7F);
  stop-opacity: 0;
}

.tu8aoybid {
  fill: var(--svg-color--2c2929, #2C2929);
  fill-rule: evenodd;
  d: path("M18.952 7.714a.8.8 0 0 1 .216-.016a.15.15 0 1 0 .038-.298a1 1 0 0 0-.313.02a1 1 0 0 0-.409.173a.15.15 0 1 0 .179.241c.084-.063.19-.1.288-.12");
}

.tybjqibrw {
  fill: var(--svg-color--443c7f, #443C7F);
  d: path("m10.524 25.788l.885.75l-.406 1.5c-.39.198-1.35.653-2.063.89c-.547.183-.887.06-1.056-.083c-.078-.065-.066-.178 0-.257l2.285-2.769a.25.25 0 0 1 .355-.031");
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

.w1fwp1zju {
  d: path("M20.293 21.545v-.003c-1.787.442-3.937.808-5.747.262c-1.2-.363-1.266-1.817-1.266-2.875l7.61.078q.4.138.702.336z");
}

.wnbeks_yi {
  d: path("m10.524 25.788l.885.75l-.406 1.5c-.39.198-1.35.653-2.063.89c-.547.183-.887.06-1.056-.083c-.078-.065-.066-.178 0-.257l2.285-2.769a.25.25 0 0 1 .355-.031");
}

.wymlfbc7t {
  d: path("M20.208 8.89c-.156-.147-.23-.405-.25-.496l-.2.065v1.125c.214.137.538.081.63-.124c.078-.176.015-.387-.18-.57");
}

.x5bf05rts {
  d: path("M18.859 8.747v-.004c0-.32.137-.58.306-.58c.17 0 .307.26.307.58v.004z");
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

.ycbjwxwiv {
  d: path("M17.207 9.413c.05 0 .085-.047.078-.096l-.173-1.25c-.008-.054-.06-.093-.112-.078a.727.727 0 0 0 .206 1.424");
}

.yes5_6oun {
  stop-color: var(--svg-color--624a8d, #624A8D);
}

.yhn3uhbth {
  fill: var(--svg-color--280017, #280017);
  fill-rule: evenodd;
  d: path("M18.719 9.86a.125.125 0 0 0 .002.177c.238.234.582.293.692.305a.125.125 0 1 0 .025-.25c-.094-.009-.366-.06-.542-.233a.125.125 0 0 0-.177.001");
}

.yjf31pb0v {
  fill: var(--svg-color--442f2e, #442F2E);
  d: path("M21.448 18.769c-.325-.003-.516.178-.57.27c.271.143.499.375.65.566c.1.124.278.17.413.086a.266.266 0 0 0 .079-.39c-.257-.329-.48-.49-.572-.532");
}

.z_p65vbje {
  stop-color: var(--svg-color--786c9a, #786C9A);
  stop-opacity: 0;
}

.zfsxwub6d {
  fill: var(--svg-color--241823, #241823);
  d: path("M20.09 6.606c.172-.41-.016-.844-.113-.992c-.367-.672-1.128-.716-1.567-.524c-.515.227-.669.347-1.503.11c-.837-.239-1.868-.13-2.407.84c-.539.968.047 2.058-.086 2.652c-.132.594-.512.652-.652 1.34c-.117.953.473 1.574.996 1.714c.524.141 1.602 0 1.953-.875c.576-1.431.184-2.109.31-2.828c.124-.718.554-.921 1.335-.765c.92.184 1.506-.126 1.734-.672");
}

.zieydyb7s {
  stop-color: var(--svg-color--342452, #342452);
}

.znd6q-m0a {
  d: path("m21.683 21.468l-.657 5.492l-.312.125l.43-5.73a.487.487 0 0 0-.482-.528c-.926-.006-3.848 0-4.542 0c-.813 0-1.094-.273-1.094-.648c1.193-.01 4.677-.025 5.664 0s1.04.862.992 1.289");
}

.zpg97tbto {
  stop-color: var(--svg-color--432b2f, #432B2F);
}

</style>
