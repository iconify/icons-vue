<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t6mhcpbse"/><path class="fgdt3w91s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sugaring" /></template>
<style>
.fgdt3w91s {
  d: path("M12.5 11.5s1.75 2.25 1.75 3.5a1.75 1.75 0 0 1-3.5 0c0-1.25 1.75-3.5 1.75-3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t6mhcpbse {
  d: path("M3.5 12H5v7a2.5 2.5 0 0 0 2.5 2.5h9A2.5 2.5 0 0 0 19 19v-7h1.5m-2.172-9.328za1.5 1.5 0 0 1 0 2.121l-3.535 3.535a1.5 1.5 0 0 1-2.121 0a1.5 1.5 0 0 1 0-2.121l3.535-3.535a1.5 1.5 0 0 1 2.121 0");
}

</style>
