<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xphw2z6aa"/><path class="lstp_mb9e"/><path class="y_ji-fbff"/><path class="fr2dt5b5r"/><path class="gr8_-eb1k"/><path class="add57ftwa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tuning-broken" /></template>
<style>
.add57ftwa {
  d: path("M7 2V6");
}

.fr2dt5b5r {
  d: path("M17 11L17 6.00003M17 2.99996L17 1.99994");
}

.gr8_-eb1k {
  d: path("M17 22V18");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lstp_mb9e {
  d: path("M4 9.5C4 11.1569 5.34315 12.5 7 12.5C8.65685 12.5 10 11.1569 10 9.5C10 7.84315 8.65685 6.5 7 6.5C5.34315 6.5 4 7.84315 4 9.5Z");
}

.xphw2z6aa {
  d: path("M14 14.5C14 12.8431 15.3431 11.5 17 11.5C18.6569 11.5 20 12.8431 20 14.5C20 16.1569 18.6569 17.5 17 17.5C15.3431 17.5 14 16.1569 14 14.5Z");
}

.y_ji-fbff {
  d: path("M7.00001 12.9999L7 17.9999M7.00001 21L7.00001 22");
}

</style>
