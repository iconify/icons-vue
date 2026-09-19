<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#iF8hr1Y)" class="lmh4whbrs"/><g filter="url(#iD69QPd)"><circle fill="url(#ig8fVZb)" class="lmh4whbrs"/><circle fill="url(#iEVSjtd)" class="lmh4whbrs"/></g><circle fill="url(#iDfclyq)" class="x5_7l-bbi"/><circle fill="url(#iWAy2He)" class="g4k3q7cmw"/><circle fill="url(#isY3BBc)" class="h2-o4in6u"/><path fill="url(#iKWHIUc)" clip-rule="evenodd" class="t3srrzbwo"/><path fill="url(#iEV94jb)" clip-rule="evenodd" class="t3srrzbwo"/><path fill="url(#iJvur2b)" clip-rule="evenodd" class="t6ruvjb9j"/><path fill="url(#iYsdLSb)" clip-rule="evenodd" class="jpaxrpb3b"/><path fill="url(#iSzhaOe)" clip-rule="evenodd" class="jpaxrpb3b"/><path fill="url(#i4hXr3d)" clip-rule="evenodd" class="jpaxrpb3b"/><g filter="url(#i0JCP2d)"><path stroke="url(#iioQCPc)" class="t4ha9ieeq"/></g><g filter="url(#itNPPSc)"><ellipse fill="url(#iZwklLb)" class="nwlvur5cs"/><ellipse fill="url(#iPDsGQb)" class="nwlvur5cs"/><path stroke="url(#iSCMR3d)" class="buq9e1bil"/></g><g filter="url(#i2r1oZb)"><circle fill="url(#in2lu1d)" class="g4k3q7cmw"/><circle stroke="url(#iIXbczb)" class="xrwbo5xlm"/></g><circle fill="url(#isN18QL)" class="h2-o4in6u"/><g filter="url(#inzdZmb)"><circle fill="url(#iROX1gd)" class="h2-o4in6u"/><circle fill="url(#i6I1WIc)" class="h2-o4in6u"/><circle stroke="url(#i85kn2d)" class="c6dds4bjf"/></g><circle fill="url(#iaVFJUr)" class="az0fwjbyp"/><circle fill="url(#ie3daVm)" class="az0fwjbyp"/><path fill="url(#iQsdB1b)" clip-rule="evenodd" class="t6ruvjb9j"/><path fill="url(#ivdK03c)" clip-rule="evenodd" class="t6ruvjb9j"/><path fill="url(#iJMGzEc)" clip-rule="evenodd" class="t6ruvjb9j"/><path fill="url(#inQ647V)" clip-rule="evenodd" class="t6ruvjb9j"/><path fill="url(#iNdIojC)" class="tzj2ytblh"/><defs><radialGradient id="iF8hr1Y" cx="0" cy="0" r="1" gradientTransform="rotate(133.363 8.703 9.384)scale(24.7588)" gradientUnits="userSpaceOnUse"><stop class="ifsoepbvs"/><stop offset="1" class="gap-yf33v"/></radialGradient><radialGradient id="ig8fVZb" cx="0" cy="0" r="1" gradientTransform="rotate(119.055 6.106 6.092)scale(18.53 14.6474)" gradientUnits="userSpaceOnUse"><stop class="ta6vrob-a"/><stop offset="1" class="euky2obga"/></radialGradient><radialGradient id="iEVSjtd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5186 -5.68059 8.7298 -2.33375 13.16 30.372)" gradientUnits="userSpaceOnUse"><stop class="c_0snyw8y"/><stop offset="1" class="r2o6f5vpf"/></radialGradient><radialGradient id="iKWHIUc" cx="0" cy="0" r="1" gradientTransform="matrix(5.00567 .33575 -.2758 4.1118 5.623 25.535)" gradientUnits="userSpaceOnUse"><stop class="t73pr8mpf"/><stop offset="1" class="ljk1kybyv"/></radialGradient><radialGradient id="iEV94jb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.4688 -2.6094 2.50068 -2.36594 7.875 26.089)" gradientUnits="userSpaceOnUse"><stop offset=".897" class="w90_s-_ul"/><stop offset=".974" class="jvx-99_5z"/></radialGradient><radialGradient id="iYsdLSb" cx="0" cy="0" r="1" gradientTransform="rotate(122.598 9.967 12.565)scale(14.0954 17.5907)" gradientUnits="userSpaceOnUse"><stop class="vm_colbur"/><stop offset="1" class="uql5ndbez"/></radialGradient><radialGradient id="iSzhaOe" cx="0" cy="0" r="1" gradientTransform="rotate(120.548 12.641 11.245)scale(26.5615 33.5752)" gradientUnits="userSpaceOnUse"><stop offset=".666" class="fz8x5pw3g"/><stop offset="1" class="qjjl1fbhp"/></radialGradient><radialGradient id="i4hXr3d" cx="0" cy="0" r="1" gradientTransform="matrix(9.49988 19.80205 -20.52668 9.84751 14 10.198)" gradientUnits="userSpaceOnUse"><stop offset=".837" class="sca3_mu8v"/><stop offset="1" class="jms9iib4t"/></radialGradient><radialGradient id="iZwklLb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.00536 0 0 -3.27072 17.281 5.5)" gradientUnits="userSpaceOnUse"><stop offset=".437" class="piy3tic3g"/><stop offset="1" class="r38asee8x"/></radialGradient><radialGradient id="iPDsGQb" cx="0" cy="0" r="1" gradientTransform="matrix(2.75536 0 0 2.97042 14.969 5.5)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="od4hrnb8k"/><stop offset="1" class="um7ihac7p"/></radialGradient><radialGradient id="in2lu1d" cx="0" cy="0" r="1" gradientTransform="matrix(5.625 -4.39546 1.44644 1.85106 20 13.396)" gradientUnits="userSpaceOnUse"><stop offset=".2" class="v30cqfxzy"/><stop offset="1" class="g1o3qybrr"/></radialGradient><radialGradient id="iROX1gd" cx="0" cy="0" r="1" gradientTransform="rotate(135 4.38 13.926)scale(3.93533 4.69999)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="kj-88vbdi"/><stop offset="1" class="hqgudgt7g"/></radialGradient><radialGradient id="i6I1WIc" cx="0" cy="0" r="1" gradientTransform="matrix(3.28124 -3.12501 2.54646 2.67376 15.094 23.01)" gradientUnits="userSpaceOnUse"><stop offset=".837" class="ey0lgwv1v"/><stop offset="1" class="rz7k2sb_t"/></radialGradient><radialGradient id="iaVFJUr" cx="0" cy="0" r="1" gradientTransform="rotate(118.867 2.135 8.518)scale(5.56671)" gradientUnits="userSpaceOnUse"><stop class="pec5941xa"/><stop offset="1" class="k-e7lvbdw"/></radialGradient><radialGradient id="ie3daVm" cx="0" cy="0" r="1" gradientTransform="matrix(-3.65738 -.7461 .79628 -3.90337 9.5 12.5)" gradientUnits="userSpaceOnUse"><stop offset=".828" class="uom2sabkf"/><stop offset="1" class="s38f0kzba"/></radialGradient><radialGradient id="iJMGzEc" cx="0" cy="0" r="1" gradientTransform="matrix(-.87214 -5.64197 4.67917 -.72331 27.35 26.823)" gradientUnits="userSpaceOnUse"><stop offset=".85" class="d1gfmbu2u"/><stop offset="1" class="x5cl77b6u"/></radialGradient><radialGradient id="inQ647V" cx="0" cy="0" r="1" gradientTransform="rotate(122.849 7.272 18.953)scale(4.72413 4.02056)" gradientUnits="userSpaceOnUse"><stop offset=".718" class="juqbnk4bv"/><stop offset=".952" class="rktfksz4s"/></radialGradient><linearGradient id="iDfclyq" x1="16.5" x2="14.5" y1="4.5" y2="6.5" gradientUnits="userSpaceOnUse"><stop class="s334l8uyu"/><stop offset="1" class="nec_isxbo"/></linearGradient><linearGradient id="iWAy2He" x1="24.167" x2="20.833" y1="9.833" y2="13.167" gradientUnits="userSpaceOnUse"><stop class="s334l8uyu"/><stop offset="1" class="nec_isxbo"/></linearGradient><linearGradient id="isY3BBc" x1="18.167" x2="14.833" y1="19.833" y2="23.167" gradientUnits="userSpaceOnUse"><stop class="s334l8uyu"/><stop offset="1" class="nec_isxbo"/></linearGradient><linearGradient id="iJvur2b" x1="29.833" x2="25.167" y1="22.167" y2="26.833" gradientUnits="userSpaceOnUse"><stop class="tfh0wfbse"/><stop offset="1" class="oc3sqsbox"/></linearGradient><linearGradient id="iioQCPc" x1="27.982" x2="24.639" y1="20.656" y2="26.313" gradientUnits="userSpaceOnUse"><stop class="eobh93bgv"/><stop offset="1" class="azg09_fix"/></linearGradient><linearGradient id="iSCMR3d" x1="17.724" x2="16.544" y1="5.17" y2="5.17" gradientUnits="userSpaceOnUse"><stop class="tneowg16w"/><stop offset="1" class="btjyt1bqw"/></linearGradient><linearGradient id="iIXbczb" x1="20.577" x2="23.646" y1="9" y2="14" gradientUnits="userSpaceOnUse"><stop class="vm_colbur"/><stop offset=".492" class="juvvm2boo"/><stop offset="1" class="vm_colbur"/></linearGradient><linearGradient id="isN18QL" x1="18.167" x2="14.833" y1="19.833" y2="23.167" gradientUnits="userSpaceOnUse"><stop class="odmjt405d"/><stop offset="1" class="qf2998b3n"/></linearGradient><linearGradient id="i85kn2d" x1="18.25" x2="14.369" y1="19.32" y2="23.257" gradientUnits="userSpaceOnUse"><stop class="qkzvsmbnh"/><stop offset="1" class="mj21lz_nw"/></linearGradient><linearGradient id="iQsdB1b" x1="29.833" x2="25.167" y1="22.167" y2="26.833" gradientUnits="userSpaceOnUse"><stop class="odmjt405d"/><stop offset="1" class="qf2998b3n"/></linearGradient><linearGradient id="ivdK03c" x1="26.059" x2="25.915" y1="21.826" y2="25.986" gradientUnits="userSpaceOnUse"><stop class="exwjse53p"/><stop offset="1" class="hbsahlgvg"/></linearGradient><linearGradient id="iNdIojC" x1="12.61" x2="7.633" y1="10.904" y2="13.038" gradientUnits="userSpaceOnUse"><stop class="q_jz696ui"/><stop offset="1" class="ok1xare_g"/></linearGradient><filter id="iD69QPd" width="28.2" height="28" x="2" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.447059 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13946"/></filter><filter id="i0JCP2d" width="5.707" height="6.614" x="23.55" y="20.55" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13946" stdDeviation=".15"/></filter><filter id="itNPPSc" width="4.148" height="3.7" x="13.926" y="3.65" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13946" stdDeviation=".1"/></filter><filter id="i2r1oZb" width="6" height="6" x="19.5" y="8.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13946" stdDeviation=".15"/></filter><filter id="inzdZmb" width="5.7" height="5.7" x="13.65" y="18.65" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13946" stdDeviation=".1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:waxing-gibbous-moon" /></template>
<style>
.az0fwjbyp {
  cx: 9.5px;
  cy: 12.5px;
  r: 3.5px;
}

.azg09_fix {
  stop-color: var(--svg-color--ffdc75, #FFDC75);
}

.btjyt1bqw {
  stop-color: var(--svg-color--ffdd7b, #FFDD7B);
}

.buq9e1bil {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M16 7.075c.983 0 1.8-.696 1.8-1.575c0-.88-.817-1.575-1.8-1.575s-1.8.696-1.8 1.575c0 .88.817 1.575 1.8 1.575Z");
}

.c_0snyw8y {
  stop-color: var(--svg-color--6a4d88, #6A4D88);
}

.c6dds4bjf {
  cx: 16.5px;
  cy: 21.5px;
  r: 2.575px;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
}

.d1gfmbu2u {
  stop-color: var(--svg-color--dfa14c, #DFA14C);
  stop-opacity: 0;
}

.eobh93bgv {
  stop-color: var(--svg-color--f5bd64, #F5BD64);
}

.euky2obga {
  stop-color: var(--svg-color--473858, #473858);
}

.exwjse53p {
  stop-color: var(--svg-color--ffd36a, #FFD36A);
}

.ey0lgwv1v {
  stop-color: var(--svg-color--e3915b, #E3915B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fz8x5pw3g {
  stop-color: var(--svg-color--fa9f56, #FA9F56);
  stop-opacity: 0;
}

.g1o3qybrr {
  stop-color: var(--svg-color--ffd975, #FFD975);
}

.g4k3q7cmw {
  cx: 22.5px;
  cy: 11.5px;
  r: 2.5px;
}

.gap-yf33v {
  stop-color: var(--svg-color--f7ca32, #F7CA32);
}

.h2-o4in6u {
  cx: 16.5px;
  cy: 21.5px;
  r: 2.5px;
}

.hbsahlgvg {
  stop-color: var(--svg-color--efb872, #EFB872);
}

.hqgudgt7g {
  stop-color: var(--svg-color--ffd87e, #FFD87E);
}

.ifsoepbvs {
  stop-color: var(--svg-color--feed6e, #FEED6E);
}

.jms9iib4t {
  stop-color: var(--svg-color--d7908f, #D7908F);
}

.jpaxrpb3b {
  fill-rule: evenodd;
  d: path("M15.681 29.996Q15.84 30 16 30c7.732 0 14-6.268 14-14S23.732 2 16 2q-.16 0-.32.004C11.606 5.304 9 10.348 9 16s2.605 10.697 6.681 13.996");
}

.juqbnk4bv {
  stop-color: var(--svg-color--ffe38a, #FFE38A);
  stop-opacity: 0;
}

.juvvm2boo {
  stop-color: var(--svg-color--fff9ac, #FFF9AC);
  stop-opacity: 0;
}

.jvx-99_5z {
  stop-color: var(--svg-color--39264b, #39264B);
}

.k-e7lvbdw {
  stop-color: var(--svg-color--654b7f, #654B7F);
}

.kj-88vbdi {
  stop-color: var(--svg-color--f29e64, #F29E64);
}

.ljk1kybyv {
  stop-color: var(--svg-color--5d4375, #5D4375);
}

.lmh4whbrs {
  cx: 16px;
  cy: 16px;
  r: 14px;
}

.mj21lz_nw {
  stop-color: var(--svg-color--ffb053, #FFB053);
}

.nec_isxbo {
  stop-color: var(--svg-color--ffef71, #FFEF71);
}

.nwlvur5cs {
  cx: 16px;
  cy: 5.5px;
  rx: 1.724px;
  ry: 1.5px;
}

.oc3sqsbox {
  stop-color: var(--svg-color--fff073, #FFF073);
}

.od4hrnb8k {
  stop-color: var(--svg-color--cd9e56, #CD9E56);
  stop-opacity: 0;
}

.odmjt405d {
  stop-color: var(--svg-color--0f0f0f, #0F0F0F);
}

.ok1xare_g {
  stop-color: var(--svg-color--e1aa4e, #E1AA4E);
}

.pec5941xa {
  stop-color: var(--svg-color--664783, #664783);
}

.piy3tic3g {
  stop-color: var(--svg-color--f3bb63, #F3BB63);
}

.q_jz696ui {
  stop-color: var(--svg-color--c29346, #C29346);
}

.qf2998b3n {
  stop-color: var(--svg-color--704e8d, #704E8D);
}

.qjjl1fbhp {
  stop-color: var(--svg-color--ee8965, #EE8965);
}

.qkzvsmbnh {
  stop-color: var(--svg-color--fbac52, #FBAC52);
}

.r2o6f5vpf {
  stop-color: var(--svg-color--6a4d88, #6A4D88);
  stop-opacity: 0;
}

.r38asee8x {
  stop-color: var(--svg-color--fff3a5, #FFF3A5);
}

.rktfksz4s {
  stop-color: var(--svg-color--ffe38a, #FFE38A);
}

.rz7k2sb_t {
  stop-color: var(--svg-color--e3915b, #E3915B);
}

.s334l8uyu {
  stop-color: var(--svg-color--f5c224, #F5C224);
}

.s38f0kzba {
  stop-color: var(--svg-color--8b6ba9, #8B6BA9);
}

.sca3_mu8v {
  stop-color: var(--svg-color--d7908f, #D7908F);
  stop-opacity: 0;
}

.t3srrzbwo {
  fill-rule: evenodd;
  d: path("M10.189 28.74a14.05 14.05 0 0 1-5.439-4.405a3.5 3.5 0 1 1 5.439 4.406");
}

.t4ha9ieeq {
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M28.764 21.234c-.887 2.16-2.255 3.963-4.032 5.422c-.548-.618-.732-1.265-.732-2.156a3.5 3.5 0 0 1 3.5-3.5c.52 0 .82.032 1.264.234Z");
}

.t6ruvjb9j {
  fill-rule: evenodd;
  d: path("M28.955 21.316a14.04 14.04 0 0 1-4.073 5.507a3.5 3.5 0 0 1 4.074-5.507");
}

.t73pr8mpf {
  stop-color: var(--svg-color--524560, #524560);
}

.ta6vrob-a {
  stop-color: var(--svg-color--7c619b, #7C619B);
}

.tfh0wfbse {
  stop-color: var(--svg-color--f6c72d, #F6C72D);
}

.tneowg16w {
  stop-color: var(--svg-color--fdc36b, #FDC36B);
}

.tzj2ytblh {
  d: path("M9 15.965c1.078-.798 2.188-2.298 2.188-3.954c0-.849-.282-2.094-.821-2.903A3.502 3.502 0 0 1 9 15.965");
}

.um7ihac7p {
  stop-color: var(--svg-color--cd9e56, #CD9E56);
}

.uom2sabkf {
  stop-color: var(--svg-color--8b6ba9, #8B6BA9);
  stop-opacity: 0;
}

.uql5ndbez {
  stop-color: var(--svg-color--ffc64f, #FFC64F);
}

.v30cqfxzy {
  stop-color: var(--svg-color--fff8b1, #FFF8B1);
}

.vm_colbur {
  stop-color: var(--svg-color--fff9ac, #FFF9AC);
}

.w90_s-_ul {
  stop-color: var(--svg-color--39264b, #39264B);
  stop-opacity: 0;
}

.x5_7l-bbi {
  cx: 15.5px;
  cy: 5.5px;
  r: 1.5px;
}

.x5cl77b6u {
  stop-color: var(--svg-color--c28255, #C28255);
}

.xrwbo5xlm {
  cx: 22.5px;
  cy: 11.5px;
  r: 2.6px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

</style>
