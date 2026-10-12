<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hg4ynlgip"/><path class="sq43u3dfb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:weather-satellite" /></template>
<style>
.hg4ynlgip {
  d: path("m13.02 4.84l4.22-1.54q.71-.26.97.45l.68 1.87q.26.71-.45.97l-4.23 1.53q-.7.26-.96-.44l-.68-1.88q-.26-.71.45-.96M4.56 7.91l4.23-1.53q.7-.26.96.44l.68 1.88q.26.71-.45.96L5.76 11.2q-.71.26-.97-.45l-.68-1.87q-.26-.71.45-.97");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sq43u3dfb {
  d: path("m9.8 5.21l1.69-.62q.56-.2.77.36l1.3 3.57q.2.57-.36.77l-1.69.62q-.56.2-.77-.36l-1.3-3.57q-.2-.57.36-.77m.69 15.99a2.5 2.5 0 0 1-.34-4.99a3.6 3.6 0 0 1 6.66-.86a2.82 2.82 0 0 1-.37 5.85Z");
}

</style>
