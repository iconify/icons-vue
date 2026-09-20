<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="q_5l_3bgt"/><path class="gzza8wbrt"/><path class="s6i5bu6gd"/><path class="sqsxh9blm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mtu-outline-bold" /></template>
<style>
.gzza8wbrt {
  d: path("M2 5v14");
}

.q_5l_3bgt {
  d: path("M5 10a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s6i5bu6gd {
  d: path("M22 5v14");
}

.sqsxh9blm {
  d: path("M5 5h14");
}

</style>
