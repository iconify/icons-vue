<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fp067408e"/><path class="g6eqxttle"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:yield-duotone-bold" /></template>
<style>
.fp067408e {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 21V3m0 4L7 2m5 5 5 -5m-5 9L7 6m5 5 5 -5m-5 9 -5 -5m5 5 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g6eqxttle {
  d: path("M12 21V3m0 4L7 2m5 5 5 -5m-5 9L7 6m5 5 5 -5m-5 9 -5 -5m5 5 5 -5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
