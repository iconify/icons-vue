<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xiota8z6p"/><path class="x7aiqk4zc"/><path class="y0gt-cbtb"/><path class="qvwmt5y0l"/><path class="hm9g1fb2w"/><path class="jyebykb6y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:schedule-cron-duotone-regular" /></template>
<style>
.hm9g1fb2w {
  d: path("M19 11v3");
}

.jyebykb6y {
  d: path("M19 16v3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qvwmt5y0l {
  d: path("M19 5v4");
}

.x7aiqk4zc {
  d: path("M2 12a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
}

.xiota8z6p {
  fill: currentColor;
  d: path("M2 12a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.y0gt-cbtb {
  d: path("M9 8v4h3.5");
}

</style>
