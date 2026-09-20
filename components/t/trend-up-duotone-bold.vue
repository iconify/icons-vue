<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fil6k9bew"/><path class="garjb9b3a"/><path class="q0ddccbcl"/><path class="kk-764bgz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:trend-up-duotone-bold" /></template>
<style>
.fil6k9bew {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 17 6 -6 4 4 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.garjb9b3a {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 7h4v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kk-764bgz {
  d: path("M17 7h4v4");
}

.q0ddccbcl {
  d: path("m3 17 6 -6 4 4 8 -8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
