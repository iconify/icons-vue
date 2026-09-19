<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="sgrv4ghng"/><path stroke="url(#iX2CQyd)" class="wvog-5rsz"/><path stroke="url(#ibB9tBe)" class="wvog-5rsz"/><path stroke="url(#iHlYbXQ)" class="wvog-5rsz"/><path stroke="url(#iqg177b)" class="wvog-5rsz"/><path fill="url(#iYVeWKd)" class="cxa08z-au"/><path fill="url(#iBi0rwe)" class="cxa08z-au"/><path fill="url(#iuJUmTc)" class="eh8955buk"/><path fill="url(#ij3sqnc)" class="eh8955buk"/><circle fill="url(#iUA5q0d)" class="psl8i8bhe"/><g filter="url(#iH2W88d)"><path stroke="url(#iaFJfVc)" class="nfy-7kxrk"/></g><g filter="url(#ieDKy0d)"><path stroke="url(#i56wqjb)" class="yd785tn_v"/></g><path fill="url(#iTvMp1b)" class="vofrtbbyw"/><g filter="url(#iifCFBc)"><path stroke="url(#ikbdNCe)" class="q_sicnbmd"/></g><defs><radialGradient id="iX2CQyd" cx="0" cy="0" r="1" gradientTransform="matrix(.03125 2.0625 -.7032 .01066 28.046 6.156)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="pnxjkfbgy"/><stop offset="1" class="cxkgc8uxn"/></radialGradient><radialGradient id="ibB9tBe" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.45071 -.70932 0 29.687 4.3)" gradientUnits="userSpaceOnUse"><stop class="qxy567bxt"/><stop offset="1" class="a1cq-5bvj"/></radialGradient><radialGradient id="iHlYbXQ" cx="0" cy="0" r="1" gradientTransform="matrix(-.60937 4.875 -1.83253 -.22907 28.765 4.969)" gradientUnits="userSpaceOnUse"><stop offset=".798" class="pr2q1460i"/><stop offset="1" class="p61025b1c"/></radialGradient><radialGradient id="iqg177b" cx="0" cy="0" r="1" gradientTransform="rotate(-66.564 22.098 -16.88)scale(3.69293 1.10065)" gradientUnits="userSpaceOnUse"><stop class="btfgyqi2h"/><stop offset="1" class="cbp9kmbmi"/></radialGradient><radialGradient id="iBi0rwe" cx="0" cy="0" r="1" gradientTransform="rotate(133.727 -3.294 14.585)scale(1.49192 1.57047)" gradientUnits="userSpaceOnUse"><stop class="nqpl1bcpq"/><stop offset="1" class="q_y0tt9kh"/></radialGradient><radialGradient id="ij3sqnc" cx="0" cy="0" r="1" gradientTransform="rotate(132.726 14.449 7.776)scale(2.29714 2.77726)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="npi0c5uzj"/><stop offset="1" class="gia9-xb5c"/></radialGradient><radialGradient id="iUA5q0d" cx="0" cy="0" r="1" gradientTransform="matrix(-.36444 2.93603 -3.49722 -.4341 4.437 27.063)" gradientUnits="userSpaceOnUse"><stop offset=".495" class="lg9-e-buk"/><stop offset="1" class="n9dhynb5b"/></radialGradient><linearGradient id="iYVeWKd" x1="16" x2="18.718" y1="13.375" y2="16.025" gradientUnits="userSpaceOnUse"><stop class="jnbu_lh_w"/><stop offset="1" class="vsfyf-b1z"/></linearGradient><linearGradient id="iuJUmTc" x1="24.093" x2="29.964" y1="9.437" y2="3.062" gradientUnits="userSpaceOnUse"><stop offset=".104" class="eoso9abdb"/><stop offset="1" class="v85q32thn"/></linearGradient><linearGradient id="iaFJfVc" x1="22.78" x2="10.593" y1="9.656" y2="21.844" gradientUnits="userSpaceOnUse"><stop class="bt5s3xegs"/><stop offset="1" class="w6qjyabkj"/></linearGradient><linearGradient id="i56wqjb" x1="30.249" x2="24.093" y1="1.688" y2="7.906" gradientUnits="userSpaceOnUse"><stop class="tf_5wd8qs"/><stop offset="1" class="tcry8c12i"/></linearGradient><linearGradient id="iTvMp1b" x1="5.156" x2="10.905" y1="27.625" y2="21.625" gradientUnits="userSpaceOnUse"><stop class="zs79j_bot"/><stop offset="1" class="pa_rx_iip"/></linearGradient><linearGradient id="ikbdNCe" x1="5.656" x2="10.593" y1="26.688" y2="21.844" gradientUnits="userSpaceOnUse"><stop class="vo4shdb8l"/><stop offset="1" class="n53szib9u"/></linearGradient><filter id="iH2W88d" width="13.916" height="13.916" x="9.744" y="8.276" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24597" stdDeviation=".325"/></filter><filter id="ieDKy0d" width="7.431" height="7.431" x="22.369" y="2.136" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24597" stdDeviation=".325"/></filter><filter id="iifCFBc" width="6.538" height="6.538" x="4.551" y="20.88" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24597" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:white-cane" /></template>
<style>
.a1cq-5bvj {
  stop-color: var(--svg-color--6b6473, #6B6473);
  stop-opacity: 0;
}

.bt5s3xegs {
  stop-color: var(--svg-color--b6afbd, #B6AFBD);
}

.btfgyqi2h {
  stop-color: var(--svg-color--53346c, #53346C);
}

.cbp9kmbmi {
  stop-color: var(--svg-color--53346c, #53346C);
  stop-opacity: 0;
}

.cxa08z-au {
  d: path("M29.51 2.517a1.55 1.55 0 0 0-2.192 0L4.053 25.782a.57.57 0 0 1-.315.153a2.04 2.04 0 1 0 2.348 2.359a.6.6 0 0 1 .153-.314L29.51 4.71a1.55 1.55 0 0 0 0-2.193");
}

.cxkgc8uxn {
  stop-color: var(--svg-color--6a656f, #6A656F);
  stop-opacity: 0;
}

.eh8955buk {
  d: path("M24.133 10.087L21.94 7.895l5.377-5.378A1.55 1.55 0 1 1 29.51 4.71z");
}

.eoso9abdb {
  stop-color: var(--svg-color--3f354a, #3F354A);
}

.ft5dv1b6b {
  fill: none;
}

.gia9-xb5c {
  stop-color: var(--svg-color--6b597c, #6B597C);
  stop-opacity: 0;
}

.jnbu_lh_w {
  stop-color: var(--svg-color--a8a3ae, #A8A3AE);
}

.lg9-e-buk {
  stop-color: var(--svg-color--ada4b6, #ADA4B6);
  stop-opacity: 0;
}

.n53szib9u {
  stop-color: var(--svg-color--f63d5a, #F63D5A);
}

.n9dhynb5b {
  stop-color: var(--svg-color--a279c6, #A279C6);
}

.nfy-7kxrk {
  stroke-width: var(--svg-stroke-width--0-65px, 0.65px);
  d: path("M22.78 9.156L10.625 21.313");
}

.npi0c5uzj {
  stop-color: var(--svg-color--6b597c, #6B597C);
}

.nqpl1bcpq {
  stop-color: var(--svg-color--d6d0dd, #D6D0DD);
}

.p61025b1c {
  stop-color: var(--svg-color--5f5867, #5F5867);
}

.pa_rx_iip {
  stop-color: var(--svg-color--e23753, #E23753);
}

.pnxjkfbgy {
  stop-color: var(--svg-color--6a656f, #6A656F);
}

.pr2q1460i {
  stop-color: var(--svg-color--5f5867, #5F5867);
  stop-opacity: 0;
}

.psl8i8bhe {
  cx: 4.072px;
  cy: 27.962px;
  r: 2.036px;
}

.q_sicnbmd {
  stroke-width: var(--svg-stroke-width--0-65px, 0.65px);
  d: path("m5.28 26.688l5.079-5.079");
}

.q_y0tt9kh {
  stop-color: var(--svg-color--b1a9ba, #B1A9BA);
  stop-opacity: 0;
}

.qxy567bxt {
  stop-color: var(--svg-color--6b6473, #6B6473);
}

.sgrv4ghng {
  stroke: var(--svg-color--352e3c, #352E3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M27.544 5.94c-.031.693.096 2.359.574 2.995c.598.794 1.507-.673 1.13-4.636");
}

.tcry8c12i {
  stop-color: var(--svg-color--4c4256, #4C4256);
}

.tf_5wd8qs {
  stop-color: var(--svg-color--7c6e8b, #7C6E8B);
}

.v85q32thn {
  stop-color: var(--svg-color--4e3964, #4E3964);
}

.vo4shdb8l {
  stop-color: var(--svg-color--f83c7f, #F83C7F);
}

.vofrtbbyw {
  d: path("m4.044 25.79l5.407-5.406l2.192 2.193l-5.406 5.406z");
}

.vsfyf-b1z {
  stop-color: var(--svg-color--b5a2c8, #B5A2C8);
}

.w6qjyabkj {
  stop-color: var(--svg-color--bab0c5, #BAB0C5);
}

.wvog-5rsz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M27.544 5.94c-.031.693.096 2.359.574 2.995c.598.794 1.507-.673 1.13-4.636");
}

.yd785tn_v {
  stroke-width: var(--svg-stroke-width--0-65px, 0.65px);
  d: path("M28.921 3.016L23.25 8.688");
}

.zs79j_bot {
  stop-color: var(--svg-color--f52b85, #F52B85);
}

</style>
