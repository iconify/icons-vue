<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nkedcuv7p"/><path class="uk7z4vhel"/><path class="e48ledu_g"/><path class="k6sgsiwcv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:plate-broken" /></template>
<style>
.e48ledu_g {
  d: path("M8 10.5H16");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k6sgsiwcv {
  d: path("M8 14H13.5");
}

.nkedcuv7p {
  d: path("M22 12C22 15.7713 22 17.6569 20.8284 18.8285C19.6569 20 17.7712 20 14 20H10C6.22876 20 4.34315 20 3.17157 18.8285C2 17.6569 2 15.7713 2 12C2 8.22881 2 6.34319 3.17157 5.17162C4.23467 4.10853 5.8857 4.01009 9 4.00098M15 4.00098C18.1143 4.01009 19.7653 4.10853 20.8284 5.17162C21.4816 5.8248 21.7706 6.69994 21.8985 8.00006");
}

.uk7z4vhel {
  d: path("M12 5L12 3");
}

</style>
