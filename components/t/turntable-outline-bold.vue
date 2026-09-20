<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="q6bd2y71t"/><path class="c33zbvbwu"/><path class="xlsprdnsf"/><path class="zni8d8bse"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:turntable-outline-bold" /></template>
<style>
.c33zbvbwu {
  d: path("M4 13a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

.q6bd2y71t {
  d: path("M3 5v16h18V5Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xlsprdnsf {
  d: path("M9 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.zni8d8bse {
  d: path("m18 8 -4 4");
}

</style>
