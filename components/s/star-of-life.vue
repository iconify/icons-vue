<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pcawiobxv"/><path class="gjmy25xrk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:star-of-life" /></template>
<style>
.gjmy25xrk {
  d: path("M12 6.5v11M9.75 15c0-1.75 4.5-1.25 4.5-3s-4.5-1.25-4.5-3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pcawiobxv {
  d: path("M9.75 3.25h4.5q.75 0 .75.75v2.05q0 .75.65.38l1.78-1.03q.65-.37 1.03.28l2.24 3.89q.38.65-.27 1.03l-1.78 1.02q-.65.38 0 .76l1.78 1.02q.65.38.27 1.03l-2.24 3.89q-.38.65-1.03.28l-1.78-1.03q-.65-.37-.65.38V20q0 .75-.75.75h-4.5Q9 20.75 9 20v-2.05q0-.75-.65-.38L6.57 18.6q-.65.37-1.03-.28L3.3 14.43q-.38-.65.27-1.03l1.78-1.02q.65-.38 0-.76L3.57 10.6q-.65-.38-.27-1.03l2.24-3.89q.38-.65 1.03-.28l1.78 1.03Q9 6.8 9 6.05V4q0-.75.75-.75");
}

</style>
