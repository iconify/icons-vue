<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hvf1rvi4c"/><path class="m3500wbus"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:page-speed-score" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hvf1rvi4c {
  d: path("M3.773 18.75a9.5 9.5 0 1 1 16.454 0");
}

.m3500wbus {
  d: path("m11.641 10.206l-1.46 2.246a.678.678 0 0 0 .569 1.048a1.037 1.037 0 0 1 1.02 1.229l-.145.771a.403.403 0 0 0 .734.294l1.46-2.246a.678.678 0 0 0-.569-1.048a1.037 1.037 0 0 1-1.02-1.229l.145-.771a.403.403 0 0 0-.734-.294");
}

</style>
