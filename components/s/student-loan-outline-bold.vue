<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jvc5rrr1z"/><path class="r1ix196dy"/><path class="wuk2mlziz"/><path class="jzi8j7bqk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:student-loan-outline-bold" /></template>
<style>
.jvc5rrr1z {
  d: path("M2 7a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.jzi8j7bqk {
  d: path("m10 16 -3 3 3 3");
}

.r1ix196dy {
  d: path("M9 10.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wuk2mlziz {
  d: path("M7 19h10");
}

</style>
