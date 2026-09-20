<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qd2a5rnak"/><path class="sfb1ntbvv"/><path class="zwghjjvbs"/><path class="k5vsxkcxh"/><path class="vfk29flre"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:memory-search-outline-bold" /></template>
<style>
.k5vsxkcxh {
  d: path("M12 10a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.qd2a5rnak {
  d: path("M2 6h7");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sfb1ntbvv {
  d: path("M2 11h7");
}

.vfk29flre {
  d: path("m19 13 2.5 2.5");
}

.zwghjjvbs {
  d: path("M2 16h7");
}

</style>
