<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gshkn9qqt"/><path class="amgqiybcj"/><path class="w3a7pgbtx"/><path class="m2q7v_gjq"/><path class="rsris_b3l"/><path class="ctg14gobl"/><path class="romdoeucp"/><path class="egqyezb9p"/><path class="zu8q05b8q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:speedometer-middle-linear" /></template>
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

.gshkn9qqt {
  d: path("M22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2C17.5228 2 22 6.47715 22 12Z");
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

.romdoeucp {
  d: path("M19.9998 12L21.9998 12");
}

.rsris_b3l {
  d: path("M5 5L6.5 6.5");
}

.w3a7pgbtx {
  d: path("M19 5L17.5 6.5");
}

.zu8q05b8q {
  d: path("M15 12C15 13.6569 13.6569 15 12 15C10.3431 15 9 13.6569 9 12C9 11.3698 9.43408 10.4955 9.972 9.65412C10.7764 8.39585 11.1786 7.76672 12 7.76672C12.8214 7.76672 13.2236 8.39585 14.028 9.65412C14.5659 10.4955 15 11.3698 15 12Z");
}

</style>
