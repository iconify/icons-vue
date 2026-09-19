<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iLF65ce)"><path class="sam0_9b6t"/></g><g filter="url(#iAq6WQd)"><path stroke="url(#iC6WfEd)" class="p7_7su-bq"/></g><path fill="url(#iG7KyUb)" class="qente3pnv"/><g filter="url(#iKLOuDb)"><path class="gd2gs2lnz"/></g><path fill="url(#ikXdvyd)" class="n8-rlbf4l"/><path fill="url(#ivf7Yoe)" class="n8-rlbf4l"/><path fill="url(#izWg1vd)" class="ybl94coej"/><g filter="url(#ipBaQdz)"><path class="v5s110bir"/><path fill="url(#i2FJsZc)" class="adicfhbgs"/><path fill="url(#ibD2GOd)" class="adicfhbgs"/></g><g filter="url(#iNyo5ic)"><path class="vat52j4mu"/><path fill="url(#i7Muxya)" class="r3vpeib4v"/><path fill="url(#idYNkwd)" class="r3vpeib4v"/></g><path fill="url(#inPqEwd)" transform="scale(-1 1)rotate(-14.867 33.859 75.015)" class="ofkpelbcu"/><path fill="url(#iNNzSbe)" class="kdqkxwb3b"/><path fill="url(#iHvDoAc)" class="kdqkxwb3b"/><path fill="url(#icjdjJc)" class="kdqkxwb3b"/><path fill="url(#iTTJ7lz)" class="kdqkxwb3b"/><g filter="url(#is8yHdz)"><path class="zq6h8rsjo"/><path fill="url(#iPA1xId)" class="zcmwu3fic"/></g><g filter="url(#icqmvYd)"><path class="ejtx4nurx"/></g><g filter="url(#ireE99d)"><path class="mhi6n6bpg"/></g><path fill="url(#iahllyp)" class="bln-e6p3x"/><path fill="url(#iAlj2dc)" class="bln-e6p3x"/><path fill="url(#iack6Ge)" class="bln-e6p3x"/><g filter="url(#igA3L4d)"><path fill="url(#iVhUPVd)" class="l7jtjqbfa"/></g><path fill="url(#ivEFmdc)" class="oyehpccfd"/><g filter="url(#iIV4N1b)"><path fill="url(#iGfmZcb)" class="k8tuyjrol"/><path fill="url(#iHrJpyc)" class="k8tuyjrol"/></g><g filter="url(#ieMgvkd)"><path class="l5lmx1bfh"/></g><path fill="url(#iaw9BZl)" class="snp7r7bfz"/><path fill="url(#iUuObUb)" class="zj4m-sbbq"/><path clip-rule="evenodd" class="l8s8c2bsj"/><g filter="url(#idxSKCc)"><path clip-rule="evenodd" class="hl5yqy78p"/></g><path class="c6hk3kafv"/><path class="dk7s-swgz"/><path fill="url(#iqKQS7c)" class="yf9sqsbvb"/><path fill="url(#iKMK55C)" class="y2h7fhbpy"/><ellipse fill="url(#ipECBte)" transform="scale(-1 1)rotate(24.61 -30.362 -39.752)" class="m1l7k9jve"/><defs><radialGradient id="iC6WfEd" cx="0" cy="0" r="1" gradientTransform="rotate(-130.67 14.445 10.533)scale(5.34656 3.97082)" gradientUnits="userSpaceOnUse"><stop class="lt2_2ybqi"/><stop offset="1" class="bils69brp"/></radialGradient><radialGradient id="iG7KyUb" cx="0" cy="0" r="1" gradientTransform="matrix(.53125 3.29646 -1.78135 .28708 15.776 22.002)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="bmj_fbbea"/><stop offset="1" class="q_g8mnbhc"/></radialGradient><radialGradient id="ivf7Yoe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03125 -5.37969 0 19.151 19.674)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="nu9hhfe4u"/><stop offset="1" class="t_vl9fbku"/></radialGradient><radialGradient id="izWg1vd" cx="0" cy="0" r="1" gradientTransform="matrix(.1094 3.14063 -8.2876 .28869 17.557 19.782)" gradientUnits="userSpaceOnUse"><stop offset=".558" class="gwwxm_bpq"/><stop offset=".971" class="xv9roqx4c"/></radialGradient><radialGradient id="inPqEwd" cx="0" cy="0" r="1" gradientTransform="rotate(-28.776 4.415 1.215)scale(2.02961 1.85514)" gradientUnits="userSpaceOnUse"><stop offset=".397" class="pc2bqsb8g"/><stop offset="1" class="l4bg9bbjp"/></radialGradient><radialGradient id="iNNzSbe" cx="0" cy="0" r="1" gradientTransform="matrix(3.45312 4 -4.99487 4.31198 14.323 15.299)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="ai9smcbyp"/><stop offset=".849" class="j-pea3b4d"/></radialGradient><radialGradient id="iHvDoAc" cx="0" cy="0" r="1" gradientTransform="matrix(1.23653 2.05948 -1.53634 .92244 15.555 14.505)" gradientUnits="userSpaceOnUse"><stop class="svuvwyb0s"/><stop offset="1" class="dlkt90brn"/></radialGradient><radialGradient id="icjdjJc" cx="0" cy="0" r="1" gradientTransform="matrix(3.73437 .23436 -.4261 6.78981 14.838 17.047)" gradientUnits="userSpaceOnUse"><stop offset=".723" class="z_p65vbje"/><stop offset="1" class="ql1m53bju"/></radialGradient><radialGradient id="iTTJ7lz" cx="0" cy="0" r="1" gradientTransform="matrix(.99016 -7.21552 5.43138 .74533 15.848 19.208)" gradientUnits="userSpaceOnUse"><stop offset=".792" class="qrku0gb0w"/><stop offset=".968" class="p7c3g0b3k"/></radialGradient><radialGradient id="iPA1xId" cx="0" cy="0" r="1" gradientTransform="scale(1.5625 2.04687)rotate(90 .737 9.25)" gradientUnits="userSpaceOnUse"><stop class="m8h2-hfui"/><stop offset="1" class="q2n0f68xb"/></radialGradient><radialGradient id="iAlj2dc" cx="0" cy="0" r="1" gradientTransform="rotate(51.841 -6.017 22.704)scale(1.35127 1.54455)" gradientUnits="userSpaceOnUse"><stop class="ove-epbrr"/><stop offset="1" class="h87azyork"/></radialGradient><radialGradient id="iack6Ge" cx="0" cy="0" r="1" gradientTransform="rotate(11.373 -75.937 84.923)scale(2.77321 5.18723)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="bd3uesbch"/><stop offset=".909" class="f-z_jdbvz"/></radialGradient><radialGradient id="ivEFmdc" cx="0" cy="0" r="1" gradientTransform="matrix(-.3125 .60583 -.77155 -.39799 20.363 9.81)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="cd4r3acma"/><stop offset="1" class="x767s0bmd"/></radialGradient><radialGradient id="iHrJpyc" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 -.04687 .05715 1.0287 16.824 9.396)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="d7kch3t0q"/><stop offset="1" class="admd7db0k"/></radialGradient><radialGradient id="iaw9BZl" cx="0" cy="0" r="1" gradientTransform="matrix(-.84375 5.57813 -4.53655 -.6862 16.131 7.218)" gradientUnits="userSpaceOnUse"><stop offset=".718" class="rmg76y8bk"/><stop offset="1" class="dgcxumb4u"/></radialGradient><radialGradient id="iUuObUb" cx="0" cy="0" r="1" gradientTransform="matrix(.45312 .9414 -1.52974 .7363 16.617 9.216)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="bervkqbmz"/><stop offset="1" class="c479w-bpn"/></radialGradient><radialGradient id="iqKQS7c" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 0 0 -.53125 19.187 9.47)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iKMK55C" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 0 0 -.54102 19.355 9.491)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><filter id="iLF65ce" width="7.28" height="8.609" x="10.996" y="20.869" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1875"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.466667 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_1875" result="effect2_innerShadow_2_1875"/></filter><filter id="iAq6WQd" width="5.734" height="7.279" x="11.071" y="21.825" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_1875" stdDeviation=".25"/></filter><filter id="iKLOuDb" width="11.64" height="10.135" x="13.28" y="19.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.490196 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1875"/></filter><filter id="ipBaQdz" width="4.352" height="2.364" x="20.218" y="27.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.254902 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1875"/></filter><filter id="iNyo5ic" width="3.579" height="3.542" x="7.83" y="26.223" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.168627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1875"/></filter><filter id="is8yHdz" width="6.876" height="3.179" x="15.419" y="16.739" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1875"/></filter><filter id="icqmvYd" width="1.171" height="1.539" x="21.358" y="18.716" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.6 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1875"/></filter><filter id="ireE99d" width="1.196" height="1.065" x="20.878" y="19.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.6 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1875"/></filter><filter id="igA3L4d" width="8.168" height="8.42" x="14.276" y="20.16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_1875" stdDeviation=".375"/></filter><filter id="iIV4N1b" width="4.493" height="5.449" x="15.506" y="6.997" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.54902 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1875"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.05"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.4 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_1875" result="effect2_innerShadow_2_1875"/></filter><filter id="ieMgvkd" width="7.013" height="7.503" x="13.347" y="5.436" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.843137 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1875"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.607843 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_1875" result="effect2_innerShadow_2_1875"/></filter><filter id="idxSKCc" width="1.013" height=".568" x="18.324" y="8.141" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.219608 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1875"/></filter><linearGradient id="ikXdvyd" x1="15.214" x2="15.214" y1="19.58" y2="20.111" gradientUnits="userSpaceOnUse"><stop class="fy99v1bac"/><stop offset="1" class="l0bg_dlbj"/></linearGradient><linearGradient id="i2FJsZc" x1="20.089" x2="21.073" y1="28.846" y2="28.846" gradientUnits="userSpaceOnUse"><stop class="jje8gccwz"/><stop offset="1" class="ifze1vbqw"/></linearGradient><linearGradient id="ibD2GOd" x1="21.526" x2="21.526" y1="29.709" y2="29.338" gradientUnits="userSpaceOnUse"><stop class="k1dl65w8i"/><stop offset="1" class="pqpq_lljy"/></linearGradient><linearGradient id="i7Muxya" x1="11.064" x2="10.378" y1="26.799" y2="27.463" gradientUnits="userSpaceOnUse"><stop class="olt5ljabw"/><stop offset="1" class="xgk77dt3o"/></linearGradient><linearGradient id="idYNkwd" x1="8.917" x2="9.132" y1="28.002" y2="28.174" gradientUnits="userSpaceOnUse"><stop offset=".098" class="fwheo7gdw"/><stop offset="1" class="oy9f4cbur"/></linearGradient><linearGradient id="iahllyp" x1="15.05" x2="17.115" y1="15.877" y2="15.97" gradientUnits="userSpaceOnUse"><stop class="d30p-0b3w"/><stop offset="1" class="cm74u7bos"/></linearGradient><linearGradient id="iVhUPVd" x1="21.694" x2="15.214" y1="26.596" y2="20.658" gradientUnits="userSpaceOnUse"><stop offset=".552" class="cl3ijcbld"/><stop offset="1" class="v224y-b0w"/></linearGradient><linearGradient id="iGfmZcb" x1="17.136" x2="19.998" y1="10.138" y2="10.31" gradientUnits="userSpaceOnUse"><stop class="sedutetcs"/><stop offset="1" class="yazmswbww"/></linearGradient><linearGradient id="ipECBte" x1="-.007" x2=".179" y1=".05" y2=".11" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-kneeling-facing-right" /></template>
<style>
.adicfhbgs {
  d: path("M20.23 28.287a6.3 6.3 0 0 1 1.413-.643l-.004.014c.433.175 1.005.467 1.55.746l.517.262c.325.162.533.495.443.847a.26.26 0 0 1-.252.196h-3.43a.25.25 0 0 1-.25-.253z");
}

.admd7db0k {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
  stop-opacity: 0;
}

.ai9smcbyp {
  stop-color: var(--svg-color--8672be, #8672BE);
}

.bd3uesbch {
  stop-color: var(--svg-color--79699e, #79699E);
  stop-opacity: 0;
}

.bervkqbmz {
  stop-color: var(--svg-color--ffd040, #FFD040);
}

.bils69brp {
  stop-color: var(--svg-color--a49dac, #A49DAC);
  stop-opacity: 0;
}

.bln-e6p3x {
  d: path("M17.724 14.381a1.261 1.261 0 0 0-2.519-.119l-.155 2.775l2.566.152z");
}

.bmj_fbbea {
  stop-color: var(--svg-color--6a5a7a, #6A5A7A);
}

.c479w-bpn {
  stop-color: var(--svg-color--fead30, #FEAD30);
}

.c6hk3kafv {
  fill: var(--svg-color--2f2c2d, #2F2C2D);
  d: path("M18.439 8.98c.131-.13.349-.16.441-.16l-.302.467c-.148-.008-.303-.143-.14-.307");
}

.cd4r3acma {
  stop-color: var(--svg-color--e9b03e, #E9B03E);
}

.cl3ijcbld {
  stop-color: var(--svg-color--a098a8, #A098A8);
}

.cm74u7bos {
  stop-color: var(--svg-color--725aaa, #725AAA);
}

.d30p-0b3w {
  stop-color: var(--svg-color--8f77c9, #8F77C9);
}

.d7kch3t0q {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
}

.dgcxumb4u {
  stop-color: var(--svg-color--a76445, #A76445);
}

.dk7s-swgz {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.464 9.491h-.988c0-.391.221-.709.494-.709s.494.318.494.71");
}

.dlkt90brn {
  stop-color: var(--svg-color--9c83d3, #9C83D3);
  stop-opacity: 0;
}

.ejtx4nurx {
  fill: var(--svg-color--eeae2f, #EEAE2F);
  d: path("m21.401 18.916l-.043.633c.233.181.452.427.603.608a.27.27 0 0 0 .346.058a.243.243 0 0 0 .085-.338a3.6 3.6 0 0 0-.99-.961");
}

.f-z_jdbvz {
  stop-color: var(--svg-color--79699e, #79699E);
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

.gd2gs2lnz {
  fill: var(--svg-color--968ba1, #968BA1);
  d: path("M22.764 22.877c-.137.575-.807 3.427-1.125 4.781c.573.232 1.39.668 2.067 1.008c.325.162.533.495.443.847a.26.26 0 0 1-.252.196h-3.43a.25.25 0 0 1-.25-.253l.076-7.17c-1.787.443-3.937.81-5.747.263c-1.2-.363-1.266-1.817-1.266-2.875l7.61.078a2.726 2.726 0 0 1 1.874 3.125");
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

.hl5yqy78p {
  fill: var(--svg-color--af5247, #AF5247);
  fill-rule: evenodd;
  d: path("M18.952 8.459a.8.8 0 0 1 .216-.016a.15.15 0 1 0 .038-.298a1 1 0 0 0-.313.02a1 1 0 0 0-.409.173a.15.15 0 1 0 .179.24c.084-.062.19-.1.288-.12");
}

.ifze1vbqw {
  stop-color: var(--svg-color--605f91, #605F91);
  stop-opacity: 0;
}

.j-pea3b4d {
  stop-color: var(--svg-color--7059a7, #7059A7);
}

.jje8gccwz {
  stop-color: var(--svg-color--605f91, #605F91);
}

.k1dl65w8i {
  stop-color: var(--svg-color--3f2d7e, #3F2D7E);
}

.k8tuyjrol {
  d: path("M19.97 8.698c-.038-.802-.297-1.188-.42-1.3h-3.732l-.062 3.163c.866 2.122 3.511 2.213 3.906 1.445c.395-.767.353-2.38.309-3.308");
}

.kdqkxwb3b {
  d: path("M18.323 14.896c.163 1.15.094 2.637-.015 3.528v1.289h-5.032c.055-2.063.578-4.729 1.367-6.047c.664-1.11 1.422-1.176 2.055-.957c.606.183 1.422.75 1.625 2.187");
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l0bg_dlbj {
  stop-color: var(--svg-color--897694, #897694);
  stop-opacity: 0;
}

.l4bg9bbjp {
  stop-color: var(--svg-color--bf6807, #BF6807);
}

.l5lmx1bfh {
  fill: var(--svg-color--ffb629, #FFB629);
  d: path("M20.09 7.35c.172-.41-.016-.843-.113-.991c-.367-.672-1.128-.717-1.567-.524c-.515.227-.669.347-1.503.11c-.837-.239-1.868-.13-2.407.84c-.539.968.047 2.058-.086 2.652c-.132.593-.512.652-.652 1.34c-.117.953.473 1.574.996 1.714c.524.141 1.602 0 1.953-.875c.576-1.431.184-2.109.31-2.828c.124-.718.554-.922 1.335-.765c.92.184 1.506-.126 1.734-.672");
}

.l7jtjqbfa {
  d: path("m21.683 22.213l-.657 5.492l-.312.125l.43-5.73a.487.487 0 0 0-.482-.528c-.926-.006-3.848 0-4.542 0c-.813 0-1.094-.273-1.094-.648c1.193-.01 4.677-.025 5.664 0s1.04.862.992 1.289");
}

.l8s8c2bsj {
  fill: var(--svg-color--87014d, #87014D);
  fill-rule: evenodd;
  d: path("M18.719 10.605a.125.125 0 0 0 .002.177c.238.233.582.293.692.304a.125.125 0 1 0 .025-.248c-.094-.01-.366-.062-.542-.235a.125.125 0 0 0-.177.002");
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

.m8h2-hfui {
  stop-color: var(--svg-color--ffc93e, #FFC93E);
}

.mhi6n6bpg {
  fill: var(--svg-color--f6b22f, #F6B22F);
  d: path("M21.448 19.513c-.325-.003-.516.179-.57.27c.271.144.499.376.65.567c.1.124.278.169.413.086a.266.266 0 0 0 .079-.39c-.257-.329-.48-.49-.572-.533");
}

.n8-rlbf4l {
  d: path("M22.764 22.877c-.137.575-.807 3.427-1.125 4.781c.573.232 1.39.668 2.067 1.008c.325.162.533.495.443.847a.26.26 0 0 1-.252.196h-3.43a.25.25 0 0 1-.25-.253l.076-7.17c-1.787.443-3.937.81-5.747.263c-1.2-.363-1.266-1.817-1.266-2.875l7.61.078a2.726 2.726 0 0 1 1.874 3.125");
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.nu9hhfe4u {
  stop-color: var(--svg-color--774e55, #774E55);
}

.ofkpelbcu {
  d: path("M0 0h1.976v2.198H0z");
}

.olt5ljabw {
  stop-color: var(--svg-color--3f3e62, #3F3E62);
}

.ove-epbrr {
  stop-color: var(--svg-color--9d84d5, #9D84D5);
}

.oy9f4cbur {
  stop-color: var(--svg-color--60608e, #60608E);
  stop-opacity: 0;
}

.oyehpccfd {
  d: path("M20.208 9.635c-.156-.147-.23-.405-.25-.497l-.2.066v1.125c.214.137.538.08.63-.124c.078-.176.015-.387-.18-.57");
}

.p7_7su-bq {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M14.792 22.361c.138.941.573 3.263 1.239 5.338a.5.5 0 0 1-.152.535a.55.55 0 0 1-.538.085c-.689-.243-2.053-.525-3.737-.302");
}

.p7c3g0b3k {
  stop-color: var(--svg-color--723b5b, #723B5B);
}

.pc2bqsb8g {
  stop-color: var(--svg-color--dc9e3c, #DC9E3C);
}

.pqpq_lljy {
  stop-color: var(--svg-color--3f2d7e, #3F2D7E);
  stop-opacity: 0;
}

.q_g8mnbhc {
  stop-color: var(--svg-color--766b81, #766B81);
  stop-opacity: 0;
}

.q2n0f68xb {
  stop-color: var(--svg-color--ffc93e, #FFC93E);
  stop-opacity: 0;
}

.qente3pnv {
  d: path("M17.27 27.385c.05-1.838-.196-4.493-.32-5.57l-3.485-.696c.555 3.344 1.328 5.508 1.687 6.265c-1.062-.265-2.578-.171-3.765-.117l-.39 1.516c1.233.125 3.339.522 3.843.648c.562.141 2.372.086 2.43-2.047");
}

.ql1m53bju {
  stop-color: var(--svg-color--786c9a, #786C9A);
}

.qrku0gb0w {
  stop-color: var(--svg-color--81547e, #81547E);
  stop-opacity: 0;
}

.r3vpeib4v {
  d: path("m10.524 26.533l.885.75l-.406 1.5c-.39.198-1.35.653-2.063.89c-.547.183-.887.06-1.056-.083c-.078-.065-.066-.179 0-.257l2.285-2.769a.25.25 0 0 1 .355-.031");
}

.rmg76y8bk {
  stop-color: var(--svg-color--fba522, #FBA522);
  stop-opacity: 0;
}

.sam0_9b6t {
  fill: var(--svg-color--97919f, #97919F);
  d: path("M17.27 27.385c.05-1.838-.196-4.493-.32-5.57l-3.485-.696c.555 3.344 1.328 5.508 1.687 6.265c-1.062-.265-2.578-.171-3.765-.117l-.39 1.516c1.233.125 3.339.522 3.843.648c.562.141 2.372.086 2.43-2.047");
}

.sedutetcs {
  stop-color: var(--svg-color--ffb536, #FFB536);
}

.snp7r7bfz {
  d: path("M20.09 7.35c.172-.41-.016-.843-.113-.991c-.367-.672-1.128-.717-1.567-.524c-.515.227-.669.347-1.503.11c-.837-.239-1.868-.13-2.407.84c-.539.968.047 2.058-.086 2.652c-.132.593-.512.652-.652 1.34c-.117.953.473 1.574.996 1.714c.524.141 1.602 0 1.953-.875c.576-1.431.184-2.109.31-2.828c.124-.718.554-.922 1.335-.765c.92.184 1.506-.126 1.734-.672");
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

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.v224y-b0w {
  stop-color: var(--svg-color--a098a8, #A098A8);
  stop-opacity: 0;
}

.v5s110bir {
  fill: var(--svg-color--55538a, #55538A);
  d: path("M20.23 28.287a6.3 6.3 0 0 1 1.413-.643l-.004.014c.433.175 1.005.467 1.55.746l.517.262c.325.162.533.495.443.847a.26.26 0 0 1-.252.196h-3.43a.25.25 0 0 1-.25-.253z");
}

.vat52j4mu {
  fill: var(--svg-color--443c7f, #443C7F);
  d: path("m10.524 26.533l.885.75l-.406 1.5c-.39.198-1.35.653-2.063.89c-.547.183-.887.06-1.056-.083c-.078-.065-.066-.179 0-.257l2.285-2.769a.25.25 0 0 1 .355-.031");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.x767s0bmd {
  stop-color: var(--svg-color--e29e3f, #E29E3F);
}

.xgk77dt3o {
  stop-color: var(--svg-color--3f3e62, #3F3E62);
  stop-opacity: 0;
}

.xv9roqx4c {
  stop-color: var(--svg-color--7e5e9a, #7E5E9A);
}

.y2h7fhbpy {
  d: path("m19.054 9.491l-.004-.072c0-.185.079-.336.176-.336s.176.15.176.336l-.004.072z");
}

.yazmswbww {
  stop-color: var(--svg-color--feb42f, #FEB42F);
}

.ybl94coej {
  d: path("M20.293 22.29v-.003c-1.787.442-3.937.808-5.747.262c-1.2-.363-1.266-1.817-1.266-2.875l7.61.078q.4.138.702.336z");
}

.yf9sqsbvb {
  d: path("M18.859 9.491v-.003c0-.32.137-.58.306-.58c.17 0 .307.26.307.58v.003z");
}

.z_p65vbje {
  stop-color: var(--svg-color--786c9a, #786C9A);
  stop-opacity: 0;
}

.zcmwu3fic {
  d: path("m17.315 17.846l.04-.782l-1.891-.125c-.047.664-.118 1.594.148 1.985c.266.39.765.858 2.2.945c1.03.062 2.618.057 3.269.031v-.18h.672l.34-.214c.038-.192-.39-.568-.79-.711c-1.254-.45-2.96-.82-3.988-.95");
}

.zj4m-sbbq {
  d: path("M17.207 10.158c.05 0 .085-.047.078-.097l-.173-1.248c-.008-.056-.06-.095-.112-.079a.727.727 0 0 0 .206 1.424");
}

.zq6h8rsjo {
  fill: var(--svg-color--ffbf36, #FFBF36);
  d: path("m17.315 17.846l.04-.782l-1.891-.125c-.047.664-.118 1.594.148 1.985c.266.39.765.858 2.2.945c1.03.062 2.618.057 3.269.031v-.18h.672l.34-.214c.038-.192-.39-.568-.79-.711c-1.254-.45-2.96-.82-3.988-.95");
}

</style>
