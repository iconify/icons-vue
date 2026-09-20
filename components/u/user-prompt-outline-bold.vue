<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="myekf3bzc"/><path class="cpvmwnddk"/><path class="vr5wd2g-l"/><path class="q1ha9bc_u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:user-prompt-outline-bold" /></template>
<style>
.cpvmwnddk {
  d: path("M2 19a5 5 0 0 1 10 0");
}

.myekf3bzc {
  d: path("M4 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.q1ha9bc_u {
  d: path("M13.5 17H22");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vr5wd2g-l {
  d: path("M13.5 11a3 3 0 0 1 3 -3H19a3 3 0 0 1 3 3 3 3 0 0 1 -3 3h-2.5a3 3 0 0 1 -3 -3");
}

</style>
