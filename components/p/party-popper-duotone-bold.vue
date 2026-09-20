<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lqmxk7bjh"/><path class="s_c1vbwpu"/><path class="rt0qgebuc"/><path class="rd9126b2a"/><path class="j1bx6i80n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:party-popper-duotone-bold" /></template>
<style>
.j1bx6i80n {
  d: path("m12 6 3 -3");
}

.lqmxk7bjh {
  fill: currentColor;
  d: path("m3 21 8 -8c2 2 3 5 2 8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rd9126b2a {
  d: path("m16 12 3 -3");
}

.rt0qgebuc {
  d: path("m14 9 3 -3");
}

.s_c1vbwpu {
  d: path("m3 21 8 -8c2 2 3 5 2 8Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
