<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><path fill="url(#iDyuLFv)" class="eqw3aac0j"/><path fill="url(#iATCDzc)" class="drn5dq16j"/><g filter="url(#ixEZ8sb)" class="mc2zb0bvp"><path class="mbmzl-bfe"/></g><g filter="url(#ibFpOzd)" class="mc2zb0bvp"><path class="sko63_bie"/></g><path class="pv1wk-bbk"/><g filter="url(#iLbYVPm)" class="qfgt6tb2e"><path class="y3alaib6w"/></g><path class="f4scbebmy"/><g filter="url(#iQkNSWc)" class="qfgt6tb2e"><path class="g3q6qab9r"/></g><path stroke="url(#i2rIFId)" class="midbazbgz"/></g><defs><radialGradient id="iuezoob" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.786 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="iDyuLFv" cx="0" cy="0" r="1" gradientTransform="translate(7.505 16.501)scale(6.49487)" gradientUnits="userSpaceOnUse"><stop class="bxihbocks"/><stop offset="1" class="otvlrubyy"/></radialGradient><radialGradient id="iATCDzc" cx="0" cy="0" r="1" gradientTransform="translate(24.505 16.501)scale(6.49487)" gradientUnits="userSpaceOnUse"><stop class="bxihbocks"/><stop offset="1" class="otvlrubyy"/></radialGradient><radialGradient id="i2rIFId" cx="0" cy="0" r="1" gradientTransform="matrix(0 6 -9.18387 0 16 17)" gradientUnits="userSpaceOnUse"><stop offset=".518" class="opsjn_43s"/><stop offset=".703" class="vb6ihbceu"/><stop offset="1" class="opsjn_43s"/><stop offset="1" class="opsjn_43s"/></radialGradient><filter id="ixEZ8sb" width="10" height="7" x="5" y="8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_23_436" stdDeviation=".75"/></filter><filter id="ibFpOzd" width="10.001" height="7" x="16" y="8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_23_436" stdDeviation=".75"/></filter><filter id="iLbYVPm" width="8.75" height="5.75" x="6.375" y="7.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_23_436" stdDeviation=".75"/></filter><filter id="iQkNSWc" width="8.75" height="5.75" x="17.375" y="7.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_23_436" stdDeviation=".75"/></filter><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:smiling-face-with-smiling-eyes" /></template>
<style>
.bxihbocks {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
  stop-opacity: 0.59;
}

.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.drn5dq16j {
  d: path("M24.5 23a6.5 6.5 0 1 0 0-13a6.5 6.5 0 0 0 0 13");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.eqw3aac0j {
  d: path("M7.5 23a6.5 6.5 0 1 0 0-13a6.5 6.5 0 0 0 0 13");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.f4scbebmy {
  stroke: var(--svg-color--43273b, #43273B);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 12s.5-2 2.5-2s2.5 2 2.5 2");
}

.fqgjm_v0b {
  stop-color: var(--svg-color--715b32, #715B32);
}

.ft5dv1b6b {
  fill: none;
}

.g3q6qab9r {
  stroke: var(--svg-color--fff, #fff);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M19.25 11.75s.25-2 2.5-2s2.5 2 2.5 2");
}

.g4z4xncfo {
  stop-color: var(--svg-color--ffb849, #FFB849);
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.maobbcvxh {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.mbmzl-bfe {
  stroke: var(--svg-color--9a4609, #9A4609);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 12.5s.25-2 2.5-2s2.5 2 2.5 2");
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.midbazbgz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 19c.5.667 2.5 2.5 6 2.5s5.5-1.833 6-2.5");
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.opsjn_43s {
  stop-color: var(--svg-color--4e2553, #4E2553);
}

.otvlrubyy {
  stop-color: var(--svg-color--ff6dc6, #FF6DC6);
  stop-opacity: 0;
}

.pv1wk-bbk {
  stroke: var(--svg-color--43273b, #43273B);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 12s.25-2 2.5-2s2.5 2 2.5 2");
}

.qfgt6tb2e {
  opacity: var(--svg-opacity--0-26, 0.26);
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.sko63_bie {
  stroke: var(--svg-color--9a4609, #9A4609);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.5 12.5s.5-2 2.5-2s2.5 2 2.5 2");
}

.vb6ihbceu {
  stop-color: var(--svg-color--5b4852, #5B4852);
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.y3alaib6w {
  stroke: var(--svg-color--fff, #fff);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M8.25 11.75s.25-2 2.5-2s2.5 2 2.5 2");
}

.zannmacjr {
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

</style>
