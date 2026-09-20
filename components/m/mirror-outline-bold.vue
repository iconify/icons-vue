<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zawn-gbuw"/><path class="m7p35uguv"/><path class="qw7b_6b1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mirror-outline-bold" /></template>
<style>
.m7p35uguv {
  d: path("M12 17v3");
}

.qw7b_6b1t {
  d: path("M8 20h8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.zawn-gbuw {
  d: path("M6 10a6 7 0 1 1 12 0 6 7 0 1 1 -12 0");
}

</style>
