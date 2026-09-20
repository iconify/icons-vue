<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="e9b6zqbrn"/><path class="m3rd84bde"/><path class="bnumaib7z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:security-check-duotone-bold" /></template>
<style>
.bnumaib7z {
  d: path("M9 13h6v6H9Z");
}

.e9b6zqbrn {
  fill: currentColor;
  d: path("M9 13h6v6H9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.m3rd84bde {
  d: path("M4 21V8l4 -4h8l4 4v13");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
