<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f3yex8bud"/><path class="ucimxmjrd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:org-welcome-sign" /></template>
<style>
.f3yex8bud {
  d: path("M6 3.5h12A3.5 3.5 0 0 1 21.5 7v4a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 11V7A3.5 3.5 0 0 1 6 3.5m.5 11v7m11-7v7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ucimxmjrd {
  d: path("M12 12.25c-1.5-1-3.25-2.25-3.25-4C8.75 7 9.75 6 11 6c.5 0 .75.25 1 .75c.25-.5.5-.75 1-.75c1.25 0 2.25 1 2.25 2.25c0 1.75-1.75 3-3.25 4");
}

</style>
