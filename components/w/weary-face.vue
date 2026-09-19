<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><path stroke="url(#ilRuPVd)" class="s6v3qbcwm"/><path stroke="url(#iRGcCMc)" class="af5gdnbdz"/><path fill="url(#iFfG30d)" clip-rule="evenodd" class="yy8vjmb0j"/><path fill="url(#iu0OgEb)" clip-rule="evenodd" class="hxyn_xb9b"/><path fill="url(#ieRAlzb)" class="sezhbclzr"/><path fill="url(#i8jntdd)" clip-rule="evenodd" class="tqvyrybuy"/></g><defs><radialGradient id="iuezoob" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.786 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="ieRAlzb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.5 28.4095 0 16 27)" gradientUnits="userSpaceOnUse"><stop class="h13dd1l8r"/><stop offset="1" class="di9ro-btr"/></radialGradient><radialGradient id="i8jntdd" cx="0" cy="0" r="1" gradientTransform="matrix(2.99933 -3.5 4.77631 4.09307 15 19.5)" gradientUnits="userSpaceOnUse"><stop offset=".454" class="vc--wpv5i"/><stop offset=".84" class="nvahlubfz"/><stop offset="1" class="kyk_hxbet"/></radialGradient><linearGradient id="ilRuPVd" x1="11.2" x2="10.965" y1="11.75" y2="13.161" gradientUnits="userSpaceOnUse"><stop class="d-sg2f4zs"/><stop offset="1" class="hvts7mbyo"/></linearGradient><linearGradient id="iRGcCMc" x1="20.8" x2="21.035" y1="11.75" y2="13.161" gradientUnits="userSpaceOnUse"><stop class="d-sg2f4zs"/><stop offset="1" class="hvts7mbyo"/></linearGradient><linearGradient id="iFfG30d" x1="9.667" x2="9.667" y1="9.4" y2="7.6" gradientUnits="userSpaceOnUse"><stop offset=".03" class="ii_r00eab"/><stop offset="1" class="zg8znn0_h"/></linearGradient><linearGradient id="iu0OgEb" x1="21" x2="19.5" y1="7" y2="8.5" gradientUnits="userSpaceOnUse"><stop offset=".03" class="ii_r00eab"/><stop offset="1" class="zg8znn0_h"/></linearGradient><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:weary-face" /></template>
<style>
.af5gdnbdz {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M25 12c-1.5 1.5-4.93 1.14-6-1");
}

.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.d-sg2f4zs {
  stop-color: var(--svg-color--52383e, #52383E);
}

.di9ro-btr {
  stop-color: var(--svg-color--89029c, #89029C);
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

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.hvts7mbyo {
  stop-color: var(--svg-color--432a35, #432A35);
}

.hxyn_xb9b {
  fill-rule: evenodd;
  d: path("M19.5 5a.5.5 0 0 0-.5.5c0 1.136.43 2.024 1.105 2.624c.666.591 1.538.876 2.395.876a.5.5 0 0 0 0-1c-.643 0-1.27-.215-1.73-.624c-.45-.4-.77-1.012-.77-1.876a.5.5 0 0 0-.5-.5");
}

.ii_r00eab {
  stop-color: var(--svg-color--524049, #524049);
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.kyk_hxbet {
  stop-color: var(--svg-color--d590ff, #D590FF);
}

.maobbcvxh {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.nvahlubfz {
  stop-color: var(--svg-color--eccdff, #ECCDFF);
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.s6v3qbcwm {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 12c1.5 1.5 4.93 1.14 6-1");
}

.sezhbclzr {
  d: path("M24.657 22.531C25.035 23.86 23.881 25 22.5 25h-13c-1.381 0-2.535-1.14-2.157-2.469a9.004 9.004 0 0 1 17.314 0");
}

.tqvyrybuy {
  fill-rule: evenodd;
  d: path("M21.657 18H10.343A8.96 8.96 0 0 1 16 16c2.143 0 4.112.75 5.657 2");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.yy8vjmb0j {
  fill-rule: evenodd;
  d: path("M12.5 5a.5.5 0 0 1 .5.5c0 1.136-.43 2.024-1.105 2.624C11.229 8.715 10.357 9 9.5 9a.5.5 0 0 1 0-1c.643 0 1.27-.215 1.73-.624c.45-.4.77-1.012.77-1.876a.5.5 0 0 1 .5-.5");
}

.zannmacjr {
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.zg8znn0_h {
  stop-color: var(--svg-color--4a2c42, #4A2C42);
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

</style>
