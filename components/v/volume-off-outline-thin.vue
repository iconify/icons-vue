<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jmjqszbgk"/><path class="ljir_j9fp"/><path class="ggag34r5e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:volume-off-outline-thin" /></template>
<style>
.ggag34r5e {
  d: path("m21 9 -5 5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jmjqszbgk {
  d: path("M8 9H3v6h5l5 5V4Z");
}

.ljir_j9fp {
  d: path("m16 9 5 5");
}

</style>
