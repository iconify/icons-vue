<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><g clip-path="url(#iHXPdyd)"><path fill="url(#iBXqXfd)" class="j1twjse4k"/><path fill="url(#iZG2Qtd)" class="j1twjse4k"/><path fill="url(#iuOm6ib)" class="j1twjse4k"/><path fill="url(#iHMiJUc)" class="p_ukrsm3b"/><path fill="url(#isYCWgb)" class="j1twjse4k"/><path fill="url(#i1HTFGe)" class="j1twjse4k"/><path fill="url(#imZ5sId)" class="j1twjse4k"/><path fill="url(#i9heKze)" class="j1twjse4k"/></g><path fill="url(#iy246lb)" class="w69j-7fon"/><path fill="url(#iUDAYcd)" class="f9bm3ybyv"/><path fill="url(#i8dKKTc)" class="l8sndmelx"/><g filter="url(#ipV2d0c)" class="mc2zb0bvp"><path class="et7b9-9xm"/></g><circle fill="url(#inkMEpX)" transform="rotate(-15 8.203 13.948)" class="q--rjt38k"/><circle fill="url(#ieuBjfe)" transform="rotate(-15 17.475 10.713)" class="q4vyqcl8w"/><path class="ag3ocacxa"/><path fill="url(#iqv1EBc)" class="avgegmblt"/><path fill="url(#iSq5GPb)" class="nkw7dq7fi"/></g><defs><radialGradient id="iBXqXfd" cx="0" cy="0" r="1" gradientTransform="rotate(117.839 9.639 10.432)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iZG2Qtd" cx="0" cy="0" r="1" gradientTransform="rotate(116.878 9.6 10.566)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iuOm6ib" cx="0" cy="0" r="1" gradientTransform="matrix(1.1486 17.8096 -22.81071 1.47114 15.094 12.62)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iHMiJUc" cx="0" cy="0" r="1" gradientTransform="rotate(120 4.795 11.802)scale(41.0122)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="isYCWgb" cx="0" cy="0" r="1" gradientTransform="rotate(62.692 -5.797 21.83)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="i1HTFGe" cx="0" cy="0" r="1" gradientTransform="matrix(10.09144 8.68402 -6.29463 7.3148 16.612 16.354)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="imZ5sId" cx="0" cy="0" r="1" gradientTransform="rotate(-5.134 197.422 -224.298)scale(11.6726)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i9heKze" cx="0" cy="0" r="1" gradientTransform="rotate(28.971 -19.75 40.592)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="iy246lb" cx="0" cy="0" r="1" gradientTransform="rotate(-105 20.25 6.55)scale(12.2222 24.4444)" gradientUnits="userSpaceOnUse"><stop class="h13dd1l8r"/><stop offset="1" class="di9ro-btr"/></radialGradient><radialGradient id="i8dKKTc" cx="0" cy="0" r="1" gradientTransform="rotate(-114.866 19.44 8.276)scale(11.6726 20.292)" gradientUnits="userSpaceOnUse"><stop class="yui1fntgg"/><stop offset=".766" class="i3nb-2ysz"/><stop offset=".864" class="p_bns_tff"/><stop offset=".886" class="twpub9y2u"/></radialGradient><radialGradient id="inkMEpX" cx="0" cy="0" r="1" gradientTransform="rotate(146.661 4.54 6.84)scale(10.4604 5.41393)" gradientUnits="userSpaceOnUse"><stop class="d3wf5jb8r"/><stop offset="1" class="fqac_w1ss"/></radialGradient><radialGradient id="ieuBjfe" cx="0" cy="0" r="1" gradientTransform="rotate(-147.897 11.846 2.443)scale(6.80073 3.83912)" gradientUnits="userSpaceOnUse"><stop class="d3wf5jb8r"/><stop offset="1" class="fqac_w1ss"/></radialGradient><linearGradient id="iUDAYcd" x1="16" x2="16.388" y1="16" y2="17.449" gradientUnits="userSpaceOnUse"><stop class="nvahlubfz"/><stop offset="1" class="vc--wpv5i"/></linearGradient><linearGradient id="iqv1EBc" x1="16.973" x2="17.351" y1="9.528" y2="13.599" gradientUnits="userSpaceOnUse"><stop class="ehgdi7b0u"/><stop offset="1" class="kiu9e17zs"/></linearGradient><linearGradient id="iSq5GPb" x1="20.061" x2="20.438" y1="5.594" y2="9.666" gradientUnits="userSpaceOnUse"><stop class="ehgdi7b0u"/><stop offset="1" class="kiu9e17zs"/></linearGradient><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath><clipPath id="iHXPdyd"><path class="xsxpazbhz"/></clipPath><filter id="ipV2d0c" width="5.011" height="6.178" x="19.318" y="20.821" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_30" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:zany-face" /></template>
<style>
.ag3ocacxa {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.429 16.458a4.5 4.5 0 1 0-2.33-8.694a4.5 4.5 0 0 0 2.33 8.694m10.625-2.848a4.5 4.5 0 1 0-2.33-8.693a4.5 4.5 0 0 0 2.33 8.694");
}

.avgegmblt {
  d: path("M9.687 15.621a2 2 0 1 0-1.035-3.864a2 2 0 0 0 1.035 3.864");
}

.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.d3wf5jb8r {
  stop-color: var(--svg-color--392108, #392108);
}

.di9ro-btr {
  stop-color: var(--svg-color--89029c, #89029C);
}

.ehgdi7b0u {
  stop-color: var(--svg-color--553b3e, #553B3E);
}

.et7b9-9xm {
  stroke: var(--svg-color--fff, #fff);
  d: path("M20.65 25.625c.836-.742 2.51-2.226 2.12-3.675");
}

.f9bm3ybyv {
  d: path("M23.633 15.508L9.143 19.39a1.5 1.5 0 0 1-1.836-1.06l17.386-4.66a1.5 1.5 0 0 1-1.06 1.838");
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

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.i3nb-2ysz {
  stop-color: var(--svg-color--ff2b8f, #FF2B8F);
}

.j1twjse4k {
  d: path("M19.622 29.521c9.016-2.416 11.9-9.677 9.898-17.145c-2-7.468-8.128-12.315-17.145-9.899s-11.9 9.677-9.898 17.145c2 7.468 8.128 12.315 17.145 9.9");
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

.l8sndmelx {
  d: path("M19.38 28.553c4.057-1.087 4.244-6.78 4.098-7.827c-.34-2.336-4.096-1.884-6.526-1.233s-5.961 2.161-5.065 4.338c.397.981 3.436 5.809 7.493 4.722");
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.nkw7dq7fi {
  d: path("M20.502 9.617a2 2 0 1 0-1.036-3.863a2 2 0 0 0 1.036 3.863");
}

.nvahlubfz {
  stop-color: var(--svg-color--eccdff, #ECCDFF);
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.p_bns_tff {
  stop-color: var(--svg-color--bb0773, #BB0773);
}

.p_ukrsm3b {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M19.622 29.521c9.016-2.416 11.9-9.677 9.898-17.145c-2-7.468-8.128-12.315-17.145-9.899s-11.9 9.677-9.898 17.145c2 7.468 8.128 12.315 17.145 9.9");
}

.q--rjt38k {
  cx: 8.203px;
  cy: 13.948px;
  r: 5px;
}

.q4vyqcl8w {
  cx: 17.475px;
  cy: 10.713px;
  r: 4.5px;
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.twpub9y2u {
  stop-color: var(--svg-color--9f0762, #9F0762);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.w69j-7fon {
  d: path("M18.588 25.66C8.93 28.246 6.341 18.587 6.341 18.587l19.318-5.176s2.589 9.66-7.07 12.247");
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.xsxpazbhz {
  fill: var(--svg-color--fff, #fff);
  d: path("m-3.596 4.686l30.91-8.282l8.282 30.91l-30.91 8.282z");
}

.yui1fntgg {
  stop-color: var(--svg-color--ff1c4a, #FF1C4A);
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

</style>
