<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pp0x4sctl"/><path class="yv74hxect"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-box-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pp0x4sctl {
  stroke-opacity: 0.4;
  d: path("m7.5 9.222l4.5 2.222l4.5-2.222M12 11.444V17");
}

.yv74hxect {
  d: path("M3 3h18v18H3Zm9 4l4.5 2.222v5.556L12 17l-4.5-2.222V9.222z");
}

</style>
