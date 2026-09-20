<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="p3mf_9b3b"/><path class="z-xj_vb1j"/><path class="sy81gyprl"/><path class="ui5fkepez"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:smart-bulb-duotone-bold" /></template>
<style>
.p3mf_9b3b {
  fill: currentColor;
  d: path("M10 4c3.5 0 6 2.5 6 6 0 2.5 -2 4 -2 6H6c0 -2 -2 -3.5 -2 -6 0 -3.5 2.5 -6 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sy81gyprl {
  d: path("M7 19h6");
}

.ui5fkepez {
  d: path("M19 8c2 3 2 7 0 10");
}

.z-xj_vb1j {
  d: path("M10 4c3.5 0 6 2.5 6 6 0 2.5 -2 4 -2 6H6c0 -2 -2 -3.5 -2 -6 0 -3.5 2.5 -6 6 -6");
}

</style>
