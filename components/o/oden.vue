<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path stroke="url(#iLjnIiY)" class="c_sdiqbtu"/><path fill="url(#iHpnE9M)" class="tw3ft2bed"/><path fill="url(#ijgkAue)" class="tw3ft2bed"/><g filter="url(#i30YCbd)"><path class="b1_ii-tan"/></g><g filter="url(#i5739Ud)"><path class="vs0l0ab0u"/></g><path fill="url(#iW8J9ae)" class="h209ndm-s"/><path fill="url(#iT2WMed)" class="h209ndm-s"/><g filter="url(#iFMBiZc)"><path class="r-_0fphwb"/></g><path fill="url(#idza3Rb)" class="ibnwr-a4g"/><path fill="url(#iw4D1sb)" class="ibnwr-a4g"/><path fill="url(#iFzxUOc)" class="ibnwr-a4g"/><path fill="url(#itgjAkb)" class="ibnwr-a4g"/><path fill="url(#iq9YqId)" class="ibnwr-a4g"/><path stroke="url(#iOuw9rb)" class="r7_soq3tc"/><g filter="url(#if670Ub)"><path class="w53fzabxz"/></g><g filter="url(#iCbsO1d)"><ellipse transform="rotate(-17.403 15 7.562)" class="oa11lc4_w"/></g><defs><radialGradient id="ijgkAue" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12502 5.0625 -5.06152 -1.1248 8 17.063)" gradientUnits="userSpaceOnUse"><stop class="fb3gzhbwb"/><stop offset="1" class="k4m4pjwvl"/></radialGradient><radialGradient id="iW8J9ae" cx="0" cy="0" r="1" gradientTransform="rotate(163.142 9.746 8.15)scale(10.7756)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="ufuwm4b_g"/><stop offset=".619" class="vm62vjlip"/><stop offset="1" class="q01ktnb8y"/></radialGradient><radialGradient id="iT2WMed" cx="0" cy="0" r="1" gradientTransform="rotate(106.243 -1.815 16.611)scale(8.2675)" gradientUnits="userSpaceOnUse"><stop class="zt5pkoenl"/><stop offset="1" class="rhtq_-bxf"/></radialGradient><radialGradient id="iw4D1sb" cx="0" cy="0" r="1" gradientTransform="rotate(73.034 1.813 27.866)scale(3.85529)" gradientUnits="userSpaceOnUse"><stop class="edc27guth"/><stop offset=".527" class="gf9lmdbmb"/><stop offset="1" class="bs7bktjrq"/></radialGradient><radialGradient id="iFzxUOc" cx="0" cy="0" r="1" gradientTransform="matrix(5.9375 1.75 -1.24769 4.23323 18.188 29.875)" gradientUnits="userSpaceOnUse"><stop class="s5kbvl20m"/><stop offset="1" class="v2lytndaz"/></radialGradient><radialGradient id="itgjAkb" cx="0" cy="0" r="1" gradientTransform="rotate(105.888 1.83 22.334)scale(4.48379 2.13703)" gradientUnits="userSpaceOnUse"><stop offset=".279" class="o6uwmmbch"/><stop offset="1" class="j62am9o9l"/></radialGradient><radialGradient id="iq9YqId" cx="0" cy="0" r="1" gradientTransform="matrix(-1.63504 6.4375 -3.7333 -.9482 15.697 24.25)" gradientUnits="userSpaceOnUse"><stop class="i_gc3hb1b"/><stop offset="1" class="mhcgwubsw"/></radialGradient><filter id="i30YCbd" width="12.181" height="12.183" x="3.975" y="3.976" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29625" stdDeviation=".75"/></filter><filter id="i5739Ud" width="9.401" height="8.794" x="8.813" y="9.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29625" stdDeviation=".5"/></filter><filter id="iFMBiZc" width="9.614" height="9.531" x="15.572" y="15.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29625" stdDeviation=".5"/></filter><filter id="if670Ub" width="13.125" height="6.888" x="3.625" y="2.924" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29625" stdDeviation="1"/></filter><filter id="iCbsO1d" width="5.044" height="5.402" x="12.478" y="4.861" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29625" stdDeviation=".75"/></filter><linearGradient id="iLjnIiY" x1="3" x2="5.375" y1="5.063" y2="2.688" gradientUnits="userSpaceOnUse"><stop class="tx1qb2bdk"/><stop offset=".5" class="dlqm9kz6y"/><stop offset=".994" class="jzv19zc5f"/></linearGradient><linearGradient id="iHpnE9M" x1="3.875" x2="16.25" y1="11.125" y2="6.125" gradientUnits="userSpaceOnUse"><stop offset=".016" class="y6h-x_bwt"/><stop offset=".183" class="l_e_-nbpc"/><stop offset=".585" class="o82jwz6ty"/></linearGradient><linearGradient id="idza3Rb" x1="20.063" x2="25.469" y1="19.688" y2="25.094" gradientUnits="userSpaceOnUse"><stop offset=".006" class="r2w136bzu"/><stop offset=".22" class="g2cxyjo3f"/><stop offset=".549" class="mjdb58jqy"/><stop offset=".871" class="du7disbya"/><stop offset="1" class="j5oc3hxqt"/></linearGradient><linearGradient id="iOuw9rb" x1="27.363" x2="25.238" y1="25.179" y2="27.305" gradientUnits="userSpaceOnUse"><stop class="bob_z0paz"/><stop offset=".251" class="bob_z0paz"/><stop offset=".574" class="e9cr-acoq"/><stop offset=".994" class="k7ymiw2cu"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:oden" /></template>
<style>
.b1_ii-tan {
  fill: var(--svg-color--4f3d81, #4F3D81);
  d: path("m5.55 8.196l1.302 4.862c.427 1.605 2.438 2.143 3.61.965l3.56-3.561c1.178-1.178.634-3.182-.964-3.61l-4.863-1.3C6.59 5.124 5.123 6.59 5.55 8.196");
}

.bob_z0paz {
  stop-color: var(--svg-color--ffd6a1, #FFD6A1);
}

.bs7bktjrq {
  stop-color: var(--svg-color--f5e2cd, #F5E2CD);
  stop-opacity: 0;
}

.c_sdiqbtu {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--3px, 3px);
  d: path("M28 27.94L3 3");
}

.dlqm9kz6y {
  stop-color: var(--svg-color--dba579, #DBA579);
}

.du7disbya {
  stop-color: var(--svg-color--f9d9cc, #F9D9CC);
}

.e9cr-acoq {
  stop-color: var(--svg-color--eaaa86, #EAAA86);
}

.edc27guth {
  stop-color: var(--svg-color--ffe, #FFE);
}

.fb3gzhbwb {
  stop-color: var(--svg-color--4c2e6e, #4C2E6E);
}

.ft5dv1b6b {
  fill: none;
}

.g2cxyjo3f {
  stop-color: var(--svg-color--dec6b5, #DEC6B5);
}

.gf9lmdbmb {
  stop-color: var(--svg-color--fceed2, #FCEED2);
}

.h209ndm-s {
  d: path("M16.78 23.63a6.85 6.85 0 1 0 0-13.7a6.85 6.85 0 0 0 0 13.7");
}

.i_gc3hb1b {
  stop-color: var(--svg-color--bc997f, #BC997F);
}

.ibnwr-a4g {
  d: path("m28.4 21.95l-6.45 6.45a3.664 3.664 0 0 1-5.18-5.18l6.45-6.45a3.664 3.664 0 0 1 5.18 5.18");
}

.j5oc3hxqt {
  stop-color: var(--svg-color--e2c4c2, #E2C4C2);
}

.j62am9o9l {
  stop-color: var(--svg-color--d798a3, #D798A3);
  stop-opacity: 0;
}

.jzv19zc5f {
  stop-color: var(--svg-color--ffd59e, #FFD59E);
}

.k4m4pjwvl {
  stop-color: var(--svg-color--503372, #503372);
  stop-opacity: 0;
}

.k7ymiw2cu {
  stop-color: var(--svg-color--c1706a, #C1706A);
}

.l_e_-nbpc {
  stop-color: var(--svg-color--422b69, #422B69);
}

.mhcgwubsw {
  stop-color: var(--svg-color--d5af96, #D5AF96);
  stop-opacity: 0;
}

.mjdb58jqy {
  stop-color: var(--svg-color--f5d3c9, #F5D3C9);
}

.o6uwmmbch {
  stop-color: var(--svg-color--d597a2, #D597A2);
}

.o82jwz6ty {
  stop-color: var(--svg-color--595295, #595295);
}

.oa11lc4_w {
  cx: 15px;
  cy: 7.562px;
  fill: var(--svg-color--6e65a3, #6E65A3);
  rx: 1px;
  ry: 1.219px;
}

.q01ktnb8y {
  stop-color: var(--svg-color--a06866, #A06866);
}

.r-_0fphwb {
  fill: var(--svg-color--c26454, #C26454);
  d: path("m16.573 22.993l6.45-6.45c1.477.3 1.696 3.363-.21 5.27c-3.047 3.046-6.047 2.562-6.24 1.18");
}

.r2w136bzu {
  stop-color: var(--svg-color--d1ae93, #D1AE93);
}

.r7_soq3tc {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--3px, 3px);
  d: path("m28 27.94l-3.4-3.39");
}

.rhtq_-bxf {
  stop-color: var(--svg-color--f1a1c4, #F1A1C4);
  stop-opacity: 0;
}

.s5kbvl20m {
  stop-color: var(--svg-color--d998b6, #D998B6);
}

.tw3ft2bed {
  d: path("m3.51 7.35l1.89 7.06c.62 2.33 3.54 3.11 5.24 1.4l5.17-5.17c1.71-1.71.92-4.62-1.4-5.24L7.35 3.51c-2.33-.62-4.46 1.51-3.84 3.84");
}

.tx1qb2bdk {
  stop-color: var(--svg-color--a96e55, #A96E55);
}

.ufuwm4b_g {
  stop-color: var(--svg-color--ffceb9, #FFCEB9);
}

.v2lytndaz {
  stop-color: var(--svg-color--dd9bb2, #DD9BB2);
  stop-opacity: 0;
}

.vm62vjlip {
  stop-color: var(--svg-color--dd9490, #DD9490);
}

.vs0l0ab0u {
  fill: var(--svg-color--30143d, #30143D);
  d: path("M15.875 10.125c-2.687 0-6.062 2.5-6.062 5.906c2.156.938 4.812 1.407 6.062 0c1.25-1.406 2.25-3.75 0-5.906");
}

.w53fzabxz {
  stroke: var(--svg-color--8c7fcf, #8C7FCF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M5.875 5.312c.042-.104.3-.25 1 0s5.375 1.605 7.625 2.25");
}

.y6h-x_bwt {
  stop-color: var(--svg-color--4a3e60, #4A3E60);
}

.zt5pkoenl {
  stop-color: var(--svg-color--c56e96, #C56E96);
}

</style>
