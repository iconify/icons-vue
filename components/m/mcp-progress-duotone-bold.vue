<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="boldsqbbb"/><path class="om2cs-bvl"/><path class="w_jkatblo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mcp-progress-duotone-bold" /></template>
<style>
.boldsqbbb {
  fill: currentColor;
  d: path("M13.5 7H19a3 3 0 0 1 3 3v4a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3v-4l3 -3h5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.om2cs-bvl {
  d: path("M13.5 7H19a3 3 0 0 1 3 3v4a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3v-4l3 -3h5.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.w_jkatblo {
  d: path("M12 7v10");
}

</style>
