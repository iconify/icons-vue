<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#i6jPBrb)" class="bmnxvhvhj"/><circle fill="url(#iXwO9bc)" class="bmnxvhvhj"/><circle fill="url(#iLI4uHr)" class="bmnxvhvhj"/><path fill="url(#iGRepqc)" class="x8cspvbof"/><path fill="url(#itkmVxd)" class="x8cspvbof"/><path fill="url(#i7yHzLe)" class="x8cspvbof"/><path fill="url(#i9AxlHz)" class="x8cspvbof"/><path fill="url(#iHB1P4b)" class="x8cspvbof"/><path fill="url(#i9sAMab)" class="ipdj63c5u"/><path fill="url(#iMhrwKb)" class="ipdj63c5u"/><path fill="url(#inDSKYk)" class="ipdj63c5u"/><path fill="url(#icUSLGh)" class="ipdj63c5u"/><path fill="url(#i2TSwre)" class="ipdj63c5u"/><path fill="url(#inm4Ifc)" class="ipdj63c5u"/><g filter="url(#iivrt4b)"><path stroke="url(#iQsioYd)" class="p4l2g9box"/></g><g filter="url(#iL4LPie)"><path stroke="url(#iFw8utc)" class="knb5ki36p"/></g><defs><linearGradient id="iGRepqc" x1="11.526" x2="7.495" y1="11.247" y2="20.747" gradientUnits="userSpaceOnUse"><stop offset=".213" class="xqnfih2gx"/><stop offset="1" class="eomw7ewte"/></linearGradient><linearGradient id="itkmVxd" x1="7.495" x2="7.495" y1="9.044" y2="14.112" gradientUnits="userSpaceOnUse"><stop class="uynbgrb0l"/><stop offset="1" class="x8ea45iup"/></linearGradient><linearGradient id="i7yHzLe" x1="8.776" x2="8.776" y1="23.309" y2="19.309" gradientUnits="userSpaceOnUse"><stop class="x5lqphq8h"/><stop offset="1" class="zvz8qlarm"/></linearGradient><linearGradient id="i9AxlHz" x1="4.526" x2="7.088" y1="18.247" y2="18.247" gradientUnits="userSpaceOnUse"><stop offset=".024" class="wld4165qw"/><stop offset="1" class="q2w1p2b0o"/></linearGradient><linearGradient id="iHB1P4b" x1="11.047" x2="10.078" y1="20.736" y2="20.736" gradientUnits="userSpaceOnUse"><stop offset=".267" class="fmch9nfhz"/><stop offset="1" class="dliz4m_2v"/></linearGradient><linearGradient id="i9sAMab" x1="21.901" x2="13.401" y1="7.747" y2="24.059" gradientUnits="userSpaceOnUse"><stop class="zll6_ybds"/><stop offset="1" class="g2jr1acbg"/></linearGradient><linearGradient id="iMhrwKb" x1="9.309" x2="13.493" y1="18.565" y2="18.565" gradientUnits="userSpaceOnUse"><stop class="yh6p7rbkd"/><stop offset="1" class="x4kltfeie"/></linearGradient><linearGradient id="icUSLGh" x1="14.495" x2="16.182" y1="25.465" y2="22.278" gradientUnits="userSpaceOnUse"><stop class="mx0-_-bnf"/><stop offset="1" class="r2ap025qq"/></linearGradient><linearGradient id="i2TSwre" x1="22.519" x2="19.134" y1="21.693" y2="21.693" gradientUnits="userSpaceOnUse"><stop class="m8s297b3v"/><stop offset="1" class="hxtzfj5-c"/></linearGradient><linearGradient id="iQsioYd" x1="26.304" x2="26.304" y1="11.59" y2="21.468" gradientUnits="userSpaceOnUse"><stop class="xjer7pf-z"/><stop offset="1" class="iliezdb7y"/></linearGradient><linearGradient id="iFw8utc" x1="26.53" x2="26.53" y1="11.396" y2="21.274" gradientUnits="userSpaceOnUse"><stop class="g829ebtyg"/><stop offset="1" class="mwpgiabok"/></linearGradient><radialGradient id="i6jPBrb" cx="0" cy="0" r="1" gradientTransform="rotate(113.233 7.098 14.632)scale(5.79574)" gradientUnits="userSpaceOnUse"><stop offset=".097" class="hrr8zy_rp"/><stop offset="1" class="h_z277b1n"/></radialGradient><radialGradient id="iXwO9bc" cx="0" cy="0" r="1" gradientTransform="rotate(145.706 9.304 11.043)scale(1.89104)" gradientUnits="userSpaceOnUse"><stop class="l60ra8jjy"/><stop offset="1" class="tgfv31bgu"/></radialGradient><radialGradient id="iLI4uHr" cx="0" cy="0" r="1" gradientTransform="matrix(-.27222 3.9757 -4.04797 -.27717 21.329 15.232)" gradientUnits="userSpaceOnUse"><stop offset=".594" class="ugdrqda4u"/><stop offset="1" class="apvdk2bdd"/></radialGradient><radialGradient id="inDSKYk" cx="0" cy="0" r="1" gradientTransform="matrix(2.625 4.375 -15.32416 9.19451 13.557 6.966)" gradientUnits="userSpaceOnUse"><stop offset=".115" class="vof13p-wh"/><stop offset="1" class="jpvc-qw9x"/></radialGradient><radialGradient id="inm4Ifc" cx="0" cy="0" r="1" gradientTransform="matrix(0 16.0625 -2.22649 0 20.463 11.653)" gradientUnits="userSpaceOnUse"><stop class="s6vdf8bty"/><stop offset="1" class="q_rhnrbqh"/></radialGradient><filter id="iivrt4b" width="3.788" height="10.979" x="24.41" y="10.39" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.396078 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17827"/></filter><filter id="iL4LPie" width="3.188" height="10.129" x="24.936" y="10.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17827" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:speaker-medium-volume" /></template>
<style>
.apvdk2bdd {
  stop-color: var(--svg-color--b9b6bf, #B9B6BF);
}

.bmnxvhvhj {
  cx: 21.057px;
  cy: 15.989px;
  r: 3.219px;
}

.dliz4m_2v {
  stop-color: var(--svg-color--ccc5d4, #CCC5D4);
  stop-opacity: 0;
}

.eomw7ewte {
  stop-color: var(--svg-color--ddd5e6, #DDD5E6);
}

.fmch9nfhz {
  stop-color: var(--svg-color--ccc5d4, #CCC5D4);
}

.ft5dv1b6b {
  fill: none;
}

.g2jr1acbg {
  stop-color: var(--svg-color--cac2d3, #CAC2D3);
}

.g829ebtyg {
  stop-color: var(--svg-color--5bc7ff, #5BC7FF);
}

.h_z277b1n {
  stop-color: var(--svg-color--cecad6, #CECAD6);
}

.hrr8zy_rp {
  stop-color: var(--svg-color--e1e0e4, #E1E0E4);
}

.hxtzfj5-c {
  stop-color: var(--svg-color--d2cbda, #D2CBDA);
  stop-opacity: 0;
}

.iliezdb7y {
  stop-color: var(--svg-color--4998f7, #4998F7);
}

.ipdj63c5u {
  d: path("M21.323 6.865c0-1.62-1.724-2.658-3.156-1.9l-7.704 4.079v13.89l7.7 4.099c1.431.762 3.16-.275 3.16-1.898z");
}

.jpvc-qw9x {
  stop-color: var(--svg-color--c2bdc7, #C2BDC7);
  stop-opacity: 0;
}

.knb5ki36p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M25.586 11.396a5.85 5.85 0 0 1 1.888 4.326c0 2.31-1.226 3.932-1.888 4.503");
}

.l60ra8jjy {
  stop-color: var(--svg-color--f4f6fe, #F4F6FE);
}

.m8s297b3v {
  stop-color: var(--svg-color--e6e7ef, #E6E7EF);
}

.mwpgiabok {
  stop-color: var(--svg-color--4c97f6, #4C97F6);
}

.mx0-_-bnf {
  stop-color: var(--svg-color--b3afb8, #B3AFB8);
}

.p4l2g9box {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-9px, 1.9px);
  d: path("M25.36 11.59a5.85 5.85 0 0 1 1.888 4.325c0 2.312-1.226 3.933-1.888 4.504");
}

.q_rhnrbqh {
  stop-color: var(--svg-color--e7e6ee, #E7E6EE);
  stop-opacity: 0;
}

.q2w1p2b0o {
  stop-color: var(--svg-color--c3becb, #C3BECB);
  stop-opacity: 0;
}

.r2ap025qq {
  stop-color: var(--svg-color--cac2d3, #CAC2D3);
  stop-opacity: 0;
}

.s6vdf8bty {
  stop-color: var(--svg-color--f8f6fb, #F8F6FB);
}

.tgfv31bgu {
  stop-color: var(--svg-color--f4f6fe, #F4F6FE);
  stop-opacity: 0;
}

.ugdrqda4u {
  stop-color: var(--svg-color--d1ccd9, #D1CCD9);
  stop-opacity: 0;
}

.uynbgrb0l {
  stop-color: var(--svg-color--c5c4c5, #C5C4C5);
}

.vof13p-wh {
  stop-color: var(--svg-color--ababac, #ABABAC);
}

.wld4165qw {
  stop-color: var(--svg-color--a5a5a5, #A5A5A5);
}

.x4kltfeie {
  stop-color: var(--svg-color--c4becc, #C4BECC);
  stop-opacity: 0;
}

.x5lqphq8h {
  stop-color: var(--svg-color--b6b0bd, #B6B0BD);
}

.x8cspvbof {
  d: path("M4.526 10.644a1.6 1.6 0 0 1 1.6-1.6h4.337v13.89H6.126a1.6 1.6 0 0 1-1.6-1.6z");
}

.x8ea45iup {
  stop-color: var(--svg-color--c5c4c5, #C5C4C5);
  stop-opacity: 0;
}

.xjer7pf-z {
  stop-color: var(--svg-color--41aeff, #41AEFF);
}

.xqnfih2gx {
  stop-color: var(--svg-color--d2ced6, #D2CED6);
}

.yh6p7rbkd {
  stop-color: var(--svg-color--c4becc, #C4BECC);
}

.zll6_ybds {
  stop-color: var(--svg-color--bfbac4, #BFBAC4);
}

.zvz8qlarm {
  stop-color: var(--svg-color--d8d0e1, #D8D0E1);
  stop-opacity: 0;
}

</style>
