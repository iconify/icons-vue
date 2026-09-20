<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="n4jvs51cl"/><path class="buwnnz1fg"/><path class="zm2kbsbyq"/><path class="hhryeubon"/><path class="oi0elobpe"/><path class="wpfzotbdn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sparkline-duotone-bold" /></template>
<style>
.buwnnz1fg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 21h5v-5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hhryeubon {
  d: path("M3 8V3h5");
}

.n4jvs51cl {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 8V3h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oi0elobpe {
  d: path("M16 21h5v-5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wpfzotbdn {
  d: path("m5 16 4 -4 3 3 4 -4 3 3");
}

.zm2kbsbyq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m5 16 4 -4 3 3 4 -4 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
