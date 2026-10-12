<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="m7znrl3qk"/><path class="l-zbc4bvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sherwani" /></template>
<style>
.l-zbc4bvm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 8h.01M12 11.25h.01M12 14.5h.01M12 17.75h.01");
}

.m7znrl3qk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 2.75h5q.75 0 1.41.36l1.93 1.03q.66.36.74 1.11l1.09 9.5q.08.75-.67.82l-1 .11q-.75.07-.81-.68l-.38-4.75q-.06-.75 0 0l.88 10.25q.06.75-.69.75H7q-.75 0-.69-.75l.88-10.25q.06-.75 0 0L6.81 15q-.06.75-.81.68l-1-.11q-.75-.07-.67-.82l1.09-9.5q.08-.75.74-1.11l1.93-1.03q.66-.36 1.41-.36m-.25 2.5h5.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
