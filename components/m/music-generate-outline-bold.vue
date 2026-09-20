<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jq9hovbrs"/><path class="yomctlb4k"/><path class="v4hdeje_n"/><path class="u8mhf344d"/><path class="ojw5_mmlr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:music-generate-outline-bold" /></template>
<style>
.jq9hovbrs {
  d: path("M14 4h5a3 3 0 0 1 3 3v7a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V7a3 3 0 0 1 3 -3h5");
}

.ojw5_mmlr {
  d: path("M12.5 6 15 8.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u8mhf344d {
  d: path("M12.5 6v6");
}

.v4hdeje_n {
  d: path("M8.5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.yomctlb4k {
  d: path("M7 17v4l4 -4");
}

</style>
