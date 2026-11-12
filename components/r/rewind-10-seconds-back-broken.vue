<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tgcis5bxj"/><path class="gj9cr867l"/><path class="yvh9lfbdn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rewind-10-seconds-back-broken" /></template>
<style>
.gj9cr867l {
  d: path("M12.5 10.25V13.75C12.5 14.7165 13.2835 15.5 14.25 15.5C15.2165 15.5 16 14.7165 16 13.75V10.25C16 9.2835 15.2165 8.5 14.25 8.5C13.2835 8.5 12.5 9.2835 12.5 10.25Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tgcis5bxj {
  stroke-linejoin: round;
  d: path("M7.5 10.5L10 8.5V15.5");
}

.yvh9lfbdn {
  stroke-linejoin: round;
  d: path("M14 4.5L12 2C17.5228 2 22 6.47715 22 12C22 17.5228 17.5228 22 12 22C8.7288 22 5.82446 20.4293 4 18.001M8 2.83209C6.87754 3.32251 5.86251 4.01303 5 4.85857C3.14864 6.67349 2 9.20261 2 12C2 12.6849 2.06886 13.3538 2.20004 14");
}

</style>
