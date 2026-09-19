<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iibicNe)"><path fill="url(#iqcS5Xb)" class="glkcv9bsm"/><path fill="url(#i4JLXid)" class="glkcv9bsm"/></g><path stroke="url(#id3RPtd)" class="s5ap1_bdt"/><path stroke="url(#iBnpKVb)" class="s5ap1_bdt"/><path stroke="url(#ijYVsNe)" class="s5ap1_bdt"/><g filter="url(#inWnynd)"><path stroke="url(#iXl6Bob)" class="i_nnbmgfk"/></g><path stroke="url(#imJp6Sb)" class="t4vh_zetk"/><path fill="url(#ixQX7Oe)" class="zkyx8ib9k"/><path fill="url(#izBoQNb)" class="zkyx8ib9k"/><path fill="url(#iZR95Hb)" class="zkyx8ib9k"/><g clip-rule="evenodd" filter="url(#i4g9XPa)" class="d2kvgvbvc"><path fill="url(#iOTA8Ib)" class="c3dgddcfj"/><path fill="url(#itjsvbd)" class="c3dgddcfj"/><path fill="url(#iEuVPOc)" class="c3dgddcfj"/></g><path stroke="url(#iPeBGld)" class="jp6wjgbdu"/><path stroke="url(#itFEced)" class="jp6wjgbdu"/><path stroke="url(#iuUyTWT)" class="jp6wjgbdu"/><path class="s8jhxkzuf"/><g filter="url(#iVQN0we)"><path class="qj7lphi5t"/></g><g filter="url(#io8QvCd)"><path fill="url(#iTVReNb)" class="wdsrevymp"/></g><g filter="url(#i78NvcM)"><path class="um293uy6v"/></g><g filter="url(#iJmdAPc)"><path stroke="url(#i7qTXbd)" class="hi3mmsbck"/></g><g filter="url(#iYltbJd)"><path fill="url(#ituJUMb)" class="r4cs_pb6i"/></g><g filter="url(#iQ4zAod)"><path fill="url(#iCDFsDe)" class="h2h9ebc9w"/></g><g filter="url(#ihLoLfe)"><path class="axz23wb-p"/></g><g filter="url(#i9sdqwd)"><path stroke="url(#iCmTnto)" class="fasq16b-p"/></g><g filter="url(#ictPbwc)"><path stroke="url(#iDlQumc)" class="efewrcb0x"/></g><defs><linearGradient id="iqcS5Xb" x1="8.456" x2="10.836" y1="24.758" y2="29.254" gradientUnits="userSpaceOnUse"><stop class="h2xe-43bg"/><stop offset="1" class="hmj9khbdy"/></linearGradient><linearGradient id="iXl6Bob" x1="9.933" x2="9.933" y1="25.973" y2="20.248" gradientUnits="userSpaceOnUse"><stop class="phgyk5qit"/><stop offset="1" class="p4dgsh1zg"/></linearGradient><linearGradient id="ixQX7Oe" x1="10.374" x2="16.436" y1="13.162" y2="13.162" gradientUnits="userSpaceOnUse"><stop class="ld--wnxmq"/><stop offset="1" class="eanfhxbao"/></linearGradient><linearGradient id="izBoQNb" x1="21.34" x2="19.878" y1="12.979" y2="12.979" gradientUnits="userSpaceOnUse"><stop class="tvdks9bhs"/><stop offset="1" class="g92n19bdu"/></linearGradient><linearGradient id="iZR95Hb" x1="19.878" x2="19.878" y1="10.512" y2="12.309" gradientUnits="userSpaceOnUse"><stop class="tvdks9bhs"/><stop offset="1" class="g92n19bdu"/></linearGradient><linearGradient id="iOTA8Ib" x1="10.84" x2="22.841" y1="11.496" y2="11.496" gradientUnits="userSpaceOnUse"><stop class="g5sxrzb3a"/><stop offset="1" class="r0f7vssdz"/></linearGradient><linearGradient id="itFEced" x1="28.822" x2="27.844" y1="3" y2="3" gradientUnits="userSpaceOnUse"><stop class="wah7xr7ll"/><stop offset="1" class="ba5893b0w"/></linearGradient><linearGradient id="iuUyTWT" x1="22.829" x2="24.035" y1="3" y2="3" gradientUnits="userSpaceOnUse"><stop class="nrxfj9bwc"/><stop offset="1" class="yh3m8cc_c"/></linearGradient><linearGradient id="iTVReNb" x1="27.527" x2="16.629" y1="16.505" y2="25.022" gradientUnits="userSpaceOnUse"><stop class="vx9w5x4-i"/><stop offset="1" class="ry3ru4t5g"/></linearGradient><linearGradient id="i7qTXbd" x1="17.924" x2="27.026" y1="25.943" y2="16.786" gradientUnits="userSpaceOnUse"><stop class="ijyh0lbjd"/><stop offset="1" class="cmsheebhx"/></linearGradient><linearGradient id="iCDFsDe" x1="17.375" x2="27.49" y1="21.5" y2="21.5" gradientUnits="userSpaceOnUse"><stop class="x9-imyafb"/><stop offset="1" class="w_ldmgbks"/></linearGradient><linearGradient id="iCmTnto" x1="9.849" x2="16.75" y1="19.848" y2="13.625" gradientUnits="userSpaceOnUse"><stop class="c35teacna"/><stop offset="1" class="fa-37gb0j"/></linearGradient><linearGradient id="iDlQumc" x1="12.438" x2="21.266" y1="11.844" y2="9.231" gradientUnits="userSpaceOnUse"><stop class="c35teacna"/><stop offset="1" class="fa-37gb0j"/></linearGradient><filter id="iibicNe" width="5.5" height="5.5" x="7.099" y="23.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.12549 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11224"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.12549 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_11224" result="effect2_innerShadow_18_11224"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.317647 0 0 0 0 0.305882 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_11224" result="effect3_innerShadow_18_11224"/></filter><filter id="inWnynd" width="1.2" height="6.691" x="9.333" y="20.183" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11224" stdDeviation=".2"/></filter><filter id="i4g9XPa" width="16.25" height="23.25" x="8.844" y=".75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.184314 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11224"/></filter><filter id="iVQN0we" width="4" height="4" x="2.274" y="19.783" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11224" stdDeviation=".375"/></filter><filter id="io8QvCd" width="16" height="16" x="14" y="13.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.180392 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11224"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.180392 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_11224" result="effect2_innerShadow_18_11224"/></filter><filter id="i78NvcM" width="13.479" height="13.479" x="15.261" y="14.761" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11224" stdDeviation=".5"/></filter><filter id="iJmdAPc" width="15.5" height="15.5" x="14.25" y="13.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11224" stdDeviation=".5"/></filter><filter id="iYltbJd" width="9.441" height="9.441" x="17.145" y="16.905" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.392157 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11224"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.45098 0 0 0 0 0.439216 0 0 0 0 0.458824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_11224" result="effect2_innerShadow_18_11224"/></filter><filter id="iQ4zAod" width="11.65" height="11" x="16.24" y="16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.309804 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11224"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 0.572549 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_11224" result="effect2_innerShadow_18_11224"/></filter><filter id="ihLoLfe" width="4" height="4" x="19.74" y="19.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.372549 0 0 0 0 0.309804 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_11224"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_11224" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.387833 0 0 0 0 0.332222 0 0 0 0 0.433333 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_11224"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.160784 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_11224" result="effect3_innerShadow_18_11224"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.160784 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="effect3_innerShadow_18_11224" result="effect4_innerShadow_18_11224"/></filter><filter id="i9sdqwd" width="10.2" height="6.7" x="9.249" y="13.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11224" stdDeviation=".2"/></filter><filter id="ictPbwc" width="10.665" height="6.028" x="11.31" y="8.478" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11224" stdDeviation=".2"/></filter><radialGradient id="i4JLXid" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.78786 -1.74581 0 9.095 25.022)" gradientUnits="userSpaceOnUse"><stop class="tia2d0b8p"/><stop offset="1" class="gp520ubwo"/></radialGradient><radialGradient id="id3RPtd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.55092 3.65892 0 9.85 26.3)" gradientUnits="userSpaceOnUse"><stop class="k420d8bzg"/><stop offset="1" class="x-fty5wry"/></radialGradient><radialGradient id="iBnpKVb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.78741 6.31207 0 10.113 25.035)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="v-xh43b4i"/><stop offset=".867" class="cv2638bxw"/></radialGradient><radialGradient id="ijYVsNe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.97088 1.00989 0 9.712 27.077)" gradientUnits="userSpaceOnUse"><stop class="qpqh-ybgk"/><stop offset="1" class="pztqqlbpb"/></radialGradient><radialGradient id="imJp6Sb" cx="0" cy="0" r="1" gradientTransform="rotate(-52.283 25.016 4.9)scale(6.52283 1.40147)" gradientUnits="userSpaceOnUse"><stop offset=".364" class="dlqfo_oig"/><stop offset=".88" class="ud0ps3v4y"/></radialGradient><radialGradient id="itjsvbd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.625 0 0 -3.01411 15.156 22.375)" gradientUnits="userSpaceOnUse"><stop offset=".538" class="rwkzd0bkx"/><stop offset="1" class="vjanrybxx"/></radialGradient><radialGradient id="iEuVPOc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9343 -1.78199 1.80137 -1.95534 19.436 16.726)" gradientUnits="userSpaceOnUse"><stop offset=".388" class="iktzviixl"/><stop offset="1" class="gsrj0rb7z"/></radialGradient><radialGradient id="iPeBGld" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9374 -4.47867 0 26.63 1.818)" gradientUnits="userSpaceOnUse"><stop class="d-sr-0j-w"/><stop offset="1" class="npo5r29wn"/></radialGradient><radialGradient id="ituJUMb" cx="0" cy="0" r="1" gradientTransform="matrix(6.83193 0 0 6.90129 18.989 22.041)" gradientUnits="userSpaceOnUse"><stop class="kvewqgdsm"/><stop offset="1" class="gygrjfxep"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:manual-wheelchair" /></template>
<style>
.axz23wb-p {
  fill: var(--svg-color--50425a, #50425A);
  d: path("M21.99 23a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3");
}

.ba5893b0w {
  stop-color: var(--svg-color--695e72, #695E72);
  stop-opacity: 0;
}

.c35teacna {
  stop-color: var(--svg-color--eb3b7e, #EB3B7E);
}

.c3dgddcfj {
  d: path("M24.805 2.275a1 1 0 0 0-1.923-.55l-1.689 5.913a.5.5 0 0 1-.48.362h-6.7a3.17 3.17 0 0 0-3.17 3.17v1.58a.25.25 0 0 1-.25.25h-.75a1 1 0 0 0-1 1v6a1 1 0 0 0 1.157.988h.004l.052-.006a2.1 2.1 0 0 1 .903.129c.216.09.416.233.57.478c.159.25.315.679.315 1.411a1 1 0 0 0 1 1h9a1 1 0 0 0 1-1V9.278q0-.14.039-.274zm-3.961 7.975a.25.25 0 0 0-.25-.25h-6.58c-.648 0-1.17.523-1.17 1.17v1.58c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25zM11.094 15a.25.25 0 0 0-.25.25v3.556c0 .124.09.228.212.253c.213.044.441.11.672.206a3.18 3.18 0 0 1 1.492 1.256q.346.545.505 1.272a.26.26 0 0 0 .25.207h6.869v-7z");
}

.cmsheebhx {
  stop-color: var(--svg-color--594c64, #594C64);
}

.cv2638bxw {
  stop-color: var(--svg-color--5b3c55, #5B3C55);
}

.d-sr-0j-w {
  stop-color: var(--svg-color--554960, #554960);
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.dlqfo_oig {
  stop-color: var(--svg-color--d2317d, #D2317D);
}

.eanfhxbao {
  stop-color: var(--svg-color--4a3d4b, #4A3D4B);
}

.efewrcb0x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m11.938 13.907l-.028-2.81a2 2 0 0 1 2-2.019h7.465");
}

.fa-37gb0j {
  stop-color: var(--svg-color--e7375d, #E7375D);
}

.fasq16b-p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M9.85 19.5v-5a.5.5 0 0 1 .5-.5h8.5");
}

.ft5dv1b6b {
  fill: none;
}

.g5sxrzb3a {
  stop-color: var(--svg-color--de2d69, #DE2D69);
}

.g92n19bdu {
  stop-color: var(--svg-color--2f1f2c, #2F1F2C);
  stop-opacity: 0;
}

.glkcv9bsm {
  d: path("M9.85 29a2.5 2.5 0 1 0 0-5a2.5 2.5 0 0 0 0 5");
}

.gp520ubwo {
  stop-color: var(--svg-color--221a26, #221A26);
  stop-opacity: 0;
}

.gsrj0rb7z {
  stop-color: var(--svg-color--771630, #771630);
  stop-opacity: 0;
}

.gygrjfxep {
  stop-color: var(--svg-color--aa9faf, #AA9FAF);
}

.h2h9ebc9w {
  d: path("M21.99 16c-3.03 0-5.5 2.46-5.5 5.5s2.47 5.5 5.5 5.5c3.04 0 5.5-2.46 5.5-5.5s-2.46-5.5-5.5-5.5m0 10a4.5 4.5 0 1 1 0-9a4.5 4.5 0 0 1 0 9");
}

.h2xe-43bg {
  stop-color: var(--svg-color--302636, #302636);
}

.hi3mmsbck {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M22 15a6.5 6.5 0 0 0-6.5 6.5c0 3.588 2.912 6.5 6.5 6.5c3.597 0 6.5-2.912 6.5-6.5S25.597 15 22 15Z");
}

.hmj9khbdy {
  stop-color: var(--svg-color--3c3243, #3C3243);
}

.i_nnbmgfk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M9.933 26.274v-5.49");
}

.ijyh0lbjd {
  stop-color: var(--svg-color--544b5c, #544B5C);
}

.iktzviixl {
  stop-color: var(--svg-color--771630, #771630);
}

.jp6wjgbdu {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M27.844 2h-4");
}

.k420d8bzg {
  stop-color: var(--svg-color--79707d, #79707D);
}

.kvewqgdsm {
  stop-color: var(--svg-color--8d8492, #8D8492);
}

.ld--wnxmq {
  stop-color: var(--svg-color--2e2830, #2E2830);
}

.npo5r29wn {
  stop-color: var(--svg-color--3a2542, #3A2542);
}

.nrxfj9bwc {
  stop-color: var(--svg-color--3b3340, #3B3340);
}

.p4dgsh1zg {
  stop-color: var(--svg-color--8e8491, #8E8491);
  stop-opacity: 0;
}

.phgyk5qit {
  stop-color: var(--svg-color--8e8491, #8E8491);
}

.pztqqlbpb {
  stop-color: var(--svg-color--604f6a, #604F6A);
  stop-opacity: 0;
}

.qj7lphi5t {
  stroke: var(--svg-color--4b484d, #4B484D);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m5.274 22.783l-2-2");
}

.qpqh-ybgk {
  stop-color: var(--svg-color--604f6a, #604F6A);
}

.r0f7vssdz {
  stop-color: var(--svg-color--f33c56, #F33C56);
}

.r4cs_pb6i {
  d: path("M21.99 26.096a4.595 4.595 0 1 0 0-9.19a4.595 4.595 0 0 0 0 9.19");
}

.rwkzd0bkx {
  stop-color: var(--svg-color--8f1d3c, #8F1D3C);
}

.ry3ru4t5g {
  stop-color: var(--svg-color--302837, #302837);
}

.s5ap1_bdt {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.85 20v6");
}

.s8jhxkzuf {
  stroke: var(--svg-color--2a292a, #2A292A);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--2-001px, 2.001px);
  d: path("m5 23l-2-2");
}

.t4vh_zetk {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.594 16.532L5 23");
}

.tia2d0b8p {
  stop-color: var(--svg-color--221a26, #221A26);
}

.tvdks9bhs {
  stop-color: var(--svg-color--2f1f2c, #2F1F2C);
}

.ud0ps3v4y {
  stop-color: var(--svg-color--9b154a, #9B154A);
}

.um293uy6v {
  fill: var(--svg-color--262129, #262129);
  d: path("M22 15.761a5.74 5.74 0 0 0-5.74 5.74A5.74 5.74 0 0 0 22 27.238a5.736 5.736 0 0 0 5.74-5.739A5.737 5.737 0 0 0 22 15.761");
}

.v-xh43b4i {
  stop-color: var(--svg-color--5b3c55, #5B3C55);
  stop-opacity: 0;
}

.vjanrybxx {
  stop-color: var(--svg-color--8f1d3c, #8F1D3C);
  stop-opacity: 0;
}

.vx9w5x4-i {
  stop-color: var(--svg-color--493656, #493656);
}

.w_ldmgbks {
  stop-color: var(--svg-color--918895, #918895);
}

.wah7xr7ll {
  stop-color: var(--svg-color--695e72, #695E72);
}

.wdsrevymp {
  d: path("M22 14c-4.14 0-7.5 3.36-7.5 7.5S17.86 29 22 29c4.15 0 7.5-3.36 7.5-7.5S26.15 14 22 14");
}

.x-fty5wry {
  stop-color: var(--svg-color--5f4859, #5F4859);
}

.x9-imyafb {
  stop-color: var(--svg-color--958d9a, #958D9A);
}

.yh3m8cc_c {
  stop-color: var(--svg-color--3b3340, #3B3340);
  stop-opacity: 0;
}

.zkyx8ib9k {
  d: path("M21.96 14.21H9v-1.05c0-1.19.97-2.16 2.16-2.16h10.8z");
}

</style>
