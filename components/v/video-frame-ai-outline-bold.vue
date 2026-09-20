<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nzpsuduik"/><path class="z3c71dbbg"/><path class="ez39r6bms"/><path class="j11us-bgd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:video-frame-ai-outline-bold" /></template>
<style>
.ez39r6bms {
  d: path("M17 3v18");
}

.j11us-bgd {
  d: path("M10.5 9v6l3 -3Z");
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

.z3c71dbbg {
  d: path("M7 3v18");
}

</style>
