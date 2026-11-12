<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vsuchmb_q"/><path class="vvbvajt1v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pie-chart-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vsuchmb_q {
  d: path("M20 15.5524C18.8263 19.2893 15.3351 22 11.2108 22C6.12383 22 2 17.8762 2 12.7892C2 11.8169 2.15064 10.8798 2.42985 10M5 5.98724C5.9789 5.09291 7.15152 4.40707 8.44759 4");
}

.vvbvajt1v {
  d: path("M14.0527 2.0869C17.8556 3.14845 20.8515 6.14438 21.9131 9.94727C22.3719 11.5909 20.9458 13 19.2394 13H12.5449C11.6917 13 11 12.3083 11 11.4551V4.76062C11 3.05419 12.4091 1.6281 14.0527 2.0869Z");
}

</style>
