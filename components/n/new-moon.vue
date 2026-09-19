<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ibKnJnc)"><circle fill="url(#inSvLhc)" class="lmh4whbrs"/></g><circle fill="url(#iYglNFe)" class="lmh4whbrs"/><g filter="url(#i2Xwu8c)"><ellipse fill="url(#ifJydCZ)" class="dgz4yubdl"/><ellipse fill="url(#iq1I09d)" class="dgz4yubdl"/><path stroke="url(#iDYOcRc)" class="bjdh0qbfw"/></g><g filter="url(#iEZwucc)"><circle stroke="url(#iYXdFSN)" class="aif3dxb6p"/></g><circle fill="url(#ijUhbVd)" class="az0fwjbyp"/><circle fill="url(#i3Vusdb)" class="az0fwjbyp"/><circle fill="url(#iUHYcXd)" class="az0fwjbyp"/><g filter="url(#i5JwUrz)"><circle fill="url(#ihdA4bc)" class="g4k3q7cmw"/><circle stroke="url(#i2pnNjJ)" class="xrwbo5xlm"/></g><g filter="url(#io20DyC)"><circle stroke="url(#iYnGicd)" class="m34e9s3yo"/></g><circle fill="url(#iKWPu0b)" class="h2-o4in6u"/><circle fill="url(#ii89wLe)" class="h2-o4in6u"/><circle fill="url(#iSzeb0c)" class="h2-o4in6u"/><circle fill="url(#i5OsGie)" class="h2-o4in6u"/><g filter="url(#iPxT50b)"><path stroke="url(#iSWueDb)" class="vfu63obhs"/></g><path fill="url(#ixWz6ze)" class="lf_xyqbww"/><g filter="url(#iTbUHvg)"><path stroke="url(#ivifywd)" class="p5hlz22-w"/></g><path fill="url(#isklnqb)" class="cmiujyb_i"/><path fill="url(#iiz6DMc)" class="cmiujyb_i"/><path fill="url(#iam0Xxb)" class="cmiujyb_i"/><defs><radialGradient id="inSvLhc" cx="0" cy="0" r="1" gradientTransform="rotate(141.611 10.504 10.055)scale(23.6976)" gradientUnits="userSpaceOnUse"><stop offset=".079" class="fw_pw5b_o"/><stop offset="1" class="p_lhof22o"/></radialGradient><radialGradient id="iYglNFe" cx="0" cy="0" r="1" gradientTransform="rotate(154.299 10.178 8.236)scale(23.217)" gradientUnits="userSpaceOnUse"><stop offset=".673" class="jdhr3wbpz"/><stop offset="1" class="gtckmub7n"/></radialGradient><radialGradient id="ifJydCZ" cx="0" cy="0" r="1" gradientTransform="matrix(-2.51084 0 0 -2.73027 16.83 5.5)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="yuoatmb7a"/><stop offset="1" class="ar4v0iy4a"/></radialGradient><radialGradient id="iq1I09d" cx="0" cy="0" r="1" gradientTransform="matrix(2.14598 0 0 1.88931 15.262 5.5)" gradientUnits="userSpaceOnUse"><stop offset=".711" class="pspj-mbwr"/><stop offset="1" class="x12ziqbrn"/></radialGradient><radialGradient id="ijUhbVd" cx="0" cy="0" r="1" gradientTransform="matrix(5.38392 .98706 -1.14913 6.26797 8.068 12.22)" gradientUnits="userSpaceOnUse"><stop class="k1ycr2tfc"/><stop offset="1" class="xn282acyu"/></radialGradient><radialGradient id="i3Vusdb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.79743 -.92775 1.02753 -4.20584 9.797 12.5)" gradientUnits="userSpaceOnUse"><stop offset=".886" class="z_043u7tj"/><stop offset="1" class="gql29xbsu"/></radialGradient><radialGradient id="iUHYcXd" cx="0" cy="0" r="1" gradientTransform="rotate(109.781 2.726 8.361)scale(7.83707)" gradientUnits="userSpaceOnUse"><stop offset=".82" class="vdekk1bcl"/><stop offset="1" class="qletn-b4z"/></radialGradient><radialGradient id="ihdA4bc" cx="0" cy="0" r="1" gradientTransform="matrix(6.91643 -5.39316 1.77476 2.27603 20 13.396)" gradientUnits="userSpaceOnUse"><stop offset=".2" class="wecidrbdj"/><stop offset="1" class="j9bg4_aho"/></radialGradient><radialGradient id="iKWPu0b" cx="0" cy="0" r="1" gradientTransform="matrix(2.29671 -3.78 4.40069 2.67384 15.472 23.51)" gradientUnits="userSpaceOnUse"><stop class="nmqja-b5r"/><stop offset="1" class="mf987ss-p"/></radialGradient><radialGradient id="ii89wLe" cx="0" cy="0" r="1" gradientTransform="rotate(118.54 2.158 15.508)scale(3.1046 3.20092)" gradientUnits="userSpaceOnUse"><stop offset=".789" class="xhmqgdkdw"/><stop offset="1" class="od20u6b3v"/></radialGradient><radialGradient id="iSzeb0c" cx="0" cy="0" r="1" gradientTransform="matrix(3.52289 -4.27779 2.99635 2.46758 14.67 23.642)" gradientUnits="userSpaceOnUse"><stop offset=".8" class="hcvo9rclz"/><stop offset="1" class="aouzsrgog"/></radialGradient><radialGradient id="i5OsGie" cx="0" cy="0" r="1" gradientTransform="matrix(2.94774 2.48038 -2.63083 3.12654 15.676 20.873)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="kowu5e5ac"/><stop offset="1" class="sk_-w8f9q"/></radialGradient><radialGradient id="isklnqb" cx="0" cy="0" r="1" gradientTransform="rotate(105.599 5.96 20.655)scale(5.89475 5.01685)" gradientUnits="userSpaceOnUse"><stop class="vd5_wxb_c"/><stop offset="1" class="ixksk13nq"/></radialGradient><radialGradient id="iiz6DMc" cx="0" cy="0" r="1" gradientTransform="rotate(131.539 8.933 17.624)scale(5.60792 3.71093)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="ay7e0ccwy"/><stop offset=".926" class="e5_k9tbvh"/></radialGradient><radialGradient id="iam0Xxb" cx="0" cy="0" r="1" gradientTransform="rotate(-92.086 25.96 -.472)scale(4.72188 4.75751)" gradientUnits="userSpaceOnUse"><stop offset=".851" class="d19p-bchf"/><stop offset=".929" class="so-cdsi-z"/></radialGradient><linearGradient id="iDYOcRc" x1="17.054" x2="14.465" y1="4.297" y2="6.843" gradientUnits="userSpaceOnUse"><stop class="cweie4cnk"/><stop offset="1" class="v05dmuh-v"/></linearGradient><linearGradient id="iYXdFSN" x1="13" x2="6.572" y1="9.945" y2="15.065" gradientUnits="userSpaceOnUse"><stop class="uhjnysbhq"/><stop offset="1" class="nln46izyc"/></linearGradient><linearGradient id="i2pnNjJ" x1="20.577" x2="23.646" y1="9" y2="14" gradientUnits="userSpaceOnUse"><stop class="co70-uzsf"/><stop offset=".492" class="ei1k3obco"/><stop offset="1" class="co70-uzsf"/></linearGradient><linearGradient id="iYnGicd" x1="19" x2="14.409" y1="19.675" y2="23.332" gradientUnits="userSpaceOnUse"><stop class="v0xcpxbum"/><stop offset="1" class="l90x68blj"/></linearGradient><linearGradient id="iSWueDb" x1="5.696" x2="11.149" y1="23.612" y2="27.583" gradientUnits="userSpaceOnUse"><stop class="d-qh370ov"/><stop offset=".213" class="ckg96ab_f"/><stop offset=".806" class="tpxhj3bwc"/><stop offset="1" class="nvyr_0bok"/></linearGradient><linearGradient id="ixWz6ze" x1="5.361" x2="11" y1="24.531" y2="28.375" gradientUnits="userSpaceOnUse"><stop class="h68pcvbge"/><stop offset="1" class="e63bi9bxf"/></linearGradient><linearGradient id="ivifywd" x1="27.829" x2="23.545" y1="20.625" y2="25.495" gradientUnits="userSpaceOnUse"><stop class="q9relispo"/><stop offset=".495" class="x7x3c4bmr"/><stop offset="1" class="q8_a2y5nm"/></linearGradient><filter id="ibKnJnc" width="36" height="34" x="2" y="-4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="8" dy="-6"/><feGaussianBlur stdDeviation="4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.215686 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13875"/></filter><filter id="i2Xwu8c" width="4.008" height="3.6" x="13.7" y="3.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13875" stdDeviation=".1"/></filter><filter id="iEZwucc" width="7.6" height="7.6" x="5.7" y="8.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13875" stdDeviation=".1"/></filter><filter id="i5JwUrz" width="5.8" height="5.8" x="19.6" y="8.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13875" stdDeviation=".1"/></filter><filter id="io20DyC" width="5.75" height="5.75" x="13.625" y="18.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13875" stdDeviation=".125"/></filter><filter id="iPxT50b" width="6.798" height="6.201" x="4.502" y="22.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13875" stdDeviation=".1"/></filter><filter id="iTbUHvg" width="5.506" height="6.47" x="23.625" y="20.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13875" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:new-moon" /></template>
<style>
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

.ay7e0ccwy {
  stop-color: var(--svg-color--9979ba, #9979BA);
  stop-opacity: 0;
}

.az0fwjbyp {
  cx: 9.5px;
  cy: 12.5px;
  r: 3.5px;
}

.bjdh0qbfw {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.704 7.05c.962 0 1.754-.688 1.754-1.55s-.792-1.55-1.754-1.55c-.963 0-1.754.688-1.754 1.55s.791 1.55 1.754 1.55Z");
}

.ckg96ab_f {
  stop-color: var(--svg-color--372447, #372447);
  stop-opacity: 0;
}

.cmiujyb_i {
  d: path("M28.955 21.316a14.04 14.04 0 0 1-4.073 5.507a3.5 3.5 0 0 1 4.074-5.507");
}

.co70-uzsf {
  stop-color: var(--svg-color--a57cd3, #A57CD3);
}

.cweie4cnk {
  stop-color: var(--svg-color--7b52a5, #7B52A5);
}

.d-qh370ov {
  stop-color: var(--svg-color--372447, #372447);
}

.d19p-bchf {
  stop-color: var(--svg-color--663f90, #663F90);
  stop-opacity: 0;
}

.dgz4yubdl {
  cx: 15.704px;
  cy: 5.5px;
  rx: 1.704px;
  ry: 1.5px;
}

.e5_k9tbvh {
  stop-color: var(--svg-color--9979ba, #9979BA);
}

.e63bi9bxf {
  stop-color: var(--svg-color--64497d, #64497D);
}

.ei1k3obco {
  stop-color: var(--svg-color--a57cd3, #A57CD3);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fw_pw5b_o {
  stop-color: var(--svg-color--9e77c9, #9E77C9);
}

.g4k3q7cmw {
  cx: 22.5px;
  cy: 11.5px;
  r: 2.5px;
}

.gql29xbsu {
  stop-color: var(--svg-color--8260a1, #8260A1);
}

.gtckmub7n {
  stop-color: var(--svg-color--494054, #494054);
}

.h2-o4in6u {
  cx: 16.5px;
  cy: 21.5px;
  r: 2.5px;
}

.h68pcvbge {
  stop-color: var(--svg-color--50425c, #50425C);
}

.hcvo9rclz {
  stop-color: var(--svg-color--64398c, #64398C);
  stop-opacity: 0;
}

.ixksk13nq {
  stop-color: var(--svg-color--9464bf, #9464BF);
}

.j9bg4_aho {
  stop-color: var(--svg-color--8e61b7, #8E61B7);
}

.jdhr3wbpz {
  stop-color: var(--svg-color--494054, #494054);
  stop-opacity: 0;
}

.k1ycr2tfc {
  stop-color: var(--svg-color--6d4a8d, #6D4A8D);
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

.p_lhof22o {
  stop-color: var(--svg-color--6d3d9c, #6D3D9C);
}

.p5hlz22-w {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M28.72 21.266c-.887 2.158-2.145 3.946-3.922 5.406c-.548-.618-.798-1.28-.798-2.172a3.5 3.5 0 0 1 3.5-3.5c.52 0 .777.063 1.22.266Z");
}

.pspj-mbwr {
  stop-color: var(--svg-color--664581, #664581);
  stop-opacity: 0;
}

.q8_a2y5nm {
  stop-color: var(--svg-color--7f58a9, #7F58A9);
}

.q9relispo {
  stop-color: var(--svg-color--7045a0, #7045A0);
}

.qletn-b4z {
  stop-color: var(--svg-color--614879, #614879);
}

.sk_-w8f9q {
  stop-color: var(--svg-color--664289, #664289);
}

.so-cdsi-z {
  stop-color: var(--svg-color--663f90, #663F90);
}

.tpxhj3bwc {
  stop-color: var(--svg-color--654e72, #654E72);
  stop-opacity: 0;
}

.uhjnysbhq {
  stop-color: var(--svg-color--603d83, #603D83);
}

.v05dmuh-v {
  stop-color: var(--svg-color--875cb4, #875CB4);
}

.v0xcpxbum {
  stop-color: var(--svg-color--683b92, #683B92);
}

.vd5_wxb_c {
  stop-color: var(--svg-color--875cb5, #875CB5);
}

.vdekk1bcl {
  stop-color: var(--svg-color--614879, #614879);
  stop-opacity: 0;
}

.vfu63obhs {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M10.267 28.578a14.05 14.05 0 0 1-5.439-4.406C5.47 23.359 6.385 23 7.5 23a3.5 3.5 0 0 1 3.5 3.5c0 .852-.227 1.471-.733 2.078Z");
}

.wecidrbdj {
  stop-color: var(--svg-color--b085d8, #B085D8);
}

.x12ziqbrn {
  stop-color: var(--svg-color--664581, #664581);
}

.x7x3c4bmr {
  stop-color: var(--svg-color--7045a0, #7045A0);
  stop-opacity: 0;
}

.xhmqgdkdw {
  stop-color: var(--svg-color--8b72a3, #8B72A3);
  stop-opacity: 0;
}

.xn282acyu {
  stop-color: var(--svg-color--60427c, #60427C);
}

.xrwbo5xlm {
  cx: 22.5px;
  cy: 11.5px;
  r: 2.6px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.yuoatmb7a {
  stop-color: var(--svg-color--79529b, #79529B);
}

.z_043u7tj {
  stop-color: var(--svg-color--8260a1, #8260A1);
  stop-opacity: 0;
}

</style>
