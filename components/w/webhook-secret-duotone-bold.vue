<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="uw3g4ocav"/><path class="todxii04r"/><path class="d5czi6rdr"/><path class="azs8m69dm"/><path class="opnv9et8e"/><path class="vnq8uj-tr"/><path class="djr1sx-jt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:webhook-secret-duotone-bold" /></template>
<style>
.azs8m69dm {
  d: path("m14 5 -2.5 2.5H14L11.5 10");
}

.d5czi6rdr {
  d: path("M3 4a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.djr1sx-jt {
  d: path("M12 17.5h2.5");
}

.opnv9et8e {
  d: path("M10 14.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.todxii04r {
  fill: currentColor;
  d: path("M10 14.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.uw3g4ocav {
  fill: currentColor;
  d: path("M3 4a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.vnq8uj-tr {
  d: path("M12 16.5V19");
}

</style>
