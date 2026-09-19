<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><g filter="url(#iL3ylMe)"><path fill="url(#iAIQfze)" class="z9kra2ndu"/></g><path fill="url(#iEV18cb)" class="z9kra2ndu"/><path fill="url(#i2zd5ee)" class="z9kra2ndu"/><path fill="url(#iSBMTue)" class="z9kra2ndu"/><path fill="url(#iIhT0Ic)" class="z9kra2ndu"/><path fill="url(#i0JA1Le)" class="z9kra2ndu"/><path fill="url(#iVpOFtd)" class="z9kra2ndu"/><path fill="url(#ip9EYBd)" class="j2xveya9o"/><path fill="url(#iEEXbxz)" class="j2xveya9o"/><g filter="url(#i0RQLJe)"><path fill="url(#i9XsYxd)" class="bg-1082bt"/></g><path fill="url(#iQJPB1b)" class="wc8_wcc1y"/><path fill="url(#iZj1lNb)" class="wc8_wcc1y"/><path fill="url(#iPhrzdd)" class="t-0lcxbrn"/><path fill="url(#ibmMzTc)" class="t-0lcxbrn"/><path fill="url(#iZ1egMe)" class="t-0lcxbrn"/><g filter="url(#iTE6n0Q)"><path fill="url(#iAKVRJb)" class="u9_cwfbjz"/></g><g filter="url(#irsMKcd)"><path class="gsxn80bbq"/></g></g><defs><radialGradient id="iEV18cb" cx="0" cy="0" r="1" gradientTransform="rotate(115.346 -.16 11.803)scale(4.01493 .89632)" gradientUnits="userSpaceOnUse"><stop class="ob-cu9big"/><stop offset="1" class="q3emu1bnv"/></radialGradient><radialGradient id="i2zd5ee" cx="0" cy="0" r="1" gradientTransform="matrix(-.93749 2.20313 -.43432 -.18481 10.156 18.347)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="p43xfjb4t"/><stop offset="1" class="a43e8mb4o"/></radialGradient><radialGradient id="iSBMTue" cx="0" cy="0" r="1" gradientTransform="matrix(0 21.1875 -29.6248 0 16 12.566)" gradientUnits="userSpaceOnUse"><stop offset=".558" class="m-3vgha1v"/><stop offset="1" class="vrduqibhm"/></radialGradient><radialGradient id="iIhT0Ic" cx="0" cy="0" r="1" gradientTransform="matrix(0 17.9375 -25.0806 0 16 12.566)" gradientUnits="userSpaceOnUse"><stop offset=".923" class="m-3vgha1v"/><stop offset="1" class="a2vxepddp"/></radialGradient><radialGradient id="i0JA1Le" cx="0" cy="0" r="1" gradientTransform="rotate(132.274 4.87 5.295)scale(5.57478 9.33925)" gradientUnits="userSpaceOnUse"><stop class="ob-cu9big"/><stop offset="1" class="q3emu1bnv"/></radialGradient><radialGradient id="iVpOFtd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.25 4.19093 -2.2485 -.67065 29.625 17)" gradientUnits="userSpaceOnUse"><stop class="ob-cu9big"/><stop offset="1" class="q3emu1bnv"/></radialGradient><radialGradient id="iEEXbxz" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.98438 -2.21304 0 3.85 9.05)" gradientUnits="userSpaceOnUse"><stop class="q-xgkhb6h"/><stop offset="1" class="edhiseb1c"/></radialGradient><radialGradient id="iZj1lNb" cx="0" cy="0" r="1" gradientTransform="matrix(.1875 2.1875 -.78752 .0675 3.156 9.753)" gradientUnits="userSpaceOnUse"><stop class="apcwdw7xw"/><stop offset="1" class="jmdyalb6n"/></radialGradient><radialGradient id="iPhrzdd" cx="0" cy="0" r="1" gradientTransform="matrix(-.40625 .5625 -.50149 -.3622 3.589 8.48)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="ibmMzTc" cx="0" cy="0" r="1" gradientTransform="rotate(137.643 .164 4.961)scale(.35946 .31624)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><radialGradient id="iAKVRJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.31849 5.125 -21.9754 -1.36563 23 22.378)" gradientUnits="userSpaceOnUse"><stop class="l35ty5bud"/><stop offset="1" class="kc-ihbcro"/></radialGradient><linearGradient id="iAIQfze" x1="13.375" x2="13.375" y1="21.066" y2="31.253" gradientUnits="userSpaceOnUse"><stop class="a36o9vbcd"/><stop offset="1" class="bsxxumbvo"/></linearGradient><linearGradient id="ip9EYBd" x1="3.85" x2="3.85" y1="15.691" y2="10.142" gradientUnits="userSpaceOnUse"><stop class="p475_abra"/><stop offset=".518" class="i46bc3-mx"/></linearGradient><linearGradient id="i9XsYxd" x1="3.711" x2="3.711" y1="13.199" y2="9.675" gradientUnits="userSpaceOnUse"><stop class="thfys92ux"/><stop offset="1" class="qlujx3bvx"/></linearGradient><linearGradient id="iQJPB1b" x1="4.219" x2="4.219" y1="10.142" y2="8.441" gradientUnits="userSpaceOnUse"><stop offset=".006" class="aoo6bub-i"/><stop offset="1" class="vuad6pb7r"/></linearGradient><linearGradient id="iZ1egMe" x1="3.342" x2="2.998" y1="8.249" y2="8.03" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><filter id="iL3ylMe" width="29" height="27.404" x="2" y="2.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.776471 0 0 0 0 0.823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_5021"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.803922 0 0 0 0 0.811765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_28327_5021" result="effect2_innerShadow_28327_5021"/></filter><filter id="i0RQLJe" width="2.484" height="4.627" x="1.953" y="9.642" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5021" stdDeviation=".25"/></filter><filter id="iTE6n0Q" width="14.637" height="12.318" x="15.363" y="18.034" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.719687 0 0 0 0 0.622708 0 0 0 0 0.816667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_5021"/></filter><filter id="irsMKcd" width="7.844" height="20.356" x="4.464" y="3.964" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5021" stdDeviation=".75"/></filter><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:swan" /></template>
<style>
.a2vxepddp {
  stop-color: var(--svg-color--b78cde, #B78CDE);
}

.a36o9vbcd {
  stop-color: var(--svg-color--e1dee4, #E1DEE4);
}

.a43e8mb4o {
  stop-color: var(--svg-color--b0aeb1, #B0AEB1);
  stop-opacity: 0;
}

.aoo6bub-i {
  stop-color: var(--svg-color--513468, #513468);
}

.apcwdw7xw {
  stop-color: var(--svg-color--736b80, #736B80);
}

.baf63sd8y {
  stop-color: var(--svg-color--5c5051, #5C5051);
}

.bg-1082bt {
  d: path("M2.453 10.142v.201c.032.426.263.845.437 1.233l1.048 2.193l-.517-2.49a1 1 0 0 1 .018-.391l.183-.746z");
}

.bsxxumbvo {
  stop-color: var(--svg-color--d1bbe7, #D1BBE7);
}

.c4ldw6bcc {
  stop-color: var(--svg-color--433437, #433437);
}

.e9_rv-bpy {
  stop-color: var(--svg-color--3b2838, #3B2838);
}

.edhiseb1c {
  stop-color: var(--svg-color--ffbc61, #FFBC61);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gsxn80bbq {
  fill: var(--svg-color--f7f4f9, #F7F4F9);
  d: path("m8.953 5.866l.087-.234zm1.422 4.016l.241.066zM7.97 21.132l.23.096l.01-.022l.005-.024zm.916 1.682a.25.25 0 0 0 .106-.489zM6.38 6.708c.103-.153.424-.422.89-.593a2.3 2.3 0 0 1 1.597-.014l.173-.469a2.8 2.8 0 0 0-1.942.014c-.531.195-.955.517-1.134.785zm2.487-.607c.694.257 1.11.792 1.307 1.463c.2.678.17 1.489-.04 2.252l.482.132c.228-.83.269-1.738.038-2.525c-.233-.794-.745-1.47-1.614-1.791zm1.267 3.715C9.781 11.1 8.38 17.87 7.724 21.082l.49.1c.658-3.225 2.055-9.97 2.402-11.234zm-2.396 11.22c-.096.232-.155.6-.005.958c.157.374.517.682 1.152.82l.106-.489c-.516-.112-.718-.335-.797-.524a.77.77 0 0 1 .006-.573z");
}

.hdqm2hb9u {
  stop-color: var(--svg-color--5c5051, #5C5051);
  stop-opacity: 0;
}

.i46bc3-mx {
  stop-color: var(--svg-color--ff8c00, #FF8C00);
}

.j2xveya9o {
  d: path("M2.1 10.142c.08.46.22.91.4 1.35l.95 2.23a.7.7 0 0 0 .63.42c.32 0 .6-.22.67-.53l.74-3.07l.11-.4z");
}

.jmdyalb6n {
  stop-color: var(--svg-color--736b80, #736B80);
  stop-opacity: 0;
}

.kc-ihbcro {
  stop-color: var(--svg-color--bfa8d6, #BFA8D6);
  stop-opacity: 0;
}

.l35ty5bud {
  stop-color: var(--svg-color--bfa8d6, #BFA8D6);
}

.m-3vgha1v {
  stop-color: var(--svg-color--c29ce5, #C29CE5);
  stop-opacity: 0;
}

.ob-cu9big {
  stop-color: var(--svg-color--f7f5f8, #F7F5F8);
}

.p43xfjb4t {
  stop-color: var(--svg-color--b0aeb1, #B0AEB1);
}

.p475_abra {
  stop-color: var(--svg-color--ff2c00, #FF2C00);
}

.q-xgkhb6h {
  stop-color: var(--svg-color--ffbc61, #FFBC61);
}

.q3emu1bnv {
  stop-color: var(--svg-color--f7f5f8, #F7F5F8);
  stop-opacity: 0;
}

.qlujx3bvx {
  stop-color: var(--svg-color--ffbe64, #FFBE64);
  stop-opacity: 0;
}

.t-0lcxbrn {
  d: path("M3.44 9.142a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.thfys92ux {
  stop-color: var(--svg-color--ffbe64, #FFBE64);
}

.u9_cwfbjz {
  d: path("M30 18.034c-.134 1.179-.42 2.305-.918 3.282c-1.95 3.825-7.125 4.552-9.469 4.438h-4.25v4.398h3.387c6.21 0 11.25-5.03 11.25-11.25z");
}

.vrduqibhm {
  stop-color: var(--svg-color--c29ce5, #C29CE5);
}

.vuad6pb7r {
  stop-color: var(--svg-color--1c1c1c, #1C1C1C);
}

.wc8_wcc1y {
  d: path("M2.1 10.142h3.5l.28-1H2c.01.33.04.67.1 1");
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.z9kra2ndu {
  d: path("M28.1 14.042a7.18 7.18 0 0 1-5.07 2.1h-6.89c-2 0-3.92.83-5.28 2.29l-.85.91c-.21.22-.58.03-.52-.27l2.02-9.44a4.8 4.8 0 0 0-3.05-5.5a4.82 4.82 0 0 0-3.81.24a4.83 4.83 0 0 0-2.42 2.96c-.38 1.37-.29 2.84.27 4.15l.95 2.23a.7.7 0 0 0 .63.42c.32 0 .6-.22.67-.53l.74-3.07l.6-2.12c.08-.28.28-.42.39-.48a.76.76 0 0 1 .62-.04c.36.13.58.52.5.9l-1.57 7.35l-1.23 5.68c-.92 4.29 2.35 8.33 6.74 8.33h7.21c6.21 0 11.25-5.03 11.25-11.25v-4.08c0-.99-1.2-1.48-1.9-.78");
}

</style>
