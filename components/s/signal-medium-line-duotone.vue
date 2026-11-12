<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a2aqw9y_p"/><path class="a3xe23f8n"/><path class="tbl0c_bwh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:signal-medium-line-duotone" /></template>
<style>
.a2aqw9y_p {
  d: path("M3 20H3.0001");
}

.a3xe23f8n {
  d: path("M7.5 20V16");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tbl0c_bwh {
  d: path("M12 20V12");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
