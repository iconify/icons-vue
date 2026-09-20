<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ha05_q27d"/><path class="w2b54lbpr"/><path class="xb-kv0a1i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tap-outline-bold" /></template>
<style>
.ha05_q27d {
  d: path("M5 4v6h11v3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.w2b54lbpr {
  d: path("M3 4h5");
}

.xb-kv0a1i {
  d: path("m16 15 2.5 2.5a3 3 0 1 1 -5 0Z");
}

</style>
