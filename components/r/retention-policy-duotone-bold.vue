<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wwqis5thb"/><path class="um0ajkigb"/><path class="p-4xkccyb"/><path class="r_4qgk6hg"/><path class="kwc83kvle"/><path class="q6qz5_ren"/><path class="jnx-0bmel"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:retention-policy-duotone-bold" /></template>
<style>
.jnx-0bmel {
  d: path("M19 17h2.5");
}

.kwc83kvle {
  d: path("M16 17a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.p-4xkccyb {
  d: path("M2 7a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.q6qz5_ren {
  d: path("M19 14.5V17");
}

.r_4qgk6hg {
  d: path("M4 9h10");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.um0ajkigb {
  fill: currentColor;
  d: path("M16 17a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wwqis5thb {
  fill: currentColor;
  d: path("M2 7a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
