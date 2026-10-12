<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="b427tmber"/><path class="d9gv9881c"/><path class="hqs9h_j5x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wire-cutter" /></template>
<style>
.b427tmber {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 11.5C8.75 8.75 9 5.25 12 2.75c3 2.5 3.25 6 2.25 8.75q-2.25 1.125-4.5 0M12 8V5.5");
}

.d9gv9881c {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 9.75h.01");
}

.hqs9h_j5x {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.6 11.75L9.4 14m4-2.25L14.6 14m-6.7.2l2.65 1.45l-2.95 5.5l-2.35-1.25Zm8.2 0l-2.65 1.45l2.95 5.5l2.35-1.25Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
