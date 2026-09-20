<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nzpsuduik"/><path class="k-gn2j_0w"/><path class="fokb-mbsz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:nested-field-outline-bold" /></template>
<style>
.fokb-mbsz {
  d: path("M6 7h7");
}

.k-gn2j_0w {
  d: path("M8 12a2 2 0 0 1 2 -2h5a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-5a2 2 0 0 1 -2 -2Z");
}

.nzpsuduik {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
