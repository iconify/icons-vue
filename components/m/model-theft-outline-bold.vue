<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="e-2lvb01c"/><path class="jaf3fnb5e"/><path class="j4csr4mvr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:model-theft-outline-bold" /></template>
<style>
.e-2lvb01c {
  d: path("M10.5 7H13a3 3 0 0 1 3 3v4a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3v-4l3 -3h2.5");
}

.j4csr4mvr {
  d: path("M19.5 9.5 22 12l-2.5 2.5");
}

.jaf3fnb5e {
  d: path("M17.5 12H20");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
