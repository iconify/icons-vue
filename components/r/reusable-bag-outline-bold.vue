<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="t69363l7x"/><path class="v5slp2tuk"/><path class="vw-y0febs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:reusable-bag-outline-bold" /></template>
<style>
.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t69363l7x {
  d: path("M6 8v13h12V8Z");
}

.v5slp2tuk {
  d: path("M6 8a3 3 0 0 1 6 0");
}

.vw-y0febs {
  d: path("M12 8a3 3 0 0 1 6 0");
}

</style>
