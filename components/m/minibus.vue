<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i9wqCxc)"><path fill="url(#imSKPHe)" class="ffbqk8bhq"/><path fill="url(#ilWNmPW)" class="ffbqk8bhq"/></g><path fill="url(#iz0O0bd)" class="d_83occ5h"/><path fill="url(#ijKMIyd)" clip-rule="evenodd" class="fbdb763mg"/><path fill="url(#iJWTHWd)" class="iar58nc3i"/><path fill="url(#ihFzLqd)" class="iar58nc3i"/><path fill="url(#iHONytb)" class="iar58nc3i"/><path fill="url(#ieLdfDJ)" class="iar58nc3i"/><g filter="url(#i3lT5fd)"><path fill="url(#ic42VUd)" class="yqlzk-blr"/><path fill="url(#idVdfmb)" class="yqlzk-blr"/></g><g filter="url(#iuKyyDb)"><rect fill="url(#iql0MGt)" class="je_49zb2l"/><rect fill="url(#iWkiRWQ)" class="je_49zb2l"/></g><path fill="url(#iB2ZMoe)" clip-rule="evenodd" class="u0kdx_b9m"/><g filter="url(#iDjzPhr)"><circle fill="url(#iVXRvvc)" class="zmo7ymbuc"/></g><g filter="url(#iNTc3Uc)"><circle fill="url(#iMLnAid)" class="xyhe28b1i"/></g><g filter="url(#iQMtUYm)"><circle fill="url(#iFuUKgb)" transform="matrix(-1 0 0 1 8.594 26.632)" class="mraanob9d"/><circle fill="url(#ifWizAe)" transform="matrix(-1 0 0 1 8.594 26.632)" class="mraanob9d"/></g><g filter="url(#itScgJd)"><circle fill="url(#iFuUKgb)" transform="matrix(-1 0 0 1 23.683 26.632)" class="mraanob9d"/><circle fill="url(#ifWizAe)" transform="matrix(-1 0 0 1 23.683 26.632)" class="mraanob9d"/></g><defs><linearGradient id="imSKPHe" x1="3.682" x2="22.36" y1="27.377" y2="21.824" gradientUnits="userSpaceOnUse"><stop class="uuuldaclm"/><stop offset="1" class="owxp8kb-s"/></linearGradient><linearGradient id="ilWNmPW" x1="16" x2="16" y1="11.111" y2="12.737" gradientUnits="userSpaceOnUse"><stop class="iqz51y3-q"/><stop offset="1" class="f1ij0hbnb"/></linearGradient><linearGradient id="ijKMIyd" x1="1.967" x2="2.746" y1="22.014" y2="24.228" gradientUnits="userSpaceOnUse"><stop class="bjim2370a"/><stop offset="1" class="r94-4otbq"/></linearGradient><linearGradient id="iJWTHWd" x1="18.01" x2="29.927" y1="15.561" y2="15.561" gradientUnits="userSpaceOnUse"><stop class="so27o3bam"/><stop offset="1" class="cc0hlfb-b"/></linearGradient><linearGradient id="ihFzLqd" x1="17.72" x2="19.181" y1="18.072" y2="18.072" gradientUnits="userSpaceOnUse"><stop class="p5rs84byj"/><stop offset="1" class="n2xtjop5u"/></linearGradient><linearGradient id="iHONytb" x1="23.969" x2="23.969" y1="13.049" y2="15.011" gradientUnits="userSpaceOnUse"><stop offset=".125" class="ui_8u6z3l"/><stop offset="1" class="ryme-zv9x"/></linearGradient><linearGradient id="ic42VUd" x1="11.474" x2="4.496" y1="11.821" y2="19.675" gradientUnits="userSpaceOnUse"><stop class="a74tmo3pm"/><stop offset="1" class="maaw98b9e"/></linearGradient><linearGradient id="idVdfmb" x1="2.234" x2="4.275" y1="17.604" y2="17.604" gradientUnits="userSpaceOnUse"><stop class="cq5_47bhh"/><stop offset="1" class="mxulxgbas"/></linearGradient><linearGradient id="iql0MGt" x1="17.929" x2="10.953" y1="11.821" y2="18.006" gradientUnits="userSpaceOnUse"><stop class="zvud-3bmj"/><stop offset="1" class="maaw98b9e"/></linearGradient><linearGradient id="iWkiRWQ" x1="10.652" x2="12.259" y1="17.604" y2="17.604" gradientUnits="userSpaceOnUse"><stop class="cq5_47bhh"/><stop offset="1" class="mxulxgbas"/></linearGradient><linearGradient id="iB2ZMoe" x1="2.073" x2="29.927" y1="21.007" y2="21.007" gradientUnits="userSpaceOnUse"><stop offset=".015" class="z2fn0kazp"/><stop offset=".053" class="jnfvfcc4r"/><stop offset=".945" class="nkz7q36of"/><stop offset=".974" class="cp3qu_qrx"/></linearGradient><linearGradient id="iVXRvvc" x1="10.468" x2="7.153" y1="24.081" y2="30" gradientUnits="userSpaceOnUse"><stop class="rvrczdb2a"/><stop offset="1" class="rkw0441jl"/></linearGradient><linearGradient id="iMLnAid" x1="25.557" x2="22.241" y1="24.081" y2="30" gradientUnits="userSpaceOnUse"><stop class="rvrczdb2a"/><stop offset="1" class="rkw0441jl"/></linearGradient><filter id="i9wqCxc" width="29.854" height="16.916" x="1.073" y="10.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.682353 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10038"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.52549 0 0 0 0 0.513726 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10038" result="effect2_innerShadow_18_10038"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.972549 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_10038" result="effect3_innerShadow_18_10038"/></filter><filter id="i3lT5fd" width="7.33" height="6.023" x="1.691" y="13.049" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy="1"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.666667 0 0 0 0 0.905882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10038"/></filter><filter id="iuKyyDb" width="5.986" height="5.773" x="10.012" y="13.049" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy=".75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.666667 0 0 0 0 0.905882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10038"/></filter><filter id="iDjzPhr" width="7.735" height="6.735" x="4.727" y="23.265" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.117647 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10038"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.243137 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10038" result="effect2_innerShadow_18_10038"/></filter><filter id="iNTc3Uc" width="7.735" height="6.735" x="19.815" y="23.265" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.117647 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10038"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.243137 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10038" result="effect2_innerShadow_18_10038"/></filter><filter id="iQMtUYm" width="3.152" height="3.152" x="6.818" y="25.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.109804 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_10038"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_10038" result="shape"/></filter><filter id="itScgJd" width="3.152" height="3.152" x="21.907" y="25.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.109804 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_10038"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_10038" result="shape"/></filter><radialGradient id="iz0O0bd" cx="0" cy="0" r="1" gradientTransform="matrix(1.5083 -1.125 .89687 1.20244 28.419 23.65)" gradientUnits="userSpaceOnUse"><stop class="v1r9mlbcs"/><stop offset="1" class="b9qh4g8tz"/></radialGradient><radialGradient id="ieLdfDJ" cx="0" cy="0" r="1" gradientTransform="matrix(-5.62506 4.96754 -1.34713 -1.52545 32.13 13.44)" gradientUnits="userSpaceOnUse"><stop offset=".609" class="n9zmzzqmm"/><stop offset="1" class="obsms1bae"/></radialGradient><radialGradient id="iFuUKgb" cx="0" cy="0" r="1" gradientTransform="rotate(46.381 -.571 .474)scale(2.47415 2.14575)" gradientUnits="userSpaceOnUse"><stop class="uy-elybtc"/><stop offset=".8" class="je7vqqg0r"/></radialGradient><radialGradient id="ifWizAe" cx="0" cy="0" r="1" gradientTransform="rotate(-125.15 1.612 .656)scale(1.43809 2.9603)" gradientUnits="userSpaceOnUse"><stop class="fdomx0bpj"/><stop offset="1" class="li9m4eegn"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:minibus" /></template>
<style>
.a74tmo3pm {
  stop-color: var(--svg-color--43bcfc, #43BCFC);
}

.b9qh4g8tz {
  stop-color: var(--svg-color--d80a52, #D80A52);
}

.bjim2370a {
  stop-color: var(--svg-color--d39131, #D39131);
}

.cc0hlfb-b {
  stop-color: var(--svg-color--52e4ff, #52E4FF);
}

.cp3qu_qrx {
  stop-color: var(--svg-color--b288fa, #B288FA);
}

.cq5_47bhh {
  stop-color: var(--svg-color--4decff, #4DECFF);
}

.d_83occ5h {
  d: path("M29.927 22.042v1.975h-.958a.988.988 0 1 1 0-1.975z");
}

.f1ij0hbnb {
  stop-color: var(--svg-color--cccccd, #CCCCCD);
  stop-opacity: 0;
}

.fbdb763mg {
  fill-rule: evenodd;
  d: path("M2.073 25.005v-2.991c.549.01.99.458.99 1.009v.973c0 .55-.441.999-.99 1.009");
}

.fdomx0bpj {
  stop-color: var(--svg-color--e0c7f5, #E0C7F5);
}

.ffbqk8bhq {
  d: path("M6.42 12.058a2 2 0 0 1 1.702-.947H28.51c.987 0 1.418.777 1.418 1.468v13.049a1.4 1.4 0 0 1-1.402 1.4H3.566c-.851 0-1.493-.723-1.493-1.496v-5.609c0-.558.156-1.105.45-1.58z");
}

.ft5dv1b6b {
  fill: none;
}

.iar58nc3i {
  d: path("M29.927 13.049v5.023H19.01a1 1 0 0 1-1-1V14.05a1 1 0 0 1 1-1z");
}

.iqz51y3-q {
  stop-color: var(--svg-color--cccccd, #CCCCCD);
}

.je_49zb2l {
  width: 4.986px;
  height: 5.023px;
  x: 11.012px;
  y: 13.049px;
  rx: 1px;
}

.je7vqqg0r {
  stop-color: var(--svg-color--cabfd4, #CABFD4);
}

.jnfvfcc4r {
  stop-color: var(--svg-color--8169c1, #8169C1);
}

.li9m4eegn {
  stop-color: var(--svg-color--e0c7f5, #E0C7F5);
  stop-opacity: 0;
}

.maaw98b9e {
  stop-color: var(--svg-color--42e0ff, #42E0FF);
}

.mraanob9d {
  r: 1.176px;
}

.mxulxgbas {
  stop-color: var(--svg-color--4decff, #4DECFF);
  stop-opacity: 0;
}

.n2xtjop5u {
  stop-color: var(--svg-color--4fffff, #4FFFFF);
  stop-opacity: 0;
}

.n9zmzzqmm {
  stop-color: var(--svg-color--51e0ff, #51E0FF);
}

.nkz7q36of {
  stop-color: var(--svg-color--9a6fe2, #9A6FE2);
}

.obsms1bae {
  stop-color: var(--svg-color--51e0ff, #51E0FF);
  stop-opacity: 0;
}

.owxp8kb-s {
  stop-color: var(--svg-color--e7d6f4, #E7D6F4);
}

.p5rs84byj {
  stop-color: var(--svg-color--4fffff, #4FFFFF);
}

.r94-4otbq {
  stop-color: var(--svg-color--b78619, #B78619);
}

.rkw0441jl {
  stop-color: var(--svg-color--50295e, #50295E);
}

.rvrczdb2a {
  stop-color: var(--svg-color--55275f, #55275F);
}

.ryme-zv9x {
  stop-color: var(--svg-color--33bdff, #33BDFF);
  stop-opacity: 0;
}

.so27o3bam {
  stop-color: var(--svg-color--4de4ff, #4DE4FF);
}

.u0kdx_b9m {
  fill-rule: evenodd;
  d: path("M2.073 21.007v-1.084a3 3 0 0 1 .124-.854h27.73v1.938z");
}

.ui_8u6z3l {
  stop-color: var(--svg-color--33bdff, #33BDFF);
}

.uuuldaclm {
  stop-color: var(--svg-color--cfc0db, #CFC0DB);
}

.uy-elybtc {
  stop-color: var(--svg-color--e8e4ef, #E8E4EF);
}

.v1r9mlbcs {
  stop-color: var(--svg-color--f02959, #F02959);
}

.xyhe28b1i {
  cx: 23.683px;
  cy: 26.632px;
  r: 3.368px;
}

.yqlzk-blr {
  d: path("m2.691 18.072l3.115-5.023H8.02a1 1 0 0 1 1 1v3.023a1 1 0 0 1-1 1z");
}

.z2fn0kazp {
  stop-color: var(--svg-color--5a5080, #5A5080);
}

.zmo7ymbuc {
  cx: 8.594px;
  cy: 26.632px;
  r: 3.368px;
}

.zvud-3bmj {
  stop-color: var(--svg-color--3ebcff, #3EBCFF);
}

</style>
