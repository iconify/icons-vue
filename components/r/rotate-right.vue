<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g6wn4v-tc"/><path class="lvnpwkv_c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rotate-right" /></template>
<style>
.g6wn4v-tc {
  d: path("M3.5 20A13.5 13.5 0 0 1 17 6.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lvnpwkv_c {
  d: path("M13.5 3L17 6.5L13.5 10");
}

</style>
