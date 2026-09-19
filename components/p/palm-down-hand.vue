<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i9Quf8c)" class="pwx37zlob"/><path fill="url(#i5LzFvc)" class="pwx37zlob"/><path fill="url(#ivIwpgc)" class="pwx37zlob"/><path fill="url(#i4Iesvd)" class="ee9lt-caf"/><path fill="url(#iJeTbWP)" class="ee9lt-caf"/><path fill="url(#iYNGnVd)" class="ee9lt-caf"/><path fill="url(#iSsfW5b)" class="ee9lt-caf"/><path fill="url(#ijN4Yfb)" class="prwbu-bjd"/><path fill="url(#irA0jDc)" class="prwbu-bjd"/><g filter="url(#is2zhRb)"><path fill="url(#i0A5kKe)" class="nou0kwcyw"/></g><path fill="url(#iY6jPTS)" class="nou0kwcyw"/><g filter="url(#ionn7Cr)"><path class="ym6un1bxo"/></g><defs><radialGradient id="i9Quf8c" cx="0" cy="0" r="1" gradientTransform="matrix(1.1711 -3.78737 2.97467 .9198 15.244 17.128)" gradientUnits="userSpaceOnUse"><stop class="i2kod4bdn"/><stop offset="1" class="fby6mybxz"/></radialGradient><radialGradient id="ivIwpgc" cx="0" cy="0" r="1" gradientTransform="matrix(.75744 4.71876 -3.97837 .6386 15.078 13.906)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="w639rbvor"/><stop offset=".909" class="o6hu3fble"/></radialGradient><radialGradient id="i4Iesvd" cx="0" cy="0" r="1" gradientTransform="matrix(1 -7.625 2.64769 .34724 18.813 19.625)" gradientUnits="userSpaceOnUse"><stop class="uzlan1bga"/><stop offset="1" class="lr_j7bc-v"/></radialGradient><radialGradient id="iJeTbWP" cx="0" cy="0" r="1" gradientTransform="matrix(-.81812 6.82953 -5.8375 -.69928 19.75 13.562)" gradientUnits="userSpaceOnUse"><stop offset=".86" class="p7as7abuj"/><stop offset=".965" class="n5qe58bbu"/></radialGradient><radialGradient id="iYNGnVd" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 -7.375 7.2506 1.59758 18.313 20.688)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="kzkxd7p7j"/><stop offset="1" class="hk3d-jb6o"/></radialGradient><radialGradient id="ijN4Yfb" cx="0" cy="0" r="1" gradientTransform="rotate(-104.097 20.08 1)scale(7.18512 1.56176)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="uzlan1bga"/><stop offset="1" class="lr_j7bc-v"/></radialGradient><radialGradient id="irA0jDc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.11676 7.14566 -4.4133 -.68973 24.188 13.781)" gradientUnits="userSpaceOnUse"><stop offset=".909" class="p7as7abuj"/><stop offset=".996" class="n5qe58bbu"/></radialGradient><radialGradient id="iY6jPTS" cx="0" cy="0" r="1" gradientTransform="matrix(5.75 6.5 -2.27067 2.00867 2.813 18.438)" gradientUnits="userSpaceOnUse"><stop class="r3cktqb8y"/><stop offset="1" class="d_pjjjbuh"/></radialGradient><linearGradient id="i5LzFvc" x1="17.138" x2="16.116" y1="17.826" y2="17.726" gradientUnits="userSpaceOnUse"><stop class="no187_brd"/><stop offset="1" class="g_3_0xash"/></linearGradient><linearGradient id="iSsfW5b" x1="21.448" x2="20.128" y1="17.477" y2="17.726" gradientUnits="userSpaceOnUse"><stop class="st2iee89d"/><stop offset="1" class="c8vew55qh"/></linearGradient><linearGradient id="i0A5kKe" x1="9.481" x2="26.71" y1="22.796" y2="10.702" gradientUnits="userSpaceOnUse"><stop class="wtooasb7w"/><stop offset="1" class="hzief3blb"/></linearGradient><filter id="is2zhRb" width="29.13" height="19.251" x="2.11" y="6.242" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25" dy="-1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.623529 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6737"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.494118 0 0 0 0 0.670588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_6737" result="effect2_innerShadow_20020_6737"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.541176 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_20020_6737" result="effect3_innerShadow_20020_6737"/></filter><filter id="ionn7Cr" width="28.173" height="19.965" x="2.768" y="6.329" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6737" stdDeviation="1.25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:palm-down-hand" /></template>
<style>
.c8vew55qh {
  stop-color: var(--svg-color--c46711, #C46711);
  stop-opacity: 0;
}

.d_pjjjbuh {
  stop-color: var(--svg-color--dc8567, #DC8567);
  stop-opacity: 0;
}

.ee9lt-caf {
  d: path("M18.77 20.177a2.193 2.193 0 0 1-1.962-2.398l.52-5.185l4.357.437l-.52 5.185a2.186 2.186 0 0 1-2.395 1.961");
}

.fby6mybxz {
  stop-color: var(--svg-color--c55a14, #C55A14);
}

.ft5dv1b6b {
  fill: none;
}

.g_3_0xash {
  stop-color: var(--svg-color--bb5202, #BB5202);
  stop-opacity: 0;
}

.hk3d-jb6o {
  stop-color: var(--svg-color--d36718, #D36718);
}

.hzief3blb {
  stop-color: var(--svg-color--ffc22b, #FFC22B);
}

.i2kod4bdn {
  stop-color: var(--svg-color--dc774a, #DC774A);
}

.kzkxd7p7j {
  stop-color: var(--svg-color--d36718, #D36718);
  stop-opacity: 0;
}

.lr_j7bc-v {
  stop-color: var(--svg-color--dc7a22, #DC7A22);
}

.n5qe58bbu {
  stop-color: var(--svg-color--e87ba6, #E87BA6);
}

.no187_brd {
  stop-color: var(--svg-color--bb5202, #BB5202);
}

.nou0kwcyw {
  d: path("M12.66 17.024c0-1.701.887-2.575 2.4-3.079c.976-.21 4.53-.148 4.53-.148c1.133 0 1.78.448 2.438 1.055l3.758 3.21c.984.907 2.484 1.119 3.492.079c1.053-1.085.937-2.735-.344-3.844L23.17 9.309c-1.3-1.168-1.922-1.817-4.31-1.817H9.887c-4.829-.029-7.777 2.93-7.777 6.805c0 2.344 2.082 4.807 3.683 6.469l1.72 1.633c1.36 1.207 3.132 2.226 4.976 2.226h1.828c.59 0 1.052-.059 1.789.383c.905.542 2.33.42 3.078-.328a2.23 2.23 0 0 0 .504-2.445c-.601-1.496-2.262-2.126-3.879-2.438l-1.125-.156c-1.445-.102-2.023-1.735-2.023-2.617");
}

.o6hu3fble {
  stop-color: var(--svg-color--df76a8, #DF76A8);
}

.p7as7abuj {
  stop-color: var(--svg-color--e87ba6, #E87BA6);
  stop-opacity: 0;
}

.prwbu-bjd {
  d: path("M23.929 20.89a2.19 2.19 0 0 1-2.552-1.753l-1.127-6.012l4.479.088l.953 5.124a2.193 2.193 0 0 1-1.753 2.553");
}

.pwx37zlob {
  d: path("M14.98 18.122a2.19 2.19 0 0 1-1.752-2.552l.947-5.121l4.305.8l-.95 5.12a2.186 2.186 0 0 1-2.55 1.753");
}

.r3cktqb8y {
  stop-color: var(--svg-color--dc8567, #DC8567);
}

.st2iee89d {
  stop-color: var(--svg-color--c46711, #C46711);
}

.uzlan1bga {
  stop-color: var(--svg-color--f7a251, #F7A251);
}

.w639rbvor {
  stop-color: var(--svg-color--df76a8, #DF76A8);
  stop-opacity: 0;
}

.wtooasb7w {
  stop-color: var(--svg-color--ffb92c, #FFB92C);
}

.ym6un1bxo {
  fill: var(--svg-color--ffdf56, #FFDF56);
  d: path("m21.428 9.702l6.69 5.338a.855.855 0 0 1-1.037 1.358l-6.16-4.515a2 2 0 0 0-1.424-.372l-4.98.606A4 4 0 0 0 11 16.087v.77a4 4 0 0 0 .961 2.601l.175.205a3 3 0 0 0 1.947 1.03l1.918.215a3 3 0 0 1 1.727.8l.798.753a.772.772 0 0 1-.904 1.235l-.58-.322a3 3 0 0 0-1.457-.378h-2.397a4 4 0 0 1-2.835-1.178l-3.92-3.94A4 4 0 0 1 5.37 14.16l.277-1.204a5 5 0 0 1 4.726-3.878l8.443-.247a4 4 0 0 1 2.612.871");
}

</style>
