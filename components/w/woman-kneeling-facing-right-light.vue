<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ipLu1Sc)"><path class="otxv6821g"/></g><g filter="url(#i1LqZuR)"><path stroke="url(#ifN8ZKd)" class="c5982svzr"/></g><path fill="url(#iViSrFc)" class="p6fapxbfv"/><g filter="url(#iv3nOab)"><path class="r93umccdm"/></g><path fill="url(#i4Gw1sF)" class="b-omp9owd"/><path fill="url(#i8ge7tc)" class="b-omp9owd"/><path fill="url(#iMgTzvJ)" class="w1fwp1zju"/><g filter="url(#il8K5ic)"><path class="qea32vbxe"/><path fill="url(#ivpJf3c)" class="orgvu4r3v"/><path fill="url(#iFFGjGd)" class="orgvu4r3v"/></g><g filter="url(#iX88ngG)"><path class="tybjqibrw"/><path fill="url(#iZ3KLnd)" class="wnbeks_yi"/><path fill="url(#i6c7nCc)" class="wnbeks_yi"/></g><path fill="url(#ipon7bb)" transform="scale(-1 1)rotate(-14.867 31.004 74.643)" class="ofkpelbcu"/><path fill="url(#iTj4Uxc)" transform="scale(-1 1)rotate(-14.867 31.004 74.643)" class="ofkpelbcu"/><path fill="url(#i4ORh4c)" class="mks244bdx"/><path fill="url(#i4Cz7Mb)" class="mks244bdx"/><path fill="url(#icwBioH)" class="mks244bdx"/><path fill="url(#iTdOzFc)" class="mks244bdx"/><g filter="url(#iCBv5ER)"><path class="avxvpzetp"/><path fill="url(#iEfuTad)" class="ahftk3bwp"/></g><g filter="url(#i1G0zwM)"><path class="xqvj_gpsw"/></g><g filter="url(#iiJbLuc)"><path class="c5o-z-ykd"/></g><path fill="url(#itaDDyb)" class="s6pqjobwz"/><path fill="url(#iPDLW1d)" class="s6pqjobwz"/><path fill="url(#ig2zGnb)" class="s6pqjobwz"/><path fill="url(#iYP2aOD)" class="s6pqjobwz"/><g filter="url(#ihjAeEd)"><path fill="url(#iFGa2jS)" class="znd6q-m0a"/></g><path fill="url(#igSoYFb)" class="wymlfbc7t"/><g filter="url(#i2Jtaie)"><path fill="url(#iTnllwe)" class="h96t81ifb"/><path fill="url(#iKa2A3d)" class="h96t81ifb"/><path fill="url(#iANxp9b)" class="h96t81ifb"/><path fill="url(#iWLcYdb)" class="h96t81ifb"/></g><g filter="url(#iygKTdd)"><path class="k794tpd4h"/><path fill="url(#ipZRa5c)" class="zi5hkidzs"/></g><g filter="url(#ixWdYCe)"><path class="en41b202k"/><path fill="url(#itUsHhe)" class="zi5hkidzs"/></g><path fill="url(#ijpUGOr)" class="g0wwmhmyn"/><path fill="url(#i7fEQEZ)" class="g0wwmhmyn"/><path fill="url(#ikb7qmc)" class="g0wwmhmyn"/><path clip-rule="evenodd" class="f7vdznmlx"/><g filter="url(#igzHWHb)"><path clip-rule="evenodd" class="ljjw1xb8w"/></g><path class="lcapjibuy"/><path class="nawft5tmm"/><path fill="url(#iVorgzg)" class="x5bf05rts"/><path fill="url(#i650qtd)" class="jg0g_1g1d"/><ellipse fill="url(#ipECBte)" transform="scale(-1 1)rotate(24.61 -28.655 -40.125)" class="m1l7k9jve"/><defs><radialGradient id="ifN8ZKd" cx="0" cy="0" r="1" gradientTransform="rotate(-130.67 14.274 10.16)scale(5.34656 3.97082)" gradientUnits="userSpaceOnUse"><stop class="lt2_2ybqi"/><stop offset="1" class="bils69brp"/></radialGradient><radialGradient id="iViSrFc" cx="0" cy="0" r="1" gradientTransform="matrix(.53125 3.29646 -1.78135 .28708 15.776 21.257)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="bmj_fbbea"/><stop offset="1" class="q_g8mnbhc"/></radialGradient><radialGradient id="i8ge7tc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03125 -5.37969 0 19.151 18.929)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="nu9hhfe4u"/><stop offset="1" class="t_vl9fbku"/></radialGradient><radialGradient id="iMgTzvJ" cx="0" cy="0" r="1" gradientTransform="matrix(.1094 3.14063 -8.2876 .28869 17.557 19.039)" gradientUnits="userSpaceOnUse"><stop offset=".558" class="gwwxm_bpq"/><stop offset=".971" class="xv9roqx4c"/></radialGradient><radialGradient id="ipon7bb" cx="0" cy="0" r="1" gradientTransform="rotate(-28.776 4.415 1.215)scale(2.02961 1.85514)" gradientUnits="userSpaceOnUse"><stop offset=".535" class="zn4yon0xn"/><stop offset="1" class="r95s-3qlg"/></radialGradient><radialGradient id="i4ORh4c" cx="0" cy="0" r="1" gradientTransform="matrix(3.45312 4 -4.99487 4.31198 14.323 14.554)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="ai9smcbyp"/><stop offset=".849" class="j-pea3b4d"/></radialGradient><radialGradient id="i4Cz7Mb" cx="0" cy="0" r="1" gradientTransform="matrix(1.23653 2.05948 -1.53634 .92244 15.555 13.76)" gradientUnits="userSpaceOnUse"><stop class="svuvwyb0s"/><stop offset="1" class="dlkt90brn"/></radialGradient><radialGradient id="icwBioH" cx="0" cy="0" r="1" gradientTransform="matrix(3.73437 .23436 -.4261 6.78981 14.838 16.302)" gradientUnits="userSpaceOnUse"><stop offset=".723" class="z_p65vbje"/><stop offset="1" class="ql1m53bju"/></radialGradient><radialGradient id="iTdOzFc" cx="0" cy="0" r="1" gradientTransform="rotate(-81.753 18.59 .076)scale(6.99015 5.26174)" gradientUnits="userSpaceOnUse"><stop offset=".86" class="pw_9qjb5p"/><stop offset=".968" class="zieydyb7s"/></radialGradient><radialGradient id="iEfuTad" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 2.34375 -.8049 -.04293 15.651 16.298)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="tr08sbvmm"/><stop offset="1" class="fz8d0bv0m"/></radialGradient><radialGradient id="iPDLW1d" cx="0" cy="0" r="1" gradientTransform="rotate(51.841 -5.251 22.332)scale(1.35127 1.54455)" gradientUnits="userSpaceOnUse"><stop class="ove-epbrr"/><stop offset="1" class="h87azyork"/></radialGradient><radialGradient id="ig2zGnb" cx="0" cy="0" r="1" gradientTransform="rotate(11.373 -72.197 84.55)scale(2.77321 5.18723)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="bd3uesbch"/><stop offset=".909" class="f-z_jdbvz"/></radialGradient><radialGradient id="iYP2aOD" cx="0" cy="0" r="1" gradientTransform="rotate(-86.772 16.452 -.863)scale(3.34906 2.70417)" gradientUnits="userSpaceOnUse"><stop offset=".868" class="q1w9isbqn"/><stop offset="1" class="yes5_6oun"/></radialGradient><radialGradient id="igSoYFb" cx="0" cy="0" r="1" gradientTransform="matrix(-.34549 .3399 -1.14146 -1.16022 20.361 9.257)" gradientUnits="userSpaceOnUse"><stop offset=".005" class="de7oo9b3j"/><stop offset=".684" class="plvhkpbev"/></radialGradient><radialGradient id="iKa2A3d" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 -.04687 .05715 1.0287 16.824 8.65)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="l7mbhnbzh"/><stop offset="1" class="biuc-6bfh"/></radialGradient><radialGradient id="iANxp9b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 1.60515 0 19.72 9.838)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="wcectbccf"/><stop offset="1" class="eqfhobc0c"/></radialGradient><radialGradient id="iWLcYdb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39063 -.60919 0 18.892 8.698)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="ie_w39bfj"/><stop offset="1" class="dx40lk_kc"/></radialGradient><radialGradient id="ipZRa5c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53488 -.4317 .92512 -3.28923 19.947 6.416)" gradientUnits="userSpaceOnUse"><stop class="k_urnmdao"/><stop offset="1" class="w7r1zi1yh"/></radialGradient><radialGradient id="itUsHhe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53488 -.4317 .92512 -3.28923 19.947 6.416)" gradientUnits="userSpaceOnUse"><stop class="tzf255bgc"/><stop offset="1" class="ctuud_14h"/></radialGradient><radialGradient id="ijpUGOr" cx="0" cy="0" r="1" gradientTransform="rotate(-163.812 9.18 3.048)scale(.75656 .36927)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="i8aj4_5_r"/><stop offset="1" class="u2yjj3mld"/></radialGradient><radialGradient id="i7fEQEZ" cx="0" cy="0" r="1" gradientTransform="rotate(100.843 5.155 11.19)scale(1.20119 1.25169)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="chiqx4b_a"/><stop offset="1" class="vmk6x9_kg"/><stop offset="1" class="hq1ekobkc"/></radialGradient><radialGradient id="iVorgzg" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 0 0 -.53125 19.187 8.725)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="i650qtd" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 0 0 -.54102 19.355 8.747)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><filter id="ipLu1Sc" width="7.28" height="8.609" x="10.996" y="20.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2296"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.466667 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_2296" result="effect2_innerShadow_2_2296"/></filter><filter id="i1LqZuR" width="5.734" height="7.279" x="11.071" y="21.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2296" stdDeviation=".25"/></filter><filter id="iv3nOab" width="11.64" height="10.135" x="13.28" y="18.929" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.490196 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2296"/></filter><filter id="il8K5ic" width="4.352" height="2.364" x="20.218" y="26.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.254902 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2296"/></filter><filter id="iX88ngG" width="3.579" height="3.542" x="7.83" y="25.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.168627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2296"/></filter><filter id="iCBv5ER" width="6.876" height="3.179" x="15.419" y="15.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.678431 0 0 0 0 0.596078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2296"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.537255 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_2296" result="effect2_innerShadow_2_2296"/></filter><filter id="i1G0zwM" width="1.071" height="1.439" x="21.358" y="18.071" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.623529 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2296"/></filter><filter id="iiJbLuc" width="1.196" height="1.065" x="20.878" y="18.669" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.623529 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2296"/></filter><filter id="ihjAeEd" width="8.168" height="8.42" x="14.276" y="19.415" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2296" stdDeviation=".375"/></filter><filter id="i2Jtaie" width="4.443" height="5.249" x="15.556" y="6.452" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.596078 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2296"/></filter><filter id="iygKTdd" width="6.813" height="7.403" x="13.347" y="4.791" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.972549 0 0 0 0 0.737255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2296"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.788235 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_2296" result="effect2_innerShadow_2_2296"/></filter><filter id="ixWdYCe" width="6.813" height="7.403" x="13.347" y="4.791" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.266667 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2296"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0901961 0 0 0 0 0.0392157 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_2296" result="effect2_innerShadow_2_2296"/></filter><filter id="igzHWHb" width="1.013" height=".568" x="18.324" y="7.396" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2296"/></filter><linearGradient id="i4Gw1sF" x1="15.214" x2="15.214" y1="18.835" y2="19.366" gradientUnits="userSpaceOnUse"><stop class="fy99v1bac"/><stop offset="1" class="l0bg_dlbj"/></linearGradient><linearGradient id="ivpJf3c" x1="20.089" x2="21.073" y1="28.101" y2="28.101" gradientUnits="userSpaceOnUse"><stop class="jje8gccwz"/><stop offset="1" class="ifze1vbqw"/></linearGradient><linearGradient id="iFFGjGd" x1="21.526" x2="21.526" y1="28.964" y2="28.593" gradientUnits="userSpaceOnUse"><stop class="k1dl65w8i"/><stop offset="1" class="pqpq_lljy"/></linearGradient><linearGradient id="iZ3KLnd" x1="11.064" x2="10.378" y1="26.054" y2="26.718" gradientUnits="userSpaceOnUse"><stop class="olt5ljabw"/><stop offset="1" class="xgk77dt3o"/></linearGradient><linearGradient id="i6c7nCc" x1="8.917" x2="9.132" y1="27.257" y2="27.429" gradientUnits="userSpaceOnUse"><stop offset=".098" class="fwheo7gdw"/><stop offset="1" class="oy9f4cbur"/></linearGradient><linearGradient id="iTj4Uxc" x1="-.013" x2=".367" y1="1.808" y2="1.78" gradientUnits="userSpaceOnUse"><stop class="hq5x-3jdn"/><stop offset="1" class="tn-khbb1y"/></linearGradient><linearGradient id="itaDDyb" x1="15.05" x2="17.115" y1="15.132" y2="15.226" gradientUnits="userSpaceOnUse"><stop class="d30p-0b3w"/><stop offset="1" class="cm74u7bos"/></linearGradient><linearGradient id="iFGa2jS" x1="21.694" x2="15.214" y1="25.851" y2="19.913" gradientUnits="userSpaceOnUse"><stop offset=".552" class="cl3ijcbld"/><stop offset="1" class="v224y-b0w"/></linearGradient><linearGradient id="iTnllwe" x1="17.136" x2="19.998" y1="9.393" y2="9.565" gradientUnits="userSpaceOnUse"><stop class="ao99c43-t"/><stop offset="1" class="n5u_3996t"/></linearGradient><linearGradient id="ikb7qmc" x1="17.201" x2="17.052" y1="8.602" y2="8.614" gradientUnits="userSpaceOnUse"><stop class="o01zddb6n"/><stop offset="1" class="h5b83fbqu"/></linearGradient><linearGradient id="ipECBte" x1="-.007" x2=".179" y1=".05" y2=".11" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-kneeling-facing-right-light" /></template>
<style>
.ahftk3bwp {
  d: path("m17.315 17.1l.04-.78l-1.891-.126c-.047.664-.118 1.594.148 1.985c.266.39.765.858 2.2.945c1.03.063 2.618.057 3.269.031v-.18h.672l.34-.214c.038-.192-.39-.568-.79-.711c-1.254-.45-2.96-.82-3.988-.95");
}

.ai9smcbyp {
  stop-color: var(--svg-color--8672be, #8672BE);
}

.ao99c43-t {
  stop-color: var(--svg-color--e4b1a5, #E4B1A5);
}

.avxvpzetp {
  fill: var(--svg-color--e6b3a6, #E6B3A6);
  d: path("m17.315 17.1l.04-.78l-1.891-.126c-.047.664-.118 1.594.148 1.985c.266.39.765.858 2.2.945c1.03.063 2.618.057 3.269.031v-.18h.672l.34-.214c.038-.192-.39-.568-.79-.711c-1.254-.45-2.96-.82-3.988-.95");
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

.biuc-6bfh {
  stop-color: var(--svg-color--eeb298, #EEB298);
  stop-opacity: 0;
}

.bmj_fbbea {
  stop-color: var(--svg-color--6a5a7a, #6A5A7A);
}

.c5982svzr {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M14.792 21.616c.138.941.573 3.264 1.239 5.338a.5.5 0 0 1-.152.535a.55.55 0 0 1-.538.086c-.689-.244-2.053-.526-3.737-.302");
}

.c5o-z-ykd {
  fill: var(--svg-color--dda89d, #DDA89D);
  d: path("M21.448 18.769c-.325-.003-.516.178-.57.27c.271.143.499.375.65.566c.1.124.278.17.413.086a.266.266 0 0 0 .079-.39c-.257-.329-.48-.49-.572-.532");
}

.chiqx4b_a {
  stop-color: var(--svg-color--e7a792, #E7A792);
  stop-opacity: 0;
}

.cl3ijcbld {
  stop-color: var(--svg-color--a098a8, #A098A8);
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

.de7oo9b3j {
  stop-color: var(--svg-color--f9bfa6, #F9BFA6);
}

.dlkt90brn {
  stop-color: var(--svg-color--9c83d3, #9C83D3);
  stop-opacity: 0;
}

.dx40lk_kc {
  stop-color: var(--svg-color--fabfa4, #FABFA4);
  stop-opacity: 0;
}

.en41b202k {
  fill: var(--svg-color--241823, #241823);
  d: path("M20.09 6.606c.172-.41-.016-.844-.113-.992c-.367-.672-1.128-.717-1.567-.524c-.515.227-.669.347-1.503.11c-.837-.239-1.868-.13-2.407.84c-.539.968.047 2.058-.086 2.652c-.132.593-.512.652-.652 1.34c-.117.953.473 1.574.996 1.714c.524.141 1.602 0 1.953-.875c.576-1.431.184-2.109.31-2.828c.124-.718.554-.922 1.335-.765c.92.184 1.506-.126 1.734-.672");
}

.eqfhobc0c {
  stop-color: var(--svg-color--e9b59f, #E9B59F);
  stop-opacity: 0;
}

.f-z_jdbvz {
  stop-color: var(--svg-color--79699e, #79699E);
}

.f7vdznmlx {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M18.719 9.86a.125.125 0 0 0 .002.177c.238.234.582.293.692.305a.125.125 0 1 0 .025-.25c-.094-.009-.366-.06-.542-.233a.125.125 0 0 0-.177.001");
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

.fz8d0bv0m {
  stop-color: var(--svg-color--f8c0b0, #F8C0B0);
  stop-opacity: 0;
}

.g0wwmhmyn {
  d: path("m17.298 9.407l-.2-1.44a.727.727 0 0 0 .2 1.44");
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gwwxm_bpq {
  stop-color: var(--svg-color--857297, #857297);
  stop-opacity: 0;
}

.h5b83fbqu {
  stop-color: var(--svg-color--f4bca5, #F4BCA5);
  stop-opacity: 0;
}

.h87azyork {
  stop-color: var(--svg-color--8366c0, #8366C0);
  stop-opacity: 0;
}

.h96t81ifb {
  d: path("M19.97 7.953c-.038-.802-.297-1.188-.42-1.3h-3.732l-.062 3.163c.866 2.122 3.511 2.213 3.906 1.445c.395-.767.353-2.38.309-3.308");
}

.hq1ekobkc {
  stop-color: var(--svg-color--e7a792, #E7A792);
}

.hq5x-3jdn {
  stop-color: var(--svg-color--e6ae9f, #E6AE9F);
}

.i8aj4_5_r {
  stop-color: var(--svg-color--fac7b1, #FAC7B1);
}

.ie_w39bfj {
  stop-color: var(--svg-color--fabfa4, #FABFA4);
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

.k_urnmdao {
  stop-color: var(--svg-color--ffecb8, #FFECB8);
}

.k1dl65w8i {
  stop-color: var(--svg-color--3f2d7e, #3F2D7E);
}

.k794tpd4h {
  fill: var(--svg-color--ffe0af, #FFE0AF);
  d: path("M20.09 6.606c.172-.41-.016-.844-.113-.992c-.367-.672-1.128-.717-1.567-.524c-.515.227-.669.347-1.503.11c-.837-.239-1.868-.13-2.407.84c-.539.968.047 2.058-.086 2.652c-.132.593-.512.652-.652 1.34c-.117.953.473 1.574.996 1.714c.524.141 1.602 0 1.953-.875c.576-1.431.184-2.109.31-2.828c.124-.718.554-.922 1.335-.765c.92.184 1.506-.126 1.734-.672");
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l0bg_dlbj {
  stop-color: var(--svg-color--897694, #897694);
  stop-opacity: 0;
}

.l7mbhnbzh {
  stop-color: var(--svg-color--eeb298, #EEB298);
}

.lcapjibuy {
  fill: var(--svg-color--2f2c2d, #2F2C2D);
  d: path("M18.439 8.236c.131-.132.349-.162.441-.16l-.302.466c-.148-.008-.303-.143-.14-.306");
}

.ljjw1xb8w {
  fill: var(--svg-color--2c2828, #2C2828);
  fill-rule: evenodd;
  d: path("M18.952 7.714a.8.8 0 0 1 .216-.016a.15.15 0 1 0 .038-.297a1 1 0 0 0-.313.019a1 1 0 0 0-.409.173a.15.15 0 1 0 .179.241c.084-.062.19-.1.288-.12");
}

.lt2_2ybqi {
  stop-color: var(--svg-color--a49dac, #A49DAC);
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

.n5u_3996t {
  stop-color: var(--svg-color--e1ab9e, #E1AB9E);
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

.o01zddb6n {
  stop-color: var(--svg-color--f4b9a2, #F4B9A2);
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

.plvhkpbev {
  stop-color: var(--svg-color--e29f90, #E29F90);
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

.r93umccdm {
  fill: var(--svg-color--968ba1, #968BA1);
  d: path("M22.764 22.132c-.137.575-.807 3.427-1.125 4.781c.573.232 1.39.668 2.067 1.008c.325.163.533.495.443.847a.26.26 0 0 1-.252.196h-3.43a.25.25 0 0 1-.25-.253l.076-7.169c-1.787.442-3.937.808-5.747.262c-1.2-.363-1.266-1.817-1.266-2.875l7.61.078a2.726 2.726 0 0 1 1.874 3.125");
}

.r95s-3qlg {
  stop-color: var(--svg-color--8b5d56, #8B5D56);
}

.s6pqjobwz {
  d: path("M17.724 13.636a1.261 1.261 0 0 0-2.519-.119l-.155 2.775l2.566.152z");
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

.tn-khbb1y {
  stop-color: var(--svg-color--e6ae9f, #E6AE9F);
  stop-opacity: 0;
}

.tr08sbvmm {
  stop-color: var(--svg-color--f8c0b0, #F8C0B0);
}

.tybjqibrw {
  fill: var(--svg-color--443c7f, #443C7F);
  d: path("m10.524 25.788l.885.75l-.406 1.5c-.39.198-1.35.653-2.063.89c-.547.183-.887.06-1.056-.083c-.078-.065-.066-.178 0-.257l2.285-2.769a.25.25 0 0 1 .355-.031");
}

.tzf255bgc {
  stop-color: var(--svg-color--534b49, #534B49);
}

.u2yjj3mld {
  stop-color: var(--svg-color--ecb39e, #ECB39E);
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

.vmk6x9_kg {
  stop-color: var(--svg-color--dd9a7e, #DD9A7E);
}

.w1fwp1zju {
  d: path("M20.293 21.545v-.003c-1.787.442-3.937.808-5.747.262c-1.2-.363-1.266-1.817-1.266-2.875l7.61.078q.4.138.702.336z");
}

.w7r1zi1yh {
  stop-color: var(--svg-color--ffecb8, #FFECB8);
  stop-opacity: 0;
}

.wcectbccf {
  stop-color: var(--svg-color--ffcdb7, #FFCDB7);
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

.xqvj_gpsw {
  fill: var(--svg-color--dda89d, #DDA89D);
  d: path("m21.401 18.17l-.043.634c.233.181.452.427.603.608a.27.27 0 0 0 .346.059c.117-.073.16-.224.085-.339a3.6 3.6 0 0 0-.99-.961");
}

.xv9roqx4c {
  stop-color: var(--svg-color--7e5e9a, #7E5E9A);
}

.yes5_6oun {
  stop-color: var(--svg-color--624a8d, #624A8D);
}

.z_p65vbje {
  stop-color: var(--svg-color--786c9a, #786C9A);
  stop-opacity: 0;
}

.zi5hkidzs {
  d: path("M20.09 6.606c.172-.41-.016-.844-.113-.992c-.367-.672-1.128-.717-1.567-.524c-.515.227-.669.347-1.503.11c-.837-.239-1.868-.13-2.407.84c-.539.968.047 2.058-.086 2.652c-.132.593-.512.652-.652 1.34c-.117.953.473 1.574.996 1.714c.524.141 1.602 0 1.953-.875c.576-1.431.184-2.109.31-2.828c.124-.718.554-.922 1.335-.765c.92.184 1.506-.126 1.734-.672");
}

.zieydyb7s {
  stop-color: var(--svg-color--342452, #342452);
}

.zn4yon0xn {
  stop-color: var(--svg-color--c5948c, #C5948C);
}

.znd6q-m0a {
  d: path("m21.683 21.468l-.657 5.492l-.312.125l.43-5.73a.487.487 0 0 0-.482-.528c-.926-.006-3.848 0-4.542 0c-.813 0-1.094-.273-1.094-.648c1.193-.01 4.677-.025 5.664 0s1.04.862.992 1.289");
}

</style>
