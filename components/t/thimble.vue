<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="k-l4m6bxw"/><path class="moal15bij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:thimble" /></template>
<style>
.k-l4m6bxw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 20.75c1-.5 1.5-1.5 1.5-2.75l.75-9.5a4.5 4.5 0 0 1 9 0l.75 9.5c0 1.25.5 2.25 1.5 2.75ZM7 17.25h10");
}

.moal15bij {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.75 8.75h.01M12 7.5h.01m2.24 1.25h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
