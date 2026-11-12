<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="amgqiybcj"/><path class="w3a7pgbtx"/><path class="m2q7v_gjq"/><path class="rsris_b3l"/><path class="ctg14gobl"/><path class="romdoeucp"/><path class="egqyezb9p"/><path class="syy4zxu2c"/><path class="nzvwhdb2q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:spedometer-max-broken" /></template>
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

.syy4zxu2c {
  d: path("M10.1209 14.3638C8.94929 13.1923 8.94929 11.2928 10.1209 10.1212C11.2924 8.94963 13.1919 8.94963 14.3635 10.1212C14.8092 10.5669 15.1204 11.492 15.335 12.4673C15.6559 13.9258 15.8164 14.6551 15.2356 15.2359C14.6548 15.8167 13.9255 15.6563 12.467 15.3353C11.4916 15.1207 10.5665 14.8095 10.1209 14.3638Z");
}

.w3a7pgbtx {
  d: path("M19 5L17.5 6.5");
}

</style>
