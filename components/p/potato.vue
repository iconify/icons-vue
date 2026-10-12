<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="kb4fnfi2i"/><path class="ayfravsaf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:potato" /></template>
<style>
.ayfravsaf {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.25 9.25h.01M15 10.5h.01m-4.26 5.25h.01");
}

.kb4fnfi2i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 6.5c2.5-2.5 6.75-3 10-1.25s4.25 5.25 3.5 8.5c-.75 3.5-3.5 6.25-7.5 7C9 21.5 5.5 20 4.25 17S4.5 8.5 6.5 6.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
