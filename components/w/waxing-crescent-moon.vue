<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#iUiEl2d)" class="lmh4whbrs"/><circle fill="url(#id4Pb9c)" class="lmh4whbrs"/><circle fill="url(#iDfclyq)" class="x5_7l-bbi"/><circle fill="url(#iqfJvtw)" class="az0fwjbyp"/><g filter="url(#iUlmsBe)"><circle fill="url(#iIBjldc)" class="g4k3q7cmw"/><circle class="s-ppsol1e"/></g><circle fill="url(#isY3BBc)" class="h2-o4in6u"/><path fill="url(#i1sbmye)" clip-rule="evenodd" class="t3srrzbwo"/><g filter="url(#iJ7o4pe)"><path stroke="url(#iioQCPc)" class="t4ha9ieeq"/></g><path fill="url(#ivdK03c)" clip-rule="evenodd" class="t6ruvjb9j"/><path fill="url(#iJMGzEc)" clip-rule="evenodd" class="t6ruvjb9j"/><path fill="url(#inQ647V)" clip-rule="evenodd" class="t6ruvjb9j"/><g clip-rule="evenodd" filter="url(#i1DRELG)" class="d2kvgvbvc"><path fill="url(#isu7WrL)" class="p5rgw1b_d"/><path fill="url(#i3AOkqc)" class="p5rgw1b_d"/></g><g filter="url(#iptxb2b)"><ellipse fill="url(#iNkNPQc)" class="qj9trqv8d"/><ellipse fill="url(#idSVxdb)" class="qj9trqv8d"/></g><g filter="url(#iA2v5ll)"><circle stroke="url(#iYXdFSN)" class="aif3dxb6p"/></g><circle fill="url(#ijUhbVd)" class="az0fwjbyp"/><circle fill="url(#i3Vusdb)" class="az0fwjbyp"/><circle fill="url(#iUHYcXd)" class="az0fwjbyp"/><g filter="url(#ihzfCQd)"><path stroke="url(#iql5bwb)" class="dd52jab0w"/></g><path fill="url(#iaEEfQc)" clip-rule="evenodd" class="h_10ppbji"/><g filter="url(#iIaXyze)"><circle stroke="url(#iYnGicd)" class="m34e9s3yo"/></g><circle fill="url(#iKWPu0b)" class="h2-o4in6u"/><circle fill="url(#ii89wLe)" class="h2-o4in6u"/><circle fill="url(#iSzeb0c)" class="h2-o4in6u"/><circle fill="url(#i5OsGie)" class="h2-o4in6u"/><g filter="url(#iu2NLez)"><path stroke="url(#ifkgOse)" class="kcv9zv55c"/></g><path fill="url(#ixWz6ze)" class="lf_xyqbww"/><defs><radialGradient id="iUiEl2d" cx="0" cy="0" r="1" gradientTransform="rotate(112.552 8.742 13.515)scale(20.3702)" gradientUnits="userSpaceOnUse"><stop offset=".223" class="ws138acza"/><stop offset=".646" class="ackb9ubid"/><stop offset="1" class="fnv--_0fx"/></radialGradient><radialGradient id="id4Pb9c" cx="0" cy="0" r="1" gradientTransform="rotate(78.413 1.758 15.466)scale(20.3539)" gradientUnits="userSpaceOnUse"><stop class="r4l_-pb2r"/><stop offset=".879" class="r4l_-pb2r"/><stop offset="1" class="fofzq4cis"/></radialGradient><radialGradient id="iIBjldc" cx="0" cy="0" r="1" gradientTransform="rotate(-22.476 40.905 -50.727)scale(2.28001)" gradientUnits="userSpaceOnUse"><stop class="y5r8bnbsm"/><stop offset="1" class="r_kg8hczw"/></radialGradient><radialGradient id="iJMGzEc" cx="0" cy="0" r="1" gradientTransform="matrix(-.87214 -5.64197 4.67917 -.72331 27.35 26.823)" gradientUnits="userSpaceOnUse"><stop offset=".85" class="d1gfmbu2u"/><stop offset="1" class="x5cl77b6u"/></radialGradient><radialGradient id="inQ647V" cx="0" cy="0" r="1" gradientTransform="rotate(122.849 7.272 18.953)scale(4.72413 4.02056)" gradientUnits="userSpaceOnUse"><stop offset=".718" class="juqbnk4bv"/><stop offset=".952" class="rktfksz4s"/></radialGradient><radialGradient id="isu7WrL" cx="0" cy="0" r="1" gradientTransform="rotate(135.942 8.322 10.64)scale(18.9674 16.3453)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="qgbgkorov"/><stop offset="1" class="yzwz82buk"/></radialGradient><radialGradient id="i3AOkqc" cx="0" cy="0" r="1" gradientTransform="matrix(14.22874 -8.1471 8.67708 15.15435 3.71 22.247)" gradientUnits="userSpaceOnUse"><stop class="q2f_lpt3v"/><stop offset="1" class="ia44887dv"/></radialGradient><radialGradient id="iNkNPQc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.49282 0 0 -2.78166 17.119 5.459)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="yuoatmb7a"/><stop offset="1" class="ar4v0iy4a"/></radialGradient><radialGradient id="idSVxdb" cx="0" cy="0" r="1" gradientTransform="matrix(2.13059 0 0 1.92488 15.56 5.459)" gradientUnits="userSpaceOnUse"><stop offset=".711" class="pspj-mbwr"/><stop offset="1" class="x12ziqbrn"/></radialGradient><radialGradient id="ijUhbVd" cx="0" cy="0" r="1" gradientTransform="matrix(5.38392 .98706 -1.14913 6.26797 8.068 12.22)" gradientUnits="userSpaceOnUse"><stop class="k1ycr2tfc"/><stop offset="1" class="xn282acyu"/></radialGradient><radialGradient id="i3Vusdb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.79743 -.92775 1.02753 -4.20584 9.797 12.5)" gradientUnits="userSpaceOnUse"><stop offset=".886" class="z_043u7tj"/><stop offset="1" class="gql29xbsu"/></radialGradient><radialGradient id="iUHYcXd" cx="0" cy="0" r="1" gradientTransform="rotate(109.781 2.726 8.361)scale(7.83707)" gradientUnits="userSpaceOnUse"><stop offset=".82" class="vdekk1bcl"/><stop offset="1" class="qletn-b4z"/></radialGradient><radialGradient id="iaEEfQc" cx="0" cy="0" r="1" gradientTransform="rotate(-28.947 34.411 -33.759)scale(3.48654 3.03371)" gradientUnits="userSpaceOnUse"><stop offset=".29" class="u_9a7lb2j"/><stop offset=".778" class="yblurlmum"/></radialGradient><radialGradient id="iKWPu0b" cx="0" cy="0" r="1" gradientTransform="matrix(2.29671 -3.78 4.40069 2.67384 15.472 23.51)" gradientUnits="userSpaceOnUse"><stop class="nmqja-b5r"/><stop offset="1" class="mf987ss-p"/></radialGradient><radialGradient id="ii89wLe" cx="0" cy="0" r="1" gradientTransform="rotate(118.54 2.158 15.508)scale(3.1046 3.20092)" gradientUnits="userSpaceOnUse"><stop offset=".789" class="xhmqgdkdw"/><stop offset="1" class="od20u6b3v"/></radialGradient><radialGradient id="iSzeb0c" cx="0" cy="0" r="1" gradientTransform="matrix(3.52289 -4.27779 2.99635 2.46758 14.67 23.642)" gradientUnits="userSpaceOnUse"><stop offset=".8" class="hcvo9rclz"/><stop offset="1" class="aouzsrgog"/></radialGradient><radialGradient id="i5OsGie" cx="0" cy="0" r="1" gradientTransform="matrix(2.94774 2.48038 -2.63083 3.12654 15.676 20.873)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="kowu5e5ac"/><stop offset="1" class="sk_-w8f9q"/></radialGradient><linearGradient id="iDfclyq" x1="16.5" x2="14.5" y1="4.5" y2="6.5" gradientUnits="userSpaceOnUse"><stop class="s334l8uyu"/><stop offset="1" class="nec_isxbo"/></linearGradient><linearGradient id="iqfJvtw" x1="11.833" x2="7.167" y1="10.167" y2="14.833" gradientUnits="userSpaceOnUse"><stop class="s334l8uyu"/><stop offset="1" class="nec_isxbo"/></linearGradient><linearGradient id="isY3BBc" x1="18.167" x2="14.833" y1="19.833" y2="23.167" gradientUnits="userSpaceOnUse"><stop class="s334l8uyu"/><stop offset="1" class="nec_isxbo"/></linearGradient><linearGradient id="i1sbmye" x1="11" x2="4" y1="24.5" y2="26" gradientUnits="userSpaceOnUse"><stop class="s334l8uyu"/><stop offset="1" class="uyvx2tbpp"/></linearGradient><linearGradient id="iioQCPc" x1="27.982" x2="24.639" y1="20.656" y2="26.313" gradientUnits="userSpaceOnUse"><stop class="eobh93bgv"/><stop offset="1" class="azg09_fix"/></linearGradient><linearGradient id="ivdK03c" x1="26.059" x2="25.915" y1="21.826" y2="25.986" gradientUnits="userSpaceOnUse"><stop class="exwjse53p"/><stop offset="1" class="hbsahlgvg"/></linearGradient><linearGradient id="iYXdFSN" x1="13" x2="6.572" y1="9.945" y2="15.065" gradientUnits="userSpaceOnUse"><stop class="uhjnysbhq"/><stop offset="1" class="nln46izyc"/></linearGradient><linearGradient id="iql5bwb" x1="20.67" x2="22.232" y1="10.547" y2="14.109" gradientUnits="userSpaceOnUse"><stop class="wapsmeief"/><stop offset=".491" class="utzjulb1k"/><stop offset="1" class="wapsmeief"/></linearGradient><linearGradient id="iYnGicd" x1="19" x2="14.409" y1="19.675" y2="23.332" gradientUnits="userSpaceOnUse"><stop class="v0xcpxbum"/><stop offset="1" class="l90x68blj"/></linearGradient><linearGradient id="ifkgOse" x1="5.629" x2="11.212" y1="23.63" y2="27.631" gradientUnits="userSpaceOnUse"><stop class="d-qh370ov"/><stop offset=".213" class="ckg96ab_f"/><stop offset=".806" class="tpxhj3bwc"/><stop offset="1" class="nvyr_0bok"/></linearGradient><linearGradient id="ixWz6ze" x1="5.361" x2="11" y1="24.531" y2="28.375" gradientUnits="userSpaceOnUse"><stop class="h68pcvbge"/><stop offset="1" class="e63bi9bxf"/></linearGradient><filter id="iUlmsBe" width="5.8" height="5.8" x="19.6" y="8.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13888" stdDeviation=".15"/></filter><filter id="iJ7o4pe" width="5.707" height="6.614" x="23.55" y="20.55" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13888" stdDeviation=".15"/></filter><filter id="i1DRELG" width="22.25" height="28" x="2" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.443137 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13888"/></filter><filter id="iptxb2b" width="3.583" height="3.256" x="14.208" y="3.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13888" stdDeviation=".05"/></filter><filter id="iA2v5ll" width="7.6" height="7.6" x="5.7" y="8.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13888" stdDeviation=".1"/></filter><filter id="ihzfCQd" width="4.071" height="5.5" x="19.73" y="8.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13888" stdDeviation=".1"/></filter><filter id="iIaXyze" width="5.75" height="5.75" x="13.625" y="18.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13888" stdDeviation=".125"/></filter><filter id="iu2NLez" width="6.753" height="6.201" x="4.547" y="22.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13888" stdDeviation=".1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:waxing-crescent-moon" /></template>
<style>
.ackb9ubid {
  stop-color: var(--svg-color--ffc850, #FFC850);
}

.aif3dxb6p {
  cx: 9.5px;
  cy: 12.5px;
  r: 3.5px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.aouzsrgog {
  stop-color: var(--svg-color--64398c, #64398C);
}

.ar4v0iy4a {
  stop-color: var(--svg-color--a276c9, #A276C9);
}

.az0fwjbyp {
  cx: 9.5px;
  cy: 12.5px;
  r: 3.5px;
}

.azg09_fix {
  stop-color: var(--svg-color--ffdc75, #FFDC75);
}

.ckg96ab_f {
  stop-color: var(--svg-color--372447, #372447);
  stop-opacity: 0;
}

.d-qh370ov {
  stop-color: var(--svg-color--372447, #372447);
}

.d1gfmbu2u {
  stop-color: var(--svg-color--dfa14c, #DFA14C);
  stop-opacity: 0;
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.dd52jab0w {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M22.39 9.002L22.302 9c-1.28.14-2.32 1.104-2.32 2.484c-.054 1.079.813 2.399 2.32 2.516c.43 0 .835-.109 1.19-.3a3 3 0 0 1-1.044-4.56z");
}

.e63bi9bxf {
  stop-color: var(--svg-color--64497d, #64497D);
}

.eobh93bgv {
  stop-color: var(--svg-color--f5bd64, #F5BD64);
}

.exwjse53p {
  stop-color: var(--svg-color--ffd36a, #FFD36A);
}

.fnv--_0fx {
  stop-color: var(--svg-color--e3945b, #E3945B);
}

.fofzq4cis {
  stop-color: var(--svg-color--d7938c, #D7938C);
}

.ft5dv1b6b {
  fill: none;
}

.g4k3q7cmw {
  cx: 22.5px;
  cy: 11.5px;
  r: 2.5px;
}

.gql29xbsu {
  stop-color: var(--svg-color--8260a1, #8260A1);
}

.h_10ppbji {
  fill-rule: evenodd;
  d: path("M22.589 9.002L22.5 9a2.5 2.5 0 1 0 1.19 4.7a3 3 0 0 1-1.044-4.56z");
}

.h2-o4in6u {
  cx: 16.5px;
  cy: 21.5px;
  r: 2.5px;
}

.h68pcvbge {
  stop-color: var(--svg-color--50425c, #50425C);
}

.hbsahlgvg {
  stop-color: var(--svg-color--efb872, #EFB872);
}

.hcvo9rclz {
  stop-color: var(--svg-color--64398c, #64398C);
  stop-opacity: 0;
}

.ia44887dv {
  stop-color: var(--svg-color--473e52, #473E52);
  stop-opacity: 0;
}

.juqbnk4bv {
  stop-color: var(--svg-color--ffe38a, #FFE38A);
  stop-opacity: 0;
}

.k1ycr2tfc {
  stop-color: var(--svg-color--6d4a8d, #6D4A8D);
}

.kcv9zv55c {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M10.28 28.578c-2.166-.99-4.003-2.452-5.407-4.344C5.513 23.422 6.385 23 7.5 23a3.5 3.5 0 0 1 3.5 3.5c0 .852-.214 1.471-.72 2.078Z");
}

.kowu5e5ac {
  stop-color: var(--svg-color--664289, #664289);
  stop-opacity: 0;
}

.l90x68blj {
  stop-color: var(--svg-color--683b92, #683B92);
  stop-opacity: 0;
}

.lf_xyqbww {
  d: path("M10.189 28.74a14.05 14.05 0 0 1-5.439-4.405a3.5 3.5 0 1 1 5.439 4.406");
}

.lmh4whbrs {
  cx: 16px;
  cy: 16px;
  r: 14px;
}

.m34e9s3yo {
  cx: 16.5px;
  cy: 21.5px;
  r: 2.5px;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
}

.mf987ss-p {
  stop-color: var(--svg-color--6f4197, #6F4197);
}

.nec_isxbo {
  stop-color: var(--svg-color--ffef71, #FFEF71);
}

.nln46izyc {
  stop-color: var(--svg-color--603d83, #603D83);
  stop-opacity: 0;
}

.nmqja-b5r {
  stop-color: var(--svg-color--724d94, #724D94);
}

.nvyr_0bok {
  stop-color: var(--svg-color--654e72, #654E72);
}

.od20u6b3v {
  stop-color: var(--svg-color--8b72a3, #8B72A3);
}

.p5rgw1b_d {
  d: path("M17.4 2.07Q16.709 2 16 2C8.268 2 2 8.268 2 16s6.268 14 14 14q.709 0 1.4-.07A17.96 17.96 0 0 0 24 16q0-1.129-.136-2.222a3 3 0 0 1-1.218-4.638A18.05 18.05 0 0 0 17.4 2.07");
}

.pspj-mbwr {
  stop-color: var(--svg-color--664581, #664581);
  stop-opacity: 0;
}

.q2f_lpt3v {
  stop-color: var(--svg-color--473e52, #473E52);
}

.qgbgkorov {
  stop-color: var(--svg-color--936dbd, #936DBD);
}

.qj9trqv8d {
  cx: 16px;
  cy: 5.459px;
  rx: 1.692px;
  ry: 1.528px;
}

.qletn-b4z {
  stop-color: var(--svg-color--614879, #614879);
}

.r_kg8hczw {
  stop-color: var(--svg-color--ffda77, #FFDA77);
}

.r4l_-pb2r {
  stop-color: var(--svg-color--d7938c, #D7938C);
  stop-opacity: 0;
}

.rktfksz4s {
  stop-color: var(--svg-color--ffe38a, #FFE38A);
}

.s-ppsol1e {
  cx: 22.5px;
  cy: 11.5px;
  r: 2.55px;
  stroke: var(--svg-color--fff8ac, #FFF8AC);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.s334l8uyu {
  stop-color: var(--svg-color--f5c224, #F5C224);
}

.sk_-w8f9q {
  stop-color: var(--svg-color--664289, #664289);
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

.tpxhj3bwc {
  stop-color: var(--svg-color--654e72, #654E72);
  stop-opacity: 0;
}

.u_9a7lb2j {
  stop-color: var(--svg-color--b185d6, #B185D6);
}

.uhjnysbhq {
  stop-color: var(--svg-color--603d83, #603D83);
}

.utzjulb1k {
  stop-color: var(--svg-color--a47bd1, #A47BD1);
  stop-opacity: 0;
}

.uyvx2tbpp {
  stop-color: var(--svg-color--fce35d, #FCE35D);
}

.v0xcpxbum {
  stop-color: var(--svg-color--683b92, #683B92);
}

.vdekk1bcl {
  stop-color: var(--svg-color--614879, #614879);
  stop-opacity: 0;
}

.wapsmeief {
  stop-color: var(--svg-color--a47bd1, #A47BD1);
}

.ws138acza {
  stop-color: var(--svg-color--fff9ad, #FFF9AD);
}

.x12ziqbrn {
  stop-color: var(--svg-color--664581, #664581);
}

.x5_7l-bbi {
  cx: 15.5px;
  cy: 5.5px;
  r: 1.5px;
}

.x5cl77b6u {
  stop-color: var(--svg-color--c28255, #C28255);
}

.xhmqgdkdw {
  stop-color: var(--svg-color--8b72a3, #8B72A3);
  stop-opacity: 0;
}

.xn282acyu {
  stop-color: var(--svg-color--60427c, #60427C);
}

.y5r8bnbsm {
  stop-color: var(--svg-color--fff2a8, #FFF2A8);
}

.yblurlmum {
  stop-color: var(--svg-color--9b6bbf, #9B6BBF);
}

.yuoatmb7a {
  stop-color: var(--svg-color--79529b, #79529B);
}

.yzwz82buk {
  stop-color: var(--svg-color--663993, #663993);
}

.z_043u7tj {
  stop-color: var(--svg-color--8260a1, #8260A1);
  stop-opacity: 0;
}

</style>
