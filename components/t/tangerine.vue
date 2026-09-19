<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iVHd6Pu)" class="s0d9jm7hs"/><path fill="url(#iLaKMDh)" class="s0d9jm7hs"/><path fill="url(#iHofV6b)" class="s0d9jm7hs"/><path class="w912s3niv"/><path fill="url(#ivyttuv)" class="e9twcdjee"/><g filter="url(#i7rFR6c)"><path fill="url(#ic07tbc)" class="yl10v9bdo"/></g><g filter="url(#ifHbotv)"><path class="k70r47n0n"/></g><path fill="url(#i2YL3wX)" class="s0d9jm7hs"/><path fill="url(#iEmNusb)" class="s0d9jm7hs"/><path fill="url(#i1dF3Ab)" class="s0d9jm7hs"/><path fill="url(#i9kIvud)" class="s0d9jm7hs"/><g filter="url(#i71NoDd)"><path fill="url(#iV6M5db)" class="rchflzb4c"/></g><defs><radialGradient id="iVHd6Pu" cx="0" cy="0" r="1" gradientTransform="rotate(132.184 7.869 11.266)scale(21.5928)" gradientUnits="userSpaceOnUse"><stop class="lr_grnbee"/><stop offset=".568" class="hy4wusbor"/><stop offset="1" class="bhg_p1bdo"/></radialGradient><radialGradient id="iLaKMDh" cx="0" cy="0" r="1" gradientTransform="rotate(90 .438 16.063)scale(14.6927)" gradientUnits="userSpaceOnUse"><stop offset=".777" class="og2_-db3e"/><stop offset="1" class="iedbks3oi"/></radialGradient><radialGradient id="iHofV6b" cx="0" cy="0" r="1" gradientTransform="matrix(-12.5001 14.49992 -8.8181 -7.60191 18 17)" gradientUnits="userSpaceOnUse"><stop offset=".777" class="og2_-db3e"/><stop offset="1" class="syd-9oble"/></radialGradient><radialGradient id="ivyttuv" cx="0" cy="0" r="1" gradientTransform="rotate(142.586 8.545 4.391)scale(9.20667 10.2529)" gradientUnits="userSpaceOnUse"><stop class="mz21bnbeq"/><stop offset=".425" class="mz21bnbeq"/><stop offset="1" class="t2nyzfb_d"/></radialGradient><radialGradient id="ic07tbc" cx="0" cy="0" r="1" gradientTransform="matrix(-.06626 2.43655 -3.09415 -.08414 14.161 3.667)" gradientUnits="userSpaceOnUse"><stop class="k0o3su82g"/><stop offset="1" class="pib_csu_h"/></radialGradient><radialGradient id="i2YL3wX" cx="0" cy="0" r="1" gradientTransform="rotate(139.72 8.491 10.488)scale(19.3342)" gradientUnits="userSpaceOnUse"><stop class="ccl91acgu"/><stop offset=".477" class="xhv_fykti"/><stop offset=".711" class="pwr-xcc-t"/><stop offset="1" class="c18o2mjuk"/></radialGradient><radialGradient id="iEmNusb" cx="0" cy="0" r="1" gradientTransform="rotate(50.44 -10.578 25.735)scale(14.9164)" gradientUnits="userSpaceOnUse"><stop offset=".681" class="a9qzwes9i"/><stop offset="1" class="kyfk8kxfe"/></radialGradient><radialGradient id="i1dF3Ab" cx="0" cy="0" r="1" gradientTransform="matrix(20 21 -21 20 5 6)" gradientUnits="userSpaceOnUse"><stop offset=".11" class="vxp66ri5w"/><stop offset=".545" class="u2774hbjh"/></radialGradient><radialGradient id="i9kIvud" cx="0" cy="0" r="1" gradientTransform="matrix(3.87506 15.375 -20.42332 5.14742 24.125 30.75)" gradientUnits="userSpaceOnUse"><stop offset=".091" class="ukysqfj_g"/><stop offset=".591" class="k5ebeywki"/></radialGradient><radialGradient id="iV6M5db" cx="0" cy="0" r="1" gradientTransform="matrix(2.1875 8.0625 -9.18372 2.4917 9.438 20.5)" gradientUnits="userSpaceOnUse"><stop class="gbzi1sgts"/><stop offset="1" class="lmsvzwwwr"/></radialGradient><filter id="i7rFR6c" width="5.518" height="4.666" x="11.388" y="1.757" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_27675" stdDeviation=".125"/></filter><filter id="ifHbotv" width="3.828" height="5.215" x="7.047" y="1.948" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_27675" stdDeviation=".125"/></filter><filter id="i71NoDd" width="12.685" height="15.793" x="4.277" y="13.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_27675" stdDeviation="1.25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:tangerine" /></template>
<style>
.a9qzwes9i {
  stop-color: var(--svg-color--da4b81, #DA4B81);
  stop-opacity: 0;
}

.bhg_p1bdo {
  stop-color: var(--svg-color--ff7273, #FF7273);
}

.c18o2mjuk {
  stop-color: var(--svg-color--f17c4c, #F17C4C);
}

.ccl91acgu {
  stop-color: var(--svg-color--ffec82, #FFEC82);
}

.e9twcdjee {
  d: path("M7 2h5c2.761 0 5 2.739 5 5.5h-5C9.239 7.5 7 4.761 7 2");
}

.ft5dv1b6b {
  fill: none;
}

.gbzi1sgts {
  stop-color: var(--svg-color--ffa65a, #FFA65A);
}

.hy4wusbor {
  stop-color: var(--svg-color--ff9a2a, #FF9A2A);
}

.iedbks3oi {
  stop-color: var(--svg-color--ff63c4, #FF63C4);
}

.k0o3su82g {
  stop-color: var(--svg-color--e3ff88, #E3FF88);
}

.k5ebeywki {
  stop-color: var(--svg-color--fb666b, #FB666B);
  stop-opacity: 0;
}

.k70r47n0n {
  fill: var(--svg-color--a4c957, #A4C957);
  d: path("M7.297 2.383c.187 3.664 3.159 4.62 3.328 4.523c-.68-.492-.922-.742-1.766-1.633c-.65-.686-1.2-2.112-1.414-2.843c-.143-.494-.148-.047-.148-.047");
}

.kyfk8kxfe {
  stop-color: var(--svg-color--da4b81, #DA4B81);
}

.lmsvzwwwr {
  stop-color: var(--svg-color--ffa65c, #FFA65C);
  stop-opacity: 0;
}

.lr_grnbee {
  stop-color: var(--svg-color--f8ec1d, #F8EC1D);
}

.mz21bnbeq {
  stop-color: var(--svg-color--8ec118, #8EC118);
  stop-opacity: 0;
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.pib_csu_h {
  stop-color: var(--svg-color--e1ff86, #E1FF86);
  stop-opacity: 0;
}

.pwr-xcc-t {
  stop-color: var(--svg-color--ff9738, #FF9738);
}

.rchflzb4c {
  d: path("M12.017 26.59C6.705 24.966 5.562 17.814 8 16.438c2.438-1.377 1.938 1.562 4.017 5c1.527 2.524 4.642 6.571 0 5.152");
}

.s0d9jm7hs {
  d: path("M16.5 30C22.851 30 28 24.851 28 18.5S22.851 7 16.5 7S5 12.149 5 18.5S10.149 30 16.5 30");
}

.syd-9oble {
  stop-color: var(--svg-color--c57345, #C57345);
}

.t2nyzfb_d {
  stop-color: var(--svg-color--8fc118, #8FC118);
}

.u2774hbjh {
  stop-color: var(--svg-color--fca21e, #FCA21E);
  stop-opacity: 0;
}

.ukysqfj_g {
  stop-color: var(--svg-color--d9516a, #D9516A);
}

.vxp66ri5w {
  stop-color: var(--svg-color--a2643f, #A2643F);
}

.w912s3niv {
  fill: var(--svg-color--bfe230, #BFE230);
  d: path("M7 2h5c2.761 0 5 2.739 5 5.5h-5C9.239 7.5 7 4.761 7 2");
}

.xhv_fykti {
  stop-color: var(--svg-color--ffa534, #FFA534);
}

.yl10v9bdo {
  d: path("M16.656 6.173c-1.076-3.835-4.783-4.328-4.96-4.128s-.032.566 1.602 1.161c2.043.743 3.358 2.967 3.358 2.967");
}

</style>
