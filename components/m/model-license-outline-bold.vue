<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lxc0b_rlj"/><path class="ik8n3ab2d"/><path class="t4qf-ybkd"/><path class="odu-y8bfl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:model-license-outline-bold" /></template>
<style>
.ik8n3ab2d {
  d: path("m12 6.5 3.5 3.5 -3.5 3.5L8.5 10Z");
}

.lxc0b_rlj {
  d: path("M5 10a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
}

.odu-y8bfl {
  d: path("M14.5 17.5V21");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t4qf-ybkd {
  d: path("M9.5 17.5V21");
}

</style>
