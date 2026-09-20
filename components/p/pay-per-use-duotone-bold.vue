<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k628-abaf"/><path class="lh7nxd5dq"/><path class="ji-xh3b0v"/><path class="hd5x_f8cb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pay-per-use-duotone-bold" /></template>
<style>
.hd5x_f8cb {
  d: path("m21 7 -4 4h3l-4 4");
}

.ji-xh3b0v {
  d: path("M8 10.5v3");
}

.k628-abaf {
  fill: currentColor;
  d: path("M3 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.lh7nxd5dq {
  d: path("M3 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
