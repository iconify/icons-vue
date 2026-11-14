<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="drnaghuwf"/><path class="l10e9gj6f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:smartwatch-health" /></template>
<style>
.drnaghuwf {
  d: path("M11.75 6h.5a5.25 5.25 0 0 1 5.25 5.25v1.5A5.25 5.25 0 0 1 12.25 18h-.5a5.25 5.25 0 0 1-5.25-5.25v-1.5A5.25 5.25 0 0 1 11.75 6M9 6l.75-3.5h4.5L15 6M9 18l.75 3.5h4.5L15 18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l10e9gj6f {
  d: path("M12 13.25S9.3 11.65 9.25 10c.05-.87.68-1.5 1.5-1.5c.5 0 .98.3 1.25.75c.27-.45.75-.75 1.25-.75c.82 0 1.45.63 1.5 1.5c-.05 1.65-2.75 3.25-2.75 3.25");
}

</style>
