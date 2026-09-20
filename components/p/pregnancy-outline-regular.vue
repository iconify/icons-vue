<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xvse_9aut"/><path class="mmi5hvbvz"/><path class="p1-vmlgml"/><path class="udbqknruk"/><path class="k04qs_b8d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pregnancy-outline-regular" /></template>
<style>
.k04qs_b8d {
  d: path("m9 18 3 3");
}

.mmi5hvbvz {
  d: path("M9 8v10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p1-vmlgml {
  d: path("M9 10c6 0 8 2 8 5 0 2 -3 3 -8 3");
}

.udbqknruk {
  d: path("m9 18 -3 3");
}

.xvse_9aut {
  d: path("M6 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
