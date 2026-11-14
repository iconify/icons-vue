<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tkajosb9t"/><path class="ks6i0oj5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-cosmetics" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ks6i0oj5k {
  d: path("m12.237 8.702l1.061 1.061a1.5 1.5 0 0 1 0 2.121l-.353.353a1.5 1.5 0 0 1-2.122 0l-1.06-1.06a1.5 1.5 0 0 1 0-2.122l.353-.353a1.5 1.5 0 0 1 2.121 0m.531-1.591l1.271-1.271a1.5 1.5 0 0 1 1.196-.433l1.245.113a.915.915 0 0 1 .564 1.557l-2.155 2.155a1.5 1.5 0 0 1-2.121 0a1.5 1.5 0 0 1 0-2.121M19 22l-2.25-2.75a2.75 2.75 0 1 1 4.5 0Z");
}

.tkajosb9t {
  d: path("m9.409 10.823l1.768 1.768a1.75 1.75 0 0 1 0 2.475l-3.182 3.182a1.75 1.75 0 0 1-2.475 0L3.752 16.48a1.75 1.75 0 0 1 0-2.475l3.182-3.182a1.75 1.75 0 0 1 2.475 0");
}

</style>
