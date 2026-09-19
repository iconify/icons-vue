<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><path fill="url(#ia2DcJc)" class="yjni8mfvt"/><path class="bye3gcedg"/><circle fill="url(#icwRaic)" class="motv4wboz"/><circle fill="url(#ilIdxfd)" class="ihfq4mlyi"/><path class="uhfgxvb8v"/><path fill="url(#il7lKad)" clip-rule="evenodd" class="o49wddb2j"/><g filter="url(#iIi9Enk)"><path clip-rule="evenodd" class="cp6uulmxy"/></g><path fill="url(#ia2DcJc)" class="yjni8mfvt"/><path fill="url(#iB6QOxc)" class="yjni8mfvt"/><path class="j1nkv8bqx"/><g filter="url(#iblvsId)" class="nctb2ac4r"><path class="we27dotwq"/></g><path fill="url(#iuj86cb)" class="nfbq_wbqo"/><path fill="url(#ipv51no)" class="efjyo50ts"/><path fill="url(#iKvhbHd)" class="d-5qrqmxm"/><defs><radialGradient id="iuezoob" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.786 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="ia2DcJc" cx="0" cy="0" r="1" gradientTransform="matrix(-16.50002 -.50009 .46634 -15.38663 15.5 22)" gradientUnits="userSpaceOnUse"><stop offset=".066" class="cs-y_rbdt"/><stop offset=".593" class="lko84qbay"/><stop offset=".904" class="y7pdl8bna"/></radialGradient><radialGradient id="icwRaic" cx="0" cy="0" r="1" gradientTransform="rotate(135 4.3 7.513)scale(10.2026 5.28051)" gradientUnits="userSpaceOnUse"><stop class="d3wf5jb8r"/><stop offset="1" class="fqac_w1ss"/></radialGradient><radialGradient id="ilIdxfd" cx="0" cy="0" r="1" gradientTransform="rotate(133.664 8.996 10.145)scale(9.48022 5.35173)" gradientUnits="userSpaceOnUse"><stop class="d3wf5jb8r"/><stop offset="1" class="fqac_w1ss"/></radialGradient><radialGradient id="iB6QOxc" cx="0" cy="0" r="1" gradientTransform="matrix(-11 1.49997 -1.53804 -11.27922 10.5 22.5)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="h_rk_7b5o"/><stop offset=".851" class="owmtzzbos"/></radialGradient><linearGradient id="il7lKad" x1="16.5" x2="15.5" y1="7" y2="14" gradientUnits="userSpaceOnUse"><stop class="ehgdi7b0u"/><stop offset="1" class="kiu9e17zs"/></linearGradient><linearGradient id="iuj86cb" x1="12.5" x2="14" y1="24" y2="25.5" gradientUnits="userSpaceOnUse"><stop class="m6vynduni"/><stop offset="1" class="z016bf25m"/></linearGradient><linearGradient id="ipv51no" x1="11.5" x2="13" y1="28.5" y2="30" gradientUnits="userSpaceOnUse"><stop class="m6vynduni"/><stop offset="1" class="z016bf25m"/></linearGradient><linearGradient id="iKvhbHd" x1="11.5" x2="13" y1="26.5" y2="28" gradientUnits="userSpaceOnUse"><stop class="m6vynduni"/><stop offset="1" class="z016bf25m"/></linearGradient><filter id="iIi9Enk" width="14.533" height="14.688" x="2.468" y="16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_62" stdDeviation="1"/></filter><filter id="iblvsId" width="10" height="4" x="8.5" y="21.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_62" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:thinking-face" /></template>
<style>
.bye3gcedg {
  stroke: var(--svg-color--402a32, #402A32);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 19s1.124-1.303 3.25-1S19 20 19 20");
}

.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.cp6uulmxy {
  fill: var(--svg-color--e4694e, #E4694E);
  fill-rule: evenodd;
  d: path("m12.703 28.688l.055-.218A.78.78 0 0 0 12 27.5l.33-.165a1.214 1.214 0 0 0 0-2.17L12 25h1.75a1.25 1.25 0 0 0 0-2.5H8v-3.06A1.44 1.44 0 0 0 6.56 18c-.84 0-1.505.718-1.517 1.559c-.015 1.058-.132 2.381-.575 3.05c1.537 3.041 4.282 5.287 8.235 6.08");
}

.cs-y_rbdt {
  stop-color: var(--svg-color--ffea67, #FFEA67);
}

.d-5qrqmxm {
  d: path("M11 26.5h3a1 1 0 0 1 1 1z");
}

.d3wf5jb8r {
  stop-color: var(--svg-color--392108, #392108);
}

.efjyo50ts {
  d: path("M11 28.5h2a1 1 0 0 1 1 1z");
}

.ehgdi7b0u {
  stop-color: var(--svg-color--553b3e, #553B3E);
}

.fqac_w1ss {
  stop-color: var(--svg-color--c87928, #C87928);
  stop-opacity: 0;
}

.fqgjm_v0b {
  stop-color: var(--svg-color--715b32, #715B32);
}

.ft5dv1b6b {
  fill: none;
}

.g4z4xncfo {
  stop-color: var(--svg-color--ffb849, #FFB849);
}

.h_rk_7b5o {
  stop-color: var(--svg-color--ffea67, #FFEA67);
  stop-opacity: 0;
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.ihfq4mlyi {
  cx: 19.244px;
  cy: 13.943px;
  r: 4.244px;
}

.j1nkv8bqx {
  stroke: var(--svg-color--402a32, #402A32);
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.5 4.5c-.333-.333-1.3-1-2.5-1s-2.167.667-2.5 1m11 4s1-1 3-1s3 1 3 1");
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.kiu9e17zs {
  stop-color: var(--svg-color--3d2432, #3D2432);
}

.lko84qbay {
  stop-color: var(--svg-color--ffc13f, #FFC13F);
}

.m6vynduni {
  stop-color: var(--svg-color--fa9428, #FA9428);
}

.maobbcvxh {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.motv4wboz {
  cx: 9.017px;
  cy: 13.421px;
  r: 4.673px;
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.nctb2ac4r {
  opacity: var(--svg-opacity--0-8, 0.8);
}

.nfbq_wbqo {
  d: path("M11 24h3a1 1 0 0 1 1 1z");
}

.o49wddb2j {
  fill-rule: evenodd;
  d: path("M13 11.5a3 3 0 1 1-6 0a3 3 0 0 1 6 0m11 0a3 3 0 1 1-6 0a3 3 0 0 1 6 0");
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.owmtzzbos {
  stop-color: var(--svg-color--f9708e, #F9708E);
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.uhfgxvb8v {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.42 16.224a4.206 4.206 0 1 0 0-8.411a4.206 4.206 0 0 0 0 8.411m11.148.077a4.244 4.244 0 1 0 0-8.489a4.244 4.244 0 0 0 0 8.49");
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.we27dotwq {
  fill: var(--svg-color--ffa048, #FFA048);
  d: path("M10 23h7v1h-7z");
}

.y7pdl8bna {
  stop-color: var(--svg-color--df9030, #DF9030);
}

.yjni8mfvt {
  d: path("M10 21.5v-3.06A1.44 1.44 0 0 0 8.56 17c-.84 0-1.505.718-1.517 1.559C7.023 19.92 6.835 21.722 6 22c-3 1-4 5.5-1.5 7.5c2 1.6 4 1.5 5.5 1.5h2.764a1.236 1.236 0 0 0 .553-2.342L13 28.5h.72a1 1 0 0 0 .97-.758l.067-.272A.78.78 0 0 0 14 26.5l.33-.165a1.214 1.214 0 0 0 0-2.17L14 24h1.75a1.25 1.25 0 1 0 0-2.5z");
}

.z016bf25m {
  stop-color: var(--svg-color--fa9428, #FA9428);
  stop-opacity: 0;
}

.zannmacjr {
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

</style>
