<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="m2s8b5b-i"/><path class="rhp9s7bcl"/><path class="usdp_ghzd"/><path class="lmsp0cbth"/><ellipse class="khnz24b3h"/><path class="thx27rtss"/><ellipse class="zuwa6sbfq"/><path class="hjojkxbmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:sport-utility-vehicle" /></template>
<style>
.hjojkxbmw {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M78.82 37.51h21.62v25.77H78.82zm-38.3 0h23.47v25.77H33.36l1.38-5.45z");
}

.khnz24b3h {
  cx: 33.64px;
  cy: 103.82px;
  fill: var(--svg-color--78a3ad, #78a3ad);
  rx: 6.98px;
  ry: 6.97px;
}

.lmsp0cbth {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M51.05 103.82c0 9.62-7.8 17.4-17.41 17.4c-9.62 0-17.42-7.79-17.42-17.4c0-9.62 7.8-17.4 17.42-17.4c9.61 0 17.41 7.78 17.41 17.4");
}

.m2s8b5b-i {
  fill: var(--svg-color--f79329, #f79329);
  d: path("m33.94 29.91l-8.38 28.77H14.79c-6.58 0-11.11 4.35-11.11 10.74V99.3h104.93V29.91z");
}

.rhp9s7bcl {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M127.43 83.35c0 2.89-2.37 5.26-5.26 5.26h-6.32c-2.89 0-5.26-2.37-5.26-5.26v-31.5c0-2.9 2.37-5.26 5.26-5.26h6.32c2.89 0 5.26 2.37 5.26 5.26z");
}

.thx27rtss {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M100.45 103.82c0 9.62-7.81 17.4-17.41 17.4c-9.62 0-17.42-7.79-17.42-17.4c0-9.62 7.8-17.4 17.42-17.4c9.6 0 17.41 7.78 17.41 17.4");
}

.usdp_ghzd {
  fill: var(--svg-color--78a3ad, #78a3ad);
  d: path("M3.91 94.35c-1.83 0-3.33-1.5-3.33-3.33v-3.99c0-1.83 1.5-3.33 3.33-3.33h3.31c1.83 0 3.33 1.5 3.33 3.33v3.99c0 1.83-1.5 3.33-3.33 3.33z");
}

.zuwa6sbfq {
  cx: 83.03px;
  cy: 103.82px;
  fill: var(--svg-color--78a3ad, #78a3ad);
  rx: 6.98px;
  ry: 6.97px;
}

</style>
