<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g_3vz90co"/><path class="m7w5vhb4k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-takeoff-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g_3vz90co {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m17 8l-2 2l.884 5.303c.073.437-.07.883-.384 1.197a.61.61 0 0 1-.924-.066L12 13l-2 1v1.293c0 .453-.18.887-.5 1.207a.707.707 0 0 1-1 0l-3-3a.707.707 0 0 1 0-1c.32-.32.754-.5 1.207-.5H8l1-2l-3.434-2.576A.61.61 0 0 1 5.5 6.5c.314-.314.76-.457 1.197-.384L12 7l2-2c2-2 3-2 4-1s1 2-1 4");
}

.m7w5vhb4k {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m17 8l-2 2l.884 5.303c.073.437-.07.883-.384 1.197a.613.613 0 0 1-.924-.066L12 13l-2 1v1.293c0 .453-.18.887-.5 1.207a.707.707 0 0 1-1 0l-3-3a.707.707 0 0 1 0-1c.32-.32.754-.5 1.207-.5H8l1-2l-3.434-2.576A.613.613 0 0 1 5.5 6.5c.314-.314.76-.457 1.197-.384L12 7l2-2c2-2 3-2 4-1s1 2-1 4M3 21h18");
}

</style>
