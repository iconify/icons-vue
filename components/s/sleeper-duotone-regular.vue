<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b_li-tbgg"/><path class="hafotv34s"/><path class="g04xkmgbk"/><path class="qcu95-bhb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sleeper-duotone-regular" /></template>
<style>
.b_li-tbgg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12.54 7.56a6 6 0 1 1 -5.08 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g04xkmgbk {
  d: path("M12.54 7.56a6 6 0 1 1 -5.08 0");
}

.hafotv34s {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 4h4l-4 4h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qcu95-bhb {
  d: path("M15 4h4l-4 4h4");
}

</style>
