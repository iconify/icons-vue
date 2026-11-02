<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ksuadbcpp"/><path class="jzt02jwik"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:save-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jzt02jwik {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3h14l4 4v14H3zm4 18v-7h10v7M9 7h6");
}

.ksuadbcpp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 2h14c.265 0 .52.105.707.293l4 4A1 1 0 0 1 22 7v14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1");
}

</style>
