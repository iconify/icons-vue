<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iChS6ed)"><path fill="url(#isW9Q4D)" class="f7p6tkbxz"/><path fill="url(#i3wdIqc)" class="f7p6tkbxz"/><path fill="url(#iP2uE9d)" class="f7p6tkbxz"/><path fill="url(#ipRIUkc)" class="f7p6tkbxz"/><path fill="url(#iUdrArl)" class="f7p6tkbxz"/><path fill="url(#iWXcFnd)" class="f7p6tkbxz"/><path fill="url(#imOF1Td)" class="f7p6tkbxz"/></g><rect fill="url(#iPMxx8c)" class="yepf0fbcr"/><rect fill="url(#iuxFQvZ)" class="yepf0fbcr"/><rect fill="url(#iivOztd)" class="yepf0fbcr"/><g filter="url(#ibkNqAd)"><path stroke="url(#iKn6fDb)" class="k1mnaabkb"/></g><g filter="url(#ianzk2d)"><path stroke="url(#ioPf1jb)" class="qqu0k0bew"/></g><defs><radialGradient id="isW9Q4D" cx="0" cy="0" r="1" gradientTransform="rotate(130.4 8.799 12.719)scale(19.2866 13.5561)" gradientUnits="userSpaceOnUse"><stop class="gdixdsbyy"/><stop offset="1" class="xj1ts9b8a"/><stop offset="1" class="qd6xcnbdi"/></radialGradient><radialGradient id="i3wdIqc" cx="0" cy="0" r="1" gradientTransform="matrix(1.53125 2.84374 -2.45715 1.32308 8.438 13.45)" gradientUnits="userSpaceOnUse"><stop class="mpg9p3b1j"/><stop offset="1" class="w-pm_zl3e"/></radialGradient><radialGradient id="iP2uE9d" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.63672 -1.41421 .86405 6.719 16)" gradientUnits="userSpaceOnUse"><stop class="mpg9p3b1j"/><stop offset="1" class="w-pm_zl3e"/></radialGradient><radialGradient id="ipRIUkc" cx="0" cy="0" r="1" gradientTransform="rotate(109.231 5.561 11.763)scale(2.84632 1.10477)" gradientUnits="userSpaceOnUse"><stop class="mpg9p3b1j"/><stop offset="1" class="w-pm_zl3e"/></radialGradient><radialGradient id="iUdrArl" cx="0" cy="0" r="1" gradientTransform="rotate(133.299 9.003 10.92)scale(2.23279 1.21415)" gradientUnits="userSpaceOnUse"><stop class="mpg9p3b1j"/><stop offset="1" class="w-pm_zl3e"/></radialGradient><radialGradient id="iWXcFnd" cx="0" cy="0" r="1" gradientTransform="rotate(130.957 9.905 12.492)scale(2.93794 3.62296)" gradientUnits="userSpaceOnUse"><stop class="ld2h1ac-l"/><stop offset="1" class="qd4csqb-p"/></radialGradient><radialGradient id="imOF1Td" cx="0" cy="0" r="1" gradientTransform="rotate(141.981 8.26 9.512)scale(2.18169 2.11857)" gradientUnits="userSpaceOnUse"><stop class="ld2h1ac-l"/><stop offset="1" class="qd4csqb-p"/></radialGradient><linearGradient id="iPMxx8c" x1="12.174" x2="15.27" y1="9.78" y2="9.78" gradientUnits="userSpaceOnUse"><stop class="er0fxuriq"/><stop offset="1" class="oal4-gbvq"/></linearGradient><linearGradient id="iuxFQvZ" x1="18.889" x2="15.27" y1="10.783" y2="11.35" gradientUnits="userSpaceOnUse"><stop class="ggssuabwp"/><stop offset="1" class="as-a-_bsh"/></linearGradient><linearGradient id="iivOztd" x1="15.039" x2="15.039" y1="11.568" y2="15.168" gradientUnits="userSpaceOnUse"><stop class="qrevpfbeq"/><stop offset="1" class="t3kgcb7ue"/></linearGradient><linearGradient id="iKn6fDb" x1="25" x2="21" y1="13.512" y2="30.512" gradientUnits="userSpaceOnUse"><stop class="fgz6lbb_q"/><stop offset="1" class="x9idaudaq"/></linearGradient><linearGradient id="ioPf1jb" x1="16.9" x2="9.541" y1="3.316" y2="15.419" gradientUnits="userSpaceOnUse"><stop class="fgz6lbb_q"/><stop offset="1" class="x9idaudaq"/></linearGradient><filter id="iChS6ed" width="19.914" height="28.977" x="6.168" y="1.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.513726 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5352"/></filter><filter id="ibkNqAd" width="9.297" height="17.594" x="18.359" y="10.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5352" stdDeviation="1.25"/></filter><filter id="ianzk2d" width="4.75" height="15.469" x="13.313" y="1.137" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5352" stdDeviation=".875"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:middle-finger" /></template>
<style>
.as-a-_bsh {
  stop-color: var(--svg-color--ffe94a, #FFE94A);
  stop-opacity: 0;
}

.er0fxuriq {
  stop-color: var(--svg-color--e3922e, #E3922E);
}

.f7p6tkbxz {
  d: path("M12.645 4.402a2.39 2.39 0 0 1 4.78 0v7.587a2.391 2.391 0 0 1 4.242 1.146a2.39 2.39 0 0 1 4.119 2.07l-.29 2.854c-.117 1.242-.84 6.046-2.527 7.937c-1.825 2.456-4.576 3.992-7.645 3.992A8.353 8.353 0 0 1 7.03 22.62l-.784-4.457a2.28 2.28 0 0 1 2.6-2.835a2.602 2.602 0 0 1 3.798-3.11z");
}

.fgz6lbb_q {
  stop-color: var(--svg-color--ffe948, #FFE948);
}

.ft5dv1b6b {
  fill: none;
}

.gdixdsbyy {
  stop-color: var(--svg-color--ffd541, #FFD541);
}

.ggssuabwp {
  stop-color: var(--svg-color--ffe94a, #FFE94A);
}

.k1mnaabkb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M24.406 14.23c-.052 1.084-.247 3.363-.797 6.063s-1.562 4.48-2 5.031");
}

.ld2h1ac-l {
  stop-color: var(--svg-color--ffe543, #FFE543);
}

.mpg9p3b1j {
  stop-color: var(--svg-color--e39738, #E39738);
}

.oal4-gbvq {
  stop-color: var(--svg-color--e3922e, #E3922E);
  stop-opacity: 0;
}

.qd4csqb-p {
  stop-color: var(--svg-color--ffe543, #FFE543);
  stop-opacity: 0;
}

.qd6xcnbdi {
  stop-color: var(--svg-color--ffb63b, #FFB63B);
}

.qqu0k0bew {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M15.688 3.512V14.23");
}

.qrevpfbeq {
  stop-color: var(--svg-color--ffc13b, #FFC13B);
  stop-opacity: 0;
}

.t3kgcb7ue {
  stop-color: var(--svg-color--ffc13b, #FFC13B);
}

.w-pm_zl3e {
  stop-color: var(--svg-color--e39738, #E39738);
  stop-opacity: 0;
}

.x9idaudaq {
  stop-color: var(--svg-color--ffe948, #FFE948);
  stop-opacity: 0;
}

.xj1ts9b8a {
  stop-color: var(--svg-color--ffb236, #FFB236);
}

.yepf0fbcr {
  width: 4.781px;
  height: 14.813px;
  x: 12.648px;
  y: 2.012px;
  rx: 2.391px;
}

</style>
