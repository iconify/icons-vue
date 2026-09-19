<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ignrFTX)"><path fill="url(#iAOUh6d)" class="rj3rt2-1c"/><path fill="url(#iSD5r9V)" class="rj3rt2-1c"/></g><g filter="url(#itxTW7d)"><path class="we8gdt59o"/><path fill="url(#ikQiSze)" class="n-_hobbuh"/></g><path fill="url(#ikGSdib)" class="n-_hobbuh"/><path fill="url(#itg2E2c)" class="n-_hobbuh"/><path fill="url(#iFTVuxb)" class="u20b2le-l"/><path fill="url(#i1y0P7d)" class="u20b2le-l"/><path fill="url(#iiLtDjx)" class="u20b2le-l"/><path fill="url(#ioEZrAd)" class="u20b2le-l"/><g filter="url(#iZqHAMV)"><path class="x5o2eitts"/><path fill="url(#i7lVGnb)" class="ytppmyblu"/><path fill="url(#idbiZjd)" class="ytppmyblu"/></g><path fill="url(#iTDiL8b)" class="ytppmyblu"/><path fill="url(#ieKHw7b)" class="ytppmyblu"/><g filter="url(#i6Gp6lD)"><path stroke="url(#idlDAxb)" class="a0hp5ukar"/></g><g filter="url(#iEJL0fe)"><path fill="url(#imZwB8c)" class="hyfre24bl"/></g><defs><radialGradient id="iAOUh6d" cx="0" cy="0" r="1" gradientTransform="matrix(8.61341 .04516 -.023 4.38885 11.424 6.65)" gradientUnits="userSpaceOnUse"><stop class="c91wfgphi"/><stop offset="1" class="c9qba746o"/></radialGradient><radialGradient id="iSD5r9V" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.55422 9.43767 0 16.2 8.636)" gradientUnits="userSpaceOnUse"><stop offset=".801" class="jfryf63fn"/><stop offset="1" class="ylv-yccmd"/></radialGradient><radialGradient id="iFTVuxb" cx="0" cy="0" r="1" gradientTransform="rotate(112.81 5.839 9.028)scale(10.4833 9.59074)" gradientUnits="userSpaceOnUse"><stop offset=".357" class="cufsq5jko"/><stop offset="1" class="rg-e9ua8h"/></radialGradient><radialGradient id="ioEZrAd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.25782 -2.97953 4.30319 -3.26086 14.077 4.888)" gradientUnits="userSpaceOnUse"><stop class="meny_svpw"/><stop offset="1" class="dk9vmjbhh"/></radialGradient><radialGradient id="i7lVGnb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.31253 11.24995 -6.93934 -2.04328 24.063 8.6)" gradientUnits="userSpaceOnUse"><stop class="d1co2qfoa"/><stop offset="1" class="tbpu6m9cz"/></radialGradient><radialGradient id="iTDiL8b" cx="0" cy="0" r="1" gradientTransform="matrix(4.4033 1.58884 -1.29089 3.57755 15.896 2.14)" gradientUnits="userSpaceOnUse"><stop offset=".15" class="xkgu4ufex"/><stop offset="1" class="i5ljqlbvp"/></radialGradient><radialGradient id="ieKHw7b" cx="0" cy="0" r="1" gradientTransform="matrix(.73438 -1.76562 1.39548 .58042 19.352 5.604)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="n37ig0bxf"/><stop offset="1" class="wla0crbsk"/></radialGradient><radialGradient id="idlDAxb" cx="0" cy="0" r="1" gradientTransform="matrix(5.5625 3.5 -4.2198 6.70645 11.516 3.557)" gradientUnits="userSpaceOnUse"><stop class="ac93etbal"/><stop offset="1" class="s6e2xbbnj"/></radialGradient><linearGradient id="ikQiSze" x1="19.812" x2="24.237" y1="26.022" y2="20.919" gradientUnits="userSpaceOnUse"><stop class="zintl0bsn"/><stop offset="1" class="xf5-6i1zd"/></linearGradient><linearGradient id="ikGSdib" x1="26.179" x2="24.643" y1="20.242" y2="21.957" gradientUnits="userSpaceOnUse"><stop offset=".068" class="s0x0ksb3h"/><stop offset="1" class="odoxxo14b"/></linearGradient><linearGradient id="itg2E2c" x1="17.825" x2="18.886" y1="18.277" y2="19.203" gradientUnits="userSpaceOnUse"><stop class="m4qsfacyn"/><stop offset="1" class="w74tqc1hu"/></linearGradient><linearGradient id="i1y0P7d" x1="16.651" x2="12.632" y1="2.856" y2="5.34" gradientUnits="userSpaceOnUse"><stop class="hns7l1blj"/><stop offset="1" class="h56ds_bxn"/></linearGradient><linearGradient id="iiLtDjx" x1="14.37" x2="12.813" y1="13.581" y2="12.339" gradientUnits="userSpaceOnUse"><stop class="rg9e3px4h"/><stop offset=".38" class="btbkjprrl"/><stop offset="1" class="zaspa1bdw"/></linearGradient><linearGradient id="idbiZjd" x1="2.378" x2="6.12" y1="30.091" y2="26.664" gradientUnits="userSpaceOnUse"><stop class="vzl144smi"/><stop offset="1" class="v1--f1bfo"/></linearGradient><linearGradient id="imZwB8c" x1="20.547" x2="17.768" y1="6.057" y2="2.526" gradientUnits="userSpaceOnUse"><stop class="a3srfacsq"/><stop offset="1" class="jb7g_acml"/></linearGradient><filter id="ignrFTX" width="10.186" height="5.719" x="11.424" y="2.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.52549 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_1305"/></filter><filter id="itxTW7d" width="16.375" height="15.649" x="14.082" y="14.505" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.521569 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_1305"/></filter><filter id="iZqHAMV" width="22.895" height="28.161" x="1.827" y="1.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.517647 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_1305"/></filter><filter id="i6Gp6lD" width="6.912" height="8.765" x="10.494" y="1.841" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_1305" stdDeviation=".25"/></filter><filter id="iEJL0fe" width="3.99" height="5.571" x="17.468" y="2.146" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_1305" stdDeviation=".15"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:reminder-ribbon" /></template>
<style>
.a0hp5ukar {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M16.656 2.636c-1-.157-4.001.051-4.882 1.327c-1.09 1.577-.52 3.341 1.897 5.892");
}

.a3srfacsq {
  stop-color: var(--svg-color--c19c31, #C19C31);
}

.ac93etbal {
  stop-color: var(--svg-color--fffc58, #FFFC58);
}

.btbkjprrl {
  stop-color: var(--svg-color--c6942e, #C6942E);
  stop-opacity: 0.796;
}

.c91wfgphi {
  stop-color: var(--svg-color--faae36, #FAAE36);
}

.c9qba746o {
  stop-color: var(--svg-color--cf7c39, #CF7C39);
}

.cufsq5jko {
  stop-color: var(--svg-color--efbc2a, #EFBC2A);
}

.d1co2qfoa {
  stop-color: var(--svg-color--ffff68, #FFFF68);
}

.dk9vmjbhh {
  stop-color: var(--svg-color--ffc42b, #FFC42B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.h56ds_bxn {
  stop-color: var(--svg-color--ffdc38, #FFDC38);
  stop-opacity: 0;
}

.hns7l1blj {
  stop-color: var(--svg-color--ffdc38, #FFDC38);
}

.hyfre24bl {
  d: path("M20.82 3.932c-.789-.972-2.276-1.377-2.813-1.486l-.239.635c.488.106 1.662.467 2.294 1.164c.984 1.084.067 2.559-.414 3.172c1.235-1.07 1.982-2.487 1.172-3.485");
}

.i5ljqlbvp {
  stop-color: var(--svg-color--fed235, #FED235);
  stop-opacity: 0;
}

.jb7g_acml {
  stop-color: var(--svg-color--c19c31, #C19C31);
  stop-opacity: 0;
}

.jfryf63fn {
  stop-color: var(--svg-color--d67b44, #D67B44);
  stop-opacity: 0;
}

.m4qsfacyn {
  stop-color: var(--svg-color--f79e36, #F79E36);
}

.meny_svpw {
  stop-color: var(--svg-color--ffc42b, #FFC42B);
}

.n-_hobbuh {
  d: path("M19.498 14.505c2.962 2.803 6.904 6.485 10.392 9.585a.5.5 0 0 1 .04.705a185 185 0 0 1-4.715 5.106a.49.49 0 0 1-.686.026c-2.985-2.697-7.069-6.812-10.447-10.307z");
}

.n37ig0bxf {
  stop-color: var(--svg-color--bd952c, #BD952C);
}

.odoxxo14b {
  stop-color: var(--svg-color--ffe151, #FFE151);
  stop-opacity: 0;
}

.rg-e9ua8h {
  stop-color: var(--svg-color--ad9347, #AD9347);
}

.rg9e3px4h {
  stop-color: var(--svg-color--c6942e, #C6942E);
}

.rj3rt2-1c {
  d: path("M19.235 8.23c-2.413-.85-5.516-.355-6.766 0a1.58 1.58 0 0 1-.953-1.266c-.125-.97-.766-4.125 4.39-4.297c4.126-.138 5.521 2.047 5.704 3.156z");
}

.s0x0ksb3h {
  stop-color: var(--svg-color--ffff5d, #FFFF5D);
}

.s6e2xbbnj {
  stop-color: var(--svg-color--fffc58, #FFFC58);
  stop-opacity: 0;
}

.tbpu6m9cz {
  stop-color: var(--svg-color--ffff68, #FFFF68);
  stop-opacity: 0;
}

.u20b2le-l {
  d: path("M18.484 13.543c-2.136-2.03-3.556-3.403-3.556-3.403c-1.2-1.175-3.319-3.395-3.038-4.895c.412-2.2 3.013-2.188 4.223-2.182h.16V1.91c-1.96 0-3.632.283-5.518 1.657c-3.075 2.24-5.202 7.058-.552 11.992c.852.904 1.89 1.995 3.034 3.186c1.738-1.725 3.546-3.518 5.246-5.201");
}

.v1--f1bfo {
  stop-color: var(--svg-color--eaa138, #EAA138);
  stop-opacity: 0;
}

.vzl144smi {
  stop-color: var(--svg-color--eaa138, #EAA138);
}

.w74tqc1hu {
  stop-color: var(--svg-color--f79e36, #F79E36);
  stop-opacity: 0;
}

.we8gdt59o {
  fill: var(--svg-color--ffc444, #FFC444);
  d: path("M19.498 14.505c2.962 2.803 6.904 6.485 10.392 9.585a.5.5 0 0 1 .04.705a185 185 0 0 1-4.715 5.106a.49.49 0 0 1-.686.026c-2.985-2.697-7.069-6.812-10.447-10.307z");
}

.wla0crbsk {
  stop-color: var(--svg-color--bd952c, #BD952C);
  stop-opacity: 0;
}

.x5o2eitts {
  fill: var(--svg-color--ffd24b, #FFD24B);
  d: path("M16.93 10.064L1.99 23.816a.5.5 0 0 0-.034.702l4.663 5.186a.5.5 0 0 0 .72.024c4.038-3.925 10.924-10.516 14.488-14.174c4.63-4.75 2.524-9.752-.551-11.992c-1.887-1.373-3.38-1.653-5.002-1.653v1.15c1.122 0 3.818.54 4.14 2.085c.302 1.445-2.283 3.744-3.482 4.92");
}

.xf5-6i1zd {
  stop-color: var(--svg-color--f69c3e, #F69C3E);
  stop-opacity: 0;
}

.xkgu4ufex {
  stop-color: var(--svg-color--fed235, #FED235);
}

.ylv-yccmd {
  stop-color: var(--svg-color--d67b44, #D67B44);
}

.ytppmyblu {
  d: path("M16.93 10.064L1.99 23.816a.5.5 0 0 0-.034.702l4.663 5.186a.5.5 0 0 0 .72.024c4.038-3.925 10.924-10.516 14.488-14.174c4.63-4.75 2.524-9.752-.551-11.992c-1.887-1.373-3.38-1.653-5.002-1.653v1.15c1.122 0 3.818.54 4.14 2.085c.302 1.445-2.283 3.744-3.482 4.92");
}

.zaspa1bdw {
  stop-color: var(--svg-color--c6942e, #C6942E);
  stop-opacity: 0;
}

.zintl0bsn {
  stop-color: var(--svg-color--f69c3e, #F69C3E);
}

</style>
