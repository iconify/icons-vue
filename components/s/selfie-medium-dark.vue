<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#in2fhkb)" class="hntxvv91o"/><rect fill="url(#ip4Cuec)" class="hntxvv91o"/><path fill="url(#ie9FQ7c)" class="trloanblz"/><path fill="url(#ifixJFd)" class="trloanblz"/><path fill="url(#imydPId)" class="trloanblz"/><path fill="url(#ifcEvfc)" class="trloanblz"/><g filter="url(#iPE0kOb)"><path fill="url(#iW9S29t)" class="pr5srbcsp"/></g><path class="xohsu7byc"/><path fill="url(#idl6uec)" class="rgekcdbdo"/><path fill="url(#izhTCVd)" class="rgekcdbdo"/><path fill="url(#inyAEPb)" class="rgekcdbdo"/><path fill="url(#inRB8xM)" class="rgekcdbdo"/><path fill="url(#ilVid8g)" class="rgekcdbdo"/><g filter="url(#iKjBpJe)"><path class="xk7k2cqmy"/><path fill="url(#igPDBXd)" class="sn692nu2n"/><path fill="url(#ifkYorc)" class="sn692nu2n"/></g><rect fill="url(#iDSkD9c)" class="s-pxt2b6i"/><rect fill="url(#iJzMS9M)" class="s-pxt2b6i"/><rect fill="url(#iEKMNcb)" class="s-pxt2b6i"/><rect fill="url(#ipFrFSc)" class="s-pxt2b6i"/><rect fill="url(#iu7BLQT)" class="s-pxt2b6i"/><rect fill="url(#in8Ijgc)" class="ezm874s8f"/><rect fill="url(#iKZEevd)" class="ezm874s8f"/><rect fill="url(#i20nHLd)" class="ezm874s8f"/><rect fill="url(#iVzNZHV)" class="hiusohbhc"/><rect fill="url(#imvL0fb)" class="hiusohbhc"/><rect fill="url(#ipPJVMb)" class="hiusohbhc"/><rect fill="url(#iHDk7ze)" class="hiusohbhc"/><rect fill="url(#i8a3Pad)" class="s6j8ehboa"/><rect fill="url(#i00pxVd)" class="s6j8ehboa"/><rect fill="url(#iQB94RZ)" class="s6j8ehboa"/><rect fill="url(#iNMyNbd)" class="s6j8ehboa"/><defs><radialGradient id="ie9FQ7c" cx="0" cy="0" r="1" gradientTransform="rotate(97.587 8.894 11.136)scale(8.79527 10.2043)" gradientUnits="userSpaceOnUse"><stop class="ty3t7mbpp"/><stop offset="1" class="kgy6yeipv"/></radialGradient><radialGradient id="ifcEvfc" cx="0" cy="0" r="1" gradientTransform="matrix(1.94501 .78125 -.58938 1.46734 18 9.352)" gradientUnits="userSpaceOnUse"><stop class="m6s5orlpe"/><stop offset="1" class="yu5deqbhy"/></radialGradient><radialGradient id="idl6uec" cx="0" cy="0" r="1" gradientTransform="matrix(-3.19961 0 0 -3.32917 23.639 12.406)" gradientUnits="userSpaceOnUse"><stop offset=".425" class="e4__0vsej"/><stop offset="1" class="zgdi4v6gv"/></radialGradient><radialGradient id="izhTCVd" cx="0" cy="0" r="1" gradientTransform="matrix(2.14654 -.49853 2.8596 12.3127 16.25 11.882)" gradientUnits="userSpaceOnUse"><stop class="e4__0vsej"/><stop offset="1" class="zgdi4v6gv"/></radialGradient><radialGradient id="inyAEPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.71723 3.30237 0 18.361 10.166)" gradientUnits="userSpaceOnUse"><stop class="e4__0vsej"/><stop offset="1" class="zgdi4v6gv"/></radialGradient><radialGradient id="inRB8xM" cx="0" cy="0" r="1" gradientTransform="matrix(-.80716 .88786 -.96855 -.8805 17.79 11.13)" gradientUnits="userSpaceOnUse"><stop class="hdh7eybjd"/><stop offset="1" class="d3plm5x9f"/></radialGradient><radialGradient id="ilVid8g" cx="0" cy="0" r="1" gradientTransform="matrix(-.62745 .62745 -.71264 -.71264 18.89 8.348)" gradientUnits="userSpaceOnUse"><stop class="hdh7eybjd"/><stop offset="1" class="d3plm5x9f"/></radialGradient><radialGradient id="igPDBXd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.68752 2.24998 -.59132 -.70631 23.483 15.062)" gradientUnits="userSpaceOnUse"><stop class="u9h--_uhg"/><stop offset="1" class="nq5--fbox"/></radialGradient><radialGradient id="iJzMS9M" cx="0" cy="0" r="1" gradientTransform="matrix(-.53893 .375 -.33792 -.48564 24.18 11.36)" gradientUnits="userSpaceOnUse"><stop class="nf-3wzt9x"/><stop offset="1" class="eu9h-twkt"/></radialGradient><radialGradient id="iEKMNcb" cx="0" cy="0" r="1" gradientTransform="matrix(1.00616 0 0 1.88344 21.572 11.648)" gradientUnits="userSpaceOnUse"><stop class="zo59dw13e"/><stop offset="1" class="ripo3pb7n"/></radialGradient><radialGradient id="iKZEevd" cx="0" cy="0" r="1" gradientTransform="matrix(-.63281 .375 -.31612 -.53345 24.716 5.352)" gradientUnits="userSpaceOnUse"><stop class="nf-3wzt9x"/><stop offset="1" class="eu9h-twkt"/></radialGradient><radialGradient id="i20nHLd" cx="0" cy="0" r="1" gradientTransform="matrix(1.07813 0 0 1.71875 21.17 5.64)" gradientUnits="userSpaceOnUse"><stop class="zo59dw13e"/><stop offset="1" class="ripo3pb7n"/></radialGradient><radialGradient id="imvL0fb" cx="0" cy="0" r="1" gradientTransform="matrix(-.63281 .375 -.31612 -.53345 24.716 9.43)" gradientUnits="userSpaceOnUse"><stop class="nf-3wzt9x"/><stop offset="1" class="eu9h-twkt"/></radialGradient><radialGradient id="ipPJVMb" cx="0" cy="0" r="1" gradientTransform="matrix(1.07812 0 0 1.71875 21.563 9.719)" gradientUnits="userSpaceOnUse"><stop class="zo59dw13e"/><stop offset="1" class="ripo3pb7n"/></radialGradient><radialGradient id="i00pxVd" cx="0" cy="0" r="1" gradientTransform="matrix(-.66202 .375 -.3091 -.54569 24.694 7.445)" gradientUnits="userSpaceOnUse"><stop class="nf-3wzt9x"/><stop offset="1" class="eu9h-twkt"/></radialGradient><radialGradient id="iQB94RZ" cx="0" cy="0" r="1" gradientTransform="matrix(1.20312 0 0 1.83341 21.375 7.734)" gradientUnits="userSpaceOnUse"><stop class="zo59dw13e"/><stop offset="1" class="ripo3pb7n"/></radialGradient><linearGradient id="in2fhkb" x1="21.513" x2="24.074" y1="5.217" y2="2.508" gradientUnits="userSpaceOnUse"><stop class="fy31g80qu"/><stop offset="1" class="jcq7qbblj"/></linearGradient><linearGradient id="ip4Cuec" x1="20.361" x2="20.361" y1="12.231" y2="11.45" gradientUnits="userSpaceOnUse"><stop class="b4id_clxv"/><stop offset="1" class="bxgu95jbn"/></linearGradient><linearGradient id="ifixJFd" x1="23.17" x2="22.466" y1="7.294" y2="7.294" gradientUnits="userSpaceOnUse"><stop class="o219w69lb"/><stop offset="1" class="ofwypjbaj"/></linearGradient><linearGradient id="imydPId" x1="16.906" x2="17.334" y1="7.016" y2="7.016" gradientUnits="userSpaceOnUse"><stop class="bxw14_b6p"/><stop offset="1" class="l5s8r7bmx"/></linearGradient><linearGradient id="iW9S29t" x1="21.942" x2="21.942" y1="10.602" y2="5.689" gradientUnits="userSpaceOnUse"><stop class="dw-6bo_en"/><stop offset="1" class="kjc7f9q9w"/></linearGradient><linearGradient id="ifkYorc" x1="11.076" x2="11.076" y1="30.813" y2="27.188" gradientUnits="userSpaceOnUse"><stop class="s-5ofoxht"/><stop offset="1" class="ab64lebgw"/></linearGradient><linearGradient id="iDSkD9c" x1="23.086" x2="23.086" y1="10.602" y2="12.695" gradientUnits="userSpaceOnUse"><stop class="o99r10iyi"/><stop offset="1" class="kg6nxsbmk"/></linearGradient><linearGradient id="ipFrFSc" x1="23.086" x2="23.086" y1="10.602" y2="10.906" gradientUnits="userSpaceOnUse"><stop class="f-gjk8b2j"/><stop offset="1" class="zfvx_3b8f"/></linearGradient><linearGradient id="iu7BLQT" x1="23.367" x2="23.367" y1="12.844" y2="12.195" gradientUnits="userSpaceOnUse"><stop class="oeu435v1g"/><stop offset="1" class="vmhe3zp-d"/></linearGradient><linearGradient id="in8Ijgc" x1="23.431" x2="23.431" y1="4.594" y2="6.688" gradientUnits="userSpaceOnUse"><stop class="o99r10iyi"/><stop offset="1" class="kg6nxsbmk"/></linearGradient><linearGradient id="iVzNZHV" x1="23.431" x2="23.431" y1="8.672" y2="10.766" gradientUnits="userSpaceOnUse"><stop class="o99r10iyi"/><stop offset="1" class="kg6nxsbmk"/></linearGradient><linearGradient id="iHDk7ze" x1="23.431" x2="23.431" y1="8.602" y2="8.906" gradientUnits="userSpaceOnUse"><stop class="f-gjk8b2j"/><stop offset="1" class="zfvx_3b8f"/></linearGradient><linearGradient id="i8a3Pad" x1="23.349" x2="23.349" y1="6.688" y2="8.781" gradientUnits="userSpaceOnUse"><stop class="o99r10iyi"/><stop offset="1" class="kg6nxsbmk"/></linearGradient><linearGradient id="iNMyNbd" x1="23.349" x2="23.349" y1="6.617" y2="6.922" gradientUnits="userSpaceOnUse"><stop class="f-gjk8b2j"/><stop offset="1" class="zfvx_3b8f"/></linearGradient><filter id="iPE0kOb" width="3.914" height="6.625" x="20.699" y="4.477" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5824" stdDeviation=".25"/></filter><filter id="iKjBpJe" width="22.048" height="15.844" x="1.998" y="15.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.713726 0 0 0 0 0.121569 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5824"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:selfie-medium-dark" /></template>
<style>
.ab64lebgw {
  stop-color: var(--svg-color--ba2083, #BA2083);
  stop-opacity: 0;
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

.d3plm5x9f {
  stop-color: var(--svg-color--9c7b72, #9C7B72);
  stop-opacity: 0;
}

.dw-6bo_en {
  stop-color: var(--svg-color--3985c0, #3985C0);
}

.e4__0vsej {
  stop-color: var(--svg-color--7a4a54, #7A4A54);
}

.eu9h-twkt {
  stop-color: var(--svg-color--9e7d70, #9E7D70);
  stop-opacity: 0;
}

.ezm874s8f {
  width: 3.555px;
  height: 2.094px;
  x: 21.654px;
  y: 4.594px;
  rx: 1.047px;
}

.f-gjk8b2j {
  stop-color: var(--svg-color--65372a, #65372A);
}

.ft5dv1b6b {
  fill: none;
}

.fy31g80qu {
  stop-color: var(--svg-color--3c4071, #3C4071);
}

.hdh7eybjd {
  stop-color: var(--svg-color--9c7b72, #9C7B72);
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

.jcq7qbblj {
  stop-color: var(--svg-color--5c618e, #5C618E);
}

.kg6nxsbmk {
  stop-color: var(--svg-color--794946, #794946);
}

.kgy6yeipv {
  stop-color: var(--svg-color--187ec3, #187EC3);
}

.kjc7f9q9w {
  stop-color: var(--svg-color--2967a0, #2967A0);
}

.l5s8r7bmx {
  stop-color: var(--svg-color--4887b6, #4887B6);
  stop-opacity: 0;
}

.m6s5orlpe {
  stop-color: var(--svg-color--267bae, #267BAE);
}

.nf-3wzt9x {
  stop-color: var(--svg-color--9e7d70, #9E7D70);
}

.nq5--fbox {
  stop-color: var(--svg-color--ff99b6, #FF99B6);
  stop-opacity: 0;
}

.o219w69lb {
  stop-color: var(--svg-color--68eaff, #68EAFF);
}

.o99r10iyi {
  stop-color: var(--svg-color--886354, #886354);
}

.oeu435v1g {
  stop-color: var(--svg-color--79405c, #79405C);
}

.ofwypjbaj {
  stop-color: var(--svg-color--68eaff, #68EAFF);
  stop-opacity: 0;
}

.pr5srbcsp {
  d: path("M21.328 5.93c0-.526.427-.953.954-.953h.876a.954.954 0 1 1 0 1.908a.954.954 0 0 1 .305 1.858a.955.955 0 0 1-.305 1.859h-.876a.954.954 0 0 1-.362-1.838a.954.954 0 0 1 .233-1.88h.129a.954.954 0 0 1-.954-.953");
}

.rgekcdbdo {
  d: path("M16.62 7.297a1.32 1.32 0 0 0-1.321 1.336v2.684a2.3 2.3 0 0 0 1.28 2.06c.237.118.401.368.349.628l-.296 1.464h5.364l.375-1.422a.75.75 0 0 1 .44-.502l.703-.244c.442-.132.852-.62.999-1.184l.067-.289l-.948.054c-.132-.006-.262.02-.392.046q-.073.015-.147.028a1 1 0 0 1-.15.013H17.88a.9.9 0 0 1-.903-.9v-.89a.25.25 0 0 1 .25-.25h.844c.73 0 1.321-.589 1.321-1.316s-.591-1.316-1.321-1.316z");
}

.ripo3pb7n {
  stop-color: var(--svg-color--744e48, #744E48);
  stop-opacity: 0;
}

.s-5ofoxht {
  stop-color: var(--svg-color--ba2083, #BA2083);
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

.sn692nu2n {
  d: path("M16.778 15.063a1.2 1.2 0 0 0-1.129.793l-2.023 5.617a.75.75 0 0 1-.706.496H2.598a.6.6 0 0 0-.6.6v6.737a.6.6 0 0 0 .6.6h13.238a4 4 0 0 0 3.819-2.81L23 16.36a1 1 0 0 0-.955-1.297z");
}

.trloanblz {
  d: path("M16.94 11V3.031h6.01V11z");
}

.ty3t7mbpp {
  stop-color: var(--svg-color--4abde1, #4ABDE1);
}

.u9h--_uhg {
  stop-color: var(--svg-color--ff99b6, #FF99B6);
}

.vmhe3zp-d {
  stop-color: var(--svg-color--79405c, #79405C);
  stop-opacity: 0;
}

.xk7k2cqmy {
  fill: var(--svg-color--e24c86, #E24C86);
  d: path("M16.778 15.063a1.2 1.2 0 0 0-1.129.793l-2.023 5.617a.75.75 0 0 1-.706.496H2.598a.6.6 0 0 0-.6.6v6.737a.6.6 0 0 0 .6.6h13.238a4 4 0 0 0 3.819-2.81L23 16.36a1 1 0 0 0-.955-1.297z");
}

.xohsu7byc {
  fill: var(--svg-color--8a6660, #8A6660);
  d: path("M16.62 7.297a1.32 1.32 0 0 0-1.321 1.336v2.684a2.3 2.3 0 0 0 1.28 2.06c.237.118.401.368.349.628l-.296 1.464h5.364l.375-1.422a.75.75 0 0 1 .44-.502l.703-.244c.442-.132.852-.62.999-1.184l.067-.289l-.948.054c-.132-.006-.262.02-.392.046q-.073.015-.147.028a1 1 0 0 1-.15.013H17.88a.9.9 0 0 1-.903-.9v-.89a.25.25 0 0 1 .25-.25h.844c.73 0 1.321-.589 1.321-1.316s-.591-1.316-1.321-1.316z");
}

.yu5deqbhy {
  stop-color: var(--svg-color--267bae, #267BAE);
  stop-opacity: 0;
}

.zfvx_3b8f {
  stop-color: var(--svg-color--65372a, #65372A);
  stop-opacity: 0;
}

.zgdi4v6gv {
  stop-color: var(--svg-color--7a4a54, #7A4A54);
  stop-opacity: 0;
}

.zo59dw13e {
  stop-color: var(--svg-color--744e48, #744E48);
}

</style>
