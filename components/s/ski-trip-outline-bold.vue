<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wt9iv5biz"/><path class="olx65-bog"/><path class="exyd3ub4k"/><path class="oqfv9rb9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ski-trip-outline-bold" /></template>
<style>
.exyd3ub4k {
  d: path("m9 8 6 -6");
}

.olx65-bog {
  d: path("m6 8 6 -6");
}

.oqfv9rb9x {
  d: path("M2 21h20");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wt9iv5biz {
  d: path("m2 19 6 -6 3 3 5 -5 5 5");
}

</style>
