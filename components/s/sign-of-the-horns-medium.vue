<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iDOnsKb)"><path class="sdf97b2bk"/><path fill="url(#i2XJnGq)" class="dv5sy3bea"/><path fill="url(#iVFc3Me)" class="dv5sy3bea"/><path fill="url(#isGwJid)" class="dv5sy3bea"/><path fill="url(#iWwYt5b)" class="dv5sy3bea"/></g><g filter="url(#ibjYKab)" class="tcbvrvbxl"><path class="v1edlkbez"/></g><g filter="url(#iP7rsje)"><path class="tc-7c1bxe"/></g><rect fill="url(#iZLmXWb)" class="rnw81cc0v"/><rect fill="url(#iEgsUeb)" class="rnw81cc0v"/><rect fill="url(#iufEKld)" class="uvkmt7bvb"/><g filter="url(#izKkhde)"><rect fill="url(#i0KLBSc)" class="y7yfpk2kk"/><rect fill="url(#ik9NF9c)" class="y7yfpk2kk"/></g><rect fill="url(#i7OM9nc)" class="y7yfpk2kk"/><rect fill="url(#iMOlRCb)" class="y7yfpk2kk"/><rect fill="url(#ibAVJqX)" class="y7yfpk2kk"/><g filter="url(#ioVWbQd)"><rect fill="url(#iI72XGd)" class="qv4bofmwo"/></g><rect fill="url(#iRYYSVc)" class="qv4bofmwo"/><g filter="url(#i1uj1ub)"><path class="x2vnqz2et"/></g><path fill="url(#iTshR8c)" class="moa_tcb3b"/><path fill="url(#izagofc)" class="moa_tcb3b"/><path fill="url(#iTshR8c)" class="qtt3bt4_x"/><path fill="url(#izagofc)" class="qtt3bt4_x"/><path fill="url(#ivI4ZKH)" class="moa_tcb3b"/><path fill="url(#ivI4ZKH)" class="qtt3bt4_x"/><g filter="url(#inVzsId)"><path stroke="url(#ilrZIxQ)" class="nrgdijnzi"/></g><path fill="url(#iu63fNd)" class="q9j8zzbkm"/><path fill="url(#iFoDZDX)" class="q9j8zzbkm"/><path fill="url(#iTyaJDd)" class="q9j8zzbkm"/><path fill="url(#inshFEd)" class="q9j8zzbkm"/><g filter="url(#ige6lcb)"><path stroke="url(#iRHzbSc)" class="z1fggfh7r"/></g><g filter="url(#iCGp05b)"><rect class="a3mqamm1s"/></g><g filter="url(#iND9X1d)"><rect class="tz7v48b0c"/></g><defs><radialGradient id="i2XJnGq" cx="0" cy="0" r="1" gradientTransform="matrix(1.40994 -4.40607 5.09243 1.62958 21.174 16.563)" gradientUnits="userSpaceOnUse"><stop class="eje-j3boi"/><stop offset="1" class="o9x4w2u4p"/></radialGradient><radialGradient id="iVFc3Me" cx="0" cy="0" r="1" gradientTransform="matrix(-5.26865 0 0 -4.94397 21.72 20.944)" gradientUnits="userSpaceOnUse"><stop class="eje-j3boi"/><stop offset="1" class="o9x4w2u4p"/></radialGradient><radialGradient id="isGwJid" cx="0" cy="0" r="1" gradientTransform="matrix(-7.59133 6.41699 -6.71794 -7.94735 11.579 16)" gradientUnits="userSpaceOnUse"><stop class="m-uqhvm0a"/><stop offset="1" class="oymmapbji"/></radialGradient><radialGradient id="iWwYt5b" cx="0" cy="0" r="1" gradientTransform="matrix(3.8524 -8.636 17.74316 7.91498 12.881 29.977)" gradientUnits="userSpaceOnUse"><stop class="ky2szyqzp"/><stop offset="1" class="h1ba48b8g"/></radialGradient><radialGradient id="iZLmXWb" cx="0" cy="0" r="1" gradientTransform="rotate(135.049 4.383 8.794)scale(6.13815 3.77004)" gradientUnits="userSpaceOnUse"><stop class="oh4xy3s-k"/><stop offset="1" class="dm2bplbix"/></radialGradient><radialGradient id="iEgsUeb" cx="0" cy="0" r="1" gradientTransform="matrix(2.07716 0 0 1.61948 9.993 7.683)" gradientUnits="userSpaceOnUse"><stop class="rv0y--rcc"/><stop offset="1" class="ctrg31j2s"/></radialGradient><radialGradient id="iufEKld" cx="0" cy="0" r="1" gradientTransform="matrix(2.5 0 0 2.21875 24.115 4.066)" gradientUnits="userSpaceOnUse"><stop class="o_6q1x5xg"/><stop offset="1" class="p04xckb9h"/></radialGradient><radialGradient id="ik9NF9c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.31357 .85703 -1.14666 -1.7575 16.011 9.946)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="a0oufp6qd"/><stop offset="1" class="ehla8-bli"/></radialGradient><radialGradient id="i7OM9nc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.59464 4.68444 0 12.966 16.686)" gradientUnits="userSpaceOnUse"><stop class="s5uev6brw"/><stop offset="1" class="yc0sevbmq"/></radialGradient><radialGradient id="ibAVJqX" cx="0" cy="0" r="1" gradientTransform="rotate(160.412 8.673 7.703)scale(9.71985 13.8653)" gradientUnits="userSpaceOnUse"><stop offset=".889" class="j3vra_g_n"/><stop offset="1" class="vedh4_b9f"/></radialGradient><radialGradient id="iTshR8c" cx="0" cy="0" r="1" gradientTransform="rotate(111.558 5.796 15.274)scale(5.65391 17.3668)" gradientUnits="userSpaceOnUse"><stop class="sxj45vdqq"/><stop offset="1" class="r2d60cc4t"/></radialGradient><radialGradient id="ivI4ZKH" cx="0" cy="0" r="1" gradientTransform="matrix(-6.05883 0 0 -12.0286 20.675 16.795)" gradientUnits="userSpaceOnUse"><stop offset=".838" class="ef6kno12t"/><stop offset="1" class="g6fq3ergl"/></radialGradient><radialGradient id="iFoDZDX" cx="0" cy="0" r="1" gradientTransform="matrix(22.82617 10.50104 -11.16142 24.26165 3.886 11.694)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="vyi0cgblc"/><stop offset="1" class="ay6le3x7r"/></radialGradient><radialGradient id="inshFEd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.73897 19.88493 -15.06185 -2.83208 18.037 10.577)" gradientUnits="userSpaceOnUse"><stop offset=".839" class="w6rbvxb_f"/><stop offset="1" class="np7uh2bmw"/></radialGradient><linearGradient id="i0KLBSc" x1="11.572" x2="14.593" y1="11.551" y2="11.561" gradientUnits="userSpaceOnUse"><stop class="c19se8b-m"/><stop offset="1" class="jmqfcwbzf"/></linearGradient><linearGradient id="iMOlRCb" x1="15.126" x2="14.757" y1="12.906" y2="12.906" gradientUnits="userSpaceOnUse"><stop class="waapiobas"/><stop offset="1" class="y4kk99bbk"/></linearGradient><linearGradient id="iI72XGd" x1="16.031" x2="20.468" y1="10.638" y2="10.638" gradientUnits="userSpaceOnUse"><stop class="jxyt_cc8p"/><stop offset="1" class="n76lh1q4d"/></linearGradient><linearGradient id="iRYYSVc" x1="20.939" x2="17.802" y1="11.495" y2="11.495" gradientUnits="userSpaceOnUse"><stop class="dywjw2-1p"/><stop offset="1" class="cndmru18i"/></linearGradient><linearGradient id="izagofc" x1="24.37" x2="21.365" y1="22.688" y2="20.179" gradientUnits="userSpaceOnUse"><stop offset=".249" class="g5v4rjb5x"/><stop offset="1" class="i9x3g4buy"/></linearGradient><linearGradient id="ilrZIxQ" x1="17.802" x2="25.147" y1="16.241" y2="18.953" gradientUnits="userSpaceOnUse"><stop class="k7t9l9bda"/><stop offset="1" class="z9xoncbqq"/></linearGradient><linearGradient id="iu63fNd" x1="26.12" x2="23.557" y1="16.723" y2="16.723" gradientUnits="userSpaceOnUse"><stop class="all9f8bhl"/><stop offset="1" class="o2mhkl41o"/></linearGradient><linearGradient id="iTyaJDd" x1="6.006" x2="6.834" y1="16.752" y2="16.752" gradientUnits="userSpaceOnUse"><stop class="dul3p7vfy"/><stop offset="1" class="u7mikvbly"/></linearGradient><linearGradient id="iRHzbSc" x1="9.844" x2="9.893" y1="8.258" y2="17.402" gradientUnits="userSpaceOnUse"><stop class="ry-d1u8of"/><stop offset="1" class="w6ssl_bcw"/></linearGradient><filter id="iDOnsKb" width="20.413" height="28.703" x="6.169" y="1.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.392157 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2528"/></filter><filter id="ibjYKab" width="14.875" height="9.703" x="11.249" y="13.252" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2528" stdDeviation="1"/></filter><filter id="iP7rsje" width="10.099" height="10.995" x="7.564" y="8.959" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2528" stdDeviation="1"/></filter><filter id="izKkhde" width="6.145" height="8.953" x="10.268" y="8.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.419608 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2528"/></filter><filter id="ioVWbQd" width="6.082" height="11.031" x="15.136" y="6.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.495833 0 0 0 0 0.385492 0 0 0 0 0.301632 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2528"/></filter><filter id="i1uj1ub" width="5.5" height="19.063" x="20.505" y="1.852" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2528" stdDeviation="1"/></filter><filter id="inVzsId" width="11.654" height="8.746" x="15.351" y="13.791" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2528" stdDeviation=".85"/></filter><filter id="ige6lcb" width="3" height="9.736" x="7.712" y="7.074" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2528" stdDeviation=".5"/></filter><filter id="iCGp05b" width="2.851" height="5.453" x="12.541" y="10.395" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2528" stdDeviation=".5"/></filter><filter id="iND9X1d" width="3.367" height="6.626" x="17.456" y="7.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2528" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:sign-of-the-horns-medium" /></template>
<style>
.a0oufp6qd {
  stop-color: var(--svg-color--5c402e, #5C402E);
}

.a3mqamm1s {
  width: 0.851px;
  height: 3.453px;
  x: 13.541px;
  y: 11.395px;
  fill: var(--svg-color--c39c88, #C39C88);
  rx: 0.426px;
}

.all9f8bhl {
  stop-color: var(--svg-color--c49d81, #C49D81);
}

.ay6le3x7r {
  stop-color: var(--svg-color--c79d81, #C79D81);
}

.c19se8b-m {
  stop-color: var(--svg-color--997461, #997461);
}

.cndmru18i {
  stop-color: var(--svg-color--caa083, #CAA083);
  stop-opacity: 0;
}

.ctrg31j2s {
  stop-color: var(--svg-color--caa388, #CAA388);
  stop-opacity: 0;
}

.dm2bplbix {
  stop-color: var(--svg-color--704546, #704546);
  stop-opacity: 0;
}

.dul3p7vfy {
  stop-color: var(--svg-color--916a5f, #916A5F);
}

.dv5sy3bea {
  d: path("M22.76 2.023a2.666 2.666 0 0 0-2.666 2.666v8.217h-8.593V8.33a2.666 2.666 0 1 0-5.332 0v10.803c0 6.656 3.453 10.406 8.734 10.844h1.187c2.91-.291 5.907-1.329 8.157-4.547c1.89-3.047 1.648-6.09 1.457-7.876l-.02-.187a95 95 0 0 1-.258-2.826V4.689a2.666 2.666 0 0 0-2.666-2.666");
}

.dywjw2-1p {
  stop-color: var(--svg-color--caa083, #CAA083);
}

.ef6kno12t {
  stop-color: var(--svg-color--936b61, #936B61);
  stop-opacity: 0;
}

.ehla8-bli {
  stop-color: var(--svg-color--5c402e, #5C402E);
  stop-opacity: 0;
}

.eje-j3boi {
  stop-color: var(--svg-color--c59e84, #C59E84);
}

.ft5dv1b6b {
  fill: none;
}

.g5v4rjb5x {
  stop-color: var(--svg-color--b18277, #B18277);
}

.g6fq3ergl {
  stop-color: var(--svg-color--936b61, #936B61);
}

.h1ba48b8g {
  stop-color: var(--svg-color--ab757e, #AB757E);
  stop-opacity: 0;
}

.i9x3g4buy {
  stop-color: var(--svg-color--b18277, #B18277);
  stop-opacity: 0;
}

.j3vra_g_n {
  stop-color: var(--svg-color--976e63, #976E63);
  stop-opacity: 0;
}

.jmqfcwbzf {
  stop-color: var(--svg-color--b28d71, #B28D71);
}

.jxyt_cc8p {
  stop-color: var(--svg-color--97755f, #97755F);
}

.k7t9l9bda {
  stop-color: var(--svg-color--cea58d, #CEA58D);
}

.ky2szyqzp {
  stop-color: var(--svg-color--ab757e, #AB757E);
}

.m-uqhvm0a {
  stop-color: var(--svg-color--966e62, #966E62);
}

.moa_tcb3b {
  d: path("M17.468 14.117a2.852 2.852 0 1 0 0 5.703h1.624a1 1 0 0 1 .743.441l2.471 3.652a1 1 0 0 0 1.744-.16l.938-2.142c.332-.759.542-1.586.38-2.398a6.346 6.346 0 0 0-6.213-5.096");
}

.n76lh1q4d {
  stop-color: var(--svg-color--c79e7d, #C79E7D);
}

.np7uh2bmw {
  stop-color: var(--svg-color--9a597f, #9A597F);
}

.nrgdijnzi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.802 16.241h2.833a3 3 0 0 1 2.613 1.527l1.308 2.319");
}

.o_6q1x5xg {
  stop-color: var(--svg-color--d0a98d, #D0A98D);
}

.o2mhkl41o {
  stop-color: var(--svg-color--c49d81, #C49D81);
  stop-opacity: 0;
}

.o9x4w2u4p {
  stop-color: var(--svg-color--c59e84, #C59E84);
  stop-opacity: 0;
}

.oh4xy3s-k {
  stop-color: var(--svg-color--704546, #704546);
}

.oymmapbji {
  stop-color: var(--svg-color--966e62, #966E62);
  stop-opacity: 0;
}

.p04xckb9h {
  stop-color: var(--svg-color--d0a98d, #D0A98D);
  stop-opacity: 0;
}

.q9j8zzbkm {
  d: path("M22.76 2.023a2.666 2.666 0 0 0-2.666 2.666v3.434c.402.467.645 1.074.645 1.738v4.95a2.666 2.666 0 0 1-5.184.879a2.697 2.697 0 0 1-5.016-1.38v-2.808c0-.828.374-1.57.962-2.064V8.33a2.666 2.666 0 1 0-5.332 0v10.803c0 6.656 3.453 10.406 8.734 10.844h1.187c2.91-.291 5.907-1.329 8.157-4.547c1.89-3.047 1.648-6.09 1.457-7.876l-.02-.187a95 95 0 0 1-.258-2.826V4.689a2.666 2.666 0 0 0-2.666-2.666");
}

.qtt3bt4_x {
  d: path("M17.468 14.117h1.68Z");
}

.qv4bofmwo {
  width: 5.332px;
  height: 10.281px;
  x: 15.136px;
  y: 7.195px;
  rx: 2.666px;
}

.r2d60cc4t {
  stop-color: var(--svg-color--9a6073, #9A6073);
}

.rnw81cc0v {
  width: 5.332px;
  height: 11.813px;
  x: 6.169px;
  y: 5.664px;
  rx: 2.666px;
}

.rv0y--rcc {
  stop-color: var(--svg-color--caa388, #CAA388);
}

.ry-d1u8of {
  stop-color: var(--svg-color--c9a286, #C9A286);
}

.s5uev6brw {
  stop-color: var(--svg-color--92596d, #92596D);
}

.sdf97b2bk {
  fill: var(--svg-color--b88480, #B88480);
  d: path("M22.76 2.023a2.666 2.666 0 0 0-2.666 2.666v8.217h-8.593V8.33a2.666 2.666 0 1 0-5.332 0v10.803c0 6.656 3.453 10.406 8.734 10.844h1.187c2.91-.291 5.907-1.329 8.157-4.547c1.89-3.047 1.648-6.09 1.457-7.876l-.02-.187a95 95 0 0 1-.258-2.826V4.689a2.666 2.666 0 0 0-2.666-2.666");
}

.sxj45vdqq {
  stop-color: var(--svg-color--bf9676, #BF9676);
}

.tc-7c1bxe {
  fill: var(--svg-color--7a4854, #7A4854);
  d: path("M9.564 10.959h6.099v6.995H9.564z");
}

.tcbvrvbxl {
  fill: var(--svg-color--7a4854, #7A4854);
}

.tz7v48b0c {
  width: 1.367px;
  height: 4.626px;
  x: 18.456px;
  y: 8.988px;
  fill: var(--svg-color--cca487, #CCA487);
  rx: 0.684px;
}

.u7mikvbly {
  stop-color: var(--svg-color--916a5f, #916A5F);
  stop-opacity: 0;
}

.uvkmt7bvb {
  width: 5.332px;
  height: 15.453px;
  x: 20.1px;
  y: 2.027px;
  rx: 2.666px;
}

.v1edlkbez {
  d: path("M16.1 15.252a2.852 2.852 0 1 0 0 5.703h1.624c3.034 0 4.128 0 6.4-.256c0-3.5-2.836-5.443-6.336-5.447m-1.688 0h1.68Z");
}

.vedh4_b9f {
  stop-color: var(--svg-color--976e63, #976E63);
}

.vyi0cgblc {
  stop-color: var(--svg-color--c79d81, #C79D81);
  stop-opacity: 0;
}

.w6rbvxb_f {
  stop-color: var(--svg-color--9a597f, #9A597F);
  stop-opacity: 0;
}

.w6ssl_bcw {
  stop-color: var(--svg-color--c9a286, #C9A286);
  stop-opacity: 0;
}

.waapiobas {
  stop-color: var(--svg-color--6b4732, #6B4732);
}

.x2vnqz2et {
  stroke: var(--svg-color--cea68c, #CEA68C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M23.255 4.602v13.562");
}

.y4kk99bbk {
  stop-color: var(--svg-color--6b4732, #6B4732);
  stop-opacity: 0;
}

.y7yfpk2kk {
  width: 5.395px;
  height: 8.203px;
  x: 10.268px;
  y: 8.805px;
  rx: 2.697px;
}

.yc0sevbmq {
  stop-color: var(--svg-color--92596d, #92596D);
  stop-opacity: 0;
}

.z1fggfh7r {
  stroke-linecap: round;
  d: path("M9.212 8.574v6.737");
}

.z9xoncbqq {
  stop-color: var(--svg-color--cea58d, #CEA58D);
  stop-opacity: 0;
}

</style>
