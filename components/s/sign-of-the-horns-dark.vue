<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i170IIe)"><path class="zg6q4e9bh"/><path fill="url(#ivssPjb)" class="dv5sy3bea"/></g><g filter="url(#ifs86Oc)" class="l24z6rfvu"><path class="pfe1pacnp"/></g><g filter="url(#iaaIK9b)"><path fill="url(#ikGLrAe)" class="ktd5xrbtc"/></g><rect fill="url(#iG5OFgb)" class="rnw81cc0v"/><rect fill="url(#iMPZI1c)" class="rnw81cc0v"/><rect fill="url(#iAIQ20L)" class="k9xaoqqep"/><g filter="url(#iNRMDZb)"><rect fill="url(#ieoD1Ad)" class="o74wf0bdl"/><rect fill="url(#i9pRKkd)" class="o74wf0bdl"/></g><rect fill="url(#ivG99xc)" class="o74wf0bdl"/><rect fill="url(#iDbxmob)" class="o74wf0bdl"/><rect fill="url(#inIgfzF)" class="o74wf0bdl"/><g filter="url(#iOr8YYc)"><rect fill="url(#iPt5Xad)" class="ihvytccoe"/></g><rect fill="url(#iTAn5tc)" class="ihvytccoe"/><g filter="url(#iUGEbJA)"><path class="cnx63eb0a"/></g><path fill="url(#iiw7AYA)" class="anmos7bcy"/><path fill="url(#iR5Etkc)" class="anmos7bcy"/><path fill="url(#iiw7AYA)" class="hkklrdbbe"/><path fill="url(#iR5Etkc)" class="hkklrdbbe"/><path fill="url(#i02gZNc)" class="anmos7bcy"/><path fill="url(#i02gZNc)" class="hkklrdbbe"/><g filter="url(#in6zWOe)"><path stroke="url(#iNtkw5c)" class="fzv5-oq4u"/></g><path fill="url(#iDtJFOb)" class="q9j8zzbkm"/><path fill="url(#ijUhOmf)" class="q9j8zzbkm"/><path fill="url(#ibrIIeb)" class="q9j8zzbkm"/><g filter="url(#i42MTjc)"><path stroke="url(#iN4HN7I)" class="ow0g1di2k"/></g><g filter="url(#iwe9X1b)"><rect class="q2yuwcb4i"/></g><g filter="url(#iQyLW5d)"><rect class="t84oa-bqy"/></g><defs><radialGradient id="ivssPjb" cx="0" cy="0" r="1" gradientTransform="matrix(1.40994 -4.40607 5.09243 1.62958 21.174 16.563)" gradientUnits="userSpaceOnUse"><stop class="ass-zyb2o"/><stop offset="1" class="y2o35pzed"/></radialGradient><radialGradient id="iG5OFgb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.39062 3.59376 -2.77814 -2.6211 12.745 12.664)" gradientUnits="userSpaceOnUse"><stop class="vyn1iyptt"/><stop offset="1" class="axc-m2bgk"/></radialGradient><radialGradient id="iMPZI1c" cx="0" cy="0" r="1" gradientTransform="matrix(2.07716 0 0 1.61948 9.993 7.683)" gradientUnits="userSpaceOnUse"><stop class="a5c9r5b5q"/><stop offset="1" class="tahqmyqsp"/></radialGradient><radialGradient id="iAIQ20L" cx="0" cy="0" r="1" gradientTransform="matrix(2.5 0 0 2.21875 24.11 4.063)" gradientUnits="userSpaceOnUse"><stop class="l_3w1myze"/><stop offset="1" class="cv7wwgeqb"/></radialGradient><radialGradient id="i9pRKkd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.31357 .85703 -1.14666 -1.7575 16.282 9.946)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="qiy2-kb5h"/><stop offset="1" class="na40w1b5t"/></radialGradient><radialGradient id="ivG99xc" cx="0" cy="0" r="1" gradientTransform="rotate(-129.818 12.024 4.933)scale(4.21217 2.77)" gradientUnits="userSpaceOnUse"><stop class="vihrfccnj"/><stop offset="1" class="uuej68q8w"/></radialGradient><radialGradient id="inIgfzF" cx="0" cy="0" r="1" gradientTransform="rotate(160.412 8.808 7.726)scale(9.71985 13.8653)" gradientUnits="userSpaceOnUse"><stop offset=".889" class="iml04913j"/><stop offset="1" class="w3kf4sgmf"/></radialGradient><radialGradient id="iiw7AYA" cx="0" cy="0" r="1" gradientTransform="rotate(112.817 6.055 15.188)scale(5.35728 16.4557)" gradientUnits="userSpaceOnUse"><stop class="s9o8v_sfw"/><stop offset="1" class="jmtf3qmpv"/></radialGradient><radialGradient id="i02gZNc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.05883 0 0 -12.0286 20.946 16.795)" gradientUnits="userSpaceOnUse"><stop offset=".838" class="zaukw8b0r"/><stop offset="1" class="v16tmmbsy"/></radialGradient><radialGradient id="ijUhOmf" cx="0" cy="0" r="1" gradientTransform="matrix(22.82617 10.50104 -11.16142 24.26165 3.886 11.694)" gradientUnits="userSpaceOnUse"><stop offset=".946" class="b2ce5hbxr"/><stop offset="1" class="ot_9x8b_q"/></radialGradient><radialGradient id="ibrIIeb" cx="0" cy="0" r="1" gradientTransform="rotate(156.737 9.376 11.71)scale(16.9939 20.4837)" gradientUnits="userSpaceOnUse"><stop offset=".872" class="j7e8hxbsm"/><stop offset="1" class="udwby5mno"/></radialGradient><linearGradient id="ikGLrAe" x1="11.264" x2="15.237" y1="14.456" y2="16.299" gradientUnits="userSpaceOnUse"><stop class="n78cagb3l"/><stop offset="1" class="nf2qu_bih"/></linearGradient><linearGradient id="ieoD1Ad" x1="11.844" x2="14.864" y1="11.551" y2="11.561" gradientUnits="userSpaceOnUse"><stop class="c_kjg6q6l"/><stop offset="1" class="q_czuw_zd"/></linearGradient><linearGradient id="iDbxmob" x1="15.398" x2="15.028" y1="12.906" y2="12.906" gradientUnits="userSpaceOnUse"><stop class="jxrnzsbgu"/><stop offset="1" class="s30n5obqo"/></linearGradient><linearGradient id="iPt5Xad" x1="16.302" x2="20.739" y1="10.638" y2="10.638" gradientUnits="userSpaceOnUse"><stop class="rttu7sb8r"/><stop offset="1" class="f8vu6db2t"/><stop offset="1" class="rxiiszonf"/></linearGradient><linearGradient id="iTAn5tc" x1="21.21" x2="18.073" y1="11.495" y2="11.495" gradientUnits="userSpaceOnUse"><stop class="n9vcambar"/><stop offset="1" class="e_kfwziyy"/></linearGradient><linearGradient id="iR5Etkc" x1="24.642" x2="21.636" y1="22.688" y2="20.179" gradientUnits="userSpaceOnUse"><stop offset=".249" class="l9p_tzbnu"/><stop offset="1" class="qz525gmkh"/></linearGradient><linearGradient id="iNtkw5c" x1="18.073" x2="25.419" y1="16.241" y2="18.953" gradientUnits="userSpaceOnUse"><stop class="ok65aabmb"/><stop offset="1" class="j30gkmbty"/></linearGradient><linearGradient id="iDtJFOb" x1="26.12" x2="23.557" y1="16.723" y2="16.723" gradientUnits="userSpaceOnUse"><stop class="jm8gaxhps"/><stop offset="1" class="h3z9pbb0d"/></linearGradient><linearGradient id="iN4HN7I" x1="10.116" x2="10.164" y1="8.258" y2="17.402" gradientUnits="userSpaceOnUse"><stop class="p6wb4qngy"/><stop offset="1" class="iv9_edb6r"/></linearGradient><filter id="i170IIe" width="20.413" height="28.703" x="6.169" y="1.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.12549 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2492"/></filter><filter id="ifs86Oc" width="14.875" height="9.703" x="11.52" y="13.252" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2492" stdDeviation="1"/></filter><filter id="iaaIK9b" width="10.099" height="10.995" x="7.835" y="8.959" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2492" stdDeviation="1"/></filter><filter id="iNRMDZb" width="6.145" height="8.953" x="10.54" y="8.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.0980392 0 0 0 0 0.14902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2492"/></filter><filter id="iOr8YYc" width="6.082" height="11.031" x="15.407" y="6.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0823529 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2492"/></filter><filter id="iUGEbJA" width="5.5" height="19.063" x="20.777" y="1.852" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2492" stdDeviation="1"/></filter><filter id="in6zWOe" width="11.654" height="8.746" x="15.623" y="13.791" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2492" stdDeviation=".85"/></filter><filter id="i42MTjc" width="3" height="9.736" x="7.983" y="7.074" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2492" stdDeviation=".5"/></filter><filter id="iwe9X1b" width="2.851" height="5.453" x="12.812" y="10.395" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2492" stdDeviation=".5"/></filter><filter id="iQyLW5d" width="3.367" height="6.626" x="17.727" y="7.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2492" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:sign-of-the-horns-dark" /></template>
<style>
.a5c9r5b5q {
  stop-color: var(--svg-color--64504e, #64504E);
}

.anmos7bcy {
  d: path("M17.739 14.117a2.852 2.852 0 0 0 0 5.703h1.624a1 1 0 0 1 .743.441l2.471 3.652a1 1 0 0 0 1.745-.16l.937-2.142c.332-.759.543-1.586.38-2.398a6.346 6.346 0 0 0-6.213-5.096");
}

.ass-zyb2o {
  stop-color: var(--svg-color--5b4846, #5B4846);
}

.axc-m2bgk {
  stop-color: var(--svg-color--281518, #281518);
  stop-opacity: 0;
}

.b2ce5hbxr {
  stop-color: var(--svg-color--503638, #503638);
  stop-opacity: 0;
}

.c_kjg6q6l {
  stop-color: var(--svg-color--402c2a, #402C2A);
}

.cnx63eb0a {
  stroke: var(--svg-color--64504e, #64504E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M23.527 4.602v13.562");
}

.cv7wwgeqb {
  stop-color: var(--svg-color--665250, #665250);
  stop-opacity: 0;
}

.dv5sy3bea {
  d: path("M22.76 2.023a2.666 2.666 0 0 0-2.666 2.666v8.217h-8.593V8.33a2.666 2.666 0 1 0-5.332 0v10.803c0 6.656 3.453 10.406 8.734 10.844h1.187c2.91-.291 5.907-1.329 8.157-4.547c1.89-3.047 1.648-6.09 1.457-7.876l-.02-.187a95 95 0 0 1-.258-2.826V4.689a2.666 2.666 0 0 0-2.666-2.666");
}

.e_kfwziyy {
  stop-color: var(--svg-color--5f4744, #5F4744);
  stop-opacity: 0;
}

.f8vu6db2t {
  stop-color: var(--svg-color--523530, #523530);
}

.ft5dv1b6b {
  fill: none;
}

.fzv5-oq4u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.073 16.241h2.834a3 3 0 0 1 2.613 1.527l1.307 2.319");
}

.h3z9pbb0d {
  stop-color: var(--svg-color--5d4643, #5D4643);
  stop-opacity: 0;
}

.hkklrdbbe {
  d: path("M17.739 14.117h1.68Z");
}

.ihvytccoe {
  width: 5.332px;
  height: 10.281px;
  x: 15.407px;
  y: 7.195px;
  rx: 2.666px;
}

.iml04913j {
  stop-color: var(--svg-color--493633, #493633);
  stop-opacity: 0;
}

.iv9_edb6r {
  stop-color: var(--svg-color--634f4d, #634F4D);
  stop-opacity: 0;
}

.j30gkmbty {
  stop-color: var(--svg-color--66514f, #66514F);
  stop-opacity: 0;
}

.j7e8hxbsm {
  stop-color: var(--svg-color--4f3c3a, #4F3C3A);
  stop-opacity: 0;
}

.jm8gaxhps {
  stop-color: var(--svg-color--5d4643, #5D4643);
}

.jmtf3qmpv {
  stop-color: var(--svg-color--371c29, #371C29);
}

.jxrnzsbgu {
  stop-color: var(--svg-color--1f0e0c, #1F0E0C);
}

.k9xaoqqep {
  width: 5.332px;
  height: 15.453px;
  x: 20.094px;
  y: 2.023px;
  rx: 2.666px;
}

.ktd5xrbtc {
  d: path("M9.835 10.959h6.099v6.995H9.835z");
}

.l_3w1myze {
  stop-color: var(--svg-color--665250, #665250);
}

.l24z6rfvu {
  fill: var(--svg-color--2a161d, #2A161D);
}

.l9p_tzbnu {
  stop-color: var(--svg-color--452a33, #452A33);
}

.n78cagb3l {
  stop-color: var(--svg-color--210f12, #210F12);
}

.n9vcambar {
  stop-color: var(--svg-color--5f4744, #5F4744);
}

.na40w1b5t {
  stop-color: var(--svg-color--221311, #221311);
  stop-opacity: 0;
}

.nf2qu_bih {
  stop-color: var(--svg-color--1c0c11, #1C0C11);
}

.o74wf0bdl {
  width: 5.395px;
  height: 8.203px;
  x: 10.54px;
  y: 8.805px;
  rx: 2.697px;
}

.ok65aabmb {
  stop-color: var(--svg-color--66514f, #66514F);
}

.ot_9x8b_q {
  stop-color: var(--svg-color--503638, #503638);
}

.ow0g1di2k {
  stroke-linecap: round;
  d: path("M9.483 8.574v6.737");
}

.p6wb4qngy {
  stop-color: var(--svg-color--634f4d, #634F4D);
}

.pfe1pacnp {
  d: path("M16.372 15.252a2.852 2.852 0 0 0 0 5.703h1.624c3.034 0 4.127 0 6.399-.256c0-3.5-2.836-5.443-6.336-5.447m-1.687 0h1.68Z");
}

.q_czuw_zd {
  stop-color: var(--svg-color--4f3835, #4F3835);
}

.q2yuwcb4i {
  width: 0.851px;
  height: 3.453px;
  x: 13.812px;
  y: 11.395px;
  fill: var(--svg-color--604d4b, #604D4B);
  rx: 0.426px;
}

.q9j8zzbkm {
  d: path("M22.76 2.023a2.666 2.666 0 0 0-2.666 2.666v3.434c.402.467.645 1.074.645 1.738v4.95a2.666 2.666 0 0 1-5.184.879a2.697 2.697 0 0 1-5.016-1.38v-2.808c0-.828.374-1.57.962-2.064V8.33a2.666 2.666 0 1 0-5.332 0v10.803c0 6.656 3.453 10.406 8.734 10.844h1.187c2.91-.291 5.907-1.329 8.157-4.547c1.89-3.047 1.648-6.09 1.457-7.876l-.02-.187a95 95 0 0 1-.258-2.826V4.689a2.666 2.666 0 0 0-2.666-2.666");
}

.qiy2-kb5h {
  stop-color: var(--svg-color--221311, #221311);
}

.qz525gmkh {
  stop-color: var(--svg-color--452a33, #452A33);
  stop-opacity: 0;
}

.rnw81cc0v {
  width: 5.332px;
  height: 11.813px;
  x: 6.169px;
  y: 5.664px;
  rx: 2.666px;
}

.rttu7sb8r {
  stop-color: var(--svg-color--3e2d2b, #3E2D2B);
}

.rxiiszonf {
  stop-color: var(--svg-color--ffd43e, #FFD43E);
}

.s30n5obqo {
  stop-color: var(--svg-color--1f0e0c, #1F0E0C);
  stop-opacity: 0;
}

.s9o8v_sfw {
  stop-color: var(--svg-color--503631, #503631);
}

.t84oa-bqy {
  width: 1.367px;
  height: 4.626px;
  x: 18.727px;
  y: 8.988px;
  fill: var(--svg-color--604d4b, #604D4B);
  rx: 0.684px;
}

.tahqmyqsp {
  stop-color: var(--svg-color--64504e, #64504E);
  stop-opacity: 0;
}

.udwby5mno {
  stop-color: var(--svg-color--4f3c3a, #4F3C3A);
}

.uuej68q8w {
  stop-color: var(--svg-color--281319, #281319);
  stop-opacity: 0;
}

.v16tmmbsy {
  stop-color: var(--svg-color--44312e, #44312E);
}

.vihrfccnj {
  stop-color: var(--svg-color--281319, #281319);
}

.vyn1iyptt {
  stop-color: var(--svg-color--281518, #281518);
}

.w3kf4sgmf {
  stop-color: var(--svg-color--493633, #493633);
}

.y2o35pzed {
  stop-color: var(--svg-color--5b4846, #5B4846);
  stop-opacity: 0;
}

.zaukw8b0r {
  stop-color: var(--svg-color--44312e, #44312E);
  stop-opacity: 0;
}

.zg6q4e9bh {
  fill: var(--svg-color--462b33, #462B33);
  d: path("M22.76 2.023a2.666 2.666 0 0 0-2.666 2.666v8.217h-8.593V8.33a2.666 2.666 0 1 0-5.332 0v10.803c0 6.656 3.453 10.406 8.734 10.844h1.187c2.91-.291 5.907-1.329 8.157-4.547c1.89-3.047 1.648-6.09 1.457-7.876l-.02-.187a95 95 0 0 1-.258-2.826V4.689a2.666 2.666 0 0 0-2.666-2.666");
}

</style>
