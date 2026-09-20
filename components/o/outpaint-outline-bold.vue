<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="b-fhdniix"/><path class="znv889pse"/><path class="x2nvzebcn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:outpaint-outline-bold" /></template>
<style>
.b-fhdniix {
  d: path("M2 9a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.x2nvzebcn {
  d: path("M17 7h4v10h-4");
}

.znv889pse {
  d: path("m5 14 2.5 -2.5L10 14");
}

</style>
