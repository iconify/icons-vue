<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><path clip-rule="evenodd" class="wox45-nwj"/><path fill="url(#iZlcy7c)" class="g1f5a3r0a"/><path fill="url(#iLeprQl)" class="dnvv5pbmb"/><path fill="url(#idE64jq)" class="hrp5c7yzv"/><path fill="url(#i0QjMTc)" class="v0qvj71nt"/><path stroke="url(#iGBxfrd)" class="qusfd8jro"/><path stroke="url(#iSp7Mcb)" class="qusfd8jro"/><path stroke="url(#iFTF3bd)" class="abcmcwchv"/><path stroke="url(#i63oYjd)" class="rzpcoz84k"/></g><defs><radialGradient id="iuezoob" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.786 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="iSp7Mcb" cx="0" cy="0" r="1" gradientTransform="matrix(2.5 3.5 -3.5 2.5 7 7)" gradientUnits="userSpaceOnUse"><stop offset=".542" class="j2t0-ibcg"/><stop offset=".807" class="scgg1abqz"/><stop offset=".955" class="zg8znn0_h"/></radialGradient><radialGradient id="iFTF3bd" cx="0" cy="0" r="1" gradientTransform="rotate(125.538 10.699 9.933)scale(4.30116)" gradientUnits="userSpaceOnUse"><stop class="hyejxlbwh"/><stop offset=".887" class="dnexucbbp"/><stop offset="1" class="zg8znn0_h"/></radialGradient><linearGradient id="iZlcy7c" x1="12.372" x2="10.88" y1="12" y2="19.76" gradientUnits="userSpaceOnUse"><stop class="ehgdi7b0u"/><stop offset="1" class="kiu9e17zs"/></linearGradient><linearGradient id="iLeprQl" x1="22.372" x2="20.88" y1="12" y2="19.76" gradientUnits="userSpaceOnUse"><stop class="ehgdi7b0u"/><stop offset="1" class="kiu9e17zs"/></linearGradient><linearGradient id="idE64jq" x1="11.783" x2="12.629" y1="12.948" y2="15.598" gradientUnits="userSpaceOnUse"><stop offset=".006" class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="i0QjMTc" x1="21.778" x2="22.624" y1="12.948" y2="15.598" gradientUnits="userSpaceOnUse"><stop offset=".006" class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iGBxfrd" x1="9.5" x2="9.5" y1="7" y2="8.5" gradientUnits="userSpaceOnUse"><stop offset=".03" class="ii_r00eab"/><stop offset="1" class="zg8znn0_h"/></linearGradient><linearGradient id="i63oYjd" x1="16" x2="16" y1="22" y2="24" gradientUnits="userSpaceOnUse"><stop class="da3dd5b9t"/><stop offset="1" class="nflylhbjg"/></linearGradient><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pleading-face" /></template>
<style>
.abcmcwchv {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M21.5 7.5s.5 3 4 3");
}

.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.da3dd5b9t {
  stop-color: var(--svg-color--4f3c43, #4F3C43);
}

.dnexucbbp {
  stop-color: var(--svg-color--462b45, #462B45);
}

.dnvv5pbmb {
  d: path("M17 15.88c0-2.14 1.74-3.88 3.88-3.88s3.88 1.74 3.88 3.88s-1.74 3.88-3.88 3.88S17 18.02 17 15.88");
}

.ehgdi7b0u {
  stop-color: var(--svg-color--553b3e, #553B3E);
}

.fqgjm_v0b {
  stop-color: var(--svg-color--715b32, #715B32);
}

.ft5dv1b6b {
  fill: none;
}

.g1f5a3r0a {
  d: path("M7 15.88C7 13.74 8.74 12 10.88 12s3.88 1.74 3.88 3.88s-1.74 3.88-3.88 3.88S7 18.02 7 15.88");
}

.g4z4xncfo {
  stop-color: var(--svg-color--ffb849, #FFB849);
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.hrp5c7yzv {
  d: path("M13.844 14.072c.368.795.064 1.628-.681 1.865s-1.639-.214-2.007-1.01c-.368-.794-.064-1.627.681-1.864s1.639.221 2.007 1.009");
}

.hyejxlbwh {
  stop-color: var(--svg-color--c2b4b5, #C2B4B5);
}

.ii_r00eab {
  stop-color: var(--svg-color--524049, #524049);
}

.j2t0-ibcg {
  stop-color: var(--svg-color--493032, #493032);
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

.maobbcvxh {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.nflylhbjg {
  stop-color: var(--svg-color--512756, #512756);
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.qusfd8jro {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M10.5 7.5s-.5 3-4 3");
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.rzpcoz84k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 25s.5-1 2-1s2 1 2 1");
}

.scgg1abqz {
  stop-color: var(--svg-color--5e445a, #5E445A);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.v0qvj71nt {
  d: path("M23.844 14.072c.368.795.064 1.628-.681 1.865s-1.639-.214-2.007-1.01c-.368-.794-.064-1.627.681-1.864c.737-.238 1.639.221 2.007 1.009");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.wox45-nwj {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M15 16.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m10.96-.02a4.48 4.48 0 1 1-8.96 0a4.48 4.48 0 0 1 8.96 0");
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
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
