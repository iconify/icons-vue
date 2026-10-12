<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="xi7aw7bfp"/><path class="pjgexrs9j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:squirrel" /></template>
<style>
.pjgexrs9j {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.5 8.5h.01");
}

.xi7aw7bfp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 21.25c-2.75 0-5.25-3.25-5.25-7.75C2.75 7.5 5.5 3 9 3c2 0 3.25 1.25 3.25 3S11 8.5 9.75 8.5c-1.75 0-2.5 1.5-2.5 4c0 3 .25 6 .75 8.75m4.25 0c-1.25 0-2-1-1.6-2.2l1.6-4.8c.5-1.5.4-2.9-.1-4.1c-.4-1 0-2.1.85-2.65l1.5-.95l.5-2.3l1.6 1.55h.9A3.5 3.5 0 0 1 21 9.3c0 .97-.78 1.75-1.75 1.75h-1.5c.75 1.5 1.25 3.25 1.25 5c0 2.75-1.75 5.2-5.25 5.2Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
