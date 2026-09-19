<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#inTc0Ld)" class="kh2n5r75o"/><circle fill="url(#i8mztob)" class="kh2n5r75o"/><circle fill="url(#ikPacob)" class="kh2n5r75o"/><path fill="url(#igNwdgb)" class="a6mjw833w"/><path fill="url(#iUrhDBQ)" class="a6mjw833w"/><path fill="url(#iUrWNwb)" class="a6mjw833w"/><path fill="url(#iVF0Mkm)" class="a6mjw833w"/><path fill="url(#iHEnmmc)" class="a6mjw833w"/><path fill="url(#iE6uNYd)" class="wk85oj57n"/><path fill="url(#ilbBzte)" class="wk85oj57n"/><path fill="url(#iBGoYAR)" class="wk85oj57n"/><path fill="url(#i6DNtte)" class="wk85oj57n"/><path fill="url(#ibe9rTc)" class="wk85oj57n"/><path fill="url(#iT2n7Jb)" class="wk85oj57n"/><g filter="url(#ioZU2Bb)"><path stroke="url(#iNnMXfc)" class="jsrupi03d"/></g><g filter="url(#ifZQyBd)"><path stroke="url(#iZBFiEy)" class="h2myt6bim"/></g><g filter="url(#iBK81HA)"><path stroke="url(#i0CeudL)" class="a7py1p9lm"/></g><g filter="url(#ioUjhnc)"><path stroke="url(#ir4JT9b)" class="zm7w0e9qx"/></g><defs><linearGradient id="igNwdgb" x1="9.466" x2="5.435" y1="11.247" y2="20.747" gradientUnits="userSpaceOnUse"><stop offset=".213" class="xqnfih2gx"/><stop offset="1" class="eomw7ewte"/></linearGradient><linearGradient id="iUrhDBQ" x1="5.435" x2="5.435" y1="9.044" y2="14.112" gradientUnits="userSpaceOnUse"><stop class="uynbgrb0l"/><stop offset="1" class="x8ea45iup"/></linearGradient><linearGradient id="iUrWNwb" x1="6.716" x2="6.716" y1="23.309" y2="19.309" gradientUnits="userSpaceOnUse"><stop class="x5lqphq8h"/><stop offset="1" class="zvz8qlarm"/></linearGradient><linearGradient id="iVF0Mkm" x1="2.466" x2="5.029" y1="18.247" y2="18.247" gradientUnits="userSpaceOnUse"><stop offset=".024" class="wld4165qw"/><stop offset="1" class="q2w1p2b0o"/></linearGradient><linearGradient id="iHEnmmc" x1="8.987" x2="8.019" y1="20.736" y2="20.736" gradientUnits="userSpaceOnUse"><stop offset=".267" class="fmch9nfhz"/><stop offset="1" class="dliz4m_2v"/></linearGradient><linearGradient id="iE6uNYd" x1="19.841" x2="11.341" y1="7.747" y2="24.059" gradientUnits="userSpaceOnUse"><stop class="zll6_ybds"/><stop offset="1" class="g2jr1acbg"/></linearGradient><linearGradient id="ilbBzte" x1="7.25" x2="11.433" y1="18.565" y2="18.565" gradientUnits="userSpaceOnUse"><stop class="yh6p7rbkd"/><stop offset="1" class="x4kltfeie"/></linearGradient><linearGradient id="i6DNtte" x1="12.435" x2="14.123" y1="25.465" y2="22.278" gradientUnits="userSpaceOnUse"><stop class="mx0-_-bnf"/><stop offset="1" class="r2ap025qq"/></linearGradient><linearGradient id="ibe9rTc" x1="20.459" x2="17.074" y1="21.693" y2="21.693" gradientUnits="userSpaceOnUse"><stop class="m8s297b3v"/><stop offset="1" class="hxtzfj5-c"/></linearGradient><linearGradient id="iNnMXfc" x1="24.244" x2="24.244" y1="11.59" y2="21.468" gradientUnits="userSpaceOnUse"><stop class="xjer7pf-z"/><stop offset="1" class="iliezdb7y"/></linearGradient><linearGradient id="iZBFiEy" x1="24.471" x2="24.471" y1="11.396" y2="21.274" gradientUnits="userSpaceOnUse"><stop class="g829ebtyg"/><stop offset="1" class="mwpgiabok"/></linearGradient><linearGradient id="i0CeudL" x1="28.409" x2="28.409" y1="11.59" y2="21.468" gradientUnits="userSpaceOnUse"><stop class="xjer7pf-z"/><stop offset="1" class="iliezdb7y"/></linearGradient><linearGradient id="ir4JT9b" x1="27.002" x2="27.002" y1="7.058" y2="26.642" gradientUnits="userSpaceOnUse"><stop class="g829ebtyg"/><stop offset="1" class="mwpgiabok"/></linearGradient><radialGradient id="inTc0Ld" cx="0" cy="0" r="1" gradientTransform="rotate(113.233 6.068 13.954)scale(5.79574)" gradientUnits="userSpaceOnUse"><stop offset=".097" class="hrr8zy_rp"/><stop offset="1" class="h_z277b1n"/></radialGradient><radialGradient id="i8mztob" cx="0" cy="0" r="1" gradientTransform="rotate(145.706 8.275 10.725)scale(1.89104)" gradientUnits="userSpaceOnUse"><stop class="l60ra8jjy"/><stop offset="1" class="tgfv31bgu"/></radialGradient><radialGradient id="ikPacob" cx="0" cy="0" r="1" gradientTransform="matrix(-.27222 3.9757 -4.04797 -.27717 19.27 15.232)" gradientUnits="userSpaceOnUse"><stop offset=".594" class="ugdrqda4u"/><stop offset="1" class="apvdk2bdd"/></radialGradient><radialGradient id="iBGoYAR" cx="0" cy="0" r="1" gradientTransform="matrix(2.625 4.375 -15.32416 9.19451 11.498 6.966)" gradientUnits="userSpaceOnUse"><stop offset=".115" class="vof13p-wh"/><stop offset="1" class="jpvc-qw9x"/></radialGradient><radialGradient id="iT2n7Jb" cx="0" cy="0" r="1" gradientTransform="matrix(0 16.0625 -2.22649 0 18.404 11.653)" gradientUnits="userSpaceOnUse"><stop class="s6vdf8bty"/><stop offset="1" class="q_rhnrbqh"/></radialGradient><filter id="ioZU2Bb" width="3.788" height="10.979" x="22.35" y="10.39" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.396078 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17849"/></filter><filter id="ifZQyBd" width="3.188" height="10.129" x="22.876" y="10.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17849" stdDeviation=".2"/></filter><filter id="iBK81HA" width="6.964" height="19.804" x="23.251" y="5.724" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.396078 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17849"/></filter><filter id="ioUjhnc" width="6.363" height="18.804" x="23.82" y="6.408" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17849" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:speaker-high-volume" /></template>
<style>
.a6mjw833w {
  d: path("M2.466 10.644a1.6 1.6 0 0 1 1.6-1.6h4.338v13.89H4.066a1.6 1.6 0 0 1-1.6-1.6z");
}

.a7py1p9lm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-9px, 1.9px);
  d: path("M24.233 7.075c.872.435 5.032 3.018 5.032 8.752c0 5.91-4.354 8.316-5.064 8.751");
}

.apvdk2bdd {
  stop-color: var(--svg-color--b9b6bf, #B9B6BF);
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

.h2myt6bim {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M23.526 11.396a5.85 5.85 0 0 1 1.889 4.326c0 2.31-1.227 3.932-1.889 4.503");
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

.jpvc-qw9x {
  stop-color: var(--svg-color--c2bdc7, #C2BDC7);
  stop-opacity: 0;
}

.jsrupi03d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-9px, 1.9px);
  d: path("M23.3 11.59a5.85 5.85 0 0 1 1.889 4.325c0 2.312-1.227 3.933-1.889 4.504");
}

.kh2n5r75o {
  cx: 18.998px;
  cy: 15.989px;
  r: 3.219px;
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

.wk85oj57n {
  d: path("M19.263 6.865c0-1.62-1.724-2.658-3.156-1.9L8.404 9.044v13.89l7.699 4.099c1.432.762 3.16-.275 3.16-1.898z");
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

.zm7w0e9qx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M24.503 7.058c.871.436 5.03 3.019 5.03 8.753c0 5.91-4.352 8.316-5.062 8.751");
}

.zvz8qlarm {
  stop-color: var(--svg-color--d8d0e1, #D8D0E1);
  stop-opacity: 0;
}

</style>
