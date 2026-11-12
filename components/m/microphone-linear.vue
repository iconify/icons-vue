<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ih2r9krfu"/><path class="mkwvu5bez"/><path class="gweihee3d"/><path class="ujrmgmblc"/><path class="obcs1cbgf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:microphone-linear" /></template>
<style>
.gweihee3d {
  d: path("M13 11L17 11");
}

.ih2r9krfu {
  d: path("M12 16C9.23858 16 7 13.7614 7 11V8C7 5.23858 9.23858 3 12 3C14.7614 3 17 5.23858 17 8V11C17 13.7614 14.7614 16 12 16Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mkwvu5bez {
  d: path("M13 8L17 8");
}

.obcs1cbgf {
  d: path("M12 19V22");
}

.ujrmgmblc {
  d: path("M20 10V11C20 15.4183 16.4183 19 12 19C7.58172 19 4 15.4183 4 11V10");
}

</style>
