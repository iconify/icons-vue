<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hr-ubj4jo"/><path class="gcrnhlesv"/><path class="ltriwmbuu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mcp-tool-permission-duotone-thin" /></template>
<style>
.gcrnhlesv {
  d: path("M12 10h3a3 3 0 0 1 3 3v4a3 3 0 0 1 -3 3H9a3 3 0 0 1 -3 -3v-4l3 -3Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hr-ubj4jo {
  fill: currentColor;
  d: path("M12 10h3a3 3 0 0 1 3 3v4a3 3 0 0 1 -3 3H9a3 3 0 0 1 -3 -3v-4l3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ltriwmbuu {
  d: path("M8 10a4 4 0 0 1 8 0");
}

</style>
