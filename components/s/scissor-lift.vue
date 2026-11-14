<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c7bwxzbqo"/><path class="pq-2s6bwa"/><path class="b6r_qab5w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:scissor-lift" /></template>
<style>
.b6r_qab5w {
  d: path("M6.25 3.5h11.5A1.25 1.25 0 0 1 19 4.75A1.25 1.25 0 0 1 17.75 6H6.25A1.25 1.25 0 0 1 5 4.75A1.25 1.25 0 0 1 6.25 3.5");
}

.c7bwxzbqo {
  d: path("M7.5 17h9a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 6 18.5A1.5 1.5 0 0 1 7.5 17M7 17l7-6l-7-5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pq-2s6bwa {
  d: path("m14 17l-7-6l7-5.5");
}

</style>
