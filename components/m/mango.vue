<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#imwNI7d)" class="wxxe5m1wn"/><g filter="url(#itp20Mc)"><path fill="url(#iDwVltb)" class="ks_47bbfb"/></g><g filter="url(#i2km2mb)"><path fill="url(#iF6hNkc)" class="x5whlibdr"/></g><path fill="url(#i75K1zc)" class="v6hb1hbky"/><path fill="url(#iiuOUjd)" class="v6hb1hbky"/><path fill="url(#iCqzedd)" class="v6hb1hbky"/><path fill="url(#inkGnSd)" class="v6hb1hbky"/><defs><radialGradient id="i75K1zc" cx="0" cy="0" r="1" gradientTransform="rotate(33.391 -8.647 11.034)scale(23.5619 19.4408)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="iduzukcea"/><stop offset=".458" class="otd44_bnn"/><stop offset=".795" class="n-4s_6bhx"/><stop offset="1" class="ibb_4dn0u"/></radialGradient><radialGradient id="iiuOUjd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66473 20.57346 -16.97512 -1.37357 18.832 9.517)" gradientUnits="userSpaceOnUse"><stop class="v3ewp6gpa"/><stop offset="1" class="dbs0ibbtq"/></radialGradient><radialGradient id="iCqzedd" cx="0" cy="0" r="1" gradientTransform="matrix(-15.99994 -4.25008 3.50672 -13.2015 25 19.75)" gradientUnits="userSpaceOnUse"><stop class="n64k09ccl"/><stop offset="1" class="sr4sqthiy"/></radialGradient><radialGradient id="inkGnSd" cx="0" cy="0" r="1" gradientTransform="rotate(-51.667 42.905 4.2)scale(13.7045 11.3075)" gradientUnits="userSpaceOnUse"><stop class="egks7zb2w"/><stop offset="1" class="qarwc_bde"/></radialGradient><linearGradient id="imwNI7d" x1="2" x2="13.183" y1="4.767" y2="4.767" gradientUnits="userSpaceOnUse"><stop class="u78b9bbfe"/><stop offset="1" class="vti2o337p"/></linearGradient><linearGradient id="iDwVltb" x1="2" x2="13.183" y1="4.767" y2="4.767" gradientUnits="userSpaceOnUse"><stop class="hxlqhbb8z"/><stop offset="1" class="i5e56mbwc"/></linearGradient><linearGradient id="iF6hNkc" x1="12.818" x2="4.093" y1="4.561" y2="3.513" gradientUnits="userSpaceOnUse"><stop class="x-fq6gbjw"/><stop offset=".182" class="zfv_-lb6l"/><stop offset=".906" class="x-fq6gbjw"/></linearGradient><filter id="itp20Mc" width="10.895" height="5.534" x="2.112" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29804" stdDeviation=".25"/></filter><filter id="i2km2mb" width="10.604" height="3.927" x="2.964" y="1.55" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29804" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:mango" /></template>
<style>
.dbs0ibbtq {
  stop-color: var(--svg-color--dd491a, #DD491A);
}

.egks7zb2w {
  stop-color: var(--svg-color--d9777b, #D9777B);
}

.ft5dv1b6b {
  fill: none;
}

.hxlqhbb8z {
  stop-color: var(--svg-color--95b91a, #95B91A);
}

.i5e56mbwc {
  stop-color: var(--svg-color--b5ce35, #B5CE35);
}

.ibb_4dn0u {
  stop-color: var(--svg-color--fff440, #FFF440);
}

.iduzukcea {
  stop-color: var(--svg-color--e24b00, #E24B00);
}

.ks_47bbfb {
  d: path("m2.612 4.818l4.132-1.991c.932-.422 2.202-.435 3.374-.04c1.009.34 1.883.962 2.389 1.802L8.327 6.59l-.006.004c-1.933.962-4.578.338-5.71-1.776");
}

.n-4s_6bhx {
  stop-color: var(--svg-color--ffc16b, #FFC16B);
}

.n64k09ccl {
  stop-color: var(--svg-color--fff33f, #FFF33F);
}

.otd44_bnn {
  stop-color: var(--svg-color--ff8323, #FF8323);
}

.qarwc_bde {
  stop-color: var(--svg-color--ffb374, #FFB374);
  stop-opacity: 0;
}

.sr4sqthiy {
  stop-color: var(--svg-color--fff33f, #FFF33F);
  stop-opacity: 0;
}

.u78b9bbfe {
  stop-color: var(--svg-color--83ae1e, #83AE1E);
}

.v3ewp6gpa {
  stop-color: var(--svg-color--ffa453, #FFA453);
  stop-opacity: 0;
}

.v6hb1hbky {
  d: path("M6.727 15.456c-.775-3.971.4-7.944 5.34-10.18c4.64-2.304 9.244-.36 11.25 2.402C29.425 16.09 27.556 23.3 27.556 23.3c-.567 4.273-6.49 9.698-13.385 4.94c0 0-5.191-3.109-7.444-12.784");
}

.vti2o337p {
  stop-color: var(--svg-color--abc932, #ABC932);
}

.wxxe5m1wn {
  d: path("m13.183 4.82l-4.64 2.22c-2.23 1.111-5.332.335-6.512-2.27c-.038-.075-.065-.193.07-.262l4.43-2.135c2.146-.976 5.63 0 6.652 2.445");
}

.x-fq6gbjw {
  stop-color: var(--svg-color--d1ed71, #D1ED71);
  stop-opacity: 0;
}

.x5whlibdr {
  d: path("M6.78 2.696c2.004-.912 5.083-.254 6.038 2.03c-2.762-1.895-3.403-2.697-9.104-.703z");
}

.zfv_-lb6l {
  stop-color: var(--svg-color--d1ed71, #D1ED71);
}

</style>
