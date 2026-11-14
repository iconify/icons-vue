<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e68yliixb"/><path class="vo_v-9bwl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:terrarium-layers" /></template>
<style>
.e68yliixb {
  d: path("M4.5 3v15.5a3 3 0 0 0 3 3h9a3 3 0 0 0 3-3V3m-15 15.5h15m-15-3h15");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vo_v-9bwl {
  d: path("M12 15.5V10m0 1.5c0-2.5 1.75-4 4-4c0 2.5-1.75 4-4 4Zm0 1C12 10.25 10.25 9 8 9c0 2.25 1.75 3.5 4 3.5Z");
}

</style>
