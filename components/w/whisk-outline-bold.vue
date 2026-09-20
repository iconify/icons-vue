<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="z_j864liq"/><path class="hx7cfzbbm"/><path class="l6rp-_-ny"/><path class="mww7ccc2b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:whisk-outline-bold" /></template>
<style>
.hx7cfzbbm {
  d: path("M6 21c0 -6 2 -12 6 -12s6 6 6 12");
}

.l6rp-_-ny {
  d: path("M10 21c0 -6 1 -12 2 -12");
}

.mww7ccc2b {
  d: path("M14 21c0 -6 -1 -12 -2 -12");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.z_j864liq {
  d: path("M12 2v7");
}

</style>
