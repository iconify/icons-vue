<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="g9aruybwn"/><path class="pg-wrtbze"/><path class="p14ag28op"/><path class="e8rvqbc4z"/><path class="yy262cc0h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:north-star-outline-bold" /></template>
<style>
.e8rvqbc4z {
  d: path("m4 20 3 -3");
}

.g9aruybwn {
  d: path("m12 7 5 5 -5 5 -5 -5Z");
}

.p14ag28op {
  d: path("m20 4 -3 3");
}

.pg-wrtbze {
  d: path("m4 4 3 3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.yy262cc0h {
  d: path("m20 20 -3 -3");
}

</style>
