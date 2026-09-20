<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="f3mcq1ban"/><path class="pynu7yt3k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:surfing-outline-bold" /></template>
<style>
.f3mcq1ban {
  d: path("M12 3c3 3 4 8 3 12H9c-1 -4 0 -9 3 -12");
}

.pynu7yt3k {
  d: path("M3 19c3 -2 6 2 9 0s6 2 9 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
