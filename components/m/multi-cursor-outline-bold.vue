<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k6nj2fbya"/><path class="d223d_x9q"/><path class="l517yxbln"/><path class="uxy9sxbfx"/><path class="z5zbrh5-r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:multi-cursor-outline-bold" /></template>
<style>
.d223d_x9q {
  d: path("M3 12h6");
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.l517yxbln {
  d: path("M12 9v6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uxy9sxbfx {
  d: path("M3 19h10");
}

.z5zbrh5-r {
  d: path("M16 16v6");
}

</style>
