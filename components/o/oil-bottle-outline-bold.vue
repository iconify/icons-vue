<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="cqen3ttkk"/><path class="u-a-7fbnu"/><path class="zm2dyvb-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:oil-bottle-outline-bold" /></template>
<style>
.cqen3ttkk {
  d: path("M8 21v-8c0 -2 2 -3 2 -4V6h4v3c0 1 2 2 2 4v8Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u-a-7fbnu {
  d: path("M10 6V3h4v3");
}

.zm2dyvb-o {
  d: path("M9 16h6");
}

</style>
