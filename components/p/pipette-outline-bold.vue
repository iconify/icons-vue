<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="aut-6nhkz"/><path class="ac5nw33zc"/><path class="pt-3kkb2k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pipette-outline-bold" /></template>
<style>
.ac5nw33zc {
  d: path("M9 6a3 3 0 0 1 6 0");
}

.aut-6nhkz {
  d: path("M9 6h6v9l-3 3 -3 -3Z");
}

.pt-3kkb2k {
  d: path("M9 11h6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
