<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="o-vpc-waj"/><path class="yq_iz_bvt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rug-outline-bold" /></template>
<style>
.o-vpc-waj {
  d: path("M3 12a9 4.5 0 1 1 18 0 9 4.5 0 1 1 -18 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.yq_iz_bvt {
  d: path("M6 12a6 3 0 1 1 12 0 6 3 0 1 1 -12 0");
}

</style>
