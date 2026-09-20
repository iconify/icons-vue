<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xqvgk9b0h"/><path class="ej39bnb_p"/><path class="g04xkmgbk"/><path class="qcu95-bhb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sleeper-duotone-thin" /></template>
<style>
.ej39bnb_p {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 4h4l-4 4h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g04xkmgbk {
  d: path("M12.54 7.56a6 6 0 1 1 -5.08 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qcu95-bhb {
  d: path("M15 4h4l-4 4h4");
}

.xqvgk9b0h {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12.54 7.56a6 6 0 1 1 -5.08 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
