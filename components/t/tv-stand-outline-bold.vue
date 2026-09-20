<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="olbeg_6gm"/><path class="m6nkjhiin"/><path class="dfugeobed"/><path class="vhf3_kexp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tv-stand-outline-bold" /></template>
<style>
.dfugeobed {
  d: path("M3 16h18v5H3Z");
}

.m6nkjhiin {
  d: path("M12 13v3");
}

.olbeg_6gm {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vhf3_kexp {
  d: path("M12 16v5");
}

</style>
