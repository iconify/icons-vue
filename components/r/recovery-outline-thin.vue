<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l3qcduxbl"/><path class="lfe90yj9e"/><path class="d0oey7bgo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:recovery-outline-thin" /></template>
<style>
.d0oey7bgo {
  d: path("m14 11 3 -3 3 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l3qcduxbl {
  d: path("M3 13a3 3 0 0 1 6 0 3 3 0 0 1 6 0l-6 6Z");
}

.lfe90yj9e {
  d: path("M17 20V8");
}

</style>
