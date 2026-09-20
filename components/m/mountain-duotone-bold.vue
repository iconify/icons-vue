<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zt0rwniba"/><path class="d5b4fcc2f"/><path class="z5cj28bhd"/><path class="z9ittvbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mountain-duotone-bold" /></template>
<style>
.d5b4fcc2f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.z5cj28bhd {
  d: path("m2 16 6 -6 3 3 4 -4 7 7");
}

.z9ittvbis {
  d: path("M2 19h20");
}

.zt0rwniba {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m2 16 6 -6 3 3 4 -4 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
