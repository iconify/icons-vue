<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ilm8u1bpr"/><path class="ezz8p8b2a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:view-orthographic" /></template>
<style>
.ezz8p8b2a {
  d: path("m3 7.5l9 4.5l9-4.5M12 12v9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ilm8u1bpr {
  d: path("m13.174 3.587l6.375 3.187A2.63 2.63 0 0 1 21 9.122v5.756a2.63 2.63 0 0 1-1.451 2.348l-6.375 3.187a2.63 2.63 0 0 1-2.348 0l-6.375-3.187A2.63 2.63 0 0 1 3 14.878V9.122a2.63 2.63 0 0 1 1.451-2.348l6.375-3.187a2.63 2.63 0 0 1 2.348 0");
}

</style>
