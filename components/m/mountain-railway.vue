<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iRNtX3b)" class="pu1xkgg7h"/><path fill="url(#i1h7SFd)" class="pu1xkgg7h"/><path fill="url(#iSOMuLd)" class="pu1xkgg7h"/><path fill="url(#iLeUbQe)" class="pu1xkgg7h"/><path fill="url(#iq73qNb)" class="pu1xkgg7h"/><path fill="url(#ibozwol)" class="p01ydubiz"/><path fill="url(#iTxsiZW)" class="p01ydubiz"/><path fill="url(#iNENzEc)" class="p01ydubiz"/><path fill="url(#iBT6QMd)" class="p01ydubiz"/><g filter="url(#i8GjE8d)"><path fill="url(#iAVDOLq)" class="nmxrss9-h"/><path fill="url(#izhwq5B)" class="nmxrss9-h"/></g><g filter="url(#iUEhaub)"><path class="zw-idtb2u"/><path fill="url(#iJDBVvb)" class="dv5l5ck3r"/></g><g filter="url(#ikPhxxE)"><path class="kk30tdbng"/><path fill="url(#ikenzRd)" class="lzsmzbbjv"/></g><g filter="url(#iXvksfe)"><path clip-rule="evenodd" class="w9zwz1bhh"/></g><g filter="url(#iEmjMNc)"><path clip-rule="evenodd" class="u83d68b5l"/></g><g filter="url(#irB0Lje)"><path class="j39mn5_oc"/><path fill="url(#izi3MHb)" class="e0136xbnl"/></g><g filter="url(#iKAmt3b)"><path fill="url(#i6abgsc)" class="r0ek86b5r"/></g><g filter="url(#ieb9lRd)"><path fill="url(#izLLOMd)" class="d-727zbxk"/></g><path fill="url(#iKqspqW)" class="lo069sbjc"/><path fill="url(#iCswQ9b)" class="lo069sbjc"/><g filter="url(#i5SjTmd)"><path fill="url(#iDptK0c)" class="jsknd-9ps"/></g><g filter="url(#i0UDr4B)"><path fill="url(#ixYoPme)" class="k9oqu0k6w"/><path fill="url(#i5ooWQb)" class="k9oqu0k6w"/></g><g filter="url(#iHal9uc)"><path fill="url(#iA43mBe)" class="h4rvlqbxj"/><path fill="url(#i3NyVSb)" class="h4rvlqbxj"/></g><g filter="url(#iMwuT8c)"><path fill="url(#iZoK9jb)" class="rsubfglyb"/><path fill="url(#igZdsNb)" class="rsubfglyb"/></g><path fill="url(#izHAK4c)" class="rsubfglyb"/><path fill="url(#inWSKKc)" class="g719dsbdu"/><path fill="url(#iK5fz2c)" class="g719dsbdu"/><g filter="url(#iu3mPVb)"><path stroke="url(#iy7QTOz)" class="epmqtcc8c"/></g><defs><linearGradient id="iRNtX3b" x1="5.797" x2="20.125" y1="23.26" y2="7.247" gradientUnits="userSpaceOnUse"><stop class="dwq3tubji"/><stop offset="1" class="frujk3b3u"/></linearGradient><linearGradient id="i1h7SFd" x1="19.628" x2="18.592" y1="7.322" y2="8.468" gradientUnits="userSpaceOnUse"><stop class="lpje_rbqp"/><stop offset="1" class="u61-y5n5k"/></linearGradient><linearGradient id="iLeUbQe" x1="8.682" x2="9.333" y1="13.184" y2="13.742" gradientUnits="userSpaceOnUse"><stop class="u10m2k0br"/><stop offset="1" class="dr4_27-ne"/></linearGradient><linearGradient id="iq73qNb" x1="16.918" x2="16.381" y1="11.805" y2="11.369" gradientUnits="userSpaceOnUse"><stop offset=".099" class="fpeqe_vgc"/><stop offset="1" class="vje63rbxx"/></linearGradient><linearGradient id="ibozwol" x1="17.366" x2="27.217" y1="12.571" y2="19.62" gradientUnits="userSpaceOnUse"><stop class="xldv61laq"/><stop offset="1" class="qz4n55brk"/></linearGradient><linearGradient id="iTxsiZW" x1="18.269" x2="18.269" y1="32.183" y2="16.547" gradientUnits="userSpaceOnUse"><stop class="jikts1b4g"/><stop offset="1" class="ekh3dhb9m"/></linearGradient><linearGradient id="iNENzEc" x1="28.866" x2="28.147" y1="4.662" y2="5.335" gradientUnits="userSpaceOnUse"><stop class="m5rm2tbtw"/><stop offset="1" class="mt3rq8yak"/></linearGradient><linearGradient id="iBT6QMd" x1="16.242" x2="17.506" y1="11.461" y2="12.484" gradientUnits="userSpaceOnUse"><stop offset=".186" class="chfxlxqbq"/><stop offset="1" class="g3yqjebac"/></linearGradient><linearGradient id="iAVDOLq" x1="16.868" x2="7.514" y1="24.591" y2="33.449" gradientUnits="userSpaceOnUse"><stop offset=".203" class="bbprzibqr"/><stop offset="1" class="e7ryisrkg"/></linearGradient><linearGradient id="izhwq5B" x1="30.109" x2="17.546" y1="28.568" y2="28.568" gradientUnits="userSpaceOnUse"><stop class="x85xq1byi"/><stop offset="1" class="u77oyxbpm"/></linearGradient><linearGradient id="iJDBVvb" x1="13.495" x2="13.495" y1="27.734" y2="28.296" gradientUnits="userSpaceOnUse"><stop class="plb8xe79g"/><stop offset="1" class="wjfkidcqc"/></linearGradient><linearGradient id="ikenzRd" x1="19.015" x2="19.015" y1="27.734" y2="28.296" gradientUnits="userSpaceOnUse"><stop class="ck_stacld"/><stop offset="1" class="lzij--6yg"/></linearGradient><linearGradient id="izi3MHb" x1="28.515" x2="28.515" y1="27.734" y2="28.296" gradientUnits="userSpaceOnUse"><stop class="jqa2sup6z"/><stop offset="1" class="aefm-rbzj"/></linearGradient><linearGradient id="izLLOMd" x1="11.01" x2="30.01" y1="25.499" y2="25.499" gradientUnits="userSpaceOnUse"><stop class="qo2stacgc"/><stop offset="1" class="g-ycbozlq"/></linearGradient><linearGradient id="iKqspqW" x1="30.015" x2="11.015" y1="17.074" y2="17.074" gradientUnits="userSpaceOnUse"><stop class="cqxdq9bas"/><stop offset="1" class="hfv13198d"/></linearGradient><linearGradient id="iCswQ9b" x1="10.914" x2="11.877" y1="23.001" y2="23.001" gradientUnits="userSpaceOnUse"><stop class="v2i60qbat"/><stop offset="1" class="gegg5367w"/></linearGradient><linearGradient id="iDptK0c" x1="11.871" x2="14.388" y1="19.302" y2="19.302" gradientUnits="userSpaceOnUse"><stop class="cj3bmuw2w"/><stop offset="1" class="fl1oe0bey"/></linearGradient><linearGradient id="ixYoPme" x1="18.673" x2="18.673" y1="14.001" y2="22.001" gradientUnits="userSpaceOnUse"><stop class="hxh6qpdtb"/><stop offset="1" class="mw9z3tb4v"/></linearGradient><linearGradient id="iA43mBe" x1="24.673" x2="24.673" y1="14.001" y2="22.001" gradientUnits="userSpaceOnUse"><stop class="hxh6qpdtb"/><stop offset="1" class="mw9z3tb4v"/></linearGradient><linearGradient id="iZoK9jb" x1="29.341" x2="29.341" y1="14.001" y2="22.001" gradientUnits="userSpaceOnUse"><stop class="hxh6qpdtb"/><stop offset="1" class="mw9z3tb4v"/></linearGradient><linearGradient id="iy7QTOz" x1="12.166" x2="24.751" y1="12.724" y2="12.724" gradientUnits="userSpaceOnUse"><stop class="hu4igh56t"/><stop offset="1" class="kxo43lbtu"/></linearGradient><filter id="i8GjE8d" width="25.656" height="13.349" x="4.778" y="17.398" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9634" stdDeviation=".75"/></filter><filter id="iUEhaub" width="4.2" height="4.2" x="12.495" y="25.801" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.309804 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9634"/></filter><filter id="ikPhxxE" width="4.2" height="4.2" x="18.015" y="25.801" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9634"/></filter><filter id="iXvksfe" width="3.113" height="1.5" x="13.632" y="27.305" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9634" stdDeviation=".125"/></filter><filter id="iEmjMNc" width="2.068" height="1.3" x="17.946" y="27.405" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9634" stdDeviation=".075"/></filter><filter id="irB0Lje" width="2.2" height="4.2" x="28.015" y="25.801" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.243137 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9634"/></filter><filter id="iKAmt3b" width="6" height="1" x="14.015" y="27.501" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.341176 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9634"/></filter><filter id="ieb9lRd" width="19.6" height="17.586" x="11.015" y="10.415" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6" dy="-.6"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9634"/></filter><filter id="i5SjTmd" width="3.01" height="9" x="11.015" y="14.001" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.517647 0 0 0 0 0.85098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9634"/></filter><filter id="i0UDr4B" width="4.49" height="8.5" x="15.515" y="14.001" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.552941 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9634"/></filter><filter id="iHal9uc" width="4.49" height="8.5" x="21.515" y="14.001" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.552941 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9634"/></filter><filter id="iMwuT8c" width="1.99" height="8.5" x="28.015" y="14.001" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.552941 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9634"/></filter><filter id="iu3mPVb" width="18.202" height="1.6" x="11.071" y="10.924" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_9634" stdDeviation=".3"/></filter><radialGradient id="iSOMuLd" cx="0" cy="0" r="1" gradientTransform="matrix(2.2334 10.05033 -4.10412 .91203 11.986 18.674)" gradientUnits="userSpaceOnUse"><stop offset=".284" class="dmyoyypni"/><stop offset="1" class="m3dyjdrly"/></radialGradient><radialGradient id="i6abgsc" cx="0" cy="0" r="1" gradientTransform="matrix(5.18722 0 0 .60043 14.823 27.999)" gradientUnits="userSpaceOnUse"><stop class="azaxdfjjn"/><stop offset="1" class="tnz914bvq"/></radialGradient><radialGradient id="i5ooWQb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.0868 1.69368 0 16.316 22.89)" gradientUnits="userSpaceOnUse"><stop class="vk3b3fbes"/><stop offset="1" class="lgq1_vlkf"/></radialGradient><radialGradient id="i3NyVSb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.0868 1.69368 0 22.316 22.89)" gradientUnits="userSpaceOnUse"><stop class="vk3b3fbes"/><stop offset="1" class="lgq1_vlkf"/></radialGradient><radialGradient id="igZdsNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.0868 .84472 0 28.165 22.89)" gradientUnits="userSpaceOnUse"><stop class="vk3b3fbes"/><stop offset="1" class="lgq1_vlkf"/></radialGradient><radialGradient id="izHAK4c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.25738 0 0 -6.1856 30.267 18.15)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="uggervb6g"/><stop offset="1" class="o9p-epyjf"/></radialGradient><radialGradient id="inWSKKc" cx="0" cy="0" r="1" gradientTransform="matrix(1.56502 0 0 1.02944 12.005 24.5)" gradientUnits="userSpaceOnUse"><stop class="haqx21bae"/><stop offset="1" class="govzgkrkn"/></radialGradient><radialGradient id="iK5fz2c" cx="0" cy="0" r="1" gradientTransform="matrix(2.13501 0 0 1.1707 11.87 24.5)" gradientUnits="userSpaceOnUse"><stop offset=".717" class="q2yladygd"/><stop offset="1" class="acg45cjqz"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:mountain-railway" /></template>
<style>
.acg45cjqz {
  stop-color: var(--svg-color--d4221b, #D4221B);
}

.aefm-rbzj {
  stop-color: var(--svg-color--483342, #483342);
  stop-opacity: 0;
}

.azaxdfjjn {
  stop-color: var(--svg-color--cfb6d9, #CFB6D9);
}

.bbprzibqr {
  stop-color: var(--svg-color--2e935a, #2E935A);
}

.chfxlxqbq {
  stop-color: var(--svg-color--56b878, #56B878);
}

.cj3bmuw2w {
  stop-color: var(--svg-color--4acdfe, #4ACDFE);
}

.ck_stacld {
  stop-color: var(--svg-color--4d3a4c, #4D3A4C);
}

.cqxdq9bas {
  stop-color: var(--svg-color--cbbed4, #CBBED4);
}

.d-727zbxk {
  d: path("M11.015 12.015a1 1 0 0 1 1-1h18V28h-18c-.55 0-1-.45-1-1z");
}

.dmyoyypni {
  stop-color: var(--svg-color--205845, #205845);
}

.dr4_27-ne {
  stop-color: var(--svg-color--407561, #407561);
  stop-opacity: 0;
}

.dv5l5ck3r {
  d: path("M14.495 30a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.dwq3tubji {
  stop-color: var(--svg-color--37806e, #37806E);
}

.e0136xbnl {
  d: path("M30.015 26c-1.1 0-2 .9-2 2s.9 2 2 2z");
}

.e7ryisrkg {
  stop-color: var(--svg-color--2e935a, #2E935A);
  stop-opacity: 0;
}

.ekh3dhb9m {
  stop-color: var(--svg-color--39be73, #39BE73);
  stop-opacity: 0;
}

.epmqtcc8c {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M11.871 11.724h16.602");
}

.fl1oe0bey {
  stop-color: var(--svg-color--38a9d9, #38A9D9);
}

.fpeqe_vgc {
  stop-color: var(--svg-color--1d543f, #1D543F);
}

.frujk3b3u {
  stop-color: var(--svg-color--398869, #398869);
}

.ft5dv1b6b {
  fill: none;
}

.g-ycbozlq {
  stop-color: var(--svg-color--ff8643, #FF8643);
}

.g3yqjebac {
  stop-color: var(--svg-color--56b878, #56B878);
  stop-opacity: 0;
}

.g719dsbdu {
  d: path("M13.505 25h-1c-.28 0-.5-.22-.5-.5s.22-.5.5-.5h1c.28 0 .5.22.5.5s-.23.5-.5.5");
}

.gegg5367w {
  stop-color: var(--svg-color--8b8692, #8B8692);
  stop-opacity: 0;
}

.govzgkrkn {
  stop-color: var(--svg-color--f6483a, #F6483A);
}

.h4rvlqbxj {
  d: path("M24.995 22h-1.98c-.55 0-1-.45-1-1l.01-6c0-.55.45-1 1-1h1.98c.55 0 1 .45 1 1l-.01 6c0 .55-.45 1-1 1");
}

.haqx21bae {
  stop-color: var(--svg-color--ff8437, #FF8437);
}

.hfv13198d {
  stop-color: var(--svg-color--dfd4e6, #DFD4E6);
}

.hu4igh56t {
  stop-color: var(--svg-color--fed956, #FED956);
}

.hxh6qpdtb {
  stop-color: var(--svg-color--40c1ff, #40C1FF);
}

.j39mn5_oc {
  fill: var(--svg-color--5f5562, #5F5562);
  d: path("M30.015 26c-1.1 0-2 .9-2 2s.9 2 2 2z");
}

.jikts1b4g {
  stop-color: var(--svg-color--39be73, #39BE73);
}

.jqa2sup6z {
  stop-color: var(--svg-color--483342, #483342);
}

.jsknd-9ps {
  d: path("M13.015 22h-2l.01-8h2c.55 0 1 .45 1 1l-.01 6c0 .55-.45 1-1 1");
}

.k9oqu0k6w {
  d: path("M18.995 22h-1.98c-.55 0-1-.45-1-1l.01-6c0-.55.45-1 1-1h1.98c.55 0 1 .45 1 1l-.01 6c0 .55-.45 1-1 1");
}

.kk30tdbng {
  fill: var(--svg-color--6e6371, #6E6371);
  d: path("M20.015 30a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.kxo43lbtu {
  stop-color: var(--svg-color--fed956, #FED956);
  stop-opacity: 0;
}

.lgq1_vlkf {
  stop-color: var(--svg-color--5affff, #5AFFFF);
  stop-opacity: 0;
}

.lo069sbjc {
  d: path("M30.015 13h-19v10h19z");
}

.lpje_rbqp {
  stop-color: var(--svg-color--59a083, #59A083);
}

.lzij--6yg {
  stop-color: var(--svg-color--4d3a4c, #4D3A4C);
  stop-opacity: 0;
}

.lzsmzbbjv {
  d: path("M20.015 30a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.m3dyjdrly {
  stop-color: var(--svg-color--205845, #205845);
  stop-opacity: 0;
}

.m5rm2tbtw {
  stop-color: var(--svg-color--66f9a1, #66F9A1);
}

.mt3rq8yak {
  stop-color: var(--svg-color--66f9a1, #66F9A1);
  stop-opacity: 0;
}

.mw9z3tb4v {
  stop-color: var(--svg-color--4ff4ff, #4FF4FF);
}

.nmxrss9-h {
  d: path("m6.783 25.196l4.708-6.299h17.443v10.35H8.813a2.534 2.534 0 0 1-2.03-4.05");
}

.o9p-epyjf {
  stop-color: var(--svg-color--4dd8ff, #4DD8FF);
  stop-opacity: 0;
}

.p01ydubiz {
  d: path("m30.005 5.87l-2.9-3.16c-.91-.99-2.5-.94-3.34.11L1.995 30h28.01z");
}

.plb8xe79g {
  stop-color: var(--svg-color--534350, #534350);
}

.pu1xkgg7h {
  d: path("M30.005 18.32L17.895 6.21a2.47 2.47 0 0 0-3.62.14L2.285 20.34c-.18.21-.28.48-.28.76l-.01 8.76c0 .08.06.14.14.14h27.87z");
}

.q2yladygd {
  stop-color: var(--svg-color--d4221b, #D4221B);
  stop-opacity: 0;
}

.qo2stacgc {
  stop-color: var(--svg-color--fecd5b, #FECD5B);
}

.qz4n55brk {
  stop-color: var(--svg-color--4ece7f, #4ECE7F);
}

.r0ek86b5r {
  d: path("M19.515 28.5h-5c-.28 0-.5-.22-.5-.5s.22-.5.5-.5h5c.28 0 .5.22.5.5c0 .27-.23.5-.5.5");
}

.rsubfglyb {
  d: path("M29.995 22h-.98c-.55 0-1-.45-1-1l.01-6c0-.55.45-1 1-1h.98z");
}

.tnz914bvq {
  stop-color: var(--svg-color--a28dad, #A28DAD);
}

.u10m2k0br {
  stop-color: var(--svg-color--407561, #407561);
}

.u61-y5n5k {
  stop-color: var(--svg-color--59a083, #59A083);
  stop-opacity: 0;
}

.u77oyxbpm {
  stop-color: var(--svg-color--34815f, #34815F);
  stop-opacity: 0;
}

.u83d68b5l {
  fill: var(--svg-color--55435b, #55435B);
  fill-rule: evenodd;
  d: path("M18.106 27.555h1.42c.189 0 .337.22.337.5s-.148.5-.338.5h-1.329a2.8 2.8 0 0 1-.09-1");
}

.uggervb6g {
  stop-color: var(--svg-color--4dd8ff, #4DD8FF);
}

.v2i60qbat {
  stop-color: var(--svg-color--8b8692, #8B8692);
}

.vje63rbxx {
  stop-color: var(--svg-color--1d543f, #1D543F);
  stop-opacity: 0;
}

.vk3b3fbes {
  stop-color: var(--svg-color--5affff, #5AFFFF);
}

.w9zwz1bhh {
  fill: var(--svg-color--55435b, #55435B);
  fill-rule: evenodd;
  d: path("M16.48 27.555h-2.098c-.28 0-.5.22-.5.5s.22.5.5.5h1.964a2 2 0 0 0 .134-1");
}

.wjfkidcqc {
  stop-color: var(--svg-color--534350, #534350);
  stop-opacity: 0;
}

.x85xq1byi {
  stop-color: var(--svg-color--34815f, #34815F);
}

.xldv61laq {
  stop-color: var(--svg-color--52db8b, #52DB8B);
}

.zw-idtb2u {
  fill: var(--svg-color--786e7c, #786E7C);
  d: path("M14.495 30a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

</style>
