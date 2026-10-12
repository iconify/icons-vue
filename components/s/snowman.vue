<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="pgw_w4x5h"/><path class="dkw9b6vju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:snowman" /></template>
<style>
.dkw9b6vju {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 14.5h.01M12 18h.01");
}

.pgw_w4x5h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.52 9.94a3.75 3.75 0 1 1 2.96 0a5.75 5.75 0 1 1-2.96 0m2.23-3.44l4.5 1");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
