<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zjs6ad-6z"/><path class="tdux9oy4s"/><path class="iwpbli9gm"/><path class="h57xi_b4m"/><path class="et81l2oxt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:multi-hop-outline-bold" /></template>
<style>
.et81l2oxt {
  d: path("M12 14a4 4 0 0 1 8 0");
}

.h57xi_b4m {
  d: path("M4 14a4 4 0 0 1 8 0");
}

.iwpbli9gm {
  d: path("M18 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tdux9oy4s {
  d: path("M10 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.zjs6ad-6z {
  d: path("M2 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
