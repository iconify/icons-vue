<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#in2fhkb)" class="hntxvv91o"/><rect fill="url(#ip4Cuec)" class="hntxvv91o"/><path fill="url(#ie9FQ7c)" class="trloanblz"/><path fill="url(#ifixJFd)" class="trloanblz"/><path fill="url(#imydPId)" class="trloanblz"/><path fill="url(#ifcEvfc)" class="trloanblz"/><g filter="url(#iIVOsjd)"><path fill="url(#iW9S29t)" class="pr5srbcsp"/></g><path class="un-k2bcdg"/><path fill="url(#iMv9Kle)" class="rgekcdbdo"/><path fill="url(#iCSEhKb)" class="rgekcdbdo"/><path fill="url(#iqTWYVc)" class="rgekcdbdo"/><path fill="url(#i5VXpke)" class="rgekcdbdo"/><path fill="url(#i4ybUNe)" class="rgekcdbdo"/><g filter="url(#idkSyJP)"><path class="e6kmpfbkd"/><path fill="url(#igPDBXd)" class="sn692nu2n"/><path fill="url(#isdeNfj)" class="sn692nu2n"/></g><rect fill="url(#iGt7MFc)" class="s-pxt2b6i"/><rect fill="url(#iV8uJDn)" class="s-pxt2b6i"/><rect fill="url(#imjUPQR)" class="s-pxt2b6i"/><rect fill="url(#i8bzNKc)" class="s-pxt2b6i"/><rect fill="url(#iYTfeub)" class="s-pxt2b6i"/><rect fill="url(#irowyhd)" class="s-pxt2b6i"/><rect fill="url(#iGl85rb)" class="ezm874s8f"/><rect fill="url(#iFXdE3d)" class="ezm874s8f"/><rect fill="url(#itbZwwc)" class="ezm874s8f"/><rect fill="url(#i38hCWi)" class="hiusohbhc"/><rect fill="url(#ikrn9Md)" class="hiusohbhc"/><rect fill="url(#iPCxkbi)" class="hiusohbhc"/><rect fill="url(#i2KHefb)" class="hiusohbhc"/><rect fill="url(#iD77kjd)" class="s6j8ehboa"/><rect fill="url(#i7O9k9b)" class="s6j8ehboa"/><rect fill="url(#iTvZbCr)" class="s6j8ehboa"/><rect fill="url(#iSHIOod)" class="s6j8ehboa"/><defs><radialGradient id="ie9FQ7c" cx="0" cy="0" r="1" gradientTransform="rotate(97.587 8.894 11.136)scale(8.79527 10.2043)" gradientUnits="userSpaceOnUse"><stop class="ty3t7mbpp"/><stop offset="1" class="kgy6yeipv"/></radialGradient><radialGradient id="ifcEvfc" cx="0" cy="0" r="1" gradientTransform="matrix(1.94501 .78125 -.58938 1.46734 18 9.352)" gradientUnits="userSpaceOnUse"><stop class="m6s5orlpe"/><stop offset="1" class="yu5deqbhy"/></radialGradient><radialGradient id="iMv9Kle" cx="0" cy="0" r="1" gradientTransform="matrix(-3.19961 0 0 -3.32917 23.639 12.406)" gradientUnits="userSpaceOnUse"><stop offset=".425" class="s6q6v0bhv"/><stop offset="1" class="jwxs8nbrt"/></radialGradient><radialGradient id="iCSEhKb" cx="0" cy="0" r="1" gradientTransform="matrix(2.14654 -.49853 2.8596 12.3127 16.25 11.882)" gradientUnits="userSpaceOnUse"><stop class="s6q6v0bhv"/><stop offset="1" class="jwxs8nbrt"/></radialGradient><radialGradient id="iqTWYVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.71723 3.30237 0 18.361 10.166)" gradientUnits="userSpaceOnUse"><stop class="s6q6v0bhv"/><stop offset="1" class="jwxs8nbrt"/></radialGradient><radialGradient id="i5VXpke" cx="0" cy="0" r="1" gradientTransform="matrix(-.62745 .62745 -.71264 -.71264 18.89 8.348)" gradientUnits="userSpaceOnUse"><stop class="xm34y9b_d"/><stop offset="1" class="iv6sy1bym"/></radialGradient><radialGradient id="i4ybUNe" cx="0" cy="0" r="1" gradientTransform="matrix(-.80716 .88786 -.96855 -.8805 17.79 11.13)" gradientUnits="userSpaceOnUse"><stop class="xm34y9b_d"/><stop offset="1" class="iv6sy1bym"/></radialGradient><radialGradient id="igPDBXd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.68752 2.24998 -.59132 -.70631 23.483 15.062)" gradientUnits="userSpaceOnUse"><stop class="u9h--_uhg"/><stop offset="1" class="nq5--fbox"/></radialGradient><radialGradient id="iV8uJDn" cx="0" cy="0" r="1" gradientTransform="matrix(-.53893 .375 -.33792 -.48564 24.18 11.36)" gradientUnits="userSpaceOnUse"><stop class="p_e8aybvr"/><stop offset="1" class="med49wbkk"/></radialGradient><radialGradient id="imjUPQR" cx="0" cy="0" r="1" gradientTransform="matrix(.91818 0 0 1.71875 21.16 11.648)" gradientUnits="userSpaceOnUse"><stop class="ry0-fcbeu"/><stop offset="1" class="i4m0w-buc"/></radialGradient><radialGradient id="iFXdE3d" cx="0" cy="0" r="1" gradientTransform="matrix(-.63281 .375 -.31612 -.53345 24.716 5.352)" gradientUnits="userSpaceOnUse"><stop class="xm34y9b_d"/><stop offset="1" class="iv6sy1bym"/></radialGradient><radialGradient id="itbZwwc" cx="0" cy="0" r="1" gradientTransform="matrix(1.07813 0 0 1.71875 21.17 5.64)" gradientUnits="userSpaceOnUse"><stop class="ihduvzbtj"/><stop offset="1" class="r_9r91bhe"/></radialGradient><radialGradient id="ikrn9Md" cx="0" cy="0" r="1" gradientTransform="matrix(-.63281 .375 -.31612 -.53345 24.716 9.43)" gradientUnits="userSpaceOnUse"><stop class="p_e8aybvr"/><stop offset="1" class="med49wbkk"/></radialGradient><radialGradient id="iPCxkbi" cx="0" cy="0" r="1" gradientTransform="matrix(1.07813 0 0 1.71875 21.17 9.719)" gradientUnits="userSpaceOnUse"><stop class="ry0-fcbeu"/><stop offset="1" class="i4m0w-buc"/></radialGradient><radialGradient id="i7O9k9b" cx="0" cy="0" r="1" gradientTransform="matrix(-.66202 .375 -.3091 -.54569 24.694 7.445)" gradientUnits="userSpaceOnUse"><stop class="p_e8aybvr"/><stop offset="1" class="med49wbkk"/></radialGradient><radialGradient id="iTvZbCr" cx="0" cy="0" r="1" gradientTransform="matrix(1.12788 0 0 1.71875 20.983 7.734)" gradientUnits="userSpaceOnUse"><stop class="ry0-fcbeu"/><stop offset="1" class="i4m0w-buc"/></radialGradient><linearGradient id="in2fhkb" x1="21.513" x2="24.074" y1="5.217" y2="2.508" gradientUnits="userSpaceOnUse"><stop class="fy31g80qu"/><stop offset="1" class="jcq7qbblj"/></linearGradient><linearGradient id="ip4Cuec" x1="20.361" x2="20.361" y1="12.231" y2="11.45" gradientUnits="userSpaceOnUse"><stop class="b4id_clxv"/><stop offset="1" class="bxgu95jbn"/></linearGradient><linearGradient id="ifixJFd" x1="23.17" x2="22.466" y1="7.294" y2="7.294" gradientUnits="userSpaceOnUse"><stop class="o219w69lb"/><stop offset="1" class="ofwypjbaj"/></linearGradient><linearGradient id="imydPId" x1="16.906" x2="17.334" y1="7.016" y2="7.016" gradientUnits="userSpaceOnUse"><stop class="bxw14_b6p"/><stop offset="1" class="l5s8r7bmx"/></linearGradient><linearGradient id="iW9S29t" x1="21.942" x2="21.942" y1="10.602" y2="5.689" gradientUnits="userSpaceOnUse"><stop class="dw-6bo_en"/><stop offset="1" class="kjc7f9q9w"/></linearGradient><linearGradient id="isdeNfj" x1="11.076" x2="11.076" y1="30.813" y2="27.188" gradientUnits="userSpaceOnUse"><stop class="xab7v5bxz"/><stop offset="1" class="pfdkdtd5y"/></linearGradient><linearGradient id="iGt7MFc" x1="23.086" x2="23.086" y1="10.602" y2="12.695" gradientUnits="userSpaceOnUse"><stop class="wfak367or"/><stop offset="1" class="h4nd85b9u"/></linearGradient><linearGradient id="i8bzNKc" x1="23.086" x2="23.086" y1="10.477" y2="10.852" gradientUnits="userSpaceOnUse"><stop class="ej2e_2bnx"/><stop offset="1" class="zna7-11if"/></linearGradient><linearGradient id="iYTfeub" x1="23.086" x2="23.086" y1="12.891" y2="12.125" gradientUnits="userSpaceOnUse"><stop class="tt7eg3bmb"/><stop offset="1" class="r-ag40bgp"/></linearGradient><linearGradient id="irowyhd" x1="23.086" x2="23.086" y1="12.73" y2="12.523" gradientUnits="userSpaceOnUse"><stop class="l17cylbmq"/><stop offset="1" class="wdvczabgj"/></linearGradient><linearGradient id="iGl85rb" x1="23.431" x2="23.431" y1="4.594" y2="6.688" gradientUnits="userSpaceOnUse"><stop class="a_bfjmssa"/><stop offset="1" class="lkizgebfg"/></linearGradient><linearGradient id="i38hCWi" x1="23.431" x2="23.431" y1="8.672" y2="10.766" gradientUnits="userSpaceOnUse"><stop class="wfak367or"/><stop offset="1" class="h4nd85b9u"/></linearGradient><linearGradient id="i2KHefb" x1="23.431" x2="23.431" y1="8.547" y2="8.922" gradientUnits="userSpaceOnUse"><stop class="ej2e_2bnx"/><stop offset="1" class="zna7-11if"/></linearGradient><linearGradient id="iD77kjd" x1="23.349" x2="23.349" y1="6.688" y2="8.781" gradientUnits="userSpaceOnUse"><stop class="wfak367or"/><stop offset="1" class="h4nd85b9u"/></linearGradient><linearGradient id="iSHIOod" x1="23.349" x2="23.349" y1="6.563" y2="6.938" gradientUnits="userSpaceOnUse"><stop class="ej2e_2bnx"/><stop offset="1" class="zna7-11if"/></linearGradient><filter id="iIVOsjd" width="3.914" height="6.625" x="20.699" y="4.477" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5814" stdDeviation=".25"/></filter><filter id="idkSyJP" width="22.048" height="15.844" x="1.998" y="15.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.0941176 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5814"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:selfie-dark" /></template>
<style>
.a_bfjmssa {
  stop-color: var(--svg-color--4e3632, #4E3632);
}

.b4id_clxv {
  stop-color: var(--svg-color--1b1f50, #1B1F50);
}

.bxgu95jbn {
  stop-color: var(--svg-color--1b1f50, #1B1F50);
  stop-opacity: 0;
}

.bxw14_b6p {
  stop-color: var(--svg-color--4887b6, #4887B6);
}

.dw-6bo_en {
  stop-color: var(--svg-color--3985c0, #3985C0);
}

.e6kmpfbkd {
  fill: var(--svg-color--d74380, #D74380);
  d: path("M16.778 15.063a1.2 1.2 0 0 0-1.129.793l-2.023 5.617a.75.75 0 0 1-.706.496H2.598a.6.6 0 0 0-.6.6v6.737a.6.6 0 0 0 .6.6h13.238a4 4 0 0 0 3.819-2.81L23 16.36a1 1 0 0 0-.955-1.297z");
}

.ej2e_2bnx {
  stop-color: var(--svg-color--250e0d, #250E0D);
}

.ezm874s8f {
  width: 3.555px;
  height: 2.094px;
  x: 21.654px;
  y: 4.594px;
  rx: 1.047px;
}

.ft5dv1b6b {
  fill: none;
}

.fy31g80qu {
  stop-color: var(--svg-color--3c4071, #3C4071);
}

.h4nd85b9u {
  stop-color: var(--svg-color--3a2027, #3A2027);
}

.hiusohbhc {
  width: 3.555px;
  height: 2.094px;
  x: 21.654px;
  y: 8.672px;
  rx: 1.047px;
}

.hntxvv91o {
  width: 6.844px;
  height: 9.938px;
  x: 16.939px;
  y: 2.031px;
  rx: 0.9px;
}

.i4m0w-buc {
  stop-color: var(--svg-color--3a2e30, #3A2E30);
  stop-opacity: 0;
}

.ihduvzbtj {
  stop-color: var(--svg-color--3d2c2c, #3D2C2C);
}

.iv6sy1bym {
  stop-color: var(--svg-color--65514f, #65514F);
  stop-opacity: 0;
}

.jcq7qbblj {
  stop-color: var(--svg-color--5c618e, #5C618E);
}

.jwxs8nbrt {
  stop-color: var(--svg-color--3d232d, #3D232D);
  stop-opacity: 0;
}

.kgy6yeipv {
  stop-color: var(--svg-color--187ec3, #187EC3);
}

.kjc7f9q9w {
  stop-color: var(--svg-color--2967a0, #2967A0);
}

.l17cylbmq {
  stop-color: var(--svg-color--473142, #473142);
}

.l5s8r7bmx {
  stop-color: var(--svg-color--4887b6, #4887B6);
  stop-opacity: 0;
}

.lkizgebfg {
  stop-color: var(--svg-color--341b1e, #341B1E);
}

.m6s5orlpe {
  stop-color: var(--svg-color--267bae, #267BAE);
}

.med49wbkk {
  stop-color: var(--svg-color--675351, #675351);
  stop-opacity: 0;
}

.nq5--fbox {
  stop-color: var(--svg-color--ff99b6, #FF99B6);
  stop-opacity: 0;
}

.o219w69lb {
  stop-color: var(--svg-color--68eaff, #68EAFF);
}

.ofwypjbaj {
  stop-color: var(--svg-color--68eaff, #68EAFF);
  stop-opacity: 0;
}

.p_e8aybvr {
  stop-color: var(--svg-color--675351, #675351);
}

.pfdkdtd5y {
  stop-color: var(--svg-color--a51f67, #A51F67);
  stop-opacity: 0;
}

.pr5srbcsp {
  d: path("M21.328 5.93c0-.526.427-.953.954-.953h.876a.954.954 0 1 1 0 1.908a.954.954 0 0 1 .305 1.858a.955.955 0 0 1-.305 1.859h-.876a.954.954 0 0 1-.362-1.838a.954.954 0 0 1 .233-1.88h.129a.954.954 0 0 1-.954-.953");
}

.r_9r91bhe {
  stop-color: var(--svg-color--3d2c2c, #3D2C2C);
  stop-opacity: 0;
}

.r-ag40bgp {
  stop-color: var(--svg-color--3c2035, #3C2035);
  stop-opacity: 0;
}

.rgekcdbdo {
  d: path("M16.62 7.297a1.32 1.32 0 0 0-1.321 1.336v2.684a2.3 2.3 0 0 0 1.28 2.06c.237.118.401.368.349.628l-.296 1.464h5.364l.375-1.422a.75.75 0 0 1 .44-.502l.703-.244c.442-.132.852-.62.999-1.184l.067-.289l-.948.054c-.132-.006-.262.02-.392.046q-.073.015-.147.028a1 1 0 0 1-.15.013H17.88a.9.9 0 0 1-.903-.9v-.89a.25.25 0 0 1 .25-.25h.844c.73 0 1.321-.589 1.321-1.316s-.591-1.316-1.321-1.316z");
}

.ry0-fcbeu {
  stop-color: var(--svg-color--3a2e30, #3A2E30);
}

.s-pxt2b6i {
  width: 3.027px;
  height: 2.094px;
  x: 21.572px;
  y: 10.602px;
  rx: 1.047px;
}

.s6j8ehboa {
  width: 3.719px;
  height: 2.094px;
  x: 21.49px;
  y: 6.688px;
  rx: 1.047px;
}

.s6q6v0bhv {
  stop-color: var(--svg-color--3d232d, #3D232D);
}

.sn692nu2n {
  d: path("M16.778 15.063a1.2 1.2 0 0 0-1.129.793l-2.023 5.617a.75.75 0 0 1-.706.496H2.598a.6.6 0 0 0-.6.6v6.737a.6.6 0 0 0 .6.6h13.238a4 4 0 0 0 3.819-2.81L23 16.36a1 1 0 0 0-.955-1.297z");
}

.trloanblz {
  d: path("M16.94 11V3.031h6.01V11z");
}

.tt7eg3bmb {
  stop-color: var(--svg-color--3c2035, #3C2035);
}

.ty3t7mbpp {
  stop-color: var(--svg-color--4abde1, #4ABDE1);
}

.u9h--_uhg {
  stop-color: var(--svg-color--ff99b6, #FF99B6);
}

.un-k2bcdg {
  fill: var(--svg-color--523d3c, #523D3C);
  d: path("M16.62 7.297a1.32 1.32 0 0 0-1.321 1.336v2.684a2.3 2.3 0 0 0 1.28 2.06c.237.118.401.368.349.628l-.296 1.464h5.364l.375-1.422a.75.75 0 0 1 .44-.502l.703-.244c.442-.132.852-.62.999-1.184l.067-.289l-.948.054c-.132-.006-.262.02-.392.046q-.073.015-.147.028a1 1 0 0 1-.15.013H17.88a.9.9 0 0 1-.903-.9v-.89a.25.25 0 0 1 .25-.25h.844c.73 0 1.321-.589 1.321-1.316s-.591-1.316-1.321-1.316z");
}

.wdvczabgj {
  stop-color: var(--svg-color--473142, #473142);
  stop-opacity: 0;
}

.wfak367or {
  stop-color: var(--svg-color--49312e, #49312E);
}

.xab7v5bxz {
  stop-color: var(--svg-color--a51f67, #A51F67);
}

.xm34y9b_d {
  stop-color: var(--svg-color--65514f, #65514F);
}

.yu5deqbhy {
  stop-color: var(--svg-color--267bae, #267BAE);
  stop-opacity: 0;
}

.zna7-11if {
  stop-color: var(--svg-color--250e0d, #250E0D);
  stop-opacity: 0;
}

</style>
