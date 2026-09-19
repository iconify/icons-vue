<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iJfiV3c)" class="r8d3-xbtp"/><path fill="url(#idgqL3Y)" class="sx-fk9bwz"/><path fill="url(#igwzucd)" class="sx-fk9bwz"/><path fill="url(#iJalxgd)" class="sx-fk9bwz"/><path class="cixq9jo8z"/><path fill="url(#i4LHIox)" class="m3ovqgbnf"/><path fill="url(#is4NQJe)" class="m3ovqgbnf"/><path fill="url(#iJd76Qb)" class="m3ovqgbnf"/><path fill="url(#io96o4C)" class="m3ovqgbnf"/><path fill="url(#iFhabqe)" class="m3ovqgbnf"/><path fill="url(#iHJTGSd)" class="m3ovqgbnf"/><circle class="ri0juacgz"/><circle class="z0bro3bze"/><circle class="a0-e4ccjn"/><g filter="url(#ijcG5ub)"><path stroke="url(#iJSDwkb)" class="ierunjztg"/></g><g filter="url(#ipHvtxc)"><path class="lhxg42bmw"/></g><g filter="url(#iRdi9be)"><path stroke="url(#iI3i8wp)" class="rgluv22eg"/></g><defs><radialGradient id="idgqL3Y" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37498 1.9375 -1.99256 -1.41405 6.625 5.438)" gradientUnits="userSpaceOnUse"><stop class="eu0qumesk"/><stop offset="1" class="zo13vrb2o"/></radialGradient><radialGradient id="igwzucd" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 -3.75 3.84167 2.49709 5.5 9.875)" gradientUnits="userSpaceOnUse"><stop offset=".421" class="wd338rbfr"/><stop offset="1" class="rgg2n055a"/></radialGradient><radialGradient id="iJalxgd" cx="0" cy="0" r="1" gradientTransform="rotate(120.261 3.87 4.55)scale(4.41397 4.52188)" gradientUnits="userSpaceOnUse"><stop offset=".074" class="fndrz0eyy"/><stop offset=".846" class="gemc-abyp"/></radialGradient><radialGradient id="i4LHIox" cx="0" cy="0" r="1" gradientTransform="rotate(123.104 7.278 14.99)scale(16.8519 17.0088)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="rg-i05b3y"/><stop offset=".594" class="s-hcfvz2l"/><stop offset=".792" class="vm_0iibfk"/><stop offset="1" class="q4t_xcc0w"/></radialGradient><radialGradient id="is4NQJe" cx="0" cy="0" r="1" gradientTransform="rotate(43.636 -2.96 23.827)scale(7.42673 5.33268)" gradientUnits="userSpaceOnUse"><stop class="pwt6w8bxc"/><stop offset="1" class="rbo5g7j5f"/></radialGradient><radialGradient id="iJd76Qb" cx="0" cy="0" r="1" gradientTransform="rotate(118.025 6.371 12.968)scale(26.3382 26.5835)" gradientUnits="userSpaceOnUse"><stop offset=".385" class="e6xucub2p"/><stop offset=".615" class="rboxso_4i"/><stop offset=".695" class="prmy01sdn"/></radialGradient><radialGradient id="io96o4C" cx="0" cy="0" r="1" gradientTransform="matrix(-.98186 9.55343 -9.64239 -.991 30.107 22)" gradientUnits="userSpaceOnUse"><stop class="xo68b3byf"/><stop offset="1" class="rnxwj6bai"/></radialGradient><radialGradient id="iFhabqe" cx="0" cy="0" r="1" gradientTransform="matrix(2.1875 7.9375 -6.59351 1.8171 10.438 19.625)" gradientUnits="userSpaceOnUse"><stop class="j5reoow2r"/><stop offset="1" class="dp7_8jz2h"/></radialGradient><radialGradient id="iHJTGSd" cx="0" cy="0" r="1" gradientTransform="matrix(1.0625 4 -4.03725 1.0724 8.563 13.875)" gradientUnits="userSpaceOnUse"><stop class="l_wuocxtl"/><stop offset="1" class="foi5y3kww"/></radialGradient><linearGradient id="iJfiV3c" x1="8.313" x2="11.188" y1="8.5" y2="6.438" gradientUnits="userSpaceOnUse"><stop class="t6z48-bqd"/><stop offset=".472" class="q95eq4o4c"/><stop offset=".699" class="rew1hmvab"/></linearGradient><linearGradient id="iJSDwkb" x1="9.028" x2="9.551" y1="11.545" y2="11.503" gradientUnits="userSpaceOnUse"><stop class="b30z_8b_b"/><stop offset=".89" class="q-t-otz6z"/></linearGradient><linearGradient id="iI3i8wp" x1="7.328" x2="7.712" y1="7.422" y2="5.172" gradientUnits="userSpaceOnUse"><stop class="jg_z5m0lz"/><stop offset="1" class="j5mwi2bke"/></linearGradient><filter id="ijcG5ub" width="4.205" height="6.125" x="7.309" y="8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29066" stdDeviation=".75"/></filter><filter id="ipHvtxc" width="4.813" height="3.844" x="6.282" y="3.285" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29066" stdDeviation=".5"/></filter><filter id="iRdi9be" width="1.858" height="3.329" x="6.832" y="4.932" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29066" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:poultry-leg" /></template>
<style>
.a0-e4ccjn {
  cx: 21px;
  cy: 19px;
  r: 1px;
  fill: var(--svg-color--e78a61, #E78A61);
}

.b30z_8b_b {
  stop-color: var(--svg-color--a57359, #A57359);
}

.cixq9jo8z {
  fill: var(--svg-color--d1815d, #D1815D);
  d: path("M11.406 26.031c2.853 4.146 8.748 5.344 12.853 2.38c3.915-2.835 4.955-8.5 2.241-12.505c-1.744-2.558-4.531-3.875-7.25-4.125c-2.22-.204-3.2-1.935-4.625-3.343c-1.01-1-2.372-1.32-3.469-.563L9.334 9.126c-1.106.755-1.31 2.403-.553 3.5c.938 1.78 1.75 2.937 1.563 4.968c-.256 2.77-.678 5.911 1.062 8.437");
}

.dp7_8jz2h {
  stop-color: var(--svg-color--b27759, #B27759);
  stop-opacity: 0;
}

.e6xucub2p {
  stop-color: var(--svg-color--c66576, #C66576);
  stop-opacity: 0;
}

.eu0qumesk {
  stop-color: var(--svg-color--f4e8ff, #F4E8FF);
}

.fndrz0eyy {
  stop-color: var(--svg-color--faf4ff, #FAF4FF);
}

.foi5y3kww {
  stop-color: var(--svg-color--874e45, #874E45);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gemc-abyp {
  stop-color: var(--svg-color--c5c2c7, #C5C2C7);
  stop-opacity: 0;
}

.ierunjztg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M9.763 9.75c-.396.354-1.087 1.225-.437 2.625");
}

.j5mwi2bke {
  stop-color: var(--svg-color--dcc2f2, #DCC2F2);
}

.j5reoow2r {
  stop-color: var(--svg-color--956a56, #956A56);
}

.jg_z5m0lz {
  stop-color: var(--svg-color--c390e6, #C390E6);
}

.l_wuocxtl {
  stop-color: var(--svg-color--874e46, #874E46);
}

.lhxg42bmw {
  fill: var(--svg-color--d3b2ee, #D3B2EE);
  d: path("M10.073 5.558c-.144.49-.879.706-1.642.484c-.764-.223-1.267-.801-1.124-1.291s.838-.57 1.602-.347c.763.222 1.306.664 1.163 1.154");
}

.m3ovqgbnf {
  d: path("M11.406 26.031c2.853 4.146 8.748 5.344 12.853 2.38c3.915-2.835 4.955-8.5 2.241-12.505c-1.744-2.558-4.531-3.875-7.25-4.125c-2.22-.204-3.2-1.935-4.625-3.343c-1.01-1-2.372-1.32-3.469-.563L9.334 9.126c-1.106.755-1.31 2.403-.553 3.5c.938 1.78 1.75 2.937 1.563 4.968c-.256 2.77-.678 5.911 1.062 8.437");
}

.prmy01sdn {
  stop-color: var(--svg-color--bd68c6, #BD68C6);
}

.pwt6w8bxc {
  stop-color: var(--svg-color--ffd2b0, #FFD2B0);
}

.q-t-otz6z {
  stop-color: var(--svg-color--dedcd9, #DEDCD9);
}

.q4t_xcc0w {
  stop-color: var(--svg-color--80584b, #80584B);
}

.q95eq4o4c {
  stop-color: var(--svg-color--e3d6e9, #E3D6E9);
}

.r8d3-xbtp {
  d: path("M4.5 7.281c.344.36.692.56.984.664c1.207.427 1.839-.41 2.266.117l4.004 5.417l2.675-1.938l-4.038-5.416c-.505-.703 1.459-1.512.234-3.188c-.68-.93-1.703-1.132-2.625-.742c-.612.26-.781.742-1.051 1.303c-.118.245-.265.396-.498.357a2.23 2.23 0 0 0-1.638.41c-.878.63-1.05 2.245-.313 3.016");
}

.rbo5g7j5f {
  stop-color: var(--svg-color--fcb682, #FCB682);
  stop-opacity: 0;
}

.rboxso_4i {
  stop-color: var(--svg-color--ae4b94, #AE4B94);
}

.rew1hmvab {
  stop-color: var(--svg-color--faf2f9, #FAF2F9);
}

.rg-i05b3y {
  stop-color: var(--svg-color--ffc995, #FFC995);
}

.rgg2n055a {
  stop-color: var(--svg-color--c68fee, #C68FEE);
  stop-opacity: 0;
}

.rgluv22eg {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M7.484 7.563c.407-.313.604-1.088.329-2.063");
}

.ri0juacgz {
  cx: 22px;
  cy: 16px;
  r: 1px;
  fill: var(--svg-color--e78a61, #E78A61);
}

.rnxwj6bai {
  stop-color: var(--svg-color--ffad78, #FFAD78);
  stop-opacity: 0;
}

.s-hcfvz2l {
  stop-color: var(--svg-color--c07554, #C07554);
}

.sx-fk9bwz {
  d: path("M4.5 7.281c.344.36.692.56.984.664c.967.342 3.594 0 1.813-3.414c2.11 2.89 4.766.094 3.328-1.594C9.769 1.932 8.922 1.805 8 2.195c-.612.26-.781.742-1.051 1.303c-.118.245-.265.396-.498.357a2.23 2.23 0 0 0-1.638.41c-.878.63-1.05 2.245-.313 3.016");
}

.t6z48-bqd {
  stop-color: var(--svg-color--b394cb, #B394CB);
}

.vm_0iibfk {
  stop-color: var(--svg-color--b26b50, #B26B50);
}

.wd338rbfr {
  stop-color: var(--svg-color--c489ee, #C489EE);
}

.xo68b3byf {
  stop-color: var(--svg-color--ffaf79, #FFAF79);
}

.z0bro3bze {
  cx: 24.078px;
  cy: 18.391px;
  r: 1px;
  fill: var(--svg-color--e78a61, #E78A61);
}

.zo13vrb2o {
  stop-color: var(--svg-color--cac7cf, #CAC7CF);
}

</style>
