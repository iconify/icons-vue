<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hma_3gb4g"/><path class="jf8si_b8r"/><path class="onmmgdbjv"/><path class="bos0j4biy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:writing-duotone-bold" /></template>
<style>
.bos0j4biy {
  d: path("M3 21h18");
}

.hma_3gb4g {
  fill: currentColor;
  d: path("M6 13 16 3l3 3L9 16Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jf8si_b8r {
  d: path("M6 13 16 3l3 3L9 16Z");
}

.onmmgdbjv {
  d: path("m6 13 -2 2v3h3l2 -2");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
