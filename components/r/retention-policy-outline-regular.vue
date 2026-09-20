<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p-4xkccyb"/><path class="r_4qgk6hg"/><path class="kwc83kvle"/><path class="q6qz5_ren"/><path class="jnx-0bmel"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:retention-policy-outline-regular" /></template>
<style>
.jnx-0bmel {
  d: path("M19 17h2.5");
}

.kwc83kvle {
  d: path("M16 17a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
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

</style>
