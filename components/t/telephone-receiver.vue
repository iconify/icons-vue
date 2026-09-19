<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iira5Ld)"><path fill="url(#it8R2ce)" class="a2-er_b2s"/><path fill="url(#iEcV55c)" class="a2-er_b2s"/></g><g filter="url(#iVWMisc)"><path fill="url(#i2BEoSb)" class="rwkwojb9h"/></g><g filter="url(#iF4GjqO)"><path fill="url(#ia4SSde)" class="wked6zbgo"/><path fill="url(#iPQ8bld)" class="wked6zbgo"/><path fill="url(#itOom4c)" class="wked6zbgo"/></g><g filter="url(#iy6mlye)"><path fill="url(#iGSNGsd)" class="h4l18_dmc"/><path fill="url(#i1EDPjd)" class="h4l18_dmc"/><path fill="url(#iqWvT9b)" class="h4l18_dmc"/></g><g filter="url(#i0QEOac)"><path fill="url(#ica3OKd)" class="gdu01-bqq"/><path fill="url(#iwKXbfd)" class="gdu01-bqq"/></g><g filter="url(#i3MG3AC)"><path fill="url(#idiALyd)" class="xl6a2cbwg"/></g><defs><radialGradient id="iEcV55c" cx="0" cy="0" r="1" gradientTransform="matrix(-1 20.0625 -36.3312 -1.8109 21.98 9.681)" gradientUnits="userSpaceOnUse"><stop offset=".792" class="xengzwq9r"/><stop offset="1" class="f_t84vt-h"/></radialGradient><radialGradient id="i2BEoSb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.24097 2.57277 -4.28637 -3.73358 10.362 8.722)" gradientUnits="userSpaceOnUse"><stop offset=".2" class="ckrjdijno"/><stop offset="1" class="gv-9g2r-l"/></radialGradient><radialGradient id="ia4SSde" cx="0" cy="0" r="1" gradientTransform="matrix(-3.09194 3.41544 -5.26042 -4.76217 26.197 24.057)" gradientUnits="userSpaceOnUse"><stop offset=".293" class="v3mcsnlgr"/><stop offset="1" class="hfmbilbzt"/></radialGradient><radialGradient id="iPQ8bld" cx="0" cy="0" r="1" gradientTransform="matrix(-2.33084 5.9193 -8.14109 -3.20571 24.561 22.2)" gradientUnits="userSpaceOnUse"><stop offset=".581" class="v7qlvuc3c"/><stop offset=".945" class="kysvaf3qi"/></radialGradient><radialGradient id="itOom4c" cx="0" cy="0" r="1" gradientTransform="rotate(114.776 4.182 16.356)scale(4.25662 2.76717)" gradientUnits="userSpaceOnUse"><stop class="egsz3lfts"/><stop offset="1" class="lyn9fibjg"/></radialGradient><radialGradient id="iGSNGsd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6071 2.85353 -5.62356 -5.1379 10.19 4.981)" gradientUnits="userSpaceOnUse"><stop class="qqmgrybra"/><stop offset="1" class="bu-_f6bkz"/></radialGradient><radialGradient id="i1EDPjd" cx="0" cy="0" r="1" gradientTransform="rotate(137.661 4.038 5.32)scale(1.52198 6.58497)" gradientUnits="userSpaceOnUse"><stop offset=".144" class="vbpec9b_y"/><stop offset="1" class="yilz6ccer"/></radialGradient><radialGradient id="iqWvT9b" cx="0" cy="0" r="1" gradientTransform="matrix(-6.889 -1.06253 1.7834 -11.56278 10.824 4.806)" gradientUnits="userSpaceOnUse"><stop offset=".578" class="e5f-lbcab"/><stop offset=".962" class="j96cl_bzp"/></radialGradient><radialGradient id="ica3OKd" cx="0" cy="0" r="1" gradientTransform="rotate(132.397 8.559 16.538)scale(3.8931 7.67182)" gradientUnits="userSpaceOnUse"><stop class="ckxo6zruf"/><stop offset="1" class="f8dp25ixi"/></radialGradient><radialGradient id="iwKXbfd" cx="0" cy="0" r="1" gradientTransform="rotate(137.226 8.719 16.638)scale(1.51947 5.12615)" gradientUnits="userSpaceOnUse"><stop class="g7b923jre"/><stop offset="1" class="yilz6ccer"/></radialGradient><filter id="iira5Ld" width="27.898" height="26.637" x="2.551" y="2.681" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.317647 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19175"/></filter><filter id="iVWMisc" width="10.844" height="10.719" x="2.699" y="2.119" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19175" stdDeviation=".5"/></filter><filter id="iF4GjqO" width="11.781" height="11.457" x="18.418" y="18.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19175" stdDeviation=".5"/></filter><filter id="iy6mlye" width="10.197" height="10.197" x="3.935" y="1.358" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.321569 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19175"/></filter><filter id="i0QEOac" width="10.266" height="10.273" x="20.245" y="17.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.321569 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19175"/></filter><filter id="i3MG3AC" width="16.781" height="14.82" x="4.73" y="11.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19175" stdDeviation=".875"/></filter><linearGradient id="it8R2ce" x1="-.645" x2="22.855" y1="6.431" y2="28.556" gradientUnits="userSpaceOnUse"><stop class="itjsh6bru"/><stop offset="1" class="bjl0mufxa"/></linearGradient><linearGradient id="idiALyd" x1="7.543" x2="15.168" y1="13.049" y2="22.205" gradientUnits="userSpaceOnUse"><stop class="ydbcd-0ps"/><stop offset="1" class="hxmbmnb0x"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:telephone-receiver" /></template>
<style>
.a2-er_b2s {
  d: path("M2.55 6.642c0-1.78.884-3.406 1.587-3.96l8.734 8.562c-.375.5-1.195 1.031-2.172 1.484c-.539.328-1.086.961-.672 2.024c2.375 4.101 6.391 6.93 7.422 7.148c.743.158 1.383-.14 1.813-1.203c.476-.953 1.031-1.625 1.36-1.922l8.827 8.758c-.52.688-1.937 1.922-4.562 1.773c-5.203-.109-11.516-1.89-16.594-7.406C2.918 15.838 2.551 8.892 2.551 6.642");
}

.bjl0mufxa {
  stop-color: var(--svg-color--e821a1, #E821A1);
}

.bu-_f6bkz {
  stop-color: var(--svg-color--b73098, #B73098);
}

.ckrjdijno {
  stop-color: var(--svg-color--f52958, #F52958);
}

.ckxo6zruf {
  stop-color: var(--svg-color--bd3995, #BD3995);
}

.e5f-lbcab {
  stop-color: var(--svg-color--a35479, #A35479);
  stop-opacity: 0;
}

.egsz3lfts {
  stop-color: var(--svg-color--ce4b6e, #CE4B6E);
}

.f_t84vt-h {
  stop-color: var(--svg-color--d43eb0, #D43EB0);
}

.f8dp25ixi {
  stop-color: var(--svg-color--ac3ba4, #AC3BA4);
}

.ft5dv1b6b {
  fill: none;
}

.g7b923jre {
  stop-color: var(--svg-color--db69b6, #DB69B6);
}

.gdu01-bqq {
  d: path("M20.842 18.369c.683-.683 1.714-.648 2.474 0c.954.812 5.922 5.781 6.552 6.551s.683 1.792 0 2.475l-.48.48a.4.4 0 0 1-.566 0l-8.46-8.46a.4.4 0 0 1 0-.566z");
}

.gv-9g2r-l {
  stop-color: var(--svg-color--db2148, #DB2148);
}

.h4l18_dmc {
  d: path("M4.532 2.02a1.75 1.75 0 0 1 2.475 0l6.463 6.463a1.75 1.75 0 0 1 0 2.475l-.48.48a.4.4 0 0 1-.566 0L4.052 3.066a.4.4 0 0 1 0-.566z");
}

.hfmbilbzt {
  stop-color: var(--svg-color--fb29ab, #FB29AB);
  stop-opacity: 0;
}

.hxmbmnb0x {
  stop-color: var(--svg-color--ff5693, #FF5693);
}

.itjsh6bru {
  stop-color: var(--svg-color--e12d3e, #E12D3E);
}

.j96cl_bzp {
  stop-color: var(--svg-color--a35479, #A35479);
}

.kysvaf3qi {
  stop-color: var(--svg-color--d531aa, #D531AA);
}

.lyn9fibjg {
  stop-color: var(--svg-color--ce4b6e, #CE4B6E);
  stop-opacity: 0;
}

.qqmgrybra {
  stop-color: var(--svg-color--c8439b, #C8439B);
}

.rwkwojb9h {
  d: path("M4.477 3.186q.04-.036.08-.067l7.986 7.826a5.76 5.76 0 0 1-8.066-7.759");
}

.v3mcsnlgr {
  stop-color: var(--svg-color--fb29ab, #FB29AB);
}

.v7qlvuc3c {
  stop-color: var(--svg-color--d82ba8, #D82BA8);
  stop-opacity: 0;
}

.vbpec9b_y {
  stop-color: var(--svg-color--dd6cb6, #DD6CB6);
}

.wked6zbgo {
  d: path("M20.809 19.713c.133-.161.255-.288.354-.379L29.2 27.39l-.082.105a5.94 5.94 0 0 1-3.71 1.296c-3.307 0-5.989-2.703-5.989-6.036c0-1.254.742-2.078 1.39-3.042");
}

.xengzwq9r {
  stop-color: var(--svg-color--d43eb0, #D43EB0);
  stop-opacity: 0;
}

.xl6a2cbwg {
  d: path("M10.73 20.33c-3.188-3.004-3.864-5.854-4.25-7.188h2.094c-.02.417.738 3.082 2.656 5.094c4.032 4.227 7.157 5.737 8.532 6.227c-1.5-.125-4.313.312-9.032-4.133");
}

.ydbcd-0ps {
  stop-color: var(--svg-color--ff6670, #FF6670);
}

.yilz6ccer {
  stop-color: var(--svg-color--db69b6, #DB69B6);
  stop-opacity: 0;
}

</style>
