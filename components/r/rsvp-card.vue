<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ucxu3gbut"/><path class="tiq5dhbbu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rsvp-card" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tiq5dhbbu {
  d: path("M7 13.75h1.5a.75.75 0 0 1 .75.75V16a.75.75 0 0 1-.75.75H7a.75.75 0 0 1-.75-.75v-1.5a.75.75 0 0 1 .75-.75m5.75-4.25h5.5m-5.5 5.75h5.5M5.75 9.5l1.5 1.5l3-3.5");
}

.ucxu3gbut {
  width: 18.5px;
  height: 14.5px;
  x: 2.75px;
  y: 4.75px;
  rx: 2.5px;
}

</style>
