<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="s7zmekbut"/><path class="i0xb73b5u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:radio-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.i0xb73b5u {
  d: path("M104 168a8 8 0 0 1-8 8H64a8 8 0 0 1 0-16h32a8 8 0 0 1 8 8m-8-40H64a8 8 0 0 0 0 16h32a8 8 0 0 0 0-16m0-32H64a8 8 0 0 0 0 16h32a8 8 0 0 0 0-16m136-16v112a16 16 0 0 1-16 16H40a16 16 0 0 1-16-16V72a8 8 0 0 1 5.7-7.66l160-48a8 8 0 0 1 4.6 15.33L86.51 64H216a16 16 0 0 1 16 16m-16 112V80H40v112zm-16-56a40 40 0 1 1-40-40a40 40 0 0 1 40 40m-16 0a24 24 0 1 0-24 24a24 24 0 0 0 24-24");
}

.s7zmekbut {
  d: path("M216 72H32v120a8 8 0 0 0 8 8h176a8 8 0 0 0 8-8V80a8 8 0 0 0-8-8m-56 96a32 32 0 1 1 32-32a32 32 0 0 1-32 32");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
