<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="y60rjib_g"/><path class="fvc8noqew"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:run-distance-outline-bold" /></template>
<style>
.fvc8noqew {
  d: path("M16 3h4v4h-4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.y60rjib_g {
  d: path("m2 21 5 -5v-4l5 -5h4");
}

</style>
