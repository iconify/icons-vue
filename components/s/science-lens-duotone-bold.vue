<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="axr5pmbgx"/><path class="up7vunb7t"/><path class="r7xk8o29f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:science-lens-duotone-bold" /></template>
<style>
.axr5pmbgx {
  fill: currentColor;
  d: path("M4 12c4 -8 12 -8 16 0 -4 8 -12 8 -16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.r7xk8o29f {
  d: path("M12 4v16");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.up7vunb7t {
  d: path("M4 12c4 -8 12 -8 16 0 -4 8 -12 8 -16 0");
}

</style>
