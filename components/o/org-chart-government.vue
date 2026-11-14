<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twvcak_fn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:org-chart-government" /></template>
<style>
.twvcak_fn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 3h2.5A1.75 1.75 0 0 1 15 4.75v1.5A1.75 1.75 0 0 1 13.25 8h-2.5A1.75 1.75 0 0 1 9 6.25v-1.5A1.75 1.75 0 0 1 10.75 3m-6 12h2.5A1.75 1.75 0 0 1 9 16.75v1.5A1.75 1.75 0 0 1 7.25 20h-2.5A1.75 1.75 0 0 1 3 18.25v-1.5A1.75 1.75 0 0 1 4.75 15m12 0h2.5A1.75 1.75 0 0 1 21 16.75v1.5A1.75 1.75 0 0 1 19.25 20h-2.5A1.75 1.75 0 0 1 15 18.25v-1.5A1.75 1.75 0 0 1 16.75 15M12 8v3.5M6 15v-3.5h12V15");
}

</style>
