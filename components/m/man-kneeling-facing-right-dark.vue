<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i8Idqnb)"><path class="bjvd-sb3y"/></g><g filter="url(#ivQbkyI)"><path stroke="url(#iVVQcUd)" class="dqeezuryw"/></g><path fill="url(#iskXoee)" class="imnkx9bdk"/><g filter="url(#iGXjrHd)"><path class="a5y-b-r0a"/></g><path fill="url(#iNk50gc)" class="hzh6l3bzz"/><path fill="url(#iZElbee)" class="hzh6l3bzz"/><path fill="url(#iBP8yDd)" class="lz9t8o9wv"/><g filter="url(#icog67b)"><path class="m8_3k6boh"/><path fill="url(#iAYuCdd)" class="q2ucym9nt"/><path fill="url(#ihastRb)" class="q2ucym9nt"/></g><g filter="url(#i8UO2He)"><path class="t63k-8bgz"/><path fill="url(#iKWyxzz)" class="w4enui6bm"/><path fill="url(#iM1lpZc)" class="w4enui6bm"/></g><path fill="url(#iSdiF7d)" transform="scale(-1 1)rotate(-14.867 31.211 73.056)" class="ofkpelbcu"/><path fill="url(#iQRtiid)" transform="scale(-1 1)rotate(-14.867 31.211 73.056)" class="ofkpelbcu"/><path fill="url(#i4EmABd)" transform="scale(-1 1)rotate(-14.867 31.211 73.056)" class="ofkpelbcu"/><path fill="url(#iq7N0uW)" class="fb232rble"/><path fill="url(#izSQ2rb)" class="fb232rble"/><path fill="url(#iQLheqc)" class="fb232rble"/><g filter="url(#i90fdNb)"><path class="hbv6r7bbf"/><path fill="url(#iNz0R1c)" class="t236wobrv"/></g><g filter="url(#i8SZTtd)"><path class="uc6-xgbya"/></g><g filter="url(#iI6lzOd)"><path class="s-u7_-b_t"/></g><path fill="url(#il80qwb)" class="padpgu-gg"/><path fill="url(#iDZ9Bpd)" class="padpgu-gg"/><g filter="url(#iuG2P6d)"><path fill="url(#iT2Hv5I)" class="v2fgqhxbh"/></g><path fill="url(#ifpNIfc)" class="th09rbbxt"/><g filter="url(#iuwdPMc)"><path fill="url(#ijF4g9d)" class="iq0jgbwyu"/><path fill="url(#isXlrxC)" class="iq0jgbwyu"/><path fill="url(#iLtBdpe)" class="iq0jgbwyu"/><path fill="url(#iiYaeQb)" class="iq0jgbwyu"/></g><g filter="url(#ivjcune)"><path fill="url(#i3YYn7b)" class="no_nv1bue"/><path fill="url(#i4IbNZo)" class="no_nv1bue"/><path fill="url(#i2roIoy)" class="no_nv1bue"/></g><path fill="url(#irKQ3Kd)" class="stsvzsb0k"/><path fill="url(#iyczR0c)" class="stsvzsb0k"/><path clip-rule="evenodd" class="vzu72pjhq"/><path class="tnv0cvbgj"/><path fill="url(#iPnzPFc)" class="ypn56962e"/><path fill="url(#iTA8X7d)" class="fnrsegbyu"/><ellipse fill="url(#ipECBte)" transform="scale(-1 1)rotate(24.61 -28.47 -39.202)" class="m1l7k9jve"/><g filter="url(#iF5hFxb)"><path clip-rule="evenodd" class="b4a30gbbs"/></g><defs><radialGradient id="iVVQcUd" cx="0" cy="0" r="1" gradientTransform="rotate(-130.67 14.067 10.256)scale(5.34656 3.97082)" gradientUnits="userSpaceOnUse"><stop class="lt2_2ybqi"/><stop offset="1" class="bils69brp"/></radialGradient><radialGradient id="iskXoee" cx="0" cy="0" r="1" gradientTransform="matrix(.53125 3.29646 -1.78135 .28708 15.362 21.257)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="bmj_fbbea"/><stop offset="1" class="q_g8mnbhc"/></radialGradient><radialGradient id="iZElbee" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03125 -5.37969 0 18.737 18.929)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="nu9hhfe4u"/><stop offset="1" class="t_vl9fbku"/></radialGradient><radialGradient id="iBP8yDd" cx="0" cy="0" r="1" gradientTransform="matrix(.1094 3.14063 -8.2876 .28869 17.143 19.038)" gradientUnits="userSpaceOnUse"><stop offset=".558" class="gwwxm_bpq"/><stop offset=".971" class="xv9roqx4c"/></radialGradient><radialGradient id="iSdiF7d" cx="0" cy="0" r="1" gradientTransform="matrix(1.75062 .2869 -.80955 4.93989 .09 1.583)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="om366ybrp"/><stop offset="1" class="al52zb3wa"/></radialGradient><radialGradient id="iQRtiid" cx="0" cy="0" r="1" gradientTransform="rotate(117.861 .923 .84)scale(.83385 .74963)" gradientUnits="userSpaceOnUse"><stop class="numeh5b7w"/><stop offset="1" class="yqah6ebzx"/></radialGradient><radialGradient id="iq7N0uW" cx="0" cy="0" r="1" gradientTransform="matrix(3.45312 4 -4.99487 4.31198 13.909 14.554)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="b2o3a7r9l"/><stop offset="1" class="g7ee89odc"/></radialGradient><radialGradient id="izSQ2rb" cx="0" cy="0" r="1" gradientTransform="matrix(2.03122 3.14064 -3.13218 2.02576 14.346 12.679)" gradientUnits="userSpaceOnUse"><stop class="oo0a8g8xe"/><stop offset="1" class="hc1x_wbbe"/></radialGradient><radialGradient id="iQLheqc" cx="0" cy="0" r="1" gradientTransform="matrix(3.73437 .23436 -.4261 6.78981 14.423 16.303)" gradientUnits="userSpaceOnUse"><stop offset=".563" class="brpomvbii"/><stop offset="1" class="lmk5_gb2n"/></radialGradient><radialGradient id="iNz0R1c" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 2.34375 -.8049 -.04293 15.237 16.298)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="bm70d-gaq"/><stop offset="1" class="xojzxxboq"/></radialGradient><radialGradient id="iDZ9Bpd" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 1.04686 -.99542 1.2183 14.789 12.678)" gradientUnits="userSpaceOnUse"><stop class="n6csxrxuy"/><stop offset="1" class="obkbkpctx"/></radialGradient><radialGradient id="ifpNIfc" cx="0" cy="0" r="1" gradientTransform="rotate(151.587 8.858 7.223)scale(.54183 .76481)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="ss7zei8xw"/><stop offset=".684" class="d4kn2qv1f"/></radialGradient><radialGradient id="isXlrxC" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 -.04687 .05715 1.0287 16.423 8.658)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="cm3jz64eh"/><stop offset="1" class="lu7jcxbxj"/></radialGradient><radialGradient id="iLtBdpe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 1.40625 0 19.32 9.845)" gradientUnits="userSpaceOnUse"><stop offset=".163" class="hrqvsac6m"/><stop offset="1" class="fblnbo7cb"/></radialGradient><radialGradient id="iiYaeQb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39063 -.60919 0 18.491 8.705)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="o5l8xobeq"/><stop offset="1" class="plhowgx4z"/></radialGradient><radialGradient id="i3YYn7b" cx="0" cy="0" r="1" gradientTransform="matrix(3.4375 3.125 -3.54355 3.8979 14.548 5.996)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="sd2k4tbbl"/><stop offset="1" class="n3xu87-4f"/></radialGradient><radialGradient id="i4IbNZo" cx="0" cy="0" r="1" gradientTransform="matrix(-.39452 2.68273 -1.18513 -.17428 14.655 6.745)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="qvi3m-3ib"/><stop offset="1" class="sx_wpgngv"/></radialGradient><radialGradient id="i2roIoy" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 -.09374 .18396 -2.94358 19.845 6.611)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="ehlb6fbrs"/><stop offset="1" class="xv-sacbws"/></radialGradient><radialGradient id="irKQ3Kd" cx="0" cy="0" r="1" gradientTransform="rotate(-163.812 8.931 3.087)scale(.75656 .36927)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="o1rzobcjq"/><stop offset="1" class="v23x_cgsr"/></radialGradient><radialGradient id="iPnzPFc" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 0 0 -.53125 18.786 8.732)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iTA8X7d" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 0 0 -.54102 18.954 8.754)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><filter id="i8Idqnb" width="7.28" height="8.609" x="10.582" y="20.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1989"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.466667 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_1989" result="effect2_innerShadow_2_1989"/></filter><filter id="ivQbkyI" width="5.734" height="7.279" x="10.657" y="21.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_1989" stdDeviation=".25"/></filter><filter id="iGXjrHd" width="11.64" height="10.135" x="12.866" y="18.929" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.490196 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1989"/></filter><filter id="icog67b" width="4.352" height="2.364" x="19.803" y="26.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.254902 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1989"/></filter><filter id="i8UO2He" width="3.579" height="3.542" x="7.416" y="25.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.168627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1989"/></filter><filter id="i90fdNb" width="6.876" height="3.179" x="15.005" y="15.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.145098 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1989"/></filter><filter id="i8SZTtd" width="1.071" height="1.439" x="20.944" y="18.071" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.168627 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1989"/></filter><filter id="iI6lzOd" width="1.196" height="1.065" x="20.464" y="18.669" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.168627 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1989"/></filter><filter id="iuG2P6d" width="8.168" height="8.42" x="13.862" y="19.415" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_1989" stdDeviation=".375"/></filter><filter id="iuwdPMc" width="4.443" height="5.249" x="15.155" y="6.459" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.239216 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1989"/></filter><filter id="ivjcune" width="6.391" height="5.479" x="13.74" y="4.815" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.262745 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1989"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0980392 0 0 0 0 0.054902 0 0 0 0 0.0705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_1989" result="effect2_innerShadow_2_1989"/></filter><filter id="iF5hFxb" width="1.117" height=".648" x="17.877" y="7.386" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0627451 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_1989"/></filter><linearGradient id="iNk50gc" x1="14.8" x2="14.8" y1="18.835" y2="19.366" gradientUnits="userSpaceOnUse"><stop class="fy99v1bac"/><stop offset="1" class="l0bg_dlbj"/></linearGradient><linearGradient id="iAYuCdd" x1="19.675" x2="20.659" y1="28.101" y2="28.101" gradientUnits="userSpaceOnUse"><stop class="jje8gccwz"/><stop offset="1" class="ifze1vbqw"/></linearGradient><linearGradient id="ihastRb" x1="21.112" x2="21.112" y1="28.964" y2="28.593" gradientUnits="userSpaceOnUse"><stop class="k1dl65w8i"/><stop offset="1" class="pqpq_lljy"/></linearGradient><linearGradient id="iKWyxzz" x1="10.649" x2="9.964" y1="26.054" y2="26.718" gradientUnits="userSpaceOnUse"><stop class="olt5ljabw"/><stop offset="1" class="xgk77dt3o"/></linearGradient><linearGradient id="iM1lpZc" x1="8.503" x2="8.718" y1="27.257" y2="27.429" gradientUnits="userSpaceOnUse"><stop offset=".098" class="fwheo7gdw"/><stop offset="1" class="oy9f4cbur"/></linearGradient><linearGradient id="i4EmABd" x1="-.003" x2=".233" y1="1.875" y2="1.869" gradientUnits="userSpaceOnUse"><stop class="ndh-ggbqf"/><stop offset="1" class="naoj9jbij"/></linearGradient><linearGradient id="il80qwb" x1="14.82" x2="17.311" y1="15.304" y2="15.382" gradientUnits="userSpaceOnUse"><stop class="ofo46gsuq"/><stop offset="1" class="lq0qk0brb"/></linearGradient><linearGradient id="iT2Hv5I" x1="21.28" x2="14.799" y1="25.851" y2="19.913" gradientUnits="userSpaceOnUse"><stop offset=".552" class="cl3ijcbld"/><stop offset="1" class="v224y-b0w"/></linearGradient><linearGradient id="ijF4g9d" x1="16.735" x2="19.598" y1="9.4" y2="9.572" gradientUnits="userSpaceOnUse"><stop class="zpg97tbto"/><stop offset="1" class="l-3q2ti-u"/></linearGradient><linearGradient id="iyczR0c" x1="16.683" x2="16.569" y1="8.607" y2="8.623" gradientUnits="userSpaceOnUse"><stop class="uysgu56cq"/><stop offset="1" class="ve-3ak5rg"/></linearGradient><linearGradient id="ipECBte" x1="-.007" x2=".179" y1=".05" y2=".11" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-kneeling-facing-right-dark" /></template>
<style>
.a5y-b-r0a {
  fill: var(--svg-color--968ba1, #968BA1);
  d: path("M22.35 22.132c-.137.575-.807 3.427-1.125 4.781c.573.232 1.39.668 2.067 1.008c.324.163.533.495.443.847a.26.26 0 0 1-.252.196h-3.43a.25.25 0 0 1-.25-.253l.076-7.169c-1.787.442-3.937.808-5.747.262c-1.2-.363-1.266-1.817-1.266-2.875l7.61.078a2.726 2.726 0 0 1 1.874 3.125");
}

.al52zb3wa {
  stop-color: var(--svg-color--5d4b4a, #5D4B4A);
}

.b2o3a7r9l {
  stop-color: var(--svg-color--45a7f8, #45A7F8);
}

.b4a30gbbs {
  fill: var(--svg-color--2c2929, #2C2929);
  fill-rule: evenodd;
  d: path("M18.294 7.897c.147-.106.363-.111.5-.111a.2.2 0 0 0 0-.4h-.01c-.128 0-.463 0-.723.186a.2.2 0 1 0 .233.325");
}

.bils69brp {
  stop-color: var(--svg-color--a49dac, #A49DAC);
  stop-opacity: 0;
}

.bjvd-sb3y {
  fill: var(--svg-color--97919f, #97919F);
  d: path("M16.855 26.64c.05-1.838-.195-4.492-.32-5.57l-3.484-.696c.554 3.344 1.328 5.508 1.687 6.266c-1.062-.266-2.578-.172-3.765-.117l-.391 1.515c1.234.125 3.34.523 3.844.648c.562.141 2.371.086 2.43-2.046");
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

.cl3ijcbld {
  stop-color: var(--svg-color--a098a8, #A098A8);
}

.cm3jz64eh {
  stop-color: var(--svg-color--34191a, #34191A);
}

.d4kn2qv1f {
  stop-color: var(--svg-color--41212e, #41212E);
}

.dqeezuryw {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M14.378 21.616c.138.941.573 3.264 1.239 5.338a.5.5 0 0 1-.152.535a.55.55 0 0 1-.538.086c-.689-.244-2.053-.526-3.737-.302");
}

.ehlb6fbrs {
  stop-color: var(--svg-color--544b49, #544B49);
}

.fb232rble {
  d: path("M17.909 14.151c.162 1.15.094 2.637-.016 3.528v1.289h-5.031c.055-2.063.578-4.728 1.367-6.047c.664-1.11 1.422-1.176 2.055-.957c.605.183 1.422.75 1.625 2.187");
}

.fblnbo7cb {
  stop-color: var(--svg-color--614c49, #614C49);
  stop-opacity: 0;
}

.fnrsegbyu {
  d: path("m18.654 8.754l-.005-.073c0-.185.08-.336.176-.336c.097 0 .176.15.176.336l-.004.073z");
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

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gwwxm_bpq {
  stop-color: var(--svg-color--857297, #857297);
  stop-opacity: 0;
}

.hbv6r7bbf {
  fill: var(--svg-color--493033, #493033);
  d: path("m16.901 17.1l.04-.78l-1.891-.126c-.047.664-.118 1.594.148 1.985c.266.39.765.858 2.2.945a42 42 0 0 0 3.269.031v-.18h.672l.34-.214c.039-.192-.39-.568-.79-.711c-1.253-.45-2.96-.82-3.988-.95");
}

.hc1x_wbbe {
  stop-color: var(--svg-color--4aa9ee, #4AA9EE);
  stop-opacity: 0;
}

.hrqvsac6m {
  stop-color: var(--svg-color--614c49, #614C49);
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

.no_nv1bue {
  d: path("M18.93 7.207c.657 0 .97-.371 1-.836c0-.657-.5-.796-.694-.817c-.22-.023-.305-.047-.61-.261a.9.9 0 0 0-.91-.098c-.148.07-.477.105-.71.035c-.392-.117-.696-.113-.997.117c-.209.16-.363.16-.613.16c-.344 0-.636.154-.856.32c-.657.498-.582 2.208-.257 3.169c.31.92.777 1.027 1.167.992c.47-.042.59-.399.66-.695c.057-.238.201-.99.266-1.238c.136-.062.431-.086.531-.473c.1-.388.493-.432.758-.407c.162.016.61.032 1.266.032");
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

.o5l8xobeq {
  stop-color: var(--svg-color--472f2c, #472F2C);
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

.padpgu-gg {
  d: path("M17.31 13.636a1.261 1.261 0 0 0-2.52-.119l-.155 2.775l2.567.152z");
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

.q2ucym9nt {
  d: path("M19.816 27.542a6.3 6.3 0 0 1 1.413-.643l-.004.014c.433.175 1.005.467 1.55.746l.517.262c.324.163.533.495.443.847a.26.26 0 0 1-.252.196h-3.43a.25.25 0 0 1-.25-.253z");
}

.qvi3m-3ib {
  stop-color: var(--svg-color--464143, #464143);
}

.s-u7_-b_t {
  fill: var(--svg-color--442f2e, #442F2E);
  d: path("M21.034 18.769c-.325-.003-.516.178-.57.27c.271.143.499.375.65.566c.1.124.278.17.413.086a.266.266 0 0 0 .079-.39c-.257-.329-.48-.49-.572-.532");
}

.sd2k4tbbl {
  stop-color: var(--svg-color--251a23, #251A23);
}

.ss7zei8xw {
  stop-color: var(--svg-color--68534f, #68534F);
}

.stsvzsb0k {
  d: path("m16.8 9.414l-.2-1.44a.727.727 0 0 0 .2 1.44");
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

.tnv0cvbgj {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.064 8.754h-.989c0-.392.221-.71.494-.71s.495.318.495.71");
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.uc6-xgbya {
  fill: var(--svg-color--442f2e, #442F2E);
  d: path("m20.987 18.17l-.043.634c.233.181.452.427.603.608a.27.27 0 0 0 .345.059c.118-.073.161-.224.085-.339a3.6 3.6 0 0 0-.99-.961");
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

.v2fgqhxbh {
  d: path("m21.268 21.468l-.656 5.492l-.313.125l.43-5.73a.487.487 0 0 0-.481-.528c-.926-.006-3.848 0-4.542 0c-.813 0-1.094-.273-1.094-.648c1.193-.01 4.676-.025 5.664 0s1.039.862.992 1.289");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.ve-3ak5rg {
  stop-color: var(--svg-color--48302c, #48302C);
  stop-opacity: 0;
}

.vzu72pjhq {
  fill: var(--svg-color--280017, #280017);
  fill-rule: evenodd;
  d: path("M18.318 9.867a.125.125 0 0 0 .002.177c.238.234.582.293.692.305a.125.125 0 0 0 .025-.249c-.093-.01-.366-.062-.542-.234a.125.125 0 0 0-.177.001");
}

.w4enui6bm {
  d: path("m10.11 25.788l.885.75l-.406 1.5c-.391.198-1.35.653-2.063.89c-.547.183-.887.06-1.056-.083c-.078-.065-.066-.178 0-.257l2.285-2.769a.25.25 0 0 1 .355-.031");
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

.ypn56962e {
  d: path("M18.458 8.754V8.75c0-.32.137-.58.307-.58s.306.26.306.58v.004z");
}

.yqah6ebzx {
  stop-color: var(--svg-color--443534, #443534);
  stop-opacity: 0;
}

.zpg97tbto {
  stop-color: var(--svg-color--432b2f, #432B2F);
}

</style>
