<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udf0r39lc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:snowy-tree" /></template>
<style>
.udf0r39lc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.179 4.001l3.703 4.713a.486.486 0 0 1-.382.786a.546.546 0 0 0-.459.841l2.473 3.848a1.5 1.5 0 0 1-1.261 2.311H6.747a1.5 1.5 0 0 1-1.261-2.311l2.473-3.848A.546.546 0 0 0 7.5 9.5a.486.486 0 0 1-.382-.786l3.703-4.713a1.5 1.5 0 0 1 2.358 0M12 16.5v3.75M5 21.5q7-2.5 14 0M5.5 4h.01M19 5.5h.01m-15.51 6h.01");
}

</style>
