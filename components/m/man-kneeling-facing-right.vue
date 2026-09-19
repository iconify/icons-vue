<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iNFfVqN)"><path class="bjvd-sb3y"/></g><g filter="url(#i2wOJlb)"><path stroke="url(#iVVQcUd)" class="dqeezuryw"/></g><path fill="url(#iskXoee)" class="imnkx9bdk"/><g filter="url(#iU6Upfe)"><path class="a5y-b-r0a"/></g><path fill="url(#iNk50gc)" class="hzh6l3bzz"/><path fill="url(#iZElbee)" class="hzh6l3bzz"/><path fill="url(#iBP8yDd)" class="lz9t8o9wv"/><g filter="url(#iNsZZVK)"><path class="m8_3k6boh"/><path fill="url(#iAYuCdd)" class="q2ucym9nt"/><path fill="url(#ihastRb)" class="q2ucym9nt"/></g><g filter="url(#ibT9h6d)"><path class="t63k-8bgz"/><path fill="url(#iKWyxzz)" class="w4enui6bm"/><path fill="url(#iM1lpZc)" class="w4enui6bm"/></g><path fill="url(#ioPrcxe)" transform="scale(-1 1)rotate(-14.867 31.211 73.056)" class="ofkpelbcu"/><path fill="url(#iq7N0uW)" class="fb232rble"/><path fill="url(#izSQ2rb)" class="fb232rble"/><path fill="url(#iQLheqc)" class="fb232rble"/><g filter="url(#ipCBAkb)"><path class="l-5zjzbqk"/><path fill="url(#iLBb3Td)" class="t236wobrv"/></g><g filter="url(#i3z5Tte)"><path class="qlrf3zbcw"/></g><g filter="url(#iOntE0b)"><path class="n55tb7b3i"/></g><path fill="url(#il80qwb)" class="padpgu-gg"/><path fill="url(#iDZ9Bpd)" class="padpgu-gg"/><g filter="url(#iMMDLQH)"><path fill="url(#iT2Hv5I)" class="v2fgqhxbh"/></g><path fill="url(#ilAuijc)" class="th09rbbxt"/><g filter="url(#itHJSst)"><path fill="url(#ixGzQld)" class="iq0jgbwyu"/><path fill="url(#ifx5xsc)" class="iq0jgbwyu"/></g><g filter="url(#i1QzoMe)"><path fill="url(#idAgILe)" class="u06r9t4db"/></g><path fill="url(#iDJ7x4r)" class="u06r9t4db"/><path fill="url(#ieVDLlb)" class="o_4b6nbkj"/><path clip-rule="evenodd" class="a2l3u_bak"/><path class="tnv0cvbgj"/><path fill="url(#iPnzPFc)" class="ypn56962e"/><path fill="url(#iTA8X7d)" class="fnrsegbyu"/><ellipse fill="url(#ipECBte)" transform="scale(-1 1)rotate(24.61 -28.47 -39.202)" class="m1l7k9jve"/><g filter="url(#ixkkcqa)"><path class="tk1w47bjp"/></g><defs><radialGradient id="iVVQcUd" cx="0" cy="0" r="1" gradientTransform="rotate(-130.67 14.067 10.256)scale(5.34656 3.97082)" gradientUnits="userSpaceOnUse"><stop class="lt2_2ybqi"/><stop offset="1" class="bils69brp"/></radialGradient><radialGradient id="iskXoee" cx="0" cy="0" r="1" gradientTransform="matrix(.53125 3.29646 -1.78135 .28708 15.362 21.257)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="bmj_fbbea"/><stop offset="1" class="q_g8mnbhc"/></radialGradient><radialGradient id="iZElbee" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03125 -5.37969 0 18.737 18.929)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="nu9hhfe4u"/><stop offset="1" class="t_vl9fbku"/></radialGradient><radialGradient id="iBP8yDd" cx="0" cy="0" r="1" gradientTransform="matrix(.1094 3.14063 -8.2876 .28869 17.143 19.038)" gradientUnits="userSpaceOnUse"><stop offset=".558" class="gwwxm_bpq"/><stop offset=".971" class="xv9roqx4c"/></radialGradient><radialGradient id="ioPrcxe" cx="0" cy="0" r="1" gradientTransform="matrix(1.75062 .2869 -.80955 4.93989 .09 1.583)" gradientUnits="userSpaceOnUse"><stop class="zogc6l03v"/><stop offset="1" class="e1qh__bvr"/></radialGradient><radialGradient id="iq7N0uW" cx="0" cy="0" r="1" gradientTransform="matrix(3.45312 4 -4.99487 4.31198 13.909 14.554)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="b2o3a7r9l"/><stop offset="1" class="g7ee89odc"/></radialGradient><radialGradient id="izSQ2rb" cx="0" cy="0" r="1" gradientTransform="matrix(2.03122 3.14064 -3.13218 2.02576 14.346 12.679)" gradientUnits="userSpaceOnUse"><stop class="oo0a8g8xe"/><stop offset="1" class="hc1x_wbbe"/></radialGradient><radialGradient id="iQLheqc" cx="0" cy="0" r="1" gradientTransform="matrix(3.73437 .23436 -.4261 6.78981 14.423 16.303)" gradientUnits="userSpaceOnUse"><stop offset=".563" class="brpomvbii"/><stop offset="1" class="lmk5_gb2n"/></radialGradient><radialGradient id="iLBb3Td" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.04687 -1.5625 0 15.19 16.679)" gradientUnits="userSpaceOnUse"><stop class="m8h2-hfui"/><stop offset="1" class="q2n0f68xb"/></radialGradient><radialGradient id="iDZ9Bpd" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 1.04686 -.99542 1.2183 14.789 12.678)" gradientUnits="userSpaceOnUse"><stop class="n6csxrxuy"/><stop offset="1" class="obkbkpctx"/></radialGradient><radialGradient id="ilAuijc" cx="0" cy="0" r="1" gradientTransform="matrix(-.3125 .60583 -.77155 -.39799 19.962 9.072)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="fvok_qxen"/><stop offset="1" class="suyap8bzv"/></radialGradient><radialGradient id="ifx5xsc" cx="0" cy="0" r="1" gradientTransform="matrix(1.21022 -.08859 .108 1.4755 16.423 8.658)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="d7kch3t0q"/><stop offset="1" class="admd7db0k"/></radialGradient><radialGradient id="idAgILe" cx="0" cy="0" r="1" gradientTransform="matrix(3.4375 3.125 -3.54355 3.8979 14.43 5.996)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="jve2rcqoj"/><stop offset="1" class="kpbiulbbs"/></radialGradient><radialGradient id="iDJ7x4r" cx="0" cy="0" r="1" gradientTransform="matrix(.11717 -1.30469 2.76647 .24846 15.064 10.192)" gradientUnits="userSpaceOnUse"><stop offset=".064" class="jfv70ccah"/><stop offset="1" class="b30rr0b3q"/></radialGradient><radialGradient id="ieVDLlb" cx="0" cy="0" r="1" gradientTransform="matrix(.45312 .9414 -1.52974 .7363 16.118 8.478)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="bervkqbmz"/><stop offset="1" class="c479w-bpn"/></radialGradient><radialGradient id="iPnzPFc" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 0 0 -.53125 18.786 8.732)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iTA8X7d" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 0 0 -.54102 18.954 8.754)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><filter id="iNFfVqN" width="7.28" height="8.609" x="10.582" y="20.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1904"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.466667 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_1904" result="effect2_innerShadow_2_1904"/></filter><filter id="i2wOJlb" width="5.734" height="7.279" x="10.657" y="21.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_1904" stdDeviation=".25"/></filter><filter id="iU6Upfe" width="11.64" height="10.135" x="12.866" y="18.929" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.490196 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1904"/></filter><filter id="iNsZZVK" width="4.352" height="2.364" x="19.803" y="26.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.254902 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1904"/></filter><filter id="ibT9h6d" width="3.579" height="3.542" x="7.416" y="25.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.168627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1904"/></filter><filter id="ipCBAkb" width="6.876" height="3.179" x="15.005" y="15.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1904"/></filter><filter id="i3z5Tte" width="1.171" height="1.539" x="20.944" y="17.971" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.6 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1904"/></filter><filter id="iOntE0b" width="1.196" height="1.065" x="20.464" y="18.669" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.6 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1904"/></filter><filter id="iMMDLQH" width="8.168" height="8.42" x="13.862" y="19.415" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_1904" stdDeviation=".375"/></filter><filter id="itHJSst" width="4.443" height="5.249" x="15.155" y="6.459" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.52549 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1904"/></filter><filter id="i1QzoMe" width="6.391" height="5.479" x="13.623" y="4.815" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.835294 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1904"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.592157 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_1904" result="effect2_innerShadow_2_1904"/></filter><filter id="ixkkcqa" width="1.117" height=".649" x="17.977" y="7.386" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.2 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1904"/></filter><linearGradient id="iNk50gc" x1="14.8" x2="14.8" y1="18.835" y2="19.366" gradientUnits="userSpaceOnUse"><stop class="fy99v1bac"/><stop offset="1" class="l0bg_dlbj"/></linearGradient><linearGradient id="iAYuCdd" x1="19.675" x2="20.659" y1="28.101" y2="28.101" gradientUnits="userSpaceOnUse"><stop class="jje8gccwz"/><stop offset="1" class="ifze1vbqw"/></linearGradient><linearGradient id="ihastRb" x1="21.112" x2="21.112" y1="28.964" y2="28.593" gradientUnits="userSpaceOnUse"><stop class="k1dl65w8i"/><stop offset="1" class="pqpq_lljy"/></linearGradient><linearGradient id="iKWyxzz" x1="10.649" x2="9.964" y1="26.054" y2="26.718" gradientUnits="userSpaceOnUse"><stop class="olt5ljabw"/><stop offset="1" class="xgk77dt3o"/></linearGradient><linearGradient id="iM1lpZc" x1="8.503" x2="8.718" y1="27.257" y2="27.429" gradientUnits="userSpaceOnUse"><stop offset=".098" class="fwheo7gdw"/><stop offset="1" class="oy9f4cbur"/></linearGradient><linearGradient id="il80qwb" x1="14.82" x2="17.311" y1="15.304" y2="15.382" gradientUnits="userSpaceOnUse"><stop class="ofo46gsuq"/><stop offset="1" class="lq0qk0brb"/></linearGradient><linearGradient id="iT2Hv5I" x1="21.28" x2="14.799" y1="25.851" y2="19.913" gradientUnits="userSpaceOnUse"><stop offset=".552" class="cl3ijcbld"/><stop offset="1" class="v224y-b0w"/></linearGradient><linearGradient id="ixGzQld" x1="16.735" x2="19.598" y1="9.4" y2="9.572" gradientUnits="userSpaceOnUse"><stop class="sh1u5ab0i"/><stop offset="1" class="yru3_4bbx"/></linearGradient><linearGradient id="ipECBte" x1="-.007" x2=".179" y1=".05" y2=".11" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-kneeling-facing-right" /></template>
<style>
.a2l3u_bak {
  fill: var(--svg-color--87014d, #87014D);
  fill-rule: evenodd;
  d: path("M18.318 9.867a.125.125 0 0 0 .002.177c.238.234.582.293.692.305a.125.125 0 0 0 .025-.249c-.093-.01-.366-.062-.542-.234a.125.125 0 0 0-.177.001");
}

.a5y-b-r0a {
  fill: var(--svg-color--968ba1, #968BA1);
  d: path("M22.35 22.132c-.137.575-.807 3.427-1.125 4.781c.573.232 1.39.668 2.067 1.008c.324.163.533.495.443.847a.26.26 0 0 1-.252.196h-3.43a.25.25 0 0 1-.25-.253l.076-7.169c-1.787.442-3.937.808-5.747.262c-1.2-.363-1.266-1.817-1.266-2.875l7.61.078a2.726 2.726 0 0 1 1.874 3.125");
}

.admd7db0k {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
  stop-opacity: 0;
}

.b2o3a7r9l {
  stop-color: var(--svg-color--45a7f8, #45A7F8);
}

.b30rr0b3q {
  stop-color: var(--svg-color--ef9926, #EF9926);
  stop-opacity: 0;
}

.bervkqbmz {
  stop-color: var(--svg-color--ffd040, #FFD040);
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

.c479w-bpn {
  stop-color: var(--svg-color--fead30, #FEAD30);
}

.cl3ijcbld {
  stop-color: var(--svg-color--a098a8, #A098A8);
}

.d7kch3t0q {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
}

.dqeezuryw {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M14.378 21.616c.138.941.573 3.264 1.239 5.338a.5.5 0 0 1-.152.535a.55.55 0 0 1-.538.086c-.689-.244-2.053-.526-3.737-.302");
}

.e1qh__bvr {
  stop-color: var(--svg-color--ffd342, #FFD342);
}

.fb232rble {
  d: path("M17.909 14.151c.162 1.15.094 2.637-.016 3.528v1.289h-5.031c.055-2.063.578-4.728 1.367-6.047c.664-1.11 1.422-1.176 2.055-.957c.605.183 1.422.75 1.625 2.187");
}

.fnrsegbyu {
  d: path("m18.654 8.754l-.005-.073c0-.185.08-.336.176-.336c.097 0 .176.15.176.336l-.004.073z");
}

.ft5dv1b6b {
  fill: none;
}

.fvok_qxen {
  stop-color: var(--svg-color--ffbf42, #FFBF42);
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

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gwwxm_bpq {
  stop-color: var(--svg-color--857297, #857297);
  stop-opacity: 0;
}

.hc1x_wbbe {
  stop-color: var(--svg-color--4aa9ee, #4AA9EE);
  stop-opacity: 0;
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

.iq0jgbwyu {
  d: path("M19.57 7.96c-.039-.801-.298-1.188-.42-1.3h-3.733l-.062 3.163c.866 2.122 3.511 2.213 3.906 1.445c.395-.767.354-2.38.309-3.308");
}

.jfv70ccah {
  stop-color: var(--svg-color--b28146, #B28146);
}

.jje8gccwz {
  stop-color: var(--svg-color--605f91, #605F91);
}

.jve2rcqoj {
  stop-color: var(--svg-color--ffbc2b, #FFBC2B);
}

.k1dl65w8i {
  stop-color: var(--svg-color--3f2d7e, #3F2D7E);
}

.kpbiulbbs {
  stop-color: var(--svg-color--ffa629, #FFA629);
}

.l-5zjzbqk {
  fill: var(--svg-color--ffbf36, #FFBF36);
  d: path("m16.901 17.1l.04-.78l-1.891-.126c-.047.664-.118 1.594.148 1.985c.266.39.765.858 2.2.945a42 42 0 0 0 3.269.031v-.18h.672l.34-.214c.039-.192-.39-.568-.79-.711c-1.253-.45-2.96-.82-3.988-.95");
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l0bg_dlbj {
  stop-color: var(--svg-color--897694, #897694);
  stop-opacity: 0;
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

.m8h2-hfui {
  stop-color: var(--svg-color--ffc93e, #FFC93E);
}

.n55tb7b3i {
  fill: var(--svg-color--f6b22f, #F6B22F);
  d: path("M21.034 18.769c-.325-.003-.516.178-.57.27c.271.143.499.375.65.566c.1.124.278.17.413.086a.266.266 0 0 0 .079-.39c-.257-.329-.48-.49-.572-.532");
}

.n6csxrxuy {
  stop-color: var(--svg-color--4ba6ed, #4BA6ED);
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.nu9hhfe4u {
  stop-color: var(--svg-color--774e55, #774E55);
}

.o_4b6nbkj {
  d: path("M16.708 9.42c.05 0 .085-.047.079-.096l-.174-1.25c-.007-.054-.059-.093-.112-.078a.727.727 0 0 0 .207 1.424");
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

.padpgu-gg {
  d: path("M17.31 13.636a1.261 1.261 0 0 0-2.52-.119l-.155 2.775l2.567.152z");
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

.q2ucym9nt {
  d: path("M19.816 27.542a6.3 6.3 0 0 1 1.413-.643l-.004.014c.433.175 1.005.467 1.55.746l.517.262c.324.163.533.495.443.847a.26.26 0 0 1-.252.196h-3.43a.25.25 0 0 1-.25-.253z");
}

.qlrf3zbcw {
  fill: var(--svg-color--eeae2f, #EEAE2F);
  d: path("m20.987 18.17l-.043.634c.233.181.452.427.603.608a.27.27 0 0 0 .345.059c.118-.073.161-.224.085-.339a3.6 3.6 0 0 0-.99-.961");
}

.sh1u5ab0i {
  stop-color: var(--svg-color--ffb535, #FFB535);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.suyap8bzv {
  stop-color: var(--svg-color--eba544, #EBA544);
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

.th09rbbxt {
  d: path("M19.794 8.924a1 1 0 0 1-.258-.457h-.18v1.125c.215.136.522.115.614-.09c.078-.176.02-.395-.176-.578");
}

.tk1w47bjp {
  stroke: var(--svg-color--bc5f4e, #BC5F4E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.794 7.586c-.129 0-.41 0-.617.148");
}

.tnv0cvbgj {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.064 8.754h-.989c0-.392.221-.71.494-.71s.495.318.495.71");
}

.u06r9t4db {
  d: path("M18.814 7.207c.656 0 .968-.371 1-.836c0-.657-.501-.796-.696-.817c-.218-.023-.304-.047-.609-.261a.9.9 0 0 0-.91-.098c-.149.07-.477.105-.711.035c-.39-.117-.695-.113-.996.117c-.21.16-.363.16-.613.16c-.344 0-.636.154-.856.32c-.657.498-.582 2.208-.258 3.169c.31.92.778 1.027 1.168.992c.47-.042.59-.399.66-.695c.057-.238.2-.792.266-1.04c.135-.062.431-.284.531-.671s.493-.432.758-.407c.162.016.61.032 1.266.032");
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

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.w4enui6bm {
  d: path("m10.11 25.788l.885.75l-.406 1.5c-.391.198-1.35.653-2.063.89c-.547.183-.887.06-1.056-.083c-.078-.065-.066-.178 0-.257l2.285-2.769a.25.25 0 0 1 .355-.031");
}

.xgk77dt3o {
  stop-color: var(--svg-color--3f3e62, #3F3E62);
  stop-opacity: 0;
}

.xv9roqx4c {
  stop-color: var(--svg-color--7e5e9a, #7E5E9A);
}

.ypn56962e {
  d: path("M18.458 8.754V8.75c0-.32.137-.58.307-.58s.306.26.306.58v.004z");
}

.yru3_4bbx {
  stop-color: var(--svg-color--fbb434, #FBB434);
}

.zogc6l03v {
  stop-color: var(--svg-color--d49944, #D49944);
}

</style>
