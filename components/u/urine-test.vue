<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="turoonb-d"/><path class="fu3hjdbge"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:urine-test" /></template>
<style>
.fu3hjdbge {
  d: path("M16.394 2.922za1.5 1.5 0 0 1 .897 1.923l-3.763 10.336a1.5 1.5 0 0 1-1.922.897a1.5 1.5 0 0 1-.897-1.923l3.763-10.336a1.5 1.5 0 0 1 1.922-.897");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.turoonb-d {
  d: path("m4.5 9.5l2 10.5c.15.9.9 1.5 1.75 1.5h7.5c.85 0 1.6-.6 1.75-1.5l2-10.5M6 14h1.9m9 0H18");
}

</style>
