<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xyj-l9cjp"/><path class="md-e9sbfv"/><path class="ne5jxubfx"/><path class="a814_sbem"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sewing-machine-outline-regular" /></template>
<style>
.a814_sbem {
  d: path("M7 12v5");
}

.md-e9sbfv {
  d: path("M10 12h6q3 0 3 6");
}

.ne5jxubfx {
  d: path("M4 7h6v5H4Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xyj-l9cjp {
  d: path("M3 18h18");
}

</style>
