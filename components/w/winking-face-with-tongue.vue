<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><path fill="url(#ikuTY2d)" clip-rule="evenodd" class="n6tkwcc_j"/><path class="abv2j0b8i"/><path fill="url(#iRIeiFe)" class="e7-aznelp"/><path fill="url(#i86ohjb)" clip-rule="evenodd" class="ot3hns_2v"/><path fill="url(#iNxwQEc)" clip-rule="evenodd" class="oud9i07az"/><path fill="url(#i2u57dd)" class="zrp_wcc4v"/><path fill="url(#iAuD0Sd)" class="qkc9gnbyc"/><g filter="url(#i9fc9Qb)" class="mc2zb0bvp"><path class="ft_ntu_rb"/></g><path fill="url(#iZ8EXsc)" class="orxee1j6a"/><defs><radialGradient id="iuezoob" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.786 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="ikuTY2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.3125 -4.82169 0 11.094 14.813)" gradientUnits="userSpaceOnUse"><stop offset=".337" class="kpzniubsk"/><stop offset=".628" class="ycdr3nb9d"/><stop offset="1" class="opsjn_43s"/><stop offset="1" class="buonrxbuj"/></radialGradient><radialGradient id="i2u57dd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.55556 17.1111 0 15.999 27.556)" gradientUnits="userSpaceOnUse"><stop class="h13dd1l8r"/><stop offset="1" class="di9ro-btr"/></radialGradient><radialGradient id="iAuD0Sd" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 -9.5 16.51504 -.86922 16.5 30)" gradientUnits="userSpaceOnUse"><stop class="yui1fntgg"/><stop offset=".766" class="i3nb-2ysz"/><stop offset=".864" class="p_bns_tff"/><stop offset=".886" class="twpub9y2u"/></radialGradient><linearGradient id="iRIeiFe" x1="22.747" x2="21.063" y1="12" y2="15.284" gradientUnits="userSpaceOnUse"><stop class="ehgdi7b0u"/><stop offset="1" class="kiu9e17zs"/></linearGradient><linearGradient id="i86ohjb" x1="10.167" x2="10.167" y1="12.4" y2="10.6" gradientUnits="userSpaceOnUse"><stop offset=".03" class="ii_r00eab"/><stop offset="1" class="zg8znn0_h"/></linearGradient><linearGradient id="iNxwQEc" x1="25.167" x2="25.167" y1="10.4" y2="8.6" gradientUnits="userSpaceOnUse"><stop offset=".03" class="ii_r00eab"/><stop offset="1" class="zg8znn0_h"/></linearGradient><linearGradient id="iZ8EXsc" x1="15.999" x2="15.999" y1="19" y2="20.43" gradientUnits="userSpaceOnUse"><stop class="nvahlubfz"/><stop offset="1" class="vc--wpv5i"/></linearGradient><filter id="i9fc9Qb" width="4.724" height="5.447" x="16.776" y="22.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_25" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:winking-face-with-tongue" /></template>
<style>
.abv2j0b8i {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.806 17.17c.89-.33 1.85-.53 2.86-.53s1.97.19 2.85.53a4.22 4.22 0 0 0 1.39-3.13c0-2.35-1.9-4.25-4.25-4.25s-4.25 1.9-4.25 4.25a4.25 4.25 0 0 0 1.4 3.13");
}

.buonrxbuj {
  stop-color: var(--svg-color--4a342f, #4A342F);
}

.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.di9ro-btr {
  stop-color: var(--svg-color--89029c, #89029C);
}

.e7-aznelp {
  d: path("M21.209 16a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.ehgdi7b0u {
  stop-color: var(--svg-color--553b3e, #553B3E);
}

.fqgjm_v0b {
  stop-color: var(--svg-color--715b32, #715B32);
}

.ft_ntu_rb {
  stroke: var(--svg-color--fff, #fff);
  d: path("M18 26.5c1-.5 2-1.5 2-3");
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

.kiu9e17zs {
  stop-color: var(--svg-color--3d2432, #3D2432);
}

.kpzniubsk {
  stop-color: var(--svg-color--4d274b, #4D274B);
}

.maobbcvxh {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.n6tkwcc_j {
  fill-rule: evenodd;
  d: path("M11.094 14.156c1.096 0 1.448.697 1.498.898a1 1 0 1 0 1.941-.483c-.225-.904-1.244-2.415-3.44-2.415s-3.214 1.511-3.438 2.415a1 1 0 0 0 1.94.483c.05-.2.402-.898 1.499-.898");
}

.nvahlubfz {
  stop-color: var(--svg-color--eccdff, #ECCDFF);
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.opsjn_43s {
  stop-color: var(--svg-color--4e2553, #4E2553);
}

.orxee1j6a {
  d: path("M22.859 20.43c.09-.46.14-.94.14-1.43h-14c0 .49.05.96.14 1.43z");
}

.ot3hns_2v {
  fill-rule: evenodd;
  d: path("M11 8.5a.5.5 0 0 0-.5-.5c-.774 0-1.742.284-2.585.83c-.848.55-1.612 1.396-1.9 2.549a.5.5 0 0 0 .97.242c.212-.847.781-1.502 1.475-1.952C9.16 9.216 9.94 9 10.5 9a.5.5 0 0 0 .5-.5");
}

.oud9i07az {
  fill-rule: evenodd;
  d: path("M23.93 7.988c.594.562.952 1.24 1.096 1.67a.5.5 0 1 0 .948-.316c-.19-.57-.63-1.392-1.355-2.08C23.887 6.567 22.852 6 21.5 6a.5.5 0 0 0 0 1c1.048 0 1.846.433 2.43.988");
}

.p_bns_tff {
  stop-color: var(--svg-color--bb0773, #BB0773);
}

.qkc9gnbyc {
  d: path("M16.016 29c4.2 0 4.87-4.2 5-5.25c.1-.85-.35-1.28-.84-1.57s-1.96-.56-4.16-.56s-3.66.27-4.16.56s-.95.72-.84 1.57c.13 1.05.8 5.25 5 5.25");
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

.ycdr3nb9d {
  stop-color: var(--svg-color--514047, #514047);
}

.yui1fntgg {
  stop-color: var(--svg-color--ff1c4a, #FF1C4A);
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

.zrp_wcc4v {
  d: path("M15.999 26c-7 0-7-7-7-7h14s0 7-7 7");
}

</style>
