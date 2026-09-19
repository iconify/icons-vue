<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><circle fill="url(#iGpZLse)" class="mv_citbmv"/><circle fill="url(#io7cAZd)" class="nmnni6m-k"/><path class="j-c6jjbfw"/><path fill="url(#iIDQKtO)" class="x9d3htb3i"/><path fill="url(#i93J0Xd)" class="oy41r6b5d"/><g filter="url(#ivZVjHe)"><path clip-rule="evenodd" class="m2i4udbok"/></g><g filter="url(#iAAhInc)" class="n52mgrb1s"><path clip-rule="evenodd" class="dqtsjxbjo"/></g><path fill="url(#iyfHlMP)" stroke="url(#iUE8DMb)" class="vj7ub1bam"/><path fill="url(#ibgQIib)" stroke="url(#iVZgjvc)" class="n9x7k_bur"/><path fill="url(#iHDwmdz)" stroke="url(#iJ2AIld)" class="hw0f0elow"/><path fill="url(#iyadRwc)" stroke="url(#ilAsCMb)" class="cl3bxd8pl"/><path fill="url(#i3ueaLY)" stroke="url(#i6glX0d)" class="jfnym5bcl"/><path fill="url(#ipRTeUd)" stroke="url(#izBhMhb)" class="w6q-flapl"/><path fill="url(#is0sQGd)" stroke="url(#iL9Lz5M)" class="ouyheebob"/><path fill="url(#iZCF5pG)" stroke="url(#iQ0zQae)" class="zm9v-g_4l"/><path clip-rule="evenodd" class="aerdp5ttn"/><defs><radialGradient id="iuezoob" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.786 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="iGpZLse" cx="0" cy="0" r="1" gradientTransform="rotate(135 4.557 7.225)scale(9.74236 5.04232)" gradientUnits="userSpaceOnUse"><stop class="d3wf5jb8r"/><stop offset="1" class="fqac_w1ss"/></radialGradient><radialGradient id="io7cAZd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.75 5.75 -3.24597 -3.24597 23 10)" gradientUnits="userSpaceOnUse"><stop class="d3wf5jb8r"/><stop offset="1" class="fqac_w1ss"/></radialGradient><radialGradient id="iUE8DMb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 1.5 -.9375 -.9375 9.5 18.5)" gradientUnits="userSpaceOnUse"><stop class="g9x2u_bdo"/><stop offset="1" class="kcdyz5b5v"/></radialGradient><radialGradient id="iVZgjvc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 1.5 -.9375 -.9375 14.5 18.5)" gradientUnits="userSpaceOnUse"><stop class="g9x2u_bdo"/><stop offset="1" class="kcdyz5b5v"/></radialGradient><radialGradient id="iJ2AIld" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 1.5 -.9375 -.9375 19.5 18.5)" gradientUnits="userSpaceOnUse"><stop class="g9x2u_bdo"/><stop offset="1" class="kcdyz5b5v"/></radialGradient><radialGradient id="ilAsCMb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 1.5 -.9375 -.9375 24.5 18.5)" gradientUnits="userSpaceOnUse"><stop class="g9x2u_bdo"/><stop offset="1" class="kcdyz5b5v"/></radialGradient><radialGradient id="i6glX0d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 1.5 -.9375 -.9375 12 20.5)" gradientUnits="userSpaceOnUse"><stop class="g9x2u_bdo"/><stop offset="1" class="kcdyz5b5v"/></radialGradient><radialGradient id="izBhMhb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 1.5 -.9375 -.9375 17 20.5)" gradientUnits="userSpaceOnUse"><stop class="g9x2u_bdo"/><stop offset="1" class="kcdyz5b5v"/></radialGradient><radialGradient id="iL9Lz5M" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 1.5 -.9375 -.9375 22 20.5)" gradientUnits="userSpaceOnUse"><stop class="g9x2u_bdo"/><stop offset="1" class="kcdyz5b5v"/></radialGradient><radialGradient id="iQ0zQae" cx="0" cy="0" r="1" gradientTransform="matrix(-4.20002 2.62497 -1.4747 -2.35956 30 21.875)" gradientUnits="userSpaceOnUse"><stop class="g9x2u_bdo"/><stop offset="1" class="kcdyz5b5v"/></radialGradient><linearGradient id="iIDQKtO" x1="19.115" x2="18.427" y1="9.5" y2="13.53" gradientUnits="userSpaceOnUse"><stop class="ehgdi7b0u"/><stop offset="1" class="kiu9e17zs"/></linearGradient><linearGradient id="i93J0Xd" x1="22.115" x2="21.427" y1="9.5" y2="13.53" gradientUnits="userSpaceOnUse"><stop class="ehgdi7b0u"/><stop offset="1" class="kiu9e17zs"/></linearGradient><linearGradient id="iyfHlMP" x1="9" x2="7.5" y1="18.5" y2="22" gradientUnits="userSpaceOnUse"><stop class="p8mtanzsq"/><stop offset="1" class="ezrjfy63b"/></linearGradient><linearGradient id="ibgQIib" x1="14" x2="12.5" y1="18.5" y2="22" gradientUnits="userSpaceOnUse"><stop class="p8mtanzsq"/><stop offset="1" class="ezrjfy63b"/></linearGradient><linearGradient id="iHDwmdz" x1="19" x2="17.5" y1="18.5" y2="22" gradientUnits="userSpaceOnUse"><stop class="p8mtanzsq"/><stop offset="1" class="ezrjfy63b"/></linearGradient><linearGradient id="iyadRwc" x1="24" x2="22.5" y1="18.5" y2="22" gradientUnits="userSpaceOnUse"><stop class="p8mtanzsq"/><stop offset="1" class="ezrjfy63b"/></linearGradient><linearGradient id="i3ueaLY" x1="11.5" x2="10" y1="20.5" y2="24" gradientUnits="userSpaceOnUse"><stop class="p8mtanzsq"/><stop offset="1" class="ezrjfy63b"/></linearGradient><linearGradient id="ipRTeUd" x1="16.5" x2="15" y1="20.5" y2="24" gradientUnits="userSpaceOnUse"><stop class="p8mtanzsq"/><stop offset="1" class="ezrjfy63b"/></linearGradient><linearGradient id="is0sQGd" x1="21.5" x2="20" y1="20.5" y2="24" gradientUnits="userSpaceOnUse"><stop class="p8mtanzsq"/><stop offset="1" class="ezrjfy63b"/></linearGradient><linearGradient id="iZCF5pG" x1="28.6" x2="26.788" y1="21.875" y2="28.64" gradientUnits="userSpaceOnUse"><stop class="p8mtanzsq"/><stop offset="1" class="ezrjfy63b"/></linearGradient><filter id="ivZVjHe" width="8.387" height="9.401" x="20.629" y="19.576" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_30_9" stdDeviation="1"/></filter><filter id="iAAhInc" width="19.5" height="8" x="5.5" y="17.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_30_9" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:zipper-mouth-face" /></template>
<style>
.aerdp5ttn {
  fill: var(--svg-color--d6a5f5, #D6A5F5);
  fill-rule: evenodd;
  d: path("M9.25 22v-2h.25v2zm5 0v-2h.25v2zm5-2v2h.25v-2z");
}

.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.cl3bxd8pl {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M24.375 19.25v2.625h-2.25V19.25a1.125 1.125 0 0 1 2.25 0Z");
}

.d3wf5jb8r {
  stop-color: var(--svg-color--392108, #392108);
}

.dqtsjxbjo {
  fill: var(--svg-color--e4694e, #E4694E);
  fill-rule: evenodd;
  d: path("M6.5 19.75a1.25 1.25 0 1 1 2.5 0v.75h2.5v-.75a1.25 1.25 0 1 1 2.5 0v.75h2.5v-.75a1.25 1.25 0 1 1 2.5 0v.75h2.5v-.75a1.25 1.25 0 1 1 2.5 0v2.75h-2.5v.75a1.25 1.25 0 1 1-2.5 0v-.75h-2.5v.75a1.25 1.25 0 1 1-2.5 0v-.75h-2.5v.75a1.25 1.25 0 1 1-2.5 0v-.75H6.5z");
}

.ehgdi7b0u {
  stop-color: var(--svg-color--553b3e, #553B3E);
}

.ezrjfy63b {
  stop-color: var(--svg-color--e3b9ff, #E3B9FF);
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

.g9x2u_bdo {
  stop-color: var(--svg-color--ffefff, #FFEFFF);
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.hw0f0elow {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.375 19.25v2.625h-2.25V19.25a1.125 1.125 0 0 1 2.25 0Z");
}

.j-c6jjbfw {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.5 16a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9m11 0a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9");
}

.jfnym5bcl {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.625 20.125h2.25v2.625a1.125 1.125 0 0 1-2.25 0z");
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.kcdyz5b5v {
  stop-color: var(--svg-color--fff2ff, #FFF2FF);
  stop-opacity: 0;
}

.kiu9e17zs {
  stop-color: var(--svg-color--3d2432, #3D2432);
}

.m2i4udbok {
  fill: var(--svg-color--cc532d, #CC532D);
  fill-rule: evenodd;
  d: path("m27.017 23.526l-.405-.798a2.1 2.1 0 0 0-2.692-.986a2.11 2.11 0 0 0-1.182 2.611l.89 2.624a10.96 10.96 0 0 0 3.389-3.45m-3.308.135a.935.935 0 0 0 1.218.498a.915.915 0 0 0 .497-1.218a.935.935 0 0 0-1.218-.497a.934.934 0 0 0-.497 1.217");
}

.maobbcvxh {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.mv_citbmv {
  cx: 9px;
  cy: 13px;
  r: 5px;
}

.n52mgrb1s {
  opacity: var(--svg-opacity--0-4, 0.4);
}

.n9x7k_bur {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M14.375 19.25v2.625h-2.25V19.25a1.125 1.125 0 0 1 2.25 0Z");
}

.nmnni6m-k {
  cx: 19.5px;
  cy: 13.5px;
  r: 4.5px;
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.ouyheebob {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.625 20.125h2.25v2.625a1.125 1.125 0 0 1-2.25 0z");
}

.oy41r6b5d {
  d: path("M21.5 13.5a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.p8mtanzsq {
  stop-color: var(--svg-color--e9c9ff, #E9C9FF);
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.vj7ub1bam {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.375 19.25v2.625h-2.25V19.25a1.125 1.125 0 0 1 2.25 0Z");
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.w6q-flapl {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M14.625 20.125h2.25v2.625a1.125 1.125 0 0 1-2.25 0z");
}

.x9d3htb3i {
  d: path("M10.5 13.5a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.zannmacjr {
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

.zm9v-g_4l {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M29.19 24.026a1.98 1.98 0 0 1 .11 2.892l-.382.382a1.98 1.98 0 0 1-2.894-.11l-2.42-2.789a1.983 1.983 0 0 1 .1-2.693a1.976 1.976 0 0 1 2.695-.1zm-5.132-.462a1.06 1.06 0 0 0 1.492 0a1.04 1.04 0 0 0 0-1.493a1.06 1.06 0 0 0-1.492 0a1.06 1.06 0 0 0 0 1.493Z");
}

</style>
