<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect transform="rotate(70.668 28.626 17.267)" class="vk15-ibht"/><rect fill="url(#iPSREbd)" transform="rotate(70.668 28.626 17.267)" class="cn5llcbit"/><rect fill="url(#iUvvXDb)" transform="rotate(70.668 28.626 17.267)" class="cn5llcbit"/><rect fill="url(#ie9iD7c)" class="la8okvyix"/><rect fill="url(#iL9mZTd)" class="la8okvyix"/><rect fill="url(#i5R5mHV)" class="la8okvyix"/><rect fill="url(#isbB6zb)" class="la8okvyix"/><g filter="url(#iu1bBDb)"><path fill="url(#iHeeNWd)" class="nad-mhqqr"/></g><path fill="url(#iZGFJIV)" class="nad-mhqqr"/><path fill="url(#iENFqHc)" class="nad-mhqqr"/><path fill="url(#idEe3zb)" class="qhhf77j9u"/><path fill="url(#i5TQyXd)" class="qhhf77j9u"/><path fill="url(#ig7LTud)" class="qhhf77j9u"/><path fill="url(#i2rb5ld)" class="pneioccjs"/><path fill="url(#iPSa2Ne)" class="pneioccjs"/><path fill="url(#i0EyQke)" class="pneioccjs"/><path fill="url(#itrqsWc)" class="pneioccjs"/><path fill="url(#iz498Nd)" class="pneioccjs"/><path fill="url(#iegnAxb)" class="pneioccjs"/><path fill="url(#ijXf6Sz)" class="jtfp82xfn"/><path fill="url(#iv56MFb)" class="jtfp82xfn"/><path fill="url(#i8npR1c)" class="jtfp82xfn"/><g filter="url(#i5HqYde)"><path fill="url(#ih8RSAf)" class="vcbj9bbvo"/></g><g filter="url(#i2Siitc)"><path fill="url(#incng3c)" class="qn8-_xb6z"/></g><g filter="url(#ijQsgjD)"><path fill="url(#i8hWRGc)" class="ngj226jrw"/></g><g filter="url(#iE8PTYd)"><path fill="url(#i3beLVd)" class="vsprw77wr"/></g><defs><linearGradient id="iPSREbd" x1="36.551" x2="34.993" y1="24.75" y2="24.795" gradientUnits="userSpaceOnUse"><stop class="rmdl0mm2h"/><stop offset="1" class="qc-ba4byl"/></linearGradient><linearGradient id="ie9iD7c" x1="14.813" x2="19.83" y1="20.829" y2="20.829" gradientUnits="userSpaceOnUse"><stop class="qss1fhl7k"/><stop offset="1" class="bzpr_3b_c"/></linearGradient><linearGradient id="i5R5mHV" x1="19.83" x2="19.83" y1="7.563" y2="14.454" gradientUnits="userSpaceOnUse"><stop class="w5-l77bxg"/><stop offset="1" class="zus49me4c"/></linearGradient><linearGradient id="iHeeNWd" x1="33.415" x2="18.221" y1="7.313" y2="19.415" gradientUnits="userSpaceOnUse"><stop class="ihn_unbcq"/><stop offset="1" class="liwehzerd"/></linearGradient><linearGradient id="iZGFJIV" x1="2.432" x2="4.676" y1="16.017" y2="16.017" gradientUnits="userSpaceOnUse"><stop class="ktr8osffa"/><stop offset="1" class="n8-2wtbuk"/></linearGradient><linearGradient id="idEe3zb" x1="10.555" x2="10.555" y1="24.891" y2="16.897" gradientUnits="userSpaceOnUse"><stop class="b36qozbof"/><stop offset="1" class="v8auszjoy"/></linearGradient><linearGradient id="i5TQyXd" x1="9.401" x2="8.076" y1="17.929" y2="17.929" gradientUnits="userSpaceOnUse"><stop class="dj1iv0dej"/><stop offset="1" class="h_43gu_fw"/></linearGradient><linearGradient id="i2rb5ld" x1="17.633" x2="17.633" y1="28.172" y2="17.163" gradientUnits="userSpaceOnUse"><stop class="aw8qrjbpp"/><stop offset="1" class="c3lo31rgp"/></linearGradient><linearGradient id="i0EyQke" x1="16.438" x2="15.065" y1="17.163" y2="17.163" gradientUnits="userSpaceOnUse"><stop class="imzhmac3x"/><stop offset="1" class="oiusqnb7o"/></linearGradient><linearGradient id="iz498Nd" x1="11.625" x2="14.413" y1="11.5" y2="16.528" gradientUnits="userSpaceOnUse"><stop class="hs2s0pyxo"/><stop offset="1" class="k-sgi4jnp"/></linearGradient><linearGradient id="iegnAxb" x1="8.625" x2="10.938" y1="21.063" y2="20.938" gradientUnits="userSpaceOnUse"><stop class="g6trdebkt"/><stop offset="1" class="lsnk7pbxr"/></linearGradient><linearGradient id="ijXf6Sz" x1="22.301" x2="26.302" y1="21.329" y2="20.772" gradientUnits="userSpaceOnUse"><stop class="fqzrp1ehz"/><stop offset="1" class="md1w_9lgm"/></linearGradient><linearGradient id="ih8RSAf" x1="6.885" x2="6.885" y1="10.967" y2="26.049" gradientUnits="userSpaceOnUse"><stop class="sih9xob4p"/><stop offset="1" class="n026h-4lj"/></linearGradient><linearGradient id="incng3c" x1="13.698" x2="13.698" y1="8.766" y2="26.554" gradientUnits="userSpaceOnUse"><stop class="m7xunidah"/><stop offset="1" class="kt333ccuz"/></linearGradient><linearGradient id="i8hWRGc" x1="21.352" x2="21.352" y1="5.235" y2="28.98" gradientUnits="userSpaceOnUse"><stop class="g4cqbacat"/><stop offset="1" class="lwhrzbbvj"/></linearGradient><linearGradient id="i3beLVd" x1="28.119" x2="28.119" y1="7.266" y2="28.514" gradientUnits="userSpaceOnUse"><stop class="qokjgbcnu"/><stop offset="1" class="mk0dts3mn"/></linearGradient><radialGradient id="iUvvXDb" cx="0" cy="0" r="1" gradientTransform="rotate(-65.982 41.876 -7.797)scale(1.80013 4.07406)" gradientUnits="userSpaceOnUse"><stop class="sk1v0d65m"/><stop offset="1" class="ndhos_tkg"/></radialGradient><radialGradient id="iL9mZTd" cx="0" cy="0" r="1" gradientTransform="matrix(0 19.7805 -10.7947 0 20.323 8.423)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="gr-z8tbuq"/><stop offset="1" class="sniln6l-o"/><stop offset="1" class="qn7h99d7k"/></radialGradient><radialGradient id="isbB6zb" cx="0" cy="0" r="1" gradientTransform="matrix(0 18.6391 -8.29832 0 19.83 8.423)" gradientUnits="userSpaceOnUse"><stop offset=".958" class="naexo5b8y"/><stop offset="1" class="apeimfb1b"/></radialGradient><radialGradient id="iENFqHc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.41485 3.40558 -4.95105 -3.51073 29.576 5.984)" gradientUnits="userSpaceOnUse"><stop class="zs58vtn7z"/><stop offset="1" class="p89bxfxiy"/></radialGradient><radialGradient id="ig7LTud" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.3638 -10.4214 0 6.365 10.967)" gradientUnits="userSpaceOnUse"><stop offset=".789" class="sv5tawk0v"/><stop offset="1" class="zsj02cceh"/></radialGradient><radialGradient id="iPSa2Ne" cx="0" cy="0" r="1" gradientTransform="matrix(0 18.0323 -10.7984 0 13.291 8.423)" gradientUnits="userSpaceOnUse"><stop offset=".789" class="pdof6qbxo"/><stop offset="1" class="vc2ezub_b"/></radialGradient><radialGradient id="itrqsWc" cx="0" cy="0" r="1" gradientTransform="matrix(-.48591 17.47465 -7.74862 -.21546 13.313 8.594)" gradientUnits="userSpaceOnUse"><stop offset=".952" class="bpultfude"/><stop offset="1" class="okkh79bje"/></radialGradient><radialGradient id="iv56MFb" cx="0" cy="0" r="1" gradientTransform="matrix(0 18.7256 -10.1586 0 27.276 8.423)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="pg5w-8okl"/><stop offset="1" class="ejtk3whrm"/></radialGradient><radialGradient id="i8npR1c" cx="0" cy="0" r="1" gradientTransform="matrix(0 17.645 -7.80931 0 26.812 8.423)" gradientUnits="userSpaceOnUse"><stop offset=".911" class="vj1ltybon"/><stop offset="1" class="azj-k76oe"/></radialGradient><filter id="iu1bBDb" width="27.985" height="23.056" x="2.432" y="3.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.568627 0 0 0 0 0.458824 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5729"/></filter><filter id="i5HqYde" width="6.044" height="15.266" x="3.863" y="9.467" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5729" stdDeviation=".75"/></filter><filter id="i2Siitc" width="6.044" height="17.467" x="10.676" y="7.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5729" stdDeviation=".75"/></filter><filter id="ijQsgjD" width="6.044" height="22.312" x="18.33" y="3.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5729" stdDeviation=".75"/></filter><filter id="iE8PTYd" width="5.613" height="20.281" x="25.312" y="5.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5729" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:oncoming-fist-medium" /></template>
<style>
.apeimfb1b {
  stop-color: var(--svg-color--a06594, #A06594);
}

.aw8qrjbpp {
  stop-color: var(--svg-color--804d5f, #804D5F);
}

.azj-k76oe {
  stop-color: var(--svg-color--a16794, #A16794);
}

.b36qozbof {
  stop-color: var(--svg-color--916364, #916364);
}

.bpultfude {
  stop-color: var(--svg-color--995d89, #995D89);
  stop-opacity: 0;
}

.bzpr_3b_c {
  stop-color: var(--svg-color--865b58, #865B58);
  stop-opacity: 0;
}

.c3lo31rgp {
  stop-color: var(--svg-color--804d5f, #804D5F);
  stop-opacity: 0;
}

.cn5llcbit {
  width: 7.66px;
  height: 16.279px;
  x: 28.626px;
  y: 17.267px;
  rx: 3.83px;
}

.dj1iv0dej {
  stop-color: var(--svg-color--683f3b, #683F3B);
}

.ejtk3whrm {
  stop-color: var(--svg-color--925079, #925079);
}

.fqzrp1ehz {
  stop-color: var(--svg-color--8b5852, #8B5852);
}

.ft5dv1b6b {
  fill: none;
}

.g4cqbacat {
  stop-color: var(--svg-color--d1a78f, #D1A78F);
}

.g6trdebkt {
  stop-color: var(--svg-color--805852, #805852);
}

.gr-z8tbuq {
  stop-color: var(--svg-color--97567e, #97567E);
  stop-opacity: 0;
}

.h_43gu_fw {
  stop-color: var(--svg-color--683f3b, #683F3B);
  stop-opacity: 0;
}

.hs2s0pyxo {
  stop-color: var(--svg-color--9b7465, #9B7465);
}

.ihn_unbcq {
  stop-color: var(--svg-color--c79e82, #C79E82);
}

.imzhmac3x {
  stop-color: var(--svg-color--7e524e, #7E524E);
}

.jtfp82xfn {
  d: path("M23.459 24.285a3.83 3.83 0 0 0 6.957-2.21v-9.822a3.83 3.83 0 0 0-5.958-3.184c-.975.653-.798 2.01-.798 3.184V23.06c0 .428-.07.84-.201 1.226");
}

.k-sgi4jnp {
  stop-color: var(--svg-color--9f7867, #9F7867);
  stop-opacity: 0;
}

.kt333ccuz {
  stop-color: var(--svg-color--c19987, #C19987);
  stop-opacity: 0;
}

.ktr8osffa {
  stop-color: var(--svg-color--94735f, #94735F);
}

.la8okvyix {
  width: 7.66px;
  height: 18.465px;
  x: 16px;
  y: 8.423px;
  rx: 3.83px;
}

.liwehzerd {
  stop-color: var(--svg-color--9a7364, #9A7364);
}

.lsnk7pbxr {
  stop-color: var(--svg-color--805852, #805852);
  stop-opacity: 0;
}

.lwhrzbbvj {
  stop-color: var(--svg-color--d1a78f, #D1A78F);
  stop-opacity: 0;
}

.m7xunidah {
  stop-color: var(--svg-color--c19987, #C19987);
}

.md1w_9lgm {
  stop-color: var(--svg-color--8b5852, #8B5852);
  stop-opacity: 0;
}

.mk0dts3mn {
  stop-color: var(--svg-color--d1a88e, #D1A88E);
  stop-opacity: 0;
}

.n026h-4lj {
  stop-color: var(--svg-color--b58d7f, #B58D7F);
  stop-opacity: 0;
}

.n8-2wtbuk {
  stop-color: var(--svg-color--94735f, #94735F);
  stop-opacity: 0;
}

.nad-mhqqr {
  d: path("M2.432 12.711v8.35a3.83 3.83 0 0 0 6.97 2.194a3.831 3.831 0 0 0 6.79 1.003a3.831 3.831 0 0 0 7.267.027a3.83 3.83 0 0 0 6.957-2.21V9.359a4.25 4.25 0 0 0-4.46-4.245l-1.633.08a5.47 5.47 0 0 1-3.088-.776a4.1 4.1 0 0 0-3.883-.186l-1.297.621a6 6 0 0 1-2.59.588H12.07a4 4 0 0 0-2.42.814L8.002 7.51c-.37.28-.796.566-1.228.734L5 8.985c-1.703.691-2.568 2.078-2.568 3.726");
}

.naexo5b8y {
  stop-color: var(--svg-color--a06594, #A06594);
  stop-opacity: 0;
}

.ndhos_tkg {
  stop-color: var(--svg-color--9a6a6a, #9A6A6A);
  stop-opacity: 0;
}

.ngj226jrw {
  d: path("m19.83 5.235l.454.172a4 4 0 0 1 2.59 3.743v13.876a1.522 1.522 0 0 1-3.044 0z");
}

.oiusqnb7o {
  stop-color: var(--svg-color--7e524e, #7E524E);
  stop-opacity: 0;
}

.okkh79bje {
  stop-color: var(--svg-color--995d89, #995D89);
}

.p89bxfxiy {
  stop-color: var(--svg-color--c8a182, #C8A182);
  stop-opacity: 0;
}

.pdof6qbxo {
  stop-color: var(--svg-color--98567e, #98567E);
  stop-opacity: 0;
}

.pg5w-8okl {
  stop-color: var(--svg-color--925079, #925079);
  stop-opacity: 0;
}

.pneioccjs {
  d: path("M13.046 8.423a3.83 3.83 0 0 0-3.83 3.83v9.82a3.83 3.83 0 0 0 6.976 2.185a3.8 3.8 0 0 1-.192-1.2V12.254c0-.642.158-1.248.438-1.78a3.83 3.83 0 0 0-3.392-2.05");
}

.qc-ba4byl {
  stop-color: var(--svg-color--9b5d89, #9B5D89);
  stop-opacity: 0;
}

.qhhf77j9u {
  d: path("M9.216 13.08c0-.466-.15-.931-.507-1.229a3.83 3.83 0 0 0-6.277 2.946v6.265a3.83 3.83 0 0 0 6.97 2.193a3.8 3.8 0 0 1-.186-1.181z");
}

.qn7h99d7k {
  stop-color: var(--svg-color--97567e, #97567E);
}

.qn8-_xb6z {
  d: path("m12.176 8.766l.13.037a4 4 0 0 1 2.914 3.85v9.058a1.522 1.522 0 1 1-3.044 0z");
}

.qokjgbcnu {
  stop-color: var(--svg-color--d1a88e, #D1A88E);
}

.qss1fhl7k {
  stop-color: var(--svg-color--865b58, #865B58);
}

.rmdl0mm2h {
  stop-color: var(--svg-color--9b5d89, #9B5D89);
}

.sih9xob4p {
  stop-color: var(--svg-color--b58d7f, #B58D7F);
}

.sk1v0d65m {
  stop-color: var(--svg-color--9a6a6a, #9A6A6A);
}

.sniln6l-o {
  stop-color: var(--svg-color--783d64, #783D64);
}

.sv5tawk0v {
  stop-color: var(--svg-color--9b608a, #9B608A);
  stop-opacity: 0;
}

.v8auszjoy {
  stop-color: var(--svg-color--916364, #916364);
  stop-opacity: 0;
}

.vc2ezub_b {
  stop-color: var(--svg-color--98567e, #98567E);
}

.vcbj9bbvo {
  d: path("M5.363 10.968a3.97 3.97 0 0 1 3.045 3.858v6.885a1.522 1.522 0 1 1-3.044 0z");
}

.vj1ltybon {
  stop-color: var(--svg-color--a16794, #A16794);
  stop-opacity: 0;
}

.vk15-ibht {
  width: 7.66px;
  height: 16.279px;
  x: 28.626px;
  y: 17.267px;
  fill: var(--svg-color--895065, #895065);
  rx: 3.83px;
}

.vsprw77wr {
  d: path("m26.812 7.266l.076.03a4 4 0 0 1 2.538 3.723v12.222a1.307 1.307 0 1 1-2.613 0z");
}

.w5-l77bxg {
  stop-color: var(--svg-color--ad8571, #AD8571);
}

.zs58vtn7z {
  stop-color: var(--svg-color--c8a182, #C8A182);
}

.zsj02cceh {
  stop-color: var(--svg-color--9b608a, #9B608A);
}

.zus49me4c {
  stop-color: var(--svg-color--ad8571, #AD8571);
  stop-opacity: 0;
}

</style>
