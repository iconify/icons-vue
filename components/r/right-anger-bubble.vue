<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#icgxW8J)"><path fill="url(#icjIMYd)" class="rfzk3ac4k"/><path fill="url(#iI5QJBb)" class="rfzk3ac4k"/><path fill="url(#itfnb4b)" class="rfzk3ac4k"/><path fill="url(#iR6dHgb)" class="rfzk3ac4k"/><path fill="url(#iso6mIe)" class="rfzk3ac4k"/></g><g filter="url(#i2zYOab)"><path fill="url(#iHt1Ckd)" class="ngz_dubjx"/></g><g filter="url(#iXqgWte)"><path fill="url(#i2EG0Tc)" class="qa9a3pbph"/></g><g filter="url(#iRDV3Pd)"><path fill="url(#ipNkaDe)" class="gsptsobgs"/></g><g filter="url(#iqa0grc)"><path fill="url(#iOHybXc)" class="xkp9o6bkz"/></g><g filter="url(#ig0JgAd)"><path fill="url(#iHVOvRX)" class="hr6hm68yu"/></g><g filter="url(#isb9mxb)"><path fill="url(#iseN2nd)" class="evk51yb1u"/></g><g filter="url(#iXTxk3b)"><path fill="url(#iIEWZ2b)" class="oyiysw7vv"/></g><g filter="url(#iuekpnd)"><path fill="url(#iqxmBse)" class="vqif-iidb"/></g><defs><linearGradient id="iR6dHgb" x1="8.512" x2=".754" y1="15.375" y2="26.543" gradientUnits="userSpaceOnUse"><stop offset=".439" class="qz913sb2z"/><stop offset=".966" class="zc1e6_uqb"/></linearGradient><linearGradient id="iHt1Ckd" x1="8.537" x2="5.087" y1="15.561" y2="18.893" gradientUnits="userSpaceOnUse"><stop offset=".432" class="u7vmszvvs"/><stop offset="1" class="es01jhb1r"/></linearGradient><linearGradient id="i2EG0Tc" x1="13.043" x2="8.48" y1="19.125" y2="23.031" gradientUnits="userSpaceOnUse"><stop offset=".411" class="u7vmszvvs"/><stop offset="1" class="es01jhb1r"/></linearGradient><linearGradient id="ipNkaDe" x1="17.637" x2="16.168" y1="18.313" y2="24.563" gradientUnits="userSpaceOnUse"><stop offset=".427" class="u7vmszvvs"/><stop offset="1" class="es01jhb1r"/></linearGradient><linearGradient id="iOHybXc" x1="21.387" x2="23.559" y1="16.906" y2="21.625" gradientUnits="userSpaceOnUse"><stop offset=".26" class="u7vmszvvs"/><stop offset="1" class="es01jhb1r"/></linearGradient><linearGradient id="iHVOvRX" x1="24.543" x2="29.371" y1="16.648" y2="16.648" gradientUnits="userSpaceOnUse"><stop offset=".26" class="u7vmszvvs"/><stop offset="1" class="es01jhb1r"/></linearGradient><linearGradient id="iseN2nd" x1="8.48" x2="5.918" y1="16.938" y2="20" gradientUnits="userSpaceOnUse"><stop offset=".26" class="n-v3d-biv"/><stop offset="1" class="gu8q78bls"/></linearGradient><linearGradient id="iIEWZ2b" x1="13.418" x2="14.527" y1="5.406" y2="7.719" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iqxmBse" x1="6.362" x2="9.387" y1="8.735" y2="9.844" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><filter id="icgxW8J" width="27.895" height="22.078" x="2.102" y="4.739" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.758333 0 0 0 0 0.758333 0 0 0 0 0.758333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_7163_6142"/></filter><filter id="i2zYOab" width="8.219" height="8" x="1.449" y="13.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7163_6142" stdDeviation=".75"/></filter><filter id="iXqgWte" width="9.719" height="9.688" x="4.387" y="17" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7163_6142" stdDeviation=".75"/></filter><filter id="iRDV3Pd" width="11.875" height="9.516" x="9.199" y="17.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7163_6142" stdDeviation=".75"/></filter><filter id="iqa0grc" width="8.078" height="8.047" x="19.871" y="16.156" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7163_6142" stdDeviation=".75"/></filter><filter id="ig0JgAd" width="6.672" height="5.828" x="24.199" y="13.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7163_6142" stdDeviation=".75"/></filter><filter id="isb9mxb" width="7.313" height="4.438" x="4.762" y="17.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7163_6142" stdDeviation=".5"/></filter><filter id="iXTxk3b" width="6.813" height="5.844" x="11.855" y="4.406" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7163_6142" stdDeviation=".5"/></filter><filter id="iuekpnd" width="7.825" height="4.824" x="5.093" y="7.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7163_6142" stdDeviation=".5"/></filter><radialGradient id="icjIMYd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.56239 16.25 -29.65848 -6.50185 20.7 8.5)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="fs6lwuw1m"/></radialGradient><radialGradient id="iI5QJBb" cx="0" cy="0" r="1" gradientTransform="rotate(-164.808 12.248 11.661)scale(24.8043 47.1164)" gradientUnits="userSpaceOnUse"><stop offset=".523" class="nsphchb3g"/><stop offset="1" class="miyj2_bix"/></radialGradient><radialGradient id="itfnb4b" cx="0" cy="0" r="1" gradientTransform="matrix(-13.37506 -21.24993 26.2018 -16.49185 19.887 27.188)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="nsphchb3g"/><stop offset="1" class="miyj2_bix"/></radialGradient><radialGradient id="iso6mIe" cx="0" cy="0" r="1" gradientTransform="matrix(-14.06239 27.87506 -63.16857 -31.86724 18.824 12.188)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="qz913sb2z"/><stop offset="1" class="zc1e6_uqb"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:right-anger-bubble" /></template>
<style>
.es01jhb1r {
  stop-color: var(--svg-color--c5bdea, #C5BDEA);
}

.evk51yb1u {
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M11.074 21.188L9.2 18.75l-3.437 2.438z");
}

.fs6lwuw1m {
  stop-color: var(--svg-color--ead3f8, #EAD3F8);
}

.ft5dv1b6b {
  fill: none;
}

.gsptsobgs {
  d: path("m17.137 19.188l-6.438 6.515l5.625-3.172l3.25 1.875z");
}

.gu8q78bls {
  stop-color: var(--svg-color--a18fee, #A18FEE);
}

.hr6hm68yu {
  d: path("m25.7 15.625l.234 2.438l3.437-2.829z");
}

.miyj2_bix {
  stop-color: var(--svg-color--cecece, #CECECE);
}

.n-v3d-biv {
  stop-color: var(--svg-color--a18fee, #A18FEE);
  stop-opacity: 0;
}

.ngz_dubjx {
  d: path("m8.168 15.531l-5.219-.437l2.719 2.344v2.656z");
}

.nsphchb3g {
  stop-color: var(--svg-color--cecece, #CECECE);
  stop-opacity: 0;
}

.oyiysw7vv {
  d: path("M12.856 5.406V9.25l4.812-1.031z");
}

.qa9a3pbph {
  d: path("m12.606 18.5l-6.72 2.531h3.75l-.187 4.157z");
}

.qz913sb2z {
  stop-color: var(--svg-color--b6a8f2, #B6A8F2);
  stop-opacity: 0;
}

.rfzk3ac4k {
  d: path("m8.757 22.719l-.234 2.916a1 1 0 0 0 1.498.945l5.491-3.178a1 1 0 0 1 1 0l2.457 1.414a1 1 0 0 0 1.294-.26l1.831-2.4a1 1 0 0 1 .795-.394h3.055a1 1 0 0 0 1-1v-2.35a1 1 0 0 1 .323-.736l2.306-2.12a1 1 0 0 0-.019-1.49l-2.237-1.955a1 1 0 0 1-.341-.723l-.077-2.613a1 1 0 0 0-.987-.97l-2.98-.037a1 1 0 0 1-.754-.357l-1.942-2.315a1 1 0 0 0-1.25-.232l-2.54 1.404a1 1 0 0 1-.964.002L12.97 4.893a1 1 0 0 0-1.237.222l-1.99 2.301a1 1 0 0 1-.756.346H5.944a1 1 0 0 0-1 1v2.556a1 1 0 0 1-.33.742l-2.183 1.971a1 1 0 0 0 .004 1.488l2.176 1.945a1 1 0 0 1 .333.746v2.507a1 1 0 0 0 1.044 1l1.728-.077a1 1 0 0 1 1.041 1.079");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.u7vmszvvs {
  stop-color: var(--svg-color--c5bdea, #C5BDEA);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vqif-iidb {
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  d: path("m6.093 8.52l3.7 2.824l2.125-2.825z");
}

.xkp9o6bkz {
  d: path("m21.543 17.656l-.172 5.047l1.328-1.562h3.75z");
}

.zc1e6_uqb {
  stop-color: var(--svg-color--b6a8f2, #B6A8F2);
}

</style>
