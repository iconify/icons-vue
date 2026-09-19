<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ifv5j1F)"><path class="ri3n41bmg"/></g><g filter="url(#iNRJfge)"><path stroke="url(#iOmZ2wc)" class="ojh1fleoa"/></g><path fill="url(#iHGRKkb)" class="s9z3jkbdd"/><g filter="url(#ieNyZIc)"><path class="kh4m-x6vr"/></g><path fill="url(#ipljM2j)" class="tr7t_rbgt"/><path fill="url(#il2anXd)" class="tr7t_rbgt"/><path fill="url(#ix6Tusc)" class="l3pib11wq"/><g filter="url(#ip0EkHe)"><path class="b73vblb6y"/><path fill="url(#ihZhDed)" class="fyyb5wxvb"/><path fill="url(#imKHItb)" class="fyyb5wxvb"/></g><g filter="url(#iy1gyDF)"><path class="s-vq7hbns"/><path fill="url(#iGdUVQc)" class="ku5md_ocu"/><path fill="url(#iUmkrXc)" class="ku5md_ocu"/></g><path fill="url(#iYmopSc)" transform="rotate(-14.867 14.3 10.454)" class="cd_fnsb8c"/><path fill="url(#i6Xcipd)" transform="rotate(-14.867 14.3 10.454)" class="cd_fnsb8c"/><path fill="url(#iG332pd)" transform="rotate(-14.867 14.3 10.454)" class="cd_fnsb8c"/><path fill="url(#iCmJLOe)" class="qbinlrgys"/><path fill="url(#iRIHiUF)" class="qbinlrgys"/><path fill="url(#iu8hjKd)" class="qbinlrgys"/><g filter="url(#is9N6Rh)"><path class="o3zdgescu"/><path fill="url(#ibaZWIe)" class="gg3gfcb3s"/></g><g filter="url(#iw4DDSf)"><path class="fv64-xbqv"/></g><g filter="url(#iwJTAQd)"><path class="cm-f7m1jn"/></g><path fill="url(#iRJf9Rf)" class="kpqoceb4x"/><path fill="url(#idcmAXc)" class="kpqoceb4x"/><g filter="url(#iikjLch)"><path fill="url(#iSgNpsd)" class="ylstrmb2p"/></g><path fill="url(#isJNZbe)" class="i05bi9b5w"/><g filter="url(#iwKX7yc)"><path fill="url(#ig8nmwe)" class="gz7zsacgq"/><path fill="url(#iPCx7Oc)" class="gz7zsacgq"/><path fill="url(#ibR4ite)" class="gz7zsacgq"/><path fill="url(#ijW8Hrb)" class="gz7zsacgq"/></g><g filter="url(#i5g9G5d)"><path fill="url(#iZRpIIb)" class="yivr38b3w"/><path fill="url(#iWYyyGe)" class="yivr38b3w"/><path fill="url(#iYwXpZb)" class="yivr38b3w"/></g><path fill="url(#iUHtOfd)" class="vepd3j-1j"/><path fill="url(#imzfj0c)" class="vepd3j-1j"/><path clip-rule="evenodd" class="r0lz-mt_g"/><path class="d--ofrihp"/><path fill="url(#i2Drysd)" class="h0kx4wbgv"/><path fill="url(#iJnjvhc)" class="i59-3w3cd"/><ellipse fill="url(#isxCbse)" transform="rotate(24.61 13.11 8.402)" class="kxqsybbxp"/><g filter="url(#iPlZt0h)"><path clip-rule="evenodd" class="rmzxn5bsn"/></g><defs><radialGradient id="iOmZ2wc" cx="0" cy="0" r="1" gradientTransform="matrix(3.48437 -4.05522 3.01176 2.5878 16.544 27.609)" gradientUnits="userSpaceOnUse"><stop class="lt2_2ybqi"/><stop offset="1" class="bils69brp"/></radialGradient><radialGradient id="iHGRKkb" cx="0" cy="0" r="1" gradientTransform="matrix(-.53125 3.29646 -1.78135 -.28708 16.638 21.257)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="bmj_fbbea"/><stop offset="1" class="q_g8mnbhc"/></radialGradient><radialGradient id="il2anXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03125 -5.37969 0 13.263 18.929)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="nu9hhfe4u"/><stop offset="1" class="t_vl9fbku"/></radialGradient><radialGradient id="ix6Tusc" cx="0" cy="0" r="1" gradientTransform="matrix(-.10938 3.14063 -8.2876 -.28863 14.857 19.038)" gradientUnits="userSpaceOnUse"><stop offset=".558" class="gwwxm_bpq"/><stop offset=".971" class="xv9roqx4c"/></radialGradient><radialGradient id="iYmopSc" cx="0" cy="0" r="1" gradientTransform="matrix(1.75062 .2869 -.80956 4.93988 14.391 12.036)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="om366ybrp"/><stop offset="1" class="al52zb3wa"/></radialGradient><radialGradient id="i6Xcipd" cx="0" cy="0" r="1" gradientTransform="rotate(117.861 4.924 10.376)scale(.83385 .74963)" gradientUnits="userSpaceOnUse"><stop class="numeh5b7w"/><stop offset="1" class="yqah6ebzx"/></radialGradient><radialGradient id="iCmJLOe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.4531 4.00002 -4.9949 -4.31194 18.091 14.554)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="b2o3a7r9l"/><stop offset="1" class="g7ee89odc"/></radialGradient><radialGradient id="iRIHiUF" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03122 3.14064 -3.13218 -2.02576 17.654 12.679)" gradientUnits="userSpaceOnUse"><stop class="oo0a8g8xe"/><stop offset="1" class="hc1x_wbbe"/></radialGradient><radialGradient id="iu8hjKd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.73437 .23436 -.4261 -6.78981 17.576 16.304)" gradientUnits="userSpaceOnUse"><stop offset=".563" class="brpomvbii"/><stop offset="1" class="lmk5_gb2n"/></radialGradient><radialGradient id="ibaZWIe" cx="0" cy="0" r="1" gradientTransform="rotate(86.947 -.214 16.99)scale(2.34708 .80604)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="bm70d-gaq"/><stop offset="1" class="xojzxxboq"/></radialGradient><radialGradient id="idcmAXc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 1.04686 -.99542 -1.2183 17.21 12.679)" gradientUnits="userSpaceOnUse"><stop class="n6csxrxuy"/><stop offset="1" class="obkbkpctx"/></radialGradient><radialGradient id="isJNZbe" cx="0" cy="0" r="1" gradientTransform="matrix(.47656 .25781 -.36391 .67269 11.915 9.361)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="ss7zei8xw"/><stop offset=".684" class="d4kn2qv1f"/></radialGradient><radialGradient id="iPCx7Oc" cx="0" cy="0" r="1" gradientTransform="matrix(-.84375 -.04688 .05715 -1.0287 15.577 8.658)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="cm3jz64eh"/><stop offset="1" class="lu7jcxbxj"/></radialGradient><radialGradient id="ibR4ite" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 1.40625 0 12.68 9.845)" gradientUnits="userSpaceOnUse"><stop offset=".163" class="hrqvsac6m"/><stop offset="1" class="fblnbo7cb"/></radialGradient><radialGradient id="ijW8Hrb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39063 -.60919 0 13.509 8.705)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="o5l8xobeq"/><stop offset="1" class="plhowgx4z"/></radialGradient><radialGradient id="iZRpIIb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.43749 3.12502 -3.54357 -3.89789 17.452 5.996)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="sd2k4tbbl"/><stop offset="1" class="n3xu87-4f"/></radialGradient><radialGradient id="iWYyyGe" cx="0" cy="0" r="1" gradientTransform="rotate(81.634 4.768 13.414)scale(2.71158 1.19788)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="qvi3m-3ib"/><stop offset="1" class="sx_wpgngv"/></radialGradient><radialGradient id="iYwXpZb" cx="0" cy="0" r="1" gradientTransform="matrix(1.5 -.09375 .18397 2.94358 12.155 6.611)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="ehlb6fbrs"/><stop offset="1" class="xv-sacbws"/></radialGradient><radialGradient id="iUHtOfd" cx="0" cy="0" r="1" gradientTransform="matrix(.72656 -.21094 .10296 .35463 15.352 8.54)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="o1rzobcjq"/><stop offset="1" class="v23x_cgsr"/></radialGradient><radialGradient id="i2Drysd" cx="0" cy="0" r="1" gradientTransform="matrix(.27344 0 0 .53125 13.214 8.732)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iJnjvhc" cx="0" cy="0" r="1" gradientTransform="matrix(.25 0 0 .54102 13.046 8.754)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><filter id="ifv5j1F" width="7.28" height="8.609" x="15.138" y="20.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_245"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.466667 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_245" result="effect2_innerShadow_4002_245"/></filter><filter id="iNRJfge" width="5.734" height="7.279" x="15.609" y="21.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_245" stdDeviation=".25"/></filter><filter id="ieNyZIc" width="11.64" height="10.135" x="8.244" y="18.929" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.490196 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_245"/></filter><filter id="ip0EkHe" width="4.352" height="2.364" x="8.244" y="26.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.254902 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_245"/></filter><filter id="iy1gyDF" width="3.579" height="3.542" x="21.005" y="25.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.168627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_245"/></filter><filter id="is9N6Rh" width="6.876" height="3.179" x="10.319" y="15.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.145098 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_245"/></filter><filter id="iw4DDSf" width="1.071" height="1.439" x="9.985" y="18.071" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.168627 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_245"/></filter><filter id="iwJTAQd" width="1.196" height="1.065" x="10.34" y="18.669" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.168627 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_245"/></filter><filter id="iikjLch" width="8.168" height="8.42" x="9.97" y="19.415" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_245" stdDeviation=".375"/></filter><filter id="iwKX7yc" width="4.443" height="5.249" x="12.202" y="6.459" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.239216 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_245"/></filter><filter id="i5g9G5d" width="6.391" height="5.479" x="11.769" y="4.815" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.262745 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_245"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0980392 0 0 0 0 0.054902 0 0 0 0 0.0705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_245" result="effect2_innerShadow_4002_245"/></filter><filter id="iPlZt0h" width="1.117" height=".648" x="12.906" y="7.386" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0627451 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_245"/></filter><linearGradient id="ipljM2j" x1="17.2" x2="17.2" y1="18.835" y2="19.366" gradientUnits="userSpaceOnUse"><stop class="fy99v1bac"/><stop offset="1" class="l0bg_dlbj"/></linearGradient><linearGradient id="ihZhDed" x1="12.325" x2="11.341" y1="28.101" y2="28.101" gradientUnits="userSpaceOnUse"><stop class="jje8gccwz"/><stop offset="1" class="ifze1vbqw"/></linearGradient><linearGradient id="imKHItb" x1="10.888" x2="10.888" y1="28.964" y2="28.593" gradientUnits="userSpaceOnUse"><stop class="k1dl65w8i"/><stop offset="1" class="pqpq_lljy"/></linearGradient><linearGradient id="iGdUVQc" x1="21.351" x2="22.036" y1="26.054" y2="26.718" gradientUnits="userSpaceOnUse"><stop class="olt5ljabw"/><stop offset="1" class="xgk77dt3o"/></linearGradient><linearGradient id="iUmkrXc" x1="23.497" x2="23.282" y1="27.257" y2="27.429" gradientUnits="userSpaceOnUse"><stop offset=".098" class="fwheo7gdw"/><stop offset="1" class="oy9f4cbur"/></linearGradient><linearGradient id="iG332pd" x1="14.297" x2="14.533" y1="12.329" y2="12.323" gradientUnits="userSpaceOnUse"><stop class="ndh-ggbqf"/><stop offset="1" class="naoj9jbij"/></linearGradient><linearGradient id="iRJf9Rf" x1="17.18" x2="14.689" y1="15.304" y2="15.382" gradientUnits="userSpaceOnUse"><stop class="ofo46gsuq"/><stop offset="1" class="lq0qk0brb"/></linearGradient><linearGradient id="iSgNpsd" x1="10.72" x2="17.201" y1="25.851" y2="19.913" gradientUnits="userSpaceOnUse"><stop offset=".552" class="cl3ijcbld"/><stop offset="1" class="v224y-b0w"/></linearGradient><linearGradient id="ig8nmwe" x1="15.265" x2="12.402" y1="9.4" y2="9.572" gradientUnits="userSpaceOnUse"><stop class="zpg97tbto"/><stop offset="1" class="l-3q2ti-u"/></linearGradient><linearGradient id="imzfj0c" x1="15.317" x2="15.431" y1="8.607" y2="8.623" gradientUnits="userSpaceOnUse"><stop class="uysgu56cq"/><stop offset="1" class="ve-3ak5rg"/></linearGradient><linearGradient id="isxCbse" x1="13.039" x2="13.225" y1="8.364" y2="8.425" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-kneeling-dark" /></template>
<style>
.al52zb3wa {
  stop-color: var(--svg-color--5d4b4a, #5D4B4A);
}

.b2o3a7r9l {
  stop-color: var(--svg-color--45a7f8, #45A7F8);
}

.b73vblb6y {
  fill: var(--svg-color--55538a, #55538A);
  d: path("M12.184 27.542a6.3 6.3 0 0 0-1.412-.643q0 .008.003.014c-.433.175-1.005.467-1.55.746l-.517.262c-.324.163-.533.495-.443.847a.26.26 0 0 0 .252.196h3.43a.25.25 0 0 0 .25-.253z");
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

.brpomvbii {
  stop-color: var(--svg-color--4b77af, #4B77AF);
  stop-opacity: 0;
}

.cd_fnsb8c {
  d: path("M14.3 10.454h1.976v2.198H14.3z");
}

.cl3ijcbld {
  stop-color: var(--svg-color--a098a8, #A098A8);
}

.cm-f7m1jn {
  fill: var(--svg-color--442f2e, #442F2E);
  d: path("M10.966 18.769c.325-.003.516.178.57.27a2.2 2.2 0 0 0-.65.566c-.1.124-.278.17-.413.086a.266.266 0 0 1-.079-.39c.257-.329.48-.49.572-.532");
}

.cm3jz64eh {
  stop-color: var(--svg-color--34191a, #34191A);
}

.d--ofrihp {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.937 8.754h.988c0-.392-.221-.71-.494-.71s-.494.318-.494.71");
}

.d4kn2qv1f {
  stop-color: var(--svg-color--41212e, #41212E);
}

.ehlb6fbrs {
  stop-color: var(--svg-color--544b49, #544B49);
}

.fblnbo7cb {
  stop-color: var(--svg-color--614c49, #614C49);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fv64-xbqv {
  fill: var(--svg-color--442f2e, #442F2E);
  d: path("m11.013 18.17l.043.634a4.3 4.3 0 0 0-.603.608a.27.27 0 0 1-.345.059c-.118-.073-.161-.224-.085-.339c.311-.472.794-.844.99-.961");
}

.fwheo7gdw {
  stop-color: var(--svg-color--60608e, #60608E);
}

.fy99v1bac {
  stop-color: var(--svg-color--897694, #897694);
}

.fyyb5wxvb {
  d: path("M12.184 27.542a6.3 6.3 0 0 0-1.412-.643q0 .008.003.014c-.433.175-1.005.467-1.55.746l-.517.262c-.324.163-.533.495-.443.847a.26.26 0 0 0 .252.196h3.43a.25.25 0 0 0 .25-.253z");
}

.g7ee89odc {
  stop-color: var(--svg-color--3370b9, #3370B9);
}

.gg3gfcb3s {
  d: path("m15.099 17.1l-.04-.78l1.892-.126c.046.664.117 1.594-.149 1.985c-.266.39-.765.858-2.2.945a42 42 0 0 1-3.269.031v-.18h-.672l-.34-.214c-.038-.192.39-.568.79-.711c1.253-.45 2.96-.82 3.988-.95");
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gwwxm_bpq {
  stop-color: var(--svg-color--857297, #857297);
  stop-opacity: 0;
}

.gz7zsacgq {
  d: path("M12.43 7.96c.039-.801.298-1.188.42-1.3h3.733l.062 3.163c-.866 2.122-3.511 2.213-3.906 1.445c-.395-.767-.354-2.38-.309-3.308");
}

.h0kx4wbgv {
  d: path("M13.542 8.754V8.75c0-.32-.137-.58-.307-.58s-.306.26-.306.58v.004z");
}

.hc1x_wbbe {
  stop-color: var(--svg-color--4aa9ee, #4AA9EE);
  stop-opacity: 0;
}

.hrqvsac6m {
  stop-color: var(--svg-color--614c49, #614C49);
}

.i05bi9b5w {
  d: path("M12.206 8.924a1 1 0 0 0 .258-.457h.18v1.125c-.215.136-.522.115-.614-.09c-.078-.176-.02-.395.176-.578");
}

.i59-3w3cd {
  d: path("m13.347 8.754l.004-.073c0-.185-.08-.336-.176-.336c-.097 0-.176.15-.176.336q0 .038.004.073z");
}

.ifze1vbqw {
  stop-color: var(--svg-color--605f91, #605F91);
  stop-opacity: 0;
}

.jje8gccwz {
  stop-color: var(--svg-color--605f91, #605F91);
}

.k1dl65w8i {
  stop-color: var(--svg-color--3f2d7e, #3F2D7E);
}

.kh4m-x6vr {
  fill: var(--svg-color--968ba1, #968BA1);
  d: path("M9.65 22.132c.137.575.807 3.427 1.125 4.781c-.573.232-1.39.668-2.067 1.008c-.324.163-.533.495-.443.847a.26.26 0 0 0 .252.196h3.43a.25.25 0 0 0 .25-.253l-.076-7.169c1.787.442 3.937.808 5.747.262c1.2-.363 1.266-1.817 1.266-2.875l-7.61.078a2.726 2.726 0 0 0-1.874 3.125");
}

.kpqoceb4x {
  d: path("M14.69 13.636a1.261 1.261 0 0 1 2.52-.119l.155 2.775l-2.567.152z");
}

.ku5md_ocu {
  d: path("m21.89 25.788l-.885.75l.406 1.5c.391.198 1.35.653 2.063.89c.547.183.887.06 1.056-.083c.078-.065.066-.178 0-.257l-2.286-2.769a.25.25 0 0 0-.354-.031");
}

.kxqsybbxp {
  cx: 13.11px;
  cy: 8.402px;
  rx: 0.064px;
  ry: 0.088px;
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

.l3pib11wq {
  d: path("M12.121 21.545v-.003c1.787.442 3.937.808 5.748.262c1.2-.363 1.265-1.817 1.265-2.875l-7.61.078a3.2 3.2 0 0 0-.701.336z");
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

.lu7jcxbxj {
  stop-color: var(--svg-color--34191a, #34191A);
  stop-opacity: 0;
}

.n3xu87-4f {
  stop-color: var(--svg-color--1d0d23, #1D0D23);
}

.n6csxrxuy {
  stop-color: var(--svg-color--4ba6ed, #4BA6ED);
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.naoj9jbij {
  stop-color: var(--svg-color--544340, #544340);
  stop-opacity: 0;
}

.ndh-ggbqf {
  stop-color: var(--svg-color--544340, #544340);
}

.nu9hhfe4u {
  stop-color: var(--svg-color--774e55, #774E55);
}

.numeh5b7w {
  stop-color: var(--svg-color--443534, #443534);
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o3zdgescu {
  fill: var(--svg-color--493033, #493033);
  d: path("m15.099 17.1l-.04-.78l1.892-.126c.046.664.117 1.594-.149 1.985c-.266.39-.765.858-2.2.945a42 42 0 0 1-3.269.031v-.18h-.672l-.34-.214c-.038-.192.39-.568.79-.711c1.253-.45 2.96-.82 3.988-.95");
}

.o5l8xobeq {
  stop-color: var(--svg-color--472f2c, #472F2C);
}

.obkbkpctx {
  stop-color: var(--svg-color--4ba6ed, #4BA6ED);
  stop-opacity: 0;
}

.ofo46gsuq {
  stop-color: var(--svg-color--439ff0, #439FF0);
}

.ojh1fleoa {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M17.622 21.616c-.138.941-.573 3.264-1.239 5.338a.5.5 0 0 0 .152.535a.55.55 0 0 0 .538.086c.689-.244 2.053-.526 3.737-.302");
}

.olt5ljabw {
  stop-color: var(--svg-color--3f3e62, #3F3E62);
}

.om366ybrp {
  stop-color: var(--svg-color--3d292a, #3D292A);
}

.oo0a8g8xe {
  stop-color: var(--svg-color--4aa9ee, #4AA9EE);
}

.oy9f4cbur {
  stop-color: var(--svg-color--60608e, #60608E);
  stop-opacity: 0;
}

.plhowgx4z {
  stop-color: var(--svg-color--472f2c, #472F2C);
  stop-opacity: 0;
}

.pqpq_lljy {
  stop-color: var(--svg-color--3f2d7e, #3F2D7E);
  stop-opacity: 0;
}

.q_g8mnbhc {
  stop-color: var(--svg-color--766b81, #766B81);
  stop-opacity: 0;
}

.qbinlrgys {
  d: path("M14.091 14.151c-.162 1.15-.094 2.637.016 3.528v1.289h5.031c-.055-2.063-.578-4.728-1.367-6.047c-.664-1.11-1.422-1.176-2.055-.957c-.605.183-1.422.75-1.625 2.187");
}

.qvi3m-3ib {
  stop-color: var(--svg-color--464143, #464143);
}

.r0lz-mt_g {
  fill: var(--svg-color--280017, #280017);
  fill-rule: evenodd;
  d: path("M13.682 9.867a.125.125 0 0 1-.002.177c-.238.234-.582.293-.692.305a.125.125 0 0 1-.025-.249c.094-.01.366-.062.542-.234a.125.125 0 0 1 .177.001");
}

.ri3n41bmg {
  fill: var(--svg-color--97919f, #97919F);
  d: path("M15.145 26.64c-.05-1.838.195-4.492.32-5.57l3.484-.696c-.554 3.344-1.328 5.508-1.687 6.266c1.062-.266 2.578-.172 3.765-.117l.391 1.515c-1.234.125-3.34.523-3.844.648c-.562.141-2.371.086-2.43-2.046");
}

.rmzxn5bsn {
  fill: var(--svg-color--2c2929, #2C2929);
  fill-rule: evenodd;
  d: path("M13.706 7.897c-.147-.106-.362-.111-.5-.111a.2.2 0 0 1 0-.4h.01c.128 0 .463 0 .723.186a.2.2 0 1 1-.233.325");
}

.s-vq7hbns {
  fill: var(--svg-color--443c7f, #443C7F);
  d: path("m21.89 25.788l-.885.75l.406 1.5c.391.198 1.35.653 2.063.89c.547.183.887.06 1.056-.083c.078-.065.066-.178 0-.257l-2.286-2.769a.25.25 0 0 0-.354-.031");
}

.s9z3jkbdd {
  d: path("M15.145 26.64c-.05-1.838.195-4.492.32-5.57l3.484-.696c-.554 3.344-1.328 5.508-1.687 6.266c1.062-.266 2.578-.172 3.765-.117l.391 1.515c-1.234.125-3.34.523-3.844.648c-.562.141-2.371.086-2.43-2.046");
}

.sd2k4tbbl {
  stop-color: var(--svg-color--251a23, #251A23);
}

.ss7zei8xw {
  stop-color: var(--svg-color--68534f, #68534F);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.sx_wpgngv {
  stop-color: var(--svg-color--464143, #464143);
  stop-opacity: 0;
}

.t_vl9fbku {
  stop-color: var(--svg-color--8f7c7f, #8F7C7F);
  stop-opacity: 0;
}

.tr7t_rbgt {
  d: path("M9.65 22.132c.137.575.807 3.427 1.125 4.781c-.573.232-1.39.668-2.067 1.008c-.324.163-.533.495-.443.847a.26.26 0 0 0 .252.196h3.43a.25.25 0 0 0 .25-.253l-.076-7.169c1.787.442 3.937.808 5.747.262c1.2-.363 1.266-1.817 1.266-2.875l-7.61.078a2.726 2.726 0 0 0-1.874 3.125");
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

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.ve-3ak5rg {
  stop-color: var(--svg-color--48302c, #48302C);
  stop-opacity: 0;
}

.vepd3j-1j {
  d: path("m15.2 9.414l.2-1.44a.727.727 0 0 1-.2 1.44");
}

.xgk77dt3o {
  stop-color: var(--svg-color--3f3e62, #3F3E62);
  stop-opacity: 0;
}

.xojzxxboq {
  stop-color: var(--svg-color--574241, #574241);
  stop-opacity: 0;
}

.xv-sacbws {
  stop-color: var(--svg-color--544b49, #544B49);
  stop-opacity: 0;
}

.xv9roqx4c {
  stop-color: var(--svg-color--7e5e9a, #7E5E9A);
}

.yivr38b3w {
  d: path("M13.07 7.207c-.657 0-.97-.371-1-.836c0-.657.5-.796.694-.817c.22-.023.305-.047.61-.261a.9.9 0 0 1 .91-.098c.148.07.476.105.71.035c.392-.117.696-.113.997.117c.209.16.363.16.613.16c.344 0 .636.154.856.32c.657.498.582 2.208.258 3.169c-.31.92-.778 1.027-1.168.992c-.47-.042-.59-.399-.66-.695c-.057-.238-.201-.99-.266-1.238c-.136-.062-.431-.086-.532-.473c-.1-.388-.492-.432-.757-.407c-.162.016-.61.032-1.266.032");
}

.ylstrmb2p {
  d: path("m10.732 21.468l.656 5.492l.313.125l-.43-5.73a.487.487 0 0 1 .481-.528c.926-.006 3.848 0 4.542 0c.813 0 1.094-.273 1.094-.648c-1.193-.01-4.677-.025-5.664 0s-1.039.862-.992 1.289");
}

.yqah6ebzx {
  stop-color: var(--svg-color--443534, #443534);
  stop-opacity: 0;
}

.zpg97tbto {
  stop-color: var(--svg-color--432b2f, #432B2F);
}

</style>
