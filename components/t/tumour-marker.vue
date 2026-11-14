<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="olsgfqz6y"/><path class="pasxli_ph"/><path class="eiwx3vrwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tumour-marker" /></template>
<style>
.eiwx3vrwj {
  d: path("M16.75 14.5h4.75v7h-4.75l-2.5-3.5Zm.5 3.5h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.olsgfqz6y {
  d: path("M5 2.5v13C5 17.4 6.6 19 8.5 19s3.5-1.6 3.5-3.5v-13m-8.5 0h10");
}

.pasxli_ph {
  fill: currentColor;
  d: path("M5 11h7v4.5c0 1.9-1.6 3.5-3.5 3.5S5 17.4 5 15.5Z");
}

</style>
