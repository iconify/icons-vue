<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ye0axzb1w"/><path class="a35jxd7zw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-graduate" /></template>
<style>
.a35jxd7zw {
  d: path("M6 20.25h12a.75.75 0 0 0 .75-.75c0-2.2-3.04-3.75-6.75-3.75S5.25 17.3 5.25 19.5a.75.75 0 0 0 .75.75m6.56-17.28l7.63 3.06q.56.22 0 .44l-7.63 3.06q-.56.22-1.12 0L3.81 6.47q-.56-.22 0-.44l7.63-3.06q.56-.22 1.12 0m8.19 3.53v3.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ye0axzb1w {
  cx: 12px;
  cy: 10.25px;
  r: 3px;
}

</style>
