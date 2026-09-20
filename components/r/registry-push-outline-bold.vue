<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="z-ephs7jm"/><path class="aho6qjb9y"/><path class="s229edbfl"/><path class="q3srlnbfr"/><path class="k2hm-7bsd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:registry-push-outline-bold" /></template>
<style>
.aho6qjb9y {
  d: path("M8 10v9");
}

.k2hm-7bsd {
  d: path("M9.5 4.5 12 7l2.5 -2.5");
}

.q3srlnbfr {
  d: path("M12 2v5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s229edbfl {
  d: path("M15 10v9");
}

.z-ephs7jm {
  d: path("M2 12a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
