<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ptpudgb7w"/><path class="m7g9b7dcw"/><path class="v8fbd0blu"/><path class="rqxmixb7d"/><path class="mut__fbgb"/><path class="krno6ds-i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mcp-transport-duotone-bold" /></template>
<style>
.krno6ds-i {
  d: path("M13 15h3");
}

.m7g9b7dcw {
  fill: currentColor;
  d: path("M16 9a3 3 0 0 1 3 -3 3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3 3 3 0 0 1 -3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.mut__fbgb {
  d: path("M13 11h3");
}

.ptpudgb7w {
  fill: currentColor;
  d: path("M7.5 6H10a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V9l3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rqxmixb7d {
  d: path("M16 9a3 3 0 0 1 3 -3 3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3 3 3 0 0 1 -3 -3Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v8fbd0blu {
  d: path("M7.5 6H10a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V9l3 -3Z");
}

</style>
