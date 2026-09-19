<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><g filter="url(#iB9IFId)"><path fill="url(#ifS8Osb)" class="cx1b_vnca"/></g><g filter="url(#ipDjVsd)"><path fill="url(#iDUQxxd)" class="mkbq4fbsi"/></g><g filter="url(#iKOMdJe)"><path fill="url(#iY9a8Wd)" class="qosizt8rk"/></g><g filter="url(#i86Bh5W)"><path fill="url(#iRuXxwb)" class="c4mmkf7gy"/></g><path fill="url(#i3lbH6d)" stroke="url(#iSbWHld)" class="g1cf1zbby"/><path fill="url(#iOO4Fdc)" stroke="url(#iCSrOsd)" class="z6cjzbb7l"/><path fill="url(#iwcV7de)" class="bod4qivqw"/><path fill="url(#i9qY4mB)" class="hh7up8s9k"/></g><defs><radialGradient id="iuezoob" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.786 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="iY9a8Wd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.5 3 -3 -4.5 20 10)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="xjyer8b8q"/><stop offset="1" class="lxsk2wb0p"/></radialGradient><radialGradient id="iRuXxwb" cx="0" cy="0" r="1" gradientTransform="rotate(158.199 2.248 7.174)scale(5.38516)" gradientUnits="userSpaceOnUse"><stop class="z3kb90exn"/><stop offset="1" class="ozk-jcbqz"/></radialGradient><radialGradient id="iwcV7de" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11 22 0 16 28)" gradientUnits="userSpaceOnUse"><stop class="h13dd1l8r"/><stop offset="1" class="di9ro-btr"/></radialGradient><linearGradient id="ifS8Osb" x1="23.5" x2="21.814" y1="11.5" y2="14.667" gradientUnits="userSpaceOnUse"><stop offset=".37" class="xjyer8b8q"/><stop offset="1" class="lxsk2wb0p"/></linearGradient><linearGradient id="iDUQxxd" x1="10.5" x2="10.25" y1="11.5" y2="14.025" gradientUnits="userSpaceOnUse"><stop class="jq0ebfbip"/><stop offset="1" class="of_fexbfm"/></linearGradient><linearGradient id="i3lbH6d" x1="7.5" x2="10" y1="1" y2="15" gradientUnits="userSpaceOnUse"><stop class="s3b-tqmbe"/><stop offset="1" class="zudi05bms"/></linearGradient><linearGradient id="iSbWHld" x1="15" x2="8.5" y1="6" y2="8.5" gradientUnits="userSpaceOnUse"><stop class="m2wrlub-b"/><stop offset="1" class="lx0g_9bvi"/></linearGradient><linearGradient id="iOO4Fdc" x1="22" x2="22.5" y1="2.5" y2="14.5" gradientUnits="userSpaceOnUse"><stop class="s3b-tqmbe"/><stop offset="1" class="zudi05bms"/></linearGradient><linearGradient id="iCSrOsd" x1="29.5" x2="23.5" y1="6" y2="6.5" gradientUnits="userSpaceOnUse"><stop class="iu-fsmb8w"/><stop offset="1" class="lx0g_9bvi"/></linearGradient><linearGradient id="i9qY4mB" x1="16" x2="16" y1="17" y2="18.5" gradientUnits="userSpaceOnUse"><stop class="djbvjbb0b"/><stop offset="1" class="vc--wpv5i"/></linearGradient><filter id="iB9IFId" width="8.5" height="9" x="18" y="10" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_23_461" stdDeviation=".5"/></filter><filter id="ipDjVsd" width="8.5" height="6.5" x="6" y="9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_23_461" stdDeviation=".5"/></filter><filter id="iKOMdJe" width="5.253" height="9" x="15.5" y="5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_23_461" stdDeviation=".5"/></filter><filter id="i86Bh5W" width="5.253" height="10" x="2" y="7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_23_461" stdDeviation=".5"/></filter><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:star-struck" /></template>
<style>
.bod4qivqw {
  d: path("M16 26c-9 0-9-9-9-9h18s0 9-9 9");
}

.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.c4mmkf7gy {
  d: path("M3 8h2c1.6 1.6 1.333 4.667 1 6l-3 2l1.5-4.5z");
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.cx1b_vnca {
  d: path("M25.5 18L19 12.5l6-1.5z");
}

.di9ro-btr {
  stop-color: var(--svg-color--89029c, #89029C);
}

.djbvjbb0b {
  stop-color: var(--svg-color--d5a8fe, #D5A8FE);
}

.fqgjm_v0b {
  stop-color: var(--svg-color--715b32, #715B32);
}

.ft5dv1b6b {
  fill: none;
}

.g1cf1zbby {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m8.624 12.865l-3.05 2.372a.15.15 0 0 1-.242-.132l.3-3.285a2.25 2.25 0 0 0-1.149-2.171L2.5 8.548a.5.5 0 0 1 .058-.902l2.529-1.012a2.25 2.25 0 0 0 1.37-1.647l.472-2.359a.47.47 0 0 1 .837-.19l1.364 1.82a2.25 2.25 0 0 0 2.004.89l3.493-.318a.15.15 0 0 1 .133.24l-1.786 2.38a2.25 2.25 0 0 0-.289 2.186l1.412 3.528l-3.65-.73a2.25 2.25 0 0 0-1.823.43Z");
}

.g4z4xncfo {
  stop-color: var(--svg-color--ffb849, #FFB849);
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.hh7up8s9k {
  d: path("M8 17.5V17h16v.5a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1");
}

.iu-fsmb8w {
  stop-color: var(--svg-color--b51aa6, #B51AA6);
}

.jq0ebfbip {
  stop-color: var(--svg-color--c85f27, #C85F27);
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.lx0g_9bvi {
  stop-color: var(--svg-color--bf33b1, #BF33B1);
  stop-opacity: 0;
}

.lxsk2wb0p {
  stop-color: var(--svg-color--fba84c, #FBA84C);
  stop-opacity: 0;
}

.m2wrlub-b {
  stop-color: var(--svg-color--a82d9c, #A82D9C);
}

.maobbcvxh {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.mkbq4fbsi {
  d: path("M13.5 14.5L7 14l4.5-4z");
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.of_fexbfm {
  stop-color: var(--svg-color--c85f27, #C85F27);
  stop-opacity: 0;
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.ozk-jcbqz {
  stop-color: var(--svg-color--e6872b, #E6872B);
  stop-opacity: 0;
}

.qosizt8rk {
  d: path("M16.5 6h2c1.6 1.6 1.333 4.667 1 6l-3 1L18 9.5z");
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.s3b-tqmbe {
  stop-color: var(--svg-color--7912b2, #7912B2);
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

.xjyer8b8q {
  stop-color: var(--svg-color--ec812a, #EC812A);
}

.z3kb90exn {
  stop-color: var(--svg-color--cc7521, #CC7521);
}

.z6cjzbb7l {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m23.376 12.865l3.05 2.372a.15.15 0 0 0 .242-.132l-.3-3.285a2.25 2.25 0 0 1 1.149-2.171L29.5 8.548a.5.5 0 0 0-.058-.902l-2.529-1.012a2.25 2.25 0 0 1-1.37-1.647l-.472-2.359a.47.47 0 0 0-.837-.19l-1.364 1.82a2.25 2.25 0 0 1-2.004.89l-3.493-.318a.15.15 0 0 0-.133.24l1.786 2.38a2.25 2.25 0 0 1 .289 2.186l-1.412 3.528l3.65-.73a2.25 2.25 0 0 1 1.823.43Z");
}

.zannmacjr {
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

.zudi05bms {
  stop-color: var(--svg-color--cf1da1, #CF1DA1);
}

</style>
