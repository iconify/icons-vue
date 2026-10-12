<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aablknbbn"/><path class="iz76s6b-z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:respawn" /></template>
<style>
.aablknbbn {
  d: path("M14.91 4.51a8.5 8.5 0 1 1-5.82 0m-.65 2.41l.65-2.41l-2.05-1.44");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iz76s6b-z {
  d: path("M12 16.5c-2-1.25-3.5-2.5-3.5-4.25a1.75 1.75 0 0 1 3.5-.6a1.75 1.75 0 0 1 3.5.6c0 1.75-1.5 3-3.5 4.25");
}

</style>
