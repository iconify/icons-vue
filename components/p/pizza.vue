<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="y6gmqzboq"/><path class="x1buefbkz"/><path class="t5fogdb9i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pizza" /></template>
<style>
.t5fogdb9i {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.75 12.25h.01m4.49-.5h.01M12 16h.01");
}

.x1buefbkz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 9.25C9.25 7 14.75 7 19 9.25");
}

.y6gmqzboq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 6.5c5.5-3.25 12-3.25 17.5 0L12.9 20.7a1 1 0 0 1-1.8 0Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
