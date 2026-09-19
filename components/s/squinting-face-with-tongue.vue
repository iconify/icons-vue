<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><g filter="url(#igluZFd)" class="ljb4srbfs"><path fill="url(#i8i7t7b)" class="vfwd0hiqu"/><path fill="url(#i8i7t7b)" class="misj7wbbj"/></g><path fill="url(#igZrl8v)" class="yws_7ab3p"/><path fill="url(#iZugPPb)" class="dnutz0b2i"/><g filter="url(#iQ0icMM)"><path fill="url(#iOsbg8c)" class="u49ms3bfa"/><path fill="url(#iOsbg8c)" class="lne9d2igy"/></g><path fill="url(#ixN4XUc)" class="pb8c3wb9y"/><path fill="url(#i505uLT)" class="nhkp9ybhu"/><path fill="url(#i2u57dd)" class="zrp_wcc4v"/><path fill="url(#iAuD0Sd)" class="qkc9gnbyc"/><g filter="url(#iebi8bd)" class="mc2zb0bvp"><path class="ft_ntu_rb"/></g><path fill="url(#iZ8EXsc)" class="orxee1j6a"/></g><defs><radialGradient id="iuezoob" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.786 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="i8i7t7b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.62502 7.125 -9.31237 -3.4309 9.781 11.438)" gradientUnits="userSpaceOnUse"><stop class="vn4n3no1s"/><stop offset=".889" class="ixmaddcbc"/></radialGradient><radialGradient id="iOsbg8c" cx="0" cy="0" r="1" gradientTransform="rotate(-135.995 17.14 3.798)scale(13.3597 17.4611)" gradientUnits="userSpaceOnUse"><stop class="kb93-db6z"/><stop offset=".802" class="z-xmlwmhd"/></radialGradient><radialGradient id="i2u57dd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.55556 17.1111 0 15.999 27.556)" gradientUnits="userSpaceOnUse"><stop class="h13dd1l8r"/><stop offset="1" class="di9ro-btr"/></radialGradient><radialGradient id="iAuD0Sd" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 -9.5 16.51504 -.86922 16.5 30)" gradientUnits="userSpaceOnUse"><stop class="yui1fntgg"/><stop offset=".766" class="i3nb-2ysz"/><stop offset=".864" class="p_bns_tff"/><stop offset=".886" class="twpub9y2u"/></radialGradient><linearGradient id="igZrl8v" x1="10.578" x2="8" y1="17.732" y2="12.389" gradientUnits="userSpaceOnUse"><stop offset=".25" class="ccr58nbuz"/><stop offset=".406" class="gvfj_gdms"/><stop offset=".511" class="ccr58nbuz"/></linearGradient><linearGradient id="iZugPPb" x1="8.86" x2="11.25" y1="14.139" y2="9.451" gradientUnits="userSpaceOnUse"><stop offset=".25" class="ccr58nbuz"/><stop offset=".406" class="gvfj_gdms"/><stop offset=".511" class="ccr58nbuz"/></linearGradient><linearGradient id="ixN4XUc" x1="21.406" x2="23.985" y1="17.732" y2="12.389" gradientUnits="userSpaceOnUse"><stop offset=".25" class="ccr58nbuz"/><stop offset=".406" class="gvfj_gdms"/><stop offset=".511" class="ccr58nbuz"/></linearGradient><linearGradient id="i505uLT" x1="23.125" x2="20.734" y1="14.139" y2="9.451" gradientUnits="userSpaceOnUse"><stop offset=".25" class="ccr58nbuz"/><stop offset=".406" class="gvfj_gdms"/><stop offset=".511" class="ccr58nbuz"/></linearGradient><linearGradient id="iZ8EXsc" x1="15.999" x2="15.999" y1="19" y2="20.43" gradientUnits="userSpaceOnUse"><stop class="nvahlubfz"/><stop offset="1" class="vc--wpv5i"/></linearGradient><filter id="igluZFd" width="7" height="6.996" x="7.5" y="10.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_35" stdDeviation=".25"/></filter><filter id="iQ0icMM" width="7" height="6.996" x="16.906" y="10.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_35" stdDeviation=".25"/></filter><filter id="iebi8bd" width="4.724" height="5.447" x="16.776" y="22.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_35" stdDeviation=".5"/></filter><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:squinting-face-with-tongue" /></template>
<style>
.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.ccr58nbuz {
  stop-color: var(--svg-color--482641, #482641);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.di9ro-btr {
  stop-color: var(--svg-color--89029c, #89029C);
}

.dnutz0b2i {
  d: path("M9.447 11.106a1 1 0 1 0-.894 1.789l2.206 1.103H14a1 1 0 0 0-.553-.892z");
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

.gvfj_gdms {
  stop-color: var(--svg-color--503a4a, #503A4A);
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.i3nb-2ysz {
  stop-color: var(--svg-color--ff2b8f, #FF2B8F);
}

.ixmaddcbc {
  stop-color: var(--svg-color--9f5e0f, #9F5E0F);
  stop-opacity: 0;
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.kb93-db6z {
  stop-color: var(--svg-color--e9830a, #E9830A);
}

.ljb4srbfs {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
}

.lne9d2igy {
  d: path("M21.959 11.543a1 1 0 0 1 .895 1.79l-2.207 1.102h-3.24a1 1 0 0 1 .552-.892z");
}

.maobbcvxh {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.misj7wbbj {
  d: path("M9.447 11.543a1 1 0 1 0-.894 1.79l2.206 1.102H14a1 1 0 0 0-.553-.892z");
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.nhkp9ybhu {
  d: path("M22.537 11.106a1 1 0 1 1 .895 1.789l-2.207 1.103h-3.24a1 1 0 0 1 .552-.892z");
}

.nvahlubfz {
  stop-color: var(--svg-color--eccdff, #ECCDFF);
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.orxee1j6a {
  d: path("M22.859 20.43c.09-.46.14-.94.14-1.43h-14c0 .49.05.96.14 1.43z");
}

.p_bns_tff {
  stop-color: var(--svg-color--bb0773, #BB0773);
}

.pb8c3wb9y {
  d: path("M22.537 16.89a1 1 0 1 0 .895-1.789l-2.207-1.103h-3.24a1 1 0 0 0 .552.892z");
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

.u49ms3bfa {
  d: path("M21.959 17.328a1 1 0 0 0 .895-1.79l-2.207-1.103h-3.24a1 1 0 0 0 .552.893z");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vfwd0hiqu {
  d: path("M9.447 17.328a1 1 0 1 1-.894-1.79l2.206-1.103H14a1 1 0 0 1-.553.893z");
}

.vn4n3no1s {
  stop-color: var(--svg-color--9f5e0f, #9F5E0F);
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.yui1fntgg {
  stop-color: var(--svg-color--ff1c4a, #FF1C4A);
}

.yws_7ab3p {
  d: path("M9.447 16.89a1 1 0 1 1-.894-1.789l2.206-1.103H14a1 1 0 0 1-.553.892z");
}

.z-xmlwmhd {
  stop-color: var(--svg-color--f08b13, #F08B13);
  stop-opacity: 0;
}

.zannmacjr {
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

.zrp_wcc4v {
  d: path("M15.999 26c-7 0-7-7-7-7h14s0 7-7 7");
}

</style>
