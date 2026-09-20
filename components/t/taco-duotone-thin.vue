<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jnnn9_b6e"/><path class="zc40vp7yl"/><path class="c6yqvq36o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:taco-duotone-thin" /></template>
<style>
.c6yqvq36o {
  d: path("M5 11c2 -3 4 -1 7 -3s5 1 7 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jnnn9_b6e {
  fill: currentColor;
  d: path("M4 11c0 5 3 8 8 8s8 -3 8 -8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zc40vp7yl {
  d: path("M4 11c0 5 3 8 8 8s8 -3 8 -8Z");
}

</style>
