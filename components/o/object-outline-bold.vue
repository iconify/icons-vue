<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k6t-okb_f"/><path class="urk2115hi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:object-outline-bold" /></template>
<style>
.k6t-okb_f {
  d: path("M9 4 7 6v4l-2 2 2 2v4l2 2");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.urk2115hi {
  d: path("m15 4 2 2v4l2 2 -2 2v4l-2 2");
}

</style>
