<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oozxr3b4k"/><path class="sg1l_symq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:paintbrush" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oozxr3b4k {
  d: path("m13.061 9.561l1.378 1.378a1.5 1.5 0 0 1 0 2.122l-.378.378a1.5 1.5 0 0 1-2.122 0l-1.378-1.378a1.5 1.5 0 0 1 0-2.122l.378-.378a1.5 1.5 0 0 1 2.122 0");
}

.sg1l_symq {
  d: path("m9.5 11l3.5 3.5c-.5 4-5.5 6.5-10 6.5c0-4.5 2.5-9.5 6.5-10m4.25-.75L20.5 3.5");
}

</style>
