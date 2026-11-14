<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ztlwh8j1u"/><path class="imvejnbow"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tag-dollar" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.imvejnbow {
  d: path("M6 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m11.5-1.75c0-.75-1-1.25-2.25-1.25S13 9.5 13 10.5s1 1.25 2.25 1.5s2.25.5 2.25 1.5s-1 1.5-2.25 1.5S13 14.5 13 13.75m2.25-6.25v9");
}

.ztlwh8j1u {
  d: path("m3.04 11.1l3.45-5.75a1.75 1.75 0 0 1 1.501-.85H19.75a1.75 1.75 0 0 1 1.75 1.75v11.5a1.75 1.75 0 0 1-1.75 1.75H7.991a1.75 1.75 0 0 1-1.501-.85L3.04 12.9a1.75 1.75 0 0 1 0-1.8");
}

</style>
