<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vnp2_kbnp"/><path class="wgkctvbsy"/><path class="v7yx62j9c"/><path class="zaji3hbsg"/><path class="yuybrcb9z"/><path class="wa8tqsbro"/><path class="y0x-x3b-m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:queue-priority-duotone-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v7yx62j9c {
  fill: currentColor;
  d: path("M17.5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.vnp2_kbnp {
  fill: currentColor;
  d: path("M5.5 8.5 9 12l-3.5 3.5L2 12Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wa8tqsbro {
  d: path("M17.5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.wgkctvbsy {
  fill: currentColor;
  d: path("M12 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.y0x-x3b-m {
  d: path("M2 18h19");
}

.yuybrcb9z {
  d: path("M12 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.zaji3hbsg {
  d: path("M5.5 8.5 9 12l-3.5 3.5L2 12Z");
}

</style>
