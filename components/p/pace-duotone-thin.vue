<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gtx4kfbor"/><path class="iqr3ry8kv"/><path class="ym_yrom4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pace-duotone-thin" /></template>
<style>
.gtx4kfbor {
  fill: currentColor;
  d: path("M3 19v-4h5l4 -4h4l4 4v4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iqr3ry8kv {
  d: path("M3 19v-4h5l4 -4h4l4 4v4Z");
}

.ym_yrom4f {
  d: path("M13 2 9 6h3l-4 4");
}

</style>
