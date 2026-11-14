<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ohe-w9b2h"/><path class="zldr22hcf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:marathon" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ohe-w9b2h {
  d: path("M12.75 3.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M12 7.5l-2.5 5L13 15l-1 4.5m-2.5-7L7 16H3.5");
}

.zldr22hcf {
  d: path("m7 11l4.5-2.5L15 11m1.5 10.5v-6.75m1.5 0h1.821a.654.654 0 0 1 .554 1l-.128.205a1.5 1.5 0 0 0 0 1.59l.128.205a.654.654 0 0 1-.554 1H18a1.5 1.5 0 0 1-1.5-1.5v-1a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
