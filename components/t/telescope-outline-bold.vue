<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bkhodo2vo"/><path class="a6o0g3bee"/><path class="ka41iob5n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:telescope-outline-bold" /></template>
<style>
.a6o0g3bee {
  d: path("m9 16 -4 4");
}

.bkhodo2vo {
  d: path("M5 14 15 4l4 4L9 18Z");
}

.ka41iob5n {
  d: path("m12 17 4 4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
