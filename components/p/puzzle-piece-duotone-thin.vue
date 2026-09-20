<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="htuj7h56e"/><path class="fm9ovcbvk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:puzzle-piece-duotone-thin" /></template>
<style>
.fm9ovcbvk {
  d: path("M4 4h6c0 -1.5 4 -1.5 4 0h6v6c1.5 0 1.5 4 0 4v6H4v-6c1.5 0 1.5 -4 0 -4Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.htuj7h56e {
  fill: currentColor;
  d: path("M4 4h6c0 -1.5 4 -1.5 4 0h6v6c1.5 0 1.5 4 0 4v6H4v-6c1.5 0 1.5 -4 0 -4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
