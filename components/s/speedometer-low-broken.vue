<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="amgqiybcj"/><path class="w3a7pgbtx"/><path class="m2q7v_gjq"/><path class="rsris_b3l"/><path class="ctg14gobl"/><path class="romdoeucp"/><path class="egqyezb9p"/><path class="upr0i9feh"/><path class="nzvwhdb2q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:speedometer-low-broken" /></template>
<style>
.amgqiybcj {
  d: path("M19 19L17.5 17.5");
}

.ctg14gobl {
  d: path("M2 12H4");
}

.egqyezb9p {
  d: path("M12 4.00021L12 2.00021");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m2q7v_gjq {
  d: path("M5 19L6.5 17.5");
}

.nzvwhdb2q {
  d: path("M9 21.5422C4.94289 20.2679 2 16.4776 2 12C2 6.47715 6.47715 2 12 2C17.5228 2 22 6.47715 22 12C22 16.4776 19.0571 20.2679 15 21.5422");
}

.romdoeucp {
  d: path("M19.9998 12L21.9998 12");
}

.rsris_b3l {
  d: path("M5 5L6.5 6.5");
}

.upr0i9feh {
  d: path("M13.7783 14.3638C14.9499 13.1923 14.9499 11.2928 13.7783 10.1212C12.6068 8.94963 10.7073 8.94963 9.5357 10.1212C9.09005 10.5669 8.77881 11.492 8.56421 12.4673C8.24329 13.9258 8.08283 14.6551 8.66363 15.2359C9.24444 15.8167 9.9737 15.6563 11.4322 15.3353C12.4076 15.1207 13.3327 14.8095 13.7783 14.3638Z");
}

.w3a7pgbtx {
  d: path("M19 5L17.5 6.5");
}

</style>
