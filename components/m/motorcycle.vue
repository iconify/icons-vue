<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iop0amb)"><path fill="url(#iovpaLc)" class="y42napekf"/><path fill="url(#iZHvsWc)" class="y42napekf"/><path fill="url(#ikGPzAd)" class="y42napekf"/></g><g filter="url(#iuFn3Lc)"><path fill="url(#ii0eJTU)" class="hxdbsfj0l"/><path fill="url(#igNrh0U)" class="hxdbsfj0l"/><path fill="url(#ir560ee)" class="hxdbsfj0l"/></g><g filter="url(#iLqWQId)"><circle stroke="url(#isCi5Rd)" class="jcixy78hd"/></g><g filter="url(#icHB97Z)"><circle stroke="url(#it1EIqd)" class="h_zugkqgp"/></g><path fill="url(#iOAwrBJ)" class="gn5xp1bvw"/><path fill="url(#igU9n2c)" class="gn5xp1bvw"/><path fill="url(#iYPxG5d)" class="gn5xp1bvw"/><path fill="url(#iEORnob)" class="akgy_zb0h"/><path fill="url(#ih2cYOe)" class="akgy_zb0h"/><path fill="url(#iMokxPS)" class="rcvgtvz7j"/><path fill="url(#iuiB0Wc)" class="rcvgtvz7j"/><g filter="url(#iqYvvnb)"><path fill="url(#i6tYuPb)" class="a2k84rj9d"/></g><g filter="url(#icQ6Gfc)"><path fill="url(#iaGBNbd)" class="yjdk6vdyk"/></g><g filter="url(#i1eDeer)"><path fill="url(#iIm2bvd)" class="n547cnbux"/><path fill="url(#isQ3y0A)" class="n547cnbux"/></g><g filter="url(#iNyfEKd)"><path class="xpbxx4bij"/></g><g filter="url(#i34p0le)"><path fill="url(#icJexoe)" class="sohj4hbok"/></g><path fill="url(#inLUWSb)" class="ax_-jhekw"/><path fill="url(#ixn4O7u)" class="gc-acyboy"/><path class="gy3iq7bws"/><g filter="url(#ikgsKqc)"><path fill="url(#ipdsS7b)" class="hlwd-vp7d"/><path fill="url(#iuHfave)" class="hlwd-vp7d"/></g><g filter="url(#iCOswfd)"><path fill="url(#inuX1Qf)" class="g28h55bke"/></g><g filter="url(#ihfjbhb)"><path fill="url(#ioItsYO)" class="fp-_-456t"/></g><g filter="url(#iaTz5oe)"><path stroke="url(#i8RQmjc)" class="zja9_hbth"/></g><defs><linearGradient id="iovpaLc" x1="23.696" x2="30.177" y1="24.464" y2="24.464" gradientUnits="userSpaceOnUse"><stop offset=".239" class="baem9ki2q"/><stop offset="1" class="mmwl-dsmc"/></linearGradient><linearGradient id="ii0eJTU" x1="4.546" x2="11.026" y1="24.464" y2="24.464" gradientUnits="userSpaceOnUse"><stop offset=".239" class="baem9ki2q"/><stop offset="1" class="mmwl-dsmc"/></linearGradient><linearGradient id="isCi5Rd" x1="28.09" x2="23.712" y1="22.409" y2="27.576" gradientUnits="userSpaceOnUse"><stop offset=".083" class="oeptinb4s"/><stop offset=".391" class="f0k16nibb"/><stop offset=".692" class="f0k16nibb"/><stop offset=".935" class="oeptinb4s"/></linearGradient><linearGradient id="it1EIqd" x1="8.81" x2="4.432" y1="22.409" y2="27.576" gradientUnits="userSpaceOnUse"><stop offset=".083" class="oeptinb4s"/><stop offset=".391" class="f0k16nibb"/><stop offset=".692" class="f0k16nibb"/><stop offset=".935" class="oeptinb4s"/></linearGradient><linearGradient id="igU9n2c" x1="10.301" x2="9.66" y1="23.625" y2="23" gradientUnits="userSpaceOnUse"><stop class="iqfta2d5r"/><stop offset="1" class="z3aeaacpb"/></linearGradient><linearGradient id="iEORnob" x1="21.781" x2="21.781" y1="27" y2="25.5" gradientUnits="userSpaceOnUse"><stop class="cac78ubcg"/><stop offset="1" class="makya1ndn"/></linearGradient><linearGradient id="ih2cYOe" x1="21.879" x2="21.879" y1="27.094" y2="26.281" gradientUnits="userSpaceOnUse"><stop class="pl1rr6bcy"/><stop offset="1" class="a1wtl2w_z"/></linearGradient><linearGradient id="iMokxPS" x1="23.365" x2="22.249" y1="22.182" y2="23.292" gradientUnits="userSpaceOnUse"><stop class="vy5vnkw3c"/><stop offset="1" class="y48n1kbza"/></linearGradient><linearGradient id="i6tYuPb" x1="7.157" x2="5.86" y1="24.092" y2="26.624" gradientUnits="userSpaceOnUse"><stop class="imsa1gbsm"/><stop offset="1" class="e-r8ytbwk"/></linearGradient><linearGradient id="iaGBNbd" x1="5.348" x2="29.473" y1="19.005" y2="19.005" gradientUnits="userSpaceOnUse"><stop class="mwvho_bfi"/><stop offset=".689" class="f58cypb-a"/><stop offset="1" class="ydgsts0xg"/></linearGradient><linearGradient id="iIm2bvd" x1="11.266" x2="20.25" y1="25.505" y2="25.505" gradientUnits="userSpaceOnUse"><stop class="sl_r14bws"/><stop offset="1" class="fb_qkbc3j"/></linearGradient><linearGradient id="isQ3y0A" x1="20.59" x2="17.68" y1="24.931" y2="24.931" gradientUnits="userSpaceOnUse"><stop class="eigzbkb4o"/><stop offset="1" class="amf-kvmpm"/></linearGradient><linearGradient id="inLUWSb" x1="26.526" x2="27.606" y1="17.634" y2="18.596" gradientUnits="userSpaceOnUse"><stop class="x75ejib-x"/><stop offset="1" class="gwqdl9xvr"/></linearGradient><linearGradient id="ixn4O7u" x1="16.031" x2="23.031" y1="18.005" y2="18.005" gradientUnits="userSpaceOnUse"><stop class="cko6ucm3i"/><stop offset="1" class="vuad6pb7r"/></linearGradient><linearGradient id="ioItsYO" x1="26.307" x2="25.01" y1="24.092" y2="26.624" gradientUnits="userSpaceOnUse"><stop class="imsa1gbsm"/><stop offset="1" class="e-r8ytbwk"/></linearGradient><linearGradient id="i8RQmjc" x1="16.597" x2="17.63" y1="19.177" y2="17.796" gradientUnits="userSpaceOnUse"><stop class="bsggeubfb"/><stop offset="1" class="ary49tssv"/></linearGradient><filter id="iop0amb" width="8.629" height="8.779" x="21.371" y="21.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0823529 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11077"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.0313726 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_11077" result="effect2_innerShadow_18_11077"/></filter><filter id="iuFn3Lc" width="8.629" height="8.779" x="2.221" y="21.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0823529 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11077"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.0313726 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_11077" result="effect2_innerShadow_18_11077"/></filter><filter id="iLqWQId" width="8.055" height="8.055" x="21.895" y="21.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11077" stdDeviation=".375"/></filter><filter id="icHB97Z" width="8.055" height="8.055" x="2.615" y="21.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11077" stdDeviation=".375"/></filter><filter id="iqYvvnb" width="3.288" height="3.288" x="4.891" y="23.856" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.364706 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11077"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886062 0 0 0 0 0.835486 0 0 0 0 0.945833 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_11077" result="effect2_innerShadow_18_11077"/></filter><filter id="icQ6Gfc" width="23.26" height="13.5" x="6.035" y="14.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.643137 0 0 0 0 0.117647 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11077"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.101961 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_11077" result="effect2_innerShadow_18_11077"/></filter><filter id="i1eDeer" width="9.816" height="5.25" x="11.266" y="22.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.180392 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11077"/></filter><filter id="iNyfEKd" width="2.432" height="2.489" x="8.795" y="16.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11077" stdDeviation=".125"/></filter><filter id="i34p0le" width="2.1" height="2.2" x="9.045" y="16.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.345098 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11077"/></filter><filter id="ikgsKqc" width="5.201" height="5.728" x="6.034" y="11.272" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.623529 0 0 0 0 0.768627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11077"/></filter><filter id="iCOswfd" width="3.1" height="1.1" x="8.045" y="13.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.0352941 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11077"/></filter><filter id="ihfjbhb" width="3.288" height="3.288" x="24.042" y="23.856" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.364706 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11077"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886062 0 0 0 0 0.835486 0 0 0 0 0.945833 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_11077" result="effect2_innerShadow_18_11077"/></filter><filter id="iaTz5oe" width="7.061" height="3.103" x="15.321" y="16.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11077" stdDeviation=".125"/></filter><radialGradient id="iZHvsWc" cx="0" cy="0" r="1" gradientTransform="rotate(-65.537 32.39 -7.371)scale(2.35409 2.45876)" gradientUnits="userSpaceOnUse"><stop offset=".523" class="ariye-f8h"/><stop offset="1" class="a2peghb2c"/></radialGradient><radialGradient id="ikGPzAd" cx="0" cy="0" r="1" gradientTransform="matrix(.7967 .52705 -.59223 .89524 26.862 25.847)" gradientUnits="userSpaceOnUse"><stop class="f6-f-cyvv"/><stop offset="1" class="qdmn3ybao"/></radialGradient><radialGradient id="igNrh0U" cx="0" cy="0" r="1" gradientTransform="rotate(-65.537 22.814 7.505)scale(2.35409 2.45876)" gradientUnits="userSpaceOnUse"><stop offset=".523" class="ariye-f8h"/><stop offset="1" class="a2peghb2c"/></radialGradient><radialGradient id="ir560ee" cx="0" cy="0" r="1" gradientTransform="matrix(.7967 .52705 -.59223 .89524 7.712 25.847)" gradientUnits="userSpaceOnUse"><stop class="f6-f-cyvv"/><stop offset="1" class="qdmn3ybao"/></radialGradient><radialGradient id="iOAwrBJ" cx="0" cy="0" r="1" gradientTransform="matrix(1.34309 1.22796 -3.49412 3.8217 8.087 22.66)" gradientUnits="userSpaceOnUse"><stop class="czooc5tzp"/><stop offset="1" class="mj00n5b-k"/></radialGradient><radialGradient id="iYPxG5d" cx="0" cy="0" r="1" gradientTransform="rotate(-31.884 45.215 -.049)scale(4.67394 4.46083)" gradientUnits="userSpaceOnUse"><stop offset=".768" class="z3aeaacpb"/><stop offset="1" class="iqfta2d5r"/></radialGradient><radialGradient id="iuiB0Wc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03429 -3.01937 3.59533 -2.42234 23.708 24.302)" gradientUnits="userSpaceOnUse"><stop offset=".768" class="z3aeaacpb"/><stop offset=".979" class="iqfta2d5r"/></radialGradient><radialGradient id="icJexoe" cx="0" cy="0" r="1" gradientTransform="matrix(1.23994 0 0 1.7451 9.7 17.184)" gradientUnits="userSpaceOnUse"><stop class="djwghwh1n"/><stop offset="1" class="b0nzitf1n"/></radialGradient><radialGradient id="ipdsS7b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.54883 3.73564 -2.11393 -2.00822 10.528 11.77)" gradientUnits="userSpaceOnUse"><stop class="vnw3i0fnh"/><stop offset="1" class="ongrvfd6a"/><stop offset="1" class="waeo7hbeq"/></radialGradient><radialGradient id="iuHfave" cx="0" cy="0" r="1" gradientTransform="matrix(-.64062 -.53125 1.5179 -1.8304 10.285 13.672)" gradientUnits="userSpaceOnUse"><stop class="r9q5o4bad"/><stop offset="1" class="bu8kq5bab"/></radialGradient><radialGradient id="inuX1Qf" cx="0" cy="0" r="1" gradientTransform="matrix(0 .44941 -1.95994 0 10.313 14.258)" gradientUnits="userSpaceOnUse"><stop class="lnveoblvi"/><stop offset="1" class="le4gszbmu"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:motorcycle" /></template>
<style>
.a1wtl2w_z {
  stop-color: var(--svg-color--3a1950, #3A1950);
  stop-opacity: 0;
}

.a2k84rj9d {
  d: path("M6.535 27.094a1.594 1.594 0 1 0 0-3.188a1.594 1.594 0 0 0 0 3.188");
}

.a2peghb2c {
  stop-color: var(--svg-color--2b1249, #2B1249);
  stop-opacity: 0;
}

.akgy_zb0h {
  d: path("M25.707 25h-8.672v2h8.672z");
}

.amf-kvmpm {
  stop-color: var(--svg-color--ff7a4a, #FF7A4A);
  stop-opacity: 0;
}

.ariye-f8h {
  stop-color: var(--svg-color--2d114d, #2D114D);
}

.ary49tssv {
  stop-color: var(--svg-color--ff4d61, #FF4D61);
  stop-opacity: 0;
}

.ax_-jhekw {
  d: path("M27.035 17.01c-.55 0-1 .45-1 1c0 .46.31.82.73.94c.58-.38 1.13-.8 1.62-1.3c.19-.19.33-.41.44-.65h-1.79z");
}

.b0nzitf1n {
  stop-color: var(--svg-color--ff8947, #FF8947);
}

.baem9ki2q {
  stop-color: var(--svg-color--34214f, #34214F);
}

.bsggeubfb {
  stop-color: var(--svg-color--ff4d61, #FF4D61);
}

.bu8kq5bab {
  stop-color: var(--svg-color--5488bb, #5488BB);
  stop-opacity: 0;
}

.cac78ubcg {
  stop-color: var(--svg-color--594561, #594561);
}

.cko6ucm3i {
  stop-color: var(--svg-color--513469, #513469);
}

.czooc5tzp {
  stop-color: var(--svg-color--7e7782, #7E7782);
}

.djwghwh1n {
  stop-color: var(--svg-color--ffde49, #FFDE49);
}

.e-r8ytbwk {
  stop-color: var(--svg-color--ddc5f6, #DDC5F6);
}

.eigzbkb4o {
  stop-color: var(--svg-color--ff7a4a, #FF7A4A);
}

.f0k16nibb {
  stop-color: var(--svg-color--615b6b, #615B6B);
  stop-opacity: 0;
}

.f58cypb-a {
  stop-color: var(--svg-color--f63551, #F63551);
}

.f6-f-cyvv {
  stop-color: var(--svg-color--392a49, #392A49);
}

.fb_qkbc3j {
  stop-color: var(--svg-color--ff714d, #FF714D);
}

.fp-_-456t {
  d: path("M25.686 27.094a1.594 1.594 0 1 0 0-3.188a1.594 1.594 0 0 0 0 3.188");
}

.ft5dv1b6b {
  fill: none;
}

.g28h55bke {
  d: path("M10.545 15h-2c-.28 0-.5-.22-.5-.5s.22-.5.5-.5h2c.28 0 .5.22.5.5s-.23.5-.5.5");
}

.gc-acyboy {
  d: path("M22.065 19h-5.06a.97.97 0 0 1-.97-.97V17h7v1.03c0 .54-.44.97-.97.97");
}

.gn5xp1bvw {
  d: path("M14.535 19L7.54 26l-1.004-2.002l6.5-6.498z");
}

.gwqdl9xvr {
  stop-color: var(--svg-color--d40b4f, #D40B4F);
}

.gy3iq7bws {
  fill: var(--svg-color--edb42b, #EDB42B);
  d: path("M7.815 19.89c.13-.27.22-.57.22-.89c0-1.1-.9-2-2-2c0 1.23.69 2.35 1.78 2.89");
}

.h_zugkqgp {
  cx: 6.642px;
  cy: 25.311px;
  r: 2.903px;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
}

.hlwd-vp7d {
  d: path("M6.034 17c.63 0 1.23-.28 1.64-.77l3.2-3.83c.44-.53-.09-1.31-.74-1.09c-2.39.8-4.1 3.05-4.1 5.69");
}

.hxdbsfj0l {
  d: path("M6.535 29.863a4.314 4.314 0 1 0 0-8.629a4.314 4.314 0 0 0 0 8.63");
}

.imsa1gbsm {
  stop-color: var(--svg-color--dfcaf6, #DFCAF6);
}

.iqfta2d5r {
  stop-color: var(--svg-color--350b32, #350B32);
}

.jcixy78hd {
  cx: 25.922px;
  cy: 25.311px;
  r: 2.903px;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
}

.le4gszbmu {
  stop-color: var(--svg-color--41175c, #41175C);
}

.lnveoblvi {
  stop-color: var(--svg-color--423b6b, #423B6B);
}

.makya1ndn {
  stop-color: var(--svg-color--9d909f, #9D909F);
}

.mj00n5b-k {
  stop-color: var(--svg-color--4d3859, #4D3859);
}

.mmwl-dsmc {
  stop-color: var(--svg-color--241337, #241337);
}

.mwvho_bfi {
  stop-color: var(--svg-color--de367f, #DE367F);
}

.n547cnbux {
  d: path("M11.266 23c.464.922.77 1.89.77 3c0 1.04.916 2 2 2h4c1.082 0 2-.85 2-1.89V26c0-1.09.265-2.12.796-3z");
}

.oeptinb4s {
  stop-color: var(--svg-color--615b6b, #615B6B);
}

.ongrvfd6a {
  stop-color: var(--svg-color--06a5e9, #06A5E9);
}

.pl1rr6bcy {
  stop-color: var(--svg-color--3a1950, #3A1950);
}

.qdmn3ybao {
  stop-color: var(--svg-color--392a49, #392A49);
  stop-opacity: 0;
}

.r9q5o4bad {
  stop-color: var(--svg-color--5488bb, #5488BB);
}

.rcvgtvz7j {
  d: path("m17.665 18.768l7.17 7.17l1.41-1.41l-7.17-7.17z");
}

.sl_r14bws {
  stop-color: var(--svg-color--fc444f, #FC444F);
}

.sohj4hbok {
  d: path("M11.045 19h-1c-.55 0-1-.45-1-1s.45-1 1-1h1z");
}

.vnw3i0fnh {
  stop-color: var(--svg-color--79f9ff, #79F9FF);
}

.vuad6pb7r {
  stop-color: var(--svg-color--1c1c1c, #1C1C1C);
}

.vy5vnkw3c {
  stop-color: var(--svg-color--868089, #868089);
}

.waeo7hbeq {
  stop-color: var(--svg-color--309ce5, #309CE5);
}

.x75ejib-x {
  stop-color: var(--svg-color--b6015e, #B6015E);
}

.xpbxx4bij {
  fill: var(--svg-color--b31e61, #B31E61);
  d: path("M10.978 19.17h-.967c-.531 0-.966-.447-.966-.994s.435-.995.966-.995h.966z");
}

.y42napekf {
  d: path("M25.686 29.863a4.314 4.314 0 1 0 0-8.629a4.314 4.314 0 0 0 0 8.63");
}

.y48n1kbza {
  stop-color: var(--svg-color--362040, #362040);
}

.ydgsts0xg {
  stop-color: var(--svg-color--fd4c61, #FD4C61);
}

.yjdk6vdyk {
  d: path("m6.035 17l1.5-2h6.5c1.1 0 2 .9 2 2h7v-1.03c0-.53.43-.97.97-.97h4.05c.54 0 .98.44.99.97v.11c0 .59-.23 1.15-.65 1.57c-1.25 1.25-2.8 2.11-4.45 2.73c-1.31.49-2.4 1.43-3.09 2.62h-.023c-.531.88-.797 1.91-.797 3v.11c0 1.04-.916 1.89-2 1.89h-4c-1.083 0-2-.96-2-2c0-1.11-.305-2.078-.77-3h-.01a6.66 6.66 0 0 0-2.89-2.84l-.54-.27A3.21 3.21 0 0 1 6.035 17");
}

.z3aeaacpb {
  stop-color: var(--svg-color--350b32, #350B32);
  stop-opacity: 0;
}

.zja9_hbth {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M15.696 16.978v1.353a1 1 0 0 0 1 1h5.31");
}

</style>
