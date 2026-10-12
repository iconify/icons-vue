<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="p0q-dvq3e"/><path class="xd3bpi6ht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:seesaw" /></template>
<style>
.p0q-dvq3e {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 13l2.5 8.25h-5Zm-9 3l18-8");
}

.xd3bpi6ht {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3.4 13.1h.01M18.6 6.34h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
