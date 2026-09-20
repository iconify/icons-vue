<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gqlg6gblx"/><path class="t3v74kb6y"/><path class="dezc-zb_n"/><path class="dvv2tacko"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sleep-track-duotone-bold" /></template>
<style>
.dezc-zb_n {
  d: path("M2 16.5h20");
}

.dvv2tacko {
  d: path("M13 4a4 4 0 1 0 0 8 3 3 0 0 1 0 -8");
}

.gqlg6gblx {
  fill: currentColor;
  d: path("M13 4a4 4 0 1 0 0 8 3 3 0 0 1 0 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t3v74kb6y {
  d: path("M2 20v-7h20v7");
}

</style>
