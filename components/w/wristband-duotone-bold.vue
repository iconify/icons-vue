<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kr2jj1hkc"/><path class="pp_u7qguw"/><path class="vcln6n2xe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wristband-duotone-bold" /></template>
<style>
.kr2jj1hkc {
  fill: currentColor;
  d: path("M10 3h4v5h-4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.pp_u7qguw {
  d: path("M14 6c4 1 7 3 7 6 0 4 -4 6 -9 6s-9 -2 -9 -6c0 -3 3 -5 7 -6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vcln6n2xe {
  d: path("M10 3h4v5h-4Z");
}

</style>
