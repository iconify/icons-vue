<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s-jxs-0ml"/><path class="oita6zben"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:payment-donation" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oita6zben {
  d: path("m14.5 14.5l3.75-2c.85-.45 1.85-.1 2.25.75c.2.7-.15 1.45-.75 1.75l-5.5 3.75c-.75.5-1.65.75-2.5.75H2.5m13-10c-1.5-1-3-2-3-3.5c0-1.25.75-2 1.75-2c.5 0 1 .25 1.25.75c.25-.5.75-.75 1.25-.75c1 0 1.75.75 1.75 2c0 1.5-1.5 2.5-3 3.5");
}

.s-jxs-0ml {
  d: path("M2.5 13H6c1.5 0 2.5-.75 4-.75h3c.8 0 1.5.65 1.5 1.5s-.7 1.5-1.5 1.5h-2.5");
}

</style>
