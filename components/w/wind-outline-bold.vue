<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="afxv9_b8a"/><path class="oq5d88tuy"/><path class="x199_yb0z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wind-outline-bold" /></template>
<style>
.afxv9_b8a {
  d: path("M3 7h12a3 3 0 1 0 -3 -3");
}

.oq5d88tuy {
  d: path("M3 12h15");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.x199_yb0z {
  d: path("M3 17h11a3 3 0 1 1 -3 3");
}

</style>
