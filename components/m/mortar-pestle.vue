<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvycqlzey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mortar-pestle" /></template>
<style>
.yvycqlzey {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.49 9.57l-.98-1.14q-.66-.75.14-1.34l4.83-3.58q.8-.59 1.46.17l.12.14q.66.76-.04 1.48l-4.17 4.3q-.7.72-1.36-.03M4.25 13.5h15.5a7.75 7.75 0 0 1-15.5 0");
}

</style>
