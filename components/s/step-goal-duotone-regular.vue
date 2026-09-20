<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gtx4kfbor"/><path class="iqr3ry8kv"/><path class="o63zcjbok"/><path class="sryr5qb0a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:step-goal-duotone-regular" /></template>
<style>
.gtx4kfbor {
  fill: currentColor;
  d: path("M3 19v-4h5l4 -4h4l4 4v4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.iqr3ry8kv {
  d: path("M3 19v-4h5l4 -4h4l4 4v4Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o63zcjbok {
  d: path("M6 8V2");
}

.sryr5qb0a {
  d: path("M6 2h5v4H6");
}

</style>
