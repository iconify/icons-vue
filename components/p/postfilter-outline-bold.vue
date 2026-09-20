<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rqvtrb2by"/><path class="m68wh_s2h"/><path class="lgv20g91n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:postfilter-outline-bold" /></template>
<style>
.lgv20g91n {
  d: path("M3 11h18l-7 7v4h-4v-4Z");
}

.m68wh_s2h {
  d: path("m10.5 7 2 2");
}

.rqvtrb2by {
  d: path("M5.5 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
