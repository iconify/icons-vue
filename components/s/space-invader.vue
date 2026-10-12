<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="gqplhgb3n"/><path class="h9qa0mbnm"/><path class="r_a-sdb5w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:space-invader" /></template>
<style>
.gqplhgb3n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.9 8.5h10.2q.4 0 .4.4v1.7q0 .4.4.4h2.7q.4 0 .4.4v6.7q0 .4-.4.4h-1.7q-.4 0-.4-.4v-1.7q0-.4-.4-.4h-2.7q-.4 0-.4.4v1.7q0 .4-.4.4H9.4q-.4 0-.4-.4v-1.7q0-.4-.4-.4H5.9q-.4 0-.4.4v1.7q0 .4-.4.4H3.4q-.4 0-.4-.4v-6.7q0-.4.4-.4h2.7q.4 0 .4-.4V8.9q0-.4.4-.4");
}

.h9qa0mbnm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 12.75h.01m4.99 0h.01");
}

.r_a-sdb5w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 6L6.5 3.5M16 6l1.5-2.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
